# Illustration of getStockTwits function

This short document displays the output of getStockTwits, a function that extracts the latest comments from StockTwits, a real-time social media platform for sharing of ideas between market participants .

# Load and run script


```r
# load libraries
library(tibble)
library(dplyr)
library(tidyr)
library(kableExtra)


# load function
source(file = "getStockTwits.R") 
```


```r
getStockTwits
```

```
## function (tickers, n) 
## {
##     na.omit.list <- function(y) {
##         return(y[!vapply(y, function(x) all(is.na(x)), logical(1))])
##     }
##     tmpFun <- function(ticker, n = 2) {
##         out <- purrr::map(ticker, .f = function(.x) {
##             tmp1 <- tryCatch(read_json(paste0("https://api.stocktwits.com/api/2/streams/symbol/", 
##                 .x, ".json?limit=30"), simplifyVector = T)$messages, 
##                 error = function(e) {
##                   (paste(.x, "not found"))
##                   NA
##                 })
##             return(tmp1)
##         })
##         if (n > 1) {
##             for (i in seq(2, n)) {
##                 out[i] <- purrr::map(ticker, .f = function(.x) {
##                   tryCatch(read_json(paste0("https://api.stocktwits.com/api/2/streams/symbol/", 
##                     .x, ".json?max=", purrr::pluck(out, i - 1) %>% 
##                       pull(id) %>% last()), simplifyVector = T)$messages, 
##                     error = function(e) {
##                       (paste(.x, "not found"))
##                       NA
##                     })
##                 })
##                 if (is.na(out[i])) 
##                   break
##             }
##             out <- na.omit.list(out)
##         }
##         return(out)
##     }
##     out1 <- furrr::future_map(tickers, .f = function(.x) {
##         tmpFun(.x, n = n)
##     }, .progress = TRUE, .options = furrr::furrr_options(seed = TRUE))
##     names(out1) <- tickers
##     out1 <- out1 %>% compact() %>% enframe() %>% mutate(value = furrr::future_map(.x = value, 
##         function(.x) {
##             tmp <- try(.x %>% bind_rows() %>% mutate(created_at = lubridate::as_datetime(created_at, 
##                 tz = "Asia/Singapore") %>% suppressMessages()) %>% 
##                 select(body, created_at) %>% rename(value = body, 
##                 time = created_at))
##             if (!inherits(tmp, "try-error")) 
##                 tmp
##         }, .progress = TRUE, .options = furrr::furrr_options(seed = TRUE))) %>% 
##         rename(comment = value)
##     return(out1)
## }
```


The argument n is the number of batches of 30 tweets to be extracted. Parallel processing is applied across the number of tickers, such that multiple tickers can be extracted simultaneously.


```r
# Enable parallel processing to extract stock comments simultaneously
future::plan('multisession')
out <- getStockTwits(c('SPY','QQQ','AAPL','TSLA'), n = 10)
future::plan('sequential')
```


# Display getStockTwits output

The output contains columns that contain the ticker, comments, and time of posting. This information can be utilized for sentiment analysis.

The function can be found at  [https://github.com/calebong/Web-Scraping/blob/main/getStockTwits.R](https://github.com/calebong/Web-Scraping/blob/main/getStockTwits.R).


```r
out
```

```
## # A tibble: 4 × 2
##   name  comment       
##   <chr> <list>        
## 1 SPY   <df [300 × 2]>
## 2 QQQ   <df [300 × 2]>
## 3 AAPL  <df [300 × 2]>
## 4 TSLA  <df [300 × 2]>
```



```r
out %>%
  unnest(cols = c(comment)) %>% 
  select(name, time, value) %>% 
  kable(format = "html", table.attr = "style='width:30%;'") %>% 
  kable_styling("striped", full_width = F, fixed_thead = T) %>%
  scroll_box(height = "900px", width = '100%')
```

<div style="border: 1px solid #ddd; padding: 0px; overflow-y: scroll; height:900px; overflow-x: scroll; width:100%; "><table style="width:30%; width: auto !important; margin-left: auto; margin-right: auto;" class="table table-striped">
 <thead>
  <tr>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> name </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> time </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> value </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:52:39 </td>
   <td style="text-align:left;"> $SPY  so I gave like 3 quality signals for this rally yesterday and then today, I lost 2 followers. Lol such is life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:51:11 </td>
   <td style="text-align:left;"> $SPY your doing good bears. No one got caught up on that spike. Hence not seeing porn spam of blown up accounts. They gonna bring it back down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:50:40 </td>
   <td style="text-align:left;"> $SPY 

If @realness365 

Doesn’t turn bull im going to beat him like a piñata 🪅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:50:26 </td>
   <td style="text-align:left;"> $SPY Wow, this is a must-see video... MRNA inventor claims that the OMICORN is unrelated to any of the COVID 19 from 2020; rather, he says that something is very strange about it; it is significantly mutated... He believes OMICORN was created in a laboratory.

https://rumble.com/vqjhq5-mrna-tech-inventor-speaks-out.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:50:09 </td>
   <td style="text-align:left;"> $SPY $AMZN why AMZN is going to lead the $QQQ in 2022 in 3 charts

1) monthly RSI(14) below 39 is where the big reversals happen on a relative basis AMZN/QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:50:01 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:49:55 </td>
   <td style="text-align:left;"> $SPY @Stocktwits please dont ban me it took me 3hrs to think of this cool name for the love of jesus christ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:49:25 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:49:10 </td>
   <td style="text-align:left;"> $SPY  cheap fucks want the dip now, coulda had $427 in October </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:55 </td>
   <td style="text-align:left;"> $SPY 

XLY/XLP at support $XLY $XLP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:53 </td>
   <td style="text-align:left;"> $SPY new name who dis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:51 </td>
   <td style="text-align:left;"> $SPY Tomorrow WS puts the final touches on its portfolios and prepares for future 5 % to 7% pullback.  Powell cannot let market drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:49 </td>
   <td style="text-align:left;"> $SPY 

Yo...

I dont mind biological male that identify as women to compete in dying women competition.

Only 1 condition.

They must chop off their balls and cock, and show proof. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:47 </td>
   <td style="text-align:left;"> $SPY my name isn’t moo

But I sure do enjoy 🍪 

😋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:23 </td>
   <td style="text-align:left;"> $SPY Santa rally is over! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:48:15 </td>
   <td style="text-align:left;"> $SPY bull rally 😆😆. Bears foooked up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:47:30 </td>
   <td style="text-align:left;"> $SPY get ready to go DOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:47:20 </td>
   <td style="text-align:left;"> $SPY 

$XLU and $XLP are about to get SMOKED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:47:10 </td>
   <td style="text-align:left;"> $SPY 

Wow they really went for max pain today. Too obvious with that high OI on 470 puts and calls hehe! 

——— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:46:52 </td>
   <td style="text-align:left;"> Honestly Nasdaq is gonna cruise past 50k faster then Dow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:46:37 </td>
   <td style="text-align:left;"> $SPY the fomc fomo is real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:46:35 </td>
   <td style="text-align:left;"> $SPY Mortimer, the technocrats and wobblies are at it again... really selling with the 1920s ambiance... what are they going to bring back the half day Saturday next? har har har </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:46:15 </td>
   <td style="text-align:left;"> $SPY Im feeling a lil rich this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:45:54 </td>
   <td style="text-align:left;"> $SPY So today was great. But is it sustainable is the question. There’s a huge gap down to fill now. Especially if we double top at ATH. Gonna need an ass of buying pressure at open or this was just a P&amp;amp;D Quad witching Friendly…fyi 

Swinging $460puts &amp;amp; $480 Calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:44:02 </td>
   <td style="text-align:left;"> $SPY the knowledge you’ll get from @OldFngGuy will earn you years worth of experience. A great teacher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:43:03 </td>
   <td style="text-align:left;"> $SPY It will be a long dark night, but gravity is extremely reliable. All puts here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:42:41 </td>
   <td style="text-align:left;"> $IWM $AMC $GME $SPY anyone use Webull? What do the large inflow orders signal? AMC is a big holder in the IWM sector, I’d like to believe we are about to see a lot of risk on movement really soon. Higher risk, higher reward growth stocks are finally about to catch a break and rally/bounce big? Let’s see… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:42:21 </td>
   <td style="text-align:left;"> $SPY you have a fifty fifty senate

The boss is Joe Manchin, not Joe Biden.

This backwoods Democrat runs the show

Go home sleepy Joe, Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:41:39 </td>
   <td style="text-align:left;"> $SPY can’t believe bearish traders are still here carpetbagging when they lost the EOY war… OMGoodness 🤦🏻‍♀️ maybe next year 🤷🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:41:34 </td>
   <td style="text-align:left;"> $SPY  last thing before i go to bed--- this non mkt--- BUILT ON A PACK OF LIES/ FRAUD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:41:21 </td>
   <td style="text-align:left;"> $SPY when inflation was this bad mortgage rates were 18% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:41:02 </td>
   <td style="text-align:left;"> $SPY JPow feeding you reassurance just like DJT feeding you China virus horseshit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:40:18 </td>
   <td style="text-align:left;"> $SPY 

Yo...

Don&amp;#39;t throw your snow baggy out when youre out of rocks - you&amp;#39;re throwing out the appetizer.

Lick your cig and absorb some dust... Cut the baggy and spread that shit on inner lip. Don&amp;#39;t lick it with tounge.

You&amp;#39;re welcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:39:59 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY 
Warming up now 🐱
https://www.investing.com/indices/indices-futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:38:44 </td>
   <td style="text-align:left;"> $SPY can we just talk about Joe Manchin? This guy is an absolute beast. Singlehandedly has all of Congress by the dads any time he wants. The human cliffhanger himself has more power than the president, although that term can be used very losely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:38:26 </td>
   <td style="text-align:left;"> $SPY When you bought Chinese “value” stocks… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:38:26 </td>
   <td style="text-align:left;"> $SPY Today we will start throwing a little less gas on the fire than usual. 7% infation and rates still 0%. Nothing wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:38:20 </td>
   <td style="text-align:left;"> This energy $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:38:08 </td>
   <td style="text-align:left;"> $SPY Waiting for the RSI purge on this froth pump! PUTS ready to print!! 📉💦🍏👀😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:37:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK My two cents on today. 
 
Markets hate uncertainty, as everyone knows.  Today Powell removed all uncertainty about direction, action, and timing.  Much of it was surmised, but now it&amp;#39;s known.  Known knowns are good, to borrow from Don Rumsfeld.  Unknown knowns are not good. 
 
The key exchange was with Steve Liesman, who asked, essentially, if the point is to end bond-buying, why keep doing it AT ALL over the next few months?  Tapering is, after all, still massive bond buying, just less. 
  
Powell replied, &amp;quot;We’ve learned that it’s best to take a careful and methodical approach. Markets can be sensitive to it. We’re basically two meetings away.”  
 
1/2 see reply for 2/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:37:02 </td>
   <td style="text-align:left;"> $SPY democrats are so desperate and delusional- they will credit Biden with everything, all while knowing the FED is independent and completely in control Washington DC. 🤦‍♂️ you’re not influencing mid terms - I’ll enjoy all the spoils but democrats will not control my life ! For any amount of fake money 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:36:42 </td>
   <td style="text-align:left;"> $SPY $BTC.X $AMC $GME $HOOD 

Reddit files to go public

https://www.cnbc.com/2021/12/15/reddit-files-to-go-public-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:36:36 </td>
   <td style="text-align:left;"> $SPY Hey Jeerrrooommeee!!! it&amp;#39;s Just Transitory... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:36:32 </td>
   <td style="text-align:left;"> $SPY why is it stonks only go up and bears have been getting it up the ass for last couple years? I really hope the bears lube up every morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:35:48 </td>
   <td style="text-align:left;"> $SPY $ARKK Senator Manchin is better than Powell ever was for the markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:35:25 </td>
   <td style="text-align:left;"> $SPY Bigly uply everly daily

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:35:23 </td>
   <td style="text-align:left;"> $SPY remember, it will take 2 years for fed rates to get to 2019 levels... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:35:00 </td>
   <td style="text-align:left;"> $SPY  i lost 195k (LONG) in the 1999-2000 mkt collaspe    MY-   clients lost over 2MM --- I believed --- i dont believe this idiot sht </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:34:55 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:34:47 </td>
   <td style="text-align:left;"> $SPY Reddit filed for IPO its symbol is $RTRD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:33:26 </td>
   <td style="text-align:left;"> $SPY come on VIX drop like it’s hot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:33:10 </td>
   <td style="text-align:left;"> $SPY i like how every asset across the entire financial systems all had the same short squeeze. There is no escaping the control right now, must be very fragile moment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:32:05 </td>
   <td style="text-align:left;"> $SPY  $IWM As usual people are flooding into blue chips since interest rates are still set at 0.25%  
 
Its nice to see some small caps have little pops today. I think it will be safe to trade THE BEST ones now since the FED has pretty much admitted that they will be doing something about inflation (3 rate hikes). So the market knows that their will STILL be more inflation but it will eventually be under control when they raise rates in a few months.  
 
However, be very selective of what penny stocks you trade, so far I gave you 3 that I like alot (look at my earlier tweet today). Lets see how it goes tomorrow. If you want to play it safe at this time its better to trade blue chips since the actual inflation is still going to F*** the economy up bad until the fed does its FIRST rate hike which will be alllll the way till JUNE of 2022 which is absolutely nuts to me.  
 
That means some penny stocks will still bleed due to high inflationary fears until that first rate hike... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:32:00 </td>
   <td style="text-align:left;"> $SPY  said mit before---- I was on a trading floor -- personalyy/ professionally making trades/ executions  19 OCTOBER 1987--- minus   22% one day  djia        ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:31:49 </td>
   <td style="text-align:left;"> $SPY Futes are confused?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:31:08 </td>
   <td style="text-align:left;"> $DOCU $SPY SANTA RALLY IS ON!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:30:53 </td>
   <td style="text-align:left;"> $SPY Kinda ironic how Bears are complaining about all the new money going into circulation…yet can’t seem to get any…😆👏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:30:39 </td>
   <td style="text-align:left;"> Market Volume Barometer 12-15-2021
Sentiment: PANICKY
Volume: 9%
Real Feel: CHILLY
Cycle: BEARISH II
Portfolio: CASH
Next Day Move: SIDEWAYS
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:30:04 </td>
   <td style="text-align:left;"> $SPY I just figured it out! The Brandon thing! It’s Russian bots! It has to be. They think we think it’s funny or hurtful. But it not. It’s a bad joke translated from some other language. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:29:59 </td>
   <td style="text-align:left;"> $SPY bears in shambles 🤣🤣🤣🚀🚀🚀 $480 here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:29:26 </td>
   <td style="text-align:left;"> $SPY when you think NFT think of each collection as a clothing brand. You have designer at the top and then etc etc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:28:56 </td>
   <td style="text-align:left;"> $SPY Build Back Better?? More like... Make Inflation Higher Than Jimmy Carter... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:28:54 </td>
   <td style="text-align:left;"> The best way to trade $SPY is by using the @mrinvestorpro strategy. Whenever and wherever he shows up, do the opposite of what he says and you win 9.5/10 times 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:28:26 </td>
   <td style="text-align:left;"> $SPY theres so much new money 💰 in circulation no matter how bad the melt down it won’t fall as far as you think 🤔! Because there are those that will capitalize off every dip ! When they create 40% of total currency  in the last 2 years the market can’t fail ! YES NOT TOO BIG TO FAIL BUT RATHER  TOO 💰MUCH FAIL ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:28:15 </td>
   <td style="text-align:left;"> $IWM small cap futures rippin!! My calls hopefully look gorgeous in the mornin. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:28:12 </td>
   <td style="text-align:left;"> $UVXY anyone notice that after all the drama, all the VIX spikes.

This is still down over 50% in 6 months.

$SPY $QQQ Did I ever tell you what the easiest trade in the world is ?????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:28:00 </td>
   <td style="text-align:left;"> Looking ahead to Thursday: Investors will receive weekly Initial and Continuing Claims, Housing Starts and Building Permits for November, Industrial Production and Capacity Utilization for November, the Philly Fed Index for December, and the preliminary IHS Markit Manufacturing and Services PMIs for December.

S&amp;amp;P 500 +25.4% YTD
NAS Comp +20.8% YTD
DJIA +17.4% YTD
Russell 2000 +11.2% YTD

$SPY $QQQ $DIA $RUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:27:18 </td>
   <td style="text-align:left;"> $SPY ah yes the good ole boring days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:27:03 </td>
   <td style="text-align:left;"> FOMC just Finished, What&amp;#39;s next? December 16th trade ideas(RE-UPLOADED) https://youtu.be/J_v7HEIcRvA 

$IWM $SPY $QQQ $HOLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:27:01 </td>
   <td style="text-align:left;"> $SPY  margin debt is beyound any recorded # === that in and of itself is the dibacle/catalyst to have 2008 redux </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:26:01 </td>
   <td style="text-align:left;"> $QQQ $SPY gonna dump as reality sets in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:25:53 </td>
   <td style="text-align:left;"> $SPY  475 by EOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:25:47 </td>
   <td style="text-align:left;"> $SPY how long will rates stay unchanged? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:25:45 </td>
   <td style="text-align:left;"> $SPY Perhaps I will start a course for bears on stonks and dating tips 

Although tbh they are hopeless when it comes to both

But yeah very low price of $999/mo, 2 yr min commitment

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:25:11 </td>
   <td style="text-align:left;"> $SPY Why would you post something called a three shot method that makes it sound like a stock will drop 3 times after your alert? Why not wait until it drops 3 times. Sounds like a method to short against. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:24:34 </td>
   <td style="text-align:left;"> $SPY  1/2 of a black crow/swan/ atomic device  away from spy 200 and below </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:24:29 </td>
   <td style="text-align:left;"> $SPY Breaking news: omicron 2.0 is coming out sometime in the near future.  You know what means right? $550 EOW. Final answer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:23:50 </td>
   <td style="text-align:left;"> $CSCO is Webex down? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:23:03 </td>
   <td style="text-align:left;"> $SPY wanna hear a story? Imagine a blowoff top drop to $430…. Just think about it. That would def help out the cause of the great reset. Can yo honestly not see the manipulation of everything!??!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:22:27 </td>
   <td style="text-align:left;"> $SPY I’ll take it 👍🏼, holding still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:22:22 </td>
   <td style="text-align:left;"> $SPY  worst rigging of a non mkt in the history of histiory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:22:06 </td>
   <td style="text-align:left;"> $SPY 

5 fat lines - 3 right nostril, 2 left. 5 shots of your favorite liq. Fat blunt with opium balls. Half a pack of cigs. Wash it down with a beer. Chew gum... and...

Midget porn on pornhub. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:21:56 </td>
   <td style="text-align:left;"> $SPY thank you Brandon. your the reason we now are at ATH,S. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:21:55 </td>
   <td style="text-align:left;"> $QQQ  $SPY  Powell will build the biggest bubble in the history of bubbles.   
 
it’s not popping yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:21:32 </td>
   <td style="text-align:left;"> $SPY Oh well I asked her out

Worst case scenario I play it as a smooch and scooch situation if you catch my drift

Also if she is a bear, it&amp;#39;s over

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:21:28 </td>
   <td style="text-align:left;"> $SPY push to 800 and let apes hold the bag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:21:23 </td>
   <td style="text-align:left;"> $SPY how are the bears sleeping tonight? 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:20:39 </td>
   <td style="text-align:left;"> $SPY $480 on Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:20:33 </td>
   <td style="text-align:left;"> $SPY bears smack talkin all week then </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:20:22 </td>
   <td style="text-align:left;"> $SPY  VIX    257 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:20:21 </td>
   <td style="text-align:left;"> $SPY Fck Joe Biden!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:20:16 </td>
   <td style="text-align:left;"> $SPY Option Order Flow Sentiment is 50.7% Bullish. https://tinyurl.com/y8x6hafb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:20:10 </td>
   <td style="text-align:left;"> $SPY rough day at the office for Da Bears… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:19:41 </td>
   <td style="text-align:left;"> $SPY algo 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:19:27 </td>
   <td style="text-align:left;"> $SPY lock limit downs--- multiples coming to a non mkt neeeer YOU! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:19:02 </td>
   <td style="text-align:left;"> $SPY Pay more attention to peoples actions and less attention to what others say it’s time to only give your energy to others when their actions meet the same frequencies as yours talk is cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:18:49 </td>
   <td style="text-align:left;"> $SPY where can I buy virtual land </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:18:25 </td>
   <td style="text-align:left;"> $SPY  has a date with 424 then 400 then  waaaaaay under all that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:18:22 </td>
   <td style="text-align:left;"> $SPY still needs a 471- and 472 daily candle none yet which means more up side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:18:13 </td>
   <td style="text-align:left;"> $SPY futures are ripping very high. Tomorrow we are seeing ATH 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:17:57 </td>
   <td style="text-align:left;"> $SPY no reason this will not go to 500 within two weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:17:35 </td>
   <td style="text-align:left;"> $SPY print me 460 by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:17:22 </td>
   <td style="text-align:left;"> $SPY over bought.  So it should run up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:17:22 </td>
   <td style="text-align:left;"> $SPY It not over, they&amp;#39;re trying to liquidate long/short positions from both sides. Side ways price action can&amp;#39;t be good for instruments that are designed to only go up right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:17:00 </td>
   <td style="text-align:left;"> $SPY Dr Michael Burry- bearish all indexes-- i do believe        ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:16:17 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $DIA  News 

https://apple.news/AVcvSQDsTS7OSzaOTBomEoA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:16:00 </td>
   <td style="text-align:left;"> $SPY  i am bearish all indexes until i say no---- and that is hndreds of points below this--- keep on dreeeeeming        ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:15:35 </td>
   <td style="text-align:left;"> $TSLA this is how dumb you idiots really are !  Elon isn’t CCP , he’s American as apple pie 🥧- lol 😂 he’s not ! And will sell you and anybody out including share holders if that keeps his stupid space x funded ! He may be rich AF ! But hes still answering to somebody !  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:15:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM is this American???
https://rumble.com/vqv2q2-new-yorkers-now-being-arrested-for-failing-to-show-proof-of-vaccination.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:15:09 </td>
   <td style="text-align:left;"> $SPY $SPX the dread and FUD this generates is bearish in it of itself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:14:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL triple witch friday. The fun isn’t over yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:14:38 </td>
   <td style="text-align:left;"> $SPY So many trapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:13:31 </td>
   <td style="text-align:left;"> $SPY the American government is now so insecure that it won’t allow another country to rise up to power or technological advancement. Pathetic. All in the name of “national security”. No, it’s called national insecurity. Grow up. $QQQ $BABA $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:13:29 </td>
   <td style="text-align:left;"> $SPY kicking myself for missing so much money today... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:13:18 </td>
   <td style="text-align:left;"> $SPY can hate on Cramer all you want but he did say to buy on December 15th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:12:58 </td>
   <td style="text-align:left;"> $SPY I think it&amp;#39;s important that you young bears lose a lot of money at this stage in your life.. you need to get back into the workforce and start your career.. you play stocks on the side as Investments .. stop gambling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:12:56 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:12:47 </td>
   <td style="text-align:left;"> $SPY infinite money glitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:12:20 </td>
   <td style="text-align:left;"> $SPY 16666 nq futures   very SOON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:12:02 </td>
   <td style="text-align:left;"> $SPY I missed the interview... did anyone ask how the Fed was going to release the 9 Trillion upon this earth, all the while Evergrand has defaulted? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:11:30 </td>
   <td style="text-align:left;"> $QQQ ahahaha bears are still in denial. Lol. $AAPL $SPY $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:10:36 </td>
   <td style="text-align:left;"> This message $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:10:36 </td>
   <td style="text-align:left;"> $SPY this game sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:10:26 </td>
   <td style="text-align:left;"> $SPY free </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:09:17 </td>
   <td style="text-align:left;"> $SPY what a fucking day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:08:30 </td>
   <td style="text-align:left;"> $SPY theta gang tomorrow. Collecting easy $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:08:26 </td>
   <td style="text-align:left;"> $SPY tomorrow pooots will burn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:08:25 </td>
   <td style="text-align:left;"> $SPY $QQQ taper and rate raise was expected so markets move higher despite it being bad news. &amp;quot;Santa rally&amp;quot; expected but markets expected to move higher lol. &amp;quot;Bulls&amp;quot; make no sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:08:18 </td>
   <td style="text-align:left;"> $SPY We live in a world where nobody has to ever work again.  All you need to do is overleverage your useless dollars into this fed induced bubble and become millionaires while watching netflix.  Is this what the great humanity has become?   Greater fool theory.   $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:08:13 </td>
   <td style="text-align:left;"> With TradesViz you can analyze all your options greeks and find the most optimal options strategy.

TradeViz leaves no data when it comes to trading performance analysis. 

Why? Your edge could be hiding in any single chart.

$SPY $$AAPL $QQQ $TSLA $STUDY

Free 👉 http://tradesviz.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:08:08 </td>
   <td style="text-align:left;"> $SPY  careful that was bullish engulfing. Don’t get your account engulfed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:07:08 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:07:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL   what do you all see ? This is NASDAQ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:06:22 </td>
   <td style="text-align:left;"> $SPY could be wrong but I think we’ll see a slight continuation of this relief rally followed by another major drop. The hawkish FED news was by no means a positive catalyst and we have to return to reality at some point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:06:22 </td>
   <td style="text-align:left;"> $SPY  this was disturbing to watch.  I honestly can&amp;#39;t understand how teachers even agreed to this.  Squid Game. :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:05:57 </td>
   <td style="text-align:left;"> $SPY I just dropped this video and for all my swing traders out there or for any of my followers who are new to swing trading, nervous about swing trading, etc this video is for you. I go over four low risk, high reward setups that I’m watching with my team. I give price targets to the upside, chart breakdown for each ticker, etc. The four tickers I go over are: $XOM $RIOT $IWM $V 

https://www.youtube.com/watch?v=HVUml3Kito0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:05:40 </td>
   <td style="text-align:left;"> $SPY cup n handle breakout. Christmas rally around the corner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:05:04 </td>
   <td style="text-align:left;"> $SPY oooooh baby baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:05:03 </td>
   <td style="text-align:left;"> FOMC just Finished, What&amp;#39;s next? December 16th trade ideas
https://youtu.be/XEueoalQwzI

$HOLX $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:04:47 </td>
   <td style="text-align:left;"> $SPY FORGET FUTURES NEW SOUTH PARK TONIGHT 🤙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:04:09 </td>
   <td style="text-align:left;"> $SPY 

Anybody else see that NIO day is this Saturday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:03:56 </td>
   <td style="text-align:left;"> Investors eye major Fed policy meeting  $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/investors-eye-major-fed-policy-meeting/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:03:37 </td>
   <td style="text-align:left;"> $SPY 2 Similar pitchfork breakout patterns. Expecting some consolidation/pullback for dips &amp;amp; continuation upward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:03:26 </td>
   <td style="text-align:left;"> $SPY One of those great 10 pt face ripper days. Hope you got some. Both sides. 

Wry smiles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:02:31 </td>
   <td style="text-align:left;"> $SPY say what you want but sentiment has changed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:02:10 </td>
   <td style="text-align:left;"> $SPY Did JPOW just say the dollar is a con today? trying to wrap my head around this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:01:58 </td>
   <td style="text-align:left;"> $DIA $SPY $AAPL $AMZN 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:01:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:01:27 </td>
   <td style="text-align:left;"> Nooo but $NVDA PE is too high. Its overpriced at a 700B  . lets ignore tesls... Merry Christmas Bears $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:00:57 </td>
   <td style="text-align:left;"> $SPY strap up cause where we’re going…..we don’t need trend lines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:00:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:00:45 </td>
   <td style="text-align:left;"> $SPY let me ask you something- do you really want to rely on iOT to do everything for you ???? 🤷‍♂️  

Am I the only guy that does everything manually and laughs at people who do everything from their phone ? This is how they Emasculate the male population , you do it because it’s easier not smarter - let me guess your father never came back with milk like he promised 😂 $TSLA  YOUR KIDS WILL BE JUST AS FUCKED UP ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:00:26 </td>
   <td style="text-align:left;"> $SPY wockhardt all in my kidneys 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 11:00:09 </td>
   <td style="text-align:left;"> The Fed Expects 6 Rate Hikes By End Of 2023 - I Don&amp;#39;t And You Shouldn&amp;#39;t Either https://talkmarkets.com/content/economics--politics/the-fed-expects-6-rate-hikes-by-end-of-2023-i-dont-and-you-shouldnt-either?post=337985 #fed $TLT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:59:57 </td>
   <td style="text-align:left;"> $SPY well then which one works haha

https://www.npr.org/sections/health-shots/2021/12/15/1064202754/omicron-evades-moderna-vaccine-too-study-suggests-but-boosters-help </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:59:35 </td>
   <td style="text-align:left;"> $SPY think we need to clear out premium at max pain tm
Gl bulls but i think we r red tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:59:20 </td>
   <td style="text-align:left;"> $SPY So I am 50/50 on whether I actually find this girl attractive but she is definitely pretty cool

Do I first date or nah ?

🤔🤔📈🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:59:09 </td>
   <td style="text-align:left;"> $SPY safe to say santa is in town! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:58:43 </td>
   <td style="text-align:left;"> $SPY The only people on here that grind my gears are the perma-bitches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:58:40 </td>
   <td style="text-align:left;"> $SPY I want to say that’s a reverse head and shoulders and the rising volume should make it break out this level it’s been  testing since November 5th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:56:49 </td>
   <td style="text-align:left;"> $SPY Upcoming catalysts. New variant. Russian invasion of Ukraine. The market is in total kangaroo mode and that came from fed’s mouth. Don’t trust it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:56:20 </td>
   <td style="text-align:left;"> $SPY Russia says it is willing to endure &amp;quot;difficulty&amp;quot; and &amp;quot;economic cost&amp;quot; to prevent Ukraine from joining NATO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:55:36 </td>
   <td style="text-align:left;"> $SPY the fact that i win way more on sports bets than the stock market shows u how fucking fucked this market is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:55:35 </td>
   <td style="text-align:left;"> $SPY pretty interesting how $VRTX chart resembles 2000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:54:37 </td>
   <td style="text-align:left;"> Glad I cash advanced to buy those call options yesterday. Going to be a good weekend at the craps table. $SPY $AAPL $NVDA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:53:59 </td>
   <td style="text-align:left;"> $SPY  you ment to say 12 year gravey train </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:53:35 </td>
   <td style="text-align:left;"> $SPY They need help and they had dreams, but don&amp;#39;t nobody give a shit
Yeah, just like them boys in cells who had dreams of NFL
How they supposed to pray to God if they keep waking up in hell?
Been there so long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:52:33 </td>
   <td style="text-align:left;"> $SPY When Robinhood’s collection agency is banging on your thin ass wooden door </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:52:32 </td>
   <td style="text-align:left;"> $SPY 470 is to spy as the hot chick in your high school you always had a thing for growing up and once you take that down after 7 8 9 tries then you move onto bigger better things. I think the mood is finally right and the lights are dim, Barry white is playing on the radio and tonight it&amp;#39;s finally time for that brown chicken brown cow (bow chicka chika bow bow for you kiddies) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:52:02 </td>
   <td style="text-align:left;"> $SPY Major Gains Coming in The Years Ahead! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:51:46 </td>
   <td style="text-align:left;"> $SPY I was right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:51:26 </td>
   <td style="text-align:left;"> $SPY keep yoloing calls bulls just don’t be greedy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:51:15 </td>
   <td style="text-align:left;"> $SPY probably pump til 9.44am and dumpster town to like 463 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:50:47 </td>
   <td style="text-align:left;"> $SPY  

Its that time of year .... here is my Fantasy Football team as I roll into first round playoffs  .... 

QB - Josh Allen

RB - Najee Harris

RB - Cordarelle Patterson

WR - Tyreek Hill

WR - Amari Cooper

TE - Dallas Goedert

Flex - Edmonds, Stevenson, Moore, Penny, Beasley

K - Prater

Def - Miami 

Good luck to all my fellow Fantasy Football participants! 

✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:50:10 </td>
   <td style="text-align:left;"> $SPY Futures and I have a love hate relationship... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:50:09 </td>
   <td style="text-align:left;"> $SPY Futes flat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:49:51 </td>
   <td style="text-align:left;"> $SPY the wealth effect Powell has created in these markets is unreal…don’t know when it will fall but when it does my fucking god it is going to be a sad day…overheard a couple using their last “child tax credit” to invest in alt coins…then watched them swipe a ebt card for payment at the grocery store…poor kids don’t have a chance and it is absolutely disgusting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:49:25 </td>
   <td style="text-align:left;"> $SPY 18 month gravy train..pulling into station...book gains. pigs get slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:49:07 </td>
   <td style="text-align:left;"> $SPY 🤲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:48:52 </td>
   <td style="text-align:left;"> $TSLA I learned to code 🤦‍♂️ I’m a software computer programmer specialist! I press keys all day - the world 🌎 should worship me ! I DRIVE AN ELECTRIC CAR POWERED BY COAL LOL  YET you still can’t find her G spot 🤪 and your soft ass hands got her identifying as a lesbian 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:48:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL never forget. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:48:01 </td>
   <td style="text-align:left;"> $tsla $spy so when does Elon become head of the fed and make Dogecoin a reserve currency? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:47:53 </td>
   <td style="text-align:left;"> $SPY economy improved lot better than last 2 years.  I m super bullish from now on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:47:49 </td>
   <td style="text-align:left;"> $SPY This rally is likely to be short lived. Prices went mental during trumps time in office and will remain subdued for a while. That will be 2 cents, thank you😛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:47:18 </td>
   <td style="text-align:left;"> $SPY Don&amp;#39;t take the vaccine.  My deductions:  1) repurposed drugs are more effective  2) money is not the motive for the push as this market clearly will give you all the money you want.  3) they want you dead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:47:01 </td>
   <td style="text-align:left;"> 1970s $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:46:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY This along with rising GEX tells you MM continue to re-hedge by buying on any drops and selling puts to retail day in and day out, rinse and repeat. If you know, you know. @OldFngGuy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:46:42 </td>
   <td style="text-align:left;"> $SPY they calculating which was to go to make as much as possible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:46:39 </td>
   <td style="text-align:left;"> $spy $RUT I went long small cap and small cap value on the 401k, from s&amp;amp;p 500. Let&amp;#39;s goooooo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:46:21 </td>
   <td style="text-align:left;"> $SPY puts on $AAPL FOR THEIR TRASH CHARGERS 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:45:59 </td>
   <td style="text-align:left;"> $SPY 

Yo them fag soy boys using chick pics to attract users are ultra sensitive when you call them out...

For real, for real... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:45:52 </td>
   <td style="text-align:left;"> $SPY  insanity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:45:28 </td>
   <td style="text-align:left;"> $SPY I think Calvin Coolidge would be the right Prez to get us through this Covid crisis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:45:17 </td>
   <td style="text-align:left;"> $SPY new batch of bears after yoloing 2 calls into FOMC and bought puts hoping for a limit down tmr to make themselves look like mike burry but gonna be burried in green candles tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:44:40 </td>
   <td style="text-align:left;"> $SPY ahh 😱 it’s going down again!?

Easy to reverse: just say it with me…

Futes… Rippin!

Boom they will rip again mow ya welcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:44:37 </td>
   <td style="text-align:left;"> $SPY bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:44:18 </td>
   <td style="text-align:left;"> $SPY bears are back 
After today ass whooping how can they still survive? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:44:00 </td>
   <td style="text-align:left;"> $SPY is currently trading near its 52 week high, which is a good sign. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:43:47 </td>
   <td style="text-align:left;"> $SPY like I said last night into this morning… a lot of bears around, and that’s always a FISHY situation. Now a lotta sour bears.. remember where there is dear there is money to
Be made.. where there is greed there is money to be lost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:43:46 </td>
   <td style="text-align:left;"> $SPY  The reason why Bitty is playing house with Spy ? I’ll give you a hint. Who are the largest holders of bitty. The top 2%. The top 2% were on watch for interest rates same as Stock market elite. They are 1 in the same in that sense. Now let’s see the bullish follow through until march $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:43:37 </td>
   <td style="text-align:left;"> $SPY I BUSTED A VICTORY NUT TODAY AFTER MY CALLS PRINTED WHO ELSE? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:43:26 </td>
   <td style="text-align:left;"> $SPY can I go from $200 to $100k in a year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:42:30 </td>
   <td style="text-align:left;"> $SPY Bears with ridiculous comments again. Keep changing your narrative. No ones noticing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:41:59 </td>
   <td style="text-align:left;"> $SPY so now that Jerome is on the back burner for the next few weeks, what’s the new narrative ? Omicron, Manchin playing hard ball on the Build Back Better bill…but then what? Fear might not peek its head back in until mid January </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:41:57 </td>
   <td style="text-align:left;"> $SPY 666 tomorrow, ha! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:41:54 </td>
   <td style="text-align:left;"> $SPY 

Yo them bitches masking themselves as a chick... and fail to crop pic you stole online to make it look reasonably real. Fucking simp nation.

Bro... and the pic quality is straight up 90s Polaroid quality in 2021. Them bitches don&amp;#39;t change pic 21 years later... why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:41:22 </td>
   <td style="text-align:left;"> $UVXY buckle up ladies and gents this party is fixing to get started. Anyone else not sitting well with the banks not participating in the pop today? Im sure not and ready for the blood. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:41:04 </td>
   <td style="text-align:left;"> $SPY damn last time i looked spy was down $4 and now its up 7??? What happened? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:40:27 </td>
   <td style="text-align:left;"> $SPY biggest bull trap ever. Remember: Santa is RED. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:40:25 </td>
   <td style="text-align:left;"> $SPY ES hitting 10k VERY soon !!!

Perhaps even SOONER than you think !

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:39:41 </td>
   <td style="text-align:left;"> $BTC.X what happened bears ? I thought it was doomsday today lolll. $SPY should have added more earlier this week but all good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:39:09 </td>
   <td style="text-align:left;"> $SPY 

Yo... too many boys masking themselves as hot chick on stock twits.

Fags. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:39:03 </td>
   <td style="text-align:left;"> $SPY good thing the hubby can still trade options on her behalf because we’re a free market economy apparently😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:38:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:38:47 </td>
   <td style="text-align:left;"> $SPY We’ll revisit 468 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:38:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA I LIKE PIZZA 🍕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:38:02 </td>
   <td style="text-align:left;"> $SPY be advised its still witching week. 

Don&amp;#39;t chase. 
Intraday dips are real. 
Premium needs to burn. 
Don&amp;#39;t YOLO weeklies.
Buy nothing closer than next Wednesday expiration. 
Debit spreads further reduce your risk.
Credit spreads cap your risk. 
Don&amp;#39;t enter a day trade without any daytrades left! It won&amp;#39;t hold overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:38:02 </td>
   <td style="text-align:left;"> $SPY The only bears that screwed are the dumb ones that went short into a FOMC meeting lmao. Big money squeezed them out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:37:54 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:37:44 </td>
   <td style="text-align:left;"> $SPY $QQQ so he said what market expected him to say, and went from like -1.5% to up 2.5% in a few hours. Smell test says something stinky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:37:37 </td>
   <td style="text-align:left;"> $SPY  sold my calls 5 min to close opened puts all in for Jan 14th $469put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:37:06 </td>
   <td style="text-align:left;"> 🔥Watchlist for Thursday #4:
1) $CPIX (Gapper potential)
2) $ESSC (Higher lows forming ww)
3) $SPY (Strong bounce, going higher )
4) $TSLA (Should test 1010+ next)
5) $GMTX (vwap reclaim can see 3.50+)

Market back GREEN🟢🥵 Be ready to hit bangers and bank, gave you guys BFRI runner early this morning. More coming tomorrow, stay tuned..🛎️🛎️🛎️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:37:03 </td>
   <td style="text-align:left;"> $SPY no lie you guys need to look into NFTs. This movement is going to be huge but you have to pick the right community to be a part of. It’s cult-like just like $GME and $AMC but there’s no manipulation so the potential is limitless unless $ETH.X goes to 0$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:37:00 </td>
   <td style="text-align:left;"> $SPY can the markets FALL 5 TO 10% OVERNIGHT???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:36:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:36:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL yes you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:36:33 </td>
   <td style="text-align:left;"> $BTC.X crypto is not 24/7 anymore! Most of its major moves correlate with $SPY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:36:20 </td>
   <td style="text-align:left;"> $SPY I JUST BUSTED A FAT NUT HOLY FUCK $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:35:03 </td>
   <td style="text-align:left;"> $SPY futures looking ifffffy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:34:52 </td>
   <td style="text-align:left;"> $SPY 500 open tomorrow going to thin out a lot of bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:33:39 </td>
   <td style="text-align:left;"> $SPY notice how it just keeps stalling out at these levels. Couldnt break it all November and now twice this month. Fucking overcooked steak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:33:20 </td>
   <td style="text-align:left;"> $SPY APC family is the best </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:57 </td>
   <td style="text-align:left;"> $SPY $QQQ ah yes the good ol Cock &amp;amp; Balls formation on the secondly. Watch out we might open blurple 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:53 </td>
   <td style="text-align:left;"> $SPY not even thinking about puts til this hits 485. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:51 </td>
   <td style="text-align:left;"> $SPY they will kill puts and calls at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:51 </td>
   <td style="text-align:left;"> $TSLA  keep  thinking &amp;amp; believing you’re saving the world 🌎! Lol 😂 your wife knows you’re incapable of fixing anything mechanically driven , but you keep Simp’n and donating to cancer research 🔬 🧐  , 🤦‍♂️ FYI cancer doesn’t respond to walking btw $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:48 </td>
   <td style="text-align:left;"> $SPY it’s a vibe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:19 </td>
   <td style="text-align:left;"> $SPY shorts rn 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:32:09 </td>
   <td style="text-align:left;"> $SPY 490+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:31:48 </td>
   <td style="text-align:left;"> $SPY Its gonna stay flat tonight, Tomorrow at 9:30am it will rip again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:31:31 </td>
   <td style="text-align:left;"> $SPY Bears rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:31:25 </td>
   <td style="text-align:left;"> $SPY bro i find everything so fking funny lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:31:20 </td>
   <td style="text-align:left;"> $SPY I get it now… the rug pull the bears have been referring to is a magic carpet ride straight to a neighboring planet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:31:17 </td>
   <td style="text-align:left;"> $SPY angry pitbull club NFT going to pluto 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:31:05 </td>
   <td style="text-align:left;"> $SPY me after 2 blunts so far 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:30:54 </td>
   <td style="text-align:left;"> $SPY stock analysis

https://youtu.be/fIJZPazx9tM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:30:47 </td>
   <td style="text-align:left;"> $SPY give the team 500 then dump to whatever you mfers want </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:30:44 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA Nasdaq 100 Flies Despite Fed’s Hawkish Turn. Will the Rally Fade on Higher Rates Risk? https://www.billionaireclubcollc.com/nasdaq-100-flies-despite-feds-hawkish-turn-will-the-rally-fade-on-higher-rates-risk/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:29:59 </td>
   <td style="text-align:left;"> $SPY Powell bought calls, so you should too …. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:29:56 </td>
   <td style="text-align:left;"> $AMC 100k floor too @FairyGodmother 😆😆😆 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:29:33 </td>
   <td style="text-align:left;"> $SPY there was so much fear before the FED meeting and now it disappeared so we will be green for few days till the Omicron or big vaccines Phuck up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:29:00 </td>
   <td style="text-align:left;"> $SPY all cash and talking shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:28:41 </td>
   <td style="text-align:left;"> $SPY Undervalued anywhere under SPY 900

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:28:31 </td>
   <td style="text-align:left;"> $AMC apes together strong $SPY 
The apes grew on me even though my shares will be gone Friday I will always be rooting for them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:28:08 </td>
   <td style="text-align:left;"> $SPY wow huge message from creator of MRNA technology $MRNA 

https://rumble.com/vqq7gc-dr.-robert-malone-before-you-inject-your-child.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:28:01 </td>
   <td style="text-align:left;"> $SPY futures are buck wild.  Going to be an interesting day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:27:49 </td>
   <td style="text-align:left;"> $SPY you can just hear the echoes....in the virtual corners of the internet.

&amp;quot;OFG was right again&amp;quot; .....

Yes, bears!  The market did exactly what Option delta $$ and VIX predicted it would do for the 151st time in a row.

Shocking!!!! Even better when I will get the stupid &amp;quot;It can&amp;#39;t keep doing this&amp;quot; replies!!  🤦‍♂️🤦‍♂️🤦‍♂️🤦‍♂️

Flawed human condition on display 24/7 here!! 

Why do the most of you bears hate $$$ ???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:27:30 </td>
   <td style="text-align:left;"> $SPY rug pull coming. Best take profits at 630 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:26:57 </td>
   <td style="text-align:left;"> News for Reddit $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:26:41 </td>
   <td style="text-align:left;"> EW $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:26:23 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:26:22 </td>
   <td style="text-align:left;"> $SPY Jerome turned on the buy program before he spewed his lies..  Perception is everything to the sheep.. The underlying technicals tell a different tale.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:26:19 </td>
   <td style="text-align:left;"> Investing $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:25:55 </td>
   <td style="text-align:left;"> Where are some of you getting the idea that Anchorage was short $DNA? According to their latest 13-F filing (link below) they held 67,151,368 shares worth $730M (which was their largest holding of a single company and second largest holding total after $SPY). That’s more than 8 days worth of daily volume which presumably they’re going to liquidate. Also see my previous comments about what may happen if a big fund liquidates (which some of you criticized as being implausible). But who knows, maybe they&amp;#39;ve already liquidated and the issue is behind us; the quarterly nature of 13-F&amp;#39;s isn&amp;#39;t super helpful.  I&amp;#39;ll give Cathie credit for her transparency with holdings.

https://www.sec.gov/Archives/edgar/data/0001300714/000156761921020422/0001567619-21-020422-index.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:25:40 </td>
   <td style="text-align:left;"> $SPY stfu and get me 477 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:25:04 </td>
   <td style="text-align:left;"> $SPY let&amp;#39;s go 70 pe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:25:01 </td>
   <td style="text-align:left;"> $SPY going thru my ideas i actually  drew this the other day lol. Probably the most accurate prediction there is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:24:41 </td>
   <td style="text-align:left;"> $AAPL I hope you bears learned you’re lesson today, but most of you are so stubborn we will pillage you again tomorrow for another 2%+ “puts printing” 🤡🤡 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:24:27 </td>
   <td style="text-align:left;"> $SPY Futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:23:46 </td>
   <td style="text-align:left;"> $SPY hawk dove or this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:23:19 </td>
   <td style="text-align:left;"> $SPY whoever shorted this market is just a rookie. They’ll learn a valuable lesson for the rest of the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:23:19 </td>
   <td style="text-align:left;"> $SPY LOL WHAT SAY THEEE BEAR? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:23:04 </td>
   <td style="text-align:left;"> $SPY overbought and overvalued. Powell put a band-aid on a gunshot wound. 
This should bleed the next couple of of days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:22:47 </td>
   <td style="text-align:left;"> $SPY  the Europe Central Bank Press Conference at 830 am NY time a must watch on ECB website or youtube..  the risk of Ms Lagarde talking rate hike will be contagion move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:22:39 </td>
   <td style="text-align:left;"> $SPY good news everyone

https://www.the-sun.com/news/4281539/omicron-grows-quicker-airways-lower-lungs/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:22:18 </td>
   <td style="text-align:left;"> $SPY why are there people that claim to be different types of animals arguing with each other non stop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:22:08 </td>
   <td style="text-align:left;"> $SPY big gains coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:22:05 </td>
   <td style="text-align:left;"> $SPY Did JPOW acknowledge markets were overvalued, then tell people should invest? In the same meeting? i missed it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:21:54 </td>
   <td style="text-align:left;"> $SE if you love the chorus, you will love the drop

$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:21:16 </td>
   <td style="text-align:left;"> $UVXY $VXX $SVXY $SPY .
 

https://www.newyorkfed.org/markets/domestic-market-operations/monetary-policy-implementation/treasury-securities/treasury-securities-operational-details#current-schedule </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:21:13 </td>
   <td style="text-align:left;"> $SPY I don’t see 475 mañana 
Could be wrong but I think not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:20:18 </td>
   <td style="text-align:left;"> $SPY am i pissed about the idiot sht that went on today--- you damn ripp i am ---- powell is a self dealing  colluding/ collusive/ colluded maniac-- SEC/FBI where the fk are you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:20:12 </td>
   <td style="text-align:left;"> $SPY say hello to BIG RED tomorrow, U guys got faked out today, U&amp;#39;ll Pay tomorrow? ROFLMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:19:54 </td>
   <td style="text-align:left;"> $SPY fed can&amp;#39;t bring inflation down because gov will spend more and more and fed need to buy those bonds, so the stocks will not down because such money injection </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:19:08 </td>
   <td style="text-align:left;"> $SPY watching to see if spy breaks 472. If not then good put entry short term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:19:01 </td>
   <td style="text-align:left;"> $SPY I BOUGHT CALLS TODAY WHENEVER I TURN BULLISH MARKETS CRASH BEWARE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:18:40 </td>
   <td style="text-align:left;"> $SPY https://images-ext-2.discordapp.net/external/EYuz5qGR3YYARS_RCXF01v8rCqzjuyai9Yq9laTOe6o/https/charts.stocktwits.com/production/original_416326597.png?width=535&amp;amp;height=567 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:18:33 </td>
   <td style="text-align:left;"> $UVXY  $VXX $SVXY $SPY 

https://www.newyorkfed.org/markets/opolicy/operating_policy_211215 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:18:28 </td>
   <td style="text-align:left;"> $SPY 500 open tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:18:22 </td>
   <td style="text-align:left;"> $QQQ $SPY fked shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:18:21 </td>
   <td style="text-align:left;"> $SPY show or hands 🙌 for the men that still change oil and work on their own  cars ? $TSLA I know you Barbie bitches don’t do shit! Your wife / GF knows you’re a pussy but loves the free chicken tendies you keep serving up ! SIMP 😂 I’ll catch her later when you’re at work slaving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:17:54 </td>
   <td style="text-align:left;"> $SPY oh no, there’s still retarded bears thinking their puts will print tomorrow $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:17:35 </td>
   <td style="text-align:left;"> $SPY so let me guess? We&amp;#39;re not going to make new aths by eoy? Lol, fucking bears never learn... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:17:14 </td>
   <td style="text-align:left;"> $SPY $SPX SEEMS TO HOLD TRUE IN MANY INSTANCES 
The unpredictable increasingly becomes more likely with time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:17:08 </td>
   <td style="text-align:left;"> $SPY big bull cock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:17:08 </td>
   <td style="text-align:left;"> $SPY dont think for one second you will have a chance to get out bears. Dont even think about it 🤡 😂 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:16:52 </td>
   <td style="text-align:left;"> $Nasdaq $spy $DJIA 

🤔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:16:50 </td>
   <td style="text-align:left;"> $SPY that was just a reminder that nothing is sure for retail in this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:16:41 </td>
   <td style="text-align:left;"> $SPY 

🚀🚀🚀

https://investorplace.com/2021/12/nio-day-2022-13-things-for-nio-stock-investors-to-expect-on-dec-18/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-16 10:16:24 </td>
   <td style="text-align:left;"> $SPY let’s rally into the eoy so we can enjoy the holidays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:51:17 </td>
   <td style="text-align:left;"> $QQQ Palladium to the moon prrrrr prrr prrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:50:09 </td>
   <td style="text-align:left;"> $SPY $AMZN why AMZN is going to lead the $QQQ in 2022 in 3 charts

1) monthly RSI(14) below 39 is where the big reversals happen on a relative basis AMZN/QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:48:14 </td>
   <td style="text-align:left;"> Long term $1200 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:39:59 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY 
Warming up now 🐱
https://www.investing.com/indices/indices-futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:37:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK My two cents on today. 
 
Markets hate uncertainty, as everyone knows.  Today Powell removed all uncertainty about direction, action, and timing.  Much of it was surmised, but now it&amp;#39;s known.  Known knowns are good, to borrow from Don Rumsfeld.  Unknown knowns are not good. 
 
The key exchange was with Steve Liesman, who asked, essentially, if the point is to end bond-buying, why keep doing it AT ALL over the next few months?  Tapering is, after all, still massive bond buying, just less. 
  
Powell replied, &amp;quot;We’ve learned that it’s best to take a careful and methodical approach. Markets can be sensitive to it. We’re basically two meetings away.”  
 
1/2 see reply for 2/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:30:56 </td>
   <td style="text-align:left;"> $QQQ Inflation Nation Baby!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:30:39 </td>
   <td style="text-align:left;"> Market Volume Barometer 12-15-2021
Sentiment: PANICKY
Volume: 9%
Real Feel: CHILLY
Cycle: BEARISH II
Portfolio: CASH
Next Day Move: SIDEWAYS
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:28:38 </td>
   <td style="text-align:left;"> $QQQ hahahaha bears where such fucking pricks the last month and a half </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:28:12 </td>
   <td style="text-align:left;"> $UVXY anyone notice that after all the drama, all the VIX spikes.

This is still down over 50% in 6 months.

$SPY $QQQ Did I ever tell you what the easiest trade in the world is ?????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:28:00 </td>
   <td style="text-align:left;"> Looking ahead to Thursday: Investors will receive weekly Initial and Continuing Claims, Housing Starts and Building Permits for November, Industrial Production and Capacity Utilization for November, the Philly Fed Index for December, and the preliminary IHS Markit Manufacturing and Services PMIs for December.

S&amp;amp;P 500 +25.4% YTD
NAS Comp +20.8% YTD
DJIA +17.4% YTD
Russell 2000 +11.2% YTD

$SPY $QQQ $DIA $RUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:27:03 </td>
   <td style="text-align:left;"> FOMC just Finished, What&amp;#39;s next? December 16th trade ideas(RE-UPLOADED) https://youtu.be/J_v7HEIcRvA 

$IWM $SPY $QQQ $HOLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:26:01 </td>
   <td style="text-align:left;"> $QQQ $SPY gonna dump as reality sets in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:25:31 </td>
   <td style="text-align:left;"> $QQQ 402 TO 404 TOMORROW VERY EASY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:21:55 </td>
   <td style="text-align:left;"> $QQQ  $SPY  Powell will build the biggest bubble in the history of bubbles.   
 
it’s not popping yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:19:34 </td>
   <td style="text-align:left;"> $QQQ I agree with Larry Kudlow&amp;#39;s thoughts on rate hikes. DO IT NOW! Short term pain, like pulling a bandaid off,  to get us back on track. The longer we prolong this insanity the worse it will be. And if you think inflation is bad now, watch what happens if this spending bill gets through. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:17:35 </td>
   <td style="text-align:left;"> $QQQ if the market chops up and doesn’t break out this month that would F a lot of people counting on a Santa Rally or dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:17:00 </td>
   <td style="text-align:left;"> $BA it’s just fact; funds need dump this and $roku down 60% and $baba down 45% and light in $crwd which is even exactly from same day last year but $qqq up 26% 
So all these need more of a dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:16:17 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $DIA  News 

https://apple.news/AVcvSQDsTS7OSzaOTBomEoA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:15:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM is this American???
https://rumble.com/vqv2q2-new-yorkers-now-being-arrested-for-failing-to-show-proof-of-vaccination.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:14:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL triple witch friday. The fun isn’t over yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:13:31 </td>
   <td style="text-align:left;"> $SPY the American government is now so insecure that it won’t allow another country to rise up to power or technological advancement. Pathetic. All in the name of “national security”. No, it’s called national insecurity. Grow up. $QQQ $BABA $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:11:30 </td>
   <td style="text-align:left;"> $QQQ ahahaha bears are still in denial. Lol. $AAPL $SPY $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:09:29 </td>
   <td style="text-align:left;"> $QQQ red soon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:08:25 </td>
   <td style="text-align:left;"> $SPY $QQQ taper and rate raise was expected so markets move higher despite it being bad news. &amp;quot;Santa rally&amp;quot; expected but markets expected to move higher lol. &amp;quot;Bulls&amp;quot; make no sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:08:18 </td>
   <td style="text-align:left;"> $SPY We live in a world where nobody has to ever work again.  All you need to do is overleverage your useless dollars into this fed induced bubble and become millionaires while watching netflix.  Is this what the great humanity has become?   Greater fool theory.   $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:08:13 </td>
   <td style="text-align:left;"> With TradesViz you can analyze all your options greeks and find the most optimal options strategy.

TradeViz leaves no data when it comes to trading performance analysis. 

Why? Your edge could be hiding in any single chart.

$SPY $$AAPL $QQQ $TSLA $STUDY

Free 👉 http://tradesviz.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:05:03 </td>
   <td style="text-align:left;"> FOMC just Finished, What&amp;#39;s next? December 16th trade ideas
https://youtu.be/XEueoalQwzI

$HOLX $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:03:56 </td>
   <td style="text-align:left;"> Investors eye major Fed policy meeting  $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/investors-eye-major-fed-policy-meeting/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:02:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $QQQ did better than 78% of all other stocks. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 11:00:13 </td>
   <td style="text-align:left;"> $QQQ The hang seng be like: oh nevermind.. $BABA $JD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:55:16 </td>
   <td style="text-align:left;"> A quick rant …

https://howardlindzon.com/i-interrupt-my-optimism-with-a-rant-disruption-is-a-myth/

Disruption is a myth 

$btc.x $gs $jpm $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:54:07 </td>
   <td style="text-align:left;"> $QQQ It’s good to be green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:53:47 </td>
   <td style="text-align:left;"> $QQQ The irrational movement today should scare the crap out of you, whether you are a bull or a bear. Just sayin.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:48:27 </td>
   <td style="text-align:left;"> $QQQ Nasdaq McClellan Oscillator update:   looking forward to more big green days ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:48:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL never forget. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:48:03 </td>
   <td style="text-align:left;"> $QQQ chart actually still looks uh bearish... even after that &amp;quot;wtf&amp;quot; was that movement... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:46:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY This along with rising GEX tells you MM continue to re-hedge by buying on any drops and selling puts to retail day in and day out, rinse and repeat. If you know, you know. @OldFngGuy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:41:22 </td>
   <td style="text-align:left;"> $UVXY buckle up ladies and gents this party is fixing to get started. Anyone else not sitting well with the banks not participating in the pop today? Im sure not and ready for the blood. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:38:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:38:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA I LIKE PIZZA 🍕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:37:44 </td>
   <td style="text-align:left;"> $SPY $QQQ so he said what market expected him to say, and went from like -1.5% to up 2.5% in a few hours. Smell test says something stinky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:36:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL yes you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:36:20 </td>
   <td style="text-align:left;"> $QQQ a lot of wreckage in individual names in the nasdaq. Clear bounces off 15000 for the nasdaq composite. Maybe we are ready for that xmas rally after all. JPOW certainly seems confident in the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:32:57 </td>
   <td style="text-align:left;"> $SPY $QQQ ah yes the good ol Cock &amp;amp; Balls formation on the secondly. Watch out we might open blurple 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:31:08 </td>
   <td style="text-align:left;"> $QQQ Why do so many obnoxious bulls on this board feel compelled to use the word &amp;quot;fuck&amp;quot; or &amp;quot;fuck the bears&amp;quot; in almost all of their posts? It shows that either they are in the 4th grade, or only have a 4th grade education, and feel compelled to lash out in anger, using four letter profanity, to justify their small genitalia. just sayin.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:31:00 </td>
   <td style="text-align:left;"> $QQQ like that. santa rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:30:44 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA Nasdaq 100 Flies Despite Fed’s Hawkish Turn. Will the Rally Fade on Higher Rates Risk? https://www.billionaireclubcollc.com/nasdaq-100-flies-despite-feds-hawkish-turn-will-the-rally-fade-on-higher-rates-risk/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:29:11 </td>
   <td style="text-align:left;"> $QQQ Remember all this talk is just to end the asset purchasing.  Then they need to sell the assets.  Sucking money out of the market .  Then they start raising rates.  I wouldn’t get too euphoric yet 😂🤣😆😀😅🤑💰💲💰💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:23:16 </td>
   <td style="text-align:left;"> $QQQ so this actually goes up⁉️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:18:22 </td>
   <td style="text-align:left;"> $QQQ $SPY fked shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:17:20 </td>
   <td style="text-align:left;"> $QQQ 

🚀🚀🚀

https://investorplace.com/2021/12/nio-day-2022-13-things-for-nio-stock-investors-to-expect-on-dec-18/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:15:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMC tomorrow we crush the shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:15:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL euphoria will turn to sadness. Be cautious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:13:16 </td>
   <td style="text-align:left;"> $QQQ 

🔥NIO DAY IS JUST 2 DAYS AWAY, 10 THINGS THAT COULD HAPPEN🔥

1. NIO will reveal 2 New Electric Vehicles
2. Rumored Apple Partnership. Apple is looking to adopt a drivetrain from someone and NIO is number 1
3. NIO will offer an affordable EV to compete with the Model 3
4. NIO is creating a Newer Brand under NIO
5. NIO is partnering with LeasePlan 
6. NIO will be Dual Listed in the U.S.A and Hong Kong. Dual listing are known to drive up share prices by a substantial amount
7. NIO is launching its ET7 Sedan on NIO Day
8. NIO has other possible partnerships
9. Unknown NIO surprises
10. Timeline of when NIO Plans to expand into the United States </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:11:54 </td>
   <td style="text-align:left;"> Powell: $SPY $QQQ $DJIA  Labor force participation has been disappointing https://www.billionaireclubcollc.com/powell-labor-force-participation-has-been-disappointing/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:07:04 </td>
   <td style="text-align:left;"> $QQQ printer is turning off boys, how to unload that 9 trillion says the Fed. We get retail to buy our stuff says the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:06:34 </td>
   <td style="text-align:left;"> $QQQ $SPY quad witching time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:05:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA $AMD where do these idiots come from with the Bearish calls? Did they not pay attention today? Do you like losing money? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:05:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL blood cometh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:01:24 </td>
   <td style="text-align:left;"> $QQQ blood 🩸 for tomorrow! $rblx $amzn thanks for the headfake , ScamStreet !!! Blood tomorrow!!! $nvda !!!! Bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 10:01:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  used to be a bear 🐻, man was I stupid.Lost a lot of money trying to be smarter than everyone else…market isn’t about being smart, stupid mistake lol. Now I fuck and make a lot of money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:58:02 </td>
   <td style="text-align:left;"> $QQQ thoughts on the Powell speech today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:57:41 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:57:04 </td>
   <td style="text-align:left;"> $QQQ aunt may dies in spiderman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:56:37 </td>
   <td style="text-align:left;"> And there you go. Indices are red only after AH trading is closed and bulls are trapped… $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:55:20 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ 
Is there a chill in your future?
https://www.investing.com/indices/indices-futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:52:06 </td>
   <td style="text-align:left;"> $QQQ Invesco QQQ Trust Implied Volatility Decreased -10.5% to 20.7. IV Rank Falls to 0.57 Moderate Level. https://tinyurl.com/y4rbmdhb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:51:58 </td>
   <td style="text-align:left;"> Stock losing streaks are snapped. Stocks close near session highs $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/stock-losing-streaks-are-snapped-stocks-close-near-session-highs/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:51:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $T $AAPL 

What’s ironic is we filmed this in December prior to Covid. We filmed the hospital scenes at McCormick place &amp;amp; less than 3 months later that’s where the city of chicago made their make shift hospital for Covid patients. This is being released just in time for Omicron. Hollywood has a crystal ball I suppose! (I play a vaccine delivery guy in this &amp;amp; did multiple stunts). Hope y’all dig it!

https://m.youtube.com/watch?v=RaAG-SwEa7k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:49:50 </td>
   <td style="text-align:left;"> $QQQ -1.5% gap down is coming tomorrow ;D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:49:30 </td>
   <td style="text-align:left;"> $MRK $QQQ $SPY  casino opening in 12 hours 12 minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:48:02 </td>
   <td style="text-align:left;"> $SPY JPOW coming in clutch with the market recovery for the holidays! $QQQ $TSLA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:47:58 </td>
   <td style="text-align:left;"> $QQQ did the fed lie? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:47:37 </td>
   <td style="text-align:left;"> $NIO oh hell yeah $QQQ $RIOT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:43:23 </td>
   <td style="text-align:left;"> $SPY $QQQ LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:42:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $DPW $SOS 

I just have this feeling we are going to the mother loving moon one more time for good ole Powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:37:43 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:37:37 </td>
   <td style="text-align:left;"> $SPY $QQQ    🎯 FOMC Day Tips:

-make money all morning with what the market is thinking otm or itm (pssst volume vs no volume matters) with TA here
-VWAP matters
-pump before the meeting (otm for a scalp)
-hedge otm for meeting
-first 1m candle ain&amp;#39;t it bruh (sell off both gamma and delta squeeze OTM here)
-ride other leg (anxiety tolerance of switching to itm vs averaging down otm is on you here)
-If OTM, secure the bag before you get hit with that random stick save. 

Most importantly: Don&amp;#39;t get greedy!! Take what the market gives you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:36:58 </td>
   <td style="text-align:left;"> Top Buy Flow Money - 12.15.2021 - $SPY $XLU $GS $QQQ via Super Stocks App </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:34:34 </td>
   <td style="text-align:left;"> Dark pool after hours activity in:

$AAPL - $344M print
$QQQ - $722M print
$FB - $146M print
$MSFT - $133M print
$HYG - $122M print

#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:34:13 </td>
   <td style="text-align:left;"> $QQQ $SPY you can argue all you want we need to pull back from these levels. I even told you the bottom of futures tonight which is working out as planned. You’re not going to get one. Across the world is bullish as well for us. There were many factors behind this move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:28:12 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY HEY dumb bears 🐻 TINA says 
The MARKET is NOT expensive, it’s the Dollar that’s CHEAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:27:41 </td>
   <td style="text-align:left;"> $QQQ $QQQM $QQQV  The Launch of the $AABB Global Cryptocurrency Exchange December 28, 2021, this event should me Massive. $AABBG.X 
https://aabbgoldtoken.com/uncategorized/asia-broadband-sets-december-launch-date-for-proprietary-cryptocurrency-exchange/2021/12/08/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:27:23 </td>
   <td style="text-align:left;"> $TSLA $QQQ My hindsight is 20/20. Bears expected bad news with doom and gloom. The market was prepping for it. They were wrong. Now they gotta cover for the XMAS rush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:26:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL if you&amp;#39;re a &amp;quot;bull&amp;quot; you have to admit you&amp;#39;re on borrowed time. Covid was used to pump the markets to ridiculous levels because the fed fed the markets endless support but corrupt j bowell just told you the party is over and you&amp;#39;re still out here partying like it&amp;#39;s just begun lol. Insanity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:25:18 </td>
   <td style="text-align:left;"> $SPY $QQQ you&amp;#39;d have to be absolutely out of your mind to buy a 2.5% pump in 1 hr, and for that reason i know they are gonna continue the pump tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:23:44 </td>
   <td style="text-align:left;"> $AAPL Apples about to get capitulation 
$spy $qqq $xlk $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:23:05 </td>
   <td style="text-align:left;"> $QQQ no news is good news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:22:02 </td>
   <td style="text-align:left;"> Keep an eye on it. $QQQ  ❤️💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:21:23 </td>
   <td style="text-align:left;"> $QQQ 16300 being defended on futures like a champ. Good buy opportunity here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:19:40 </td>
   <td style="text-align:left;"> $SPY $QQQ  The Fed will be hiking rates into a slowdown. Huge policy mistake. I&amp;#39;d give this run until the end of February before the insane rug pull about to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:19:17 </td>
   <td style="text-align:left;"> $QQQ Tough being a bear in the face of such a monstrous move up today based on what ??? uhhh... The Fed once again lying to us about the state of the economy,  while at the same time telling us flat out to our faces, that stocks are overvalued. Chickens waiting in the wings...anticipating the inevitable coming home to roost party. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:18:33 </td>
   <td style="text-align:left;"> $SPY $QQQ new ATHs coming up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:18:03 </td>
   <td style="text-align:left;"> $QQQ what exactly was the good news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:16:50 </td>
   <td style="text-align:left;"> latexc7df94994f65eb22487fae7d1a683eecLLY 280c 250%
$AAPL 177.5c 165%

Live Stream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:11:03 </td>
   <td style="text-align:left;"> $QQQ In all my years of trading I have NEVER seen a 13point move in so little time. Impressive power! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:11:01 </td>
   <td style="text-align:left;"> $AAPL Aapl can never  handle 3 Trillion now with the interest rate hikes / sales ratio 

It’s going be ugly $SPX $SPY $QQQ $XLK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:10:52 </td>
   <td style="text-align:left;"> $TNA $GUSH $QQQ High IQ MENSA members bought puts at the end of the day.  Lots of other smart people waiting for the morning dip to scale in.  This means that tomorrow we gap and go wheeeee 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:07:05 </td>
   <td style="text-align:left;"> $QQQ oh no. The kids took it 🤣💩🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:05:38 </td>
   <td style="text-align:left;"> $QQQ Picture perfect example of a Hollow Red Candlestick (confirming)
https://share.trendspider.com/chart/QQQ/6682885hqj </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:05:28 </td>
   <td style="text-align:left;"> $QQQ possible pump before the witching day dump? No position but watching carefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:05:12 </td>
   <td style="text-align:left;"> $QQQ bulls cuming all over themselves for this?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:04:08 </td>
   <td style="text-align:left;"> $QQQ idk future&amp;#39;s are shady looking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:01:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $XLK $DIA $SMH … Now all the scared cash 💰 dry powder that got parked on the sidelines will be injected  💉 right back into the markets for the santa 🎅 clause rally ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:01:25 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $DIA 

Meant EOY 🧞‍♂️ Morgan Stanley’s PT S&amp;amp;P </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:01:04 </td>
   <td style="text-align:left;"> $QQQ is currently trading in the upper part of its 52 week range, slightly lagging the index. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 09:00:31 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F 

Going with Morgan Stanley’s EOW PT $4400

   🧞‍♂️ $QQQ $DIA  Update 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:57:28 </td>
   <td style="text-align:left;"> $NASDAQ $NDX $QQQ $XLK $SPY  🧞‍♂️

Interest rate sensitive stocks and indexes about to drop 30% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:56:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL if you&amp;#39;re a bull you are mentally handicapped and that&amp;#39;s ok. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:56:03 </td>
   <td style="text-align:left;"> $QQQ JPOW IS A REAL LIFE HERO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:55:24 </td>
   <td style="text-align:left;"> latex7d65d11df3e2e4efdc4035292ee6aca0QQQ &amp;lt;--speaking of resistance

$ES_F Speaking of smartest guys to evaluate and guide us into tom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:55:15 </td>
   <td style="text-align:left;"> $AMD I called AMD @ $180 EoY back in the 70s. Don’t know if it will get there or not but it sure will get close. $SPY $QQQ $SMH $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:54:24 </td>
   <td style="text-align:left;"> $QQQ $SPY we will now carry the torch over to asia and Europe to rocket us up. More so for nasdaq of course. But it’s going to be a great night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:54:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Omicron is basically a political affair at this point (and pharmas). If any govt truly cared and scared, they will have to shut down society again. But can&amp;#39;t, why? It costs too much money (= govt debt) and can&amp;#39;t risk that again when China and Russia is around to take every bit of opportunity they can find against US. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:52:31 </td>
   <td style="text-align:left;"> $QQQ FUCK U DUMB BEARS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:50:43 </td>
   <td style="text-align:left;"> $QQQ $SPY yikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:50:33 </td>
   <td style="text-align:left;"> $QQQ $410 by Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:50:19 </td>
   <td style="text-align:left;"> $QQQ no more Fed policy support for the crypto kiddies. Holding Fed baggies now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:49:15 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $QQQ November retail sales only grew 0.2%. We’re in another big wave of Covid (I know some people are too tough for Covid). I don’t think stocks are going to work. Digital assets are the place to be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:47:45 </td>
   <td style="text-align:left;"> $QQQ what did he even say the old man? Saying we have everything under control? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:47:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL j bowell literally told you all he is speeding up tapering which means the fed is PULLING their monetary support aka market propping and you&amp;#39;re all running into the market with reckless abandon lol. Make your money but you can&amp;#39;t be that stupid to think the markets will keep going up. The covid mania party is wrapping up quickly. Be careful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:46:59 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL $DIA $QQQ  🧞‍♂️

Apple closed three stores in the United States temporarily due to Covid outbreaks in the surrounding areas

Lock downs pretty much right Apple? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:42:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 
Christmas is still coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:42:36 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ $CFVI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:42:18 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $NDX 

Quite hard to move anymore up 

With a Vix that is Green and up after hours 

Vix looks like it wants to rip again 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:42:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL BULLS WON TODAY BUT BEARS ALWAYS EAT 😤😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:38:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures up, the bears actually thought the FED and Powell were going to help them out lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:37:46 </td>
   <td style="text-align:left;"> $NIO $LCID $GGPI Alright now J Powell is done, We can rally from here and on, Right right?! Bull market baby the show must go on! $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:34:33 </td>
   <td style="text-align:left;"> $SPY $ SPX $QQQ $NDX I find it interesting that EVERYONE stopped talking about poor market breadth all of a sudden… 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:34:32 </td>
   <td style="text-align:left;"> $QCOM $AMD $QQQ $SPY Ready to bank tomorrow 🤑💰💰💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:33:06 </td>
   <td style="text-align:left;"> $QQQ bottom is in on futures tonight for this puppy. Asia and Europe will send it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:31:41 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $DIA $BTC.X  
 
brownie points to JPow for mentioning the fact that the US has never had a large scale network outage yet, and that he sees the possibility as worrying. 
 
It was in response to question about crypto/blockchain, and whether he sees systemic risk in such digital assets. 
 
maybe he got word of the largest single-day outage of Amazon Web Services (again) this morning (Dec 15th), which lead to 88,000 websites being inaccessible at the peak.   
 
totally unreported in the news.  let the sheep graze until the shepherd calls.  lamb chops on order. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:31:41 </td>
   <td style="text-align:left;"> $QQQ looks like Santa threw coal at the shorts who weren&amp;#39;t quick to cover...

The Santa rally only failed once in my memory, although it still did, in 2018. That was ultimately the first double bottom before the covid crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:30:55 </td>
   <td style="text-align:left;"> $QQQ $SPY Nice Biden market today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:30:02 </td>
   <td style="text-align:left;"> $QQQ ath tomorrow 🤣🤣 hope y’all loaded them calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:28:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK After hours be like ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:28:04 </td>
   <td style="text-align:left;"> $gld $nugt $spy $qqq gold will most likely close at 1800 by quad witching this Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:26:37 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F    $4400      

$qqq $dia Futures Update 🧞‍♂️📞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:26:20 </td>
   <td style="text-align:left;"> $QQQ 405 Friday close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:25:51 </td>
   <td style="text-align:left;"> $QQQ Still green 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:22:59 </td>
   <td style="text-align:left;"> $SPY $ARKK $QQQ want to see green Christmas mfs lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:20:32 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $NVDA $TSLA https://apple.news/APfOuINLMTaay4Nm17jcr_g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:19:24 </td>
   <td style="text-align:left;"> $SPY $QQQ 

https://www.cnbc.com/2021/12/15/fauci-says-covid-boosters-work-against-omicron-no-need-for-variant-specific-third-shot-.html

Bottom line, get vaccinated if you haven&amp;#39;t yet, the vaccine protects you from either the Delta or the Omicron variant. If you aren&amp;#39;t vaccinated, you put yourself and your family at risk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:18:58 </td>
   <td style="text-align:left;"> $SPY $QQQ we fucking tomorrow boyz!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:17:07 </td>
   <td style="text-align:left;"> $QQQ $DJIA  🕵️‍♂️ I SPY TA – Thursday Dec. 16, 2021 : options https://www.billionaireclubcollc.com/%f0%9f%95%b5%ef%b8%8f%e2%80%8d%e2%99%82%ef%b8%8f-i-spy-ta-thursday-dec-16-2021-options/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:16:49 </td>
   <td style="text-align:left;"> $QQQ ATH Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:14:47 </td>
   <td style="text-align:left;"> $SPY $QQQ bears still don’t get it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:14:00 </td>
   <td style="text-align:left;"> $SPY To all those saying espy earnings be good next time, that tech is the way to go forever now, $QQQ is perfect,  that, blah this higher, blah that. Blah, blah, blah.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:12:48 </td>
   <td style="text-align:left;"> Why the Fed feels now is time to tighten credit more quickly $SPY $QQQ $DJIA  https://www.billionaireclubcollc.com/why-the-fed-feels-now-is-time-to-tighten-credit-more-quickly/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:12:28 </td>
   <td style="text-align:left;"> $SPY $QQQ all those crushed puts that couldn&amp;#39;t seem to find a bid at close will be worth so much on Friday after lunch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:11:33 </td>
   <td style="text-align:left;"> $SPY $QQQ all time high next week for sure tho and last week of dec we rally to 480+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:11:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ JPow for president! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:11:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA now that the Fed excitement is behind us for now, the only thing in the news is Omicron. It seems America, and it&amp;#39;s markets, are woefully unprepared for the potential outcomes. Will the markets shrug it off like delta, or are we in for more volatility...
https://www.google.com/amp/s/nymag.com/intelligencer/amp/2021/12/omicron-is-about-to-overwhelm-us.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:10:59 </td>
   <td style="text-align:left;"> $SPY $QQQ going into opex becareful for a pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:07:21 </td>
   <td style="text-align:left;"> $QQQ $SPY imagine thinking we are going to tank overnight LOL. The Nasdaq will always remain the strongest. I’m always heaviest in the nasdaq and lighter in the S&amp;amp;P just because of it’s makeup. Tech is always superior. The returns on tech especially the big boys have been endless. That won’t end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:05:44 </td>
   <td style="text-align:left;"> $SPY $QQQ geez they can&amp;#39;t even wait until 8pm to start dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:04:02 </td>
   <td style="text-align:left;"> $SPY $qqq Friday quadruple witching.  ES and Nq expire early on Friday morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:03:16 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA  best trading day in my 5 years of experience. What a day 🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:02:07 </td>
   <td style="text-align:left;"> $SPY $QQQ Raising rates isn&amp;#39;t bullish, but raising them with plenty of transparency isn&amp;#39;t bearish... does that make sense? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:02:04 </td>
   <td style="text-align:left;"> $SPY $NVDA $QQQ the funny thing here is most bears need and wish for the market to collapse just so they have a chance of finally making some real money. Is your life that pathetic you wish the country to fail just because you suck ass at trading? Lmao absolutely pathetic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 08:01:08 </td>
   <td style="text-align:left;"> $SPY $QQQ If there is no meaningful pullback and a continued ramp of the markets in 2022 along with rate hikes from the FED. I&amp;#39;m thinking a 1929 scenario is in play. I hope the market finds some way to slow down. $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:59:25 </td>
   <td style="text-align:left;"> $QQQ Truly epic pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:57:38 </td>
   <td style="text-align:left;"> $QQQ fed said employment is stronger than all previous recoveries. Liquidity will be removed. 
Tank coming
Good luck all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:57:21 </td>
   <td style="text-align:left;"> $MJ You can&amp;#39;t get high with $MJ only the real thing can $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:56:49 </td>
   <td style="text-align:left;"> $QQQ 
So just thought you guys other then the fed speaking nothing has changed  make sure you have some hedge against qqq
Just to protect your profits 
Just thought 💭 what y’all think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:54:33 </td>
   <td style="text-align:left;"> $ETH.X hmm $QQQ $TQQQ $RIOT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:54:26 </td>
   <td style="text-align:left;"> $SPY I’m married to $QQQ and occasionally sleep with $SPY. I know it’s kinda cringe but these two barely let you down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:53:32 </td>
   <td style="text-align:left;"> $QQQ It&amp;#39;s interesting that the FED comes right out and tells you to your face that stocks are overinflated and overvalued and the lemmings and sheeple just lower their heads and buy buy buy more and more. Just incredible. Never seen anything like it in my lifetime.... although I wasn&amp;#39;t around in 1929. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:53:13 </td>
   <td style="text-align:left;"> $QQQ yes nearly every single company became dramatically more valuable at exactly 2:03pm today LOL i promise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:51:23 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ Yet again “Everyone is a genius in a bull market”… Pathetic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:51:19 </td>
   <td style="text-align:left;"> Stocks Jump As Volatility Dumps Post #FOMC $QQQ $AAPL $SPX $VIX https://talkmarkets.com/content/stocks--equities/stocks-jump-as-volatility-dumps-post-fomc?post=337978 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:50:11 </td>
   <td style="text-align:left;"> $AMC $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:50:08 </td>
   <td style="text-align:left;"> $SPY $QQQ pumper in chief had to go in for a retune.. started sounding a little too hawkish.. unacceptable. We at the fed have no idea what is going on, and will continue to provide free money and act way too slowly to combat inflation so our rich friends continue to over inflate every asset known to man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:49:36 </td>
   <td style="text-align:left;"> $SPY $QQQ  where are we still using QE? I don’t understand how we’re going to be able to deflate, raising rates without this market imploding at least 20% to the downside? Thoughts? Buying large short positions on my bday in March. Make it make sense plz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:48:51 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY chances of getting a bull rally through q1 better now that JPow ripped bandaid off and announced the taper? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:48:49 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:44:09 </td>
   <td style="text-align:left;"> $QQQ what did the fed say that tech liked so much? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:44:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA $AAPL $AMZN Bears really thought this was their year for a Santa rally. ATH coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:43:26 </td>
   <td style="text-align:left;"> $QQQ Who panic sold ? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:42:41 </td>
   <td style="text-align:left;"> $QQQ Where&amp;#39;s all the retarded shortie bear morons that usually stink up the joint?

Where&amp;#39;s the 40% crash Bozo and the economist doom dude? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:42:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X If you think Santa knows if you&amp;#39;ve been bad or good, there&amp;#39;s Someone who knows even more so (including every idle thought you&amp;#39;ve ever had).  

Sin is the problem, Jesus is the answer. ♥️✝️♥️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:42:07 </td>
   <td style="text-align:left;"> $QQQ fuck yeah boyz, what a day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:37:55 </td>
   <td style="text-align:left;"> $KDA.X $AVAX.X $ETH.X $QQQ $SPY   was there any doubt about today&amp;#39;s fed meeting and the price action??? A monkey could of called that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:37:42 </td>
   <td style="text-align:left;"> $QQQ 

By the looks of the posting here quite a few dickhead imbeciles got wiped out today ... Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:37:24 </td>
   <td style="text-align:left;"> Quad Witching Visualized and My Way Around it  $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/quad-witching-visualized-and-my-way-around-it/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:36:17 </td>
   <td style="text-align:left;"> $QQQ Made 85R today on day trade account. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:35:08 </td>
   <td style="text-align:left;"> $QQQ fucking bullish you guys 🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:33:46 </td>
   <td style="text-align:left;"> $QQQ This country is literally falling apart at the seams and the stock market is like a blind cow, rampaging in the dark, having no sane reason to sustain its continuously massive growth bubble other than the propaganda from the FED and the Media. Today was something out of Alice in Wonderland. The Market is so broken now, there is no where left for it to go but into a  deep dark crater. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:32:57 </td>
   <td style="text-align:left;"> $QQQ 500% return today for buying a car just before the Fed meeting. 

This will be my new life I am a permanent QQQ caller </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:32:16 </td>
   <td style="text-align:left;"> $QQQ why can’t you delete messages on here you post anymore they want everything to be set in stone? Well let this be set in stone: Long calls on this and $SPY are the easiest money in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:31:03 </td>
   <td style="text-align:left;"> $QQQ Back to that 400 supply zone. Pretty much the line in the sand to determine if Santa is really in play this year with most of the techs reset and perking upward and set up to sustain a move thanks to the recent volatility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:30:49 </td>
   <td style="text-align:left;"> $SPY $QQQ please understand even at THIS point buying is safe. It’s a risk free market. They want more. Never be afraid to buy near ATH because you never will buy the top. If you need to dca that’s fine too! But always remember who makes out more in this market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:30:34 </td>
   <td style="text-align:left;"> 🧭 SPY Daily: Panic On Wall Street $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/%f0%9f%a7%ad-spy-daily-panic-on-wall-street/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:29:03 </td>
   <td style="text-align:left;"> $QQQ if you were still short heading into today’s meeting…:you are…retarded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:28:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK Going live tonight at 7pm Central to cover:
✅General Market Outlook
✅Stocks on my Watchlist
✅Chart Requests from YOU!
https://youtu.be/E3yIn3GIfDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:28:24 </td>
   <td style="text-align:left;"> $QQQ Kneel before the mighty Jpow…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:27:17 </td>
   <td style="text-align:left;"> $QQQ Just remember -  It comes crashing down just as fast and furious as it goes skyrocketing up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:25:51 </td>
   <td style="text-align:left;"> $QQQ legit 15$ from the lows of today, that’s fucking insane . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:25:36 </td>
   <td style="text-align:left;"> $QQQ the whole market went bullish. That’s a sign of euphoria across all sectors. There will be winners and there will be losers please don’t think for 1 minute the whole market about to rally into end of the year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:23:48 </td>
   <td style="text-align:left;"> $QQQ Gotta admit... it&amp;#39;s tough to be a bear in this kind of nonsensical pie in the sky rally from the depths - just incredible - and don&amp;#39;t let these asshole bulls tell you they knew what would happen today - they were all hiding in their holes, and then came scurrying out like land crabs, boasting and bragging, huffing and puffing, when they saw things had miraculously turned in their favor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:23:41 </td>
   <td style="text-align:left;"> $SPY They can never hike.. powell cant say it
 Never will.  Too many pensions. Too many baby boomers too many retirement accounts.  He cant bring the whole party down. Let the bubble grow
$DIA $QQQ $GLD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:23:39 </td>
   <td style="text-align:left;"> $QQQ rip my bear friends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:23:15 </td>
   <td style="text-align:left;"> $QQQ tomorrow 405? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:22:47 </td>
   <td style="text-align:left;"> $NFLX $SPY $QQQ $AAPL  BouuGht ThiS BaD BoY eaRlier… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:22:42 </td>
   <td style="text-align:left;"> THE RALLY OF AGES  
 
Please told me you all listened when I outline this yesterday.  If ST didn’t ban my original account I could Have helped so many more  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:22:21 </td>
   <td style="text-align:left;"> $QQQ Either J Pow is the greatest or the worst. The man is an enigma. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:21:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $GLD $OIL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:20:49 </td>
   <td style="text-align:left;"> $QQQ When should I buy puts? Everyday I think I&amp;#39;ve gotten puts for cheap, this stock manages to wiggle out of the bottom and flies. I&amp;#39;m mentally exhausted now. Maybe the so-called big correction the old time bears have been preaching is a bit exaggerated. I&amp;#39;m not sure anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:20:48 </td>
   <td style="text-align:left;"> $QQQ $SPY man they’re going to fuck them overnight too. GENIUS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:18:46 </td>
   <td style="text-align:left;"> $AAPL Crazy I closed Feb 160/130 puts yesterday, this is madness BTFD markets 😂 $QQQ $SPY $IWM Bears get squeezed all the time after FOMC 😂 waiting for new ATH 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:15:57 </td>
   <td style="text-align:left;"> $SPY $QQQ one thing is for sure - today&amp;#39;s market move could create a giant squeeze as so many idiots (the pros) were short before FOMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:15:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM And the Emmy Award for Best Supporting Actor goes to… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:13:11 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 12/15/2021 $SPY $XLF $QQQ $TSLA $NVDA https://www.chartguys.com/daily-market-videos/4080/where-i-am-looking-for-continued-strength </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:09:52 </td>
   <td style="text-align:left;"> latex65328ad8f28b1f6ad58fe38f84b68d6eQQQ Nasdaq is so weak, totally dependent on FED money to move too. Growth about to halt it too, that retail # didn&amp;#39;t exactly speak of growth, did it? 

$ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:09:42 </td>
   <td style="text-align:left;"> $QQQ quad bitching is more like it 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:09:35 </td>
   <td style="text-align:left;"> FUTS 🚀
With the Fed now behind us. Let’s start this Santa Rally 🎅 

$SPY $QQQ $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:09:13 </td>
   <td style="text-align:left;"> $QQQ Oh thank you very much nikkei futures. Ty ty ty 🤑🙂🙂🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:08:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA wheres everybodys favourite place to go for ES1 quotes outside of their brokerage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:08:47 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/QzSNHp2lxPM $QQQ $SNAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:08:10 </td>
   <td style="text-align:left;"> $JPM $BAC $QQQ $XLF 
The big move ALWAYS happens the day after when the BOE meets.
Either way, banking stocks will fall like a crack hoe&amp;#39;s under pantaloons.
Almost every day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:07:28 </td>
   <td style="text-align:left;"> There is NOTHING between US and the END OF THE YEAR = SANTA CLAUS RALLY INSANE $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:06:38 </td>
   <td style="text-align:left;"> $QQQ $SPY hasnt been a day in months futures opened red. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:06:36 </td>
   <td style="text-align:left;"> $QQQ 10% inflation incoming but the stocks are gonna be printing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:05:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN, SCOTTIE PIPPEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:03:46 </td>
   <td style="text-align:left;"> $QQQ $SPY $FB $AAPL   $NFLX  I pray none of youll actually bought short dated puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:02:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

there’s a reason why politicians by shares and not puts! 

https://www.cnbc.com/2021/12/15/house-speaker-nancy-pelosi-opposes-banning-stock-buys-by-congress-members.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:02:35 </td>
   <td style="text-align:left;"> $QQQ Fuck your puts - J POW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:02:34 </td>
   <td style="text-align:left;"> $QQQ $SPY who’s ready to rip bears to shreds all night? I am! Any dip will be a big buy. This was a huge anticipated event and now that it is bullish there is literally NOTHING that will take this market lower now. They’re still buying. 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:02:10 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA 

CONGRATS BULLS 

Dow jumps 380 points, Nasdaq surges 2% in relief rally after Fed gives rate hiking timeline https://www.cnbc.com/2021/12/14/stock-futures-are-flat-ahead-of-key-fed-decision-.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:01:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $NVDA $TSLA 

Ho Ho Ho 🎅🏼 is coming to town 
All the naughty list will get 🎁💎
So, are you naughty or nice?? 🤔😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:01:18 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL you gotta love how everyone is so excited about individual stocks rising &amp;quot;on their own merits&amp;quot; when literally every stock rose starting at the same time. Market controllers are in charge and they aren&amp;#39;t done sucking euphoric bulls dry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:01:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY these morons scream “manipulated” and yet trade against it. Special kind of stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 07:00:42 </td>
   <td style="text-align:left;"> $QQQ $SPY didnt matter what the hell powell said today mms needed no reason to pump.and kill the quad witching puts. after those millions of options die we can get the true move from the fomc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:59:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA It seems like every day another high profile millionaire leaves the state of California and moves somewhere with low income taxes

https://www.msn.com/en-us/money/realestate/hilary-swank-moves-to-colorado-lists-california-mansion-for-10-5m/ss-AARNVCs?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:59:12 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Fed Tightening Doesn&amp;#39;t Have to Doom Nasdaq-100 https://www.stck.pro/news/QQQ/19779926 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:59:10 </td>
   <td style="text-align:left;"> $SPY $QQQ great move today especially by EOD. seems like the market was penciling in garage sentiment from Powell despite the tapering being online with the whisper number. Just be careful, I don&amp;#39;t expect many of the companies that caught a bid with the buying this afternoon to hold, which will weigh down on the indexes. I&amp;#39;m watching to see how the chart develops. He broad picture hasn&amp;#39;t changed because of today&amp;#39;s action especially considering the quad witching that adds to volatility. We could go higher, just be careful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:59:00 </td>
   <td style="text-align:left;"> $QQQ is currently trading in the upper part of its 52 week range, slightly lagging the index. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:58:53 </td>
   <td style="text-align:left;"> $QQQ Haha. day from that double bottom this morning. Call played beautifully. With equity up 16.4K for the day from being down 8K this morning. Tripled down on options I had bought monday for .85 and cut my average from 5.80 to 2.80 and rose them to 4.50. Very blessed today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:58:26 </td>
   <td style="text-align:left;"> $QQQ $SPY whats hilarious is that any drop will be forming endless bull flags LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:58:11 </td>
   <td style="text-align:left;"> $QQQ $SPY 3 super bullish news today:
• Fed was more hawkish, 3 hikes in 2022
• PPI hit record highs in Nov
• Retail sales dropped

WTF, markets kept dropping all week fearful of a hawkish Fed but they were even more hawkish. Senseless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:54:57 </td>
   <td style="text-align:left;"> $MSFT $QQQ  shouldn’t we rally from here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:54:54 </td>
   <td style="text-align:left;"> $PLTR remember when institution’s bought up all the paper hands’ shares? Me too.

Big financial institutions obviously have no idea what they’re doing. They totally don’t have edge or insider information.

Powell talking today about financial institutions, and last time about how government needs a better way to modernize their infrastructure..

Palantir is all I could hear. Lfg $SPY $TQQQ $QQQ 

Bye bye bears 🐻 🤡🐻🐻🤌🔥🔥🔥🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:54:37 </td>
   <td style="text-align:left;"> $QQQ At this point, bears need some seriously bad news to get their put options to print bigly. This market is way too bullish beyond reason and it hurts seeing big green candles day after day as a bear. May God help us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:51:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD NEWCOMER TRADERS,  if you’ve never experienced this , tomorrow and Friday were most likely going to get LIMIT UP  circuit breakers! your calls will go up between 2,000- 3000% all the way up to 10,000%! $100 in calls  could be worth 10,000 within 24 hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:50:50 </td>
   <td style="text-align:left;"> $QQQ It&amp;#39;s not safe for bears anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:50:42 </td>
   <td style="text-align:left;"> $QQQ $SPY interest rates drop, market bullish....interest rates high...market bullish...If you think you are able to explain the market always remember that it is irrational. The last spike on bad news didn&amp;#39;t end so well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:46:34 </td>
   <td style="text-align:left;"> $SPY $QQQ If you didn&amp;#39;t buy today then you might have missed the bottom that we won&amp;#39;t see again for awhile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:44:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears got decimated towards the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:44:20 </td>
   <td style="text-align:left;"> $QQQ &amp;quot;The end of year rally should remain intact if the variants do not suddenly spike out of control.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:44:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL insane bull trap. Impending doom on route and everyone is blinded by euphoric covid mania. So sad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:44:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA the unknowns are done for the year. Finally santa clause rally time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:43:36 </td>
   <td style="text-align:left;"> $QQQ $SPY if any of you all thought the Fed news would be received negatively by Mr Market then you have been sleeping for decade!  I bet it’s a 95% success rate and they were handing out free $$$$ all morning!  :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:42:48 </td>
   <td style="text-align:left;"> REST OF THE MONTH…Markets going to rally and   blow so fast you’re heads going to spin!  limit up circuit breakers👇 like we had in  March 2020 days..in one day we could see 
$DJIA up  2,000 pts
 $SPY up 5-10 percent
 $QQQ up 5-10 percent  
you’re call options could go up 2,000 to 7000% in one day💯💯💯
WELCOME TO THE REVOLUTION FOLKS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:42:43 </td>
   <td style="text-align:left;"> $QQQ $SPY stock market took the news as bullish as one could imagine. The dollar however said you thought we had inflation? Watch this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:42:38 </td>
   <td style="text-align:left;"> $spy $qqq $dia $iwm
Bonafide inverse head and shoulder.
Target $492 -$496. We will see it by early next week $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:42:03 </td>
   <td style="text-align:left;"> $SPY $QQQ radio silence from the bears after this afternoons anal probe.  Nothing taking this market down.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:41:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Tomorrow should be interesting. I have no idea what happens but I’m open to creating a new plan very quickly 😉 GL to us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:41:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM 

Market be like after the meeting today: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:41:21 </td>
   <td style="text-align:left;"> Stocks rise on Wall Street after Fed dials back stimulus  $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/stocks-rise-on-wall-street-after-fed-dials-back-stimulus/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:39:48 </td>
   <td style="text-align:left;"> The CDC tracks variant prevalence across thousands of tests weekly for quick data on omicron. In our current model, we anticipate 20-40% of all Covid cases to be from Omicron in January and 50-70% by the end of February. Currently, we believe that case numbers will have peaked by the end of March and steadily decrease into the summer. This estimate is subject to change pending new data. I plan to use any omicron-based weakness in the market $SPY $QQQ $DIA $IWM  to my advantage and add to high conviction stocks in both my investment and swing portfolio. 
https://covid.cdc.gov/covid-data-tracker/#variant-proportions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:38:16 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

6 rate hikes are bullish for markets? 🤣🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:37:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA $NVDA 

💎Fortes fortuna adiuvat💎

https://crypto.com/fftb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:34:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT $IWM 

Bottom is in folks. Fed won’t be raising interest rate much, only 0 to 1/4 percent is what they said.

I’m banking on Will Meade being right. We also saw a small cap rally spring 2021.

Here’s the link to the FOMC meeting:  https://www.federalreserve.gov/monetarypolicy/files/monetary20211215a1.pdf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:33:16 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:33:04 </td>
   <td style="text-align:left;"> Fed will tighten credit faster and sees 3 rate hikes in 2022 $SPY $QQQ $DJIA  https://www.billionaireclubcollc.com/fed-will-tighten-credit-faster-and-sees-3-rate-hikes-in-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:32:27 </td>
   <td style="text-align:left;"> $SPY our discord making bank today ! Want to join a group very knowledgeable traders ? Comment for the link . Discord is free guys . 500$-10k challenge starts Friday ! Don’t miss this ❤️💴💴 $QQQ $GME $AMC $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:30:47 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F     🧞‍♂️.   $QQQ $DIA 

With Vix still above $19 we must be heading to $4800-4900 next week or Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:30:39 </td>
   <td style="text-align:left;"> $SPY  You have to read everything I say to get things, following my best advice, and I am a bear but I am also all cash. 
Whether it&amp;#39;s pkay all cash or not, I pray to God if I give you advice it&amp;#39;s as if I&amp;#39;m spending REAL MONEY. Because I am real, unlike a rubber ducky @ybanmeyo 

Afterall, who would you rather have in a fight for you, a duck. Or, I&amp;#39;ll take it further, the most terrifying dog to mankind, maybe, a rot, or, a lion, which, ahem, is me👍

But it&amp;#39;s almost like a restart right now, just get to end of day last Friday and we at same 370s # for close.

So......we&amp;#39;ve gone nowhere fast, LOL. 

This is where the real fun starts, in other words, and, Tutes, not you, retail, will dictate &amp;quot;the flow.&amp;quot;
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:29:33 </td>
   <td style="text-align:left;"> $QQQ tomorrow likely a  early dip maybe to 395? Before heading back up again maybe 400 tomorrow or Friday but there is a high likelihood on Friday end of day sell off I doubt people will hold over the weekend most will take profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:27:39 </td>
   <td style="text-align:left;"> $CRWD sitting exactly where it was last year on this weekly date almost to the penny 
You ytd return &amp;gt;&amp;gt;&amp;gt;&amp;gt; 00.000
Return on $qqq &amp;gt;&amp;gt;&amp;gt; 26% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:27:33 </td>
   <td style="text-align:left;"> $QQQ  Claiming Santa rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:27:14 </td>
   <td style="text-align:left;"> $QQQ was bear but have to switch to bull till mid-end of January. Fed delivered bulls their meal on a silver platter. Come about Feburary though we should start to see a correction ahead of the beginning of tapering. Moved 401k from cash back to big tech today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:26:23 </td>
   <td style="text-align:left;"> $QQQ the dump is over ath highs are nigh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:26:14 </td>
   <td style="text-align:left;"> $QQQ ask yourself this.  Do you know if AMZN is worth 3310 or 3460? What about TSLA at 930 or 970?  FB 323 or 340?  It&amp;#39;s all the same. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:24:53 </td>
   <td style="text-align:left;"> $QQQ After rallying 2.3% it just sits at the highest points and no sells. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:24:50 </td>
   <td style="text-align:left;"> Dow jumps 380 points, Nasdaq surges 2% in relief rally after Fed gives rate hiking timeline

$DJIA $QQQ $SPY $IWM

https://www.cnbc.com/2021/12/14/stock-futures-are-flat-ahead-of-key-fed-decision-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:24:39 </td>
   <td style="text-align:left;"> $QQQ So how is the dollar up today? Seems like the perfect opportunity to sell. Fools buying into the Santa Rally bs and the value of the dollar is up while stocks are still inflated. Maximum value is right now for the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:22:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  know what will happen next day… there are times when market rally super hard and then drops back down next day…. Omicron is getting worse . I bet on puts  Monday Tuesday… let see if I will get another surprise on Thursday market open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:22:24 </td>
   <td style="text-align:left;"> $SPY $QQQ bears (shorts) covering and bulls buying; this was a rally on STRONG VOLUME. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:21:19 </td>
   <td style="text-align:left;"> $QQQ jesus.

Fuck, your, puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:21:07 </td>
   <td style="text-align:left;"> $QQQ Easy money at CALT, FDA APPROVAL. Almost up 85% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:18:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  apple 🍎 is 🔥 
💰💥💰💥💰💥💰💥💰💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:17:04 </td>
   <td style="text-align:left;"> $QQQ the pig never ends! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:16:57 </td>
   <td style="text-align:left;"> $SPY $QQQ So true! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:15:41 </td>
   <td style="text-align:left;"> $QQQ 😂😂😂
Pelosi opposes banning lawmakers from owning stocks, cites &amp;#39;free-market economy&amp;#39; https://www.cnbc.com/2021/12/15/house-speaker-nancy-pelosi-opposes-banning-stock-buys-by-congress-members.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:15:26 </td>
   <td style="text-align:left;"> $QQQ 390 max pain.  Get ready for some selling the next 2 days!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:15:11 </td>
   <td style="text-align:left;"> $SPY Unless you gambled--I didn&amp;#39;t, all cash, wasn&amp;#39;t about to go bull with that crap retail report-- you are FINE....

Now, the real party starts, we simply have retraced our points (up) to last Friday, 470.94, think was THE CLOSE.

So, now, is where REAL MONEY is made.
Texh didn&amp;#39;t move all that strong today sans $AMD  faultful retail hysteria + xylink merger that may or may not be China approved by NEXT X-mas, but, yeah, they, $NVDA, ironically, retail stocks, moved things up from severe doldrums pre-FOMC.

I don&amp;#39;t hate nor dislike either, I&amp;#39;m simply making a point that IF they are realistic,  they should be weaker and it would help market not jump unrealistically post-FED.

But, yeah, we&amp;#39;re, as the saying goes, almost right back where we started from, a day removed.

Bullish?
Bearish? 

Let the real war begin.....
$QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:13:51 </td>
   <td style="text-align:left;"> Crazy day WOWWW… VERY unexpected to see what the $SPY $QQQ did. Just craziness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:12:26 </td>
   <td style="text-align:left;"> $SPY $QQQ  Strong capital inflow！ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:12:26 </td>
   <td style="text-align:left;"> $qqq $aapl $msft https://www.youtube.com/watch?v=1jnfZaEyseE&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:11:26 </td>
   <td style="text-align:left;"> $qqq $spy $amzn https://www.youtube.com/watch?v=xD9Nu_487sQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:10:59 </td>
   <td style="text-align:left;"> $SPY $QQQ anyone ELI5 why the news today was taken well by wall st? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:10:04 </td>
   <td style="text-align:left;"> $QQQ triple bottom inverse H&amp;amp;S on QQQ lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:10:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $AAPL The I-told-you-so selfie.$500 PT by year end. 🤑🤑😴🤑😴🤑🤑🤑🤑🤑😴🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:09:21 </td>
   <td style="text-align:left;"> $QQQ 1.82 million block sell. Sheesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:09:20 </td>
   <td style="text-align:left;"> $ES_F $SPY $QQQ $NQ_F indexes closed at new highs. New higher highs coming into Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:08:50 </td>
   <td style="text-align:left;"> $QQQ Short term bullish swing and shedding profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-16 06:08:21 </td>
   <td style="text-align:left;"> $QQQ hey guys here from spy 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:39:31 </td>
   <td style="text-align:left;"> $AAPL got a 40% gain for the year so far with apple. I would love to close it out with about a 52%. Think that’s not asking to much?!?!??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:39:22 </td>
   <td style="text-align:left;"> $AAPL FMs have to buy this for year end statements….  Going higher.  Some profit taking after year end.  Then over 200 jan feb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:39:11 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow.

https://youtu.be/kXwO4d4T7fE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:38:27 </td>
   <td style="text-align:left;"> Stop Trading Options! You Are Being Scammed!

$TSLA $MRNA $AAPL $FUBO $GME

https://www.chartlearning.com/2021/09/stop-trading-options-you-are-being.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:37:10 </td>
   <td style="text-align:left;"> $WIMI $FB If the last century represented an era of mass production and the rise of the internet, the 21st century might be known for creating and expanding the virtual world or Metaverse. It promises to be far more immersive, interactive, and collaborative than what the internet has accomplished so far. $AAPL 
https://skinnerifffz85.medium.com/if-the-last-century-represented-an-era-of-mass-production-and-the-rise-of-the-internet-the-21st-4b70111ec965 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:36:33 </td>
   <td style="text-align:left;"> $AAPL Let’s start a contest.  Post the date when we cross $200.00.

1-20-22. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:36:30 </td>
   <td style="text-align:left;"> $AAPL open puts position for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:33:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-15 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=_4PLcgUrZ4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:32:36 </td>
   <td style="text-align:left;"> $AAPL Puts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:31:18 </td>
   <td style="text-align:left;"> $AAPL … 400 shares average $25 after the last split… Bullish AF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:31:16 </td>
   <td style="text-align:left;"> $AAPL another new ath possible this week... 187 on the break is what i have

Link in bio for free discord where i provide daily and pre mkt analysis with price targets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:27:24 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 221.9K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:25:19 </td>
   <td style="text-align:left;"> $AAPL PT raising my target to 210 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:22:20 </td>
   <td style="text-align:left;"> $AAPL There are any number of government officials in the US, EU, and Asia who could take 5% to 25% or so out of Apple’s profit. I have no opinion on whether all the issues I read about in the news are serious.  Remember, all this money is extracted by Capital from Labor. So I try not to get twitty.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:21:47 </td>
   <td style="text-align:left;"> $AAPL what if we gap down to $165 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:19:08 </td>
   <td style="text-align:left;"> $AAPL sick and tired of all this apple bullshit. Iphonesmone ipadbidad, aorpodfod. Fffffuuuuuuuucccc cckkkkkk!!¡!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:19:07 </td>
   <td style="text-align:left;"> $AAPL    Apple (AAPL) PT Raised to $200 at Evercore ISI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:18:00 </td>
   <td style="text-align:left;"> $AAPL 🍏👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:16:50 </td>
   <td style="text-align:left;"> $AAPL Apple Closes 3 Stores In US, Canada After COVID-19 Surge Affects Employees 

https://newsfilter.io/a/d9d6a0a2b1698d9cefd8d5f5e65fc9f5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:15:59 </td>
   <td style="text-align:left;"> $AAPL https://youth-investment-group.com/2021/12/14/apple-stock-forecast-for-2022-will-aapl-hit-210/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:14:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL triple witch friday. The fun isn’t over yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:13:41 </td>
   <td style="text-align:left;"> $AAPL 
AAPL  Trending on Twitter and Stocktwits the last 24hrs - getting some solid traction. Looking forward to a strong day tomorrow- keep an eye on the trend and what the &amp;quot;whale&amp;quot; accounts say.

https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20211215 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:13:34 </td>
   <td style="text-align:left;"> $AAPL I still think 200 is possible by January. Just my opinion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:11:30 </td>
   <td style="text-align:left;"> $QQQ ahahaha bears are still in denial. Lol. $AAPL $SPY $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:10:39 </td>
   <td style="text-align:left;"> $AAPL This company has averaged 30% per year for the last 10 years. Dumb to bet against that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:09:40 </td>
   <td style="text-align:left;"> $AAPL Bears word of advice … don’t bet against the Fed .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:08:13 </td>
   <td style="text-align:left;"> With TradesViz you can analyze all your options greeks and find the most optimal options strategy.

TradeViz leaves no data when it comes to trading performance analysis. 

Why? Your edge could be hiding in any single chart.

$SPY $$AAPL $QQQ $TSLA $STUDY

Free 👉 http://tradesviz.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:07:56 </td>
   <td style="text-align:left;"> $AAPL $170 and under by Friday. Let see if my 400 contract print big money out of bulls. 😀😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:07:40 </td>
   <td style="text-align:left;"> $AAPL normally I go into trades alone. A lone wolf you might say. But I hear this mother fucker @Jonnyzzzz is trying to join me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:07:05 </td>
   <td style="text-align:left;"> $AAPL - Next fiscal quarter end is on 31st of December 2021. Overlap studies show critical… https://www.macroaxis.com/stocks/Overlap-Studies/Weighted-Moving-Average/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:07:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL   what do you all see ? This is NASDAQ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:06:28 </td>
   <td style="text-align:left;"> $AAPL $TSLA 🚀🌙💎💎💎💎💎💎💎🖨💸💸💸💸💸💸💸💸💸💸💸💸💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:06:28 </td>
   <td style="text-align:left;"> $AAPL undervalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:05:41 </td>
   <td style="text-align:left;"> $AAPL AAPL NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:04:48 </td>
   <td style="text-align:left;"> $AAPL can y’all stfu about nio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:04:00 </td>
   <td style="text-align:left;"> $AAPL has a Profit Margin of 25.88%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:03:13 </td>
   <td style="text-align:left;"> $AAPL 

HOPING FOR THAT NIO + APPLE PARTNERSHIP TO BE TRUE.

NIO DAY IS THIS SATURDAY BTW 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:02:02 </td>
   <td style="text-align:left;"> $AAPL I’ve chugged alcohol today because of my loss on my puts today. Not afraid to admit it lol… I’m drunk af but at least now I’m able to confidently express my feelings to y’all. I was up 645% in the last 2 weeks of trading (my record) and now that 645% turned into 315%. It hurts a lot. But I’m only human and we all make mistakes. My mistake was taking a gamble on that fed talk and I’m so mad at myself because I was up $4,570 and finished off with -$5,450 because of Powell… every time that mf opens his mouth the market falls lmao but not this time and I had a bad feeling this time too. Oh well I’m ready to see that $200 now. Hopefully get my $$$ back! 190c exp 12/31! Go 🍏! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:01:58 </td>
   <td style="text-align:left;"> $DIA $SPY $AAPL $AMZN 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:00:06 </td>
   <td style="text-align:left;"> $AAPL $200 by the eoy would be a dream come true 🙏🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 11:00:05 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:58:25 </td>
   <td style="text-align:left;"> $AAPL tomorrow we find out if we rally or if it was a pump just to buy cheap puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:55:17 </td>
   <td style="text-align:left;"> $AAPL https://www.marketwatch.com/investing/stock/aapl?mod=over_search </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:54:37 </td>
   <td style="text-align:left;"> Glad I cash advanced to buy those call options yesterday. Going to be a good weekend at the craps table. $SPY $AAPL $NVDA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:51:52 </td>
   <td style="text-align:left;"> $AAPL got fucked on puts, closed @ loss and bought Disney calls in hope for miracle... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:48:31 </td>
   <td style="text-align:left;"> $AAPL bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:48:21 </td>
   <td style="text-align:left;"> $AAPL feel sorry for bears tomorrow the squeeze going to be marvelous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:48:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL never forget. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:46:21 </td>
   <td style="text-align:left;"> $SPY puts on $AAPL FOR THEIR TRASH CHARGERS 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:45:30 </td>
   <td style="text-align:left;"> $AAPL @ck6 I don&amp;#39;t always jackoff at funerals but when I do, it&amp;#39;s gonna be $AAPL&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:44:21 </td>
   <td style="text-align:left;"> $AAPL https://stocktwits.com/Stonks85/message/397941455 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:42:33 </td>
   <td style="text-align:left;"> $AAPL bought puts 400 contract. Tomorrow and Friday gonna bloody. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:42:08 </td>
   <td style="text-align:left;"> $AAPL You bears telling me this thing ran to $180 the last week to pullback to $170 and now run back to $180 just to pullback to $170 again. You Motha Fuckas are delusional 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:41:27 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:40:52 </td>
   <td style="text-align:left;"> $AAPL apple is about to spuge on you bears and shorts 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:39:33 </td>
   <td style="text-align:left;"> $AAPL To all my fellow bears 🐻… I was on your side today before the fed talk but honestly let’s be real here and agree that betting against a 3T dollar company is not the wisest move. There is many other stocks to be a bear on that’s more ideal. 🍏is just too damn strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:39:06 </td>
   <td style="text-align:left;"> $AAPL you bears are fucked! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:38:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:36:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL yes you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:36:42 </td>
   <td style="text-align:left;"> $AAPL Road to 3 Trillion tomm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:36:23 </td>
   <td style="text-align:left;"> $AAPL I’ve been trading for 5+ years and when I tell you this stock is hitting $190 before New Years plz take my word for it. I gambled today on puts and payed the price but now the rally starts with the fed talk earlier today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:34:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-15 Daily Forecast Video: 
https://www.youtube.com/watch?v=XyskSA_U-z0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:33:34 </td>
   <td style="text-align:left;"> $AAPL NEXT STOP $200.00!!!!!!!!!!!!!!!!!!!  YOU SILLY BEARS!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:29:03 </td>
   <td style="text-align:left;"> $AAPL all the people jerkin off to AAPL being up 3 percent shows this is topping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:25:43 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m always amused when cute bear clowns see Apple go down a few bucks and automatically assume it&amp;#39;s going back to $100 so they can dream of making smart investors feel stupid. Then it climbs back to record new all time highs and those princess bear clowns delete their account when they realize how much money they have lost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:25:28 </td>
   <td style="text-align:left;"> $AAPL managed to get out of my short position with a 30% gain. Was up 53% but got greedy and you bulls came in and went bonkers when I stepped away from my screen for a moment 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:25:19 </td>
   <td style="text-align:left;"> $MMAT ZERO SHARES AVAILABLE TO SHORT FROM A LEADING PRIME BROKERAGE! Take a bite off the green $AAPL #Metaverse $MMAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:24:41 </td>
   <td style="text-align:left;"> $AAPL I hope you bears learned you’re lesson today, but most of you are so stubborn we will pillage you again tomorrow for another 2%+ “puts printing” 🤡🤡 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:22:34 </td>
   <td style="text-align:left;"> $AAPL 10,000+ shares… own this for 15 years….  
 
i just can’t sell it… best company ever! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:20:58 </td>
   <td style="text-align:left;"> $AAPL let’s do the 3 trillion thingy tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:19:51 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:18:52 </td>
   <td style="text-align:left;"> $AAPL 👇🏼😂🤣😂🤣👏👏💎💎 true sto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:17:54 </td>
   <td style="text-align:left;"> $SPY oh no, there’s still retarded bears thinking their puts will print tomorrow $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:17:46 </td>
   <td style="text-align:left;"> $AAPL  pussie bears and shorts are crying 😂🤣💎💎👏👏🖕🏼🖕🏼🖕🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:15:53 </td>
   <td style="text-align:left;"> $DKNG $TSLA $AAPL Lets make one thing clear!! DraftKings will moon throughout this decade as online gaming and sports betting takes off around America, plus the NFT space!!

Get in now while you can!! 🚀🚀🚀💪🏽🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:15:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL euphoria will turn to sadness. Be cautious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:14:00 </td>
   <td style="text-align:left;"> $AAPL will not hold 3T market cap. It will sell off strongly to $165 after rallying to $182.x. This will happen as soon as tomorrow. Wait for the pullback to reenter. 

The same thing happened with tesla, msft and other big tech as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:13:19 </td>
   <td style="text-align:left;"> $AAPL I will be selling this call tomorrow , guess how many contracts I have to make over $16,000 ?! Once I sell time to go puts  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:12:53 </td>
   <td style="text-align:left;"> $AAPL 🛑🛑🛑breaking news!!   oh my! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:12:28 </td>
   <td style="text-align:left;"> $AAPL  overbought area again  like last time 181-182 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:11:51 </td>
   <td style="text-align:left;"> $AAPL got slaughtered today from buying puts. Whatever u do don’t bet against apple. All my profits from 2 weeks gone in 1 minute lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:11:28 </td>
   <td style="text-align:left;"> $AAPL plan to drop another 10k in appl,  investment for a 12 months period!!  I think now is pretty high price for entrance..??
What&amp;#39;s your thoughts?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:11:25 </td>
   <td style="text-align:left;"> $AAPL wth why features falling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:11:15 </td>
   <td style="text-align:left;"> $AAPL 
What will Apple shares be priced at when 2022 doesn’t stack up to 2021?  $300/share, I suppose…😎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:11:09 </td>
   <td style="text-align:left;"> $AAPL will be red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:10:35 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/PnSPc6KtdvE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:10:31 </td>
   <td style="text-align:left;"> $AAPL All time high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:05:47 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN $NVDA $MSTR 🎅🏼🎄🎶 All I want for Christmas is a new ATH 🎶🎄🎅🏼💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:05:23 </td>
   <td style="text-align:left;"> We called the beginning of the Christmas rally, only question is will it die out fast or how long will it last? $AMD $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:05:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL blood cometh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:04:40 </td>
   <td style="text-align:left;"> $AAPL 200 coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:04:29 </td>
   <td style="text-align:left;"> $AAPL 181-187 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 10:04:20 </td>
   <td style="text-align:left;"> $AAPL Tomorrow&amp;#39;s gonna be pumping hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:58:43 </td>
   <td style="text-align:left;"> $AAPL can we see ath tomorrow please lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:58:00 </td>
   <td style="text-align:left;"> $AAPL quick rally! Either stagnant market or dump.. with ATH , it cannot stay stagnant hence it will drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:57:42 </td>
   <td style="text-align:left;"> $AAPL $185 by Christmas 🍏✅✅🎄🎄🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:57:19 </td>
   <td style="text-align:left;"> $SPY $tsla $aapl Biden said if we finish the year under 500 he’s moving JPOWs office to a Chinese virus research 🥼 🧫 🧪 lab </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:52:49 </td>
   <td style="text-align:left;"> $AAPL got me some puts for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:52:38 </td>
   <td style="text-align:left;"> $AAPL THE WHOLE WORLD WILL BE WATCHING TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:51:25 </td>
   <td style="text-align:left;"> $AAPL, $RGLS here goes on http://www.stocksequity.com/active-stocks/eye-catching-shares-apple-inc-nasdaqaapl-regulus-therapeutics-inc-nasdaqrgls/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:51:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $T $AAPL 

What’s ironic is we filmed this in December prior to Covid. We filmed the hospital scenes at McCormick place &amp;amp; less than 3 months later that’s where the city of chicago made their make shift hospital for Covid patients. This is being released just in time for Omicron. Hollywood has a crystal ball I suppose! (I play a vaccine delivery guy in this &amp;amp; did multiple stunts). Hope y’all dig it!

https://m.youtube.com/watch?v=RaAG-SwEa7k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:50:44 </td>
   <td style="text-align:left;"> $AAPL  19.54% up since the Buy alert. check out the chart from ultraalgo below.

https://www.reddit.com/r/UltraAlgo/comments/qrn6eb/aapl_awaiting_buy_signal_stock_trading_ideas_by/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:50:08 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $GOOG $MSFT X50-X100 DD GLTA https://aabbgoldtoken.com/uncategorized/asia-broadband-sets-december-launch-date-for-proprietary-cryptocurrency-exchange/2021/12/08/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:48:52 </td>
   <td style="text-align:left;"> $AAPL future is ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:48:02 </td>
   <td style="text-align:left;"> $SPY JPOW coming in clutch with the market recovery for the holidays! $QQQ $TSLA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:47:57 </td>
   <td style="text-align:left;"> $AAPL if you are not a trader. WTF are you doing on these forums? Makes 0 sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:45:54 </td>
   <td style="text-align:left;"> $AAPL oh Aapl, you’re simply the best! 
 
3 trillion coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:44:08 </td>
   <td style="text-align:left;"> $AAPL Best company ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:43:45 </td>
   <td style="text-align:left;"> $AAPL shorts and bears just up and leave the party?? Having another one tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:42:29 </td>
   <td style="text-align:left;"> $ROKU everyones a stock expert on stocktwits. can&amp;#39;t make any money trading so yall turn to that discord money.  bahahahahaha $spy $aapl $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:37:59 </td>
   <td style="text-align:left;"> $AAPL hey shorts!!!🤑🤑🤑🤑🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:37:03 </td>
   <td style="text-align:left;"> $spy $aapl $tsla $f in other words he basically said “F yo PUTs” 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:34:34 </td>
   <td style="text-align:left;"> Dark pool after hours activity in:

$AAPL - $344M print
$QQQ - $722M print
$FB - $146M print
$MSFT - $133M print
$HYG - $122M print

#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:29:41 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on multiple timeframes.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.  Surprises can be to the upside which is why we do not like to sell it.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:29:39 </td>
   <td style="text-align:left;"> $AAPL SURE BET EVERYTIME..!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:29:34 </td>
   <td style="text-align:left;"> $AAPL buffet about the cut his apple position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:28:33 </td>
   <td style="text-align:left;"> $AAPL $190 tommorow MINIMUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:26:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL if you&amp;#39;re a &amp;quot;bull&amp;quot; you have to admit you&amp;#39;re on borrowed time. Covid was used to pump the markets to ridiculous levels because the fed fed the markets endless support but corrupt j bowell just told you the party is over and you&amp;#39;re still out here partying like it&amp;#39;s just begun lol. Insanity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:24:22 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD $ETH.X $BTC.X 

BEARS  WHAT HAPPENED TO THe “HUGE marKet crASH” after JPOW spoke  today ?????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:23:44 </td>
   <td style="text-align:left;"> $AAPL Apples about to get capitulation 
$spy $qqq $xlk $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:21:17 </td>
   <td style="text-align:left;"> Why Apple Stock Rallied Today | The Motley Fool $AAPL  https://www.fool.com/investing/2021/12/15/why-apple-stock-rallied-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:18:48 </td>
   <td style="text-align:left;"> latex520f616d580c1aef4c8605988d1cb956LLY 280c 250%
$AAPL 177.5c 165%

Live Stream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:11:01 </td>
   <td style="text-align:left;"> $AAPL Aapl can never  handle 3 Trillion now with the interest rate hikes / sales ratio 

It’s going be ugly $SPX $SPY $QQQ $XLK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:10:11 </td>
   <td style="text-align:left;"> $AAPL what is chance we see $185 by Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:09:46 </td>
   <td style="text-align:left;"> $AAPL let’s get this to $200! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:09:06 </td>
   <td style="text-align:left;"> $AAPL parabola monthly view </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:08:44 </td>
   <td style="text-align:left;"> $AAPL parabola beginning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:08:40 </td>
   <td style="text-align:left;"> $AAPL market may surprise us tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:05:34 </td>
   <td style="text-align:left;"> $AAPL
🍏
BUSINESS INSIDER: Warren Buffett&amp;#39;s Apple stake is 50% of Berkshire&amp;#39;s equity portfolio

Warren Buffett&amp;#39;s Apple stake is 50% of Berkshire&amp;#39;s equity portfolio
Berkshire Hathaway&amp;#39;s Apple holdings of 887 million shares swelled to a value of $159 billion on Friday. That makes the stake worth half of Berkshire&amp;#39;s entire equity portfolio, and almost 25% of its latexbb5512bfa4dfe983a4dabb9767905d06SHOP
$SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:03:08 </td>
   <td style="text-align:left;"> $AAPL WHAT A FUCKING DAY, LMAO. Day’s gain, by the way… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:03:00 </td>
   <td style="text-align:left;"> The industry average ROE is 22.20%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:02:06 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;d love to see Apple Car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:02:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-15 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=_4PLcgUrZ4Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:02:00 </td>
   <td style="text-align:left;"> $AAPL looks like an early morning pop to a possible 181 and fade to 178 area. Eod ah tug of war with shorts initiated again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:00:30 </td>
   <td style="text-align:left;"> $AAPL 

Today touch $180

Tomorrow another day… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:00:27 </td>
   <td style="text-align:left;"> $AAPL https://apple.news/A9YfxtUPHRgCjt3tzGj0aJA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 09:00:07 </td>
   <td style="text-align:left;"> $AAPL Simulated 182.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:59:28 </td>
   <td style="text-align:left;"> $AAPL 182.85$ here we come :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:59:06 </td>
   <td style="text-align:left;"> $AAPL DONT BE A BAG HOLDER FOR THE NEXT 5 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:58:22 </td>
   <td style="text-align:left;"> $AAPL buy high sell low right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:57:29 </td>
   <td style="text-align:left;"> $AAPL let’s go bears 🐻 Do your magic . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:56:30 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL if you&amp;#39;re a bull you are mentally handicapped and that&amp;#39;s ok. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:56:12 </td>
   <td style="text-align:left;"> $AAPL Santa rally started today. $200 eoy, bank on it and enjoy the gift of JPOWW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:55:49 </td>
   <td style="text-align:left;"> $AAPL  Please buy higher tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:54:08 </td>
   <td style="text-align:left;"> $AAPL people who really thinks their tweets gonna make difference to stock price 🤡🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:53:32 </td>
   <td style="text-align:left;"> $AAPL ATH tomorrow LFG!! 🍏📈🚀💰💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:51:34 </td>
   <td style="text-align:left;"> $AAPL get some </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:48:17 </td>
   <td style="text-align:left;"> $AAPL  190 Calls ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:47:42 </td>
   <td style="text-align:left;"> $BKKT and $AAPL Dec 15th…https://www.bakkt.com/blog/consumer/tap-into-crypto-with-bakkt-and-apple-pay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:47:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL j bowell literally told you all he is speeding up tapering which means the fed is PULLING their monetary support aka market propping and you&amp;#39;re all running into the market with reckless abandon lol. Make your money but you can&amp;#39;t be that stupid to think the markets will keep going up. The covid mania party is wrapping up quickly. Be careful. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:46:59 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL $DIA $QQQ  🧞‍♂️

Apple closed three stores in the United States temporarily due to Covid outbreaks in the surrounding areas

Lock downs pretty much right Apple? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:46:29 </td>
   <td style="text-align:left;"> $AAPL 👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:45:22 </td>
   <td style="text-align:left;"> $AAPL Who buying calls tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:45:21 </td>
   <td style="text-align:left;"> $AAPL big push tmw to break new highs tmw. Will be very interesting to see. Glad I sold my puts! $200 apple 🍎 here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:43:27 </td>
   <td style="text-align:left;"> $AAPL hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:43:18 </td>
   <td style="text-align:left;"> $AAPL bears basically lost everything today buying puts before the fed $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:42:56 </td>
   <td style="text-align:left;"> $AAPL 
Remember when JPM increased the price target and Apple went to 182? Well fed worries are gone. This is going up. 
I WANT TO SEE 185 BY FRIDAY!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:42:15 </td>
   <td style="text-align:left;"> $AAPL Any connection to Bakkt https://www.reddit.com/r/wallstreetfools/comments/rh2kjj/bakkt_and_apple_pay_finally/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:42:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL BULLS WON TODAY BUT BEARS ALWAYS EAT 😤😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:41:39 </td>
   <td style="text-align:left;"> $AAPL got me some Dec 31 puts at the end of day 🙊🙈, price came back around to load up more bag holders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:39:27 </td>
   <td style="text-align:left;"> $AAPL wait did this really touch 181.00
After hours? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:38:52 </td>
   <td style="text-align:left;"> $AAPL bears are fucking pissed right now ignore them this leads the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:37:16 </td>
   <td style="text-align:left;"> $AAPL I know it’s a $3T company, but what the stock price % growth projection is going to be for the next 3-4 years? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:37:07 </td>
   <td style="text-align:left;"> $AAPL 💥💥💥💥💥💥💥💥💥💥💥💎💎💎💎💎💎💎💎💎💎💎💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:36:29 </td>
   <td style="text-align:left;"> $AAPL 190c on Friday- please get there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:36:05 </td>
   <td style="text-align:left;"> $AAPL sold have my short position prior to the fed speaking. Once stocks reversed I immediately regretted not closing the entire position. That is until I saw just how much they decided to pump this. This is now a massive bubble. Not a matter of Id but a matter of when. (Wouldnt be anything more than a 10-12% correction dragged out over multiple days). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:33:54 </td>
   <td style="text-align:left;"> $AAPL gonna get hit hard when they post q4 earnings due to supply chain issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:33:11 </td>
   <td style="text-align:left;"> $AAPL btw, just got my first apple watch recently. 5/5 if you are willing to look for good apps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:32:50 </td>
   <td style="text-align:left;"> $AAPL Overextended again. Expect a pull back to 20 EMA in 30 min chart before buying again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:32:41 </td>
   <td style="text-align:left;"> $AAPL yeah, Apple keeps going someone like me, one of those suckas refuse to use other brands no matter what - for more than two decades. 😭MacBook Pro, Airpod, iPad.... I ordered iPhone 13 Pro Max 1TB, still waiting for.... confession from a suckka. 😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:32:12 </td>
   <td style="text-align:left;"> $AAPL look at the chart and tell me it doesn’t tell you it will go little down !! 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:30:48 </td>
   <td style="text-align:left;"> $AAPL  Who’s buying more 🍎 tomorrow morning at 183 to cover their puts???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:26:42 </td>
   <td style="text-align:left;"> $AAPL wish option market was open for calls… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:26:07 </td>
   <td style="text-align:left;"> $AAPL ya gotta. A lot of suckas out there that blindly buy their products. Hey, I&amp;#39;ll continue to trade it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:25:50 </td>
   <td style="text-align:left;"> $AAPL 200$ inevitable :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:25:36 </td>
   <td style="text-align:left;"> $AAPL how wrong I was 👇🏻;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:23:24 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:20:32 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $NVDA $TSLA https://apple.news/APfOuINLMTaay4Nm17jcr_g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:20:17 </td>
   <td style="text-align:left;"> $AAPL $200 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:19:48 </td>
   <td style="text-align:left;"> $AAPL come on baby make it $200 eom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:19:44 </td>
   <td style="text-align:left;"> $AAPL bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:18:00 </td>
   <td style="text-align:left;"> $AAPL, $TMO and $KEYS are amongst the strongest stocks in the market, nearing a new high. https://www.chartmill.com/stock/stock-screener?sid=16&amp;amp;f=p_pg10,v1_50b500,s_str,s_nnh,exch_us&amp;amp;v=3&amp;amp;timeframe=DAILY&amp;amp;type=CANDLES&amp;amp;months=0.05&amp;amp;width=720&amp;amp;cl=F&amp;amp;o1=3&amp;amp;o2=3&amp;amp;o3=1&amp;amp;op1=200,16711680&amp;amp;op2=50,255&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_Strong_Stocks_near_New_High&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:16:21 </td>
   <td style="text-align:left;"> $AAPL 175p 1.75-4.05 (+150%) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:16:16 </td>
   <td style="text-align:left;"> $SPY $AAPL If markets are not res next two days, 💯 bubble which could break with 10-15% correction in JAN. Desperately entered Tesla calls . Got to exit tomorrow. Fuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:15:28 </td>
   <td style="text-align:left;"> $AAPL  SHORT SQUEEZE TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:15:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple is delaying return to office indefinitely: report https://www.stck.pro/news/AAPL/19783262 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:13:04 </td>
   <td style="text-align:left;"> $AAPL 

https://stocktwits.com/c/newsletters/the-daily-rip/issues/2021/12/15/jpow-drops-the-mic

This is good read!!

Jerome Powell decision would help to strengthen US dollars meaning all the stocks that are priced at cheap USD are attractive buy…

Hence blunt inflation which hurts USD and economy. 

This helps the institutional investors to unlock more money into cheaper stocks valued in USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:13:01 </td>
   <td style="text-align:left;"> $AAPL why go back to the office when you bout to break 3 trill!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:12:21 </td>
   <td style="text-align:left;"> $AAPL Bingo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:12:01 </td>
   <td style="text-align:left;"> $AAPL FUCK YOUR PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:10:22 </td>
   <td style="text-align:left;"> $AAPL me sitting on all these puts right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:09:58 </td>
   <td style="text-align:left;"> $AAPL very nice. Glad i bought this 2 years ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:09:03 </td>
   <td style="text-align:left;"> $AAPL $190 is obtainable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:08:30 </td>
   <td style="text-align:left;"> $AAPL tomorrow easy 3T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:08:29 </td>
   <td style="text-align:left;"> $SPY $AAPL They really want that 3 trillion dollar market cap and they will get it. What happens next is anyone&amp;#39;s guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:07:47 </td>
   <td style="text-align:left;"> $TSLA trying to break down tend AH! Might pull an nvda if she’s able to! $NVDA $SPY $AAPL  PUMP IT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:07:27 </td>
   <td style="text-align:left;"> $MSFT 12/17 $330c bought @2.50
 $AAPL 12/23 $180c bought @3.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:07:25 </td>
   <td style="text-align:left;"> $AAPL proud 3T , market will make it happen tomorrow (182.6) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:05:23 </td>
   <td style="text-align:left;"> $AAPL double top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:04:27 </td>
   <td style="text-align:left;"> $AAPL would it be dumb to buy a bunch of 12/31 200 calls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:03:16 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA  best trading day in my 5 years of experience. What a day 🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:02:19 </td>
   <td style="text-align:left;"> $AAPL https://seekingalpha.com/article/4475237-apple-stock-is-now-a-bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:02:10 </td>
   <td style="text-align:left;"> $AAPL 

https://www.teslarati.com/tesla-will-not-honor-retroactive-full-self-driving-pricing-model-y/?fbclid=IwAR3XEcZobxcrdXsiffB7CIAA4euKdnHLz3aM9jV0LyjERAfzKSlaWpzpK10

Hurry up AAPL to step up the autonomous game and challenge TSLA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:02:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-15 Trade Analysis Video: 
https://www.youtube.com/watch?v=lhAk49c-gq0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:01:53 </td>
   <td style="text-align:left;"> $AAPL awesome day everything in my portfolio green.....😁😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:01:41 </td>
   <td style="text-align:left;"> $AAPL gave a nice double bottom at $172.50 on the hrly that was the opportunity to go long or cover your short before the face ripper to $180 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 08:01:03 </td>
   <td style="text-align:left;"> $AAPL  I have no need to pump this company If it go to $80 dollars I still make money  I brought into this years ago  
Going back to 2008! In the group I write 
Don’t trade Apple 🍎 invest in $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:59:58 </td>
   <td style="text-align:left;"> $TQQQ $SPXL $AAPL $UNH  today it feels good to be a long term bull, who knows what tomorrow will bring… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:59:38 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:59pm)

⦿ $AAPL is down 0.0% in the last 5 mins. 

⦿ There are 11 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 13.9% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:59:34 </td>
   <td style="text-align:left;"> $AAPL Easy trade today based on 5 min supply and demand zones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:58:05 </td>
   <td style="text-align:left;"> $AAPL I can see a short squeeze in the cards tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:57:06 </td>
   <td style="text-align:left;"> $AAPL Oh when will those silly bears learn how risky it is to short AAPL? When they lose all there money? $200 here we come! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:56:20 </td>
   <td style="text-align:left;"> $AAPL $BA $TSLA 
Bears in a world of hurt

https://youtube.com/shorts/2nwOnWDI-Fg?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:55:56 </td>
   <td style="text-align:left;"> $SPY $BTC.X $TGGI  $ETH.X $AAPL 
Happy Thursday. Hope everyone has a great rest of the week and I know you’re having an  amazing day. Welcome to the revolution welcome to the good life. I hope y’all get rich and all your dreams come true. Remember never give up on your convictions, n always   double down when you know they’re coming  true💯💯💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:55:54 </td>
   <td style="text-align:left;"> $AAPL tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:53:51 </td>
   <td style="text-align:left;"> $AAPL history in the making. Who’s NOT sleeping tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:53:21 </td>
   <td style="text-align:left;"> $AAPL 3 trillion market cap by selling same phone over n over again 🤦🏼‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:52:15 </td>
   <td style="text-align:left;"> $AAPL $175 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:52:04 </td>
   <td style="text-align:left;"> $SPY  $AMD $AAPL $BTC.X $NVDA  

WE FLYING ALL WEEK! looks like I better call the office!  I ain’t coming the rest of the week! I’ll be in an island in the Bahamas sipping margaritas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:51:23 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ Yet again “Everyone is a genius in a bull market”… Pathetic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:51:19 </td>
   <td style="text-align:left;"> Stocks Jump As Volatility Dumps Post #FOMC $QQQ $AAPL $SPX $VIX https://talkmarkets.com/content/stocks--equities/stocks-jump-as-volatility-dumps-post-fomc?post=337978 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:51:15 </td>
   <td style="text-align:left;"> $AAPL This thing has been ripping the last few weeks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:51:12 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 207.0K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:51:12 </td>
   <td style="text-align:left;"> $SPY

ATH tomorrow?

$AAPL $AMZN should reach ATH too!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:50:39 </td>
   <td style="text-align:left;"> $AAPL another ath coming up i guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:50:14 </td>
   <td style="text-align:left;"> $AAPL 3 trillion coming b!tche$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:49:50 </td>
   <td style="text-align:left;"> $AAPL and imagine the iphone …ipad …..monitoring all your medical needs ….to be sent to a computerized medical center for evaluation and immediate response to your medical needs… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:49:40 </td>
   <td style="text-align:left;"> @investclem1682 $AAPL

Finally got my account reinstated after dealing with ST ..

I better be careful with word … 

Anyways, it was a fun ride with bulls whole day from starting two hell days ago to blue sky today .. I am happy for all of you bulls staying together.

We have lots of work to do and make sure we celebrate once we touched and stayed at 3T. It will be helluva ride.

Look forward to it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:49:26 </td>
   <td style="text-align:left;"> $AAPL 
🍏
VOLUME AH 9.158.923. 
In The Air. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:48:56 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:48:32 </td>
   <td style="text-align:left;"> $AAPL gimme that ATH I wanna see $182.5 so those calls print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:46:48 </td>
   <td style="text-align:left;"> $AAPL 

Is Powell making mortgage payments if you have an iPhone? What did he say for it to pop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:46:36 </td>
   <td style="text-align:left;"> $AAPL 163% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:46:01 </td>
   <td style="text-align:left;"> $AAPL Apple giving employees $1,000 equipment bonus isn&amp;#39;t enough for the cheapest macbook but you can get a stand. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:45:41 </td>
   <td style="text-align:left;"> $AAPL -$4-$5 tomorrow, Friday at the latest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:44:28 </td>
   <td style="text-align:left;"> $SPY $TSLA $NVDA $AAPL $FB 

My thoughts on the market action today .... 

On Monday I got bearish, and I sent email alerts out to subscribers starting in my pre-mkt commentary. I had a target of 465 on the SPY and then 461/461.5. We dropped 100 handles from 470.5 to 460.5 - just under my target. 

Yesterday I got more optimistic. And I even came on this site (SEE BELOW) mentioning we would likely see a &amp;quot;sell the rumor, buy the news&amp;quot; rally that could take us right back above 470. 

I do this for a living. And my subscribers have come to rely on my technical insight and learn what to look for in the charts. I put an enormous amount of time and effort into my work to provide the highest quality of content I can. 

Thank you to all of you who have continued to follow. For those interested in joining, feel free to email me at jessielivermore1929@gmail.com 

It was a great day for bulls ( AAPL, TSLA, FB, NVDA) . A great bounce of lows. We will see if momentum can continue ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:44:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA $AAPL $AMZN Bears really thought this was their year for a Santa rally. ATH coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:44:01 </td>
   <td style="text-align:left;"> $AAPL 182.5C 12/23…
Anyone else? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:42:55 </td>
   <td style="text-align:left;"> $AAPL @Snowball2013 how many shares do you have now? Your an OG here iv noticed 

I don&amp;#39;t trade apple I just buy hold and own never sell...assume your the same? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:41:58 </td>
   <td style="text-align:left;"> $AAPL +535% in last 5 years,  not bad. Best days ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:40:15 </td>
   <td style="text-align:left;"> $AAPL the world is better prepared for any pandemic... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:39:31 </td>
   <td style="text-align:left;"> $AAPL like duh! We have this pandemic for almost 2yrs! If they close stores let people buy online. It’s not new </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:39:02 </td>
   <td style="text-align:left;"> $AAPL wow Crossed 180..250 here i come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:38:44 </td>
   <td style="text-align:left;"> $AAPL so what if they’re closing stores. People can always order online </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:38:36 </td>
   <td style="text-align:left;"> $AAPL hello $180.00 ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:38:30 </td>
   <td style="text-align:left;"> $DWAC So during the reg Session with ever real company like $aapl &amp;amp; $amzn fell while $dwac was up, now in the AH when real companies are seeing more buying $dwac is dropping.

You can&amp;#39;t make this scam up :o) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:38:22 </td>
   <td style="text-align:left;"> $AAPL For all you WWF OGs, $AAPL this week is essentially Hulk Hogan coming back to life after getting knocked down.  We know how those matches ended. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:38:10 </td>
   <td style="text-align:left;"> $AAPL c’mon man! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:37:11 </td>
   <td style="text-align:left;"> $AAPL omg are we seeing 190$ tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:36:15 </td>
   <td style="text-align:left;"> $AAPL keep buying my top dollar shorts… couple bull balls in there.  🥰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:35:28 </td>
   <td style="text-align:left;"> #OptionsPlaybookRadio 393: Reducing Your Pandemic Risk In $PFE with @BrianOverby is now available. On this episode, Brian first looks at last week&amp;#39;s FOMO long-term in-the-money call in $AAPL. Then he follows that up by exploring how a similar trade in $PFE can help you reduce some of your pandemic risk.  Download from your preferred #podcast provider or listen now via http://traffic.libsyn.com/playbook/OPR_12-15-21_-_FINAL.mp3
#OptionsEducation #EducationWednesday #optionsTrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:35:17 </td>
   <td style="text-align:left;"> $AAPL get out the🍿 bears sad delusional stories and projections  incoming all that negativity y&amp;#39;all spread comes back 10x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:35:11 </td>
   <td style="text-align:left;"> $AAPL 
🍏
$180.16
+$0.88
+0.49%
——————————————————
NASDAQ. GO TO +135 Points =+0.88%
For Apple +1.23%AH. 
Closed $179.30
+$2.21
$181.51. Easy
—————————————————— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:34:56 </td>
   <td style="text-align:left;"> $AAPL what to do cone Friday Jan Feb 
I think saint marks sun and fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:34:32 </td>
   <td style="text-align:left;"> $MRNA I&amp;#39;ve got so caught up with life that I was thinking Xmas is in 2weeks instead of next week...

So... That unfortunately means I can&amp;#39;t be too sure of my bearish statements since I am a believer of the Xmas rally.

My bad 😞😔

$AAPL $MRNA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:33:56 </td>
   <td style="text-align:left;"> $AAPL bears are so screwed 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:33:13 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;puts printing&amp;quot; ladies&amp;quot;????
🙊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:33:08 </td>
   <td style="text-align:left;"> $AAPL gosh dam Christmas rally. I dgaf. I&amp;#39;ll cum out on top or go down swinging. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:32:59 </td>
   <td style="text-align:left;"> $AAPL 

Today was a fun ride .. enjoyed the sip of coffee and watched the movement - first it was red territory - (clearly it was BTD) and FOMC came at 2 PM … boom now it end with nearly $5.00

Clearly, it’s like beauty of magic - just boom another $120 billion into the pocket of AAPL.

It’s like a lot of bulls felt good about it, so I do. 

We have long way to go with metaverse and Autonomy for 2022! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:32:55 </td>
   <td style="text-align:left;"> $ibm  
if we get a deal with $AAPL to get those new chips for phones, which allows phones to go a week without charging IBM will be worth 4x as much today in the future. Those same chips could also be extended into gaming and possibly crypto mining </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:30:50 </td>
   <td style="text-align:left;"> $AAPL looks like $185 tomorrow then $200 by the end of next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:30:23 </td>
   <td style="text-align:left;"> $AAPL AAPL sling shot move to 👉185.00 Tomorrow to Boost $SPY 
🍎Most Action and Highest Volume Leader in Tech Land </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:30:08 </td>
   <td style="text-align:left;"> $AAPL Remember, history has shown that Long-term being bearish has only lost money. Instead of panic selling, now is the time to buy, nibble, &amp;amp; accumulate. Position yourself for Xponential gains long-term in Apple - https://youtu.be/btBGZB5Fak0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:29:57 </td>
   <td style="text-align:left;"> $AAPL Going to have catalyst after catalyst for years to come. Green apples for everyone!🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:29:56 </td>
   <td style="text-align:left;"> $AAPL too high… way too fast.. not normal…expect a dip tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:29:54 </td>
   <td style="text-align:left;"> $AAPL Just opened a short again @180.30 GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:29:23 </td>
   <td style="text-align:left;"> $AAPL this Friday will be fun at All times high! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:29:18 </td>
   <td style="text-align:left;"> $AAPL   🍏 VIX, Closed under 20. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:28:29 </td>
   <td style="text-align:left;"> $AAPL The bigger they are the harder they fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:28:05 </td>
   <td style="text-align:left;"> $AAPL waiting for it to retrace from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:27:58 </td>
   <td style="text-align:left;"> $AAPL 🚨lets give all you folks 45 and under some info🚨
If you had 300 shares in 1987 you now have 72,000 shares exclusive of 63,000 bucks a year dividend
Those 72,000 shares are worth 12,816,000 bucks 
So when you invest…take your time buy a little bit and hold…there will never be a regret… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:27:13 </td>
   <td style="text-align:left;"> $AAPL whoa!!! Someone’s face got ripped off today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:26:59 </td>
   <td style="text-align:left;"> $AAPL agree or disagree this market is all wackadoodle? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:26:50 </td>
   <td style="text-align:left;"> $AAPL   🍏 AfterHours, 180.10. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:26:36 </td>
   <td style="text-align:left;"> $AAPL love your bull balls.  I plan to be one as well (a bull ball! As a 🌈 🐻 ). Going Shoooooooort!!! Until that opportunity arises.  Carry on bullion’s! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:25:44 </td>
   <td style="text-align:left;"> $AAPL how did we do today??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:25:33 </td>
   <td style="text-align:left;"> $AAPL Maybe I’ll close some tomorrow and put in that iPad order. Need to decide between Air or Mini. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:24:48 </td>
   <td style="text-align:left;"> $AAPL 

Let’s all party all together bulls when we hit and stayed at 3T.

Cheers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:24:32 </td>
   <td style="text-align:left;"> $AAPL bear eats poops. Tomorrow $185.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:24:26 </td>
   <td style="text-align:left;"> $AAPL Hellooo 180s!🎉🍾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:24:19 </td>
   <td style="text-align:left;"> $AAPL AH accumulation 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:24:01 </td>
   <td style="text-align:left;"> $AAPL I like the hype </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:23:47 </td>
   <td style="text-align:left;"> $AAPL I like money. Your first 100k is the hardest... the rest is inevitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:23:38 </td>
   <td style="text-align:left;"> $AAPL so mad I didn&amp;#39;t buy that cheap $180 call when it hit $172 smh .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:22:47 </td>
   <td style="text-align:left;"> $NFLX $SPY $QQQ $AAPL  BouuGht ThiS BaD BoY eaRlier… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:22:42 </td>
   <td style="text-align:left;"> $AAPL keep adding crazy easy $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:22:39 </td>
   <td style="text-align:left;"> $AAPL think I’m going to host a 3T watch party tomorrow 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:21:34 </td>
   <td style="text-align:left;"> $AAPL MARKET CAP 2.94T USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:21:15 </td>
   <td style="text-align:left;"> $AAPL I sold my biggest position on Friday made 25k off my calls i just had to sell. Now I’m blasting under the bridge by RHCP cus this shit could hit 200 this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:21:00 </td>
   <td style="text-align:left;"> $AAPL 
🍏
Scalping $180.27
+$0.97+0.54%. 
Go to +2% AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:20:08 </td>
   <td style="text-align:left;"> $AAPL ahahah wheres all the 🌈🐻 that was hoping the fed meeting tanked it some more? 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:20:01 </td>
   <td style="text-align:left;"> $ROKU buy and hold iOS of the television. This is your $MSFT $AAPL $AMZN $NFLX  chance you missed years ago. Don’t let it pass you “buy” long since pre ipo and adding since. We see $680 in 3 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-16 07:19:25 </td>
   <td style="text-align:left;"> $AAPL 183 than 185+ then 198+ then 210, than $240 after 5 - 1 split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:51:49 </td>
   <td style="text-align:left;"> $TSLA very soon… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:50:17 </td>
   <td style="text-align:left;"> $TSLA tomorrow gonna sky rocket premarket 1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:48:45 </td>
   <td style="text-align:left;"> $TSLA Expecting 1500+ by EOY

🙂👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:47:51 </td>
   <td style="text-align:left;"> $TSLA This Meme Coin Named After Elon Musk&amp;#39;s Pet Is Up 734% , Outshining Dogecoin and Shiba Inu 

https://newsfilter.io/a/00b7ec2be7c10b5707f1dc8d1128d34b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:46:35 </td>
   <td style="text-align:left;"> $NIO $CALT $TSLA $50,000 a day keeps the 9 to 5 away. Big thanks to this chat...   https://www.discord.io/xEvE2Aatrp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:45:29 </td>
   <td style="text-align:left;"> $LCID $TSLA $NKLA $RIVN if you don’t sell, you don’t lose! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:43:58 </td>
   <td style="text-align:left;"> $TSLA this thing will be well over $1000 by open tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:42:05 </td>
   <td style="text-align:left;"> $TSLA this guy always makes me feel good about being a tesla long term holder.  https://youtu.be/l3VBK4t7HN4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:41:18 </td>
   <td style="text-align:left;"> $TSLA if TSLA breaks the 1009 level buyers will be coming in buy the boatload imo. 1161 target for tomorrow after 1009 breaks

Link in bio for free discord where i provide daily and pre mkt analysis with price targets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:40:43 </td>
   <td style="text-align:left;"> latexc5bb7c2c20ee7245f3ed18d85fb6ac5f at open then a run to 1,045$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:38:35 </td>
   <td style="text-align:left;"> Equity Sentiment: $TSLA is the #4 stock that institutions are trading with 32.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:38:27 </td>
   <td style="text-align:left;"> Stop Trading Options! You Are Being Scammed!

$TSLA $MRNA $AAPL $FUBO $GME

https://www.chartlearning.com/2021/09/stop-trading-options-you-are-being.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:36:43 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow.

https://youtu.be/ragUzxB8hP4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:34:16 </td>
   <td style="text-align:left;"> $TSLA but but who will have cash to give to doge daddy now??? Lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:33:32 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-15 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=Y-GVX10r1hw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:33:14 </td>
   <td style="text-align:left;"> Jim Chanos about to get his short position crushed by $DKNG the same way $TSLA crushed him last year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:33:05 </td>
   <td style="text-align:left;"> $TSLA contrarion, we might be too bullish , seems weird . let&amp;#39;s see what happens tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:32:36 </td>
   <td style="text-align:left;"> latex3979ccf5cf922070122c623390b92bb5NVDA
$MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:29:32 </td>
   <td style="text-align:left;"> $TSLA Breaking: @Reddit has submitted a draft registration with the SEC to go public. 

In August, the company raised $700 million at a valuation in excess of $10 billion. In the second quarter of 2021, Reddit reached $100 million in advertising revenue, +192% year-over-year. Yoooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:28:23 </td>
   <td style="text-align:left;"> $TSLA     https://youtu.be/1NroxTz-Pn4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:27:01 </td>
   <td style="text-align:left;"> $TSLA Tomorrow should be green. With that being said, I expect around $1,030-$1,050 range at close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:23:23 </td>
   <td style="text-align:left;"> Noteworthy Wednesday Option Activity: $TSLA, $COOP, $RSI https://www.billionaireclubcollc.com/noteworthy-wednesday-option-activity-tsla-coop-rsi/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:22:16 </td>
   <td style="text-align:left;"> $TSLA 😂 tesla drivers admit their time has come when they receive their 15th est. delivery date </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:18:48 </td>
   <td style="text-align:left;"> $TSLA my time has come! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:18:44 </td>
   <td style="text-align:left;"> $TSLA cathie wood regreting selling now lol I think that move to shitty hot  Florida fucked up her game.  nothing like nyc home of the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:18:41 </td>
   <td style="text-align:left;"> $ARKK $ARKW $ARKF $TSLA $PLTR The .618 held and today was basically a double bottom bounce off of a key support level.  Past three weeks have seen heavy volume with little price movement week by week so we may see a huge run up here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:17:40 </td>
   <td style="text-align:left;"> $GGPI $TSLA  polestar beating tesla Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:16:18 </td>
   <td style="text-align:left;"> $XRP.X $TSLA $DWAC $CFVI exposing  SEC lies and institutional corruption </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:15:35 </td>
   <td style="text-align:left;"> $TSLA this is how dumb you idiots really are !  Elon isn’t CCP , he’s American as apple pie 🥧- lol 😂 he’s not ! And will sell you and anybody out including share holders if that keeps his stupid space x funded ! He may be rich AF ! But hes still answering to somebody !  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:15:33 </td>
   <td style="text-align:left;"> $LCID Rawlinson has proved the point that he was chief engineer of model S. Musk was lying.

History will remember this Great rivalry $TSLA 

https://twitter.com/elonmusk/status/1303495330223198208?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:15:07 </td>
   <td style="text-align:left;"> $TSLA Tesla haters -&amp;gt;  crying out loud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:14:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL triple witch friday. The fun isn’t over yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:14:38 </td>
   <td style="text-align:left;"> $TSLA what’s the word here tomorrow? We mooning again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:13:51 </td>
   <td style="text-align:left;"> $TSLA Total Recall 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:13:49 </td>
   <td style="text-align:left;"> $TSLA bears looking a little panicky. What’s wrong?🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:12:53 </td>
   <td style="text-align:left;"> $TSLA Reversal in the works to send this to $1200 plus! This 💰maker is on my radar along with other tasty treats!! Thanks for this one @RiskVsReward !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:11:25 </td>
   <td style="text-align:left;"> $TSLA GO GIGA | Tesla Giga Principle of Cost Control 

https://youtu.be/esa7iC0MOJ8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:11:10 </td>
   <td style="text-align:left;"> $TSLA 

TSLA  Trending on Twitter and Stocktwits the last 24hrs - getting some solid traction. Looking forward to a strong day tomorrow- keep an eye on the trend and what the &amp;quot;whale&amp;quot; accounts say.

https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20211215 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:10:22 </td>
   <td style="text-align:left;"> $TSLA Wall Street ends higher; FOMC to end QE bond purchases in March 2022 ; Three (3) QT hikes 2022 http://www.streetinsider.com/ETFs/Wall+Street+ends+higher%3B+Fed+to+end+bond+purchases+in+March/19353194.html via @Street_Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:10:19 </td>
   <td style="text-align:left;"> $TSLA #nio  
 
nioday is saturday. Hedge funds shorted it to 29. Now they jump in and ride wave back up. Get in to. Morning for quick 15-20 percent gain by Monday mid day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:08:45 </td>
   <td style="text-align:left;"> $TSLA what a nice eod. Bullish, everything looks so bullish! 

Must be a red day tomorrow then. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:08:13 </td>
   <td style="text-align:left;"> With TradesViz you can analyze all your options greeks and find the most optimal options strategy.

TradeViz leaves no data when it comes to trading performance analysis. 

Why? Your edge could be hiding in any single chart.

$SPY $$AAPL $QQQ $TSLA $STUDY

Free 👉 http://tradesviz.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:08:12 </td>
   <td style="text-align:left;"> $TSLA did Elon sell today?? Thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:07:04 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL   what do you all see ? This is NASDAQ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:06:58 </td>
   <td style="text-align:left;"> $TSLA not-for-Jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:06:50 </td>
   <td style="text-align:left;"> Cathie Wood Sells Another $88M In Tesla Day After Piling Up Stake In Chinese EV Rival  $TSLA $ARKK $ARKW $XPEV $ROKU 

https://newsfilter.io/a/84d55251165840a00b24164fa6d31d22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:06:28 </td>
   <td style="text-align:left;"> $AAPL $TSLA 🚀🌙💎💎💎💎💎💎💎🖨💸💸💸💸💸💸💸💸💸💸💸💸💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:04:47 </td>
   <td style="text-align:left;"> $TSLA I just love Elon Musk being honest with the media. We need more people speaking up for America. Elon is not from the USA by the way. Why is it that home grown billionaires are such complicit pussies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:04:47 </td>
   <td style="text-align:left;"> $TSLA Simulated 985.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:04:39 </td>
   <td style="text-align:left;"> $TSLA don’t be surprise if tomorrow’s PM high is the day’s high. A fade the rest of the day…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:04:26 </td>
   <td style="text-align:left;"> $TSLA

Enjoy the Thursday Relief Rally Longs!! 
-----------------------------------------------------
 Wall Street ends higher; FOMC to end QE bond purchases in March 2022 ; Three (3) QT hikes 2022 http://www.streetinsider.com/ETFs/Wall+Street+ends+higher%3B+Fed+to+end+bond+purchases+in+March/19353194.html via @Street_Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:04:09 </td>
   <td style="text-align:left;"> $TSLA I say Tesla retakes 1000 tomorrow. Called the drop from 1120 to sub 1k, but it’s time for a rebound </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:02:19 </td>
   <td style="text-align:left;"> $TSLA MUSKY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:01:54 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood is egregiously overrated and a Jesus freak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:01:24 </td>
   <td style="text-align:left;"> $AMZN $SQ $PYPL $TSLA Inflation hits Tech Stocks Again https://www.billionaireclubcollc.com/inflation-hits-tech-stocks-again/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:01:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Cathie Wood Sells Another $88M In Tesla Day After Piling Up Stake In Chinese EV Rival https://www.stck.pro/news/TSLA/19788554 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 11:00:45 </td>
   <td style="text-align:left;"> $SPY let me ask you something- do you really want to rely on iOT to do everything for you ???? 🤷‍♂️  

Am I the only guy that does everything manually and laughs at people who do everything from their phone ? This is how they Emasculate the male population , you do it because it’s easier not smarter - let me guess your father never came back with milk like he promised 😂 $TSLA  YOUR KIDS WILL BE JUST AS FUCKED UP ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:59:55 </td>
   <td style="text-align:left;"> $TSLA lol so cathie woods sells sub 1k when she coulda sold at 1.2k and she’s supposed to be a genius in the market? Lol ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:59:28 </td>
   <td style="text-align:left;"> $RIDE $FCEL $TSLA $RMO $PLUG https://www.barrons.com/articles/cheap-small-company-stocks-51636763053 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:58:50 </td>
   <td style="text-align:left;"> $TSLA lfg tessie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:57:19 </td>
   <td style="text-align:left;"> $TSLA oh well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:57:15 </td>
   <td style="text-align:left;"> $TSLA Bears checking the stock price at the AH close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:57:11 </td>
   <td style="text-align:left;"> Tesla Motors, Inc. (NASDAQ: $TSLA), ( $ARKK) – Cathie Wood Sells Another $88M In Tesla Day After Piling Up Stake In Chinese EV Rival  latex8566f9ec421839b0a32138e49ed3f47bBA Calls &amp;gt; 197 | Puts &amp;lt; 195
$UPST Calls &amp;gt; 160 | Puts &amp;lt; 141

Last watchlist payed. 🚨👀

Check my bio for more. Constantly giving out bangers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:49:31 </td>
   <td style="text-align:left;"> $TSLA Feds check their Tesla Brokerage account before meeting. Feds make correct decision.  Tesla Brokerage account healthy again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:49:16 </td>
   <td style="text-align:left;"> $TSLA So what Elon got divorced he gets to keep sentiment if he can keep custody according to the original bill of rights 1787 Elon will be president. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:48:52 </td>
   <td style="text-align:left;"> $TSLA I learned to code 🤦‍♂️ I’m a software computer programmer specialist! I press keys all day - the world 🌎 should worship me ! I DRIVE AN ELECTRIC CAR POWERED BY COAL LOL  YET you still can’t find her G spot 🤪 and your soft ass hands got her identifying as a lesbian 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:48:01 </td>
   <td style="text-align:left;"> $tsla $spy so when does Elon become head of the fed and make Dogecoin a reserve currency? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:47:43 </td>
   <td style="text-align:left;"> $TSLA So many bears but really at the end of the day, TSLA is going to make NEW HIGHS, this is a dip opportunity, come through link in bio if you are LONG TSLA. All TSLA holders there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:47:25 </td>
   <td style="text-align:left;"> $TSLA $1015 @ open tomorrow or higher? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:46:53 </td>
   <td style="text-align:left;"> $TSLA no filing yet, every day he doesn’t sell makes it more likely statistically that it could be tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:46:11 </td>
   <td style="text-align:left;"> $TSLA when ever Elon announces that he sold the minimum amount required to exercise his expiring options and he is now done and won’t sell another share for 5 years, we will see 1500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:46:00 </td>
   <td style="text-align:left;"> $TSLA: The EPS is expected to grow by 51.00% on average over the next 5 years. This is a very strong growth. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:44:57 </td>
   <td style="text-align:left;"> $TSLA why so many bears ??? This is clearly going up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:43:05 </td>
   <td style="text-align:left;"> $TSLA Most people get divorced because of a lack of commitment the remainder say they married to young. Elon married for shareholder sentiment in the younger generation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:42:41 </td>
   <td style="text-align:left;"> $TSLA 🐻 not gone no where </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:42:21 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:41:53 </td>
   <td style="text-align:left;"> $TSLA trash....again! Tomorrow and Friday will put the nail in this once and for all 870 boys...short again tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:39:26 </td>
   <td style="text-align:left;"> $PLTR Cathie $ARKK sold almost 2M share today ; and still keep adding $HOOD !! Weird thing is that she kept saying $tsla going 3K while she keep selling every day last couple months 😉 
She should follow me ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:38:36 </td>
   <td style="text-align:left;"> $TSLA Does Elon sell tomorrow I bet he does! B careful if not this will go to 1050-1060 area my opinion only </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:38:30 </td>
   <td style="text-align:left;"> $TSLA tomorrow me please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:38:21 </td>
   <td style="text-align:left;"> $TSLA A merry Christmas will be to wake up to a $1 T market cap tomorrow and close on 12/23 at $1150 or higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:38:20 </td>
   <td style="text-align:left;"> $TSLA 
Anyone know off hand what the short float is here right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:38:05 </td>
   <td style="text-align:left;"> $TSLA Giddy bears gone. Now just pouty bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:37:06 </td>
   <td style="text-align:left;"> 🔥Watchlist for Thursday #4:
1) $CPIX (Gapper potential)
2) $ESSC (Higher lows forming ww)
3) $SPY (Strong bounce, going higher )
4) $TSLA (Should test 1010+ next)
5) $GMTX (vwap reclaim can see 3.50+)

Market back GREEN🟢🥵 Be ready to hit bangers and bank, gave you guys BFRI runner early this morning. More coming tomorrow, stay tuned..🛎️🛎️🛎️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:37:00 </td>
   <td style="text-align:left;"> If everyone got to see the Lucid Air with their own eyes, they&amp;#39;d understand why they would see it as Tesla&amp;#39;s closest competitor

$LCID $TSLA 

https://vocal.media/wheel/if-everyone-got-to-see-the-lucid-air-with-their-own-eyes-they-d-understand-why-they-would-see-it-as-tesla-s-closest-competitor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:36:40 </td>
   <td style="text-align:left;"> $tsla $BTC.X 🦄👑 into 1393.8 vs right shoulder of bahhhcoin into 2023??  Ain’t bullish.  It’s fookin bahhhish!  ❤️🐒🍌 🖕🐑

❤️👑🌈🦄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:34:34 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-15 Daily Forecast Video: 
https://www.youtube.com/watch?v=6RCazU5z0ck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:34:26 </td>
   <td style="text-align:left;"> $NKLA $TSLA $JBHT $SNDR $SWFT
Let&amp;#39;s a second to bury some more Diesel Engine&amp;#39;s and Diesel Particular Filter DPF systems.⚡🔋🙋
He&amp;#39;s coming and his first name is Nikola... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:33:25 </td>
   <td style="text-align:left;"> $TSLA Tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:32:51 </td>
   <td style="text-align:left;"> $TSLA  keep  thinking &amp;amp; believing you’re saving the world 🌎! Lol 😂 your wife knows you’re incapable of fixing anything mechanically driven , but you keep Simp’n and donating to cancer research 🔬 🧐  , 🤦‍♂️ FYI cancer doesn’t respond to walking btw $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:32:18 </td>
   <td style="text-align:left;"> $TSLA what price target tomorrow 1050? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:31:55 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:30:44 </td>
   <td style="text-align:left;"> $TSLA $1,500 this time next year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:29:54 </td>
   <td style="text-align:left;"> $TSLA $NVDA $AMD JPow for president!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:29:19 </td>
   <td style="text-align:left;"> $TSLA I am taking all my crabass comments back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:25:54 </td>
   <td style="text-align:left;"> $TSLA - job well done by the fed’s 😬

Nice coverage on what we can expect next..

https://youtu.be/8NP8aD8gHSc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:25:53 </td>
   <td style="text-align:left;"> $TSLA why does your pp look like you just came. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:25:14 </td>
   <td style="text-align:left;"> $TSLA whoa… just saw this on $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:24:26 </td>
   <td style="text-align:left;"> Top UOA of the day 🔮
$TSLA buyer $1.4 Million worth of the 2/18 1100 calls 

$CLF buyer $1.3 Million worth of the 2/17 21 calls 

$EXPE buyer $1.1 Million worth of the 6/17 170 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:22:54 </td>
   <td style="text-align:left;"> $TSLA when you peel back the layers and look at  Teslas over valuation foe what it really is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:21:54 </td>
   <td style="text-align:left;"> $TSLA What a relief to see a green closing, look like  the start of a Bull Run 🏃‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:19:55 </td>
   <td style="text-align:left;"> $TSLA wouldn&amp;#39;t buy this scam bubble even it was $200. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:18:21 </td>
   <td style="text-align:left;"> $SPY show or hands 🙌 for the men that still change oil and work on their own  cars ? $TSLA I know you Barbie bitches don’t do shit! Your wife / GF knows you’re a pussy but loves the free chicken tendies you keep serving up ! SIMP 😂 I’ll catch her later when you’re at work slaving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:18:04 </td>
   <td style="text-align:left;"> $TSLA Elon is a scammer, sold Tesla shares after pumping it to the peak then move the money to dogecoin and then pump it with the news that telsa will use dogecoin for transactions… he should be put to jail! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:17:26 </td>
   <td style="text-align:left;"> $TSLA the fools keep buying as musk won&amp;#39;t stop selling LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:15:53 </td>
   <td style="text-align:left;"> $DKNG $TSLA $AAPL Lets make one thing clear!! DraftKings will moon throughout this decade as online gaming and sports betting takes off around America, plus the NFT space!!

Get in now while you can!! 🚀🚀🚀💪🏽🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:15:14 </td>
   <td style="text-align:left;"> $RIDE honestly as a long term investor, it saddens me that this clown is taking 600k a year and up to 1.2 mill if he gets bonuses , all he does is talk about tesla, seriously someone needs to tell this goof, that our bleeding $ is what feeds him, not thinking he looks cool promoting $TSLA had to be said and I said it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:14:21 </td>
   <td style="text-align:left;"> $TSLA  Can&amp;#39;t stop won&amp;#39;t stop

https://youtu.be/R5taDnVikIo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:13:52 </td>
   <td style="text-align:left;"> $TSLA truth hidden https://youtu.be/PnSPc6KtdvE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:12:11 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:11:38 </td>
   <td style="text-align:left;"> $TSLA Futures are red, if Elon sells in the morning RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:11:28 </td>
   <td style="text-align:left;"> $TSLA 🚨 🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:09:57 </td>
   <td style="text-align:left;"> $TSLA Hey if Elon up and died tomorrow would you sell your Tesla shares? If yes, even you think it&amp;#39;s overvalued... just saying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:09:42 </td>
   <td style="text-align:left;"> $TSLA Elon just admitted to being a big fan of Dilbert that alone gets us to 1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:08:22 </td>
   <td style="text-align:left;"> $TSLA so what’s next to be scared of bears? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:07:11 </td>
   <td style="text-align:left;"> $TSLA trending! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:07:02 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-15 Largest Trades Data: 
https://www.youtube.com/watch?v=nsw4Q8egS-o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:06:52 </td>
   <td style="text-align:left;"> $SPY Excellent earnings report today! CEO Powell’s statements helped her rip during power hour!  I’m expecting continuation going into tomorrow! Pamp it! $TSLA   $NVDA $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:05:47 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN $NVDA $MSTR 🎅🏼🎄🎶 All I want for Christmas is a new ATH 🎶🎄🎅🏼💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:04:21 </td>
   <td style="text-align:left;"> $TSLA parked right at $990…how convenient </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:02:43 </td>
   <td style="text-align:left;"> $TSLA hello bears, where are you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:01:48 </td>
   <td style="text-align:left;"> $TSLA, $QD here goes on http://www.stocksequity.com/active-stocks/may-this-data-fuel-up-investors-confidence-tesla-inc-nasdaqtsla-qudian-inc-nyseqd/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:01:08 </td>
   <td style="text-align:left;"> $TSLA I’m glad I decided to slowly start here at 945$. 🤑 I love Elon! 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 10:00:55 </td>
   <td style="text-align:left;"> $TSLA I talked shit all day. And it went my way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:59:35 </td>
   <td style="text-align:left;"> $TSLA 20$ soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:57:19 </td>
   <td style="text-align:left;"> $SPY $tsla $aapl Biden said if we finish the year under 500 he’s moving JPOWs office to a Chinese virus research 🥼 🧫 🧪 lab </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:56:21 </td>
   <td style="text-align:left;"> $TSLA retest 1060 tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:56:19 </td>
   <td style="text-align:left;"> Thursday Watchlist Part 2: 🎅

1) $AMC
2) $SOFI 
3) latex4cc09cf9bc5038c8a0e053473aa52978BA Calls &amp;gt; 197 | Puts &amp;lt; 195
$UPST Calls &amp;gt; 160 | Puts &amp;lt; 141

Check my bio for more. Constantly giving out bangers. 💸🤝 seasonal rally almost upon us and you want to be with us to take full advantage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:54:56 </td>
   <td style="text-align:left;"> $TSLA watch oceans 8
Smooth criminal aww for sandy bullock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:54:15 </td>
   <td style="text-align:left;"> $TSLA I have been trimming a lot but let’s rally!!! A rising tide raises all ships or something like that. Lmao! Still my biggest holding!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:54:08 </td>
   <td style="text-align:left;"> $TSLA Wednesday is or was depending where youre at the last day of sell-off for Elon as the employee blacout period starts untill the earnings report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:54:03 </td>
   <td style="text-align:left;"> $TSLA https://www.bloomberg.com/news/articles/2021-12-15/nypd-eyes-order-of-250-teslas-as-city-pushes-to-electrify-fleet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:53:35 </td>
   <td style="text-align:left;"> $TSLA When Bears loaded with tons of puts, what will market makers do? Just siding with bulls to get rid of value in those puts. Be careful bears....It is nothing but reversal of what happened to bulls a week ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:52:21 </td>
   <td style="text-align:left;"> $TSLA when are earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:50:26 </td>
   <td style="text-align:left;"> $TSLA $700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:50:08 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $GOOG $MSFT X50-X100 DD GLTA https://aabbgoldtoken.com/uncategorized/asia-broadband-sets-december-launch-date-for-proprietary-cryptocurrency-exchange/2021/12/08/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:48:11 </td>
   <td style="text-align:left;"> $TSLA 

🔥NIO DAY IS JUST 2 DAYS AWAY, 10 THINGS THAT COULD HAPPEN🔥

1. NIO will reveal 2 New Electric Vehicles
2. Rumored Apple Partnership. Apple is looking to adopt a drivetrain from someone and NIO is number 1
3. NIO will offer an affordable EV to compete with the Model 3
4. NIO is creating a Newer Brand under NIO
5. NIO is partnering with LeasePlan 
6. NIO will be Dual Listed in the U.S.A and Hong Kong. Dual listing are known to drive up share prices by a substantial amount
7. NIO is launching its ET7 Sedan on NIO Day
8. NIO has other possible partnerships
9. Unknown NIO surprises
10. Timeline of when NIO Plans to expand into the United States. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:48:02 </td>
   <td style="text-align:left;"> $SPY JPOW coming in clutch with the market recovery for the holidays! $QQQ $TSLA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:46:59 </td>
   <td style="text-align:left;"> $TSLA remember back in 2021 when you could still buy Tesla for under $1000/share? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:44:33 </td>
   <td style="text-align:left;"> $tsla Elon only encourages the hopeful which is different than cheerleading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:44:23 </td>
   <td style="text-align:left;"> $TSLA won’t be surprised if Tesla phone is announced soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:43:42 </td>
   <td style="text-align:left;"> $TSLA buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:42:29 </td>
   <td style="text-align:left;"> $ROKU everyones a stock expert on stocktwits. can&amp;#39;t make any money trading so yall turn to that discord money.  bahahahahaha $spy $aapl $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:42:19 </td>
   <td style="text-align:left;"> $TSLA been asleep for the past 12 hours, thefuq happened </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:40:11 </td>
   <td style="text-align:left;"> $TSLA Bears… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:39:17 </td>
   <td style="text-align:left;"> $TSLA still expecting lots of volatility tomorrow with assumed Leon selling w it being Thur. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:38:39 </td>
   <td style="text-align:left;"> $TSLA 1/29 conspiracy  fri jan 28th last chance to dance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:38:09 </td>
   <td style="text-align:left;"> $TSLA would love to see 1070 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:37:27 </td>
   <td style="text-align:left;"> $TSLA is it today last day we see it at 900+ ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:37:03 </td>
   <td style="text-align:left;"> $spy $aapl $tsla $f in other words he basically said “F yo PUTs” 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:36:17 </td>
   <td style="text-align:left;"> $TSLA is Elon done selling...this is not ripping as people are cautious including me...didn’t want to jump in today and get stuck in ladder selling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:34:48 </td>
   <td style="text-align:left;"> $TSLA anyone remember the closing price when Elon announced the first split? Wasn’t it around 1200+ range? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:33:57 </td>
   <td style="text-align:left;"> $TSLA zamnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:31:05 </td>
   <td style="text-align:left;"> $TSLA she always bounces back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:28:25 </td>
   <td style="text-align:left;"> $TSLA no </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:28:15 </td>
   <td style="text-align:left;"> $TSLA Stock split hypothesis: to discourage a profit-taking sell-off between Christmas and the new year, what if Musk announces a split to occur in January 2022, benefiting &amp;quot;shareholders of record on 12/31/2021?&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:28:06 </td>
   <td style="text-align:left;"> $LCID should be getting $tsla money rest of week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:27:54 </td>
   <td style="text-align:left;"> $SHOP ===&amp;gt; THIS FUCKER WILL EXPLODE TOWARDS END OF YEAR.   FASTEN YOUR SEATBELTS  THE  STOCK MARKET &amp;quot;SANTA RALLY&amp;quot;  IT&amp;#39;S  ON!!!!!  $SPY  🔥🔥🚀🚀🚀
.
$TSLA  $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:27:23 </td>
   <td style="text-align:left;"> $TSLA $QQQ My hindsight is 20/20. Bears expected bad news with doom and gloom. The market was prepping for it. They were wrong. Now they gotta cover for the XMAS rush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:25:46 </td>
   <td style="text-align:left;"> $TSLA Tesla (TSLA): A taxi company suspends Tesla fleet, according to Electrek </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:25:33 </td>
   <td style="text-align:left;"> $TSLA Fuck it. Putting my entire portfolio on the line on weekly calls. Tired of being a peasant. 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:25:31 </td>
   <td style="text-align:left;"> $TSLA just hoping this hits 1k tomorrow to sell calls against my position. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:23:19 </td>
   <td style="text-align:left;"> $TSLA 65 min. stochastics recently crossed bullish and daily is extreme oversold but hasn&amp;#39;t crossed yet.  Long run coming IMO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:23:18 </td>
   <td style="text-align:left;"> $TSLA fed done so now gotta roll with the flow. 1014-1065 possible soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:23:13 </td>
   <td style="text-align:left;"> $TSLA lets strong hold!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:23:09 </td>
   <td style="text-align:left;"> $TSLA 🥺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:22:26 </td>
   <td style="text-align:left;"> $SPY I can’t believe bears thought 💭 money printer Powell was going to tell the world 🌎 the market is too high &amp;amp; THERES NO HOPE 🤦‍♂️ - He’s a FED NOT CCP ELON MUSK 😂 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:22:23 </td>
   <td style="text-align:left;"> $TSLA Three major pumped and dumped so far. Bears or Bulls, get money!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:21:28 </td>
   <td style="text-align:left;"> $TSLA take it easy boys, we need to still see next day.  This last afternoon was a nice PUMP by BEARS, but MF Elon will sell more of his stock and you will all now what will happen.  Stay off until he finish selling.  We can see this bellow $900 any time soon.  Hope I am wrong.  I am shit loaded with CALLS...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:19:13 </td>
   <td style="text-align:left;"> $TSLA 

Stop blaming @elonmusk for 24% drop in the stock — 5.6m shares don’t cause a stock to lose 300b in value !! 

Currently short HFs think they can outsmart the man who put America back in the space and defame him like some of our clowns 🤡 in the senate do on Twitter daily , think again !! 

The current low entry in SP is a gift from @elonmusk to you and made possible by these insufferable numbskulls (as planned)!! 

Be grateful and happy, when you revisit my post a yr from now you most likely will understand why!! 

🙏🏻🐉🦅 imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:16:57 </td>
   <td style="text-align:left;"> $TSLA 1100 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:14:46 </td>
   <td style="text-align:left;"> $TSLA calm down you can do this tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:13:26 </td>
   <td style="text-align:left;"> $TSLA all «dip-buyers» who believes sub 1000$ is a massive steal😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:11:15 </td>
   <td style="text-align:left;"> $TSLA back up to $1200 soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:10:06 </td>
   <td style="text-align:left;"> $TSLA     $CALT 

Mid week gains with @TWOWSofficial </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:09:55 </td>
   <td style="text-align:left;"> $MCO2.X  
 
$TSLA  make all of their profits from Carbon Credits not the 500 or 600k cars they sell - ALL OF IT FROM SELLING CARBON CREDITS  
 
in 2020 natural disasters created 210 BILLION USD in global damages up 26.5% from 2019  
 
https://www.investopedia.com/natural-disasters-cost-usd210-billion-worldwide-in-2020-5094629 
 
all of Australia was on fire, California and Oregon.  
Earthquake and Tsunami in Greece and Turkey, Puerto Rico 
Hurricane Eta Honduras, Guatemala, Mexico, El Salvador, Panama, Nicaragua and Costa Rica 
Cyclones Amphan in India Phillipines Bangladesh  
 
to name a few... 
 
https://www.usnews.com/news/best-countries/slideshows/here-are-10-of-the-deadliest-natural-disasters-in-2020?slide=11 
 
offsetting carbon emissions is the new Gold standard and something that EVERY corporation will be paying- Microsoft has plans to go carbon negative in 2030, Amazon Carbon Neutral in 2045 (greedy ass appropriating Bezos) and many more to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:08:44 </td>
   <td style="text-align:left;"> $TSLA decent chance I don’t sleep tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:04:18 </td>
   <td style="text-align:left;"> $TSLA why sec is not going after the corrupt lawmakers but going after musk, satya? Totalitarianism is in full practice in US. Funded by Soros and gang. https://www.businessinsider.com/we-are-free-market-economy-pelosi-rejects-stock-ban-congress-2021-12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:04:10 </td>
   <td style="text-align:left;"> $SV we may looking NUSCALE as the  next $TSLA of electrical grid. Decarbonization without this kind of projects is not possible. It may take some time to get there, contracts are secured, more countries are coming for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:03:43 </td>
   <td style="text-align:left;"> $TSLA Us bulls have been beaten so bad the last couple weeks we’re acting like it doubled today. Up $30 a share. Not complaining, just a reminder how quickly it can change. Stay “humbull”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:03:42 </td>
   <td style="text-align:left;"> $TSLA Simulated 985.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:03:32 </td>
   <td style="text-align:left;"> $TSLA shorts phuket 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:03:22 </td>
   <td style="text-align:left;"> $TSLA Investors gobbled up tech stocks Wednesday (Tesla, Amazon, Google) even as the Federal Reserve took a hawkish stance 

https://www.bloomberg.com/news/articles/2021-12-15/big-tech-bulls-are-vindicated-even-after-fed-pulls-the-trigger?sref=pHyhiApD via @markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:03:16 </td>
   <td style="text-align:left;"> $TSLA  $1000 then 1100  and soon $1400 friends Enjoying the ride? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:02:41 </td>
   <td style="text-align:left;"> $TSLA 

Show me $2k by Christmas💰💰💰💸💸💸💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:02:39 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-15 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=Y-GVX10r1hw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:02:06 </td>
   <td style="text-align:left;"> $TSLA will be down $5 pm tomorrow morning.  🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:01:47 </td>
   <td style="text-align:left;"> $TSLA those $1000 naked calls that the MM’s sold, will make this fly tomorrow… They are toast! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:01:40 </td>
   <td style="text-align:left;"> $TSLA wild shit AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:01:37 </td>
   <td style="text-align:left;"> $WISH The shtonk has 100x wish local partners as $TSLA  has dealerships, where you at Elon? $TWTR  us baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 09:00:56 </td>
   <td style="text-align:left;"> $Tsla $msft why exec only, and not law makers like Pelosi? https://apple.news/A3u1_X1jXRL6Y9Tw3t06l5w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:59:56 </td>
   <td style="text-align:left;"> $TSLA few seconds to go don&amp;#39;t miss the train </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:59:40 </td>
   <td style="text-align:left;"> $TSLA my bull spread may not be fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:59:21 </td>
   <td style="text-align:left;"> $TSLA bears never learn, period </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:58:31 </td>
   <td style="text-align:left;"> $TSLA LUCID2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:58:29 </td>
   <td style="text-align:left;"> What Happened to the Stock Market Today?  J Powell makes market go ham! $TSLA, $PFE, $AMD, $NVDA https://youtu.be/GQ9LfI8YI68 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:58:01 </td>
   <td style="text-align:left;"> $TSLA  Set it and forget it. See you at $1400 friends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:57:35 </td>
   <td style="text-align:left;"> latexa90264d50b32a7330c7a014c9e2e619e 12/17 calls for 5$ did I buy a 10 bagger ???!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:57:34 </td>
   <td style="text-align:left;"> $TSLA &amp;amp; $AMZN PUMP 📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:57:07 </td>
   <td style="text-align:left;"> $TSLA My calls not giving AF about your puts. &amp;amp; Not feeling bad about it. 

https://youtu.be/B9FzVhw8_bY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:56:55 </td>
   <td style="text-align:left;"> $TSLA Strong bounce at $950 support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:56:52 </td>
   <td style="text-align:left;"> $FUBO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:56:51 </td>
   <td style="text-align:left;"> latexb8e522d4cafb363ee1e9be732147dcbcGM
$F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:55:12 </td>
   <td style="text-align:left;"> $SPY $SHIB.X $ETH.X $CRO.X $TSLA 

Rippin rounds and making money! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:54:03 </td>
   <td style="text-align:left;"> $TSLA it’s the time Tsla run 
It’s been hard time for our investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:54:02 </td>
   <td style="text-align:left;"> $TSLA stupid bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:52:18 </td>
   <td style="text-align:left;"> $TSLA just imagine Elon sells in the morning, then tweets &amp;quot;Im done, merry christmas everyone&amp;quot;
stock will go PLAID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:51:56 </td>
   <td style="text-align:left;"> $TSLA 2025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:51:40 </td>
   <td style="text-align:left;"> $TSLA so glad I kept adding leaps! Never thought I would get a solid opportunity like this dip to leverage at a good price. I think this portfolio exceeds $1m in 2022 😁 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:51:20 </td>
   <td style="text-align:left;"> $TSLA so long as volatility for this stays Tesla is a great play to day trade 🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:50:18 </td>
   <td style="text-align:left;"> $BTC.X $TSLA $MARA $RIOT $ETH.X 

 if you know what this store is like this post. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:49:43 </td>
   <td style="text-align:left;"> $TSLA when will Tesla come out with their own phone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:49:40 </td>
   <td style="text-align:left;"> $TSLA short pump ⛽ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:49:34 </td>
   <td style="text-align:left;"> $TSLA Bears Tesla is heading to $1400.  In simple words, giving me your money. Merry Christmas suckers. LoL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:48:53 </td>
   <td style="text-align:left;"> $GGPI &amp;quot;Polestar Announces 270-Mile EPA Range, Power Upgrades, and Efficiency Aids for Polestar 2 Electric Fastback Variants&amp;quot;

- Polestar, the pure play, premium electric car company, today announced the Polestar 2 Long range Single motor received one of the best ratings in its class by the U.S. Environmental Protection Agency (EPA) an estimate range of 270 miles. 
$TSLA $GOEV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:48:41 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:48:08 </td>
   <td style="text-align:left;"> $TSLA usted sabe que Tesla puede bajar $100 en un dia👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:48:06 </td>
   <td style="text-align:left;"> $TSLA hope our man won’t play with our sentiments and start selling again in the morning, if it holds well till noon then we got this bulls 🦾🦾🦾🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:47:26 </td>
   <td style="text-align:left;"> $tsla 1020 will be key level to break tomorrow 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:45:07 </td>
   <td style="text-align:left;"> $TSLA best stock, not going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:45:00 </td>
   <td style="text-align:left;"> $TSLA has an average volume of 27281900. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/TSLA?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:44:38 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:44:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:43:52 </td>
   <td style="text-align:left;"> $GGPI Take that $TSLA. 😆 

https://www.autonews.com/automakers-suppliers/polestar-2-single-motor-variant-gets-270-mile-range-topping-tesla-model-3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:43:32 </td>
   <td style="text-align:left;"> $TSLA sell those 1000 weekly calls at open. you got lucky, but dont push your luck too much. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:43:31 </td>
   <td style="text-align:left;"> $TSLA 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:42:41 </td>
   <td style="text-align:left;"> $TSLA as of right now I don’t want to hear anymore bear bullshit ok. You guys should have made a fortune the last few days. Let’s not be heartless and greedy this holiday with all the craziness going on. I’m making money both ways.  So stop with the bs collapse shit. If your short and fucked right now, that’s your poor decision. Anyone who post Bear shit right now is a straight up 🤡🤡🤡🤡😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:42:14 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m kicking and screaming for selling half of my calls. I should have been greedy and quadruple my money oh well can&amp;#39;t win them all... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:42:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL BULLS WON TODAY BUT BEARS ALWAYS EAT 😤😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:41:30 </td>
   <td style="text-align:left;"> $TSLA $AMD 😂🤣😂 so anyone that has to do layoffs!!! Do what this CEO did 🤣😂🤣👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:41:22 </td>
   <td style="text-align:left;"> $TSLA so basically rates are going up and no social spending deal,  very positive! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:41:16 </td>
   <td style="text-align:left;"> $TSLA play halo infinite </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:41:07 </td>
   <td style="text-align:left;"> $LAC holds the 30 level tomorrow, she can rocket to 36 by end of this week, 
And 45 plus by end of the year, provided $TSLA also remains smoking Hot. 

Good timer for small account, and less volatility 😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:41:05 </td>
   <td style="text-align:left;"> $TSLA overvalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:40:52 </td>
   <td style="text-align:left;"> $TSLA  $1400 soon friends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:40:02 </td>
   <td style="text-align:left;"> $TSLA recovering like the beast it already is with so much not potential! Thanks to @RiskVsReward for catching the bottom on this one! Next stop $1400!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:39:04 </td>
   <td style="text-align:left;"> $TSLA futures are ripping lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:38:32 </td>
   <td style="text-align:left;"> $TSLA $1,150 tomorrow 
R U agree? 🤣 
Needs 100 likes 👍🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:38:25 </td>
   <td style="text-align:left;"> $TSLA 
$1000 call next week expiring 
What’s it worth? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:37:37 </td>
   <td style="text-align:left;"> $TSLA 24 month wait list on a product must mean this company is in trouble right? 1st variant &amp;quot;pre owned&amp;quot; Model 3&amp;#39;s selling for +$15K original purchase price? Must mean they&amp;#39;re shitty cars and nobody wants them. CEO became richest man in the universe in a matter of years? Must be a failure of a human being.

I ask this with absolute seriousness. What the unholy fuck is the bear thesis here? 

The entire world has been rendered obsolete by Tesla, which stands alone as the producer of the only product worth your time, attention and money.

Change my fucking mind. You won&amp;#39;t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:37:33 </td>
   <td style="text-align:left;"> EVery Hydrogen Highway EV Hyvia is another RETIRED DIRTY DIESEL!!! 
 
 
When are the USA INVESTORS going to understand that $plug Power is the EV of EVerything? 
 
$f $tsla  
https://www.sustainabletruckvan.com/hyvia-ceo-david-holderbach-interview/?fbclid=IwAR1EnW1fFuWyiYPl-x6If9Y3tR0BuT495o6HfgHUa2crM2oO9BZUfojHmCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:37:21 </td>
   <td style="text-align:left;"> $LITM This company might get bought out before they even start drilling dependent on the analysis of the ongoing drone survey of the land. Companies like Tesla need as much lithium as possible for all their ongoing projects $TSLA $LAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:35:46 </td>
   <td style="text-align:left;"> $TSLA if we wake up to 1000 tomorrow in Premarket, it will be an easy 1050 by end of day, maybe we see 1110 by end of the week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:34:22 </td>
   <td style="text-align:left;"> $TSLA Investors gobbled up megacap tech stocks Wednesday even as the Fed took a more hawkish stance than expected, doubling the pace of stimulus rollbacks and projecting three rate hikes next year.

Apple Inc. was an example. The world’s largest company by market value is roughly 2% short of hitting a $3 trillion valuation. Megacap peers Microsoft  and Google also rallied off day’s lows and were about 5% away from their all-time highs. The tech-heavy Nasdaq 100 was the best performing major average, rising 2.4%.

The strength in those stocks in the face of hawkish Fed commentary shows how much investors want to own high-quality companies with track records of profit growth even with the risk of rising rates

https://www.bloomberg.com/news/articles/2021-12-15/big-tech-bulls-are-vindicated-even-after-fed-pulls-the-trigger?sref=pHyhiApD via @markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:33:08 </td>
   <td style="text-align:left;"> $TSLA $1200 EOW? 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:31:57 </td>
   <td style="text-align:left;"> $TSLA display recall imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:30:32 </td>
   <td style="text-align:left;"> $TSLA  Cramer says the Santa Claus rally may have started early this year. Here&amp;#39;s why  https://cnb.cx/3FcbWa8 

CNBC’s Jim Cramer said Wednesday it’s possible stocks begin their potential Santa Claus rally a bit ahead of schedule this year.
After the Fed’s decision, the “Mad Money” host said he does not see anything that could “derail the market” through year-end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:30:05 </td>
   <td style="text-align:left;"> $TSLA noticed something - the board is so clean without bears...damn idiots are so loud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:29:19 </td>
   <td style="text-align:left;"> $TSLA where from here kids? Buys only? 🤣😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:29:12 </td>
   <td style="text-align:left;"> $TSLA shorts got what they deserved today the amount of disrespect they show , they really think the are some jokers from Batman. Fact of the matter is most of them tasted KARMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:28:34 </td>
   <td style="text-align:left;"> $TSLA took a small little flyer today on the dip on 5 call options.. hopefully they will be juicy in the morning. Wish I would have gone in more heavy.. all profits over to $CLEU massive upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:28:09 </td>
   <td style="text-align:left;"> $TSLA could the US govt ban autopilot ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:28:05 </td>
   <td style="text-align:left;"> $TSLA hey bears just checking to see if you are ok??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:27:47 </td>
   <td style="text-align:left;"> $TSLA im Cramer says the Santa Claus rally may have started early this year. Here&amp;#39;s why  https://cnb.cx/3FcbWa8 

CNBC’s Jim Cramer said Wednesday it’s possible stocks begin their potential Santa Claus rally a bit ahead of schedule this year.
After the Fed’s decision, the “Mad Money” host said he does not see anything that could “derail the market” through year-end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:27:39 </td>
   <td style="text-align:left;"> $TSLA whoever swung puts are dumbasses hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:27:37 </td>
   <td style="text-align:left;"> $TSLA hey maybe Giga Berlin opening will be delayed to 2023 or even 2025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:27:09 </td>
   <td style="text-align:left;"> $TSLA poor shorts!! It was most likely going to 850 BUT now.....bad luck for the shorts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:27:06 </td>
   <td style="text-align:left;"> $TSLA nice bounce but is Elon Musk really retiring soon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:26:48 </td>
   <td style="text-align:left;"> $TSLA get F*CKED shortzes🤣🤣😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:26:39 </td>
   <td style="text-align:left;"> $TSLA pete bootyfudger a real flunkie...a failed mayor in south bend and a even bigger clown as transportation sec...call it like it is ELON... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:26:38 </td>
   <td style="text-align:left;"> $TSLA Investors gobbled up megacap technology stocks Wednesday even as the Federal Reserve took a more hawkish stance than expected, doubling the pace of stimulus rollbacks and projecting three rate hikes next year.

Apple Inc. was the hot pick, rising as much as 2.9%. The world’s largest company by market value is roughly 2% short of hitting a $3 trillion valuation. Megacap peers Microsoft Corp. and Google-owner Alphabet Inc. also rallied off day’s lows and were about 5% away from their all-time highs. The tech-heavy Nasdaq 100 was the best performing major average, rising 2.4%.

The strength in those stocks in the face of hawkish Fed commentary shows how much investors want to own high-quality companies with track records of profit growth even with the risk of rising rates, according to Michael Mullaney, director of global market research at Boston Partners. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:25:22 </td>
   <td style="text-align:left;"> $TSLA I see 1020 tomorrow no doubt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:24:40 </td>
   <td style="text-align:left;"> $TSLA where we go one, we go all 💯 https://m.youtube.com/watch?v=I-eN_ZDVfjs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:24:22 </td>
   <td style="text-align:left;"> $TSLA the jig works!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:24:13 </td>
   <td style="text-align:left;"> $TSLA Investors gobbled up megacap tech stocks Wednesday even as the FOMC took a hawkish stance  

https://www.bloomberg.com/news/articles/2021-12-15/big-tech-bulls-are-vindicated-even-after-fed-pulls-the-trigger?sref=pHyhiApD  

Apple again closing in on $3 trillion mark despite hawkish Fed
Investors well-positioned for stimulus pullback, rate hikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:24:01 </td>
   <td style="text-align:left;"> $SHINJA.X https://youtu.be/jmLGpJWWU-A $TSLA $BNB.X $ETH.X $MATIC.X SHIBNOBI SPACE X BILLBOARD AND THE CUP AND HANDKE BREAK OUT IMMINENT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:23:49 </td>
   <td style="text-align:left;"> $TSLA Paris taxi firm suspends Tesla fleet after fatal accident 
https://www.cnn.com/2021/12/15/tech/tesla-paris-taxi-fatal-accident/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:23:20 </td>
   <td style="text-align:left;"> $TSLA didn&amp;#39;t you Tesla Fanboys listen to the Fed&amp;#39;s announcement today? In layman&amp;#39;s terms, the Fed said money printer go bye-bye in March 2022. No more brrrrrrrr. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:23:06 </td>
   <td style="text-align:left;"> $TSLA Oh my god. If I was a put holder, I would be regretting for not cashing out when this hit 920 and running with my money. Hubris is the demise of the unwise. TSLA can be volatile, but don&amp;#39;t buy the notion that Elon will &amp;quot;sell&amp;quot; this to the bottom and lose his &amp;quot;Trillion dollar&amp;quot; influence or the title of the &amp;quot;richest man&amp;quot;. The guy is still a maniac who loves attention.  Whenever it drops too low, his MM friends will prop it up. 

TSLA will close at 1100 by EOY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:22:32 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;...is recalling about 11,700 Model S, Model 3 and Model X vehicles, and 2020 to 2021 Model Y vehicles, because a communication error with the software may cause unexpected activation of the emergency brake system, according to a notice filed with the National Highway Traffic Safety&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:20:32 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $NVDA $TSLA https://apple.news/APfOuINLMTaay4Nm17jcr_g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:20:09 </td>
   <td style="text-align:left;"> $TSLA theres a lot of things you could respect Elon for but lately for me its the way he&amp;#39;s been giving the assclowns running the country a big FUCK YOU... keep it up Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:20:05 </td>
   <td style="text-align:left;"> $TSLA Fed&amp;#39;s Powell said doesn&amp;#39;t expect to raise int-rates  until QE taper is complete (March 2022) http://www.streetinsider.com/Fed/Feds+Powell+said+doesnt+expect+to+raise+rates+until+taper+is+complete/19356158.html via @Street_Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:19:52 </td>
   <td style="text-align:left;"> $TSLA Told U opening at 1k+ tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:19:19 </td>
   <td style="text-align:left;"> $TSLA bam... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:18:55 </td>
   <td style="text-align:left;"> $TSLA if you know you know! 331 PE! fools gold! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:18:43 </td>
   <td style="text-align:left;"> $TSLA Green to red move:  +1.37% to -1.53%  
 https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=greentoredDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:18:34 </td>
   <td style="text-align:left;"> $TSLA 

So if you recall someone said will close over latexe6cea32b92833403863442992808b69a$ bull do NOT mislead ppl just because you disposed your shares or some of your shares hoping to catch it at a lower entry — seriously !

🙏🏻🦅🐉👀
PT$1425-$1509 🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:17:50 </td>
   <td style="text-align:left;"> $TSLA remember bulls, whatever happens, just HOLD
TSLA is a stock that is VERY volatile, it can flip $50-100 down and in the next minute go $50-100 up.  if it goes down, you just turn off your trading app then look at it later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:17:44 </td>
   <td style="text-align:left;"> $TSLA wow what did I miss this evening? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:17:40 </td>
   <td style="text-align:left;"> $TSLA gonna poke through the whiskers in the coming days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:17:00 </td>
   <td style="text-align:left;"> $TSLA still big chance to print 1K tonight!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:16:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Deutsche Bank Keeps Their Buy Rating on Tesla (TSLA) https://www.stck.pro/news/TSLA/19783329 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:16:00 </td>
   <td style="text-align:left;"> $TSLA tomorrow definitely is a  play day get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:15:46 </td>
   <td style="text-align:left;"> $TSLA bezinga , the msnbc of financial news...fucking clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:15:36 </td>
   <td style="text-align:left;"> $TSLA GL bullz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:15:23 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:15:12 </td>
   <td style="text-align:left;"> $TSLA Lot of hot air in here. Hope yalls average is over 800. Good luck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-16 08:14:35 </td>
   <td style="text-align:left;"> $TSLA bears shredded again </td>
  </tr>
</tbody>
</table></div>

