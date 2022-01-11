---
output:
  html_document:
    keep_md: true
---

# Investment Analytics Portfolio

My portfolio exhibits some examples of the data analytics and financial modelling that I conduct in my daily workflows.

* Forecasting Models
  * Target Stock Price Setting for US Listed Equities
  * Economic Forecasting
  * Currency Forecasting
  
* Data Scraping
  * Financial News Scraping
  * Stock Tweets Scraping
  
---

## Forecasting Models

---

### Target Stock Price Setting for US Listed Equities

#### Bottom-up, systematic approach to stock price forecasting via statistical modelling of company fundamental data.


[Introductory Document for Clients](/pdf/Introduction-To-PromiseLand-s-Stock-Price-Targets.pdf)

[View the latest Price Targets](/Latest-Target-Prices.html)


<img src="images/ghpStockPlotUpper.png?raw=true"/>
<img src="images/ghpStockPlotLower.png?raw=true"/>

---

### Economic Forecasting

#### Econometric analysis of economic data and indicators to forecast market and sector trends.

[Introductory Document for Clients](/pdf/Introduction-To-PromiseLand-s-Economic-Forecasts.pdf)

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Jan-2022-.pdf)

<img src="images/ghpEconPlotUpper.png?raw=true"/>
<img src="images/ghpEconPlotMid.png?raw=true"/>
<img src="images/ghpEconPlotLower.png?raw=true"/>

---

### Currency Forecasts

#### Autoregressive modelling to forecast trends of major currency pairs.

[Introductory Document for Clients](/pdf/Introduction-To-PromiseLand-s-Stock-Price-Targets.pdf)

[View the latest Currency Forecasts](/Latest-Currency-Forecasts.html)

<img src="images/ghpCurrencyFrontplot.png?raw=true"/>
<img src="images/ghpCurrencyTestplot.png?raw=true"/>
<img src="images/ghpCurrencyFutureplot.png?raw=true"/>

---

## Data Scraping

---

### Financial News Scraping

#### Extraction of latest financial news from a variety of news sources. 

At present, sources of news include:

- Bloomberg
- MarketWatch
- Fox News
- New York Times
- Reuters
- BBC News
- CNBC News
- CNN News
- TradingEconomics

[Brief Illustration of Script](/Output-of-getNews.md)



Last Updated: 2022-01-11 10:03:31 UTC +8

<div style="border: 1px solid #ddd; padding: 0px; overflow-y: scroll; height:900px; overflow-x: scroll; width:100%; "><table style="width:30%; width: auto !important; margin-left: auto; margin-right: auto;" class="table table-striped">
 <thead>
  <tr>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> URL </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> Date </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> Article Title </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> Article Text </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-11 10:01:11 </td>
   <td style="text-align:left;"> Philippines Trade Gap Largest Since April 2017 </td>
   <td style="text-align:left;"> The Philippines' trade deficit jumped to USD 4.71 billion in November 2021 from USD 2.05 billion in the same month a year earlier. This was the largest trade gap since April 2017, according to Refinitive Eikon, as exports grew by 6.6% yoy to USD 6.27 billion while imports climbed 36.8% to USD 10.98 billion. Considering the first eleven months of the year, the trade gap widened sharply to USD 37.92 billion from USD 22.15 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brunei/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-11 09:48:20 </td>
   <td style="text-align:left;"> Brunei Inflation Rate at 3-Month Low of 1.8% </td>
   <td style="text-align:left;"> The annual inflation rate in Brunei declined to a 3-month low of 1.8 percent in October 2021 from 2.2 percent in the previous month, which was the highest rate in 10 months. Price rose softer for food and non-alcoholic beverages (2.3% vs 2.5% in September), transport (5.0% vs 7.8%), restaurants and hotels (0.7% vs 1.6%). Meanwhile, prices continued to increase for clothing &amp; footwear (9.5% vs 2.5%), health (1.1% vs 1.0%), communication (0.03% vs 0.03%), and miscellaneous goods and services (0.6% vs 0.6%). By contrast, prices fell further for furnishing (-0.3% vs -0.4%), housing (-0.2% vs -0.2%), and recreation &amp; culture (-0.2% vs -0.2%). On a monthly basis, consumer prices edged up 0.1 percent in October, easing from a 0.4 percent gain in September. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/brc-retail-sales-monitor-yoy </td>
   <td style="text-align:left;"> 2022-01-11 09:20:52 </td>
   <td style="text-align:left;"> UK Retail Sales Slows in December </td>
   <td style="text-align:left;"> Retail sales in the United Kingdom increased 0.6% in December 2021 on a like-for-like basis from a year earlier, slowing from a 1.8% rise in the previous month as the spread of omicron and updated government guidelines dented spending during the final weeks of the year. The British Retail Consortium report showed sales of clothing and jewelry continued to dominate Christmas gift buying, while spending on food and drink was solid despite concern over the impact of omicron. It also noted that many people have chosen to shop online in December rather than travel to nearby high streets and shopping centers. However, the report warned of significant headwinds for the industry in 2022 from high inflation, rising energy bills and planned tax increases. On an annual basis, retail sales increased 8.9% on a like-for-like basis in 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 08:56:54 </td>
   <td style="text-align:left;"> Australian Shares Fall on Omicron Concerns </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index fell 0.6% to 7,400 on Tuesday, with retailers, consumer and financial stocks leading the market lower as an omicron-driven surge in domestic Covid cases weighed on investor sentiment. The Australian government vowed to “push through” the fast-spreading omicron outbreak even as the total tally of infections surpassed 1 million on Monday. The recent outbreak strained hospitals and supply chains, with supermarkets and retailers facing staff shortages. Woolworths, Wesfarmers and Coles each dropped more than 1%. Other notable decliners include Commonwealth Bank (-2%), Macquarie Group (-2%), ANZ Bank (-1.1%), Arb Corporation (-6%) and Ingrams Group (-7.2%). Heavyweight miners also declined on weaker commodity prices, while technology firms mostly gained. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/exports </td>
   <td style="text-align:left;"> 2022-01-11 08:54:00 </td>
   <td style="text-align:left;"> Australia Exports Rise 2% MoM in November </td>
   <td style="text-align:left;"> Exports of goods and services from Australia grew 2 percent month-over-month to AUD 43.86 billion in November 2021. Sales of non-rural goods rose 1 percent to AUD 31.30 billion, supported by metals, excl. non-monetary gold (28 percent); other manufactures (7 percent), and other non-rural, incl. sugar and beverages (32 percent). In addition, shipments of rural goods surged 13 percent to AUD 5.74 billion, driven by cereal grains and cereal preparations (12 percent); meat and meat preparations (4 percent), and other rural (21 percent). Also, sales of services increased 2 percent to AUD 4.82 billion, due to higher sales of travel (4 percent) and other services (1 percent). By contrast, shipments of non-monetary gold plunged 14 percent to AUD 1.97 billion, while net exports of goods under merchanting were unchanged at AUD 32 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/dot-com-bubble-dynamic-may-drive-sp-500-above-5500-julian-emanuel.html </td>
   <td style="text-align:left;"> 2022-01-11 08:51:04 </td>
   <td style="text-align:left;"> This dot-com bubble dynamic may drive the S&amp;P 500 above 5,500 this year </td>
   <td style="text-align:left;"> , Market bull Julian Emanuel sees a dot-com era dynamic that could shatter the S&amp;P 500's record highs.                                                                                                                                                                                                                                          , In his first TV interview since starting at Evercore ISI, Emanuel told CNBC's "Fast Money" an emotionally charged public could drive the index to 5,509 this year.                                                                                                                                                                            , "They really haven't committed sort of every last dollar in the way that was the case in '99 and '00," the firm's senior managing director of equity, derivatives and quantitative strategy said Monday. "If you get that kind of emotion, particularly if the pandemic turns endemic at mid-year, that's how you get that kind of overshoot.", It is Emanuel's best case market scenario for 2022. The move implies an 18% jump from the current S&amp;P 500 level and an 8% gain from his official 5,100 price target. The index's all-time high is 4,818.62.                                                                                                                                   , "We've seen very vigorous participation for the last year and a half without actually the concurring emotions that you tend to get with that kind of participation," said Emanuel, who left BTIG in October.                                                                                                                                  , According to Emanuel, the Federal Reserve would have to assure investors they would avoid derailing market rallies.                                                                                                                                                                                                                           , "Ultimately to get stock prices to move to those kinds of extremes on the upside through our price target, you're going to need a perception that inflation is going to moderate," he said. "We actually do think it moderates later in the year, but stays high for an extended period."                                                     , Given strong earnings and economic momentum, Emanuel believes the broader market can withstand pricing pressures.                                                                                                                                                                                                                             , His worst case scenario implies the S&amp;P 500 would fall to 3,575 this year. In his recent research note, Emanuel cited a prolonged pandemic — as well as a potential debt and spending "hangover" similar to the period after World War I and the 1918 flu epidemic.                                                                           , In the meantime, Emanuel is sticking to his 2022 game plan. He prefers value stocks over growth, and sees trouble ahead for the Nasdaq due to high valuations and rising rates.                                                                                                                                                               , He believes industrials will get a bid from easing supply chain concerns and health care will insulate investors from tightening Fed policies.                                                                                                                                                                                                , Emanuel also likes financials.                                                                                                                                                                                                                                                                                                                , "Those stocks still in comparison to their weighting are barely off their financial crisis lows," Emanuel said.                                                                                                                                                                                                                               , Disclaimer                                                                                                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/retail-sales </td>
   <td style="text-align:left;"> 2022-01-11 08:48:00 </td>
   <td style="text-align:left;"> Australia Retail Sales Growth Beats Forecasts </td>
   <td style="text-align:left;"> Retail sales in Australia rose by 7.3% mom in November 2021, exceeding market consensus of 3.9% and after a 4.9% gain in October. This was the 4th-strongest monthly rise in the series, amid a further easing of COVID-19 curbs in the South-Eastern states and as consumers brought forward Christmas spending to take advantage of sales and minimize delivery and stock availability concerns. Discretionary spending continued to be strong, with five retail industries seeing rises for the 2nd straight month. Pent-up demand combined with an extended November sales period saw record sales in clothing, footwear (38.2% vs 27.7% in October), household goods retailing (11.6% vs 4.5%), department stores (26.0% vs 22.4%) and other retailing (7.3% vs 2.2%). Also, sales at cafes, restaurants gained 9.3% after a 12.3% jump in October. “... retail sales now at their highest level ever recorded, up 5.8% on the prior record set in November 2020," said Ben James, Director of Quarterly Economy Wide Statistics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-11 08:40:00 </td>
   <td style="text-align:left;"> Australia Trade Surplus Smallest in 7 Months </td>
   <td style="text-align:left;"> Australia's trade surplus declined to AUD 9.42 billion in November 2021 from a downwardly revised AUD 10.78 billion in the previous month and below market consensus of AUD 10.6 billion. It was the smallest trade surplus since April, amid softening global demand as more countries battled with a resurgence of coronavirus infections. Exports grew 2 percent month-over-month to AUD 43.86 billion and imports rose at a faster 6 percent to a 23-month high of AUD 34.44 billion. Considering the first eleven months of the year, the trade surplus surged to AUD 114.80 billion from AUD 65.22 billion in the same period of 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/imports </td>
   <td style="text-align:left;"> 2022-01-11 08:39:00 </td>
   <td style="text-align:left;"> Australia Imports Hit 23-Month High </td>
   <td style="text-align:left;"> Imports of goods and services to Australia jumped 6% mom to a 23-month high of AUD 34.44 billion in November 2021, buoyed by solid domestic demand ahead of Christmas and year-end holidays as strict lockdown measures in several key states eased following an acceleration in vaccinations. Arrivals of intermediate and other merchandise goods climbed 7% to AUD 12.98 billion, boosted by primary industrial supplies n.e.s. (148%) and processed industrial supplies n.e.s. (7%). Also, imports of capital goods surged 7 percent to AUD 7.09 billion, lifted by civil aircraft and confidentialised items (46%) and industrial transport equipment n.e.s (19%); and those of consumption goods went up 3 percent to AUD 8.96 billion, led by household electrical items (20%) and consumption goods n.e.s (3%). In addition, arrivals of services gained 2% to AUD 4.82 billion, largely due to travel (4%) and other services (1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/current-account </td>
   <td style="text-align:left;"> 2022-01-11 08:33:31 </td>
   <td style="text-align:left;"> South Korea Current Account Surplus Narrows </td>
   <td style="text-align:left;"> South Korea’s current account surplus narrowed to $7.16 billion in November 2021 from a surplus of $9.18 billion tallied a year earlier, as imports increased due to high energy and raw materials prices. The reading marked the 19th straight month with a surplus. Imports increased by $16.74 billion to $53.7 billion in November driven mainly by a 72.9% YoY surge in raw material prices, with crude oil jumping 127.8%. The goods balance saw its surplus decline to $5.95 billion in November from the previous year’s $9.95 billion. Exports also totaled $59.65 billion compared with $46.92 billion a year earlier. Meanwhile, the service account posted a deficit of $140 million in November, compared with a deficit of $980 million a year earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-11 08:09:28 </td>
   <td style="text-align:left;"> Malaysia 10Y Bond Yield Hits 30-month High </td>
   <td style="text-align:left;"> Malaysia 10 Year Government Bond Yeld increased to a 30-month high of 3.688% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 08:07:09 </td>
   <td style="text-align:left;"> US Futures Flat After Nasdaq’s Late Comeback </td>
   <td style="text-align:left;"> US stock futures were little changed on Tuesday after a volatile session on Wall Street, with the Nasdaq staging a late session comeback to end in positive territory. Dow futures were flat, while S&amp;P 500 and Nasdaq 100 futures rose 0.05% and 0.1%, respectively. In regular trading on Monday, the three major averages sold off throughout the day before rallying into the close as investors bought the dip. The Dow and S&amp;P 500 closed 0.45% and 0.14% lower, respectively, after each fell more than 1.5% earlier in the day, while the Nasdaq reversed a 2.72% drop to end 0.05% higher. Rising bond yields and prospects of tighter monetary policies continued to weigh on stocks.  However, analysts suggested that the market may be more focused on the direction of real earnings than the pace of rate hikes. Meanwhile, investors await earnings reports, inflation data and statements from Fed officials this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-11 07:30:07 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 43-week High </td>
   <td style="text-align:left;"> Japan 10 Year Government Bond Yeld increased to a 43-week high of 0.145% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/kudlow/kudlow-nancy-pelosi-trading </td>
   <td style="text-align:left;"> 2022-01-11 07:24:15 </td>
   <td style="text-align:left;"> Kudlow: I have a problem with Nancy Pelosi trading companies that have serious regulatory issues pending </td>
   <td style="text-align:left;"> ‘Kudlow’ host examines the House speaker’s stock trades while in Washington.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , I'm extremely worried this evening over a 1% drop in the tech-heavy NASDAQ Index. Why this sudden concern? Because it may do great damage to Nancy Pelosi's almost perfect investment track record.                                                                                                                                                                                                                                                                                                                                             , You may have read that one website has already nominated her as the 2021 Wall Street trader of the year. In fact, reading jacobinmag.com – which I'm told is a left-wing outfit – nonetheless, they have a fabulous story about Ms. Pelosi and her trading acumen.                                                                                                                                                                                                                                                                              , The Gordon Gekko of the New York Stock Exchange. The oracle of Omaha is dead. Long live the Queen of Stocks.  According to reports, she and her husband Paul Pelosi have traded over $50 million in assets over the past year with annualized returns at 69% as of October, according to an estimate from the Nancy Pelosi portfolio tracker.                                                                                                                                                                                                   , PELOSI'S HUSBAND BETS BIG ON GOOGLE, SALESFORCE, DISNEY AFTER SPEAKER DEFENDS LAWMAKER TRANSACTIONS                                                                                                                                                                                                                                                                                                                                                                                                                                             , That's higher than Buffett, George Soros, Cathy Wood, and other star investors. Apparently, the Pelosi portfolio beat the S&amp;P 500 by 4.9 percent in 2019 and a big 14.3 percent gain in 2020, according to an outfit called FinePrint. Ms. Pelosi is becoming a cult figure among stock investors.                                                                                                                                                                                                                                              , One brilliant move was the purchase of hundreds of thousands of dollars in Roblox when the gaming company went public in March, according to jacobinmag.com. Many were skeptical of the value of a kids video game, but the stock has doubled in value since then.                                                                                                                                                                                                                                                                              , In July, she invested at least $1 million in computer chip maker Nvidia, which skyrocketed 70% during the worldwide chip shortage.                                                                                                                                                                                                                                                                                                                                                                                                              , A TikTok account called @quicktrades got 70,000 likes for a post highlighting the "queen of investing."                                                                                                                                                                                                                                                                                                                                                                                                                                         , Last month the Pelosis disclosed that they purchased millions in bullish call options for stocks including Google, Salesforce, and Micron Technology. The Pelosis have reportedly reaped at least $5.6 million and up to $30.4 million in capital gains and dividends from their holdings in five Big Tech firms: Facebook, Google, Amazon, Apple, and Microsoft.                                                                                                                                                                               , JON OSSOFF EXPLORING BILL TO BAN CONGRESS STOCK TRADES, REBUFFING PELOSI                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Now, frankly, I don't have any problem with Ms. Pelosi getting rich. I like the fact that she's heavily invested in stocks and is last year's Wall Street trader of the year.  I've always believed that a rising tide would lift all boats,                                                                                                                                                                                                                                                                                                    , But I do have a slight problem with Ms. Pelosi's trading companies that have serious regulatory issues pending before the Congress. Some people believe she has been slow-walking regulatory issues around the tech giants.                                                                                                                                                                                                                                                                                                                     , There is always an issue of access and influence and confidential briefings and non-public information. I know in the executive branch you are allowed to trade stocks, but anything above a thousand bucks requires an ethics signoff with respect to potential conflicts of interest.                                                                                                                                                                                                                                                         , Supposedly similar rules prevail in Congress, but I wonder about that. Ms. Pelosi has upset a number of her left-wing colleagues who think stock trading should be banned altogether. She does not agree.                                                                                                                                                                                                                                                                                                                                       , And late last month, in response to criticism, Ms. Pelosi said, "We're in a free market economy."                                                                                                                                                                                                                                                                                                                                                                                                                                               , Really, Ms. Pelosi? Just sayin' ma'am. Every policy you have backed runs counter to your "free market economy."                                                                                                                                                                                                                                                                                                                                                                                                                                 , Not only does that include your advocacy for government takeovers for energy, health care, banking, and elsewhere, but you have always enthusiastically supported big tax hikes on those who "don't pay their fair share.'                                                                                                                                                                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , On that last point, I was particularly interested in the report that you may have reaped up to $30 million on capital gains and dividends over the past many years. Nothin' wrong with that, especially since George W. Bush slashed the tax rate on cap gains and dividends to 15% in 2003. But now Ms. Pelosi, you want to jack those investment rates sky-high and even tax unrealized capital gains as a way of getting to a wealth tax. So while you've got yours, you would effectively stop others from getting their benefits after tax., I recall interviewing Ms. Pelosi about 15 years ago when she was on the verge of becoming House speaker. It was a very pleasant interview, requested by her, and I asked her at the end if she believed in the stock market and wealth creation, and she responded "Oh yes, Larry, how do you think I got these?" As she lifted her hair and showed a spectacular set of diamond earrings.                                                                                                                                                      , Truthfully, I kind of loved it. I think she was waiting for the question and had a terrific answer, and I was completely blinded by the diamond dazzle in front of me. Down through the years, I interviewed her twice more, both pleasant enough. I've never harbored any personal animosity toward her.                                                                                                                                                                                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , When I went to work in the Trump White House, she greeted me before the start of a cabinet room meeting with a hug.                                                                                                                                                                                                                                                                                                                                                                                                                             , Of course, I disagree with her policy views. But then again, if Ms. Pelosi is back to defending the free market and stock market trading, maybe the gap between her economic thinking and mine is about to narrow. Wouldn't bet on it, but hope springs eternal.                                                                                                                                                                                                                                                                                , That said, I would suggest to the speaker that she promote tax incentives that will create the grand opportunity for all Americans to get rich and benefit by superior stock-picking skills. If you tax something less, Ms. Pelosi, like stocks, wealth, or jobs and incomes, you'll get much more of it. The non-rich can get rich.                                                                                                                                                                                                            , And by the way, I'd love to interview her again or even have another pleasant phone call. And that's my Riff.                                                                                                                                                                                                                                                                                                                                                                                                                                   , This article is adapted from Larry Kudlow's opening commentary on Jan. 10, 2022.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-11 07:06:23 </td>
   <td style="text-align:left;"> Stock futures are flat after Nasdaq’s Monday comeback </td>
   <td style="text-align:left;"> , U.S. stocks were flat on Monday evening after the major averages extended declines, until the Nasdaq rallied to snap a four-day losing streak.                                                                                                                                                                                                                                                     , Futures tied to the Dow Jones Industrial Average fell 17 points, or 0.05%. S&amp;P 500 futures edged 0.01% lower, and Nasdaq 100 futures were slightly higher.                                                                                                                                                                                                                                         , In regular trading, the Nasdaq turned slightly green into the close after a day of continued declines from the previous week's sell-off, sparked by a rate in bond yields and worries about upcoming actions by the Federal Reserve. It closed 0.05% higher and erasing a 2.7% loss. Meanwhile, the Dow lost 162 points, or 0.4%, while the S&amp;P 500 slid 0.1%.                                     , Stocks remained under pressure as bond yields continued to rise. On Monday the 10-year U.S. Treasury yield rose to 1.8%, after ending 2021 at 1.5%.                                                                                                                                                                                                                                                , On Monday JPMorgan's Marko Kolanovic put out a note saying markets can withstand higher yields, as well as omicron, and that investors should buy the dip in the tech stocks.                                                                                                                                                                                                                      , "The pullback in risk assets in reaction to the Fed minutes is arguably overdone," he said. "Policy tightening is likely to be gradual and at a pace that risk assets should be able to handle, and is occurring in an environment of strong cyclical recovery."                                                                                                                                   , The Leuthold Group's Jim Paulsen said that while the stock market is likely to encounter a correction this year – and last week's action could perhaps have been the start of one – it will be met by strong company fundamentals.                                                                                                                                                                 , "Historically, the stock market has suffered some nasty 'temper tantrums,' and numerous rate hikes eventually led to recessionary bear markets," Paulsen said in a note Monday evening. "However, the current focus among investors may be misplaced. The stock market's response may have less to do with the timing and number of rate hikes than it does with the 'direction' of real earnings.", Earnings season will be in full swing by the end of this week with the big banks set to report starting Friday. In the more immediate term, Albertson's is scheduled to report its quarterly results before the bell Tuesday.                                                                                                                                                                      , It's a big week in economic data as well, including key inflation data. On Tuesday Federal Reserve Chairman Jerome Powell's confirmation hearing will take place. Kansas City Fed President Esther George is also scheduled to speak about on economic policy, as is St. Louis Fed president James Bullard later in the day.                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/10/business/starbucks-union-election-buffalo.html </td>
   <td style="text-align:left;"> 2022-01-11 07:03:09 </td>
   <td style="text-align:left;"> Union Wins Vote at Second Buffalo-Area Starbucks - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                           , By Noam Scheiber                                                                                                                                                                                                                                                                                                                                                                                        , The National Labor Relations Board announced Monday that it had certified a victory for a union at a second Starbucks store in the Buffalo area, where votes were tallied in December but remained inconclusive as the union challenged the ballots of several employees it said did not work at the store.                                                                                             , The labor board declared the union the winner at another Buffalo-area store when it counted the votes on Dec. 9, and the union lost an election at a third store.                                                                                                                                                                                                                                       , The board agreed with the union that the challenged ballots should not count, giving the union a 15-to-9 win. None of the other roughly 9,000 company-operated Starbucks locations in the United States have a union.                                                                                                                                                                                   , Labor experts have said that establishing a second unionized store in the same market could provide a significant boost to the union, Starbucks Workers United. The union is part of Workers United, an affiliate of the giant Service Employees International Union.                                                                                                                                   , Under U.S. labor law, employers are obligated to bargain in good faith with a union that has won an N.L.R.B. election, but they are not required to reach agreement on a contract. As a result, winning a contract often requires unions to apply economic pressure such as a work stoppage, something that a second store could make more potent.                                                      , Last week, several employees of the first unionized store near Buffalo walked off the job amid concerns about rising Covid-19 infection rates. The workers said they returned on Monday.                                                                                                                                                                                                                , The newly unionized store, near the Buffalo airport, filed for a union election in late August, along with the two other stores that voted in December. The union has formally objected to the outcome of the election that it lost, and that objection is pending before the labor board.                                                                                                              , Starbucks has 10 business days to request an appeal of the decision announced on Monday. If the request was filed and denied, the result would become final. A company spokesman said that Starbucks was evaluating whether or not to appeal and that it believed its employees’ voices should be heard.                                                                                                , Throughout the union campaign last year, Starbucks dispatched out-of-town managers and a top executive to Buffalo in what it said was an attempt to fix operational issues like understaffing and the poor layout of certain stores. The officials often questioned employees about their workplaces and helped with menial tasks like throwing out garbage.                                            , Several union supporters said they were intimidated by the presence of the officials and were disoriented by other disruptions to their work lives, such as the company’s decision to temporarily close certain stores and send employees to other locations.                                                                                                                                           , Since the initial victory in Buffalo, workers at several other Starbucks stores throughout the country have filed for union elections, including in Boston, Chicago, Seattle and Knoxville, Tenn.                                                                                                                                                                                                       , “Today we put an end to Starbucks’s delay attempts and formed our union,” Alexis Rizzo, a shift supervisor at the second unionized location, said in a statement, adding: “We demand that Starbucks stop their union busting in Buffalo and across the nation immediately. No other partners should have to endure what we went through to have a voice on the job.”                                    , Starbucks has denied that it has sought to intimidate employees, but it has said it prefers that its employees not unionize.                                                                                                                                                                                                                                                                            , Last week, the federal labor board scheduled an election for a Starbucks store in Mesa, Ariz., where workers had filed paperwork in November. Ballots in the election will be mailed out on Friday and will be due back by Jan. 28. Workers at more than 10 other locations, including three in the Buffalo area, are still awaiting decisions from the board on if and when it will set election dates., Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/10/politics/kevin-mccarthy-committees-republican-house-majority/index.html </td>
   <td style="text-align:left;"> 2022-01-11 06:58:54 </td>
   <td style="text-align:left;"> McCarthy vows to remove Democrats from committees if Republicans win House - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)House Minority Leader Kevin McCarthy has vowed to remove three Democratic lawmakers from key committee assignments if Republicans win back the chamber in the upcoming midterm elections.                                                                                                                                                                                                                                                                                                  , Citing a "new standard" that Democrats had created last year by removing GOP Reps. Marjorie Taylor Greene of Georgia and Paul Gosar of Arizona from their committees for inflammatory rhetoric and posts, McCarthy told Breitbart he would strip Democratic Reps. Adam Schiff and Eric Swalwell, both of California, and Ilhan Omar of Minnesota of their committee assignments.                                                                                                                           , Schiff and Swalwell serve on the House Intelligence Committee, while Omar serves on the House Foreign Affairs Committee.                                                                                                                                                                                                                                                                                                                                                                                   , "The Democrats have created a new thing where they're picking and choosing who could be on committee. Never in the history have you had the majority tell the minority who could be on committee," McCarthy lamented in the interview.                                                                                                                                                                                                                                                                     , The California Republican had previously hinted that if Republicans win back the House, a GOP majority may kick some House Democrats off their committee seats. "[House Speaker Nancy] Pelosi has set new policies here. Those same members that I talked about in my speech ... voted for these new policies," McCarthy said in November, alluding to Schiff, Swalwell, Omar and Democratic Rep. Maxine Waters, also of California. "This isn't about threats, but it's about holding people accountable.", "I think the majority is going to have to approve any of those members on the committees on which they can serve," he said at the time.                                                                                                                                                                                                                                                                                                                                                                    , Pelosi had told CNN in response that she was not concerned that Republicans plan to retaliate should the GOP win back the House. "No, we would not walk away from our responsibilities for fear of something they may do in the future," the California Democrat said at the time.                                                                                                                                                                                                                         , Gosar was censured and removed from his committee seats for posting a photoshopped anime video to his Twitter and Instagram accounts showing him appearing to kill Democratic Rep. Alexandria Ocasio-Cortez of New York and attacking President Joe Biden. He eventually took the post down but retweeted a tweet that contained the video hours after being disciplined by the House.                                                                                                                     , Greene, meanwhile, was stripped of her committee assignments last February in the wake of incendiary and violent past statements that had been unearthed shortly after she was sworn in.                                                                                                                                                                                                                                                                                                                   , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/meta-mandates-boosters-employees-working/story.aspx?guid={0FAE3EBB-F44C-4B03-AA59-2805CB9E7C84}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 06:18:51 </td>
   <td style="text-align:left;"> Meta mandates boosters for employees working at U.S. campuses, eyes late March reopening - MarketWatch </td>
   <td style="text-align:left;"> Facebook parent Meta Platforms Inc. 
        FB,
        -1.12%
       is eyeing a reopening of its U.S. campuses on March 28, but it comes with a caveat: Employees who wish to work out of those offices will require a COVID-19 booster shot. "Boosters provide increased protection," a Meta spokesman told the Wall Street Journal on Monday. "Given the evidence of booster effectiveness, we are expanding our vaccination requirement to include boosters." Meta's move is the latest by an American company to ramp up additional doses amid a surge in the omicron variant., Tilray Inc. undefined on Monday posted a second-quarter net loss attributable to shareholders of $201,000 or zero cents a share, compared to a loss of $99.9 million, or 41 cents a share, in the year-ago period. Revenue increased to $155.15 million from $129.46 million. Analysts expected Tilray to lose 9 cents a share on revenue of $170.5 million, according to a survey by FactSet. The cannabis company is also changing its name to Tilray Brands Inc. Shares of Tilray rose 4.2% in premarket trades.                                                                     , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/car-sharing-company-turo-files-ipo/story.aspx?guid={F32080EC-5FE2-4069-89BD-2174119935E2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 06:12:19 </td>
   <td style="text-align:left;"> Car-sharing company Turo files for IPO - MarketWatch </td>
   <td style="text-align:left;"> Peer-to-peer car-sharing company Turo has filed for an initial public offering, according to a filing late Monday. Turo, based in San Francisco, filed to sell up to $100 million worth of shares, although that figure is often a placeholder used to calculate fees. The company plans to list its stock on the New York Stock Exchange under the symbol TURO, and underwriters include JPMorgan and Morgan Stanley. "Our mission is to put the world's 1.5 billion cars to better use," Turo said in its prospectus, adding that its business is "resilient" as it "dynamically adjusts" to the needs of car owners and car renters. For the nine months ended on Sept. 30, Turo had sales of $330.5 million, up 207% from sales of $107.8 million for the same period in 2020, the company said. Net loss rose to $129.3 million, from $51.7 million for the same period in 2020. After a record-shattering 2021, the IPO market is expected to welcome companies such as grocery-delivery service Instacart, data-analytics company Databricks, and retailer Mattress Firm this year. , Zynga Inc. is selling for less than $10 a share, more than a decade after going public at that price and embarking on an acquisition parade.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/abercrombie-fitch-stock-rises/story.aspx?guid={FDF71259-6226-41EC-8A69-004018D803E0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 05:52:36 </td>
   <td style="text-align:left;"> Abercrombie &amp; Fitch stock rises more than 6% after retailer's outlook - MarketWatch </td>
   <td style="text-align:left;"> Abercrombie &amp; Fitch Co. 
        ANF,
        -2.53%
       shares jumped more than 6% late Monday after the retailer said it expects fiscal 2021 net sales to be between 19% and 20% higher than its 2020 net sales of $3.13 billion, and up between 2% and 3% compared with 2019 net sales. Abercrombie tweaked its fiscal 2021 fourth-quarter sales expectations, however, thanks to "additional unexpected and uncontrollable inventory receipt delays and increased COVID-related impacts and restrictions." It expects net sales up in a range between 4% and 6% compared to 2020 net sales of $1.1 billion, and flat to down 2% as compared with 2019 net sales. The prior outlook called for sales up between 3% and 5% as compared to 2019. The retailer called for a flat gross profit rate as compared to 2019, in line with its previous outlook, as fewer promotions and markdowns were offset by rising freight and related costs. Shares of Abercrombie &amp; Fitch ended the regular trading day down 2.5%., Wedbush analyst Dan Ives is looking ahead to earnings season. Here's what he says Wall Street needs to get back to bullishness on tech.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/stocks-making-the-biggest-moves-after-hours-intel-micron-and-more.html </td>
   <td style="text-align:left;"> 2022-01-11 05:52:14 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Intel, Micron, Wynn Resorts and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                          , Check out the companies making headlines in after-hours trading.                                                                                                                                                                                                                                                                                                         , Intel — The tech giant jumped more than 4% after hours after the company confirmed the appointment of David Zinsner as chief financial officer. Current CFO George Davis will retire from Intel in May.                                                                                                                                                                  , Micron Technology — Shares of the chipmaker fell more than 1% in extended trading after New Street Research initiated the stock at a buy with a price target of $135, implying about 43% upside from its closing price Monday.                                                                                                                                           , Wynn Resorts — The hotel and casino stock fell 1% after Citi on Monday downgraded it to neutral from buy. The move after hours followed a trading day when its peer, Las Vegas Sands, declined about 2% on a downgrade of its own. Investors in both stocks have been focused on the renewal of their concession licenses to operate in Macau, which will expire in June., Amgen — Biotech company Amgen's shares fell more than 1% after the European Commission granted the company conditional marketing authorization for its medication that treats adults with advanced non-small cell lung cancer.                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/big-lots-stock-tanks-7/story.aspx?guid={B1FDF0AB-8B83-4CC7-920F-355197EFD5DD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 05:40:10 </td>
   <td style="text-align:left;"> Big Lots stock tanks 7% after retailer sees sales, traffic 'softening' due to omicron - MarketWatch </td>
   <td style="text-align:left;"> Shares of Big Lots Inc. 
        BIG,
        -6.70%
       fell more than 7% in the extended session Monday after the retailer said it has been seeing "softening of traffic and sales trends" in January caused by the spread of the omicron variant of the coronavirus in addition to winter weather. The company said that could lead to flat to a below-expectations comparable-sales increase for fiscal January, and result in per-share earnings for the quarter between $1.80 and $1.95. Analyst consensus was of EPS of $2.17, according to FactSet. "Our outstanding team has worked tirelessly to offset headwinds from the global supply chain," Chief Executive Bruce Thorn said in a statement. "While the Omicron variant creates some near-term challenges, we look forward to rounding out another very successful year for the company." Shares of Big Lots ended the regular trading day down 6.7%. , Wedbush analyst Dan Ives is looking ahead to earnings season. Here's what he says Wall Street needs to get back to bullishness on tech.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 05:32:20 </td>
   <td style="text-align:left;"> Canada Stocks Little Changed on Monday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, traded around the flatline to close at 21,072 on Monday as losses on industrial and tech stocks were offset by gains in healthcare and materials stocks. Meanwhile, the session was marked by a global risk-off sentiment fueled by growing concerns that the Federal Reserve will bring forward rate hike plans. On the corporate front, cannabis producer Tilray surged more than 10% after posting a surprise profit of $6 million for the quarter ended in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 05:24:32 </td>
   <td style="text-align:left;"> Brazil Stocks Trade Lower, Miners Weigh </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, dropped 0.9% to close at 101,781 on Monday, tracking a fall in international markets, while heavyweight miners were pressured by weaker iron ore prices and production disruptions. Also, bets about a sooner-than-anticipated unwinding of monetary stimulus by the US Fed fueled a broad risk aversion in international equity markets. A major port in Rio de Janeiro halted operations due to heavy rains, disrupting the shipment of ore cargoes. Meanwhile, the Central Bank of Brazil’s market expectations survey showed end-of-year 2022 interest rate forecasts were updated to 11.75%, up 25bps from last week, while GDP expectations for the year were trimmed to 0.28% as optimism about the recovery faded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/federal-reserve-no-2-official/story.aspx?guid={45BF373A-48C4-490B-A17C-EAF52EB50446}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 05:19:40 </td>
   <td style="text-align:left;"> Federal Reserve No. 2 official Clarida to resign after stock controversy - MarketWatch </td>
   <td style="text-align:left;"> Richard Clarida, the vice chairman of the Federal Reserve, said Monday he will resign on Jan. 14, two weeks before his term was set to end on Jan. 31. Clarida, who was tapped for the Fed by President Donald Trump, was not going to be renominated by the Biden administration. Clarida has become embroiled in a controversy involving a stock transaction in 2020 shortly before the central bank took action to prop up the economy. His announcement comes one day before Chairman Jerome Powell testifies to the Senate, a hearing at which he was expected to be asked about Clarida's investment decisions. Massachusetts Sen. Elizabeth Warren has been especially critical of Fed officials for buying and selling assets during the crisis, accusing them of a conflict of interest. Clarida did not mention the controversy in his resignation letter. Two other senior Fed officials resigned in the fall after disclosures about their investments during the pandemic., ‘I think it will deter [Russia's] ability to wage a major conflict in Ukraine,’ says House Republican Mark Green of Tennessee.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Jeffry Bartash is a reporter for MarketWatch in Washington. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nasdaq-ekes-out-gain-post/story.aspx?guid={352339E9-864A-421B-9C70-5BAAA9C61D6B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 05:09:30 </td>
   <td style="text-align:left;"> Nasdaq ekes out gain to post biggest intraday rebound since February 2020 - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended mostly lower but well off session lows Monday, with the tech-heavy Nasdaq Composite erasing its early plunge to eke out a small gain. The Nasdaq 
        COMP,
        +0.05%
       finished with a gain of around 7 points, or less than 0.1%, near 14,943, according to preliminary figures, after falling as much as 2.7% at its session low. The reversal marked the index's biggest intraday comeback since Feb. 28, 2020, according to Dow Jones Market Data. The Dow Jones Industrial Average finished with a loss of around 163 points, or 0.4%, near 36,069 after dropping by around 592 points at its low. The S&amp;P 500 
        SPX,
        -0.14%
       closed with a loss of around 7 points, or 0.1%, near 4,670., Cathie Wood says it isn't the stocks that she favors that are in a bubble.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 04:36:00 </td>
   <td style="text-align:left;"> Wall Street Slips Amid Higher Rates Prospects </td>
   <td style="text-align:left;"> US stocks started the week on a negative note, with the Dow Jones falling more than 150 points, a 4th straight session of losses while the S&amp;P 500 slipped 0.1%, a 5-day losing streak. Meantime, the Nasdaq composite was little changed, after falling more than 2.5% at the beginning of the session. Treasury yields continue to jump to levels not seen in 2 years as the odds are rising that the Fed may raise the fed funds rate four times this year instead of three. Traders also await the inflation report, the confirmation hearing for Fed Chair Powell, and speeches from several other policymakers for more clues on the Fed's timeline for a fed funds hike. On the corporate front, the earnings season kicks off this week with Wells Fargo, Citigroup, JPMorgan reporting on Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 04:30:08 </td>
   <td style="text-align:left;"> The Dow Jones Index falling 0.85% </td>
   <td style="text-align:left;"> United States Stock Market is dropping 310 points. Leading the losses are Nike (-4.73%), Boeing (-2.98%) and Visa (-2.68%). Top gainers were Intel (2.42%), Merck &amp; Co (2.24%) and UnitedHealth (1.24%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-11 04:00:04 </td>
   <td style="text-align:left;"> Spain 10Y Bond Yield Hits 19-month High </td>
   <td style="text-align:left;"> Spain 10 Year Government Bond Yeld increased to a 19-month high of 0.675% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/portillos-launching-first-drive-through-only/story.aspx?guid={1892D25E-D6F3-4499-9C36-3041CF443615}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 03:51:39 </td>
   <td style="text-align:left;"> Portillo's launching first drive-through only location - MarketWatch </td>
   <td style="text-align:left;"> Chicago hot dog chain Portillo's Inc. 
        PTLO,
        -5.04%
       said Monday that it will open its first drive-through only location in Joliet, Ill. on February 1. The 3,750-square-foot restaurant will not have a dining room, though there will be an area for pick-up orders. Delivery and catering will also be available. The company is hiring full- and part-time workers for the location. Portillo's stock began trading in October 2021 with a $20 IPO price. Shares were trading at $32.05 on Monday afternoon. The Renaissance IPO ETF 
        IPO,
        +0.38%
       is down 23.6% over the past year while the S&amp;P 500 index 
        SPX,
        -0.14%
       is up 21.5% for the period., Zynga will be acquired in a cash-and-stock deal with an enterprise value of $12.7 billion.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-prices-settle-lower-traders/story.aspx?guid={1664CBD9-F634-45D8-A356-D96529CA836D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 03:45:03 </td>
   <td style="text-align:left;"> Oil prices settle lower as traders weigh risks to supply and demand - MarketWatch </td>
   <td style="text-align:left;"> Oil prices settled lower on Monday for a second session in a row. Traders weighed support from global oil supply risks tied to protests in Kazakhstan and tensions between Russia and Ukraine, as well as concerns over a slowdown in energy demand due to the spread of the omicron variant of coronavirus. "The various conflicts and threats across eastern Europe and the Middle East will remain supportive for energy in the near term, but it already appears that some of the supply and production disruptions are being sorted out so that could result in a 'sell the news' reaction from markets in the sessions ahead, pending any new developments," said Tyler Richey, co-editor at Sevens Report Research. February West Texas Intermediate crude 
        clg22
       declined by 67 cents, or nearly 0.9%, to settle at $78.23 a barrel on the New York Mercantile Exchange. , Wedbush analyst Dan Ives is looking ahead to earnings season. Here's what he says Wall Street needs to get back to bullishness on tech.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59930206?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-11 03:44:51 </td>
   <td style="text-align:left;"> Ikea cuts sick pay for unvaccinated staff forced to self-isolate </td>
   <td style="text-align:left;"> Ikea has cut sick pay for unvaccinated staff who need to self-isolate because of Covid exposure and in some cases for workers who test positive.                                                                                                                                                     , The retail giant acknowledged it was an "emotive topic" but said its policy had to evolve with changing circumstances.                                                                                                                                                                               , From this week, sick pay cuts will be implemented at Wessex Water and in the US several major companies have started penalising unjabbed workers.                                                                                                                                                    , It comes as firms struggle with mass staff absences and rising costs.                                                                                                                                                                                                                                , At Ikea unvaccinated workers, who do not have mitigating circumstances, who test positive will be paid in line with company sick pay.                                                                                                                                                                , Unvaccinated workers, without mitigating circumstances and required to isolate owing to being identified as a close contact, could now receive as little as £96.35 a week - the Statutory Sick Pay (SSP) minimum.                                                                                    , Average wages at Ikea are between about £400 and £450, depending on location and, as is the case at many companies, staff get enhanced sick pay. The move was first reported by the Mail on Sunday.                                                                                                  , Ikea, which employs about 10,000 people in the UK, said in a statement: "Fully vaccinated co-workers or those that are unvaccinated owing to mitigating circumstances which, for example, could include pregnancy or other medical grounds, will receive full pay.                                   , "Unvaccinated co-workers without mitigating circumstances that test positive with Covid will be paid full company sick pay in line with our company absence policy.                                                                                                                                  , "Unvaccinated co-workers without mitigating circumstances who have been identified as close contacts of a positive case will be paid Statutory Sick Pay."                                                                                                                                            , In England, people who are vaccinated with at least two doses need not self-isolate if they have been in close contact with someone infected with Covid. Unvaccinated people contacted through the government's test-and-trace system must still isolate by law.                                     , Many companies complained of labour shortages throughout 2021, and now are seeing mass absences due to the more infectious Omicron Covid strain.                                                                                                                                                     , Prime Minister Boris Johnson repeated on Monday that the data continued to show those people most seriously affected by Omicron remained the unvaccinated.                                                                                                                                           , Wessex Water's sick pay rule change comes into force this week.                                                                                                                                                                                                                                      , Any employee without at least one Covid-19 vaccination - who does not have a valid medical reason - or does not have a confirmed vaccination appointment, will get only statutory sick pay if required to self-isolate due to close contact with someone testing positive.                           , A Wessex Water spokesperson said absences have soared this year: "The vast majority of our workforce has been vaccinated and it's important as a company providing essential services with key worker employees, the remainder get vaccinated to protect themselves, customers and their colleagues. , "Absences due to Covid have doubled in the last week, so we need everyone to be available so we can continue to provide uninterrupted essential water and sewerage services."                                                                                                                        , The company said that throughout the pandemic it had not furloughed staff and those self-isolating had received full pay.                                                                                                                                                                            , Last year, supermarket Morrisons cut sick pay terms, while several companies, including banking giant Citigroup, introduced a "no jab, no job" policy. Delta Airlines imposed a surcharge on unvaccinated staff members of its healthcare plan.                                                      , Ben Willmott, head of public policy at the Chartered Institute of Personnel and Development (CIPD), told the BBC there were pros and cons with changing sick pay terms for certain workers.                                                                                                          , It could encourage staff to get vaccinated, but others might be less likely to test themselves or self-isolate because they could not afford time off work at the statutory rate of about £96.                                                                                                       , His organisation's official guidance was not to differentiate between employees, as the consequences could be complex and there were potential legal problems.                                                                                                                                       ,  "You would have to manage it on a case-by-case basis because of legal risks," Mr Willmott said.                                                                                                                                                                                                     , Earlier this month, David Josephs, boss of food importer and retailer All Greens, told the BBC that staff at some firms were ignoring Covid rules for financial reasons.                                                                                                                             , "We know that in our sector a lot of staff do not get paid sick pay. Ours do - but staff who are on limited contracts or on minimum wage cannot afford to be off work," he said.                                                                                                                     , Employment lawyer Sarah Ozanne, of CMS, also warned of complex legal issues and said striking the right balance was difficult.                                                                                                                                                                       , "This action [by Ikea] seems more of a reaction to staff shortages and how to manage them than any intended 'discrimination' of the unvaccinated," she said.                                                                                                                                         , "But employers should consider whether their actions are proportionate as a means of achieving the aim of getting employees back into work."                                                                                                                                                         , Has your place of work cut sick pay for unvaccinated staff? How do you feel about this? Email haveyoursay@bbc.co.uk.                                                                                                                                                                                 , Please include a contact number if you are willing to speak to a BBC journalist. You can also contact us in the following ways:                                                                                                                                                                      , Or use this form to get in touch:                                                                                                                                                                                                                                                                    , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your comment or send it via email to HaveYourSay@bbc.co.uk. Please include your name, age and location with any comment you send in.                                      , What is it really like to live in Dubai?                                                                                                                                                                                                                                                             , The unusual way a parasite attracts pollinators                                                                                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/el-salvador/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-11 03:43:00 </td>
   <td style="text-align:left;"> El Salvador Inflation Rate Eases From 10-Year High </td>
   <td style="text-align:left;"> Consumer prices in El Salvador rose 6.11 percent year-on-year in December of 2021, following a 56.2 percent jump in November. The rate of price increase eased as costs rose at a slower pace for transports (9.46 percent vs 10.74 percent), housing &amp; utilities (6.97 percent vs 8.36 percent), and furnishing &amp; household equipment (6.57 percent vs 7.07 percent). Meanwhile, costs kept accelerating for food &amp; non-alcoholic beverages (7.96 vs 7.42 percent), apparel &amp; footwear (3.34 percent vs 3.09 percent), and recreation &amp; culture (2.87 percent vs 1.87 percent). On a monthly basis, consumer prices advanced 0.11 percent from 0.83 percent in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/10/business/robert-durst-dies/index.html </td>
   <td style="text-align:left;"> 2022-01-11 03:39:00 </td>
   <td style="text-align:left;"> Robert Durst, convicted murderer and subject of HBO's 'The Jinx,' has died  - CNN </td>
   <td style="text-align:left;"> (CNN)Robert Durst, the eccentric millionaire who fascinated viewers as the subject of HBO's documentary series "The Jinx" before being convicted last year of murder, has died in a California prison hospital, according to his longtime attorney Dick DeGuerin. He was 78.                                                                                    , Durst, who had been housed at the California Health Care Facility in Stockton, died of natural causes at 6:44 a.m. on Monday, according to the California Department of Corrections and Rehabilitation.                                                                                                                                                          , The coroner in San Joaquin County will determine an exact cause of death.                                                                                                                                                                                                                                                                                        , Serving a life sentence without the possibility of parole, Durst was treated after being diagnosed with Covid-19 in October. The real estate heir also suffered from a multitude of other ailments, including bladder cancer.                                                                                                                                    , On November 1, a grand jury in New York indicted him for murder in the death of Kathie McCormack Durst.                                                                                                                                                                                                                                                          , The Westchester County, New York District Attorney's Office had hoped Durst would appear in court, and DA Miriam Roach reacted to the news.                                                                                                                                                                                                                      , "After 40 years spent seeking justice for her death, I know how upsetting this news must be for Kathleen Durst's family," Roach said. "We had hoped to allow them the opportunity to see Mr. Durst finally face charges for Kathleen's murder because we know that all families never stop wanting closure, justice and accountability."                         , The DA's office added it plans to make further information surrounding the case available to the public, to the extent allowed by law, in the coming days.                                                                                                                                                                                                       , TV audiences saw pieces of Durst's strange life                                                                                                                                                                                                                                                                                                                  , Durst's bizarre life of fortune and infamy played out before tens of millions of viewers of the HBO series, which aired in 2015.                                                                                                                                                                                                                                 , The fortune came from an inheritance, as Durst was born into a New York City skyscraper empire built by relatives, including his father. The infamy came from the deaths of three people close to him, starting with his first wife, Kathie McCormack Durst.                                                                                                     , In "The Jinx," an eerily calm Durst, along with detectives, friends, and family, discussed McCormack Durst's mysterious disappearance in 1982. Durst said he last saw his wife when he dropped her off at a train station in South Salem, New York, near their weekend home.                                                                                     , She was headed for Manhattan, where she was finishing medical school, Durst said.                                                                                                                                                                                                                                                                                , Kathie's brother, Jim McCormack, and other members of her family screamed murder, alleging Durst physically and mentally abused her. McCormack Durst was declared legally dead in 2017. Her body has not been found.                                                                                                                                             , In a sensational moment in "The Jinx," Durst said he did not want to have children because "somehow I thought that I would be a jinx."                                                                                                                                                                                                                           , Durst was also caught off camera but on a live microphone during the broadcast muttering, "What the hell did I do? Killed them all, of course."                                                                                                                                                                                                                  , His lawyers argued Durst's comments were heavily edited and not uttered in the order in which they are heard in the documentary. But his comments would lead to Durst's arrest for the murder of a longtime friend and confidante, Susan Berman, in her Los Angeles-area home in 2000.                                                                           , Durst was arrested in New Orleans the night before the final episode of the "The Jinx" aired in March 2015, making the finale must-see TV. (HBO, like CNN, is owned by WarnerMedia.)                                                                                                                                                                             , Durst faced charges in multiple deaths                                                                                                                                                                                                                                                                                                                           , Prosecutors said Berman knew that Durst had killed his wife, and he shot and killed his former UCLA classmate to keep her from incriminating him in a scheduled interview with investigators.                                                                                                                                                                    , He repeatedly denied killing Berman, but also swore for years he did not write a highly publicized so-called "cadaver note" that pointed police to Berman's body. Durst's lawyers would later concede their client did write the "cadaver note."                                                                                                                 , His multimillion-dollar defense team asserted their client found Berman's body, panicked, and ran because he thought no one would believe he did not kill his friend. Durst ran far from that crime scene and other troubles, eventually winding up in Galveston, Texas, where he lived in a shabby apartment in a converted house.                              , Durst disguised himself as a woman, pretended to be mute and befriended his across-the-hall neighbor, Morris Black.                                                                                                                                                                                                                                              , Death again seemed to follow Durst, as he wound up on trial for Black's killing. He said it was self-defense when his gun went off in a struggle with Black, whose body was later found cut up in Galveston Bay. A Texas jury acquitted Durst of murder.                                                                                                         , Authorities eventually flew Durst to Los Angeles to stand trial for Berman's murder. While his defense team sought delays and filed motions for mistrials, Durst's health deteriorated.                                                                                                                                                                          , Durst finally went on trial in March 2020 before the trial was suspended for more than a year because of Covid-19.  When he was diagnosed with bladder cancer in 2021, his legal team motioned for a mistrial, arguing he could not competently defend himself from the witness stand in his state of poor health.                                               , But the judge denied the defense motion for mistrial, and several others. The trial finally resumed in May 2021.                                                                                                                                                                                                                                                 , Durst insisted he testify in his defense, a strategy that imploded. Prosecutor John Lewin's withering cross-examination of Durst spread out over nine contentious days. The cross-examination might have gone on longer, but the judge outside the jury's presence limited the prosecution's time, saying the defendant's credibility had already been destroyed., Lewin prompted Durst to say he estimated he perjured himself five times during the trial. When asked if he would lie if he had killed his first wife and his confidante Berman, Durst replied "correct."                                                                                                                                                         , The jury took just seven hours to reach a verdict and convict Durst of first-degree murder.                                                                                                                                                                                                                                                                      , In his last days in court, Durst looked frail and spoke barely above a whisper, bent over in a wheelchair.                                                                                                                                                                                                                                                       , CNN's Sonia Moghe and Jean Casarez contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/btcusd:cur </td>
   <td style="text-align:left;"> 2022-01-11 03:29:00 </td>
   <td style="text-align:left;"> Bitcoin Near 3-Month Low </td>
   <td style="text-align:left;"> Bitcoin hovered around $40,000 in the second week of January, the lowest in 3 months as interest in risky assets such as digital assets and stocks waned on hawkish monetary policy stance from major central banks. After rallying more than 500% since the end of 2019, the bitcoin declined almost 40% from its recent record high of $67,559 hit on November 8th and is almost down 10% so far in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-01-11 03:14:00 </td>
   <td style="text-align:left;"> Swiss Franc Falls to 3-Week Lows </td>
   <td style="text-align:left;"> The Swiss franc fell to 0.93 per USD, the lowest in 3 weeks, amid outlooks of tighter foreign monetary policy and increased sight deposits by the SNB. Minutes of the FOMC’s meeting indicated that the Fed could cut back stimulus faster than previously thought, with potential rate hikes coming in March followed by a balance sheet rundown. At the same time, expectations of high consumer inflation in the US for December strengthened the case for imminent rate hikes. Meanwhile, the ECB slowed the pace of the PEPP in January and confirmed its conclusion in the end of March. Contrarily, the SNB has yet not signaled any policy tightening, as domestic inflation is still well below those of its main trading partners and should maintain negative interest rates through 2022. At the same time, sights deposits in the SNB increased by nearly CHF 2 billion in the week ending January 7th, a possible indication that the central bank is capping the franc’s appreciation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/10/technology/elizabeth-holmes-trial-jurors.html </td>
   <td style="text-align:left;"> 2022-01-11 02:56:30 </td>
   <td style="text-align:left;"> What It Was Like on the Elizabeth Holmes Jury for 18 Weeks - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Away from the media frenzy, jurors dealt with the trial’s disruption to their lives and had little idea of the case’s implications.                                                                                                                                                                                                                                                                                                                                                  , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                              , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                       , By Erin Woo                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SAN JOSE, Calif. — If you wondered what it was like to serve as a juror in Silicon Valley’s trial of the decade, Susanna Stefanek can tell you.                                                                                                                                                                                                                                                                                                                                      , For 18 weeks, Ms. Stefanek juggled her family, her work as an editorial manager at Apple and her duty as one of 12 jurors in the trial of Elizabeth Holmes, the founder of the failed blood testing start-up Theranos. Ms. Holmes, whose case was viewed as a referendum on Silicon Valley’s start-up excesses, was found guilty last week of four of 11 counts of fraud for lying to investors about Theranos’s technology.                                                         , Her case was closely scrutinized because Ms. Holmes was the rare entrepreneur to be indicted, igniting a media frenzy and a zillion hot takes about what her conviction meant — or did not mean — for the tech industry. But for the eight men and four women on the jury, such issues were far from their minds, said Ms. Stefanek and another juror in the case, who declined to be named.                                                                                         , Instead, they said, the trial meant rearranging their lives. Initially anticipated to last 13 weeks, the proceedings stretched on for 18. As other high-profile criminal trials started and finished around the country, Ms. Holmes’s trial schedule was episodic, with testimony sometimes happening three days a week and sometimes not. All the while, jurors were barred from talking about Ms. Holmes or reading media coverage about her.                                      , Inside the federal courthouse in San Jose, Calif., where Ms. Holmes’s trial took place, jurors heard from 32 witnesses, with testimony frequently lasting at least five hours a day. Jurors were fueled by court-provided bagels, fruit cups, juice and coffee, Ms. Stefanek and the other juror said. In their down time, they worked on a puzzle of Georges Seurat’s “A Sunday Afternoon on the Island of La Grande Jatte” and played the tile game Rummikub.                      , “It was like I was living two different lives during the trial: the life where I’d go to court, and the one where I’d sit down at my desk and log in to work as usual,” Ms. Stefanek, 51, said in an interview.                                                                                                                                                                                                                                                                      , She said she had little idea about the trial’s broader implications. “I didn’t realize the impact of this verdict could potentially have an effect on how business is done in Silicon Valley,” Ms. Stefanek said. “It’s actually pretty amazing.”                                                                                                                                                                                                                                    , Four other jurors declined to be interviewed on the record, and seven could not be reached for comment. Ms. Stefanek was earlier interviewed by The Wall Street Journal.                                                                                                                                                                                                                                                                                                             , When Ms. Stefanek was selected for the jury in August, she said, she knew very little about Ms. Holmes, who had founded Theranos in 2003. Ms. Holmes, who had styled herself as a new Steve Jobs, had promised to revolutionize health care with blood tests that could discern various ailments with a few drops of blood. She raised $945 million and became the toast of Silicon Valley before her claims unraveled.                                                              , “I knew she had started a company,” Ms. Stefanek said. “I knew that it had failed. I knew she liked to wear black turtlenecks. That was about it.”                                                                                                                                                                                                                                                                                                                                   , Ms. Holmes’s trial began with opening statements on Sept. 8. That started a new routine for Ms. Stefanek: She often woke up at 5 a.m. to squeeze in some work and pack lunch for her 12-year-old daughter before driving from Mountain View, Calif., where she lives, to the San Jose courthouse.                                                                                                                                                                                    , During testimony, Ms. Stefanek said, she took 541 pages of notes. At times, she said, jurors struggled to stay awake. Other times, they were shocked to see star witnesses like James Mattis, the retired four-star Marine Corps general and former defense secretary, who had served on Theranos’s board.                                                                                                                                                                           , “When he walked in the door, I kind of felt this rustle in the room and I couldn’t believe it,” Ms. Stefanek said. “I was actually more excited about him than I was about Elizabeth Holmes, just because I knew who he was before.”                                                                                                                                                                                                                                                 , Over time, the trial’s schedule became increasingly unpredictable. Judge Edward J. Davila of the Northern District of California, who presided over the case, tacked on extra court sessions and extended days in court, which initially were scheduled to end at 2 p.m., to 3 p.m. and then to 4 p.m.                                                                                                                                                                               , That “made it hard for me to commit to things at work” and “made it more challenging to get some things done,” Ms. Stefanek said, adding that her manager at Apple was understanding.                                                                                                                                                                                                                                                                                                , After closing arguments concluded in December, the jury began deliberating a verdict. They had a method for discussions, Ms. Stefanek said, recapping each witness’s testimony on sheets of paper that were hung around the fifth-floor courtroom where they spent time when the trial was not in session. They also enlisted the courtroom deputy, Adriana Kratzmann, to make photocopies of one juror’s handmade worksheet that listed the criteria for a conviction on each count., To keep up their energy, bagels were supplemented with sandwiches from the nearby Erik’s DeliCafé.                                                                                                                                                                                                                                                                                                                                                                                   , Jurors quickly agreed to find Ms. Holmes guilty of four counts of defrauding investors because she had given information — including inaccurate financial projections and altered reports — that jurors found purposefully misleading, Ms. Stefanek said. They also decided to find her not guilty on four counts of defrauding patients because Ms. Holmes had too much distance from the patients to have intentionally defrauded them, she said.                                  , But they deadlocked on three additional investor counts because they disagreed on whether there was enough evidence that those investors had been lied to, Ms. Stefanek said.                                                                                                                                                                                                                                                                                                        , On Jan. 3, after seven days of deliberations, Judge Davila asked jurors to fill out the verdict form on the eight counts they agreed on. Then they were asked to file into the courtroom so the courtroom deputy could read the verdict.                                                                                                                                                                                                                                             , As the verdict was read, Ms. Stefanek said, she avoided eye contact with Ms. Holmes, who faces up to 20 years in prison for each guilty count.                                                                                                                                                                                                                                                                                                                                       , “It was a stressful moment for me, because even though our work was done and that was a good thing, knowing the impact that our decision was going to have on the defendant’s life was still a burden,” Ms. Stefanek said.                                                                                                                                                                                                                                                           , With the trial over, Ms. Stefanek caught up on months of media coverage and funny tweets, saved for her by a friend. She said she was heartened by analyses praising the jury’s decision. She plans to follow the fraud trial of Ramesh Balwani, Theranos’s chief operating officer and Ms. Holmes’s ex-boyfriend, when it begins in March.                                                                                                                                          , After four months, she could also finally talk about the case. Her daughter, too young to know who Ms. Holmes was, had understood only that Ms. Stefanek was on the jury for a “famous woman.”                                                                                                                                                                                                                                                                                       , “I think it was really good she got to see,” Ms. Stefanek said. “This is how the justice system works.”                                                                                                                                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/beyond-meat-permanently-added-canadian/story.aspx?guid={8FBD970B-1708-4716-A953-069CA8EEC008}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 02:51:23 </td>
   <td style="text-align:left;"> Beyond Meat permanently added to Canadian Pizza Hut menus - MarketWatch </td>
   <td style="text-align:left;"> Beyond Meat Inc. 
        BYND,
        -2.77%
       said Monday that it will become a permanent menu item at Pizza Hut locations across Canada. Beyond Italian Sausage Crumbles will be included on Great Beyond Pizza, Beyond Italian Sausage Alfredo Loaded Flatbread and Beyond Creamy Alfredo. The companies conducted a test in Edmonton and Toronto last summer. Pizza Hut is part of the Yum Brands Inc. 
        YUM,
        -1.40%
       portfolio. The two companies introduced Beyond Fried Chicken at KFC locations across the U.S. on Monday, for a limited time and while supplies last. Beyond Meat stock has dropped 44.2% over the past year. Yum Brands shares are up 24.5%. And the S&amp;P 500 index 
        SPX,
        -0.14%
       has gained 20.8% for the period., Wedbush analyst Dan Ives is looking ahead to earnings season. Here's what he says Wall Street needs to get back to bullishness on tech.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/jamie-dimon-sees-the-best-economic-growth-in-decades-more-than-4-fed-rate-hikes-this-year.html </td>
   <td style="text-align:left;"> 2022-01-11 02:48:05 </td>
   <td style="text-align:left;"> Jamie Dimon sees the best economic growth in decades, more than 4 Fed rate hikes this year </td>
   <td style="text-align:left;"> , Jamie Dimon said the U.S. is headed for the best economic growth in decades.                                                                                                                                                                           , "We're going to have the best growth we've ever had this year, I think since maybe sometime after the Great Depression," Dimon told CNBC's Bertha Coombs during the 40th Annual J.P. Morgan Healthcare Conference. "Next year will be pretty good too.", Dimon, the longtime CEO and chairman of JPMorgan Chase, said his confidence stems from the robust balance sheet of the American consumer. JPMorgan is the biggest U.S. bank by assets and has relationships with half of the country's households.     , "The consumer balance sheet has never been in better shape; they're spending 25% more today than pre-Covid," Dimon said. "Their debt-service ratio is better than it's been since we've been keeping records for 50 years."                            , Dimon said growth will come even as the Fed raises rates possibly more than investors expect. Goldman Sachs economists predicted four rate hikes this year and Dimon said he would be surprised if the central bank didn't go further.                 , "It's possible that inflation is worse than they think and they raise rates more than people think," Dimon said. "I personally would be surprised if it's just four increases."                                                                        , Dimon has expressed expectations for higher rates before. Banks tend to prosper in rising-rate environments because their lending margins expand as rates climb.                                                                                       , Indeed, bank stocks have surged so far this year as rates climbed. The KBW Bank Index jumped 10% last week, the best start to a year on record for the 24-company index.                                                                               , However, Dimon said that while the underlying economy looks strong, stock market investors may endure a tumultuous year as the Fed goes to work.                                                                                                       , "The market is different," Dimon said. "We're kind of expecting that the market will have a lot of volatility this year as rates go up and people kind of redo projections."                                                                           , "If we're lucky, the Fed can slow things down and we'll have what they call a `soft landing'," Dimon added.                                                                                                                                            , The bank was forced to move its annual healthcare conference to a virtual format because of the spread of the omicron variant of Covid-19.                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-11 02:39:00 </td>
   <td style="text-align:left;"> Oil Slips as Supply Concerns Ease </td>
   <td style="text-align:left;"> WTI crude futures slipped more than 0.5% to below $78.5 per barrel on Monday, extending losses for a second consecutive session as production resumed in Libyan and Kazakhstan, but still, prices remain near a 7-week high after a strong rally last week. Libyan production rose to 900,000 barrels a day after maintenance in a major pipeline was completed, while some output was restored in Kazakhstan following unrest that interrupted supplies last week. Meanwhile, demand concerns resurfaced again after China began a city-wide testing campaign in the port city of Tianjin after 20 people tested positive as the country maintains its zero-tolerance approach to Covid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-end-slightly-higher/story.aspx?guid={BD6E649B-B76F-4C1B-AE59-6F7F0639EB78}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-11 02:36:08 </td>
   <td style="text-align:left;"> Gold futures end slightly higher, but hold below $1,800 an ounce - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled with a slight gain on Monday, finding support after posting their worst weekly loss since late November. Prices, however, marked a third straight finish below the key $1,800 mark, pressured by strength in the U.S. dollar and Treasury yields. February gold 
        GCG22,
        +0.30%
       rose $1.40, or nearly 0.1%, to settle at $1,798.80 an ounce, after briefly tapping a high at $1,802. , 'I know it was unintentional, but Steven Spielberg couldn't have written and directed a better script,' DraftKings sportsbook director Johnny Avello said.                                                                                                                                                                                                                                                                         , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-11 02:10:39 </td>
   <td style="text-align:left;"> Russian 10Y Bond Yield Rebounds </td>
   <td style="text-align:left;"> The yield on the 10-year OFZ treasury bond rose to 8.6% on the second week of January, not far from the 3-year high of 8.66% touched on November 23rd, amid growing geopolitical tensions and expectations of tighter policy in the United States. Military tension in the Russia-Ukraine border led US President Biden to say the United States will “respond decisively” if Russia further invades Ukraine. At the same time, the Federal Reserve could hike federal fund rates as early as March. Meanwhile, the Bank of Russia raised its key rate by 100bps to 8.5% on its last meeting, December 17th, but expectations that the policy rate could be close its peak and will ease through 2022 should increase foreign demand of Russian debt instruments. The central bank estimated inflation to be at 8.1% on mid-December, but on track to edge down to 4%-4.5% by the end of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/luxembourg/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-11 02:03:44 </td>
   <td style="text-align:left;"> Luxembourg Inflation Rate Eases on December </td>
   <td style="text-align:left;"> Luxembourg’s annual inflation rate eased to 4.1 percent in December of 2021 from 4.5 percent in the previous month. It was the first decrease in consumer inflation June, as prices rose at a slower rate for housing and utilities (8.3 percent vs 9.6 percent in November), transportation (7.9 percent vs 9.4 percent), and recreation and culture (2.3 percent vs 3.5 percent). On the other hand, consumer prices accelerated for food and non-alcoholic beverages (2.3 percent vs 1.4 percent), and hotels and restaurants (3.2 percent vs 2.9 percent). On a monthly basis, consumer prices declined 0.1 percent, compared to the 0.7 percent increase in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/stocks-making-the-biggest-moves-midday-moderna-zynga-lululemon-tilray-and-more.html </td>
   <td style="text-align:left;"> 2022-01-11 02:01:59 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Moderna, Zynga, Lululemon, Tilray and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                            , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                , Zynga, Take-Two Interactive — Shares of the mobile gaming company Zynga soared 40.6% after Take-Two Interactive, another gaming company, revealed plans to buy it for $12.7 billion, or $9.86 a share, in a cash and stock deal. That's a roughly 64% premium to Zynga's closing price Friday. Shares of Take-Two tumbled by 13.1%.                                        , Moderna — Moderna shares jumped 9.2% after the company's CEO said Monday that it's working on a booster that targets the omicron variant of Covid-19 "with public health leaders around the world," targeting a fall rollout. The booster will enter clinical trials soon, he added.                                                                                       , Lululemon — Shares of the athletic apparel maker shed 1.9% after the company said it now expects weaker results for the fourth quarter due to the omicron Covid-19 variant. Lululemon said Monday that its fourth-quarter earnings and revenue to come in at the low end of its projected ranges as staffing shortages and reduced store hours are weighing on results.    , Apria — Home health-care company Apria saw its shares surge 26.1% following news it will be acquired by health-care equipment company Owens &amp; Minor for about $1.45 billion in cash, or $37.50 per share. Owens &amp; Minor shares gained about 3%.                                                                                                                            , Tilray — The cannabis stock surged 13.5% after the company reported an unexpected quarterly profit. Tilray said its revenue increased by about 20% from a year earlier on stronger demand for cannabis products.                                                                                                                                                           , Beam Therapeutics — Beam, the gene-editing company, saw its shares fall 2.7% following news about a partnership with Pfizer. The two will collaborate to develop therapies for rare genetic diseases. Pfizer shares rose slightly.                                                                                                                                         , Cardinal Health — The health-care company saw its shares drop 5.9% after it provided a full-year 2022 update saying it expects to see more inflationary impacts and lower volumes as a result of global supply chain constraints. The company's pricing actions are also expected to offset those impacts less than it expected.                                           , Shockwave Medical — Shares of Shockwave Medical rose 4.5% after Bloomberg reported rival medical device maker Penumbra is exploring a merger. However, a Penumbra representative said in a statement to Bloomberg that it is not in discussions with Shockwave to pursue a business combination or similar transaction.                                                    , Airbnb — Shares of Airbnb retreated 3.2% after Piper Sandler downgraded the stock to a neutral rating from overweight. The firm also cut its price target on the stock. Piper Sandler said travel patterns should return to pre-pandemic trends in 2022 and consumers are more interested in traditional lodging and air service companies.                                , Crypto stocks — Crypto-related stocks fell sharply on Monday as the price of bitcoin briefly tumbled to its lowest point since September. Coinbase declined 3.1% while Silvergate Capital lost 4%. MicroStrategy fell slightly and Block slid 3.8% before bouncing back. The moves come amid a broader sell-off in risky assets as the 10-year U.S. Treasury yield climbed.,  — CNBC's Yun Li and Hannah Miao contributed reporting                                                                                                                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/half-of-teachers-consider-quitting-jobs-survey-shows </td>
   <td style="text-align:left;"> 2022-01-11 01:19:46 </td>
   <td style="text-align:left;"> Half of teachers consider quitting jobs, survey shows </td>
   <td style="text-align:left;"> FOX Business' Jackie DeAngelis reports on why people are not valuing the profession anymore.                                                                                                                                                                  , A recent survey showed that nearly half of teachers are currently considering quitting their jobs with about a third of those surveyed saying they might leave the profession entirely.                                                                       , Data from Teachers Pay Teachers, an online forum for curriculum content for teachers, revealed that 48% of 6,000 teachers surveyed in November said they had considered changing jobs in the past month, an increase from 32% in June, K-12 Dive reported.    , The outlet noted that 34% of those teachers surveyed said they considered changing careers in the past month and 11% said they considered taking a leave of absence.                                                                                          , "Ten years ago, the program enrollment for traditional ed [education] programs started to decrease," Dr. Heather Sparks, director of teacher education at Oklahoma City University, said in an interview that aired on "Varney and Co." on Monday.            , TEACHER SHORTAGES IMPACTING SCHOOLS NATIONWIDE                                                                                                                                                                                                                , "People are just not valuing the profession anymore," she added. "These are folks who put in four years and then some, continue to get training even after their degree and yet are paid minimally compared to other professions who have four-year degrees." , Schools across the U.S. say they are dealing with significant teacher shortages, and some principals are saying the start of the school year has been the most difficult one yet.                                                                             , Officials are pointing to an array of factors that have converged to create the vacancies in the wake of COVID-19, and experts warn the problem may not be fixed any time soon.                                                                               , Party Panel examines the key voter issues in close Virginia election on ‘Kennedy.’                                                                                                                                                                            , Administrators are being called into the classroom in some districts dealing with teacher shortages, and several places are calling on retirees to step in and fill the voids.                                                                                , As teachers continue to flee the profession, studies show fewer college students are pursuing education degrees – a trend researchers had seen long before COVID-19 hit.                                                                                      , Enrollment in education programs at Louisiana colleges has fallen by nearly 8,000 students over the past two decades, according to statewide enrollment data from the Louisiana Board of Regents.                                                             , The pandemic is not the sole reason why teachers are leaving the profession, but it has contributed to the burnout that has been common among educators for years.                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                   , "Teachers, because of COVID and other reasons, are under a lot of stress," teacher and president of the Lafayette Parish Association of Educators Julia Reed said at a school board meeting Oct. 6, according to the Lafayette Daily Advertiser.              , Reed noted that when she speaks with teachers "their No. 1 issue is not money; it's workload."                                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                       , FOX Business’ Breck Dumas contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 01:16:00 </td>
   <td style="text-align:left;"> FTSE Falls 0.5% on Monday </td>
   <td style="text-align:left;"> FTSE 100 shed 0.5% to close at 7,445 on Monday, in line with its European peers, as investors across the globe traded cautiously awaiting another US inflation print later this week that could provide further guidance on the Federal Reserve's monetary policy path. US policymakers are now expected to raise interest rates four times this year as the CPI is seen hitting a near four-decade high of 7% year-on-year in December. Domestically, Britain ordered housebuilders to pay around $5.4 billion to remove dangerous cladding from buildings after a deadly fire in 2017, dragging down Persimmon (-5.2%), Barratt Developments (-4%), Berkeley Group (-3.6%), and Taylor Wimpey (-3.5%). On the other hand, a weaker pound boosted gains in larger dollar earners such as British American Tobacco (1.7%), Unilever (0.8%), and Reckitt Benckiser (0.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 00:48:00 </td>
   <td style="text-align:left;"> Sell-Off in Italian Stocks Continues </td>
   <td style="text-align:left;"> The FTSE MIB Index erased early gains to close 1% lower at 27,354 on Monday, amid concerns of rising inflation and expectations of interest rate hikes, while investors await US Consumer price data on Wednesday. The United States' CPI from December is expected to rise to a four-decade high of 7% on the year, strengthening expectations for tighter monetary policy from the Federal Reserve and potential rate hikes in March. Shares from the technology sector, which typically benefit on looser monetary policy, were sold-off across Europe and North America, with STMicroelectronics (-4.5%) and Nexi (-4.8%) taking the biggest losses in the Milan exchange. At the same time, healthcare stocks closed 3.1% down, led by Amplifon (-4.4%) and DiaSorin (-4.3%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 00:47:00 </td>
   <td style="text-align:left;"> European Shares End Lower </td>
   <td style="text-align:left;"> European shares finished lower on Monday extending their first weekly drop in three weeks last Friday, amid concerns over a sooner-than-anticipated rate hike, rising inflation and fast-spreading Omicron. Across sectors, technology led losses with a 2.3% fall, while banks gained from the expectations of tighter monetary policy. On corporate news, French consulting technology firm Atos slid 16.8% after warning it would miss its annual profit targets. On the data front, the Eurozone unemployment rate inched down to 7.2% in November, from 7.3% in the prior month, while investor morale in the bloc improved in January. Looking ahead, investors await the US inflation report due Wednesday, which is expected to show the largest increase in consumer prices in nearly four decades and might prompt the Federal Reserve to hike rates in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-11 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Close Down For a 3rd Session </td>
   <td style="text-align:left;"> The CAC 40 Index fell 1.4% to close at 7,116 on Monday, amid losses in the tech sector, while investors await US consumer inflation data on Wednesday. The annual inflation rate in US is expected to hit a four-decade high of 7%, furthering expectations that a hike in the federal funds rate could come earlier than expected. On the corporate front, Atos lost 16.8% after the firm reported sales to be 2.4% lower than its financial target presented last summer at EUR 10.8 billion, even though the IT service provider was betting on stable returns. Other firms in the tech sector, which particularly benefited from lower interest rates, traded on the red, dragged by STMicroelectronics (-4%), Capgemini (-2.7%), and Dassault Systemes (-2.1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-01-11 00:45:03 </td>
   <td style="text-align:left;"> Mexican Peso Slips From 2-Month High </td>
   <td style="text-align:left;"> The Mexican peso traded around 20.45 per USD, slightly weakening from a two-month high of 20.367 hit on January 7th, tracking a fall in Latam currencies and lower oil prices. Prospects of higher US rates are weighing on investors' sentiment as the odds are rising that the Fed will raise the fed funds four times this year instead of three as previously signaled from the Central bank. Also, the US consumer prices data, due on January 12th, is awaited so traders can assess further clues on US policy rate hike timing. Domestically, the rapid spread of Covid-19 cases also helped to dent the sentiment after the country keeps recording record-high daily cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-01-11 00:37:00 </td>
   <td style="text-align:left;"> Brazilian Real Weakens Slightly </td>
   <td style="text-align:left;"> The Brazilian Real traded above 5.65, weakening from a near 1-week high of 5.6355 hit on January 7th, tracking a fall in Latam currencies and lower Iron ore prices. Prospects of higher US rates are weighing on investors' sentiment as the odds are rising that the Fed will raise the fed funds four times this year instead of three as previously signaled from the Central bank. Also, the US consumer prices data, due on January 12th, is awaited so traders can assess further clues on US policy rate hike timing. Meanwhile, in Brazil, the IPCA for December is on investors’ radar to see whether the decline observed in November persists. Nevertheless, the inflation rate is expected to remain at a six-year high, which puts pressure on the central bank to keep a hawkish policy stance with higher rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/czech-republic/unemployment-rate </td>
   <td style="text-align:left;"> 2022-01-11 00:16:16 </td>
   <td style="text-align:left;"> Czech Jobless Rate Inches Up in December </td>
   <td style="text-align:left;"> The Czech unemployment rate inched up to 3.5 percent in December of 2021 from 3.3 percent in the previous month, as expected. The number of job seekers rose to 258,173, 12,624 more than the previous month, whilst the number of job vacancies decreased by 1,692 thousand to 343,148. In December of 2020, the unemployment rate was 4.0 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-11 00:12:00 </td>
   <td style="text-align:left;"> Canadian Dollar Remains Weak </td>
   <td style="text-align:left;"> The Canadian dollar traded above 1.265, weakening from a 1-week high of 1.2643 hit on January 7th, as investors sentiment was hit by prospects of higher US rates, while also lower oil prices weighed on the loonie. In the US, traders are betting on higher interest rates and the odds are rising that the Fed will raise the fed funds rate four times this year instead of three as the central bank signalled early. Meanwhile, investors await US consumer price data, due on January 12th, for an indication of policy rate hikes by the Fed. The American inflation rate from December is expected to come at 7%, a four-decade high. Also, the confirmation hearing for Fed Chair Powell, and speeches from several other policymakers are on investors' radar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/inflation-expectations </td>
   <td style="text-align:left;"> 2022-01-11 00:08:00 </td>
   <td style="text-align:left;"> US Inflation Expectations Remain at Record High </td>
   <td style="text-align:left;"> US consumer inflation expectations for the year ahead remained at a record 6% in December of 2021, the same as in November. Home price expectations rose to 5.5% from 5% in November but remained below their May 2021 peak. Also, uncertainty and disagreement about future inflation decreased and expectations about year-ahead price changes fell by 3.5 percentage points for the price of gas (to 5.7%), 1.4 percentage points for food (to 7.8%), and 1.0 percentage point for the cost of a college education (to 8.1%). At the same time, households reported increased optimism about their labor market prospects, with earnings growth, job loss, and job finding expectations all improving. Households' income growth expectations also improved, rising to a new series high. Meanwhile, the medium-term three-year inflation expectations were also steady at 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/czech-republic/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 23:59:54 </td>
   <td style="text-align:left;"> Czech Republic 10Y Bond Yield Hits 9-1/2-year High </td>
   <td style="text-align:left;"> Czech Republic 10 Year Government Bond Yeld increased to a 9-1/2-year high of 3.336% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wind </td>
   <td style="text-align:left;"> 2022-01-10 23:58:11 </td>
   <td style="text-align:left;"> Wind Energy Index Hits 13-month Low </td>
   <td style="text-align:left;"> Wind Energy Index decreased to a 13-month low of 320.77 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 23:55:00 </td>
   <td style="text-align:left;"> South African Stocks Little Changed </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index finished around the flatline to close at 73,913 on Monday, as gains on financials and commodity-backed shares were offset by worries of higher rates in the US. Investors await for US consumer price data due Wednesday for an indication on policy rate hikes by the Fed and future gold prices. The American inflation rate from December is expected to come at 7%, a four-decade high. On the corporate front, Impala Platinum (2.2%), and Anglo American (1.3%) booked gains, tracking higher bullion prices at the begging of the session, while Exxaro Resources (1.3%) rose on higher coal prices. On the other hand, Kumbala (-1.1%) fell amid lower coal prices. Meanwhile, traders keep an eye on the possible tariffs to be implemented for state-owned utility Eskom. The National Energy Regulator of South Africa pro forma implementation plans show tariffs could increase to 40.38% or 41.18%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-10 23:54:50 </td>
   <td style="text-align:left;"> Portugal Posts Largest Trade Gap in 11 Years </td>
   <td style="text-align:left;"> Portugal’s trade deficit widened significantly to EUR 2.097 billion in November of 2021 from EUR 0.935 billion in the same month last year, the largest trade gap since December 2010. Imports surged 32.3 percent year-on-year to EUR 8.107 billion, on the back of industrial supplies (39.7 percent to EUR 2.573 billion), capital goods (14.6 percent to EUR 1.405 billion); and consumer goods (21.6 percent to EUR 1.167 billion). Among major import suppliers, purchases rose sharply from both Spain (27.6 percent) and Germany (11.1 percent), whilst less significantly from France (4.2 percent). Meanwhile, exports jumped 15.7 percent to EUR 6.010 billion, driven by sales of industrial supplies (32.8 percent to EUR 2.045 billion); transport material &amp; equipment (2.0 percent to EUR 1.142 billion), and consumer goods (13.7 percent to EUR 1.080 billion). The three main export destinations saw double-digit growth, namely Spain (23.2 percent), France (14.6 percent) and Germany (23.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-59939536?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-10 23:53:01 </td>
   <td style="text-align:left;"> Tesla adds chill and assertive self-driving modes </td>
   <td style="text-align:left;"> Tesla's automated driver assist feature has added an assertive driving mode.                                                                                                                                                                                                                             , The setting will follow other cars more closely, change lanes more frequently, not leave the overtaking lane, and perform rolling stops.                                                                                                                                                                 , Such driver behaviour by humans is often discouraged by safety groups.                                                                                                                                                                                                                                   , However, it could sometimes be safer for an automated system to be more assertive, like a human driver, rather than being overly cautious, one motor safety expert said.                                                                                                                                 , The three driving profiles - chill, average, and assertive - were first added in Tesla's October update. That update, however, was quickly pulled because of other issues, but the driving profiles feature has now been restored.                                                                       , A screenshot of the update was posted to Twitter by David Zipper, a technology writer and visiting fellow at Harvard Kennedy School, and was first reported by The Verge.                                                                                                                                , It shows the assertive mode described as: "Your Model X will have a smaller follow distance, perform more frequent speed lane changes, will not exit passing lanes and may perform rolling stops."                                                                                                       , The list of behaviours has been criticised by some on social media as being less safe.                                                                                                                                                                                                                   , But Matthew Avery, from the UK's Thatcham Research, said that well-designed driverless systems are theoretically safer than human drivers because they eliminate human error.                                                                                                                            , As such, if a more assertive driving style encourages more drivers to take up self-driving systems than a very cautious style would, that could be a net gain for safety.                                                                                                                                , "If we want widespread adoption of automation, drivers are going to expect the vehicle to do and make the decisions that you would do as a human driver, not some very benign and very safe algorithm," he explained.                                                                                    , Human drivers come to an impasse regularly, such as when one has to pull over in a single-lane country road or at a four-way intersection, and one driver must make the move first. Two extremely careful automated cars might both wait for the other to act.                                           , "This is what the manufacturers are trying to learn at the moment," Mr Avery explained.                                                                                                                                                                                                                  , "So, a degree of being slightly less cautious, If that means more people use the systems more of the time because they feel that they're more human-like, that's a good thing."                                                                                                                          , This video can not be played                                                                                                                                                                                                                                                                             , But he warned that it depends on how "assertive" the system is - and said it must avoid aggressive driving.                                                                                                                                                                                              , "It's a fine line between assertive and aggressive, but definitely there are situations when automation going through some very basic rules will eventually sort of stop because it just can't progress," he said.                                                                                       , "I don't think we're there yet. I don't think the technology is sophisticated enough."                                                                                                                                                                                                                   , In many jurisdictions, failing to come to a complete halt at a stop line is illegal, and can result in someone failing their driving test. As a habit, many drivers simply come to a slow crawl - or a rolling stop - instead, but it is considered a dangerous technique.                               , These appear to be part of both Tesla's average and assertive modes. The description that the car "will not exit passing lanes" also seems to contradict some regional rules.                                                                                                                            , Tesla's so-called "Full Self-Driving" feature is currently only available in the US as part of a limited test.                                                                                                                                                                                           , But in the US, where they drive on the right, several states - but not all - have made it illegal to leave the right-hand lane unless overtaking. Similarly, in the UK, the Highway Code says motorists should always stay in the left lane unless overtaking, and return to the left when safe to do so., It is not clear if Tesla's system will account for national or state-based variations in the rules about staying in the overtaking lanes, or what the term rolling stops means in relation to stop signs.                                                                                                , The company has disbanded its media relations department and does not respond to queries from journalists.                                                                                                                                                                                               , Tesla's so-called full self-driving has been subject to much scrutiny, with crashes and incidents involving the technology gaining widespread media coverage.                                                                                                                                            , It is not, despite its name, a self-driving technology, but is rather considered a driver assistance feature similar to other car-makers' lane assist technology. It is at level two on a five-point scale of automated systems.                                                                         , Tesla owners must remain in control of the vehicle and alert at all times, ready to take over in an instant for safety.                                                                                                                                                                                  , What is it really like to live in Dubai?                                                                                                                                                                                                                                                                 , The unusual way a parasite attracts pollinators                                                                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 23:53:00 </td>
   <td style="text-align:left;"> Ukraine Inflation Rate Slows to 6-Month Low of 10% in December </td>
   <td style="text-align:left;"> The annual inflation rate in Ukraine edged down to 10 percent in December of 2021 from 10.3 percent in the previous month, below market expectations of 10.2 percent. It was the lowest inflation rate since June, as cost slowed for food and non-alcoholic beverages (12.7 percent vs 13.3 percent); housing and utilities (9.8 percent vs 10 percent); and transport (11.1 percent vs 12.1 percent). On the other hand, prices advanced faster for household furnishings (4.2 percent vs 4 percent); education (17 percent vs 16.9 percent) and restaurants and hotels (9 percent vs 8.6 percent). Meanwhile, inflation was steady for communication (at 7.4 percent) and healthcare (at 6.1 percent) whereas prices continued to decline for clothing and footwear (-3.5 percent vs -4.5 percent). On a monthly basis, consumer prices rose 0.6 percent, slowing from a 0.8 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tanzania/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 23:51:21 </td>
   <td style="text-align:left;"> Tanzania Annual Inflation Rate at Over 4-Year-High </td>
   <td style="text-align:left;"> Tanzania’s annual inflation rate rose to 4.2 percent in December of 2021 from 4.1 percent in the previous month. It was the highest inflation rate since November of 2017, mainly due to the higher prices of food &amp; non-alcoholic beverages (4.9 percent vs 4.4 percent in November); transport (5.9 percent vs 5.4 percent); housing &amp; utilities (3.9 percent vs 4 percent); clothing &amp; footwear (4.5 percent vs 5.5 percent); and restaurants &amp; hotels (4.9 percent vs 5.3 percent). On a monthly basis, consumer prices were up 0.8 percent, after a 0.5 percent uptick in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/elizabeth-warren-federal-reserve-jerome-powell-trading-scandal </td>
   <td style="text-align:left;"> 2022-01-10 23:50:46 </td>
   <td style="text-align:left;"> Elizabeth Warren demands Fed's Powell release more details on trading scandal </td>
   <td style="text-align:left;"> Scott Crowe, chief investment strategist at CenterSquare Investment Management, weighs in on expected action by the Federal Reserve, which includes several rate hikes this year.                                                                                                                                                                                                                                                                                                , Sen. Elizabeth Warren called on the Federal Reserve in a Monday letter to release more information about financial trades made by several top officials at the onset of the coronavirus pandemic, when the central bank was pumping trillions of dollars into the U.S. economy.                                                                                                                                                                                                  , The Massachusetts Democrat, who sits on the powerful Senate Banking Committee, made the request after a New York Times report revealed that Richard Clarida, the Fed's departing vice chair, failed to initially disclose the extent of a financial transaction he made in early 2020, suggesting that he was actively trading just days before Chairman Jerome Powell suggested the central bank may swoop in to prop up in the economy.                                        , FED EYES FASTER INTEREST RATE LIFTOFF, BALANCE SHEET REDUCTION                                                                                                                                                                                                                                                                                                                                                                                                                   , "I am deeply concerned that your continued refusal to release information about Fed officials’ trading is at odds with your stated commitment to address the scandal ‘forthrightly and transparently’ and that, particularly in light of the new report, it raises suspicions that the Fed may be failing to disclose the full scope of the scandal to the public," Warren wrote in the letter.                                                                                  , Sen. Elizabeth Warren, D-Mass., talks to Federal Reserve Chairman Jerome Powell before a Senate Banking, Housing and Urban Affairs Committee hearing on the CARES Act on Capitol Hill, Tuesday, Sept. 28, 2021 in Washington.  (Kevin Dietsch/Pool via AP / AP Newsroom)                                                                                                                                                                                                         , Clarida, whose term is set to end Jan. 31, had already drawn scrutiny for moving between $1 million and $5 million out of a bond fund into a stock fund on Feb. 27, 2020, one day before Powell pledged that the Fed would take whatever action was needed to shore up the economy. But Clarida later revealed that he had sold between $1 million and $5 million in the same stock fund three days prior to buying it; he later said it was an "inadvertent error."             , The revelation marked the latest in a string of ethics scandals plaguing the central bank after two Fed policymakers – Robert Kaplan, president of the Federal Reserve Bank of Dallas, and Eric Rosengren, president of the Federal Reserve Bank of Boston – bought and sold stocks and real estate-tied assets last year as the central bank undertook aggressive policy action to bolster the economy                                                                          , Kaplan traded millions of dollars of stock in companies, including Apple, Amazon and Google, while Rosengren traded in stocks and real estate investment trusts, according to financial disclosure forms. Both men resigned following the controversy (although Rosengren cited health reasons for his early departure).                                                                                                                                                         , In the wake of the trading scandal, Powell acknowledged the U.S. central bank's current rules dictating what its officials are allowed to invest in and trade are "not adequate" and need to be updated. The rules, which ban senior officials from owning bank stocks, limit trading around monetary policy meetings and warn against any activity that could suggest a conflict of interest, are crucial to ensuring the public's trust in the U.S. central bank, Powell said. , In this Sept. 30, 2021, file photo, Federal Reserve Chairman Jerome Powell testifies during a House Financial Services Committee hearing on Capitol Hill in Washington.  (Sarah Silbiger/Pool Photo via AP, File / Associated Press)                                                                                                                                                                                                                                             , "We need to make changes, and we're going to do that as a consequence of this," Powell told reporters in September following the Fed's two-day policy-setting meeting. "No one is happy about this."                                                                                                                                                                                                                                                                             , Warren has also called on the Securities and Exchange Commission to investigate the Fed officials' trading to determine if it violated insider trading rules and had previously asked the central bank to disclose all ethics communications provided to officials in 2020 and 2021.                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                      , "As new details about the trading scandal are uncovered, your continued refusal to release this information severely compounds concerns about the Fed’s lack of transparency and your commitment to fully and honestly addressing the Fed’s broken ethics culture," she wrote.                                                                                                                                                                                                   , Warren requested a response by Jan. 17.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 23:41:47 </td>
   <td style="text-align:left;"> Macedonia Inflation Rate Quickens to Over 10-1/2-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Macedonia rose to 4.9 percent in December of 2021 from 4.1 percent in the previous month, quickening to its highest level since May of 2011. Main upward pressure came from transport charges (16.8 percent);  prices of food &amp; non-alcoholic beverages (6.9 percent); restaurants &amp; hotels (5.7 percent); recreation &amp; culture (3.2 percent). On the other hand, prices went down in communication (-0.7 percent); and education (-0.2 percent). On a monthly basis, consumer prices ticked up 0.4 percent in December, following a  0.5 percent rise in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-01-10 23:41:19 </td>
   <td style="text-align:left;"> Bulgaria Retail Sales Rise for 9th Straight Month </td>
   <td style="text-align:left;"> Retail sales in Bulgaria advanced 6.7 percent year on year in November of 2021, easing from a 7.6 percent rise in the previous month, pointing to the ninth monthly expansion in retail sales. Sales rose for both food, beverage &amp; tobacco (9.6 percent) and non-food products (4.1 percent), namely pharmaceuticals and medical goods, cosmetics and toilet articles (21.9 percent);  non-specialised stores with food, beverages or tobacco predominating (11.6 percent); sale via mail order houses or via internet (10.4 percent); and automotive fuel (9.9 percent). On a monthly basis, retail sales edged up 0.5 percent, following an upwardly revised 1 percent rise in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/construction-output </td>
   <td style="text-align:left;"> 2022-01-10 23:40:51 </td>
   <td style="text-align:left;"> Bulgaria Construction Output Rebounds in November </td>
   <td style="text-align:left;"> Construction output in Bulgaria rebounded 3.2 percent over a year earlier in November 2021, from a downwardly revised 2 percent decline in the previous month as both civil engineering (3.1 percent vs -1.9 percent in October), and building activity (3.3 percent vs -2 percent) rose faster. On a seasonally adjusted monthly basis, construction output rose 1.9 percent, after a 0.6 percent fall in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/romania/interest-rate </td>
   <td style="text-align:left;"> 2022-01-10 23:36:00 </td>
   <td style="text-align:left;"> Romania Hikes Key Interest Rate As Expected </td>
   <td style="text-align:left;"> The National Bank of Romania raised its benchmark interest rate by 25 bps to 2% at its January meeting strictly as expected, sticking with its gradual approach towards rate hikes. The deposit rate was kept at 1% whereas the lending facility rate was raised by 50 bps to 3%. The bank said it will maintain firm control over money market liquidity and aims to restore and maintain the annual inflation rate in line with its target range of 2.5% ±1%. At the same time, the NBR board keep the current levels of minimum required reserve ratios for liabilities in lei and foreign currency of credit institutions. Policymakers see inflation to rise gradually and stay above the upper limit of the target range in the coming months due to supply shocks, higher energy prices, and the economic activity is expected to stagnate, implying a significant decline in annual GDP dynamics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/industrial-production </td>
   <td style="text-align:left;"> 2022-01-10 23:27:41 </td>
   <td style="text-align:left;"> Sweden Industrial Output Growth Eases in November </td>
   <td style="text-align:left;"> Sweden's industrial output rose 4.2 percent year-on-year in November of 2021, easing from an upwardly revised 4.4 percent increase in the previous month. It was the tenth straight month of growth of industrial production, underpinned by the manufacturing industry (4.3 percent vs 5.2 percent in October), while mining &amp; quarrying output rebounded from a sharp drop (3.8 percent vs -14.0 percent). On a seasonally adjusted monthly basis, industrial production edged up 0.5 percent, slowing from a 1.7 percent gain in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 23:15:30 </td>
   <td style="text-align:left;"> Canada Stocks Dip on Tech &amp; Oil Stocks </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, fell to three-week lows below the 21,000 mark, amid a global risk-off sentiment fueled by growing concerns that the Federal Reserve will bring forward rate hike plans. Technology stocks dipped 2.3%, falling for the sixth session in a row as bond yields continue to rally, while the energy sector dipped 0.7% amid weaker oil prices. On the other hand, cannabis producer Tilray surged almost 20% after posting a surprise profit of $6 million for the quarter ended November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/industrial-production </td>
   <td style="text-align:left;"> 2022-01-10 23:14:07 </td>
   <td style="text-align:left;"> Belgium Industrial Output Growth Eases in November </td>
   <td style="text-align:left;"> Belgium’s industrial production rose 8.9 percent year-on-year in November of 2021, easing from an upwardly revised 12.6 percent increase in October. It was the slowest increase since March, as industrial growth eased for manufacturing, the dominant sector (9.2 percent vs 12.8 percent in October), and utilities (6.6 percent vs 11.9 percent). On the other hand, output contracted at a slower pace for mining and quarrying (-0.4 percent vs -3.5 percent). On a seasonally adjusted monthly basis, production fell 4.4 percent, from a 1.5 percent increase in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/wholesale-inventories </td>
   <td style="text-align:left;"> 2022-01-10 23:07:00 </td>
   <td style="text-align:left;"> US Wholesale Inventories Rise More than Initially Thought </td>
   <td style="text-align:left;"> Wholesale inventories in the United States rose 1.4 percent from a month earlier to $771.09 billion in November of 2021, above a preliminary estimate of 1.2 percent. Increases were seen in inventories of durables (2.1 percent), namely machinery (1.2 percent), automotive (2.7 percent) and professional equipment (0.9 percent). Also, stocks of nondurable goods went up 0.3 percent, particularly groceries (2.6 percent), apparel (3.9 percent) and paper (1.5 percent). On a yearly basis, wholesale inventories advanced 15.9 percent in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/10/business/media/symone-sanders-msnbc.html </td>
   <td style="text-align:left;"> 2022-01-10 23:01:03 </td>
   <td style="text-align:left;"> Symone Sanders, a Strategist for Biden and Harris, Is Joining MSNBC - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                 , Ms. Sanders, 32, will host a weekend show on the cable network, one of the first big programming moves by MSNBC’s president, Rashida Jones.                                                                                                                                                                                                                                                                                                  , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                      , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                               , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                                                       , Symone D. Sanders, the former chief spokeswoman for Vice President Kamala Harris, is joining MSNBC as an anchor and will host a new weekend program on the cable channel, the network said on Monday.                                                                                                                                                                                                                                        , Ms. Sanders, 32, who left her post with Ms. Harris at the end of December, is the most prominent member of the Biden White House to shift from politics into a full-time job in the news media.                                                                                                                                                                                                                                              , The format, title and time slot of her MSNBC program, which will air on Saturdays and Sundays starting in the spring, are to be determined. She will also serve as a fill-in anchor on the network and host a show on The Choice, the streaming arm of MSNBC on NBCUniversal’s digital service, Peacock.                                                                                                                                     , The hiring of Ms. Sanders is one of the first big programming moves by MSNBC’s president, Rashida Jones, who took charge of the channel in February, after the departure of its longtime head, Phil Griffin. Ms. Jones must reshape the network lineup after the recent exit of the anchor Brian Williams and the decision by Rachel Maddow, the network’s biggest draw, to dial back her on-air presence later this year.                   , Ms. Sanders, who was one of the highest-ranking Black women in the Biden White House, is among the few recognizable personalities in an administration that tends to discourage aides from seeking the spotlight.                                                                                                                                                                                                                            , In her mid-20s, she became national press secretary for Senator Bernie Sanders’s 2016 presidential campaign, then joined CNN as a commentator with a talent for making rapid-fire retorts and getting under the skin of Republicans. When a Republican official told her to “shut up” during a live interview, she parlayed the viral moment into the title of her memoir: “No, You Shut Up: Speaking Truth to Power and Reclaiming America.”, She joined the Biden campaign in 2019 as a senior adviser, acting as a conduit for constituencies including women, Black voters and Democrats previously loyal to Mr. Sanders. Her fierce advocacy for her candidate extended beyond the airwaves: In March 2020, she tackled a protester who rushed the stage during Mr. Biden’s speech on Super Tuesday. At the White House, she played a central role in Ms. Harris’s brain trust.        , In an interview over the weekend, fresh off a morning of shopping for a wedding dress, Ms. Sanders said she planned “to bring my whole self to this show.”                                                                                                                                                                                                                                                                                   , “I’m a young woman, a young Black woman from the Midwest,” said Ms. Sanders, who grew up in Omaha and plans to marry her fiancé in August. “Yes, I do politics, but I’m also a consumer of pop culture. I watch the news, I check Twitter, but I’m also into ‘Real Housewives.’ I’m interested in reaching what I call the nonpolitical group chats, the discussions that are penetrating outside of Washington.”                            , There is a well-worn path between the White House and television news.                                                                                                                                                                                                                                                                                                                                                                       , Numerous alumni of the Trump administration went on to jobs at Fox News; a pair of senior Trump officials, Sean Spicer and Larry Kudlow, host weekday programs on Newsmax and Fox Business. Barack Obama’s chief strategist, David Axelrod, is a staple of CNN; Bill Clinton’s communications aide George Stephanopoulos is a lead anchor at ABC.                                                                                            , As a political spokeswoman, Ms. Sanders has not always seen eye to eye with the news media that she is now joining full time.                                                                                                                                                                                                                                                                                                                , “Oftentimes, when it came to the vice president over the last year, people were not reporting on the truth, they were reporting on the gossip,” she said when asked about the recent spate of tough press coverage for the vice president.                                                                                                                                                                                                   , Speaking last month to The Omaha World-Herald about her departure from Ms. Harris’s staff, Ms. Sanders said she planned “to continue to be a reliable voice for this White House on the outside, regardless of whatever I do next.”                                                                                                                                                                                                          , Asked about those comments, Ms. Sanders offered a more nuanced take. “I’m going to tell the truth, and sometimes the truth is critical,” she said of her new role at MSNBC.                                                                                                                                                                                                                                                                  , She added: “This administration has its critics, just like everyone does — I have my critics — and we’re going to have those conversations.”                                                                                                                                                                                                                                                                                                 , MSNBC’s most popular anchors, including Ms. Maddow, Lawrence O’Donnell and Nicolle Wallace, fall into the category of left-leaning opinion. Ms. Sanders’s program is likely to attract a built-in fan base of viewers eager to hear about current affairs with a pro-Biden bent.                                                                                                                                                             , “Symone’s been on our radar for a while,” Ms. Jones, the MSNBC president, said in a separate interview. “As soon as we had the opportunity, after she left the White House, we shared the thought that this was the best place for her.”                                                                                                                                                                                                     , Ms. Jones said she wanted Ms. Sanders’s “perspective as a woman, as a politico, as a Black woman who’s navigated all these areas from a cultural standpoint — her being herself.” She declined to comment on other future programming moves.                                                                                                                                                                                                 , For Ms. Sanders, who will remain based in Washington, a shot at cable news stardom is a fulfillment of an early dream: As a child, she sometimes acted out imaginary TV broadcasts as an alter-ego host named “Donna Burns.”                                                                                                                                                                                                                 , “I picked up a spoon, a fork, a remote or whatever was there, and I would report on the kitchen,” she recalled. “I think I watched too much evening news as a child.”                                                                                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/solar </td>
   <td style="text-align:left;"> 2022-01-10 22:37:30 </td>
   <td style="text-align:left;"> Solar Energy Index Hits 33-week Low </td>
   <td style="text-align:left;"> Solar Energy Index decreased to a 33-week low of 356.58 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/sports/2022/01/10/novak-djokovic-australian-open-family-press-conference-intl-ldn-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-10 22:33:30 </td>
   <td style="text-align:left;"> Hear from Djokovic's family as tennis star wins appeal - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rwanda/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 22:32:17 </td>
   <td style="text-align:left;"> Rwanda Deflation Slows in December </td>
   <td style="text-align:left;"> Consumer prices in Rwanda fell 2 percent year-on-year in December of 2021, easing from a 3.4 percent decrease in November. It marked the sixth consecutive month of deflation, due to a sharp decline in cost of food &amp; non-alcoholic beverages (-9.5 percent vs -12.3 percent), in particular vegetables (-23.4 percent vs -27.0 percent). Meanwhile, upward pressure came from housing and utilities (3.7 percent vs 2.5 percent), furnishings household equipment and routine household maintenance (9.8 percent vs 8.0 percent), education (12.6 percent, the same as in November), transport (3.6 percent vs 2.9 percent), alcoholic beverages tobacco and narcotics (2.3 percent vs 4.0 percent), restaurants and hotels (2.3 percent vs 4.3 percent), and clothing and footwear (3.8 percent vs 3.9 percent). On a monthly basis, consumer prices edged up 0.1 percent, compared to a 0.9 percent decline in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 22:32:00 </td>
   <td style="text-align:left;"> US Stocks Sink, Inflation Eyed </td>
   <td style="text-align:left;"> US stocks started the week on a negative note, with the Dow Jones falling more than 400 points, a 4th straight session of losses while the S&amp;P 500 declined 1.5% and the Nasdaq dropped more than 2%, a 5-day losing streak for both indexes. Treasury yields continue to jump to levels not seen in 2 years amid prospects of higher interest rates and the odds are rising the Fed will raise the fed funds rate four times this year instead of 3 the central bank signalled early. Traders also await the inflation report, the confirmation hearing for Fed Chair Powell and speeches from several other policymakers for more clues on the Fed's timing for a fed funds hike. On the corporate front, the earnings season kicks-off this week with Wells Fargo, Citigroup, JPMorgan reporting Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/industrial-production </td>
   <td style="text-align:left;"> 2022-01-10 22:30:32 </td>
   <td style="text-align:left;"> Ireland Industrial Output Shrinks at Record Pace </td>
   <td style="text-align:left;"> Industrial production in Ireland declined 29.2 percent year-on-year in November of 2021, the highest decline on record, following a downwardly revised 10.9 percent decline in the previous month. Output plunged for manufacturing industries (30.7 percent vs 10 percent in October), transportable goods industries (-30.2 percent vs -11.8 percent), and utilities (-12.5 percent vs 18.5 percent). On a monthly basis, industrial output rose by 37.4 percent, the steepest monthly rise since March of 2020, following a 32.1 percent decline in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ndx:ind </td>
   <td style="text-align:left;"> 2022-01-10 22:30:02 </td>
   <td style="text-align:left;"> NASDAQ 100 Hits 11-week Low </td>
   <td style="text-align:left;"> USNDX decreased to a 11-week low of 15373 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/take-two-interactive-zynga-merger </td>
   <td style="text-align:left;"> 2022-01-10 22:24:22 </td>
   <td style="text-align:left;"> Take-Two Interactive to buy Zynga in $12.7B deal </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                           , Take-Two Interactive, the video game giant known for Grand Theft Auto and Red Dead Redemption, has announced it will buy Zynga, the mobile gaming company behind titles including FarmVille and Words with Friends, in a cash and stock transaction valued at approximately $12.7 billion, or $9.86 per Zynga share.                                                        , RICHARD BRANSON'S VIRGIN ORBIT ADDS TO SPACE INVESTING LIFTOFF                                                                                                                                                                                                                                                                                                              , Under the terms of the agreement, Zynga stockholders will receive $3.50 in cash and $6.36 in shares of Take-Two common stock for each share of Zynga common stock outstanding at the closing of the transaction. The purchase price represents a premium of 64% to Zynga’s closing share price on Jan. 7, 2022.                                                             , Upon closing of the transaction, current Take-Two stockholders will own between 67.2% and 70.4% of the combined company on a fully diluted basis, while current Zynga stockholders are expected to own between 29.6% and 32.8%.                                                                                                                                             , The transaction is expected to close during Take-Two’s first quarter of fiscal year 2023, subject to approval by Take-Two and Zynga stockholders and regulators. The merger agreement includes a go-shop provision, which gives Zynga 45 days to "actively solicit, receive, evaluate, and potentially enter negotiations with parties that offer alternative proposals."   , Shares of Zynga have surged 47% during Monday's trading session, while Take Two Interactive shares have slipped more than 12% following the announcement.                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                 , "This strategic combination brings together our best-in-class console and PC franchises, with a market-leading, diversified mobile publishing platform that has a rich history of innovation and creativity," Take-Two Interactive chairman and CEO Strauss Zelnick said in a prepared statement.                                                                           , Zelnick will continue to retain his roles in the combined company, which will be led by Take-Two management. Meanwhile, Zynga CEO Frank Gibeau and president of publishing Bernard Kim will oversee the integration and day-to-day operations of the combined Zynga and T2 Mobile Games business, which will operate under the Zynga brand as its own label within Take-Two., In addition, Take-Two will expand its board of directors to 10 members upon the closing of the transaction to add two members from Zynga’s board of directors.                                                                                                                                                                                                              , A pedestrian walks in front of a sign at Zynga in San Francisco, Tuesday, March 16, 2021. (AP Photo/Jeff Chiu, File)                                                                                                                                                                                                                                                        , Zelnick expects the deal to deliver $100 million in annual cost synergies within the first two years post-closing and at least $500 million of annual net booking opportunities over time.                                                                                                                                                                                  , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                     , Mobile gaming is the fastest growing segment in the video game sector, with an estimated $136 billion in gross bookings in 2021 and a compound annual growth rate of 8% expected over the next three years.                                                                                                                                                                 , Take-Two, which reported $6.1 billion in net bookings in the 12 months ending Sept. 30, 2021, expects mobile gaming to account for over half of its net bookings in fiscal year 2023, up from 12% in fiscal 2022.                                                                                                                                                           , The combined company is expected to deliver a 14% compound annual growth rate for net bookings from fiscal years 2021 through 2024.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/americans-inflation-fears-december-new-york-fed-survey </td>
   <td style="text-align:left;"> 2022-01-10 22:17:25 </td>
   <td style="text-align:left;"> Americans' inflation fears stay at record high, New York Fed survey shows </td>
   <td style="text-align:left;"> Former Kansas City Federal Reserve President and CEO Thomas Hoenig discusses U.S. monetary policy amid high inflation.                                                                                                                                                                                                                                                                                                                                      , Americans' inflation fears held steady for the first time in months in December, although concerns over rising prices remained at a record high, according to a key Federal Reserve Bank of New York survey published Monday.                                                                                                                                                                                                                               , The median expectation is that the inflation rate will be up 6% one year from now, the highest level for the gauge since its launch in June 2013, according to the New York Federal Reserve's Survey of Consumer Expectations. Inflation expectations over the next three years also remained unchanged at 4%.                                                                                                                                              , "Median inflation uncertainty—or the uncertainty expressed regarding future inflation outcomes—decreased at the short- and medium-term horizons, retreating from their series highs recorded in November," the report said.                                                                                                                                                                                                                                 , US INFLATIONS HITS 39-YEAR HIGH AS CONSUMER PRICES JUMP                                                                                                                                                                                                                                                                                                                                                                                                     , Although consumers are braced for the highest inflation levels in nearly a decade, they expect things like gasoline, food and college tuition to get cheaper over the next year. Their expectations for the price of medical care and rent remained unchanged.                                                                                                                                                                                              , The report is based on a rotating panel of 1,300 households.                                                                                                                                                                                                                                                                                                                                                                                                , Billboard on the cruelties of inflation in Coon Rapids, Minnesota. (Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                 , The survey plays a critical role in determining how Fed policymakers respond to the recent inflation spike. That's because actual inflation depends – at least in part – on what consumers think it will be. It's a sort of self-fulfilling prophecy – if everyone expects prices to rise by 3% in the year, that signals to businesses that they can increase prices by at least 3%. Workers, in turn, will want a 3% pay raise to offset the rising costs., This is about well-anchored inflation expectations," Fed Vice Chairman Richard Clarida said during a question-and-answer session at the Cleveland Fed two weeks ago. "Getting actual inflation down close to 2% is going to be an important part of keeping those expectations anchored."                                                                                                                                                                   , Fed Chairman Jerome Powell has already signaled the U.S. central bank plans to speed up its withdrawal of support for the U.S. economy in order to combat inflation, which has been higher and longer-lasting than policymakers initially expected. Minutes released last week from the Fed's December meeting showed that officials discussed the possibility of a faster interest rate hike as the inflation burst forces them to readjust policy.        , Traffic passes a downtown Los Angeles gas station where a gallon of gas costs over six dollars on December 10, 2021.  (Photo by FREDERIC J. BROWN/AFP via Getty Images) / Getty Images)                                                                                                                                                                                                                                                                     , "It may become warranted to increase the federal funds rate sooner or at a faster pace than participants had earlier anticipated," the minutes said. Central bankers projected during the meeting that they would raise rates as many as three times in 2022. Economists think those increases could begin as soon as March, once the Fed concludes its massive bond-buying program.                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                 , A Labor Department report last month revealed that the price of consumer goods rose by 6.8% in November from last year, the fastest pace since June 1982 – all but solidifying the Fed's plans to accelerate its tapering timeline.                                                                                                                                                                                                                         , "[The] consumer price data, with annual inflation reaching a near 40-year high of 6.8%, greatly increase the pressure on the Federal Reserve to wind down its asset purchase program even more quickly than previously communicated and bring interest rate hikes forward to the first half of 2022," said Matthew Sherwood, global economist at the Economist Intelligence Unit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lithium </td>
   <td style="text-align:left;"> 2022-01-10 22:00:39 </td>
   <td style="text-align:left;"> Lithium Carbonate Extends Rally </td>
   <td style="text-align:left;"> Lithium carbonate prices in China rose to 298,500 yuan/tonne in the second week of January, amid rising global demand and tightening supplies. Upward pressure can be attributed to continuously increasing demand from lithium battery manufacturers, amid projections of higher electric vehicle sales. According to Benchmark Mineral Intelligence, battery manufacturer’s lithium carbonate stocks are at low to non-existent levels due to high demand for EV battery production. Global electric vehicle sales are estimated to have increased by 160% during 2021, while deliveries in China are expected to double in 2022 to over 5 million sales. Meanwhile, miners in China cannot keep up with increased orders. According to Chinese lithium traders, producers are having difficulty in fulfilling their long-term contracts, as the current mining pace cannot match demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/jon-ossoff-bill-ban-congress-stock-trades-rebuff-pelosi </td>
   <td style="text-align:left;"> 2022-01-10 21:52:22 </td>
   <td style="text-align:left;"> Jon Ossoff exploring bill to ban Congress stock trades, rebuffing Pelosi </td>
   <td style="text-align:left;"> Former Forbes Chairman and editor-in-chief Steve Forbes on the market selloff, inflation, the Federal Reserve and Manhattan DA Alvin Bragg defending a soft-on-crime approach.                                                                                                                                       , Sen. Jon Ossoff is planning to introduce legislation that would prohibit members of Congress from holding or trading individual stocks while in elective office, a source familiar with the matter told FOX Business.                                                                                                , The ethics bill, which the freshman Georgia Democrat hopes to file as soon as he secures a Republican cosponsor, would also target conflicts of interest by making it illegal for lawmakers' spouses and family members to trade stocks while in office, the source said. The New York Post first reported the news. , US INFLATIONS HITS 39-YEAR HIGH AS CONSUMER PRICES JUMP                                                                                                                                                                                                                                                              , It may also require lawmakers to put their financial assets in a blind trust – something that Ossoff did himself a few months after he was elected in January 2021. Ossoff's blind trust contributed to a net worth somewhere between $2 million and $7.3 million as of late 2020.                                   , The proposed bill could serve as a major rebuff of House Speaker Nancy Pelosi, D-Calif., who just a few weeks ago vehemently defended the practice, even though it has drawn scrutiny because it could give lawmakers the chance to profit off inside information gleaned through their official duties.             , Sen. Jon Ossoff questions Treasury Secretary Janet Yellen and Federal Reserve Chairman Jerome Powell during a Senate hearing on Sept. 28, 2021, in Washington. (Kevin Dietsch/Getty Images / Getty Images)                                                                                                           , "We are a free market economy. They should be able to participate in that," Pelosi told reporters on Dec. 15. Pelosi does not own any stock herself, but her husband holds tens of millions of dollars worth of stocks and options in companies like Apple, Disney, Amazon and Google.                               , The California Democrat has previously said she has no prior knowledge or involvement in her husband's trading decisions.                                                                                                                                                                                            , Lawmakers' spouses are allowed to trade in companies or industries that their partner may help regulate. But under the STOCK Act, passed in 2012, it's illegal for members of Congress and their families to profit from inside information and requires lawmakers to report stock trades to Congress within 45 days., In some recent cases, lawmakers have failed to report their trades altogether.                                                                                                                                                                                                                                       , "We have a responsibility to report," Pelosi said. "If people aren’t reporting they should be."                                                                                                                                                                                                                      , House Speaker Nancy Pelosi meets with reporters to discuss President Joe Biden's domestic agenda at the Capitol on Sept. 8, 2021. (AP Photo/J. Scott Applewhite / AP Newsroom)                                                                                                                                       , Pelosi is worth an estimated $114 million, according to her 2018 personal financial disclosure, making her the sixth-richest member of the House and the 10th richest member of Congress, according to data tracked by the Center for Responsive Politics.                                                           , Other Democrats, such as progressive Rep. Alexandria Ocasio-Cortez, D-N.Y., and Sen. Elizabeth Warren, D-Mass., have voiced support for banning trading among members of Congress.                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                          , It's unclear, however, whether Ossoff will be able to find a Republican to back the bill. No Senate Republicans have publicly voiced opposition against trading among members, so far, although House Republicans, including Reps. Chip Roy and Michael Cloud of Texas, have endorsed the idea.                      , The person familiar with the matter said Ossoff is hoping to find Republican support in the Senate.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-10 21:37:11 </td>
   <td style="text-align:left;"> Baltic Dry Index Extends Drop to 2-Week Low </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index declined 0.5% to 2,277 on Monday, its lowest since December 24th and following a 0.3% decrease in the previous session. The panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, fell 3.7% to 2,849 and the supramax index went down 73 points to 2,001, its lowest since April 2021. On the other hand, the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, rose 5% to 2,554. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/armenia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 21:29:40 </td>
   <td style="text-align:left;"> Armenia Inflation Rate at 6-Month Low </td>
   <td style="text-align:left;"> Armenia’s annual inflation rate slowed to 7.7 percent year-on-year in December of 2021, from a near eleven-year high of 9.6 percent in the previous month. It was the smallest price increase since June of 2021, as momentum eased significantly in prices of food &amp; non-alcoholic beverages (12.9 percent vs 16.9 percent in November); transport (5.7 percent vs 8.5 percent); furnishings, household equipment &amp; routine maintenance (7.5 percent vs 8.7 percent). Conversely, prices rose faster for clothing &amp; footwear (12.3 percent vs 12.1 percent); housing &amp; utilities (1.9 percent vs 1.6 percent); recreation &amp; culture (11.9 percent vs 11.5 percent); and restaurants &amp; hotels (5.5 percent vs 4.7 percent). On a monthly basis, consumer prices went up 1.6 percent, after a 1.7 percent gain in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/private-investment </td>
   <td style="text-align:left;"> 2022-01-10 21:12:00 </td>
   <td style="text-align:left;"> Mexico Private Investment Rises at a Slower Pace </td>
   <td style="text-align:left;"> Gross fixed investment in Mexico advanced by 6.5 percent year-on-year in October of 2021, following a 9.9 percent jump in the previous month. It was the fifth consecutive month of slowing growth in private investment, largely due to low base effects from the previous year. Mexico recorded smaller rates of growth for investment in construction (3.5 percent vs 9.3 percent in September) and machinery and equipment (10.3 percent vs 10.7 percent). On a seasonally adjusted monthly basis, private investment remained unchanged, compared to a 1.6 percent drop in September. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 21:00:00 </td>
   <td style="text-align:left;"> Italian Stocks Erase Gains </td>
   <td style="text-align:left;"> The FTSE MIB Index erased early gains to drop 0.3% and hover around the 27,520 level on Monday, dragged by the tech and healthcare sectors, as investors await US consumer price data on Wednesday for further indication of monetary policy by the Federal Reserve, while weighing on European labor market data. Healthcare stocks dropped 1.4%, led by Amplifon (-3.6%), while tech shares fell 1%, led by STMicroelectronics (-2.9%). On the data front, the US CPI from December is expected to rise to a four-decade high of 7% on the year, strengthening expactations for rate hikes in March. Meanwhile, the Italian unemployment rate for November was at 9.2%, below market expectations, while the euro area unemployment edged down to 7.2 percent, a new pandemic low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-10 20:59:24 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield at 10-Month High </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB soared past 0.12% in the beginning of January, the highest since March of 2021, in line with the US Treasury note yield, as traders bet on sooner-than-expected rate hikes by the US Fed. The yield surged over 215% since December 20th, as concerns about the Omicron variant derailing the economic recovery faded, while improvements in the domestic economic outlook, rising inflation rates worldwide, and the beginning of unwinding of the pandemic-era stimulus by major central banks added to the upside momentum. On Monday, Japanese equity and bond markets were closed for the Coming of Age Day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/stocks-making-the-biggest-moves-in-the-premarket-zynga-lululemon-apria-and-more.html </td>
   <td style="text-align:left;"> 2022-01-10 20:46:03 </td>
   <td style="text-align:left;"> Stocks making the biggest moves in the premarket: Zynga, Lululemon, Apria and more </td>
   <td style="text-align:left;"> , Take a look at some of the biggest movers in the premarket:                                                                                                                                                                                                                                                                                                                                , Zynga (ZYNG) – The online game maker's shares soared 48.2% in the premarket after it agreed to be acquired by video game maker Take-Two Interactive (TTWO) for $9.86 per share in cash and stock, implying a total deal value of $12.7 billion. Take-Two tumbled 8.9%.                                                                                                                     , Lululemon (LULU) – The athletic apparel maker said it now expects fourth-quarter earnings and revenue to come in at the low end of its projected ranges, saying it had experienced a number of negative consequences from the spread of the Covid-19 omicron variant. Lululemon slid 6.5% in premarket action.                                                                             , Apria (APR) – The home health care services provider agreed to be acquired by health-care equipment and services company Owens &amp; Minor (OMI) for about $1.45 billion in cash, or $37.50 per share. Apria had closed Friday at $29.72 per share, and its stock surged 24.5% in premarket trading. Owens &amp; Minor shares slumped 9.1%.                                                        , Tilray (TLRY) – Tilray gained 3.6% in premarket trading after reporting an unexpected quarterly profit. Revenue increased by 20% from a year earlier on stronger demand for cannabis products, although its sales were below analysts' forecasts.                                                                                                                                          , Beam Therapeutics (BEAM) – Beam shares jumped 5.3% in the premarket following the announcement of a new partnership with Pfizer (PFE). Pfizer will collaborate with Beam – which specializes in gene editing – to develop therapies for rare genetic diseases.                                                                                                                             , ViacomCBS (VIAC) – ViacomCBS rallied 3.2% in the premarket after Deutsche Bank upgraded the media company's stock to "buy" from "hold," based on upbeat prospects for its streaming business and the likelihood of continuing industry consolidation.                                                                                                                                      , Sinclair Broadcast Group (SBGI) – Sinclair is close to finalizing a deal to carry NBA games on its planned new streaming app, according to a Bloomberg report quoting people familiar with the matter. The deal could be announced as soon as this week. Sinclair gained 1.4% in premarket action.                                                                                         , SolarEdge Technologies (SEDG) – SolarEdge was added to the "Conviction Buy" list at Goldman Sachs, which raised the price target for the solar equipment company's stock to $448 per share from $420 a share. Goldman cites improvements in battery storage capacity as well as the company's prospects for increasing profit margins. SolarEdge rose 2.4% in the premarket.               , Shockwave Medical (SWAV) – Penumbra (PEN) is exploring a combination with its rival medical device maker, according to people with knowledge of the matter who spoke to Bloomberg. However, Penumbra told Bloomberg in an emailed statement that it is not in discussions with Shockwave to pursue a business combination or similar transaction. Shockwave jumped 6% in premarket trading., Dell Technologies (DELL) – Bernstein upgraded Dell to "outperform" from "market perform," noting Dell's approximately six-week backlog in its PC business as well as a relatively high mix of commercial versus consumer business. Dell added 2.4% in the premarket.                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/01/10/business/stock-market-economy-news </td>
   <td style="text-align:left;"> 2022-01-10 20:41:42 </td>
   <td style="text-align:left;"> Stock Market and Business News: Live Updates - The New York Times </td>
   <td style="text-align:left;"> Richard Clarida, the vice chair of the Federal Reserve, will leave on Friday, two weeks ahead of schedule. Updated disclosures showed rapid moves out of and back into stocks as the central bank prepared to reassure markets.                                                                                                                                                                                                                                                                                                                                                                                                                            , S&amp;P 500                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Dow                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Nasdaq                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , %                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , As of                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Richard H. Clarida, the Federal Reserve’s vice chair, announced on Monday that he would resign from his position two weeks earlier than planned. While he did not give a reason, he had faced renewed scrutiny about trades he made in 2020 as the central bank was poised to rescue financial markets.                                                                                                                                                                                                                                                                                                                                                    , “With my statutory term as governor due to expire on Jan. 31, 2022, I am writing to inform you that it is my intention to resign from the board on Jan. 14, 2022,” Mr. Clarida wrote in a letter to President Biden that the Fed released Monday.                                                                                                                                                                                                                                                                                                                                                                                                          , The New York Times reported last week that Mr. Clarida had corrected his 2020 financial disclosures in late December. Ethics experts said one of his updated trades raised questions — he sold a stock fund on Feb. 24 before repurchasing it on Feb. 27, just before the chair of the Fed announced on Feb. 28 that the central bank stood ready to help markets and the economy.                                                                                                                                                                                                                                                                         , His initial disclosures had noted only the purchase of the stock fund, which the Fed had described on his behalf as a planned portfolio rebalancing. But the rapid move out of and back into stocks called that explanation into question, some experts said, and the repurchase could have put Mr. Clarida in a position to benefit as the Fed reassured markets.                                                                                                                                                                                                                                                                                         , Neither the Fed nor Mr. Clarida provided an new explanation for the trades, though the Fed’s ethics office noted in the updated filing that they still appeared to be in compliance with conflict-of-interest laws.                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mr. Clarida’s updated disclosure drew widespread media coverage and lawmaker attention. Senator Elizabeth Warren, Democrat of Massachusetts, called on the Fed on Monday to release more information about trades by top Fed officials in light of the news.                                                                                                                                                                                                                                                                                                                                                                                               , The amended disclosure and volley of attention came at an inopportune moment for Jerome H. Powell, the Fed chair, who has been renominated to his position by Mr. Biden. He is scheduled to appear on Tuesday at a confirmation hearing before the Senate Banking Committee.                                                                                                                                                                                                                                                                                                                                                                               , Ms. Warren sits on the Banking Committee, so Mr. Powell is still almost sure to face questions about why some Fed officials traded so actively as markets gyrated and the Fed staged a huge rescue at the start of the pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                           , “The whole rebalancing story, that just collapses in the face of the fact that he sold and then bought,” said Simon Johnson, an economist at the Massachusetts Institute of Technology. “If you are Chair Powell, you don’t want to have your reconfirmation hearing focused on this.”                                                                                                                                                                                                                                                                                                                                                                     , Mr. Powell and his colleagues have in recent months revamped the central bank’s ethics guidelines — in October releasing plans to overhaul them and prevent many types of financial activity, including trading during times of turmoil. He may point to that as a sign of how seriously the Fed has taken the issue.                                                                                                                                                                                                                                                                                                                                      , Mr. Clarida’s resignation is the latest development in a monthslong trading scandal that has embroiled top officials and prompted high-profile departures at the Fed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Financial disclosures released in late 2021 showed that Robert S. Kaplan, the former president of the Federal Reserve Bank of Dallas, had made big individual-stock trades, while Eric S. Rosengren, the former Boston Fed president, had traded in real estate securities. Those moves drew immediate and intense backlash from lawmakers, ethics experts and former Fed employees.                                                                                                                                                                                                                                                                       , Fed officials were actively rescuing a broad swath of markets in 2020. In March and April, they slashed rates to zero, bought mortgage-tied and government bonds in mass quantities, and rolled out rescue programs for corporate and municipal debt.                                                                                                                                                                                                                                                                                                                                                                                                      , The concern is that continuing to deal in affected securities for their own portfolios throughout the year could have given officials room to profit from their privileged knowledge.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Mr. Kaplan resigned in September, citing the scandal; Mr. Rosengren resigned simultaneously, citing health issues.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Mr. Clarida’s term was scheduled to end at the close of this month because his seat as governor was expiring. Bloomberg News first reported on his stock fund purchase — what was visible before he corrected the disclosure — in October.                                                                                                                                                                                                                                                                                                                                                                                                                 , While Mr. Clarida didn’t address the trading issues in his resignation letter, he did mention them indirectly during a speech late last year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , “I’ve always acquitted myself honorably and with integrity with respect to the obligations of public service,” he said in mid-October.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The Fed’s government watchdog is investigating the trades officials made in 2020, and Ms. Warren has called for an investigation by the Securities and Exchange Commission. The S.E.C. does not comment on whether such investigations are underway.                                                                                                                                                                                                                                                                                                                                                                                                       , Mr. Clarida has been vice chair since 2018, and during that time has been a close collaborator of Mr. Powell’s and a valuable second-in-command. His speeches were closely watched by Wall Street for the policy signals they often offered, and he was lauded for his skills as a clear and careful communicator.                                                                                                                                                                                                                                                                                                                                         , He also led a push to revamp the Fed’s policy-setting framework to make it more focused on employment and more fitted to the challenges of the modern economic era, one of the major hallmarks of Mr. Powell’s first term.                                                                                                                                                                                                                                                                                                                                                                                                                                 , “I will miss his wise counsel and vital insights,” Mr. Powell said in a statement announcing Mr. Clarida’s early departure.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Jerome H. Powell, the Federal Reserve chair whom President Biden has nominated for a second four-year term, is set to tell senators on Tuesday that central bankers will use their economic tools to keep inflation — which has been high — from becoming entrenched.                                                                                                                                                                                                                                                                                                                                                                                      , Mr. Powell, who is scheduled to testify before the Senate Banking Committee as he seeks confirmation, faces reappointment at an anxious economic moment. Inflation is running at the fastest pace in nearly 40 years. While economists have hoped for months that it would soon fade, that has yet to happen. Higher prices are chipping away at household incomes, even as wages rise and as companies hire at a solid clip.                                                                                                                                                                                                                              , “We know that high inflation exacts a toll, particularly for those less able to meet the higher costs of essentials like food, housing and transportation,” Mr. Powell will tell lawmakers, according to his prepared remarks. “We are strongly committed to achieving our statutory goals of maximum employment and price stability.”                                                                                                                                                                                                                                                                                                                     , Mr. Powell and his colleagues in recent months have reoriented their policies to pull back on support for the economy in light of the inflationary burst. They are slowing a large bond-buying program they had been using to keep longer-term borrowing cheap and to stoke the economy, and they could raise interest rates as soon as March.                                                                                                                                                                                                                                                                                                             , “Monetary policy must take a broad and forward-looking view, keeping pace with an ever-evolving economy,” Mr. Powell will tell senators.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Economists increasingly expect Fed officials to make three or even four increases this year and eventually to shrink the size of their bond holdings, policies that together will make borrowing more expensive for households and businesses, take juice out of the stock market and slow overall growth.                                                                                                                                                                                                                                                                                                                                                 , The pivot — which squarely puts the Fed in inflation-fighting mode — could assuage some lawmakers who are worried that the central bank is going to allow inflation to jump out of control. Even so, some may worry what has taken monetary policymakers so long.                                                                                                                                                                                                                                                                                                                                                                                          , Others may ask whether the central bank risks overdoing it. Removing support for the economy could slow the job market and curtail hiring while virus concerns and child care issues are keeping many former workers on the labor market’s sidelines.                                                                                                                                                                                                                                                                                                                                                                                                      , Mr. Powell most likely will also need to address a trading scandal that has rocked the Fed in recent months. Several prominent central bankers traded financial assets for their own portfolios in early 2020, when the Fed was very active in rescuing markets.                                                                                                                                                                                                                                                                                                                                                                                           , One, Richard H. Clarida, the vice chair, recently corrected his financial disclosures in a way that made his hot-button transaction — a move into stocks that took place on the eve of a big Fed announcement — look less like the rebalancing that the Fed originally said it had been and more like a response to market conditions.                                                                                                                                                                                                                                                                                                                     , Mr. Clarida announced on Monday that he would resign earlier than planned from the Fed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Mr. Powell did not address that development directly in the prepared remarks, but he pledged to be fair and independent in policy choices.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “I am committed to making those decisions with objectivity, integrity and impartiality, based on the best available evidence and in the longstanding tradition of monetary policy independence,” he will say.                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Noam Scheiber                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The National Labor Relations Board announced Monday that it had certified a victory for a union at a second Starbucks store in the Buffalo area, where votes were tallied in December but remained inconclusive as the union challenged the ballots of several employees it said did not work at the store.                                                                                                                                                                                                                                                                                                                                                , The labor board declared the union the winner at another Buffalo-area store when it counted the votes on Dec. 9, and the union lost an election at a third store.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The board agreed with the union that the challenged ballots should not count, giving the union a 15-to-9 win. None of the other roughly 9,000 company-operated Starbucks locations in the United States have a union.                                                                                                                                                                                                                                                                                                                                                                                                                                      , Labor experts have said that establishing a second unionized store in the same market could provide a significant boost to the union, Starbucks Workers United. The union is part of Workers United, an affiliate of the giant Service Employees International Union.                                                                                                                                                                                                                                                                                                                                                                                      , Under U.S. labor law, employers are obligated to bargain in good faith with a union that has won an N.L.R.B. election, but they are not required to reach agreement on a contract. As a result, winning a contract often requires unions to apply economic pressure such as a work stoppage, something that a second store could make more potent.                                                                                                                                                                                                                                                                                                         , Last week, several employees of the first unionized store near Buffalo walked off the job amid concerns about rising Covid-19 infection rates. The workers said they returned on Monday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The newly unionized store, near the Buffalo airport, filed for a union election in late August, along with the two other stores that voted in December. The union has formally objected to the outcome of the election that it lost, and that objection is pending before the labor board.                                                                                                                                                                                                                                                                                                                                                                 , Starbucks has 10 business days to request an appeal of the decision announced on Monday. If the request was filed and denied, the result would become final. A company spokesman said that Starbucks was evaluating whether or not to appeal and that it believed its employees’ voices should be heard.                                                                                                                                                                                                                                                                                                                                                   , Throughout the union campaign last year, Starbucks dispatched out-of-town managers and a top executive to Buffalo in what it said was an attempt to fix operational issues like understaffing and the poor layout of certain stores. The officials often questioned employees about their workplaces and helped with menial tasks like throwing out garbage.                                                                                                                                                                                                                                                                                               , Several union supporters said they were intimidated by the presence of the officials and were disoriented by other disruptions to their work lives, such as the company’s decision to temporarily close certain stores and send employees to other locations.                                                                                                                                                                                                                                                                                                                                                                                              , Since the initial victory in Buffalo, workers at several other Starbucks stores throughout the country have filed for union elections, including in Boston, Chicago, Seattle and Knoxville, Tenn.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , “Today we put an end to Starbucks’s delay attempts and formed our union,” Alexis Rizzo, a shift supervisor at the second unionized location, said in a statement, adding: “We demand that Starbucks stop their union busting in Buffalo and across the nation immediately. No other partners should have to endure what we went through to have a voice on the job.”                                                                                                                                                                                                                                                                                       , Starbucks has denied that it has sought to intimidate employees, but it has said it prefers that its employees not unionize.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Last week, the federal labor board scheduled an election for a Starbucks store in Mesa, Ariz., where workers had filed paperwork in November. Ballots in the election will be mailed out on Friday and will be due back by Jan. 28. Workers at more than 10 other locations, including three in the Buffalo area, are still awaiting decisions from the board on if and when it will set election dates.                                                                                                                                                                                                                                                   , By Stephen Gandel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , By: Ella Koeze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Wild volatility in the Nasdaq composite index on Monday pointed to the new reality for technology stocks: After being largely immune to bad economic news during most of the pandemic, that resilience may be waning.                                                                                                                                                                                                                                                                                                                                                                                                                                      , The Nasdaq composite fell as much as 2.7 percent Monday, a slide that had it approaching a correction, a key technical and psychological measure on Wall Street that is defined as a drop of more than 10 percent from a high. By the end of the day, however, tech stocks had rebounded and the index ended the day with a small gain. The S&amp;P 500, a broader index and the U.S. benchmark, ended with a small loss.                                                                                                                                                                                                                                      , But market watchers said Monday’s volatility in tech stocks could soon become a problem for investors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , “People have a mind-set that equity prices always go up,” said Vincent Reinhart, the chief economist of Dreyfus and Mellon. “There is nothing magical about drawing the line at 10 percent other than it makes people realize that stocks don’t always go up.”                                                                                                                                                                                                                                                                                                                                                                                             , Even with Monday’s rebound, many tech company shares, including ones that appeared to be early pandemic winners, remained far from the highs they held just a few months ago. Shares of Zoom Video Communications, the virtual-meeting software company, are now down nearly 70 percent from their high of $560 in late 2020.                                                                                                                                                                                                                                                                                                                              , Companies that consumers turned to for escape during lockdowns have also fallen. Netflix’s stock price has fallen 24 percent from its high, and Teslahas seen its stock drop nearly 20 percent from its November high.                                                                                                                                                                                                                                                                                                                                                                                                                                     , A large part of this drop, and the recent reversal of the market in general, appears to be tied to the expectation that the Federal Reserve will raise interest rates sooner than previously expected. Last week, the central bank released minutes from its December meeting that showed Fed officials are preparing to raise interest rates to tamp down inflation; many economists expect that to happen as soon as March.                                                                                                                                                                                                                              , And although December’s overall jobs report was weaker than expected, it still showed a significant jump in wages for the past year, which also raised inflation concerns and could prompt the Fed to move quicker.                                                                                                                                                                                                                                                                                                                                                                                                                                        , Rising interest rates discourage risk-taking by investors, which tends to hit tech stocks more than others. What’s more, shares of many technology companies trade at high valuations because of fast growth and expectations that they will produce significant profits in the future. But higher interest rates put future growth in doubt and make those future earnings worth less to current investors.                                                                                                                                                                                                                                               , Other areas of Wall Street have also shown volatility. On Monday, the yield on the 10-year Treasury note rose to about 1.8 percent, the highest since the beginning of the pandemic, before falling slightly by the end of the day.                                                                                                                                                                                                                                                                                                                                                                                                                        , “There is a white knuckle fear on the Street around tech stocks,” said Dan Ives, the managing director of equity research at Wedbush Securities. “Tech stocks have been on a bull run, and now Fed worries and the spiking 10-year yield are crashing the tech party, with investors hitting the sell button and heading for the elevators in unison.”                                                                                                                                                                                                                                                                                                     , Mr. Ives said that he thought the sell-off was just a pause and not the end of a rise in tech stocks, but he added that investors should expected more volatility.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The adjustment to higher interest rates isn’t bad news for all stocks. Shares of banks have been climbing as investors anticipate their profits will grow.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Overall, the profit picture for corporate America remains quite strong. Earnings at companies in the S&amp;P 500 are estimated to have risen nearly 22 percent in the final three months of 2021 compared with a year prior.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Analysts, though, expect that earnings growth to drop to 9 percent this year, as the boost from government stimulus checks and a surge in consumer spending as pandemic restrictions end are likely to all but disappear.                                                                                                                                                                                                                                                                                                                                                                                                                                  , By Alan Rappeport                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , WASHINGTON — The federal tax filing season will run from Jan. 24 to April 18 this year, the Internal Revenue Service said on Monday, warning in its announcement that staffing shortages and paperwork backlogs could make for a messy and frustrating experience for taxpayers.                                                                                                                                                                                                                                                                                                                                                                           , In a briefing on Monday, Treasury Department officials said that the I.R.S. would struggle to promptly answer telephone calls from taxpayers with questions and that a lower level of service should be expected. They blamed Republican legislators, who have blocked efforts to increase funding at the agency, for the lack of resources.                                                                                                                                                                                                                                                                                                               , The Biden administration has asked for an additional $80 billion over a decade for the I.R.S. to bolster its enforcement and its customer service capacity, raising its staff by nearly 87,000 employees and upgrading its technology. That request is part of the administration’s Build Back Better Act, which is stalled in Congress. The Treasury Department estimates that enhancing the enforcement powers of the I.R.S. could yield the federal government $400 billion in additional tax revenue over a decade by shrinking the so-called tax gap, or tax money that is owed the government but goes uncollected.                                  , Treasury officials noted that in the first half of last year, fewer than 15,000 employees were available to handle more than 240 million calls — one person for every 16,000 calls.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Although the population of the United States has grown by about 60 percent since 1970 and the tax code has become more complex, the size of the work force at the I.R.S. has been flat, the Treasury Department said. The agency has fewer auditors now than it has employed at any time since World War II.                                                                                                                                                                                                                                                                                                                                               , “In many areas, we are unable to deliver the amount of service and enforcement that our taxpayers and tax system deserves and needs,” Charles P. Rettig, the I.R.S. commissioner, said in a statement. “This is frustrating for taxpayers, for I.R.S. employees and for me.”                                                                                                                                                                                                                                                                                                                                                                               , He added: “Additional resources are essential to helping our employees do more in 2022 — and beyond.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Republicans seized on the Biden administration’s plans to beef up the I.R.S. last year, issuing dire warnings that the agency would be deployed to spy on Americans and target conservatives. Their attacks succeeded in killing a proposal that would have required banks to submit additional taxpayer data to the I.R.S.                                                                                                                                                                                                                                                                                                                                , The tax season this year will be more complicated than usual because pandemic-related economic impact payments and child tax credit payments were distributed last year. Taxpayers will be required to report the amount of money that they received.                                                                                                                                                                                                                                                                                                                                                                                                      , The I.R.S. is urging taxpayers to file their returns electronically, and said people should generally receive refunds within 21 days of filing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Usually Tax Day falls on April 15, but it will be delayed for most tax payers to April 18 because of the Emancipation Day holiday in Washington. Filing deadlines for state taxes may differ.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Katie Robertson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Goli Sheikholeslami, the head of New York Public Radio, will become Politico’s new chief executive, Axel Springer announced on Monday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Her appointment is the first big move by Axel Springer, the German publishing giant, since it bought Politico Media Group last year for more than $1 billion. As part of its ambition to become a force in the American news media, the company acquired Business Insider in 2015 and a controlling stake in the newsletter Morning Brew in 2020.                                                                                                                                                                                                                                                                                                          , Jan Bayer, Axel Springer’s president of news media, said that Ms. Sheikholeslami would “further our vision to build the global news and information leader on politics, policy and regulation in power centers across the world.”                                                                                                                                                                                                                                                                                                                                                                                                                          , Politico Media Group includes Politico, which has a newsroom of nearly 400 journalists, and its tech news counterpart, Protocol.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , “What I admire most about Politico is the tenacity that underpins the organization’s fearless, fact-based journalism and its successful business model,” Ms. Sheikholeslami said in a statement.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Ms. Sheikholeslami will start in her new role next month. She succeeds Patrick Steel, who stepped down as chief executive last year. She is making the move after two years as the chief executive of New York Public Radio, which owns WNYC, WQXR and Gothamist. It was a turbulent period for WNYC, which has had significant staff turnover and bullying complaints.                                                                                                                                                                                                                                                                                    , In an email to staff, the New York Public Radio board chair, Timothy Wilkins, said that Ms. Sheikholeslami had invested significantly in diversity, equity and inclusion efforts at the organization while also strengthening its financial position and increasing the size of the newsroom.                                                                                                                                                                                                                                                                                                                                                              , “And she did all this while leading through a pandemic — working with all of you to keep our audiences informed, connected and inspired during one of the most challenging times for our organization and our city and region,” Mr. Wilkins wrote.                                                                                                                                                                                                                                                                                                                                                                                                         , Mr. Wilkins said the board would lead a national search for a new leader.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , By Michael J. de la Merced and Kellen Browning                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The video game publisher Take-Two Interactive agreed on Monday to buy Zynga, a mobile game maker, for more than $11 billion, in a deal that unites the makers of Grand Theft Auto and FarmVille.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , With the deal, Take-Two — known for producing games like Grand Theft Auto and NBA 2K for traditional platforms like the Sony PlayStation console and personal computers — is acquiring a specialist in mobile and social gaming, with Zynga’s best-known titles including Words With Friends and other apps.                                                                                                                                                                                                                                                                                                                                               , Adding Zynga’s stable of app developers is meant to help Take-Two roll out more smartphone versions of its popular titles. Zynga will also help Take-Two expand its revenue from so-called recurrent consumer spending, in which players pay for new content and upgrades within games.                                                                                                                                                                                                                                                                                                                                                                    , The deal values Zynga at about $12.7 billion, making it one of the largest in the history of the video game industry, topping the purchase of Supercell by the Chinese internet giant Tencent in 2016 for $10 billion and Microsoft’s acquisition of ZeniMax Media for $7.5 billion in 2020.                                                                                                                                                                                                                                                                                                                                                               , The gaming industry has boomed during the pandemic, providing large tech companies with the cash to buy smaller rivals. It has also helped more troubled companies like Zynga, which found early success tying itself to Facebook with the mobile game FarmVille. The company stumbled as the mobile gaming industry shifted away from social media and toward apps like Clash of Clans and Candy Crush.                                                                                                                                                                                                                                                   , Zynga has laid off employees and cycled through executives over the years as it struggled to maintain relevance. It was still losing money — $42 million — in its most recent quarterly earnings report.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , By contrast, Take-Two is profitable and has gone on a buying spree since the pandemic, adding a handful of smaller studios to its portfolio of games.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “This strategic combination brings together our best-in-class console and PC franchises, with a market-leading, diversified mobile publishing platform that has a rich history of innovation and creativity,” Strauss Zelnick, Take-Two’s chairman and chief executive, said in a statement.                                                                                                                                                                                                                                                                                                                                                               , Frank Gibeau, Zynga’s chief executive, said in a statement that combining the two companies would “allow us to create even better games, reach larger audiences and achieve significant growth as a leader in the next era of gaming.”                                                                                                                                                                                                                                                                                                                                                                                                                     , Under the terms of the deal, Take-Two will pay $3.50 in cash and $6.36 worth of newly issued stock for each Zynga share. That amounts to $9.86 a share, up 64 percent from where Zynga closed on Friday.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , By Daisuke Wakabayashi                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Google wrongly claimed attorney-client privilege to protect documents subpoenaed in a National Labor Relations Board case filed by former employees who say the company fired them because of their unionization efforts, a labor judge has ruled.                                                                                                                                                                                                                                                                                                                                                                                                         , The administrative law judge, Paul Bogas, whom the N.L.R.B. appointed as a special master to review the documents, said in a report on Friday that “this broad assertion is, to put it charitably, an overreach.”                                                                                                                                                                                                                                                                                                                                                                                                                                          , The ruling is the latest legal blow to Google’s defense against a complaint, brought by the labor agency in December 2020, that said the company illegally fired and surveilled employees who were involved in labor organizing.                                                                                                                                                                                                                                                                                                                                                                                                                           , A Google spokeswoman, Jennifer Rodstrom, said in a statement on Monday that the matter had nothing to do with unionization but was about employees breaching security protocols. “We disagree with the characterization of the legally privileged materials referred to by the complainants,” she said.                                                                                                                                                                                                                                                                                                                                                    , Judge Bogas ruled in November that Google had improperly characterized 71 of 80 documents sought by the former employees as privileged. The latest report covers around 200 additional documents pertaining to communications around Google’s hiring of IRI Consultants, a firm known for its anti-union work, as part of Project Vivian, an effort to fight labor organizing at the company.                                                                                                                                                                                                                                                              , Google must hand over nearly all of those 200 documents, Judge Bogas ruled. He also ordered the company to produce for his review more than 1,000 additional documents that it logged as privileged.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Google’s argument that it had the right to withhold the documents was not “persuasive,” Judge Bogas said, because IRI assisted Google with messaging that did not include legal advice.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , In one document that the judge said did not pass muster for confidentiality, a Google lawyer explained that the company wanted consulting help for Project Vivian “to engage employees more positively and convince them that unions suck.” The lawyer provided a long list of areas where IRI could help, including “understanding the current sentiment around labor organizing/unionization efforts at Google.” The lawyer did not mention assistance with legal help.                                                                                                                                                                                  , In another document that Google claimed was privileged, a different Google lawyer offered public relations advice but not legal counsel. The lawyer proposed that the company find a “respected voice” to publish an editorial about what a union would look like in a tech workplace to discourage employees of Facebook, Microsoft, Amazon and Google from forming one. A human resources director said that she supported the idea, but that it needed to be done without Google’s fingerprints. IRI then sent a proposed editorial to the Google lawyer.                                                                                               , Judge Bogas also chastised Google for marking documents as privileged just because it copied in a company lawyer, even though the communication did not seek legal advice.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “A company cannot cloak a document in privilege merely by providing a copy to counsel,” the judge wrote.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The New York Times reported earlier that Google encouraged employees to aggressively mark internal communication as “A/C Priv,” which is shorthand for “attorney-client privilege,” in the subject line even if they are not seeking legal advice.                                                                                                                                                                                                                                                                                                                                                                                                         , Google denied that was the case, and said it informed employees that they should do that only when appropriate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , By Katie Robertson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The Committee to Protect Journalists on Monday named Jodie Ginsberg, a journalist turned news executive, as its new president.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Ms. Ginsberg, a former international correspondent and business journalist at Reuters, is the chief executive of Internews Europe, a nonprofit organization that supports independent media. She previously headed the Index on Censorship, a freedom of expression campaign group.                                                                                                                                                                                                                                                                                                                                                                        , She will replace Joel Simon, who led the Committee to Protect Journalists for 15 years before announcing last year that he was stepping down. Founded in 1981, the organization defends the rights of journalists around the world.                                                                                                                                                                                                                                                                                                                                                                                                                        , “We wanted to find someone who had experience as a journalist and as an advocate,” Kathleen Carroll, the chair of the Committee to Protect Journalists, said in an interview. “The two skills are different. You really need granular on-the-ground experience if you are going to be the head of an organization protecting journalists.”                                                                                                                                                                                                                                                                                                                 , Ms. Ginsberg, a citizen of Britain and South Africa who was also the bureau chief for Britain and Ireland during her 11 years at Reuters, is scheduled to start as the organization’s president in April.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “Journalists help hold power to account, expose corruption and injustice and shine a spotlight on the most important issues of our day — from health to climate to social change,” Ms. Ginsberg said in a statement. “For that, far too many face a growing threat of violence and harassment. I am determined to help reverse this trend and am honored to be leading C.P.J. at such a critical juncture.”                                                                                                                                                                                                                                                , According to a census by the organization, the number of journalists jailed for doing their job hit 293 in 2021, a record. At least 24 journalists were killed for reasons having to do with their work last year, according to the group.                                                                                                                                                                                                                                                                                                                                                                                                                 , By John Koblin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Audie Cornish, who signed off as a host of NPR’s news program “All Things Considered” on Friday, is heading to CNN’s new streaming service.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The longtime NPR star, who had been a host of “All Things Considered” since 2012 and was a 17-year veteran of the public broadcaster, will host a weekly show for CNN+, as well as contribute to the streaming service’s slate of live programming, the network announced on Monday. She will also appear on the cable news network during breaking news stories.                                                                                                                                                                                                                                                                                          , “I am very excited to join CNN and the CNN+ team,” Ms. Cornish said in a statement. “There are fresh stories to be told and new ways to tell them. CNN has a dynamic system of reporters and storytelling channels. I am thrilled to be a part of it.”                                                                                                                                                                                                                                                                                                                                                                                                     , The move comes as the CNN president, Jeff Zucker, builds a roster for CNN+, which is scheduled to debut in the spring.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ms. Cornish’s exit from NPR followed the recent departures of other prominent NPR hosts of color, including Noel King, who went to Vox Media, and Lulu Garcia-Navarro, who went to The New York Times. Ari Shapiro, Ms. Cornish’s former co-host at “All Things Considered,” observed on Twitter last week that NPR was “hemorrhaging hosts from marginalized backgrounds.”                                                                                                                                                                                                                                                                                , “If NPR doesn’t see this as a crisis, I don’t know what it’ll take,” Mr. Shapiro continued.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Ms. Cornish addressed the issue in a Twitter thread on Thursday. “My path through public media and frankly journalism has of course not been all roses,” she wrote, adding that she had often been “the only person of color” covering events. She added that circumstances have changed over the years “for the better.”                                                                                                                                                                                                                                                                                                                                  , Last week, CNN announced it had hired Alison Roman, the author of a popular cooking newsletter, to host a “highly opinionated and never finicky” cooking show for the planned streaming service. The network also announced that the actress and producer Eva Longoria would host a series in which she travels Mexico and explores the culinary culture there, similar to the CNN show “Stanley Tucci: Searching for Italy.” Last month, the anchor Chris Wallace left Fox News to join CNN+.                                                                                                                                                             , By Eshe Nelson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Energy prices have soared across Europe over the past few months, straining household budgets and unnerving politicians. As the cost of oil and natural gas remain volatile, a policymaker at the European Central Bank has warned that the transition to a low carbon economy could lead to rising energy bills and faster inflation.                                                                                                                                                                                                                                                                                                                     , This could also force central bankers to rethink how energy prices are considered when setting monetary policy, Isabel Schnabel, a member of the central bank’s executive board, said in a speech on Saturday.                                                                                                                                                                                                                                                                                                                                                                                                                                             , Some central banks, increasingly focused on the risks created by climate change, have set out plans to stress-test banks to see if their financial systems can withstand the risks from extreme weather and are analyzing the economy to calculate the costs of the transition to a low-carbon economy.                                                                                                                                                                                                                                                                                                                                                    , “While in the past energy prices often fell as quickly as they rose, the need to step up the fight against climate change may imply that fossil fuel prices will now not only have to stay elevated, but even have to keep rising if we are to meet the goals of the Paris climate agreement,” which commits countries to restrict global warming to 1.5 degrees Celsius above preindustrial levels, Ms. Schnabel said.                                                                                                                                                                                                                                    , Looking ahead, higher carbon prices, fewer investments in fossil fuel energy, and a period during which renewable energy production can’t meet demand will mean there is a risk of a “protracted transition period” when energy bills are rising, Ms. Schnabel said.                                                                                                                                                                                                                                                                                                                                                                                       , But governments shouldn’t roll back or slow down transition measures in the face of higher prices, she added. For central banks, the challenges posed by the green transition are “equally profound,” she said.                                                                                                                                                                                                                                                                                                                                                                                                                                            , Central bankers tend to “look through” energy price shocks because the surges are usually short-lived. Also, policymakers don’t want to exacerbate the negative effects by raising interest rates and dampening demand, Ms. Schnabel said.                                                                                                                                                                                                                                                                                                                                                                                                                 , That is the case in the eurozone today, where the annual rate of inflation climbed to 5 percent last month, a record high. Energy prices were 26 percent higher than they were a year earlier.The European Central Bank has held interest rates at record lows and made a plan to slow, but not stop, its bond-buying programs because it expects inflation to be once again below its 2 percent target by next year. Christine Lagarde, the president of the bank, has insisted that the surge in prices is temporary because, for one, energy costs will stabilize throughout this year, and so monetary policy needs to continue to support the economy., But Ms. Schnabel said that the central bank’s forecasts depend on energy prices not contributing to inflation rates in 2023 and 2024 — something that would be “unusual.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “The scale of the energy transition, and the political determination behind it, implies that these estimates could be conservative,” she said, adding that the energy transition poses “measurable upside risks” to the bank’s inflation projections.                                                                                                                                                                                                                                                                                                                                                                                                      , If higher energy prices from the transition push up long-term inflation expectations and cause widespread demands for higher wages, or if higher carbon prices help increase economic growth and push up prices more broadly, then the central bank would need to act, Ms. Schnabel said.                                                                                                                                                                                                                                                                                                                                                                  , By Niraj Chokshi                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Airlines canceled thousands more flights in recent days as the industry tried to move past its holiday hangover.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Bad weather and coronavirus outbreaks among workers continued to disrupt schedules across the United States, but airlines have also called off many recent flights, in advance, so they can correct course at a traditionally slow time for travel without surprising customers with last-minute cancellations.                                                                                                                                                                                                                                                                                                                                            , About 5,000 flights were canceled from Friday through Sunday, according to FlightAware, a data tracking service, with the daily number of cuts declining steadily over that period. Southwest Airlines suspended over 1,000 flights, more than any other carrier. SkyWest Airlines, which operates flights for several major carriers, and United Airlines each canceled more than 500 flights.                                                                                                                                                                                                                                                            , The turmoil began before Christmas, caused by bad weather in the West and staff shortages because of virus outbreaks among employees. Snowfall in the Northeast continued to wreak havoc at major airport hubs across the country into the first weekend of this month.                                                                                                                                                                                                                                                                                                                                                                                    , “Given the ongoing surge in Covid cases and related sick calls, we’ve been working with each of our major partners to proactively reduce our January schedules,” SkyWest said in a statement. The airline operates flights for United, Delta Air Lines, American Airlines and Alaska Airlines and said the pullback is intended to “ensure we’re able to adequately staff our remaining flying as we work to recover in the coming weeks.”                                                                                                                                                                                                                 , After canceling flights at high rates over the holidays, JetBlue Airways said it would preemptively cut about 1,300 flights in the first half of January. Alaska said in a statement last week that it would slash about one in 10 flights planned for the month to gain “the flexibility and capacity needed to reset.”                                                                                                                                                                                                                                                                                                                                   , As in many other industries, airlines are also contending with workers calling in sick at high rates as the Omicron virus variant spreads at astonishing speed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , “It has been one of the most difficult operational environments we’ve ever faced,” Allison Ausband, Delta’s chief customer experience officer, said in a statement last week apologizing to customers for the disorder.                                                                                                                                                                                                                                                                                                                                                                                                                                    , To deal with staffing shortages, many carriers have started offering extra pay to those who were otherwise not scheduled to work. Southwest, for example, said last week that it was offering double pay for most of the month to employees who picked up extra shifts, incentives available to workers across its operation, including ground staff, flight attendants, customer service employees, flight schedulers and maintenance technicians.                                                                                                                                                                                                        , The chaos comes at a frustrating time for the industry, which is preparing for a significant rebound this summer. That recovery rests largely on the hope that the pandemic will be mostly under control by then and that people will be more willing to travel internationally and for work.                                                                                                                                                                                                                                                                                                                                                              , On television, the pandemic is already over. In reality, it continues to wreak havoc on the entertainment industry.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The Golden Globes, which traditionally kick off the award show season, were not televised on Sunday night because of ethical issues surrounding the group that gives out the awards. The jump in coronavirus cases is also threatening the rest of awards season, which is about more than just self-congratulation.                                                                                                                                                                                                                                                                                                                                       , The undercutting of an effective form of advertising comes at a time when the industry desperately needs it, and it has the movie business reconsidering its fate in a year that was supposed to signal a return of Hollywood’s glamour, Nicole Sperling reports for The New York Times. The Academy Awards remain scheduled for March 27, with nominations on Feb. 8, but there has been no indication what the event will be like.                                                                                                                                                                                                                       , If the Hollywood hype machine loses steam, it could prove devastating to the box office, which has struggled with each rise in coronavirus cases. The latest Spider-Man movie was a big success, but other big-budget films, like “West Side Story,” flopped. Pixar said last week that its latest film, “Turning Red,” would skip theaters and will debut exclusively on Disney+ in March, free for subscribers.                                                                                                                                                                                                                                          , Movies with midsize budgets are particularly vulnerable, given their reliance on word of mouth and awards to spread awareness. In response, studios are experimenting with slowing theatrical rollouts, accelerating home streaming and holding more virtual screenings to court award voters.                                                                                                                                                                                                                                                                                                                                                             , “The movie business is this gigantic rock, and we’re close to seeing that rock crumble,” said Stephen Galloway, the dean of Chapman University’s Dodge College of Film and Media Arts. According to a recent study, 49 percent of prepandemic moviegoers are no longer buying tickets. Eight percent say they will never return.                                                                                                                                                                                                                                                                                                                           , By Coral Murphy Marcos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Fed chair confirmation hearing: The Senate Banking Committee will begin to hold confirmation hearings for the Federal Reserve chair, Jerome H. Powell. Mr. Powell is expected to face questions regarding the outlook on inflation and the Fed’s former permissive culture toward stock trading by policymakers.                                                                                                                                                                                                                                                                                                                                           , Consumer Price Index: The Labor Department is set to publish its latest report on price increases, which is being watched closely by the Federal Reserve as policymakers decide how quickly to pull back on the central bank’s support for the economy.                                                                                                                                                                                                                                                                                                                                                                                                    , Fed vice chair confirmation hearing: Lael Brainard, a Fed governor, will also face the Senate Banking Committee for her confirmation hearing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Delta earnings: The airline is set to publish its financial performance report for the three months ending in December as it faces new staffing challenges posed by the Omicron variant of the coronavirus. Delta canceled more than 1,700 flights between Christmas Eve and New Year’s weekend.                                                                                                                                                                                                                                                                                                                                                           , Retail sales: The Commerce Department’s report on consumer spending in December will offer economists a snapshot of spending during the last month of the holiday season, as well as a sense of whether the Omicron variant affected retailers.                                                                                                                                                                                                                                                                                                                                                                                                            , Bank earnings: JPMorgan Chase, Citigroup and Wells Fargo are set to publish their earnings reports for the fourth quarter. Analysts are expecting the banks to post strong profits, driven by investment-banking and strong capital markets.                                                                                                                                                                                                                                                                                                                                                                                                               , This year’s tax filing season is likely to be another challenging one because of pandemic-related tax changes. But the first step for many taxpayers is simple: Check your mail.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Internal Revenue Service is sending special statements to the millions of Americans who received monthly payments of the expanded child tax credit last year as part of the pandemic relief program. The agency is also sending letters to the people who got the third stimulus payment last year, reports Ann Carrns for The New York Times.                                                                                                                                                                                                                                                                                                         , The advance payments of the child tax credit reflected half of a family’s estimated credit. To claim the other half, people must enter information from the I.R.S. statement on their federal tax return to reconcile the amounts. The document, I.R.S. Letter 6419, details the total amount of advance payments paid last year and how the amount was calculated.                                                                                                                                                                                                                                                                                        , A quick refresher:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Congress expanded the child tax credit for the 2021 tax year, providing as much as $3,600 per child, up from $2,000.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Half of the credit was paid in advance, divided into monthly payments delivered from July through December.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The aid went to families with about 61 million children, according to the Treasury Department.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The I.R.S. is also sending a second letter later this month regarding the third round of stimulus checks. The third batch of checks, of $1,400 per person, was sent beginning in March as part of the pandemic relief effort.                                                                                                                                                                                                                                                                                                                                                                                                                              , Most eligible people have already received the payments. But if you didn’t, or if you got less than the full amount, the letter — known as Letter 6475, Your Third Economic Impact Statement — will help determine if you can claim the money as a “recovery rebate credit” on your 2021 tax return.                                                                                                                                                                                                                                                                                                                                                       , Filing season normally starts in mid- to late January, but the I.R.S. hasn’t yet announced when it will begin accepting returns. READ MORE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/10/goldman-predicts-the-fed-while-hike-rates-four-times-this-year-more-than-previously-expected.html </td>
   <td style="text-align:left;"> 2022-01-10 20:35:18 </td>
   <td style="text-align:left;"> Goldman predicts the Fed will hike rates four times this year, more than previously expected </td>
   <td style="text-align:left;"> , Persistently high inflation combined with a labor market near full employment will push the Federal Reserve to raise interest rates more than expected this year, according to the latest forecast from Goldman Sachs.                                                                                                                                                                                      , The Wall Street firm's chief economist, Jan Hatzius, said in a note Sunday that he now figures the Fed to enact four quarter-percentage point rate hikes in 2022, representing an even more aggressive path than the central bank's indications of just a month ago. The Fed's benchmark overnight borrowing rate is currently anchored in a range between 0%-0.25%, most recently around 0.08%.            , "Declining labor market slack has made Fed officials more sensitive to upside inflation risks and less sensitive to downside growth risks," Hatzius wrote. "We continue to see hikes in March, June, and September, and have now added a hike in December for a total of four in 2022."                                                                                                                     , Goldman had previously forecast three hikes, in line with the level Fed officials had penciled in following their December meeting.                                                                                                                                                                                                                                                                         , The firm's outlook for a more hawkish Fed comes just a few days ahead of key inflation readings this week that are expected to show prices rising at their fastest pace in nearly 40 years. If the Dow Jones estimate of 7.1% year-over-year consumer price index growth in December is correct, that would be the sharpest gain since June 1982. That figure is due out Wednesday.                         , At the same time, Hatzius and other economists do not expect the Fed to be deterred by declining job growth.                                                                                                                                                                                                                                                                                                , Nonfarm payrolls rose by 199,000 in December, well below the 422,000 estimate and the second month in a row of a report that was well below consensus. However, the unemployment rate fell to 3.9% at a time when employment openings far exceed those looking for work, reflecting a rapidly tightening jobs market.                                                                                       , Hatzius thinks those converging factors will cause the Fed not only to raise rates a full percentage point, or 100 basis points, this year but also to start shrinking the size of its $8.8 trillion balance sheet. He pointed specifically to a statement last week from San Francisco Fed President Mary Daly, who said she could see the Fed starting to shed some assets after the first or second hike., "We are therefore pulling forward our runoff forecast from December to July, with risks tilted to the even earlier side," Hatzius wrote. "With inflation probably still far above target at that point, we no longer think that the start to runoff will substitute for a quarterly rate hike."                                                                                                             , Up until a few months ago, the Fed had been buying $120 billion a month in Treasurys and mortgage-backed securities. As of January, those purchases are being sliced in half and are likely to be phased out completely in March.                                                                                                                                                                           , The asset purchases helped hold interest rates low and kept financial markets running smoothly, underpinning a nearly 27% gain in the S&amp;P 500 for 2021.                                                                                                                                                                                                                                                     , The Fed most likely will allow a passive runoff of the balance sheet, by allowing some of the proceeds from its maturing bonds to roll off each month while reinvesting the rest. The process has been nicknamed "quantitative tightening," or the opposite of the quantitative easing used to describe the massive balance sheet expansion of the past two years.                                          , Goldman's forecast is in line with market pricing, which sees a nearly 80% chance of the first pandemic-era rate hike coming in March and close to a 50-50 probability of a fourth increase by December, according to the CME's FedWatch Tool. Traders in the fed funds futures market even see a nonnegligible 22.7% probability of a fifth rise this year.                                                , Still, markets only see the funds rate increasing to 2.04% by the end of 2026, below the 2.5% top reached in the last tightening cycle that ended in 2018.                                                                                                                                                                                                                                                  , Markets have reacted to the prospects of a tighter Fed, with government bond yields surging higher. The benchmark 10-year Treasury note most recently yielded around 1.77%, nearly 30 basis points higher than a month ago.                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/latvia/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-10 20:13:58 </td>
   <td style="text-align:left;"> Latvia Trade Gap Narrows in November </td>
   <td style="text-align:left;"> Latvia’s trade deficit narrowed to EUR 23 million in November of 2021 from EUR 79.4 million in the corresponding month of the previous year. Exports jumped by 30.7 percent yearly to EUR 1,635.8 million, driven by base metals and articles of base metals (110 percent); wood and articles of wood (46.6 percent); and mineral products (110 percent). Sales to EU countries advanced 38.8 percent, while those to CIS countries dropped by 3.8 percent. Meanwhile, imports rose by a softer 24.6 percent yearly to EUR 1,658.8 million, driven by mineral products (79 percent); products of the chemical and allied industries (42.9 percent); and base metals and articles of base metals (45.6 percent. Purchases from the EU rose by 23.3 percent, while those from CIS countries jumped by 42.9 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/weather/2022/01/10/climate-change-extreme-weather-explainer-lon-orig-bks.cnn </td>
   <td style="text-align:left;"> 2022-01-10 20:11:14 </td>
   <td style="text-align:left;"> How climate change makes extreme weather worse - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-10 19:58:26 </td>
   <td style="text-align:left;"> Lithuania Inflation Rate at Over 13-Year High </td>
   <td style="text-align:left;"> Lithuania’s annual inflation rate increased to 10.6 percent in December of 2021 from 9.2 percent in the previous month. It was the highest inflation rate since September 2008, mainly boosted by prices of housing &amp; utilities (24.6 percent vs 18.8 percent in November), food &amp; non-alcoholic beverages (10.4 percent vs 7.6 percent), and transport (17.8 percent vs 19.9 percent). At the same time prices advanced more for recreation &amp; culture (9 percent vs 8.5 percent), clothing &amp; footwear (4.7 percent vs 2.7 percent), and miscellaneous goods &amp; services (7.8 percent vs 7 percent). On a monthly basis, consumer prices rose 1.2 percent in December, accelerating from a 0.9 percent increase in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-10 19:48:00 </td>
   <td style="text-align:left;"> Natural Gas Futures at Near 6-Week High </td>
   <td style="text-align:left;"> Natural gas futures rose past $4.1 per million British thermal units, the highest since December 1st, as temperatures were expected to stay cold through January and a freeze-off in parts of the US more than offset higher-than-usual storage levels. New weather forecasts see an arctic blast ripping through the US Midwest and Northeast, which should augur well for heating and power demand. Charges for electricity and natural gas in the US Northeast rose to their highest since January 2018, as the weather remained cold after a snowstorm last week. Meanwhile, natural gas wells remained frozen in Texas, New Mexico, North Dakota, Pennsylvania, West Virginia and Ohio, which has caused output to drop to 94.5 bcfd so far this month, compared with a record 97.6 bcfd last month. Elsewhere, strong demand for US LNG exports has been keeping exporting facilities operating at unprecedented levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/iron-ore </td>
   <td style="text-align:left;"> 2022-01-10 19:47:00 </td>
   <td style="text-align:left;"> Iron Ore Slightly Down on Worries Over Omicron Spread </td>
   <td style="text-align:left;"> Spot prices of iron ore with 63.5% iron content for delivery to Tianjin were slightly down at $120 a tonne, as news about a coronavirus outbreak in the region raised concerns over disruptions to production and transportation in downstream sectors. The northern Chinese city of Tianjin announced tightening exit controls over the weekend and began mass-testing its 14 million residents after it reported cases of infection with the Omicron. Still, iron ore remained close to an over two-month high of $122 a tonne hit on December 21st, amid hopes for an easing of steel production controls in top steel producer China after the Beijing 2022 Olympics next month. Elsewhere, Brazilian miner Vale said it has partially halted operations at its Southeastern and South iron ore systems due to heavy rains that are affecting the state of Minas Gerais, but left 2022 production forecasts unchanged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/new-orders </td>
   <td style="text-align:left;"> 2022-01-10 19:18:05 </td>
   <td style="text-align:left;"> Sweden New Orders Growth Eases in November </td>
   <td style="text-align:left;"> Total orders received by Swedish industries rose by 3 percent year-on-year in November of 2021, easing from an upwardly revised 7.8 percent increase in the previous month. Orders received from customers in Sweden surged by 7.2 percent (vs 11.7 percent in October) and orders received from customers abroad went up by 0.5 percent (vs 4.6 percent). On a seasonally adjusted monthly basis, orders went down 0.9 percent, after a 5.9 percent gain in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 19:17:55 </td>
   <td style="text-align:left;"> South African Stocks Rebound </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index rebounded 0.5% to trade at the 74,300 level on Monday, boosted by financials and commodity-backed shares, while investors await for US consumer price data due Wednesday for an indication on policy rate hikes by the Fed and future gold prices. The American inflation rate from December is expected to come at 7%, a four-decade high. On the corporate front, Impala Platinum (2.2%), and Anglo American (1.3%) booked gains, tracking higher bullion prices, while Exxaro Resources (1.3%) rose on higher coal prices. Meanwhile, traders keep an eye on the possible tariffs to be implemented for state-owned utility Eskrom. The National Energy Regulator of South Africa pro forma implementation plans show tariffs could increase to 40.38% or 41.18%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59930934?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-10 19:15:03 </td>
   <td style="text-align:left;"> Virgin Mobile and O2 users will not face EU roaming charges </td>
   <td style="text-align:left;"> Virgin Mobile and O2 phone users will not face roaming charges following announcements by other networks to reintroduce extra fees after Brexit.                                                                                                , It means customers travelling to Europe will be able to use their mobile data and make calls and texts on the same deal as they have in the UK.                                                                                                 , Vodafone, EE and Three are set to reintroduce roaming fees this year for customers travelling to Europe.                                                                                                                                        , Consumer champion Which? urged the UK and EU to "strike a deal" on charges.                                                                                                                                                                     , Before the UK left the EU, users were able to use their calls, texts, and data allowance in their mobile plans in any EU country after the bloc removed roaming charges in 2017.                                                                , However, the EU trade deal of December 2020 gave mobile operators the option of reintroducing charges.                                                                                                                                          , Prime Minister Boris Johnson tweeted that he welcomed the decisionby Virgin and O2 to keep roaming free across Europe.                                                                                                                          , Virgin Media O2 - the company that owns the Virgin Mobile and O2 networks - said a family of four going abroad for two weeks could see an extra £100 on their bill, based on analysis of rates from other providers.                            , "We're starting the year by giving our customers some certainty: we will not be reintroducing roaming fees in Europe for customers on O2 or Virgin Mobile," said Gareth Turpin, chief commercial officer.                                       , "With many Brits now looking to plan a trip abroad, we've got our customers covered and extra roaming charges will be one less thing to worry about."                                                                                           , Vodafone plans to bring back roaming charges at the end of January, while EE is set to in March. Both networks delayed reintroducing the charges earlier due to testing and technical issues respectively.                                      , Meanwhile, Three is to introduce fees in May.                                                                                                                                                                                                   , Customers who joined or upgraded with EE after 7 July 7 2021 face a £2 daily roaming charge in EU countries, while Vodafone will charge the same fee for people who joined the network after 11 August 11 or upgraded or renewed their contract., However, both companies will offer deals to avoid the fee, with EE customers able to buy a 30-day roaming pass for £10 and Vodafone users able to pay £1 a day for an eight or 15-day pass.                                                     , Three will bring in the £2 daily charge for people who joined or upgraded after 1 October 2021.                                                                                                                                                 , Sue Davies, head of consumer protection policy at Which?, said it was "reassuring" that Virgin Media O2 had offered some certainty to customers.                                                                                                , "As the UK continues to negotiate trade deals, it should take the opportunity to lower the cost of roaming for consumers travelling around the world," she added.                                                                               , "The UK and EU should also work to strike a deal on roaming charges to stop companies chipping away at the roaming benefits customers have become used to and to ensure the high charges people used to face do not return."                    , In April last year, a £31bn merger between Virgin Media and O2 was approved, making it one of the the UK's largest entertainment and telecoms firms.                                                                                            , What is it really like to live in Dubai?                                                                                                                                                                                                        , The unusual way a parasite attracts pollinators                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nigeria/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 18:59:37 </td>
   <td style="text-align:left;"> Stocks in Nigeria Hit Near 4-year High </td>
   <td style="text-align:left;"> NSE-All Share increased to a near 4-year high of 44314 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 18:30:00 </td>
   <td style="text-align:left;"> BSE Sensex Extends Gains on Monday </td>
   <td style="text-align:left;"> The BSE Sensex ended 650.98 points or 1.09% higher to close at 60,395.63 on Monday, on expectations of a strong earnings season despite weak global cues and surging covid cases in the country. Moreover, domestic sentiment strengthened as the Ministry of External Affairs Secretary said that the World Bank estimated India’s GDP to be over $10 trillion in next 25 years, while addressing the Youth Pravasi Bhartiya Diwas Conference yesterday. Gains were driven by banks, autos and a few capital goods. Among the individual stocks, Titan (+3.29%), Maruti (+2.74%), Larsen and Toubro (+2.54%),State Bank of India (+2.49%) and Housing Development Finance Corporation Limited (+2.43%) were the top gainers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-10 18:19:05 </td>
   <td style="text-align:left;"> Italian Stocks Trade Higher on Monday </td>
   <td style="text-align:left;"> The FTSE MIB Index traded 0.2% higher at around the 27,670 level on Monday, boosted by the banking and utilities sectors, as investors weigh on domestic labor market data while awaiting US consumer price data on Wednesday. The Italian unemployment rate for November was at 9.2%, below market expectations. Meanwhile, consumer inflation in the US is expected to rise to 7% on the year, a 4-decade high. On the corporate front, Banca Carige gained 1.7% after reports that Bper Banca (1.1%) improved its initial offer to acquire Carige, becoming the top candidate for the acquisition ahead of Credit Agricole. At the same time, utilities rose 0.8%, driven by Enel (1%). </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-11 10:03:45 UTC +8

<div style="border: 1px solid #ddd; padding: 0px; overflow-y: scroll; height:900px; overflow-x: scroll; width:100%; "><table style="width:30%; width: auto !important; margin-left: auto; margin-right: auto;" class="table table-striped">
 <thead>
  <tr>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> Symbol </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> Date </th>
   <th style="text-align:left;position: sticky; top:0; background-color: #FFFFFF;position: sticky; top:0; background-color: #FFFFFF;"> Comment </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:03:25 </td>
   <td style="text-align:left;"> ;) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:03:07 </td>
   <td style="text-align:left;"> SOME PLAYS POSTED TODAY 🏆🔥 :
$ADBE $ACN $SPY $TSLA $NFLX 

https://rooms.stocktwits.com/checkout/4451239/prod_KEH7byRXcPlJ63 👈🏻 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:02:39 </td>
   <td style="text-align:left;"> $SPY america is waking up from its covid slumber. Time to remove the illegitimate president and put trump back in! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:02:37 </td>
   <td style="text-align:left;"> :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:02:25 </td>
   <td style="text-align:left;"> $SPY uh oh here comes the bears 🤨 futes -3.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:02:24 </td>
   <td style="text-align:left;"> $SPY i covered some shorts because i saw capitulation..short term bottom but just the beginning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:02:12 </td>
   <td style="text-align:left;"> $SPY ready for a dip or a rip tomorrow, just please for the love of god no more sideways trading. today was a breath of fresh air compared to the last couple of weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:00:45 </td>
   <td style="text-align:left;"> $INTC bought at 44.5 because $spy was red and this was up 2% and earnings soon lets go! follow me on instagram. 
my youtube channel if you need to get into technical analysis. also perdicted spy reversing today because it was down 2% too quickly!https://www.youtube.com/watch?v=W6sWDOP9n6w&amp;amp;t=264s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:00:39 </td>
   <td style="text-align:left;"> $SPY Don&amp;#39;t lie.. we are all a little perplexed on whats gonna happen tomorrow. Very opened ended. Gonna have to see how that premarket looks before bell and how the overall health is looking. I dont think futures will tell much tonight.. like they ever do anyways. But you catch my drift. Wait and see game I suppose. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 10:00:21 </td>
   <td style="text-align:left;"> Daily Market Update for 1/10 
$NASDAQ $COMPQ $IXIC $SPY $DJIA $RUT 
https://www.drewby.com/2022/01/10/daily-market-update-for-1-10/ 
Markets dipped in the morning, but the Nasdaq rallied in the afternoon to close the day with a small gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:59:14 </td>
   <td style="text-align:left;"> $SPY figure it out yet ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:58:44 </td>
   <td style="text-align:left;"> $SPY Nice gains made on the reversal!!🚨
Join the free discord and start banking with us!💰(1st 100 members are free!)
Link in bio!🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:58:42 </td>
   <td style="text-align:left;"> $SPY rsi of breadth, pretty bearish here as short, medium, and long term breadth all fall below 50% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:58:40 </td>
   <td style="text-align:left;"> $SPY  what a day ! Earlier morning seems like end of world, but those  465 puts again proved its power </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:58:31 </td>
   <td style="text-align:left;"> $SPY we flyin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:58:27 </td>
   <td style="text-align:left;"> $SPY $QQQ The FED is now expected to hike rates 4 times due to high inflation but if inflation begins to ease later this year then the FED could reduce the number of rate hikes to something like 3 or even 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:57:58 </td>
   <td style="text-align:left;"> $SPY Down 5 days in a row. 477.59 | 477.59 | 468.62 | 467.86 | 466.03 | 458.05 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:57:52 </td>
   <td style="text-align:left;"> $SPY  Gotta have these light red to flat futes to build momentum into the open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:57:52 </td>
   <td style="text-align:left;"> $SPY any idea when fed speaking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:57:10 </td>
   <td style="text-align:left;"> $SPY red futures hehehehe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:56:14 </td>
   <td style="text-align:left;"> $SPY just to clarify futes are not ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:55:56 </td>
   <td style="text-align:left;"> $SPY give me liquidity or give me death 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:55:14 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $DJIA … 

Nasdaq January seasonal performance average 👇🏻⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:54:34 </td>
   <td style="text-align:left;"> $SPY $QQQ I see how this plays out 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:54:04 </td>
   <td style="text-align:left;"> $SPY are futes rippin yet? Asking for a friend…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:54:04 </td>
   <td style="text-align:left;"> $SPY 
We all k ow bama better talent but we all know refs are gonna make dawgs win, that’s why I bet 7.5 Gs on their choker butt, let’s go refs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:53:34 </td>
   <td style="text-align:left;"> $SPY: Mentioned over the weekend that if 465 was lost, we would pullback to the 456 level. Look at where we bounced. 456 is the line in the sand. As long as we hold this, I am bullish. If we lose 456, we will see a bigger pullback towards 430. Follow through day important tomo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:53:29 </td>
   <td style="text-align:left;"> $SPY desperate bears salivating at those red futures like we aren’t gonna rip ass tm anyways </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:53:14 </td>
   <td style="text-align:left;"> $SPY what type time you on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:53:03 </td>
   <td style="text-align:left;"> Alright team- here&amp;#39;s the update, $QQQ not only captured the 375 level but also back at the support, making it a triple bottom false breakdown. AND the false breakdown of the TL going back to 2020. This was all a great achievement IMO.  
Heading to $SPY which showed me early signs of reversal also closed within the rising TL going back to Oct 2021. See how the price brokedown while RSI respecting TL, that was a good sign and then capturing all the imp. levels was just cherry on the cake. Overall, an hectic day with a shit ton of hammers. Plan going into next few days- false breakdowns are bear traps and can usually V up or come test the lows again to trap more bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:52:32 </td>
   <td style="text-align:left;"> $SPY time to unleash the bull market in China. 

https://youtu.be/vTDvippHyBM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:52:18 </td>
   <td style="text-align:left;"> $SPY huge stick up my ass. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:52:14 </td>
   <td style="text-align:left;"> $SPY 
SAY NO TO VACCINES UNTIL THEY GIVE REAL DEATH RATES. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:52:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Sick day where if you traded 0dte’s all the way down then nailed the calls all the way up you could turn $1000 into $1,000,000. They don’t come around often but cool to see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:51:49 </td>
   <td style="text-align:left;"> $PFE $SPY $DWAC For all you covid enthusiasts, now you can finally feel safe!

https://babylonbee.com/news/pfizer-introduces-bane-suit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:51:42 </td>
   <td style="text-align:left;"> $SPY that nasdaq intra day move was some 2020 level shit.  wont soon be forgotten. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:50:10 </td>
   <td style="text-align:left;"> US $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:49:51 </td>
   <td style="text-align:left;"> $SPY like there&amp;#39;s no competition </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:49:28 </td>
   <td style="text-align:left;"> $SPY still feel like more blood is on the way, child tax credit, no further stimmy, powells turned hawkish…..Dimon said Powell needs to
give us a “soft landing” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:49:25 </td>
   <td style="text-align:left;"> $SPY bro bama is in a cover 3 rn wow. Its like running prevent in madden on a 3rd and 9🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:49:03 </td>
   <td style="text-align:left;"> $SPY Daddy saved the bulls again? Disgusting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:49:03 </td>
   <td style="text-align:left;"> $SPY 
Fkn refs already starting to fk my bet up, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:48:43 </td>
   <td style="text-align:left;"> $SPY did you see this ? It’s code for if the market can handle the selling - Wall Street knows spy went up 30% but if you take away 5 stocks it went up 0% since 2019 - I can’t post a link if you like 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:48:41 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:48:36 </td>
   <td style="text-align:left;"> $BTC.X last stop 🛑 for leverage ............ and don’t forget our Bitcoin MINIZ 🥳🥳🥳 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:48:19 </td>
   <td style="text-align:left;"> $SPY A lot of folks, delirious bulls mainly think JPow will not walk back quicker rates hike plan but still say something positive.

Not sure what really, only data he really got is Jobs Friday to reference and that was highly bullish for inflation.
Could speak to CPI, PPI, but my guess he doesn&amp;#39;t touch that retail report on Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:47:52 </td>
   <td style="text-align:left;"> $SPY spy closed red and bulls talking crap lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:47:42 </td>
   <td style="text-align:left;"> $SPY  these boards need more ladies. #DontBeGey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:47:37 </td>
   <td style="text-align:left;"> $SPY Closest I have gotten to 300 in a bit. 

How about this:

I am a flight instructor and can teach you how to fly.

I am an aircraft mechanic and can teach you how to fix

I am a general contractor and can teach you how to construct

I am a developer and can teach you the macro ideas of master planned development 

I have a better command of order flow and auction range than 98% of the guys here..
I can teach you the wheel and how to work a core

I could also teach you how to hunt, fish and protect your family but let’s start w this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:47:17 </td>
   <td style="text-align:left;"> $SPY what are futes doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:46:59 </td>
   <td style="text-align:left;"> $SPY shorter than Martin Short, but I have a few K in short term calls. Basically last years 180ed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:46:49 </td>
   <td style="text-align:left;"> $SPY all time highs until February before an actual 10-15% correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:46:07 </td>
   <td style="text-align:left;"> $SPY I have calls and puts so definitely flat all day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:46:05 </td>
   <td style="text-align:left;"> $SPY like young is about to torch weak side 1-on-1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:46:04 </td>
   <td style="text-align:left;"> $SPY 💥 AT LEAST FOUR?!?! So to make a few: heart disease, diabetes, hypertension, obesity, cancer. If you have FOUR of these you MIGHT die with Covid? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:45:38 </td>
   <td style="text-align:left;"> $PFE $SPY https://babylonbee.com/news/pfizer-promises-omicron-vaccine-will-be-ready-in-time-for-their-q1-earnings-report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:45:32 </td>
   <td style="text-align:left;"> $SPY If tomorrow wants to do the same thing as today... IM TOOOOTALY DOWN with that. RIP DOWN RIP UP. LEZZZ GO!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:45:29 </td>
   <td style="text-align:left;"> $SPY These frauds and crooks get all the inside info direct from the horses mouth and get to pull off their massive trades and no one says boo... The retail investor occasionally gets an inside tip makes a few bucks and not only pays it back in restitution but goes to jail and never allowed to trade again...Amazing how that works....

Fed Vice Chair Clarida to step down early following scrutiny over his trades

https://www.cnbc.com/2022/01/10/fed-vice-chair-clarida-to-step-down-early-following-scrutiny-over-his-trades-during-pandemic.html?__source=androidappshare </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:45:18 </td>
   <td style="text-align:left;"> $SPY ONLY retail buying now you will be holding STEVE heavy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:44:29 </td>
   <td style="text-align:left;"> $SPY futes creeping 🙈🙉🤸‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:44:20 </td>
   <td style="text-align:left;"> $SPY Futes&amp;#39; guys , what&amp;#39;s &amp;#39;the JPow trade&amp;#39; showing us for tomorrow. 
Yay or nay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:44:06 </td>
   <td style="text-align:left;"> $DWAC $SPY I love to watch a good dumpster fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:44:02 </td>
   <td style="text-align:left;"> $SPY what kind of D was that? Cover 1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:43:35 </td>
   <td style="text-align:left;"> $SPY RIP weekly puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:42:55 </td>
   <td style="text-align:left;"> $SPY 2022 And 🇺🇸 is on this assholes list ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:42:18 </td>
   <td style="text-align:left;"> #Futures $ES_F #ES_F $spx $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:42:02 </td>
   <td style="text-align:left;"> $SPY this is why u buy the dip. Up 168% on my contracts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:41:45 </td>
   <td style="text-align:left;"> $SPY pos vessel for money. Fuck this etf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:41:37 </td>
   <td style="text-align:left;"> $SPY There were a lot of 530 Puts purchased today. What would be the reason for buying a lot of Puts already WAY ITM? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:41:33 </td>
   <td style="text-align:left;"> $SPY my pick, Georgia 27-21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:41:30 </td>
   <td style="text-align:left;"> $SPY put at open tomorrow before fed speaks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:41:27 </td>
   <td style="text-align:left;"> $SPY timed the bottom perfectly. Gotta learn to play both sides to win it baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:41:19 </td>
   <td style="text-align:left;"> $SPY futes canonly be red anymore.   and alabama sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:40:30 </td>
   <td style="text-align:left;"> $SPY $455 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:40:18 </td>
   <td style="text-align:left;"> $SPY $QQQ tomorrow we slaughter the dogshit bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:39:34 </td>
   <td style="text-align:left;"> 15600 the new Nasdaq floor support level $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:39:30 </td>
   <td style="text-align:left;"> $HIMX   $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:39:06 </td>
   <td style="text-align:left;"> $SPY usa going to shit   China is king now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:39:01 </td>
   <td style="text-align:left;"> $SPY How will the referees call the game when they are getting paid by both teams? $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:38:59 </td>
   <td style="text-align:left;"> $SNAP ...Nice hamer off support although it is still below previous trendline support that is acting as resistance. Snapchat needs to get back above the line. At that point red line will be resistance after that previous support resistance curve yellow will be next major resistance level $STUDY   $SPY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:38:46 </td>
   <td style="text-align:left;"> $SPY Bet it trades sideways tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:56 </td>
   <td style="text-align:left;"> $SPY Oil is key, it&amp;#39;ll start sucking the life outta folk when it gets back to 85+, not far from it either, with inventory going down weekly. 
Oil reports should be telling Wed., Thurs., I expect oil over 82 tomorrow, hearing for those 2 big days. It&amp;#39;s more inflationary data. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:53 </td>
   <td style="text-align:left;"> $spy $o $btc.x j.powell has already increased the money supply 40% in 2021 alone, and bonds yield basically nothing. Is anyone in risk assets actually scared? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:40 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:08 </td>
   <td style="text-align:left;"> $SPY bought UVXY puts today which means I’m </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:08 </td>
   <td style="text-align:left;"> $SPY  Is it ok to talk about TINA again hehe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:04 </td>
   <td style="text-align:left;"> $SPY Georgia has a good punter. good punt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:37:01 </td>
   <td style="text-align:left;"> $SPY SO…
Screw PMI, Inflation, (3) rate hikes and USD/ $DX_F 
The mean reversion coming (like every February) will open up buying ops on small caps, Bio, crypto and metals. 
GLD wants 3k this year. Infrastructure bill will see $30 SLV
But the crap out of weed on down index days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:43 </td>
   <td style="text-align:left;"> New Analysis: Bears tried to break the market and they were broken instead. Plus, is #Bitcoin so bad it&amp;#39;s good? https://cracked.market/2022/01/bears-tried-to-break-the-market-and-they-were-broken-instead-plus-is-bitcoin-so-bad-its-good/ $SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:35 </td>
   <td style="text-align:left;"> $SPY futures don’t even matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:30 </td>
   <td style="text-align:left;"> $SPY I want tomorrow to be identical- sorry I’m selfish 🤷‍♂️📉📈 all cash and i want volatility - shakes out the fakers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:22 </td>
   <td style="text-align:left;"> $TSRI stock of the day tomorrow… $qqq $spy $oef </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:15 </td>
   <td style="text-align:left;"> $SPY lol is this a prank? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:09 </td>
   <td style="text-align:left;"> $SPY is the world really taking medical advice from a veterinarian? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:36:07 </td>
   <td style="text-align:left;"> $SPY  “someone knows something” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:35:57 </td>
   <td style="text-align:left;"> $SPY ITS GOING TO BE A BAD TIME FOR BOND BUYERS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:34:47 </td>
   <td style="text-align:left;"> $SPY 
Georgia qb white boy has wheels! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:34:37 </td>
   <td style="text-align:left;"> $QQQ $spy Dark pool prints don&amp;#39;t lie 
Going to the shit house 🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:34:19 </td>
   <td style="text-align:left;"> $SPY does jpow talking tomorrow even matter anymore? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:34:09 </td>
   <td style="text-align:left;"> $SPY this will probably be green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:34:06 </td>
   <td style="text-align:left;"> $SPY  $QQQ predictions  - Besides Alabama winning tonight, QQQ will open in the red tomorrow and close green barely then Wed/Thurs mother Rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:33:54 </td>
   <td style="text-align:left;"> $SPY will lie through his teeth tomorrow to prop market ...even I know that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:33:40 </td>
   <td style="text-align:left;"> $SPY  every aspiring “Furu” posts before and after pics of their plays. But check this out, it’s not about the Dollar $ gain after the post. It’s the message conveyed in that moment. That Pivotal moment to take profits before reversal and switch to calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:33:29 </td>
   <td style="text-align:left;"> $SPY red january gonna be swanky. Predicting another 5-6% haircut </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:33:10 </td>
   <td style="text-align:left;"> $AAPL $SPY  LETS GO CRAZY TOMORROW BULLS. LIMIT UP. Put $UVXY  in the can of HELLLL🤣🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:33:02 </td>
   <td style="text-align:left;"> $SPY $SPX Lookin for Futes to be retrace’n </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:31:55 </td>
   <td style="text-align:left;"> $SPY Maybe I ain’t serious enough. But take an ST poll and you’ll find that I have a &amp;gt;90% success rate in calling macro moves for the last 5 years. 
No one would put up w my ass if I weren’t as advertised. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:31:40 </td>
   <td style="text-align:left;"> $SPY matter of fact, although sounds absolutely clown ish , i only get out when pelosi get out, the rest never matters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:31:29 </td>
   <td style="text-align:left;"> $SPY The times they are a changin&amp;#39;
https://www.youtube.com/watch?v=DL_kPNFL3dY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:30:56 </td>
   <td style="text-align:left;"> $SPY 10yr starting to go down again... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:30:36 </td>
   <td style="text-align:left;"> Most people don’t have a love or hate for letters of the alphabet but the bears truly are disgusted by the letter V 
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:29:55 </td>
   <td style="text-align:left;"> $SPY Jesus Christ those calls printed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:29:54 </td>
   <td style="text-align:left;"> $SPY back to were we started </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:29:18 </td>
   <td style="text-align:left;"> latex6cd94556369ec76bb56498480535c829$hole!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:29:12 </td>
   <td style="text-align:left;"> $SPY its over Georgia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:28:59 </td>
   <td style="text-align:left;"> $SPY Nancy ??? When?

https://youtu.be/cRFe0tLcOPQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:28:41 </td>
   <td style="text-align:left;"> $SPY  damn this facts. I think the market is in for a rude awakening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:27:57 </td>
   <td style="text-align:left;"> $SPY They can cure inflation by crashing bitcoins to their intrinsic value of zero.  It’s the new beanie babies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:27:57 </td>
   <td style="text-align:left;"> $SPY Georgia or Bama </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:26:58 </td>
   <td style="text-align:left;"> $SPY $QQQ JPOW message tomorrow to all bulls...Start 👇👇👇👇
Idiots that don&amp;#39;t understand the market 🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:26:56 </td>
   <td style="text-align:left;"> $SPY you really think Nancy would buy fresh calls if jpow was going to tank the market?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:26:46 </td>
   <td style="text-align:left;"> $SPY ST weeklies gamma is the true source of my strength…if you want to be rid of me- stop gambling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:26:03 </td>
   <td style="text-align:left;"> $SPY Oracle at Delphi giving out cheap spy plays. Anyone want to take the trip with me ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:25:41 </td>
   <td style="text-align:left;"> $SPY futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:25:06 </td>
   <td style="text-align:left;"> $SPY 🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:25:04 </td>
   <td style="text-align:left;"> $SPY futures mean nothing 99% of time until 3am. Just pajama traders trying to steal from each other. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:24:16 </td>
   <td style="text-align:left;"> $SPY Powell is gonna get lit up like a Christmas tree tomorrow. Hope he is all stocked up on beta blockers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:24:15 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/cRFe0tLcOPQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:23:26 </td>
   <td style="text-align:left;"> $SPY  oh and I held on to the 472 C long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:23:15 </td>
   <td style="text-align:left;"> $SPY Funny listening to people, futures going there way, they all for &amp;#39;em.

When not, always an excuse and a sentiment squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:23:14 </td>
   <td style="text-align:left;"> $SPY prob should not have sold my 457 Feb call EOD 

But you never know

Looking to enter again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:23:01 </td>
   <td style="text-align:left;"> $SPY  These are the conversations that I love to have here 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:22:18 </td>
   <td style="text-align:left;"> $SPY jan 21 471 calls. I will be itm tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:22:17 </td>
   <td style="text-align:left;"> $SPY brady rule </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:22:11 </td>
   <td style="text-align:left;"> $SPY fuck ya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:22:02 </td>
   <td style="text-align:left;"> $SPY 12/3 … enough said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:21:36 </td>
   <td style="text-align:left;"> $SPY What if I told you that I could pick a mean reversion within 60 days of the b swan event, tell you which individual security to get into when it happened and could still crack good jokes along the way…
Would you pay? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:21:15 </td>
   <td style="text-align:left;"> $SPY Anyone else expecting 7.4% inflation Wednesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:20:52 </td>
   <td style="text-align:left;"> $SPY futures holding strong against a whole lot of selling earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:20:22 </td>
   <td style="text-align:left;"> $SPY The old days...

https://www.youtube.com/watch?v=UGGEfl8GzK8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:20:06 </td>
   <td style="text-align:left;"> $SPY gosh i want 470 something tomorrow id be hype </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:19:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Oil is headed to over $120, no way this hot jobs, inflationary atmosphere keeps it down. Goldman Sachs backs me, they are pretty hood buttrrss, no, #1 investment bank. 

A lot getting things delivered , as as &amp;#39;cron&amp;#39; is a thang, so will oil as transportation companies using a lot of oil.  
Consumer too because they are out working, commuting + a lot of food delivery jobs requiring much gas , $DASH $UBER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:19:37 </td>
   <td style="text-align:left;"> $SPY 
Take that bch, bama lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:19:30 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:19:26 </td>
   <td style="text-align:left;"> $SPY bull trap???…sub 460 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:19:04 </td>
   <td style="text-align:left;"> $SPY o man, if es breaks this resistance overnight, see yall at 471 tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:18:54 </td>
   <td style="text-align:left;"> $SPY when in doubt, buy imaginary money $BTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:18:17 </td>
   <td style="text-align:left;"> $SPY I hate lake effect snow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:18:09 </td>
   <td style="text-align:left;"> $SPY if you bought puts on Friday you’re smart. If you bought puts today you’re dumb. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:18:01 </td>
   <td style="text-align:left;"> $SPY $VXX CONTANGO A GO GO  ✔️👌👍👍🤑
http://vixcentral.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:54 </td>
   <td style="text-align:left;"> $SPY Global Warming is…? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:47 </td>
   <td style="text-align:left;"> $SPY god brice young is so inspirational </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:43 </td>
   <td style="text-align:left;"> $SPY can you imagine being this woke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:33 </td>
   <td style="text-align:left;"> $SPY all jokes aside. LETS GO BAMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:33 </td>
   <td style="text-align:left;"> $SPY last night futures were forest green and I woke up to period blood futures lol everyone relax and put some college football on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:14 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Let us continue our honest examination of events, without which we will be hopelessly lost. Success can and shall be found in the intimate tying of decisions. Whose beginnings and ends inevitably converge to form purposeful intent and in time measurable results. 

Though such confidence in the espousals of the prediction of future states can contain within them flickering moments of clarity, one would be foolish to base such high confidence in the nearly limitless predictions possible of future outcomes. Whose randomness possesses the truest expression of beauty found in the unknown nature of future states. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:08 </td>
   <td style="text-align:left;"> $SPY not expecting the FED to be dovish. But at this point there’s a much better chance of a surprise to the upside as opposed to the downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:17:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Understand, with inflation we are talking domestic purchasing power.   The dollar itself has been and continues to gain strength.   
 
Purchasing power is what we are talking about, lol.  Money needs to head INTO the market to attempt to preserve said power. 
 
There is no lacking global confidence in the USD.  Anyone following will confirm it is the opposite. 
 
Rate hikes will bring in MORE global money into our markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:59 </td>
   <td style="text-align:left;"> $SPY red futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:43 </td>
   <td style="text-align:left;"> $SPY my god futures mean nothing until the overnight drift period when the big boys actually start moving market. Until then it’s low volume and illiquid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:35 </td>
   <td style="text-align:left;"> $SPY send Seal Team Six to assassinate Putin. Him invading Ukraine suddenly is the black swan event IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:31 </td>
   <td style="text-align:left;"> $SPY 
Fk bama
Go dawgs make me 6gs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:30 </td>
   <td style="text-align:left;"> $SPY Ask yourself - why we came up short of the gap - unfinished business </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:21 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/zs5G5qPudzo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:14 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:13 </td>
   <td style="text-align:left;"> $SPY Powell must feel like an Egyptian god I would fuck with markets if I were him. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:07 </td>
   <td style="text-align:left;"> $SPY  Am I loosing  it orrrrrr.....Are we making plays 🏦💭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:16:03 </td>
   <td style="text-align:left;"> $SPY is tomorrow volatile or </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:15:51 </td>
   <td style="text-align:left;"> $QQQ $SPY  
No worries.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:15:49 </td>
   <td style="text-align:left;"> $SPY we need lockdowns plus military in the streets enforcing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:15:39 </td>
   <td style="text-align:left;"> $SPY us trade deficit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:15:18 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m bearish on Tuesday close though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:15:16 </td>
   <td style="text-align:left;"> $SPY It’s a certainty. Russia is going to take the vast majority of Ukraine with overwhelming force. And it will happen very soon. The entire world is going to be shocked when it happens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:15:04 </td>
   <td style="text-align:left;"> $SPY y no ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:54 </td>
   <td style="text-align:left;"> $SPY textbook head fake day, going back down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:39 </td>
   <td style="text-align:left;"> $QQQ If Chartmill is positive we Know it&amp;#39;s going back Downnnn Tx Cm.. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:33 </td>
   <td style="text-align:left;"> $SPY So Apple had double the outflow compared to inflow.. yet ended up positive. Are we working with supply and demand or somthing new? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:31 </td>
   <td style="text-align:left;"> $SPY Article saying people are running out of money. It’s printing soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:19 </td>
   <td style="text-align:left;"> $SPY I believe this will rally again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:14 </td>
   <td style="text-align:left;"> $SPY the results are in.  You get laid 3x times easier if you&amp;#39;re vax&amp;#39;d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:14:12 </td>
   <td style="text-align:left;"> $SPY $SPX  the Greasy move down to flat cloud equilibirum next as its riding red line 9 day candle average. today retested white 26 candle average line resistance..  the $5 Billion in Darkpool  at 466..  the selling getting bigger on each pop.. caution! Hot!  The 10 Piece Bot Bucket of selling 
 
the buy program back to ichimoku 26 day candle average resistance (known as kijusen in ichimoku  was brazen as JPM Ceo spoke, (..  that is where over $5 $Billion in Darkpool selling @ $466 was . classic unload..  Caution below 466.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:41 </td>
   <td style="text-align:left;"> $SPY 🤡😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:40 </td>
   <td style="text-align:left;"> $SPY  just tell me if I was speaking facts or not, who else takes care of you this way on trade by trade basis....🥂💭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … ⚠️ tomorrow live on CNBC another perma bull billionaire paul Tudor boosting pre markets 📈✅ ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:23 </td>
   <td style="text-align:left;"> $SPY I will pull for Bama because that will piss off the most people! Roll Tide! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:18 </td>
   <td style="text-align:left;"> $SPY I occasionally realize that I am not really an ST mascot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:16 </td>
   <td style="text-align:left;"> FS $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:09 </td>
   <td style="text-align:left;"> $SPY you can thank Jamie dimon for the pump today. Sadly tomorrow we resume the sell program </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:07 </td>
   <td style="text-align:left;"> $SPY after seeing futures last night, are we really going to play the game where we pretend they matter again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:13:06 </td>
   <td style="text-align:left;"> Today $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:12:14 </td>
   <td style="text-align:left;"> $SPY i would like to knw who felt the need to buy all the fckn twinkies.  this really in your prepper guide? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:12:12 </td>
   <td style="text-align:left;"> $SPY In the recent reporting quarter: 2 institutions initiated a position, while 1 completely liquidated https://insider-analysis.com/search_whales.php?ticker=TABLE_SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:11:51 </td>
   <td style="text-align:left;"> $SPY people saying inflation bad, Cathie saying deflation bad. Who the hell do we believe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:11:30 </td>
   <td style="text-align:left;"> $SPY doing some light research </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:11:28 </td>
   <td style="text-align:left;"> $SPY  I do accept pennies for my thoughts! 💭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:56 </td>
   <td style="text-align:left;"> $SPY lol another 9$ tommorrow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:47 </td>
   <td style="text-align:left;"> $SPY Cheezits got his account permanently suspended for posting about the virus outbreak in Wuhan China... on stocktwits.

That&amp;#39;s a fact. It happened 3 times in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:47 </td>
   <td style="text-align:left;"> $SPY we good for tomm?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:40 </td>
   <td style="text-align:left;"> $SPY  🏦🚨Taking some of these intra day ideas?👀 buddy of mine made just under 2k by 4pm. Remember to show love on my timeline so I can keep working on these🧑🏼‍🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:40 </td>
   <td style="text-align:left;"> $SPY 
Georgia -2.5 pts 
7gs for 6gs
Atlanta stole the presidency
Braves won, Tonight dawgs too
$ too ez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:18 </td>
   <td style="text-align:left;"> $SPY Ripping hard AF. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:10:16 </td>
   <td style="text-align:left;"> $SPY $MRNA $PFE $JNJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:09:51 </td>
   <td style="text-align:left;"> $SPY What exactly happens tomorrow at 10am with Powell? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:09:47 </td>
   <td style="text-align:left;"> $SPY futures look pretty flat just like lastnight 🤭🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:09:44 </td>
   <td style="text-align:left;"> $SPY poor doves 🤣🩸☠️
 https://www.reddit.com/r/Epic_Economics/comments/s105aq/fed_hawks_are_hungry/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:09:41 </td>
   <td style="text-align:left;"> $SPY tomorrow red to green . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:08:28 </td>
   <td style="text-align:left;"> $SPY why does North Korea even bother? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:07:38 </td>
   <td style="text-align:left;"> $SPY pop and drop at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:07:27 </td>
   <td style="text-align:left;"> $SPY Even the futures can&amp;#39;t make up its mind... up and down up and down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:06:51 </td>
   <td style="text-align:left;"> $SPY All the people who say &amp;quot;mark it&amp;quot;  - you should guarantee each like on that post a dollar if you&amp;#39;re wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:05:47 </td>
   <td style="text-align:left;"> $SPY inflation is transitory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:05:38 </td>
   <td style="text-align:left;"> $SPY What a gift this was today :) I&amp;#39;m glad I was paying attention! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:05:35 </td>
   <td style="text-align:left;"> $SPY futures looking pretty weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:05:30 </td>
   <td style="text-align:left;"> $SPY jpow is going to start adding printers soon brrrrbbrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:05:27 </td>
   <td style="text-align:left;"> $SPY Cheezits was posting in early 2020 that he was monitoring satellite imagery over China..  light emissions, power plant emissions...

Do any of you remember his posts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:05:19 </td>
   <td style="text-align:left;"> $SPY 
Futures green right at the open 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:04:11 </td>
   <td style="text-align:left;"> $SPY although Pelosi gets all the media coverage for her uncanny stock picking, lots of politicians used their insider info to crush the market last year, with Austin Scott from Georgia leading the pack, rumor has it he learned to trade cattle futures from the legend herself Hillary Clinton </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:03:57 </td>
   <td style="text-align:left;"> $SPY word of the decade, “transitory” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:03:14 </td>
   <td style="text-align:left;"> $SPY Cheezits posted that he was monitoring satellite imagery in Feb 2020 of China. Anyone remember that guy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:02:45 </td>
   <td style="text-align:left;"> $SPY $UBER $TSLA time to get piss drunk and watch futures half the night cheering on my Uber calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:02:07 </td>
   <td style="text-align:left;"> $SPY 

Buy 
The 
Fucking
Dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:01:55 </td>
   <td style="text-align:left;"> $SPY god devonta was such a 🐐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:01:40 </td>
   <td style="text-align:left;"> $SPY Are you a permabull?
Do you think Biden is stupid?
If you answered yes to both questions you are eligible to join Team Muppets 
Muppet up your avatar and show your support!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:01:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT Fed chair Powell Senate confirmation hearing tomorrow.  There’s no concern over re-confirmation, it’s what Powell says for questions on economy and inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:01:16 </td>
   <td style="text-align:left;"> $SPY I’m going to make SPY my bitch this year! Already crushing it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:00:54 </td>
   <td style="text-align:left;"> $SPY $QQQ You cucks are scared of a little inflation lol! Interest rates are still low even if they did 20 rate hikes 😂😂 $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:00:51 </td>
   <td style="text-align:left;"> $TSLA $SPY $V $amd $LCID   huge100- 200 percent gainer today. Called in the live session and recorded on the spreadsheet. Hit the follow and join for my option entries , exits and stops! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:00:41 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m going all in on Girl Scout cookies this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:00:40 </td>
   <td style="text-align:left;"> $BZFD BUZZFEED IS GETTING SHORTED TO THE GROUND AS IT SHOULD BE. PRODUCING SHITTY CLICK BAITY ARTICLES THAT STIR UP HATE AND DIVISION HOLDS NO PLACE ON WALL ST. THE FACT BUZZFEED IS EVEN PUBLIC BOGGLES ME. WHO LET THESE GUYS ON THE NADDAQ? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 09:00:01 </td>
   <td style="text-align:left;"> $SPY after hours closed ding dongs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:59:55 </td>
   <td style="text-align:left;"> $SPY .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:59:54 </td>
   <td style="text-align:left;"> $SPY Cheezits was right January and February 2020, anyone remember him? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:59:41 </td>
   <td style="text-align:left;"> $SPY Last thing of all these &amp;#39;I&amp;#39; thoughts: FED will unwind balance sheet very soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:59:38 </td>
   <td style="text-align:left;"> $SPY my ex so mad that she ain’t around me
My ex soooo mad, made a mistake about me
I don’t even drink but everyday I drink about u
But,nowadays I don’t give  a F about you 
Now I got a baddie sittin up in my coupe
MArried to the money MF “I DO”

Last one 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:59:05 </td>
   <td style="text-align:left;"> $SPY Not in on this trade but been charted two weeks back still holding, shark move . Traders trapped ready for next move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:58:47 </td>
   <td style="text-align:left;"> $SPY  
 
You bulls do realize that you&amp;#39;re currently fighting to reclaim what you first got back in early November, and have since lost 5 times, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:58:28 </td>
   <td style="text-align:left;"> $SPY you PJ boys got work to do tonight.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:58:14 </td>
   <td style="text-align:left;"> $QQQ $SPY  If we can get this to a full correction this week, 2022 will outperform 2021. 
 
As it sits now, we at least got something and are going to have minimum 15% 2022 gains on the major indexes for 2022. 
 
If you are selling, you are getting played. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:58:07 </td>
   <td style="text-align:left;"> $SPY $PFE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:57:54 </td>
   <td style="text-align:left;"> $SPY you morons dont know this is about the agenda . You all a bunch of sardines here. They gonna lure you all in and buy at these ridiculous prices showing little treats that the market only goes up and whammo taketh away and you will own nothing and be happy about it too. Not sure why you would be happy about it though? Oh yea I&amp;#39;m like 90 percent cash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:57:45 </td>
   <td style="text-align:left;"> $SPY retail bulls are clueless about what&amp;#39;s happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:57:43 </td>
   <td style="text-align:left;"> $SPY Imagine not being long? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:57:26 </td>
   <td style="text-align:left;"> $QQQ $SPY come morons keep pumping higher...you think today&amp;#39;s drop was a fluke? that was just a glimpse at what&amp;#39;s to come ;)))
Never seen such idiots....they play the market like playing darts blindly lollll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:57:00 </td>
   <td style="text-align:left;"> $SPY was working and didn’t get to buy calls at 458 :(((( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:56:45 </td>
   <td style="text-align:left;"> $SPY If someone asks you for a dollar, ask if you can have one too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:56:35 </td>
   <td style="text-align:left;"> $SPY Levels to keep in mind: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:56:33 </td>
   <td style="text-align:left;"> $SPY bears switching to bulls tomorrow like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:56:11 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:56:07 </td>
   <td style="text-align:left;"> $SPY Corso picked Georgia. That settles it, Bama has it in the bag. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:55:54 </td>
   <td style="text-align:left;"> $SPY CALLS PAID THE BILLS TODAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:55:44 </td>
   <td style="text-align:left;"> $SPY If you didn&amp;#39;t cash out on your short position today, you might feel some discomfort the rest of the week. Tech rotation might be back after today. 
After years of trading, these rotations move rapidly. One day the news says value, that jumps 10% in a week (like financials and commodities), the next week they cash out and push into another category. Growth or small caps might be the next week or two. Recognize that this is continually happening and it&amp;#39;s very hard to read markets week to week. You can be fundamentally and principally right, but these markets don&amp;#39;t operate on that logic. 
Just trade fast while these markets are going through this continued bipolar turmoil. Book profits fast, wait.. watch for the next setup. Could be an overbought sector, or an oversold sector. 
Gotta be nimble in 2023. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:55:37 </td>
   <td style="text-align:left;"> $EL nice pull back on this #HighFlyer 325 gap fill $SPY $QQQ sell lower 299 gap fill then 282 area support Daily time frame </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:55:35 </td>
   <td style="text-align:left;"> $SPY Do not buy at top. Buy at bottom that is good strategy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:55:25 </td>
   <td style="text-align:left;"> $SPY  $QQQ So last night mostly bear were so excited ; now bulls all over and excited after middle of the day big recover :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:54:45 </td>
   <td style="text-align:left;"> $SPY 480. $AAPL 190🥂🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:54:18 </td>
   <td style="text-align:left;"> $SPY Max it can go 469 and drops to 441 as shown here: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:54:17 </td>
   <td style="text-align:left;"> $SPY bitches really trippin, if you looking for a check go get it
Bitch, IM THE WRONG N**** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:54:15 </td>
   <td style="text-align:left;"> $SPY u guys dont know this but on the other side of da planet both thailand and indo futes rippin 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:54:08 </td>
   <td style="text-align:left;"> $SPY im so ready!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:53:44 </td>
   <td style="text-align:left;"> $SPY                       BAMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:53:15 </td>
   <td style="text-align:left;"> $SPY BRANDON RULES!! 🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:53:08 </td>
   <td style="text-align:left;"> $SPY Powell is not here to ruin the markets, relax and btfd 
https://www.bloomberg.com/news/articles/2022-01-10/powell-says-fed-to-ensure-inflation-doesn-t-take-root-in-economy?srnd=premium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:53:00 </td>
   <td style="text-align:left;"> $SPY ok ALGOS DONT FORGET TO FOLLOW NIKKEI MOVES ON THE DOWN SIDE TOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:52:59 </td>
   <td style="text-align:left;"> $SPY at another shoulder spot here in ES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:52:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Dark Pool Sentiment: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:52:26 </td>
   <td style="text-align:left;"> $SPY you know the levels already!! Support at 464, Buyers at 467 and Resistance at 470… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:51:48 </td>
   <td style="text-align:left;"> $ARKK latex9db0ce3ef86e1334b17583cd1927bf04spy
$nflx

Lynk in bayo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:51:35 </td>
   <td style="text-align:left;"> $SPY dip buyers got caught. Bad habits. 
 https://www.tradingview.com/chart/NAS100/p0QW0Xkm-NAS100-Fallout-Buyer-BEWARE-Growth-at-all-Costs-is-No-More/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:51:13 </td>
   <td style="text-align:left;"> $SPY no can move the market like that except the big guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:51:03 </td>
   <td style="text-align:left;"> $SPY Georgia, please put up a fight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:50:53 </td>
   <td style="text-align:left;"> $SPY  &amp;quot;We were firm, however, on pushing back on security proposals that are simply nonstarters for the United States,&amp;quot; Sherman said, adding &amp;quot;we will not allow anyone&amp;quot; to shut NATO’s &amp;quot;open-door policy&amp;quot; that extends to countries seeking entry in the alliance.

She said Washington &amp;quot;will not forgo bilateral cooperation with sovereign states that wish to work with the United States. And, we will not make decisions about Ukraine without Ukraine, about Europe without Europe or about NATO without NATO.&amp;quot;

Additionally Sherman said, &amp;quot;If Russia stays at the table and takes concrete steps to deescalate tensions, we believe we can achieve progress.&amp;quot; She also reaffirmed the &amp;quot;costs&amp;quot; of any potential Russian offensive into Ukraine: &amp;quot;Those costs will include financial sanctions, and it&amp;#39;s been reported those sanctions will include key financial institutions, export controls that target industries; enhancements of NATO force posture on ally territory; and increased security assistance to Ukraine.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:50:37 </td>
   <td style="text-align:left;"> $SPY so puts Or calls tomorrow for a 6x play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:50:27 </td>
   <td style="text-align:left;"> $SPY stock analysis 

https://youtu.be/Ih08JBtuG-s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:50:16 </td>
   <td style="text-align:left;"> $SPY Green open...we&amp;#39;ll see what happens at 470 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:50:11 </td>
   <td style="text-align:left;"> $SPY those algos having fun again lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:50:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXX Overstepping inflation target of 2% is all fine and dandy and actually OK, but to then say &amp;quot;inflation not transitory,&amp;quot; it means that it&amp;#39;s getting out of control.

Honestly, FED telling us FED FUNDS RATE of 2% hammered home for 3 years as where we want to be and being at 6.8%, that is VERY scary. 

Even scarier?

I think saying a overstep target of 2.25% is good or 2.5% but it shows both incompetency as well as uncertainty when they throw the range to 3% .
*Do own DD
K? 👍🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:49:59 </td>
   <td style="text-align:left;"> $QQQ $SPY Hey monkey&amp;#39;s if $BTC.X breaks below 39k tonight and remains there and lower.... this will spell DISASTER FOR THE MARKETS TOMORROW!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:49:09 </td>
   <td style="text-align:left;"> $SPY betting on Georgia is like buying SPY puts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:49:03 </td>
   <td style="text-align:left;"> $QQQ $SPY $JNK $SPXL $DIA Another fancy hammer for the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:48:26 </td>
   <td style="text-align:left;"> $SPY j.pow gonna sing you a sweet love song tm. BbrRrR printer bRrR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:48:15 </td>
   <td style="text-align:left;"> $SPY Bottom not In. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:48:09 </td>
   <td style="text-align:left;"> $SPY lfg dawgs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:48:05 </td>
   <td style="text-align:left;"> $JNK $SPY latex9fe747f7dadc17de627f1875b5c6e8c3BMY 56c 60%
@MommasOptions 
$AAPL 177.5c 90% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:50 </td>
   <td style="text-align:left;"> $SPY if it hit ATH again this month, I would not be surprised. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:38 </td>
   <td style="text-align:left;"> $SPY come on its gonna crash, no adults to take charge. Horrible whats gonna happen in the next month. Hello ANYBODY AWAKE. Take care of your love ones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:30 </td>
   <td style="text-align:left;"> They just CCAANNTT take this market ddoooowwnnnnnn 
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:20 </td>
   <td style="text-align:left;"> $QQQ Nothing but NEWBIES posting on this board and we all know how smart that is? lol $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:11 </td>
   <td style="text-align:left;"> $SPY rinse and repeat.  If only. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:09 </td>
   <td style="text-align:left;"> $SPY bears kinda quiet tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:07 </td>
   <td style="text-align:left;"> $SPY bull bear bull bear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:47:00 </td>
   <td style="text-align:left;"> $SPY is currently trading in the upper part of its 52 week range, which is inline with the index. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:46:56 </td>
   <td style="text-align:left;"> $SPY Jereome Powell&amp;#39;s prepared testimonial for his renomination hearing tomorrow. Durrrr. https://www.federalreserve.gov/newsevents/testimony/powell20220111a.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:46:55 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m ok with being tiny.
https://www.youtube.com/watch?v=rRqY0ndUqMg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:46:53 </td>
   <td style="text-align:left;"> $QQQ $SPY Facts 👇🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:46:52 </td>
   <td style="text-align:left;"> $SPY just finished return to normal phase </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:46:43 </td>
   <td style="text-align:left;"> $SPY I really don’t understand how everyone is so bullish right now? Watch this shit be down 2.5% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-11 08:46:10 </td>
   <td style="text-align:left;"> $SPY this has to be the greatest monday ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:58:27 </td>
   <td style="text-align:left;"> $SPY $QQQ The FED is now expected to hike rates 4 times due to high inflation but if inflation begins to ease later this year then the FED could reduce the number of rate hikes to something like 3 or even 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:56:49 </td>
   <td style="text-align:left;"> $NQ_F: If we have a follow through day tomo, this will have been a beautiful bear trap. Got the hammer right back up to support. Again, tomorrow is important. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:55:57 </td>
   <td style="text-align:left;"> $QQQ bounce was nothing crazy advanced. Simple uptrend, AVWAP and GP support confluence.  
 
Don&amp;#39;t over complicate trading or TA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:55:14 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $DJIA … 

Nasdaq January seasonal performance average 👇🏻⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:54:34 </td>
   <td style="text-align:left;"> $SPY $QQQ I see how this plays out 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:53:03 </td>
   <td style="text-align:left;"> Alright team- here&amp;#39;s the update, $QQQ not only captured the 375 level but also back at the support, making it a triple bottom false breakdown. AND the false breakdown of the TL going back to 2020. This was all a great achievement IMO.  
Heading to $SPY which showed me early signs of reversal also closed within the rising TL going back to Oct 2021. See how the price brokedown while RSI respecting TL, that was a good sign and then capturing all the imp. levels was just cherry on the cake. Overall, an hectic day with a shit ton of hammers. Plan going into next few days- false breakdowns are bear traps and can usually V up or come test the lows again to trap more bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:52:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Sick day where if you traded 0dte’s all the way down then nailed the calls all the way up you could turn $1000 into $1,000,000. They don’t come around often but cool to see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:50:40 </td>
   <td style="text-align:left;"> $QQQ that rally was not just a twist bounce. That was vavavoommmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:48:41 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:47:57 </td>
   <td style="text-align:left;"> $QQQ should’ve got some calls today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:46:11 </td>
   <td style="text-align:left;"> $QQQ my team of analysts and I have upgraded this stock from SELL to OVERWEIGHT and increased the target price from $300 to $550 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:45:02 </td>
   <td style="text-align:left;"> $BTC.X  and $QQQ update.

https://youtu.be/E4_9cglYtZk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:44:11 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $AMD The 10 year Treasury yield seems to cap at 1.8 and have rotated down 0.51%. Bank stocks have rallied for a while. Time for big techs to shine ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:41:22 </td>
   <td style="text-align:left;"> $QQQ squeeze tm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:41:10 </td>
   <td style="text-align:left;"> $QQQ I was expecting $350ish to be bottom back to October lows. Looks like it’s holding support. Tomorrow will be the ultimate test and direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:40:18 </td>
   <td style="text-align:left;"> $SPY $QQQ tomorrow we slaughter the dogshit bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:39:34 </td>
   <td style="text-align:left;"> 15600 the new Nasdaq floor support level $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:39:30 </td>
   <td style="text-align:left;"> $HIMX   $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:39:01 </td>
   <td style="text-align:left;"> $SPY How will the referees call the game when they are getting paid by both teams? $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:38:09 </td>
   <td style="text-align:left;"> $QQQ what did Nancy buy today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:36:43 </td>
   <td style="text-align:left;"> New Analysis: Bears tried to break the market and they were broken instead. Plus, is #Bitcoin so bad it&amp;#39;s good? https://cracked.market/2022/01/bears-tried-to-break-the-market-and-they-were-broken-instead-plus-is-bitcoin-so-bad-its-good/ $SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:36:25 </td>
   <td style="text-align:left;"> $QQQ needs a strong push after todays reversal. Need to break $383.26 on hourly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:36:22 </td>
   <td style="text-align:left;"> $TSRI stock of the day tomorrow… $qqq $spy $oef </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:35:44 </td>
   <td style="text-align:left;"> $QQQ While FinTwit and ST panics every couple months, I have always said I&amp;#39;ll get out of the way if/when this trendline fails and we close below it. In the meantime, I&amp;#39;ve bought every time we tangle with it, including today.

The trend is your friend. And if the trend changes, reevaluate. For the time being, the trend has not changed. Make a plan and stick to it!

$SQQQ $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:35:08 </td>
   <td style="text-align:left;"> $QQQ Does anyone know when Jerome Powell is speaking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:34:37 </td>
   <td style="text-align:left;"> $QQQ $spy Dark pool prints don&amp;#39;t lie 
Going to the shit house 🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:34:06 </td>
   <td style="text-align:left;"> $SPY  $QQQ predictions  - Besides Alabama winning tonight, QQQ will open in the red tomorrow and close green barely then Wed/Thurs mother Rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:32:36 </td>
   <td style="text-align:left;"> Called it last night on my stream. 

Word for word said $QQQ will break the triple bottom, then fake out before a breakout to the upside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:30:53 </td>
   <td style="text-align:left;"> $QQQ Even kyle rittenhouse pulled the trigger on this dip. Bears are fuk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:29:57 </td>
   <td style="text-align:left;"> $QQQ options profit over the last 2 weeks. Tomorrow we’re watching triple Q, might be a huge play here. Would be up close to 1.5k if I didn’t throw an option that dropped me -600, but recovered nicely today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:26:58 </td>
   <td style="text-align:left;"> $SPY $QQQ JPOW message tomorrow to all bulls...Start 👇👇👇👇
Idiots that don&amp;#39;t understand the market 🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:26:11 </td>
   <td style="text-align:left;"> $QQQ three strike rule </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:26:04 </td>
   <td style="text-align:left;"> $QQQ 
If you got greedy and didn’t sell your puts when we were down by 8-10 points then RIP 🪦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:26:01 </td>
   <td style="text-align:left;"> $QQQ lot of triggered bears who bought puts right before the reversal today 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:24:48 </td>
   <td style="text-align:left;"> $QQQ $NDX $XLK … 🪦 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:23:47 </td>
   <td style="text-align:left;"> $QQQ  Looking for another drop tomorrow. Tomorrow  QQQ close in the red.  $367.00 PUTs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:19:45 </td>
   <td style="text-align:left;"> $SPY $QQQ Oil is headed to over $120, no way this hot jobs, inflationary atmosphere keeps it down. Goldman Sachs backs me, they are pretty hood buttrrss, no, #1 investment bank. 

A lot getting things delivered , as as &amp;#39;cron&amp;#39; is a thang, so will oil as transportation companies using a lot of oil.  
Consumer too because they are out working, commuting + a lot of food delivery jobs requiring much gas , $DASH $UBER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:19:30 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:17:15 </td>
   <td style="text-align:left;"> $QQQ https://www.politico.com/news/2022/01/10/fed-chief-powell-economy-challenge-526783 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:17:14 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Let us continue our honest examination of events, without which we will be hopelessly lost. Success can and shall be found in the intimate tying of decisions. Whose beginnings and ends inevitably converge to form purposeful intent and in time measurable results. 

Though such confidence in the espousals of the prediction of future states can contain within them flickering moments of clarity, one would be foolish to base such high confidence in the nearly limitless predictions possible of future outcomes. Whose randomness possesses the truest expression of beauty found in the unknown nature of future states. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:17:12 </td>
   <td style="text-align:left;"> $QQQ red futures 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:17:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Understand, with inflation we are talking domestic purchasing power.   The dollar itself has been and continues to gain strength.   
 
Purchasing power is what we are talking about, lol.  Money needs to head INTO the market to attempt to preserve said power. 
 
There is no lacking global confidence in the USD.  Anyone following will confirm it is the opposite. 
 
Rate hikes will bring in MORE global money into our markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:16:38 </td>
   <td style="text-align:left;"> $QQQ Up 2-3% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:15:51 </td>
   <td style="text-align:left;"> $QQQ $SPY  
No worries.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:15:44 </td>
   <td style="text-align:left;"> $QQQ I could see this dropping 20% before rising 10%, just being practical. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:14:39 </td>
   <td style="text-align:left;"> $QQQ If Chartmill is positive we Know it&amp;#39;s going back Downnnn Tx Cm.. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:14:33 </td>
   <td style="text-align:left;"> Must have been wild af trading the Q’s during this window $qqq https://twitter.com/sjd10304/status/1480647031521640448?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:13:39 </td>
   <td style="text-align:left;"> $TSLA $QQQ dont know but I have a feeling these two will tank tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:13:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … ⚠️ tomorrow live on CNBC another perma bull billionaire paul Tudor boosting pre markets 📈✅ ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:12:32 </td>
   <td style="text-align:left;"> $QQQ tomorrow he gonna give it a final spin! Encore! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:12:07 </td>
   <td style="text-align:left;"> $QQQ Bring it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:12:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $QQQ did better than 75% of all other stocks. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:11:53 </td>
   <td style="text-align:left;"> An interestingly bullish thot $qqq https://twitter.com/patrickc/status/1480647701221896195?s=12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:10:33 </td>
   <td style="text-align:left;"> $QQQ that’s a wrap
 https://www.reddit.com/r/Epic_Economics/comments/s105aq/fed_hawks_are_hungry/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:10:12 </td>
   <td style="text-align:left;"> $QQQ closure was very bullish, bit salty cuz im a put holder in $ZM. powell tmr will def be interesting. so far hes been dumping rather than pumping when he speaks. today someone bought and i feel like based off the new market mentality its highly likely to have been retail. overall nasdaq and other tech did break support, a hammer back above support would spell disaster for any short term bear. structure changes on short term so it&amp;#39;d be foolish to deny the bullish sentiment we saw today. granted not much matters since powell speaks tomorrow unless hes neutral. but overall i def think the markets have changed a bit due to the large influx of retail traders into the scene. i doubt well see large scale crashes unless we see a recession since retail will always be there or at least get manipulated into buying the banks bags </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:09:48 </td>
   <td style="text-align:left;"> $QQQ Basically an intraday V recovery. Really tempted to fade with Powell and his pearls of bearish wisdom coming up tomorrow but I’ll wait to see if the move today has legs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:06:58 </td>
   <td style="text-align:left;"> $PFE https://www.reuters.com/business/healthcare-pharmaceuticals/pfizer-ceo-says-omicron-variant-targeted-vaccine-is-most-likely-outcome-2022-01-10/?taid=61dcd7c5ed344f0001a57f70&amp;amp;utm_campaign=trueAnthem:+Trending+Content&amp;amp;utm_medium=trueAnthem&amp;amp;utm_source=twitter $MRNA $JNJ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:05:29 </td>
   <td style="text-align:left;"> $QQQ $SQQQ $UVXY Dark pool resistance levels: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:01:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT Fed chair Powell Senate confirmation hearing tomorrow.  There’s no concern over re-confirmation, it’s what Powell says for questions on economy and inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 09:00:54 </td>
   <td style="text-align:left;"> $SPY $QQQ You cucks are scared of a little inflation lol! Interest rates are still low even if they did 20 rate hikes 😂😂 $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:58:14 </td>
   <td style="text-align:left;"> $QQQ $SPY  If we can get this to a full correction this week, 2022 will outperform 2021. 
 
As it sits now, we at least got something and are going to have minimum 15% 2022 gains on the major indexes for 2022. 
 
If you are selling, you are getting played. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:57:26 </td>
   <td style="text-align:left;"> $QQQ $SPY come morons keep pumping higher...you think today&amp;#39;s drop was a fluke? that was just a glimpse at what&amp;#39;s to come ;)))
Never seen such idiots....they play the market like playing darts blindly lollll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:55:37 </td>
   <td style="text-align:left;"> $EL nice pull back on this #HighFlyer 325 gap fill $SPY $QQQ sell lower 299 gap fill then 282 area support Daily time frame </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:55:25 </td>
   <td style="text-align:left;"> $SPY  $QQQ So last night mostly bear were so excited ; now bulls all over and excited after middle of the day big recover :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:55:22 </td>
   <td style="text-align:left;"> $QQQ  bears thought the buy the dip era was suddenly over? Lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:54:25 </td>
   <td style="text-align:left;"> $QQQ risk off. Terrible
 https://www.reddit.com/r/Epic_Economics/comments/s0ztj4/dip_buyers_got_caught_nas100_to_continue_selloff/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:53:04 </td>
   <td style="text-align:left;"> Today $QQQ shows HOLD signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/QQQ?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:52:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Dark Pool Sentiment: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:50:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXX Overstepping inflation target of 2% is all fine and dandy and actually OK, but to then say &amp;quot;inflation not transitory,&amp;quot; it means that it&amp;#39;s getting out of control.

Honestly, FED telling us FED FUNDS RATE of 2% hammered home for 3 years as where we want to be and being at 6.8%, that is VERY scary. 

Even scarier?

I think saying a overstep target of 2.25% is good or 2.5% but it shows both incompetency as well as uncertainty when they throw the range to 3% .
*Do own DD
K? 👍🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:49:59 </td>
   <td style="text-align:left;"> $QQQ $SPY Hey monkey&amp;#39;s if $BTC.X breaks below 39k tonight and remains there and lower.... this will spell DISASTER FOR THE MARKETS TOMORROW!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:49:03 </td>
   <td style="text-align:left;"> $QQQ $SPY $JNK $SPXL $DIA Another fancy hammer for the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:48:05 </td>
   <td style="text-align:left;"> $JNK $SPY $DIA $QQQ $SPXL Really nice hammer for $JNK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:47:20 </td>
   <td style="text-align:left;"> $QQQ Nothing but NEWBIES posting on this board and we all know how smart that is? lol $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:46:53 </td>
   <td style="text-align:left;"> $QQQ $SPY Facts 👇🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:45:17 </td>
   <td style="text-align:left;"> $QQQ being a bear really tough downside is -100% while upside is infinite 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:43:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $SMH  ⚠️  🟩🔨  ⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:42:28 </td>
   <td style="text-align:left;"> $QQQ you can delay it, you can slow it, it may dip or crash or sell off but it is inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:41:59 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $AAPL $TQQQ 

Apple chart has bearishness written all over it. Easily $160 from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:41:24 </td>
   <td style="text-align:left;"> AMD Stock Price Alert: Buy the Dip Opportunity Is Here - TheStreet $AMD $QQQ  https://www.thestreet.com/investing/buy-the-dip-in-amd-stock-now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:40:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $IWM FUTES SLIPPIN 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:40:03 </td>
   <td style="text-align:left;"> $QQQ So many motherfuxkers are speaking tomorrow. What are they gonna talk about? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:38:26 </td>
   <td style="text-align:left;"> $QQQ slightly oversold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:36:03 </td>
   <td style="text-align:left;"> $SPY In case you Joe wannabe&amp;#39;s didn&amp;#39;t notice even though the spy came back from the lows it still finished Downnnnn! May be even worse Dive tomorrow for this and the $QQQ idiots that think the market never goes down....gl you&amp;#39;re going to need it! $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:33:39 </td>
   <td style="text-align:left;"> $QQQ do ya smell the rebound bear ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:33:33 </td>
   <td style="text-align:left;"> $QQQ $TSLA People looking at futures are just plain stupid. Yesterday futures were super green just to become red in pre-market. Today futures were hella red in pre-market just to end up green for the day. Futures don&amp;#39;t mean sh!t. PT tomorrow $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:33:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AMZN $AAPL Jpow going to say, we pumped too much need to raise rates now!!! 

In other news, a local grocery store Nob Hill is closing a store as employees reported. Parent company Raleys have not answered. More jobs lost....😕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:33:00 </td>
   <td style="text-align:left;"> $SPY $QQQ Right now I would expect a fairly flat to maybe a slight green day tomorrow and then we soar on the lower than expected inflation data on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:32:48 </td>
   <td style="text-align:left;"> $QQQ This is too easy….. Futures red by 10:30 pm est tonight 

Sell any upward moves, were going down hard again tomorrow. Uncle JP will be shitting dove feathers tomorrow 

They need to make up for the lost “transitory” time 

Accelerated tapering done by March
First fed funds fate hike, end of March
Selling of assets off their balance sheet after tapering 
And they still haven’t mentioned increasing the reserves ….. yet

Add grandpa Biden getting his ass kicked by Putin 
COVID keeps on giving 
Inflation will hit 7% this week
CPI will hit 5%
JP’s printing press, broken 🤣
Kids will be learning remotely 
Puts for tomorrow 💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:32:24 </td>
   <td style="text-align:left;"> $QQQ $SPY which is it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:32:02 </td>
   <td style="text-align:left;"> $QQQ years and years of fraud. Made in China zombies 
 https://www.reddit.com/r/Epic_Economics/comments/s0zbaq/futures_crypto_turn_for_the_downside_cash_hunters/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:31:56 </td>
   <td style="text-align:left;"> $QQQ $SPY ready for a big move tomorrow one way or the other. MM wants it flat as always. We&amp;#39;ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:31:52 </td>
   <td style="text-align:left;"> $QQQ so what&amp;#39;s next, Raise rates after Pelosi exits her calls? Or keep the party going? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:31:31 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Papa Powell testifies tomorrow! S&amp;amp;P 500 needs a full 10% drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:31:01 </td>
   <td style="text-align:left;"> $spy $qqq $labu
Tomorrow Powell confirmation, obviously very bullish $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:30:47 </td>
   <td style="text-align:left;"> What a crock of bs Monday was re indices rally post face plant.  Regardless, moving forward ... incoming crash Tuesday  ... 10:00 a.m. ...
Testimony -- Chair Jerome H. Powell ... Watch Live ... Hearing ... Before the Committee on Banking, Housing, and Urban Affairs, U.S. Senate ... https://www.federalreserve.gov/newsevents/calendar.htm  $tsla $f $ccl  $spy $qqq and more 🐻❤😈✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:30:08 </td>
   <td style="text-align:left;"> $SPY $QQQ watch this massive bullish hammer day play off as a sell.. give the bulls a taste of all the technical traps bears have fallen for past 2 years 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:29:07 </td>
   <td style="text-align:left;"> $QQQ retest of ATH’s by end of earning season ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:28:48 </td>
   <td style="text-align:left;"> $SPY total bs back to Zero after all that? I don&amp;#39;t buy it! $QQQ $ARKR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:27:10 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:25:15 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.youtube.com/watch?v=CjhpaUsLddY 
 
Jamie Dimon is very bullish on the US consumers and the US economy overall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:24:48 </td>
   <td style="text-align:left;"> $SPY $QQQ we should be able to get to target goal of zero tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:23:42 </td>
   <td style="text-align:left;"> $QQQ added 3 more at 370. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:21:51 </td>
   <td style="text-align:left;"> $QQQ all made in China. Profits over people. 
 https://www.reddit.com/r/Epic_Economics/comments/s0z30c/defaults_abundant_market_contagion/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:21:16 </td>
   <td style="text-align:left;"> $QQQ FUTES RIPPIN!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:21:13 </td>
   <td style="text-align:left;"> $QQQ Down 5 days in a row. 396.47 | 396.47 | 384.29 | 384.02 | 379.86 | 370.74 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:20:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $AAPL Bears died a slow and painful death today.  They should have gotten vaccinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:20:09 </td>
   <td style="text-align:left;"> $SPY. 🥺
$qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:18:53 </td>
   <td style="text-align:left;"> $SPY $QQQ today was one of the sickest bear traps I have ever seen.  Look at the volume…dips were bought today.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:17:55 </td>
   <td style="text-align:left;"> $SPY these reports the next few days will bring panic to inflation , both roil and roast bulls who do not heed  THE TASTE of rates they got a couple different times flirting over 1.80 on 10 yr yield $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:17:54 </td>
   <td style="text-align:left;"> $QQQ 
March 5 
Not what you want to see on March 6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:15:16 </td>
   <td style="text-align:left;"> $QQQ $SPY big institutions all got in on this pump till the close. They all sold positions before and after the bell. Dark pool prints show big money and tomorrow they&amp;#39;re going to dump the shit on you rat basterds 
learn how it&amp;#39;s done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:14:55 </td>
   <td style="text-align:left;"> $QQQ What will Powell say tmr????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:14:30 </td>
   <td style="text-align:left;"> ETF overview, 5million not value and above  
 
$SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:14:20 </td>
   <td style="text-align:left;"> $QQQ  
 
QQQ Trending on Twitter the last 24hrs - seeing some movement on stocktwits as well. Keep an eye on what people are saying across social media - especially before market open tomorrow morning. Check it out here. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220110 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:13:46 </td>
   <td style="text-align:left;"> $QQQ my 50 1-12-22 $377 calls are beautiful paid $130 closed $515 OH LAWD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:13:38 </td>
   <td style="text-align:left;"> after a TREMENDOUS V rally today - finished at session highs - futures are CONTINUING THR FOLLOW THRU RIPPAGE - bears decimated $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:13:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA IF ANYONE NEEDS ME ILL BE ROLLING IN THE DIRT UNTIL 9:30 TOMORROW BECAUSE IM A BEAR 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:12:21 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/MPSVD0lecfk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:12:15 </td>
   <td style="text-align:left;"> Shorts covered .. might of caused a bounce in broader market with buying back… now Fed mtg on Wed will determine either a greater fall or stabilization. Let’s see 

🚨 $SPY $QQQ $DIA $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:11:09 </td>
   <td style="text-align:left;"> $QQQ powell will be hawkish tomorrow but question is how will the market react? Im betting it will be a nothing burger. Market already discounted his QT talk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:11:07 </td>
   <td style="text-align:left;"> $TNXP $QQQ $SPY $ARKG what do y&amp;#39;all think of this company Tonix? Check out the interview below, the CEO Seth Lederman looks promising, exciting company working on facsinating groundbreaking things such as seven years ago taking old drugs that already exist and modifying them for a new patent to help treat fibromyalgia!!!  https://youtu.be/8eRleALz6-8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:10:36 </td>
   <td style="text-align:left;"> $QQQ wtf just happened after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:09:14 </td>
   <td style="text-align:left;"> $QQQ 355-360 BY FRIDAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:06:11 </td>
   <td style="text-align:left;"> $QQQ $NVDA $AMZN $TSLA QQQ 383 is a key level. It is the summit of the early September pivot high, as well as the approximate location of the 100 day moving average. We are currently sitting around 380. 
If we break decisively above, I believe that the tech pullback is over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:03:19 </td>
   <td style="text-align:left;"> $QQQ GAPP UPPPPP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:02:32 </td>
   <td style="text-align:left;"> $QQQ meme plays are better than this lol. This trades like a penny stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:02:28 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-10 Trade Analysis Video: 
https://www.youtube.com/watch?v=mpeVC1WTLFc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:02:05 </td>
   <td style="text-align:left;"> $QQQ 10 to 11 Pt Run.  Fantastic!  Expecting a gap tomorrow.
$SPY $IWMcontent_type: image/png
filename: unknown.png
height: 608
id: 9302500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:01:44 </td>
   <td style="text-align:left;"> $QQQ so much pain being dispensed.  Ask yourself if u r a buyside institutional money manager can you stay underweight tech? If not should you buy QQQ or TQQQ or FNGU to tey to catch up? That is all that is going on right now in big money land, trust me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:00:50 </td>
   <td style="text-align:left;"> $SPY $QQQ im going to start a 10k to 1k challenge.. who’s with me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:00:28 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AMD $AAPL Funny how the market took a U-turn when Goldman Sachs said they &amp;quot;see&amp;quot; a possible 4 rate hikes this year. Everyone knows predictions from banks are half true most of the time. That&amp;#39;s how they play the retail investors with weak hearts and then buy the dip. Unless FED confirms it during meetings, anything released in between is just FUD. A well played move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 08:00:24 </td>
   <td style="text-align:left;"> $QQQ almost a week of getting fucked, and the day we end green is like this...wow lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:59:46 </td>
   <td style="text-align:left;"> $AMD $QQQ Nasdaq Broke Down Noticeably below key trend line 
Intraday recovery was secondary. Watching for continuing downward downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:58:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP 

Daily Market Recap for Monday 1/10/2022 for trending #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/tVSLuIIFe6s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:55:13 </td>
   <td style="text-align:left;"> $QQQ bro I shoulda bought the o DTE calls I’d have made 15k on 400 fk oh well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:52:57 </td>
   <td style="text-align:left;"> $QQQ bro wait I almost bought qqq dte calls this am I had $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:49:36 </td>
   <td style="text-align:left;"> $SPY $QQQ I knew I was in trouble with my $380 strike Q calls I bought at Friday’s bell. I played catch up with $DIA $360 calls at the morning dip for $200/ea. Turned out I saved my day. all 15 calls expire Friday. I’ll unload them tomorrow around lunch. I’m making small moves right now bcuz… let’s be honest… sh*t’s getting hard to read. Those are my plays today. What you got? Temporarily bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:46:43 </td>
   <td style="text-align:left;"> $QQQ fraud everywhere is not bullish
 https://www.reddit.com/r/Epic_Economics/comments/s0ycaw/fed_officials_congress_members_illegal_trades/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:45:14 </td>
   <td style="text-align:left;"> Jamie Dimon sees the best economic growth in decades, more than 4 Fed rate hikes this year

https://www.google.com/amp/s/www.cnbc.com/amp/2022/01/10/jamie-dimon-sees-the-best-economic-growth-in-decades-more-than-4-fed-rate-hikes-this-year.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:43:48 </td>
   <td style="text-align:left;"> $SPY $QQQ If inflation is slightly lower than the market expects on Wednesday then I can see this market rallying very hard on Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:43:43 </td>
   <td style="text-align:left;"> $FB this ain’t over $nvda $amzn more blood-letting 
May get a chance to reman solvent on open ( small window ) $qqq crashy crashy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:41:55 </td>
   <td style="text-align:left;"> $QQQ NOO and I think you have to do it I think you are a lot more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:41:12 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ $DIA 

If Jamie is right then why aren&amp;#39;t growth stocks rallying???  They&amp;#39;ve been decimated over the Cathie Wood Hatred and Jealousy trade.

When is everyone going to see how undervalued they are and how OVERVALUED the value stocks are????

https://www.cnbc.com/2022/01/10/jamie-dimon-sees-the-best-economic-growth-in-decades-more-than-4-fed-rate-hikes-this-year.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:39:53 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
JPOW ain&amp;#39;t gonna raise rates! 
 
JPOW ain&amp;#39;t gonna reduce the balance sheet! 
 
JPOW gonna keep supporting the markets indefinitely... 
 
It&amp;#39;s literally impossible to have a FED-BACKED BULL MARKET without the FED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:38:22 </td>
   <td style="text-align:left;"> Jan 10, 2022: Healthcare outperforms 1.1%, basic materials and industrials slammed -1% 
 
Top 3 Sectors YTD (as of today&amp;#39;s close):  
1. Energy +9.8% 
2. Financials +4.3% 
3. Consumer Def -0.4% 
 
$XLE $XLF $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:37:30 </td>
   <td style="text-align:left;"> $QQQ People are aware that Powell is going to be spending most of tomorrow testifying at his confirmation hearing. That is a whole of him detailing how he intends to fight inflation by raising rates-selling assets. I am sure this will be swell for the Qs. Smells strongly of pump and dump here .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:36:21 </td>
   <td style="text-align:left;"> $QQQ haha fuck it...I bought calls on this and spy. Difference is when you realize to get out. Think we see a strong bull market this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:36:18 </td>
   <td style="text-align:left;"> $QQQ today was dump and pump lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:35:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
&amp;quot;TRILLIONS of dollars on the sidelines&amp;quot; but somehow we *still* need the FED to pump TRILLIONS into the market. 
 
What a racket! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:35:40 </td>
   <td style="text-align:left;"> $QQQ $JMIA $SOFI $SPCE yeet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:35:39 </td>
   <td style="text-align:left;"> $QQQ poor shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:34:36 </td>
   <td style="text-align:left;"> $QQQ I missed when $NASDAQ  was trending last night $SPY  all those overnight bulls got rugged in the morning and most probably sold for a loss on the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:34:36 </td>
   <td style="text-align:left;"> $SPY Too bad you bulls brought this back up, retail just probably sleeps in own 3-yr unlaundered bed as JPow will see things looking ok into talk and just let bears RIP this lower tomorrow .
Remember, he wants a revised 2.5-3% target inflation, we&amp;#39;re double that, and more, now. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:33:31 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM big hammer...my analysis had the market entering &amp;quot;panic&amp;quot; mode early in the day...then came a massive turnaround going into the close...this is bullish.  Hopefully, we&amp;#39;ll have clear sailing for the next couple of weeks.

Did you go long today? Which stocks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:32:34 </td>
   <td style="text-align:left;"> $BTC.X. 😮
$qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:32:33 </td>
   <td style="text-align:left;"> $QQQ crazy day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:31:07 </td>
   <td style="text-align:left;"> $SPY $QQQ who cares what happens now...it&amp;#39;s all for nothing
The real party starts during the night and at 10am tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:30:45 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA Yet another horrible Beijing Biden market day. Endless crap! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:29:32 </td>
   <td style="text-align:left;"> $QQQ This was the headline this morning - shortly  after that, it was straight up:

&amp;quot;Nasdaq Enters &amp;#39;Correction&amp;#39;, Breaks Below Key Technical Support&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:29:18 </td>
   <td style="text-align:left;"> $QQQ going up tomorrow right...RIGHT?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:28:45 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $SMH … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:28:11 </td>
   <td style="text-align:left;"> $QQQ all these angry needle dick bears were so happy in the early AM and now they are roid raging wishing everyone to lose their money cause it’s green now. Hahahaha Why you so mad???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:26:28 </td>
   <td style="text-align:left;"> $SPY This week&amp;#39;s going to be very synthetic b4 getting really real.
First, tomorriw, the artificiality of FED speak &amp;amp; pump , what could possibly go wrong with that based on current knowledge of tightening + jobs PROOF, rising sooner than later.

Then Wednesday wel get some authenticity to inflation, will cars, electronics and $40 BILLION credit spend (when consensus 20B) push that 6.8% to 7.1% as predicted or higer.

My guess CPI? It&amp;#39;s perfect. 7.7%

PPI really hits us Thursday, again, it is not going to be a bullish # based on CPI &amp;amp; how much consumer willing to CREDIT to their accounts in December.

Friday? Sheesh. Get real. This will beca YUGE beat, prob beats so much we get my drop to 440-445. 

Everything will be prep for the incoming gaudy (gucci? since apparel #1 sector increase) retail report print

$QQQ $AMD  $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:25:57 </td>
   <td style="text-align:left;"> $QQQ $SPY bears got trapped today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:24:51 </td>
   <td style="text-align:left;"> $SPY $QQQ It looks like nobody is considering a 3% flush tommorow.Im in cash , but do you know a bear that bought a put? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:23:29 </td>
   <td style="text-align:left;"> $QQQ There has never been any bag holder in the history of qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:23:13 </td>
   <td style="text-align:left;"> $QQQ my take is rates are just a excuse for sell off caused by thing simply being overvalued.  Apples isn’t worth x2 what it was 1 year ago and neither is any other mega cap.  Need some stories for it I guess.   Rates aren’t really a issue if the economy is strong they have much room to go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:22:46 </td>
   <td style="text-align:left;"> $QQQ damn… I really though this was a fake rally and bought pits at close.  Can’t believe we’re green in futures. But maybe that’s a good thing for out buyers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:22:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Stupid idiots thinking it&amp;#39;s going to run
You all deserve to blow up your accounts and get real jobs lolll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:21:54 </td>
   <td style="text-align:left;"> $QQQ face ripping rally tomm. Rumor has been sold. News will be bought. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:21:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Can&amp;#39;t wait for tomorrow at 10am.. perhaps during the night as well
TO THE SHIT HOUSE LOWER LOWS TOMORROW
LETS GET THAT MONEY!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:21:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $DJIA … Jpow tomorrow 👇🏻? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:20:21 </td>
   <td style="text-align:left;"> $QQQ it’s sad when the economy is suppose to be doing so great but investors find it so compelling to pay for start ups and non profit companies before the ones actually making building on the balance sheet not just market caps. I mean seriously is there no room for anything else but tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:19:31 </td>
   <td style="text-align:left;"> $QQQ hyperinflated. trash
 https://www.reddit.com/r/Epic_Economics/comments/s0xq2e/fed_mistakes_cost_investors_everything/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:18:01 </td>
   <td style="text-align:left;"> $TSLA  YOU ALL KNOW  WHAT HAPPENS NEXT..... LMAO 🤑🤑🤑🚀🚀🚀 
. 
$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:17:14 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Off the charts: QQQs breach 150-DMA for first time in 18 months https://www.stck.pro/news/QQQ/21094916 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:15:42 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $IWM

Sheep getting vaccinated, literally.  😅

https://i.imgur.com/Oo5oCE7.gifv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:14:30 </td>
   <td style="text-align:left;"> $QQQ I am bearish on this index this year but one has to remember: rates have not actually been raised yet. Until that happens, and these companies start reporting ER, nothing has changed. This has all been pure fear selling. CPI is the only wildcard but we could be in store for a big rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:13:09 </td>
   <td style="text-align:left;"> $QQQ $NDX …  was this the correction bears been waiting for ?

Cuz banks $xlf and energy $xle won’t let $spy down further imo 

I hope so 🤞🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:12:49 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/10/2022 $SPY $XLF $QQQ $TSLA $NFLX https://www.chartguys.com/daily-market-videos/4101/are-bulls-in-control-or-is-the-sky-falling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:12:47 </td>
   <td style="text-align:left;"> Jim Cramer confirms a bottom today - says if it opens down BTFD whatever you want $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:12:15 </td>
   <td style="text-align:left;"> $QQQ $SPY powelll gonna smooth talk the markets like he always does, and pump it up rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:12:06 </td>
   <td style="text-align:left;"> $QQQ made in China. Profits over people. ☠️
 https://www.tradingview.com/chart/QQQ/KuhZpxqd-Invesco-QQQ-Ponzied-Valuation-Matters-Smallcaps-Win/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:11:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $QQQ did better than 75% of all other stocks. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:10:00 </td>
   <td style="text-align:left;"> $QQQ prob gonna dump at open then rally after Powell says his thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:09:36 </td>
   <td style="text-align:left;"> $QQQ toots rippin’? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:08:06 </td>
   <td style="text-align:left;"> $QQQ short term rally. Going back down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:07:54 </td>
   <td style="text-align:left;"> $QQQ Can Powell crash the market tmr??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:07:05 </td>
   <td style="text-align:left;"> $QQQ $SPY cpi data out tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:06:17 </td>
   <td style="text-align:left;"> $QQQ $SPY wow that was a scary 2022 bear market.  Alright back to all time highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:05:27 </td>
   <td style="text-align:left;"> $QQQ Triple top. 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:04:52 </td>
   <td style="text-align:left;"> $QQQ we rippin yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:03:45 </td>
   <td style="text-align:left;"> $QQQ futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:03:10 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ here&amp;#39;s what everyone else thinks. Sorted by accuracy on previous Tesla call/targets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:02:26 </td>
   <td style="text-align:left;"> $INTC - FALL-OW FOR MORE TRADE ALERTS. 
LYNX IN BAYU
$TLRY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 07:00:02 </td>
   <td style="text-align:left;"> $TSLA $SPY  $QQQ this just in.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:59:50 </td>
   <td style="text-align:left;"> $QQQ ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:59:49 </td>
   <td style="text-align:left;"> $SPY $QQQ Made a shit load of $$$ shorting the markets since last week. Thank you
Now the pump last 4hrs of trading was a joke but hey, i&amp;#39;ll take it....puts galore from here and retest the lows again
SUCKERS who bought the DEAD CAT BOUNCE
CLASSIC Looollll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:57:18 </td>
   <td style="text-align:left;"> $QQQ stock market gonna keep being shitty until we get over this diseases and vaccines bump ...this is literally the worlds topic right now, every country in the world is on the same page about this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:56:41 </td>
   <td style="text-align:left;"> $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:56:12 </td>
   <td style="text-align:left;"> $SPY $QQQ BEARS  WHAT HAPPENED TO THE CRASH TODAY??!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:55:49 </td>
   <td style="text-align:left;"> $QQQ When treasury climbs algos will auto dump growth and expensive tech stocks. Retail dip buying will lose momentum imo. Don’t fight the Fed! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:55:40 </td>
   <td style="text-align:left;"> $NVDA  $SPY  $QQQ  -- Lol, I traded thru Bank collapse2007-2009,  Covid, BP oil spill ,  lol ..  Of-course I held my april NVDA calls thru this pull back... haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:55:33 </td>
   <td style="text-align:left;"> #GreenScores™ If you were batting at 52% Green stocks today, you matched the $NDX $QQQ.  $SPX $SPY was 36% Green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:54:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $DWAC The Plunge Protection team was out in full force today because Jerome Powell’s nomination day is tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:54:31 </td>
   <td style="text-align:left;"> $SPY $QQQ tough to be in puts or calls in to tomorrow.. no one knows what can happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:53:06 </td>
   <td style="text-align:left;"> $QQQ gap up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:50:01 </td>
   <td style="text-align:left;"> $QQQ gap up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:49:42 </td>
   <td style="text-align:left;"> $QQQ flying tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:49:41 </td>
   <td style="text-align:left;"> $BTC.X Lets go Chinatown dump this shit to 36k
Markets will follow as well ;)))
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:48:57 </td>
   <td style="text-align:left;"> Regardless of market, $tsla can go nuts if get momentum. $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:47:26 </td>
   <td style="text-align:left;"> $QQQ calls more than puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:45:35 </td>
   <td style="text-align:left;"> $QQQ $400 Where are you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:45:35 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ alright monkies here is chart #2   
apple can hit 200 end of this wave 
 
feb 18 200 dollar calls are amazing here 
earnings soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:45:07 </td>
   <td style="text-align:left;"> $QQQ $INTC $SPX $DIA “A smooth sea never made a skilled sailor.”
Franklin D. Roosevelt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:44:45 </td>
   <td style="text-align:left;"> $SPY $QQQ alright you apes that dont know how to chart, imma bless u with some charts 
 
$FB inverse head and shoulder, earnings soon  
spy is bullish rn 
good play to do calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:44:17 </td>
   <td style="text-align:left;"> $UDOW $QQQ $SSO $F  any stock and any index can turn into a meme.. there are no rules. Feds and deep state are the rulers. News doesn&amp;#39;t take a stock up nor down. News is dependant on what &amp;quot;they&amp;quot; want to happen. Shorts eating shit regardless of covid, inflation, or shit economy. Fundamentals never mattered.  Wake up people! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:44:16 </td>
   <td style="text-align:left;"> $SPY $QQQ congrats everyone ! great profits day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:41:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $NVDA &amp;#39;Bout to get cooked, bulls, you won&amp;#39;t get off the hook with CPI consumer prices reading, Wednesday.

Keep fighting.

Won&amp;#39;t get off hook Thursday with PPI wholesale read. COGS is rising.

Keep fightin&amp;#39;.

And you won&amp;#39;t get off the hook with retail sales #s, this will be the one you fight the most, seeing dollar $igns  for your stock(s). But, all that HOT retail # will do is fire up the FED to have FEBRUARY, and not March, be 1st rate hike option?

Keep fighting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:40:33 </td>
   <td style="text-align:left;"> $AFRM $RBLX $NVDA Correct me if I’m wrong but I don’t think I’ve seen $QQQ down 3.03% and finish the day up 0.07%. Like…. Ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:39:49 </td>
   <td style="text-align:left;"> #7 $SPY $QQQ $DIA $BTC.X $NFT; Blood Bath? Market Crashing? Where to Put Y... https://youtu.be/OImSXr8bDGU via @YouTube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:39:34 </td>
   <td style="text-align:left;"> $NVDA THIS FUCKER  $300 ++  IN THE MORNING..  WHAT A BOUNCE   LOLOL  🤑🤑🤑🚀🚀🚀 
. 
$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:39:22 </td>
   <td style="text-align:left;"> $QQQ $SPY What an insane day. Down 2+% and closing practically flat. BANANAS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:38:18 </td>
   <td style="text-align:left;"> $QQQ all price action today, completely legitimate.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:38:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $RUT $IWM 

🗓 JPow speaking tomorrow @ 10 E.T. and we all know how the market loves to hear him talk…NOT. 😒

Link: https://www.federalreserve.gov/newsevents.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:37:26 </td>
   <td style="text-align:left;"> $QQQ $GOOG  BUY THE FUKING DIP OR QUIT TRADING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:36:02 </td>
   <td style="text-align:left;"> $QQQ Down to the 200dma (363) would be just around a 10% correction from the high (408) ... I don&amp;#39;t think we are done quite yet.. 

$ENPH $APPS $ENVX $HYZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:35:07 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $GLD Stocktwits needs more loss porn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:34:51 </td>
   <td style="text-align:left;"> $SPY $QQQ If the bears didn&amp;#39;t cover earlier today then they simply got way too greedy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:34:44 </td>
   <td style="text-align:left;"> JPow on deck Tue 10 AM ET 
$SPX $QQQ $TQQQ $IWM $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:34:04 </td>
   <td style="text-align:left;"> latex897595b01b9c38cf544ec43543f50ebb Bank of America 40$ pt. Cookieless advertisement. 500 million mc. 200ml+ revenue. Little debt. $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:33:04 </td>
   <td style="text-align:left;"> $spy $qqq $iwm $tsla https://www.youtube.com/watch?v=9XIaFT4uTzE&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:32:51 </td>
   <td style="text-align:left;"> $QQQ nice come back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:32:49 </td>
   <td style="text-align:left;"> $qqq $btc.x $eth.x $shop https://www.youtube.com/watch?v=Bre2OSK2axA&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:32:17 </td>
   <td style="text-align:left;"> $VIAC no idea why $DIS or $nflx hasn&amp;#39;t made offering for this - huge margins and would be major additions to their growing content libraries. $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:31:56 </td>
   <td style="text-align:left;"> $QQQ long term hold
https://shop.robindrip.com/collections/qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:31:38 </td>
   <td style="text-align:left;"> $qqq $soxx $soxl https://www.youtube.com/watch?v=9969iOjo4jM&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:31:26 </td>
   <td style="text-align:left;"> $QQQ Nasdaq rallies on Monday afternoon to snap losing streak, erasing loss of more than 2%

https://www.cnbc.com/2022/01/09/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:31:23 </td>
   <td style="text-align:left;"> $QQQ back to $390 you go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:31:20 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ wild day! model statuses:
TA - Trend: BUY
TA - Mean Reversion: BUY
Vix Basic: SELL
https://grizzlybulls.com

Is the recovery real, or just an oversold dead cat? Free models remain mixed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:31:07 </td>
   <td style="text-align:left;"> $QQQ everyone expecting  dump after speech.  You know that means it will rip right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:29:53 </td>
   <td style="text-align:left;"> $QQQ back to $390 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:29:07 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $XLK … 

today is the day where u block “experts” … vs following “real winners”   ⚠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:29:05 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:28:54 </td>
   <td style="text-align:left;"> $QQQ Bounced off 200 MA support, tomorrow we have some relief rally hopefully </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:28:25 </td>
   <td style="text-align:left;"> $QQQ what a bounce we had today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:28:02 </td>
   <td style="text-align:left;"> $QQQ $COMPQ $SPY $UVXY $TWTR Something I tweeted this morn! 
 
-Unexpected dip in the cyclical bull market for Nasdaq?  
-Not according to the 1998-2000 analogue! 
-Same path, healthier plane! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:25:06 </td>
   <td style="text-align:left;"> $QQQ We secured 415% gains today on QQQ $380 calls expiring today on a break above the gap resistance. For more plays like this, join our discord, link in bio. We give out free plays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:19:28 </td>
   <td style="text-align:left;"> $QQQ needs to find new support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:19:22 </td>
   <td style="text-align:left;"> $QQQ Insane bear trap today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:18:34 </td>
   <td style="text-align:left;"> $QQQ I don’t trust it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:18:28 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … fed powel will be a fool 🤡 if he derails this market… 

🔹but he is no fool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:17:40 </td>
   <td style="text-align:left;"> $QQQ what a crazy day!!!  I called a great entry point to buy today: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:17:24 </td>
   <td style="text-align:left;"> Today worked out much better than I thought it would for the bulls.  The market bounced off the lower trendline and broke the upper trend line formed from last week. $NDX $ES_F $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:16:13 </td>
   <td style="text-align:left;"> $QQQ took a lot of bullish positions but imma close tomorrow morning. I realized I was sucked in and I think this is the Start of a bear trend down. The fed is legit telling us what they doing. Let’s not get emotional and act accordingly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:14:51 </td>
   <td style="text-align:left;"> $QQQ 

Perfect channel for over a year. Almost to support. Time to buy dips. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:14:05 </td>
   <td style="text-align:left;"> $QQQ $DKNG $FSR $SOFI $IONQ  
 
Today may have been the bottom with that strong reversal we saw in the NASDAQ. We shall see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:14:01 </td>
   <td style="text-align:left;"> $QQQ Hope everyone was buying these lows. Everything was on clearance and shoved right in your faces </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:13:54 </td>
   <td style="text-align:left;"> $QQQ nice rally but I don’t like  that large cap still running </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:10:29 </td>
   <td style="text-align:left;"> $QQQ Personally always welcome new friends to join TEAM HOUSE 🎰 ALWAYS WINS ;) BUT the thought manufacturers do have to keep subscriptions going ya know + ratings and what not..old bank wanting no part of the $308 Discount for weeks = No new friends :( 👉 Bearish data needed “Santa Rally” promo..good vibes though 👌

Sorry friends If don’t get the $308 discount..we’ll see what data is and how it’s presented this week though. You never know! 🍀✌️

FUN either way 🏄‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:10:21 </td>
   <td style="text-align:left;"> $QQQ red or green tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:09:50 </td>
   <td style="text-align:left;"> $QQQ mega tech the best all around stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:09:14 </td>
   <td style="text-align:left;"> $QQQ I like how excited bulls are to rebound and &amp;#39;beat&amp;#39; the bears, but honestly look at the market. How much further up are y&amp;#39;all willing to take it? Because in the end...someone will be holding the bags and best hope its not you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:08:25 </td>
   <td style="text-align:left;"> $QQQ Just a big trap, Mega Tech held this up.   Any growth tech got hammered again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:08:06 </td>
   <td style="text-align:left;"> $SPY $QQQ RIGGED MARKETS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:07:49 </td>
   <td style="text-align:left;"> $QQQ nice recovery today!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:07:33 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $AMZN $VZ  
 
Coming into 2022, we anticipated more volatility and headwinds during H1, that breed dip buying opportunities for savvy and long-term investors. Active portfolio managers likely do better than passive portfolio managers in 2022.  
 
With such an outlook, and having positioned for such an environment in Q4 2021,  dip buying opportunities and market volatility are easy to act upon. Drawdowns are the expectation for long-term holdings in the interim. EQ over IQ sets the stage for an easily executable game plan. Up you win, down you win eventually.  
 
I bought hella TQQQ right out of the gate this morning. Again, lower is better, and still actionable. Added SBUX, PYPL and recaptured, but flipped AAPL. Shorted VXX for another profitable trade on the day and took profits on long-term holdings in VZ, after already qualifying for dividend.  
 
The savvy investor and trader will find themselves in Win:Win situations more often than not. You can trade with me! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:06:39 </td>
   <td style="text-align:left;"> $QQQ derp cat bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:06:26 </td>
   <td style="text-align:left;"> $QQQ will likely attempt, if not gap up to open, at 385 tomorrow, with the big test at around 390 which I imagine it we will try this week. Short term bullish, medium outlook still bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:05:12 </td>
   <td style="text-align:left;"> $QQQ $SPY anyone feel that!  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:04:27 </td>
   <td style="text-align:left;"> $QQQ I have a question.   Did the market sell-off today? LOL 
JANUARY 10 2022 
QQQ price at entry.  375.58 
Buy to Open 
20 Contracts QQQ Jan 28 2022 375 Calls Limit at $8.94 (Day)  Filled at $8.89 
Also posted in my Facebook group in real time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:04:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM I can’t wait for these crooks to retire and write a book entitled ‘How to trade lotto calls on inside information like a sleazy politician 🚀🌕’

🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:04:24 </td>
   <td style="text-align:left;"> Common colds can protect against Covid 19

$iwm $spy $qqq

https://www.reuters.com/business/healthcare-pharmaceuticals/t-cells-common-colds-can-provide-protection-against-covid-19-study-2022-01-10/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:04:01 </td>
   <td style="text-align:left;"> $QQQ 
Repeat after me :

BTMFD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:03:29 </td>
   <td style="text-align:left;"> $QQQ Guy Adami… perma bear. 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:03:02 </td>
   <td style="text-align:left;"> $QQQ gap filled perfectly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:01:59 </td>
   <td style="text-align:left;"> $AMD So sad, no volatility in the market anymore $QQQ $SOXX $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:01:39 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQ $NVDA $AFRM I told everyone to buy the dip at 11:16 am EST on QQQ SPY NVDA SQ AFRM (check for yourself) and other tech stocks yet i get harassed by stubborn perma bears. Little do they know that their account will be down the drain tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:00:33 </td>
   <td style="text-align:left;"> $QQQ was a nice short covering rally. Need an UP day tomorrow to confirm the reversal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:00:15 </td>
   <td style="text-align:left;"> $QQQ anyone else see all those dark pool prints???  Tomorrow should be VERY exciting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 06:00:03 </td>
   <td style="text-align:left;"> Keep an eye on it. $QQQ  💥💴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:59:38 </td>
   <td style="text-align:left;"> $PFE $MRNA $SPY $QQQ $VXRT fund a real vaccine! https://twitter.com/JordanSchachtel/status/1480646641875132418?t=I3KeYbKwVMY8clgzDWoyDw&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:59:17 </td>
   <td style="text-align:left;"> $QQQ all the bears on here musta forgot to put SL on them puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:59:12 </td>
   <td style="text-align:left;"> $QQQ I can&amp;#39;t wait for what is yet to come. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:59:10 </td>
   <td style="text-align:left;"> $SPY $QQQ almighty channel trendline </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:58:38 </td>
   <td style="text-align:left;"> $SPY $QQQ profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:58:11 </td>
   <td style="text-align:left;"> $QQQ what a come back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:57:41 </td>
   <td style="text-align:left;"> $QQQ I hope this fucking tanks tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:56:49 </td>
   <td style="text-align:left;"> $TLRY $QQQ $BCRX $INTC $FUBO ;;;; 
 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,929 
Goal: $100,000 by end of January, 2022 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓 discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:56:48 </td>
   <td style="text-align:left;"> $QQQ we close above 386 tomorrow and the bulls back into play :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:55:23 </td>
   <td style="text-align:left;"> $QQQ caught the falling knife </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:55:16 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $AMD You see what im seeing boys. Let&amp;#39;s give bears a second thought about keeping shorts overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:54:42 </td>
   <td style="text-align:left;"> $QQQ  I&amp;#39;m taking advantage of this volatile market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:54:09 </td>
   <td style="text-align:left;"> $QQQ I’m fine if it goes to 360 by Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:54:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA  Everyone is so bullish going into tomorrow, everything has to go up. MM&amp;#39;s know better than to piss of retail investors.
Sorry I rebought puts now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:53:35 </td>
   <td style="text-align:left;"> $QQQ Don’t get trapped! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:53:14 </td>
   <td style="text-align:left;"> $QQQ Strong close today with a few leaders forming up. Gap down that gets supported is the best case scenario. A gap up to open and I&amp;#39;ll look for the weakest names to short. Staying open minded to the next move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:53:04 </td>
   <td style="text-align:left;"> $QQQ the way this recovered I&amp;#39;m thinking green tomorrow 
hope so hope so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:52:29 </td>
   <td style="text-align:left;"> $QQQ wow good job NASDAQ what a comeback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-11 05:51:50 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m taking advantage of this volatile market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 10:03:25 </td>
   <td style="text-align:left;"> ;) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 10:02:37 </td>
   <td style="text-align:left;"> :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:58:08 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $172.5 CALL Expiring: 01-14-2022 worth 48K🐂 |🥇  The trade has a sentiment of BULLISH | SweepCast.com or Premium Room ➡️  #daytradingtips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:55:03 </td>
   <td style="text-align:left;"> $AAPL fck beqrs and fck ultra bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:54:34 </td>
   <td style="text-align:left;"> $AAPL a nice play to have in the bag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:52:18 </td>
   <td style="text-align:left;"> $AAPL... $175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:50:36 </td>
   <td style="text-align:left;"> $AMD $nvda  $intc   $tsla   $Aapl 
https://seekingalpha.com/article/4478841-amd-ces-2022-shows-why-its-just-getting-started?messageid=2800&amp;amp;utm_campaign=4478841&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=RTA+Article+Smart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:47:40 </td>
   <td style="text-align:left;"> $AAPL RSI curl and MACD ready to cross. Watch how it trades into the MAs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:45:40 </td>
   <td style="text-align:left;"> $AMRS $RNLX $AAPL $INTC  
You heard it here first: (second if you read my sources and didn&amp;#39;t have the world&amp;#39;s best Taco Monday ever) 
 
St. Marko says HODL and buy the dip 
https://www.cnbc.com/2022/01/10/jpmorgans-top-strategist-kolanovic-says-buy-the-dip-markets-can-handle-higher-yields.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:44:11 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $AMD The 10 year Treasury yield seems to cap at 1.8 and have rotated down 0.51%. Bank stocks have rallied for a while. Time for big techs to shine ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:42:35 </td>
   <td style="text-align:left;"> Always interesting to c what the retail investor is up to. See if there is an actionable edge in their patterns.

In Dec @TipRanks users bought the following top 10 stocks
DIS $AAPL $TSLA $NVDA FB MSFT PYPL BABA $AMZN 

$NIO becoming a favorite 
More👉 https://bit.ly/3zuZRep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:42:30 </td>
   <td style="text-align:left;"> $AAPL I thought we were seeing 160? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:40:03 </td>
   <td style="text-align:left;"> $AAPL thing is, we have such a strong investor base keeping up to date with the latest evolution of products and new technologies! We’re talking about tapping into new industries, revolutionary things from a single company. ANDDDDDD EARNINGS IS COMING UP SOON!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:40:00 </td>
   <td style="text-align:left;"> $AAPL Cup forming. Two huge candles at the end. Calls go… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:39:01 </td>
   <td style="text-align:left;"> $SPY How will the referees call the game when they are getting paid by both teams? $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:37:54 </td>
   <td style="text-align:left;"> $AAPL gapping down tomorrow could wipe out the calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:37:40 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:37:20 </td>
   <td style="text-align:left;"> $AAPL shorts are super angry today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:36:47 </td>
   <td style="text-align:left;"> $AAPL $180+ by eow calling it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:35:28 </td>
   <td style="text-align:left;"> $AAPL  
🍏
1) Excellent Close At 4Pm. 
The last 10 minutes between 3:50 to 3:59Pm. 
Volume Intraday 97.8M. 
+0.02 +0.01%.  Extra Ordinary From NASDAQ-400 Points. 

2)Excellent Close at 7:59Pm. 
Volume 6.560M. 
+$071 +0.41%. 

Difference Vs Nasdaq ZERO. 
VERY STRONG TODAY.  
SOON $192. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:35:17 </td>
   <td style="text-align:left;"> $DSP bullish $TTD $PUBM $SNAP $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:33:21 </td>
   <td style="text-align:left;"> $WIMI $NVDA 🔥🔥🔥Wall Street firm, said the “biggest disruption humanity has ever experienced” would be the metaverse, which would present attractive investment opportunities. While a single metaverse may be more than a decade away, as it develops, it has the potential to upend almost everything in human life that hasn’t been upended yet.$FB $AAPL 
https://skinnerifffz85.medium.com/the-metaverse-market-will-usher-in-its-second-phase-with-seven-metaverse-stocks-to-watch-for-2022-11e7e2c4b2e2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:33:10 </td>
   <td style="text-align:left;"> $AAPL $SPY  LETS GO CRAZY TOMORROW BULLS. LIMIT UP. Put $UVXY  in the can of HELLLL🤣🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:24:47 </td>
   <td style="text-align:left;"> $AAPL great company. Stock could use a rest after years of parabolic rise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:21:17 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:17:29 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: January 14, 2022 $172.50 Calls 
Entry Price: $2.19 - $2.20 
Exit Price: $2.67 
Stop Loss: $1.93 
Potential ROI: 22% 
Estimated Hold Time: 68 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:14:27 </td>
   <td style="text-align:left;"> $AAPL Just saying it looks like a straight up double bottom zone being formed .. need to break out of it.. throwing this at 190 imho. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:13:44 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $5,273,100 call block traded with $170.0 strike expiring on 2022-02-18. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:11:27 </td>
   <td style="text-align:left;"> $AAPL Can somone explain the double outflow but positive results. Market obviously isn&amp;#39;t based on supply and demand anymore. It&amp;#39;s a casino run by the feds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:09:11 </td>
   <td style="text-align:left;"> $AAPL $AMD $BAC $NVDA  
 
Best Chatroom ,Best Trading Alerts. I&amp;#39;ve made over $103K with them, By their alerts !!💰🚀  discord.io/3CmBSrWuGJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:03:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:02:19 </td>
   <td style="text-align:left;"> $AAPL night all tomorrow is definitely looking up! 😃😃😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 09:02:11 </td>
   <td style="text-align:left;"> $AAPL very strong close tomorrow should be a interesting day i see it touching 175+ n maybe ending the day 174.20ish 🍏 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:58:48 </td>
   <td style="text-align:left;"> $AAPL  🍏 Note:  The VIX, at Today’s Close, was under “20”.  Under “20”, is good news.  Keep your eyes on the VIX.  It is WallSt’s “favorite tool” to Algo manipulate.  Bulls love the number 17…but, will take under 20! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:58:18 </td>
   <td style="text-align:left;"> $AAPL oh tomorrow will be interesting. Have a good night everyone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:57:18 </td>
   <td style="text-align:left;"> $AAPL this could be up 3-5 dollars  tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:56:01 </td>
   <td style="text-align:left;"> $AAPL made in China Stonk
 https://www.reddit.com/r/Epic_Economics/comments/s0ztj4/dip_buyers_got_caught_nas100_to_continue_selloff/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:55:08 </td>
   <td style="text-align:left;"> $AAPL time to close your short…already up 60c on the close…it’s an indicator folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:54:45 </td>
   <td style="text-align:left;"> latex7ecb3132123745de37e17679a9212489BMY 56c 60%
@MommasOptions 
$AAPL 177.5c 90% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:46:19 </td>
   <td style="text-align:left;"> $AAPL At today’s low there was a confluence of many indicators that pointed to at least a temporary bottom and at best to cycle bottom. 
Nothing is sure but it looks like we might start up move from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:44:43 </td>
   <td style="text-align:left;"> $AAPL 80 puts Oct 2022 anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:43:38 </td>
   <td style="text-align:left;"> $AAPL generated record revenue from their App Store in 2021 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:41:59 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $AAPL $TQQQ 

Apple chart has bearishness written all over it. Easily $160 from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:41:13 </td>
   <td style="text-align:left;"> Why $AAPL dont buy $ASML to become a dominant in high technologies company? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:40:44 </td>
   <td style="text-align:left;"> $AAPL $F $TWNK was up 10% on the day, ended the day $-4.00 lmao what a day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:39:07 </td>
   <td style="text-align:left;"> $PLTR $AAPL wtf vix futures are up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:33:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AMZN $AAPL Jpow going to say, we pumped too much need to raise rates now!!! 

In other news, a local grocery store Nob Hill is closing a store as employees reported. Parent company Raleys have not answered. More jobs lost....😕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:32:11 </td>
   <td style="text-align:left;"> $CLOV Holy hell this is a buy, investors freaked out over a MCR of 102% when it it 94% normalized? So many mature insurers run MCR above 100%. MCR should go back to 94% after Q1. Should have a profitable year this year. Will probably have a book value above it&amp;#39;s current share price end of 2023. Let&amp;#39;s see $AAPL $TSLA or $MSFT get a BV anywhere near their current market cap in the next decade or ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:30:50 </td>
   <td style="text-align:left;"> latex2c148c3f035f2ca73dfe6cedb130bd58NVDA - 62% call flow

#optionsflow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:22:25 </td>
   <td style="text-align:left;"> latexfefabb2904657447172161ebbe183d31 and push 180$ by Friday..tomorrow will be green!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:20:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $AAPL Bears died a slow and painful death today.  They should have gotten vaccinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:19:56 </td>
   <td style="text-align:left;"> $AAPL POWELL tries to keep his job tomorrow and he’s hoping for a Senate Confirmation.  Rates will go up in March, that’s almost a gimi not a reason at this time to bail or hold a short.  SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:18:03 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPL Trending on Twitter the last 24hrs - seeing some movement on stocktwits as well. Keep an eye on what people are saying across social media - especially before market open tomorrow morning. Check it out here. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220110 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:17:00 </td>
   <td style="text-align:left;"> $AAPL and tomorrow we rally. Sorry bears, you have overstayed your welcome. 👊🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:13:01 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $PYPL $SBUX 

From inside Finom Group trading room today… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:12:15 </td>
   <td style="text-align:left;"> Shorts covered .. might of caused a bounce in broader market with buying back… now Fed mtg on Wed will determine either a greater fall or stabilization. Let’s see 

🚨 $SPY $QQQ $DIA $BTC.X $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:11:23 </td>
   <td style="text-align:left;"> $SPY — Hard to time the bottom, but once a rip starts, it’s hard to catch… Loaded $AAPL $DIS $TQQQ calls today 🤷🏼‍♂️ Sell off into fed speech imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:08:30 </td>
   <td style="text-align:left;"> $AAPL hmmm can we get to $1.00 north of the close and another dolla in the am??  Indicator hour is on… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:08:29 </td>
   <td style="text-align:left;"> $AAPL Seeing Two Possibilities. Either this is the reversal or just a dead-cat bounce. $175.10 reclaim is key pivot. https://share.trendspider.com/chart/AAPL/404229cta0v </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:06:53 </td>
   <td style="text-align:left;"> $AABB Global Merchants accepting $AABBG.X can do so through $AAPL app store and $GOOG $GOOGL play. $AABBG.X Merchats accepting Gold are now on 5 continents including Australia! $AABBG.X is THE FIRST TO MARKET Global Gold currency system! 2022 BOOM TOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:04:07 </td>
   <td style="text-align:left;"> $AAPL was curious post from WSB tonight:  Fuck TSLA. AAPL 10% move this week. Back to three trilly &amp;amp; beyond </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:03:23 </td>
   <td style="text-align:left;"> $AAPL gap up tomorrow @ open wouldnt be surprised if we open @174-175 dip then rip 🍏  🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 08:00:28 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AMD $AAPL Funny how the market took a U-turn when Goldman Sachs said they &amp;quot;see&amp;quot; a possible 4 rate hikes this year. Everyone knows predictions from banks are half true most of the time. That&amp;#39;s how they play the retail investors with weak hearts and then buy the dip. Unless FED confirms it during meetings, anything released in between is just FUD. A well played move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:59:50 </td>
   <td style="text-align:left;"> $SPY $TSLA $FB $AAPL 

Lots of plays made money today!💰
Come join the free discord team and bank with us! Link in bio!💸💰🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:55:49 </td>
   <td style="text-align:left;"> $AAPL  change .63 vs .80 come on….lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:50:53 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 92.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:49:21 </td>
   <td style="text-align:left;"> $AAPL watch out tomorrow - it might be a runner on double digit growth projections </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:49:02 </td>
   <td style="text-align:left;"> $AAPL Imagine trying to make your money shorting this 🤣🤣 I’d rather take that money and play blackjack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:46:54 </td>
   <td style="text-align:left;"> $AAPL $172.19 Close 
 
AH 6:43 PM 
Bid  ARCX 
172.63 x 2 
Ask  ARCX 
172.70 x 2 
Volume 
106,686,753 
 
Keeps getting stronger in AH. Shorts being smart  covering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:46:47 </td>
   <td style="text-align:left;"> $AAPL big buyer just pulled 172.63 buy? Here we go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:42:01 </td>
   <td style="text-align:left;"> $AAPL omg look at the spreads the mm’s are putting out there, can anyone say mm manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:41:35 </td>
   <td style="text-align:left;"> latex2e1ec52b93d5e1316cd11ca6de9c1b24$ys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:39:40 </td>
   <td style="text-align:left;"> $AAPL ha ha ha ...gotta laugh... 🐻 and 🐂... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:38:29 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA $AMD $BTC.X yes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:37:50 </td>
   <td style="text-align:left;"> $AAPL keep trying, that was amusing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:37:04 </td>
   <td style="text-align:left;"> $AAPL is 169.50 a good entry? I purchase 20 stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:34:02 </td>
   <td style="text-align:left;"> $AAPL less than an hour and a half to cover, this should be fun to watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:33:31 </td>
   <td style="text-align:left;"> $AAPL     🍏 JPM, has just issued a “Rare Buy the Dip Call”.  https://www.google.com/amp/s/finance.yahoo.com/amphtml/news/buy-dip-wall-street-sell-225916976.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:32:15 </td>
   <td style="text-align:left;"> $AAPL $TSLA $FB $BTC.X  $SPY these Clowns 🤡 should sell Course on Investing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:31:47 </td>
   <td style="text-align:left;"> $AAPL is the crash over now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:31:31 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The Top Semiconductor Stocks of 2021 https://www.stck.pro/news/AAPL/21095372 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:31:06 </td>
   <td style="text-align:left;"> $AAPL short this pig.  OTCX next month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:30:28 </td>
   <td style="text-align:left;"> $AAPL lol who’s the idiot that just sold at $160.00?  Haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:30:12 </td>
   <td style="text-align:left;"> $AAPL lol every media source out there is pushing this price! Hedges sucking in retail to limit the rug pull drop. No worries I got time… 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:29:05 </td>
   <td style="text-align:left;"> $AAPL 140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:28:04 </td>
   <td style="text-align:left;"> $AAPL $TSLA  Got 18.5% cash left to buy aapl but dmn stk won’t cooperate, might be putting into tsla? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:27:39 </td>
   <td style="text-align:left;"> $SNAP screw snap it has no form of money making or products ! Unlike $AAPL we got App Store, phones, iPad , a lot technology, even streaming , soon Aapl car and vr glasses!! So screw snap, join Aapl !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:26:48 </td>
   <td style="text-align:left;"> $AAPL Jan 10, 2022,05:53pm EST 
MLB In Serious Talks With Apple To Stream Mid-Week Games 
Maury Brown 
Maury BrownSenior Contributor 
SportsMoney 
2020 Natl Sportswriter Of The Year Nominee, BBWAA, MLB, Motorsports  
This should take APPLE to $200 
The Grand Slam! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:26:43 </td>
   <td style="text-align:left;"> $AAPL Options Overview from Today... 
 
If you would like to make ticker requests I created a patreon page you can find on my profile. ten bucks a month. 
 
Looks like we see puts coming in at the end of the range but it could be a hedge and may see short term bullishness. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:25:38 </td>
   <td style="text-align:left;"> $AAPL 😂🤣😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:25:20 </td>
   <td style="text-align:left;"> $AAPL go BABY go!!! North just like I said.  Gap~n~go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:25:11 </td>
   <td style="text-align:left;"> $AAPL  🍏 ❗️Alert:  ST Ticker, lagging.  Share Price Upticking:  172.86 Ask/Bid 172.78. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:24:48 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #23 ticker with unusual activity from institutional traders with an average of 14% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:24:05 </td>
   <td style="text-align:left;"> $AAPL these 125 jan 21st 182.5 calls I bought today on the dip look like money baby! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:23:21 </td>
   <td style="text-align:left;"> $AAPL 175 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:22:10 </td>
   <td style="text-align:left;"> $AAPL holy rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:19:10 </td>
   <td style="text-align:left;"> $AAPL could kick myself for not adding more earlier today, was stuck in a meeting…ugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:18:57 </td>
   <td style="text-align:left;"> $AAPL https://www.bloomberg.com/news/articles/2022-01-10/bottom-fishers-save-nasdaq-from-five-day-rout-in-frantic-close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:17:48 </td>
   <td style="text-align:left;"> $AAPL 🔥🔥🔥🔥🔥🔥🔥🔥🔥

https://www.bloomberg.com/news/articles/2022-01-10/bottom-fishers-save-nasdaq-from-five-day-rout-in-frantic-close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:17:11 </td>
   <td style="text-align:left;"> $AAPL reviewing our new indicator on the 1 hour chart, looking for same candle reversals. got 2 winners today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:16:01 </td>
   <td style="text-align:left;"> $AAPL Ready for a bullish week!

https://www.bloomberg.com/news/articles/2022-01-10/bottom-fishers-save-nasdaq-from-five-day-rout-in-frantic-close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:15:27 </td>
   <td style="text-align:left;"> $AAPL reversal time 😈 

https://www.wsj.com/amp/articles/global-stock-markets-dow-update-01-10-2022-11641804091 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:14:37 </td>
   <td style="text-align:left;"> $AAPL the majority of family friends and coworkers I know are all lifetime Apple users, and earnings are going to beat expectations, this is a buy and hold opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:13:47 </td>
   <td style="text-align:left;"> $AAPL https://www.benzinga.com/node/24981236 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:04:10 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $MSFT $SPY SO no one thinking this was just a dead cat bounce, and once Powell starts yacking it&amp;#39;ll tank again ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:03:12 </td>
   <td style="text-align:left;"> $AAPL wrong answers only: Let’s guess what the earning reaction will be for AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:02:33 </td>
   <td style="text-align:left;"> $AAPL flutes ripping? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:02:30 </td>
   <td style="text-align:left;"> Watching my stocks go back up a little bit at the end of the end after an ass whooping for a whole week straight. $AMZN $AAPL $TSLA $BTC.X $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 07:02:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:58:04 </td>
   <td style="text-align:left;"> $AAPL $MSFT load up my guyyyy!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:56:43 </td>
   <td style="text-align:left;"> $AAPL how many parents out there have bought your kid/kids iPhone, iPad’s?  In just that segment, Apple secured multigenerational users. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:55:26 </td>
   <td style="text-align:left;"> $AAPL  Jan 25th 🚀😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:53:32 </td>
   <td style="text-align:left;"> $AAPL which way do we break out? 
🧐 🕵️‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:51:33 </td>
   <td style="text-align:left;"> $AAPL APPLE INC 4 PM Close $172.19 
 
5:45 PM 
Bid  XNMS 
172.53 x 3 
Ask  ARCX 
172.56 x 5 
 
Volume 
106,628,482 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:51:30 </td>
   <td style="text-align:left;"> $AAPL so net income before taxes in 2020 was 67 billion. Also 2019-15 income before taxes averaged out about the same. Why was net income nearly double in 2021, is it an outlier? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:50:11 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple: Huge Moat, but Valuation Leaves Little Upside https://www.stck.pro/news/AAPL/21092209 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:49:46 </td>
   <td style="text-align:left;"> $AAPL are you going back to green days now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:47:30 </td>
   <td style="text-align:left;"> $AAPL        🍏”🐐” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:47:11 </td>
   <td style="text-align:left;"> $AAPL bulls saying they feel bad for bears that didn’t cover… bulls I really am worried you all if you didn’t take this gift and cover while you could. Good luck all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:47:05 </td>
   <td style="text-align:left;"> $AAPL Realization setting in for perma bears. Moving forward. Always temp bear, perma bull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:45:35 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ alright monkies here is chart #2   
apple can hit 200 end of this wave 
 
feb 18 200 dollar calls are amazing here 
earnings soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:45:16 </td>
   <td style="text-align:left;"> $AAPL        🍏 MLB…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:39:25 </td>
   <td style="text-align:left;"> $TQQQ $SPY $AAPL $PYPL $UVXY   
 
Finom Group trade alerts YTD and back to July 2021 updated. https://1drv.ms/x/s!Aj3zbNeZWtzPZ4N6DtMsvnE7Ujs?e=BDqFeq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:39:15 </td>
   <td style="text-align:left;"> $AAPL how many shorts are greedy enough to hold overnight and kiss their profits goodbye??? Tides are a turning’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:36:48 </td>
   <td style="text-align:left;"> $AAPL da fuck just happened lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:36:08 </td>
   <td style="text-align:left;"> $NVDA $AAPL $MU $AFRM $SPY 
The gap up tomorrow is gunna wreck a lot of accounts.

Thanks for playing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:34:13 </td>
   <td style="text-align:left;"> $AAPL 176 177 tomorrow yes I said it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:34:04 </td>
   <td style="text-align:left;"> latex897595b01b9c38cf544ec43543f50ebb Bank of America 40$ pt. Cookieless advertisement. 500 million mc. 200ml+ revenue. Little debt. $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:34:03 </td>
   <td style="text-align:left;"> $AAPL Watch your MLB games with Apple TV. 
 
https://9to5mac.com/2022/01/10/mlb-apple-tv-sports/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:33:51 </td>
   <td style="text-align:left;"> $AAPL    Its coming SOON. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:32:23 </td>
   <td style="text-align:left;"> $AAPL $175 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:30:42 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-10 Largest Trades Data: 
https://www.youtube.com/watch?v=TnaeLWqt1e0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:28:47 </td>
   <td style="text-align:left;"> $DSP $APPS buy this $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:27:35 </td>
   <td style="text-align:left;"> $AAPL i like this. 18 points a day is 56% a year. Dope! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:27:30 </td>
   <td style="text-align:left;"> $DSP good opportunity here $AAPL $TSLA $BABA $PINS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:23:59 </td>
   <td style="text-align:left;"> $AAPL  🍏 Surge in AfterHours Volume:  6.4 Million Shares have traded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:22:51 </td>
   <td style="text-align:left;"> $AAPL there wouldnt be this much outflow if today’s reversal is solid $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:22:24 </td>
   <td style="text-align:left;"> $AAPL $180++++++++ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:21:24 </td>
   <td style="text-align:left;"> $AAPL solid gain today 💪 hopefully more to come tomo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:20:48 </td>
   <td style="text-align:left;"> $AAPL $180+ by eow. Last week my prediction of “175 by eow” was right AND MORE!!!

This week, as I said, $180+ conservatively!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:17:49 </td>
   <td style="text-align:left;"> $AAPL Will an official PR on deal finalization kickstart a bull run on this? Could be big🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:17:08 </td>
   <td style="text-align:left;"> $AAPL Everything hints towards a bullish move for the rest of the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:15:30 </td>
   <td style="text-align:left;"> $AAPL S&amp;amp;P roses because Powell is speaking tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:15:11 </td>
   <td style="text-align:left;"> $AAPL $GM 

Why Sony And GM Are Apple’s Latest Competitors In The Smart EV Car Market read more... read more...

https://finance.neuy.io/predictions.aspx?sort=&amp;amp;asc=&amp;amp;sec=&amp;amp;term=&amp;amp;s=aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:12:23 </td>
   <td style="text-align:left;"> $AAPL got calls when price was 168.53. Up 26% and counting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:12:22 </td>
   <td style="text-align:left;"> latex04cf821c5a2bca4ace72867308ade489NVDA 726k (57% call/43% put)
$F 589k (61% call/39% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:11:41 </td>
   <td style="text-align:left;"> $AAPL back up EOM
https://shop.robindrip.com/collections/aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:11:39 </td>
   <td style="text-align:left;"> $AAPL huge after hours buy just now😲😲😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:09:32 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : App Store developers made about $60 billion in 2021, Apple says https://www.stck.pro/news/AAPL/21091746 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:08:55 </td>
   <td style="text-align:left;"> $AAPL talking about this Yunno what tha means lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:08:18 </td>
   <td style="text-align:left;"> $SPY $AMZN $AAPL $TSLA 

Two words : 

BEARS ARE FUK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:03:40 </td>
   <td style="text-align:left;"> $INTC what’s Gregory M. Bryant next stop $AMD or $AAPL ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:01:27 </td>
   <td style="text-align:left;"> Apple in serious talks with MLB to broadcast games $AAPL https://nypost.com/2022/01/10/apple-in-serious-talks-with-mlb-to-broadcast-games/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:01:10 </td>
   <td style="text-align:left;"> $AAPL Apple Services Business Flourishes In 2021: Record High App Store Developer Revenues, Launch Of Apple TV 4K, Apple Pay Expands To New Markets And More 

https://newsfilter.io/a/331be6de2c73526d9a5d5c9799f057a3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:00:49 </td>
   <td style="text-align:left;"> $AAPL today &amp;amp; tomorrow don&amp;#39;t matter as CPI figures out on Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:00:34 </td>
   <td style="text-align:left;"> $HIMX If Himax gets tied to even one big name $AAPL $GOOG $MSFT $FB directly for their next-gen AR glasses the stock will skyrocket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:00:14 </td>
   <td style="text-align:left;"> $AAPL 160P Exp:21-Oct-22 --  🔥 Total(Day): $25,700 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:00:11 </td>
   <td style="text-align:left;"> $AAPL 180C Exp:21-Jan-22 --  🚀 Total(Day): $28,050 
$AAPL 180C Exp:18-Feb-22 ↑↑  🚀 Total(Day): $28,800 
$AAPL 120P Exp:19-Jan-24 ↓  🔥 Total(Day): $27,300 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 06:00:07 </td>
   <td style="text-align:left;"> $AAPL 172.5C Exp:14-Jan-22 --  🚀 &amp;lt;R&amp;gt; Total(Day): $227,774 
$AAPL 175C Exp:14-Jan-22 --  🚀 &amp;lt;R&amp;gt; Total(Day): $280,119 
$AAPL 177.5C Exp:14-Jan-22 ↑  🚀 Total(Day): $46,500 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:58:45 </td>
   <td style="text-align:left;"> $AAPL The only ones more mad about not buying today’s dip are those who sold at today’s lows. Oh and bears, I guess. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:58:27 </td>
   <td style="text-align:left;"> Road to $3 trillion $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:55:57 </td>
   <td style="text-align:left;"> ⏳📈💰 $AAPL - &amp;#39;Uber is the latest popular app to bail on the Apple Watch&amp;#39; -The Verge Report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:55:55 </td>
   <td style="text-align:left;"> $AAPL  to the bears 😜😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:55:16 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $AMD You see what im seeing boys. Let&amp;#39;s give bears a second thought about keeping shorts overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:54:27 </td>
   <td style="text-align:left;"> $AAPL  4:53 PM, EST 
 
$172.54 
+$0.35 (0.20%) 
 
Bid  ARCX 
172.48 x 1 
Ask  ARCX 
172.57 x 5 
 
Volume 
104,518,609 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:53:16 </td>
   <td style="text-align:left;"> $RH got in at 475 today long hold $BAC $GS $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:53:15 </td>
   <td style="text-align:left;"> $AAPL and there you have it positive articles flow in, now on TD AMERITRADE… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:52:16 </td>
   <td style="text-align:left;"> $AAPL AAPL has hit bottom, $168.17. This took 5 days. Now AAPL is retracing back to $182.94. I wonder how long that will take. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:52:10 </td>
   <td style="text-align:left;"> $AAPL said it this morning! Bear trap is locked and loaded! You have to be a dingbat to short Apple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:50:13 </td>
   <td style="text-align:left;"> $SPY $AAPL and $TSLA had nearly $100 Billion swings in 4 hours.  Completely rational. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:50:00 </td>
   <td style="text-align:left;"> $AAPL the last big one day gain 🍏 made was $25.00 bucks!!  CAN IT HAPPEN AGAIN?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:49:12 </td>
   <td style="text-align:left;"> $AAPL bulls always win at the end of the day believe it!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:49:08 </td>
   <td style="text-align:left;"> $AAPL heck of a lot of buying going on AH, shorts are F’d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:48:05 </td>
   <td style="text-align:left;"> $AAPL | Apple In Serious Talks With MLB To Broadcast Games - NYP https://nypost.com/2022/01/10/apple-in-serious-talks-with-mlb-to-broadcast-games/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:45:30 </td>
   <td style="text-align:left;"> $AAPL watch the big boys take all profits and open 169 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:44:16 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:43:59 </td>
   <td style="text-align:left;"> $AAPL $QQQ $AMD $TSLA Who cares about Fed rate-hikes. Over the last 3 decades of hiking rates period, Tech still outperforms. Now is the perfect time to BUY THE DIP ! All this sell-off is just panic selling and pricing in 4 rate hikes and balance sheet this year. This means any worse news about inflation, market already priced in. On the other hand, if CPI is below expected, market will rally like no tomorrow. Market swings fast just like today. People that sell at dips, well don&amp;#39;t expect to ride any gains lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:39:44 </td>
   <td style="text-align:left;"> $AAPL and she continues to rise AH, again Gap north tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:36:05 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 480.7K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:34:24 </td>
   <td style="text-align:left;"> $AAPL $VIX  $SPY  $TSLA  and just like that, everyone&amp;#39;s bullish again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:34:19 </td>
   <td style="text-align:left;"> $AAPL bulls can thank Jamie dimon for today.  Tomorrows another story. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:33:56 </td>
   <td style="text-align:left;"> $AAPL $F  
 
Will Apple be eventually using the vast Ford manufacturing Platforms for its future car/suv/truck plans?? 
 
Ford Rumor mill? 
 
Apple should just buy it for $33.00 and build all EV&amp;#39;s and merge planes with Farley. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:31:27 </td>
   <td style="text-align:left;"> $AAPL after all the shorting over the last several days, the inevitable SQUEEZE is going to be so much FUN!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:29:34 </td>
   <td style="text-align:left;"> $AAPL back up we go. $190 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:28:42 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s incredible how AAPL went up in spite of the millions of shorted shares. UNBELIEVABLE!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:28:15 </td>
   <td style="text-align:left;"> $AAPL 

1 mth chart - oversold has just exited and heading towards to uptrend momentum 

3 mth chart - oversold has begun to bottom out and is about to exit heading towards to uptrend momentum

6 mth chart - it’s oversold and is about to bottom out and is about to exit tmw.

1 yr chart it’s about to bottom on positive trend meaning rally will ensue prior to ER date

Remember this is algo based so have no fear !! 

Let’s go for green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:27:13 </td>
   <td style="text-align:left;"> $AAPL Apple implies it generated record revenue from the App Store during 2021    https://www.cnbc.com/2022/01/10/apple-implies-it-generated-record-revenue-from-app-store-during-2021-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:27:12 </td>
   <td style="text-align:left;"> $AAPL haha you donks missed the dip 🤣🤣🤣📈🛰🚗🚗🚗🛰🆙🆙✅✅💥💥👑👑🔥🔥🔥🍎🍎🍎🌙🌙🌙🚗🚗🚗🛰🛰🛰📈📈📈🎊🎊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:26:16 </td>
   <td style="text-align:left;"> $AAPL AAPL ....but a very nice reversal this afternoon (172.19). And continuing in AH (172.34). 
Bodes well for tomorrow. 
I&amp;#39;m looking for at least $182 near term. Maybe $185-190 into ER on the 27th. 
Then, if a good report for the holiday quarter as I expect, possibly $200. 
Lot of &amp;quot;ifs&amp;quot; there.. 
 
MG 
 
https://stockcharts.com/h-sc/ui?s=AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:26:06 </td>
   <td style="text-align:left;"> $INTC DAYUM Apple losing its head talent to now intel $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:24:38 </td>
   <td style="text-align:left;"> $AAPL   🍏 Volume, is back.  Massive surge in Volume into the Close, 103.8 Million AAPL Traded on the Day.  In the “final second” of the Close, 10.4 Million AAPL Shares trade to the “Buy Side”.  AfterHours Trade is brisk, 3.6 Million Shares traded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:23:16 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $TSLA $AAPL 
 
FED says it&amp;#39;s gonna raise rates and reduce size of it&amp;#39;s balance sheet in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:22:31 </td>
   <td style="text-align:left;"> $AAPL my covered calls still finished the day very green, the rest of the week could get bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:21:34 </td>
   <td style="text-align:left;"> $AAPL what a rollercoaster day that was ending up green 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:20:33 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
of course! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:19:36 </td>
   <td style="text-align:left;"> Most Traded Contracts 

$AAPL 14 January $170 Call
$AAPL 14 January $175 Call
$AAPL 14 January $172.50 Call
$AAPL January $170 Call
$AFRM February $85 Call
$AFRM February $95 Call
$TSLA 14 January $1100 Call
$AAPL 14 January $170 Put
$AAPL 14 January $177.50 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:17:58 </td>
   <td style="text-align:left;"> $AAPL with the size of  the bounce, today&amp;#39;s low was likely wave (1) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:17:30 </td>
   <td style="text-align:left;"> $AAPL S&amp;amp;P like dip 55 points tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:17:12 </td>
   <td style="text-align:left;"> $AAPL feels good calling bottoms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:16:20 </td>
   <td style="text-align:left;"> $AAPL 173 open let’s get it boys and girls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:15:29 </td>
   <td style="text-align:left;"> $AAPL still waitin for 120 like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:15:27 </td>
   <td style="text-align:left;"> $AAPL IPhone best product I ever owned besides my car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:14:23 </td>
   <td style="text-align:left;"> $AAPL moose knuckle my puts are toasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:14:00 </td>
   <td style="text-align:left;"> $AAPL how bad bullies like to squeeze 🤦 cant even push it to the 180&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:13:49 </td>
   <td style="text-align:left;"> $AAPL Duhh fake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:13:40 </td>
   <td style="text-align:left;"> $AAPL Bull trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:13:17 </td>
   <td style="text-align:left;"> $AAPL 180$ and ill put my life savings on Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:13:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX $AAPL $TSLA  
 
Breaking, 
 
Bears after making +500% on puts and losing -600% because they&amp;#39;re degenerate fuckwits who don&amp;#39;t take profits... are once again rushing into 0 probability puts in the hopes of bankruptcy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:12:57 </td>
   <td style="text-align:left;"> $AAPL 140 eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:12:36 </td>
   <td style="text-align:left;"> $AAPL $NVDA $DKNG $SOFI $TTCF prime entries on all swings time to fly folks :) 

If any dips will add more win win situation 

Follow for alerts :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:12:20 </td>
   <td style="text-align:left;"> $AAPL hope the bears covered today…tomorrow we ride </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:11:24 </td>
   <td style="text-align:left;"> $AAPL squeeze to $180.00. Correction over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:10:54 </td>
   <td style="text-align:left;"> $aapl short squeeze in play. Bear thesis is based on CPI numbers but i am afraid could be priced in. PT - $175 eow. $176 intraweek MAYBE. Unsustainable. $175 close this week means we retest $180+ for ER Run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:09:42 </td>
   <td style="text-align:left;"> $AAPL he has his confirmation hearing coming up.  He was renominated by Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:09:26 </td>
   <td style="text-align:left;"> $AAPL 200$ soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:08:45 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA Our 712 in chat get it…
We try to help folks but some refuse free education and experience…. Oh well🤷🏼‍♂️🤣
It’s good comedy at least </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:08:33 </td>
   <td style="text-align:left;"> $ZNGA If you are not shorting this and take two , what are you doing with your life ? Short these pos! 🐻📉 $QQQ $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:08:13 </td>
   <td style="text-align:left;"> $CIDM $SQ $AAPL $NVEI can anyone confirm if J Powell is indeed stepping down Jan 17th?  I need to spend my cash piles before that goes mainstream if it&amp;#39;s real.  My buddy says he&amp;#39;s stepping down but I can&amp;#39;t find any legitimate sources </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:08:07 </td>
   <td style="text-align:left;"> $AAPL Was the only bull here at 116 in March. I lost sight of the truth when i started shorting, but being bullish on apple is the only true way to make money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:08:00 </td>
   <td style="text-align:left;"> $AAPL wise people sold today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:07:58 </td>
   <td style="text-align:left;"> $AAPL Imagine tomorrow they announce an Apple car, fk tsla in the ass, send SPY to 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:07:56 </td>
   <td style="text-align:left;"> $AAPL think they have suckered enough shorts, now SQUEEZE ‘EM HARD!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:07:42 </td>
   <td style="text-align:left;"> $AAPL BZ: Top 10 WallStreetBets Mentions for January 10, 2022 Since 9:30 AM Open: GME, TSLA, TLRY, PLTR, AMC, NVDA, LCID, MSFT, AAPL, HOOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:07:37 </td>
   <td style="text-align:left;"> $AAPL (Delayed) Trading Jan 21 $170 Calls.  Noted gap filling today at $168. Expecting a positive run to $175 or higher pre-earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:07:10 </td>
   <td style="text-align:left;"> $AAPL What a come back! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:07:05 </td>
   <td style="text-align:left;"> $AAPL  Bears bought more puts today right? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:06:07 </td>
   <td style="text-align:left;"> $AAPL come on Apple positive news, nows is the time put news out now or early am a F the short interest! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:58 </td>
   <td style="text-align:left;"> $AAPL Hey bears, don’t go away mad! 
Just go away! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:43 </td>
   <td style="text-align:left;"> $AAPL green like a Granny Smith apple!! Don’t quit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:41 </td>
   <td style="text-align:left;"> $AAPL   For the win! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:15 </td>
   <td style="text-align:left;"> $AAPL 🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:14 </td>
   <td style="text-align:left;"> $AAPL How bout them apples? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:13 </td>
   <td style="text-align:left;"> $SPY $NVDA $AAPL tomorrow there will be blood on the street!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:05:11 </td>
   <td style="text-align:left;"> $AAPL  Apple Analyst Explains Why Cupertino Is Tracking Ahead Of Expectations In December Quarter

https://www.benzinga.com/analyst-ratings/analyst-color/22/01/24970849/apple-analyst-explains-why-cupertino-is-tracking-ahead-of-expectations-in-december- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:04:59 </td>
   <td style="text-align:left;"> $AMD Unbelievable $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:04:55 </td>
   <td style="text-align:left;"> $PLTR $AAPL latex876e43f43302215c622f1276ae297d12$k is going on? I went to being 5% down in my portfolio today to .13% up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:04:26 </td>
   <td style="text-align:left;"> $AMD $TSLA $AAPL $QQQ This is probably one of the biggest intraday price swings. If you sold in the morning oof... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:04:25 </td>
   <td style="text-align:left;"> $AAPL 170 calls 230 to 375. Solid win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:04:22 </td>
   <td style="text-align:left;"> $AAPL 🍏🟢🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:03:46 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:03:10 </td>
   <td style="text-align:left;"> $AAPL got 20 180 calls lotto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:03:05 </td>
   <td style="text-align:left;"> $AAPL $TSLA swings.. smell money tomorrow.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:59 </td>
   <td style="text-align:left;"> $aapl opened the day 3% in the red. closing 1.5% in the green, with a 2 cent move. I love spreads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:57 </td>
   <td style="text-align:left;"> $AAPL that 172 was borken to 168 low and come back green OMG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:55 </td>
   <td style="text-align:left;"> $AAPL Gap north tomorrow ahead of rocketing toward $200.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:52 </td>
   <td style="text-align:left;"> $AAPL easy gonna open green tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:47 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA $MSFT $NVDA HOLY SMOKES crazy bounce plays today! killed AAPL/SPY bounce on those dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:38 </td>
   <td style="text-align:left;"> $MSFT $AAPL $FB $AMZN today marks the bottom… and rotation back to stable tech… its distribution time in cyclicals and financials … they have topped! Check their charts for 2018-2019

Made good some on msft day trade! Love this stock! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:37 </td>
   <td style="text-align:left;"> $AAPL $300 in 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:02:11 </td>
   <td style="text-align:left;"> $AAPL YOUNG BLOOD STRIKES BACK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:50 </td>
   <td style="text-align:left;"> $AAPL Go fucking figure ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:39 </td>
   <td style="text-align:left;"> $AAPL Lets get $180 before earnings 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:31 </td>
   <td style="text-align:left;"> $AAPL we close green 😂! Who’s the noob that short/puts while stocks was already down?! Always load up when stock drop.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:22 </td>
   <td style="text-align:left;"> $AAPL ready for 200 ✅✅🍏🍏 patience </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:20 </td>
   <td style="text-align:left;"> Block and PayPal - Ostensibly Bottomed &amp;gt; https://tinyurl.com/5n6fd7xt

$SQ $PYPL $COIN $AAPL #stocks #Block #PayPal #Coinbase #Affirm #Venmo #CashApp #investing #crypto #Apple #blockchain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:16 </td>
   <td style="text-align:left;"> $AAPL let’s go!! Way to bounce back!! 🤤🤤🤑🤑💪🏽👊🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:01:09 </td>
   <td style="text-align:left;"> $AAPL 

Told you - you don’t need to be fearful ..

See this is very very impressive push! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:41 </td>
   <td style="text-align:left;"> $AAPL Wow! What a way to end the day. See you all tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:38 </td>
   <td style="text-align:left;"> $AAPL See you at 175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:37 </td>
   <td style="text-align:left;"> $AAPL lol should have held my calls for 30
Extra minutes what a finish!! Tomorrow 175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:21 </td>
   <td style="text-align:left;"> $AAPL it’s fair to say that this week should be good for aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:16 </td>
   <td style="text-align:left;"> $AAPL $240 this year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:15 </td>
   <td style="text-align:left;"> $AAPL  thanks bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 05:00:04 </td>
   <td style="text-align:left;"> $AAPL 173.50 next level baby!! BTFD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:51 </td>
   <td style="text-align:left;"> $AAPL 

Ripping faces baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:47 </td>
   <td style="text-align:left;"> $AAPL cover while you can, tomorrow a ripper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:43 </td>
   <td style="text-align:left;"> $AAPL wow thought it was gonna close red and tomorrow green. It proved me wrong damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:40 </td>
   <td style="text-align:left;"> $AAPL bullish AF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:38 </td>
   <td style="text-align:left;"> $AAPL THERE IS A GOD AND HE LISTENS TO MY PRAYERS WOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:37 </td>
   <td style="text-align:left;"> $AAPL The goal is 185 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:36 </td>
   <td style="text-align:left;"> $AAPL good job apple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:33 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:33 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG Green on the day!!
Along with $QQQ. An amazing reversal that not a lot of people expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:27 </td>
   <td style="text-align:left;"> $AAPL   🍏😎👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:24 </td>
   <td style="text-align:left;"> $AAPL wow major rug pull on bears today…paper hands got scammed big time today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:21 </td>
   <td style="text-align:left;"> $AAPL ok close now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:21 </td>
   <td style="text-align:left;"> $AAPL 190 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:19 </td>
   <td style="text-align:left;"> $AAPL GREEEEEEEEEEN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:06 </td>
   <td style="text-align:left;"> $AAPL wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:59:01 </td>
   <td style="text-align:left;"> $AAPL downtrend over!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:58:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Seeing a lot of pumpers celebrating across the board to me this is a BIG red flag especially right before powell speaks tomorrow, this looks like distribution before the dump. Added puts before the close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:58:44 </td>
   <td style="text-align:left;"> $AAPL Green baby Green BOOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:58:00 </td>
   <td style="text-align:left;"> $AAPL has an average volume of 96877000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:57:39 </td>
   <td style="text-align:left;"> $AAPL green by close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:57:16 </td>
   <td style="text-align:left;"> $AAPL entire day was a buying opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:57:00 </td>
   <td style="text-align:left;"> $AAPL holy sh!t, we&amp;#39;re going to finish green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:56:45 </td>
   <td style="text-align:left;"> $AAPL   🍏 “🐐”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:56:25 </td>
   <td style="text-align:left;"> $AAPL 

Lets crack skulls baby!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-11 04:56:06 </td>
   <td style="text-align:left;"> $AAPL boo ya jim </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:03:25 </td>
   <td style="text-align:left;"> ;) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:03:13 </td>
   <td style="text-align:left;"> $TSLA WAY too much bear chatter tonight. As I said last night, it will be higher again tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:03:07 </td>
   <td style="text-align:left;"> SOME PLAYS POSTED TODAY 🏆🔥 :
$ADBE $ACN $SPY $TSLA $NFLX 

https://rooms.stocktwits.com/checkout/4451239/prod_KEH7byRXcPlJ63 👈🏻 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:02:37 </td>
   <td style="text-align:left;"> :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:00:38 </td>
   <td style="text-align:left;"> $TSLA Tesla’s smart investors don’t care about weekly or monthly ups and downs!Let weekly options and put buyers worry for that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:00:35 </td>
   <td style="text-align:left;"> $TSLA when moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:00:20 </td>
   <td style="text-align:left;"> $TSLA 
Sorry bears and shorts, TSLA has put in it&amp;#39;s lows for all of 2022. 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 10:00:06 </td>
   <td style="text-align:left;"> $TSLA 539.48 ????????????????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:59:26 </td>
   <td style="text-align:left;"> $TSLA 7 times she tied to break above 1208.  If Q4 earning doesn&amp;#39;t helps it break that level.  The abyss it will go. Thought anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:59:24 </td>
   <td style="text-align:left;"> $TSLA Literally all the market drama today and I just drove my mode 3  chilled with my friends and snowboarded and this shit got knocked down like 5 bucks cheaper where the last dip was at 985 where I bought. And now back up Y’all funny </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:57:49 </td>
   <td style="text-align:left;"> $TSLA These Tesla calls were alerted in the discord and ended up running to 55.30!🔥
Join the free discord team and start banking with us! Link in bio!🚨💰
 (1st 100 members are free) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:56:48 </td>
   <td style="text-align:left;"> $TSLA futures down LOLLLL. So Tesla down tmrw easy AHHAHAH THANKS
BULLS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:56:42 </td>
   <td style="text-align:left;"> $TSLA Don’t pay attention and give any credit to any call or put options buyers all they care is their weekly profit they don’t care about Company and what their true investors gain or lose. Just do your investment based on a wide fundamentals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:56:37 </td>
   <td style="text-align:left;"> $TSLA BULL TRAP!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:56:06 </td>
   <td style="text-align:left;"> $TSLA $AMZN get out asap. J powell will tank the market tomorrow. You&amp;#39;ve been warned. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:55:35 </td>
   <td style="text-align:left;"> $TSLA $AMZN I hope none of you feel for today&amp;#39;s OBVIOUS bull trap... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:53:33 </td>
   <td style="text-align:left;"> $TSLA this is why TSLA carries my portfolio DCA and holding for over 2 yrs.  Seen too many shorts and bears come and go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:53:28 </td>
   <td style="text-align:left;"> $TSLA 

There was likely a big take down effort by MS and Goldman to bring the stock down. Then they give their price target raise. Bunch of bull but the only way retail wins is by buying the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:53:02 </td>
   <td style="text-align:left;"> $TSLA I like the stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:51:39 </td>
   <td style="text-align:left;"> $TSLA Fed Powell testifies Tuesday, &amp;amp; his  prepared remarks are out 
https://www.fxstreet.com/news/federal-reserve-jerome-powell-testifies-tuesday-prepared-remarks-out-202201102210  
 
 No market reaction to these prepared remarks, as investors are &amp;quot;already priced&amp;quot; for a faster QE tapering and for (Pending) QT rate hikes  
 
(Futures flat/red in Tues Asia) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:50:36 </td>
   <td style="text-align:left;"> $AMD $nvda  $intc   $tsla   $Aapl 
https://seekingalpha.com/article/4478841-amd-ces-2022-shows-why-its-just-getting-started?messageid=2800&amp;amp;utm_campaign=4478841&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=RTA+Article+Smart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:44:59 </td>
   <td style="text-align:left;"> $TSLA that’s what Jerome Powell said this evening is there any bull friend who can interpret his words in a best investing strategy for a short and long term? Thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:44:11 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $AMD The 10 year Treasury yield seems to cap at 1.8 and have rotated down 0.51%. Bank stocks have rallied for a while. Time for big techs to shine ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:42:46 </td>
   <td style="text-align:left;"> $TSLA Nomination hearing for Chair Jerome H. Powell (His Prepared Speech) http://www.streetinsider.com/Fed/Nomination+hearing%2C+Chair+Jerome+H.+Powell/19443321.html via @Street_Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:42:45 </td>
   <td style="text-align:left;"> $TSLA Don’t buy weekly calls until Wednesday because Jerome Powell’s hearing on Tomorrow and inflation numbers on Wednesday can be so tricky so be patient until the </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:42:35 </td>
   <td style="text-align:left;"> Always interesting to c what the retail investor is up to. See if there is an actionable edge in their patterns.

In Dec @TipRanks users bought the following top 10 stocks
DIS $AAPL $TSLA $NVDA FB MSFT PYPL BABA $AMZN 

$NIO becoming a favorite 
More👉 https://bit.ly/3zuZRep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:41:13 </td>
   <td style="text-align:left;"> $TSLA putting deposit on 25k car whenever we can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:40:53 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:40:04 </td>
   <td style="text-align:left;"> $TSLA I predicted right that today would be up but I’m not sure about Tomorrow and Wednesday. But next week will be up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:38:52 </td>
   <td style="text-align:left;"> $TSLA  
 
Shorts ! Up 10 Points  
 
 
Tesla Texas factory opens up next week. Tesla Giga Berlin and Texas will ramp up on Model Y 10 days 
 
Musk lectures on Cybertruck &amp;amp; 25K  sports car timeline (When they hit the road) on 01-26-22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:38:11 </td>
   <td style="text-align:left;"> Tesla FSD Beta Offers New Modes to Choose the Driving Style

Drivers can now select from the “Chill,” “Average,” and “Assertive” modes to choose the driving style that is most comfortable for them

$TSLA
 https://www.tesmanian.com/blogs/tesmanian-blog/tesla-fsd-beta-provides-new-driving-profiles-depending-on-which-ai-will-act-during-driving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:37:36 </td>
   <td style="text-align:left;"> $TSLA I keep wimping out. I have ptsd from my losses last year haha augh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:37:34 </td>
   <td style="text-align:left;"> $TSLA 
TSLA could carry the Whole Market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:36:17 </td>
   <td style="text-align:left;"> $TSLA would love to see an open above 1080. Around 1085. So we can dip to 1080 and bounce to 1100. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:35:39 </td>
   <td style="text-align:left;"> Morgan Stanley&amp;#39;s Adam Jonas hikes his PT to $1,300 from $1,200 while maintaining his Overweight rating, citing Q4 deliveries that came in 20% above his forecast.

$TSLA
 https://seekingalpha.com/news/3786906-tesla-pt-raised-to-1300-by-morgan-stanleys-jonas-after-q4-unit-beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:35:30 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:35:08 </td>
   <td style="text-align:left;"> $TSLA | named a top stock pick for 2022 at Goldman Sachs

$TSLA | price target raised from $1200 to $1300 at Morgan Stanley </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:35:03 </td>
   <td style="text-align:left;"> $TSLA MS says 1300!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:34:27 </td>
   <td style="text-align:left;"> $TSLA if I was a bear and have puts overnight tonight....Its gonna be a long night and PM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:34:19 </td>
   <td style="text-align:left;"> Ticker: $TSLA 
Buy: January 14, 2022 $1060.00 Calls 
Entry Price: $30.20 - $30.40 
Exit Price: $33.52 
Stop Loss: $26.58 
Potential ROI: 11% 
Estimated Hold Time: 60 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:33:51 </td>
   <td style="text-align:left;"> $TSLA Morgan Stanley PT raise $1300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:33:30 </td>
   <td style="text-align:left;"> $TSLA went out tonight ! Met bear at the bar ! Lost his pants! 
Unbelievable! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:33:28 </td>
   <td style="text-align:left;"> $TSLA Bull flag forming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:33:24 </td>
   <td style="text-align:left;"> Tesla signs deal to source nickel for battery production from upcoming new mine in the US - Electrek

$TSLA
 https://electrek.co/2022/01/10/tesla-signs-deal-source-nickel-battery-production-upcoming-new-mine-us/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:33:07 </td>
   <td style="text-align:left;"> $TSLA Bears are OUT OF CREDITS

                   G A M E   O V E R </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:32:14 </td>
   <td style="text-align:left;"> $TSLA Fed Powell vows to prevent inflation from becoming &amp;#39;entrenched&amp;#39;  
http://www.streetinsider.com/Fed/Feds+Powell+vows+to+prevent+inflation+from+becoming+entrenched/19443294.html   
&amp;quot;The economy has rapidly gained strength despite the ongoing pandemic, giving rise to supply-and-demand bottlenecks, and thus to elevated inflation&amp;quot; (Powell speaks Tuesday) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:32:12 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-10 Options Analysis Video: 
https://www.youtube.com/watch?v=VICHyTfsKZs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:31:58 </td>
   <td style="text-align:left;"> $TSLA simply amazing they took a market on brink of giving out to a halt into a total V. All in the same day. This market just finds new absurd ways to move. Big win for bulls today. Congrats. 

 Be interesting what happens tomorrow. See if it was just another criminal pump before powell speaks. This whipsaw price action isnt healthy but to each their own. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:31:39 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:31:37 </td>
   <td style="text-align:left;"> $TSLA has anyone modified the kid CyberQuad yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:31:22 </td>
   <td style="text-align:left;"> $TSLA perfect set up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:31:16 </td>
   <td style="text-align:left;"> $TSLA anyone want a CyberQuad for kids near HTX ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:30:58 </td>
   <td style="text-align:left;"> $TSLA Final tabulation for after hours.  Shorts loaded up in the After Hours and the Dark Pool volume was up overall today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:30:53 </td>
   <td style="text-align:left;"> $TSLA easy long.  Don’t be a dumb bear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:30:02 </td>
   <td style="text-align:left;"> $TSLA $NVDA $AMD futures struggling again , not looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:29:38 </td>
   <td style="text-align:left;"> $TSLA Easy short soon. Please pump it higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:29:22 </td>
   <td style="text-align:left;"> $TSLA so are we expecting the Chinese delivery numbers for Dec tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:27:50 </td>
   <td style="text-align:left;"> $MCO2.X 

This is not a crypto this is a 1 ton of carbon credit - packed into a coin with a current supply of only 2.8 million 

able to be burnt to offset Corporate emissions…this has not once traded at its true value which must at a 

MINIMUM be $360 that’s what $TSLA got for the 5 million metric tons they sold for 1.6 Billion 

Given we have 2.8 million currently trading we should have a MINIMUM market cap of 
1.008 BILLION - currently trading at a market cal of 23 million 

Don’t let them fool you highly manipulated big money does not want this to trade at true market value $BTC.X 2009 opportunity lives right here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:25:06 </td>
   <td style="text-align:left;"> $MINE.CA $CNIKF $TSLA 

#Nickel price buoyed by strong EV demand, dwindling stocks:
https://financialpost.com/pmn/business-pmn/nickel-price-buoyed-by-strong-demand-dwindling-stocks #BatteryMetals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:23:17 </td>
   <td style="text-align:left;"> $TSLA Tesla needs to be tossed around once in a while, keeps Elon humble.  😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:22:52 </td>
   <td style="text-align:left;"> $TSLA 1000-1200....the shitty zone😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:21:40 </td>
   <td style="text-align:left;"> $TSLA moves like a penny stock!! 9% swing in a day!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:20:58 </td>
   <td style="text-align:left;"> $AMZN $SQ $TWTR $TSLA good reversal in these names today. We need to get over ‘4685.00’ on the $SPX to get a good rally this week… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:19:26 </td>
   <td style="text-align:left;"> $TSLA yes baby love Koreans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:19:10 </td>
   <td style="text-align:left;"> $TSLA when moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:16:27 </td>
   <td style="text-align:left;"> $TSLA pump daddy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:14:53 </td>
   <td style="text-align:left;"> $TSLA pimp this to $1,110 so I can short it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:14:18 </td>
   <td style="text-align:left;"> $TSLA I don&amp;#39;t care if this stock goes up or down. I want to thank you all for making this stock the golden goose to a million dollars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:14:10 </td>
   <td style="text-align:left;"> $TSLA So Much Great News AH Bears Are Fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:13:52 </td>
   <td style="text-align:left;"> Unusual Option Alert on $TSLA $3,020,198 put sweep traded with $2100.0 strike expiring on 2023-01-20. Via: https://www.stockgrid.io/optionsflowcumulativestats/TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:13:39 </td>
   <td style="text-align:left;"> $TSLA $QQQ dont know but I have a feeling these two will tank tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:13:37 </td>
   <td style="text-align:left;"> $tsla
Called Tesla short last week said would break 1000! - The Forecast https://theforecast.co/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:13:03 </td>
   <td style="text-align:left;"> $TSLA Just signed on, bet there are NO bears, huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:12:00 </td>
   <td style="text-align:left;"> $TSLA if the 10 year drops and no fireworks with Powell on the hill lookout! This may be well past 1150+ EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:11:52 </td>
   <td style="text-align:left;"> $TSLA managed to get more at $988 today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:10:30 </td>
   <td style="text-align:left;"> $TSLA  margin’d up to the max $1.97m exposure take me to $2,000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:09:05 </td>
   <td style="text-align:left;"> $TSLA To the people telling me I&amp;#39;m drinking too much Tesla Kool-Aid, I say: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:07:17 </td>
   <td style="text-align:left;"> US dream team would be $TSLA and $MVIS... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:06:55 </td>
   <td style="text-align:left;"> $PLUG Power has to get more web searches!  More popular than $f $tsla and $goog $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:06:40 </td>
   <td style="text-align:left;"> $TSLA  gonna dump these bad boys at the open, prob get a 10 15 dollar pop and down from there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:04:42 </td>
   <td style="text-align:left;"> $TSLA bears checking futures and about to start spreading fear 🤣 even if everything goes red, this will be green with great stuff happening and earnings approaching! Sleep hibernate well 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:04:26 </td>
   <td style="text-align:left;"> $TSLA No Cathie sale today - what&amp;#39;s going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:04:19 </td>
   <td style="text-align:left;"> $AABB You can&amp;#39;t go back in time and buy $TSLA at 4$ in penny stock land or $BTC.X at .0002 in 2010 $NFLX $AMZN all had penny stock infancy stages. Today is a different story but still the same opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:03:41 </td>
   <td style="text-align:left;"> $TSLA $1140 WED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:03:35 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-10 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=CbI0bnxyN6E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:03:25 </td>
   <td style="text-align:left;"> $TSLA good close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:02:45 </td>
   <td style="text-align:left;"> $SPY $UBER $TSLA time to get piss drunk and watch futures half the night cheering on my Uber calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:01:27 </td>
   <td style="text-align:left;"> $TSLA it’s weird this is 4% green on a day where SPY was almost -2% at one point. Yeah it recovered but didn’t go green like tesla.

Witchcraft. Still bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:01:10 </td>
   <td style="text-align:left;"> $TSLA haha nerds . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 09:00:51 </td>
   <td style="text-align:left;"> $TSLA $SPY $V $amd $LCID   huge100- 200 percent gainer today. Called in the live session and recorded on the spreadsheet. Hit the follow and join for my option entries , exits and stops! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:59:11 </td>
   <td style="text-align:left;"> $TSLA We all know they have to throw a green day in there.  Five days of red is out of the ordinary.  How many people were stupid enough to take the bait and buy $1000 and $1100 calls today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:58:15 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:57:50 </td>
   <td style="text-align:left;"> $TSLA Dear Elon, Can you adopt me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:55:18 </td>
   <td style="text-align:left;"> $TSLA can’t hold up
Forever. No demand. Just sloppy crypto kid call slappers. 
 https://www.reddit.com/r/Epic_Economics/comments/s0ztj4/dip_buyers_got_caught_nas100_to_continue_selloff/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:54:56 </td>
   <td style="text-align:left;"> https://youtu.be/oBApsJ61o0c Another attempt of the 1150 spot?  $TSLA ww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:52:20 </td>
   <td style="text-align:left;"> $TSLA UP ALMOST 4 PERCENT WHILE $SOFI IS DOWN 3 PERCENT ! 
LISTEN AND LEARN INSTEAD OF BRAGGING ABOUT YOUR WRONG PREDICTIONS!! 🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:52:18 </td>
   <td style="text-align:left;"> $TSLA futures dropping. Cramer said giving it back tomorrow in his evening session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:51:52 </td>
   <td style="text-align:left;"> $TSLA  you can&amp;#39;t use logic with TSLA shorts.  They don&amp;#39;t know that language.   You have to yell at them.  They need to be disciplined forcefully.  Remember, it&amp;#39;s for their own good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:51:48 </td>
   <td style="text-align:left;"> latex56d6d9513783eee40cb7df1d121adf29NIO
$F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:50:57 </td>
   <td style="text-align:left;"> $TSLA Tesla (TSLA) granted special approval from Bradenburg State Environment to build 2,000 Model Y bodies at Berlin Gigafactory, according to electrek </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:50:55 </td>
   <td style="text-align:left;"> $RIDE $RIVN $TSLA   All mentioned here $latex4b21cb0eb26935fc1540bd87cedca6e0BMY 56c 60%
@MommasOptions 
$AAPL 177.5c 90% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:47:34 </td>
   <td style="text-align:left;"> $TSLA People who
Make more noise here are not true investors they are either weekly call or put options buyers who fucked the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:47:29 </td>
   <td style="text-align:left;"> $TSLA Morgan Stanley $1,300 PT upgrade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:47:19 </td>
   <td style="text-align:left;"> $TSLA $1120 close tomorrow, just my take. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:46:50 </td>
   <td style="text-align:left;"> $TSLA  there is only one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:46:22 </td>
   <td style="text-align:left;"> $TSLA If you think the big boys will not close this above 1150 by Monthly options expiration, you are just not reading things right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:46:15 </td>
   <td style="text-align:left;"> $TSLA Technical Analysis Bull or Bear 1.10.2022 
https://www.stockbookie.com/tsla-daily-video-1-10-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:45:34 </td>
   <td style="text-align:left;"> Tesla Strikes Battery-Metal Deal in Push to Ensure Supply $TSLA https://youtu.be/3tCPrTr3dSg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:44:24 </td>
   <td style="text-align:left;"> $TSLA still holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:44:03 </td>
   <td style="text-align:left;"> $TSLA given green light to build 2,000 Model Y vehicles at Giga Berlin ahead of final environmental approval </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:44:01 </td>
   <td style="text-align:left;"> $TSLA whale buy wall 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:43:28 </td>
   <td style="text-align:left;"> $TSLA aren&amp;#39;t they supposed to release the China sales numbers tomorrow morning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:42:26 </td>
   <td style="text-align:left;"> $TSLA You can always tell the people who got burned of all their money [ Bears } betting against Tesla.....Pathetic bunch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:41:20 </td>
   <td style="text-align:left;"> $TSLA take $1070 now or $1020 tomorrow… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:41:17 </td>
   <td style="text-align:left;"> $TSLA Why you wanna fight the most wealthiest man in the world!!! Lol He will destroy you if you mess with Tesla 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:41:15 </td>
   <td style="text-align:left;"> $TSLA anyone here went &amp;quot;all in&amp;quot; on calls toward the end of the day believing we will moooooooon tomorrow 🤣😂? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:41:00 </td>
   <td style="text-align:left;"> $TSLA has an Altman-Z score of 23.66, meaning it is financially healthy with little risk of bankruptcy. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:40:58 </td>
   <td style="text-align:left;"> $TSLA HUGE GAINS MADE HERE!💰🔥
Join the free discord team and start banking with us!💰
(first 100 members are free)
Link in bio!💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:40:33 </td>
   <td style="text-align:left;"> $TSLA when all stocks fell Tesla yelled HODL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:40:25 </td>
   <td style="text-align:left;"> $TSLA Tesla PT raised to $1,300 by Morgan Stanley&amp;#39;s Jonas after Q4 unit beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:40:04 </td>
   <td style="text-align:left;"> $TSLA made a couple intraday flips today. Didn’t hold anything overnight. It’s been unstable the last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:39:38 </td>
   <td style="text-align:left;"> $TSLA last stock standing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:37:02 </td>
   <td style="text-align:left;"> $VOO $SPY $TSLA $BTC.X https://youtu.be/UsW009ltnnU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:36:56 </td>
   <td style="text-align:left;"> $TSLA silly bulls. Market future red ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:36:29 </td>
   <td style="text-align:left;"> $TSLA 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:36:23 </td>
   <td style="text-align:left;"> $TSLA this market is entertaining right now to say the least.. interesting times for sure right now!!!! All I know is there’s a lot of people “ALL IN “on this. This kind of market can bring you right to your knees.
Feels kinda good just to sit back and watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:35:01 </td>
   <td style="text-align:left;"> $TSLA The only thing that can stop this one is JPOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:34:55 </td>
   <td style="text-align:left;"> $TSLA any idea what Powell going to say? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:34:45 </td>
   <td style="text-align:left;"> $TSLA Hey Brandon, if you’re on here, you should read this.  I learned it in college Macroeconomics as I’m sure you did too.  Jpow shouldn’t have to fix your incompetence with rate hikes.🙄

https://en.wikipedia.org/wiki/Demand-pull_inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:34:19 </td>
   <td style="text-align:left;"> $TSLA tomorrow opens at 1077-1080 and stays there whole day… then boom $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:34:13 </td>
   <td style="text-align:left;"> $TSLA Powell sippin’ Hennesy, before putting the final nail to the coffin of bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:34:10 </td>
   <td style="text-align:left;"> $TSLA why is future down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:34:03 </td>
   <td style="text-align:left;"> $TSLA bears are SHARTING down their legs right now. Gonna be like that through earnings! WAY too many catalysts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:33:33 </td>
   <td style="text-align:left;"> $QQQ $TSLA People looking at futures are just plain stupid. Yesterday futures were super green just to become red in pre-market. Today futures were hella red in pre-market just to end up green for the day. Futures don&amp;#39;t mean sh!t. PT tomorrow $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:33:10 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AMZN $AAPL Jpow going to say, we pumped too much need to raise rates now!!! 

In other news, a local grocery store Nob Hill is closing a store as employees reported. Parent company Raleys have not answered. More jobs lost....😕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:33:07 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $ETH.X just go ahead and announce you’ll accept btc and eth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:33:02 </td>
   <td style="text-align:left;"> $TSLA this could go to $1400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:33:01 </td>
   <td style="text-align:left;"> $TSLA MS upgrade on TESLA, oh boy shorts, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:32:22 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-10 Technical Analysis Video: 
https://www.youtube.com/watch?v=VuKNACtuBlc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:32:11 </td>
   <td style="text-align:left;"> $CLOV Holy hell this is a buy, investors freaked out over a MCR of 102% when it it 94% normalized? So many mature insurers run MCR above 100%. MCR should go back to 94% after Q1. Should have a profitable year this year. Will probably have a book value above it&amp;#39;s current share price end of 2023. Let&amp;#39;s see $AAPL $TSLA or $MSFT get a BV anywhere near their current market cap in the next decade or ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:31:21 </td>
   <td style="text-align:left;"> $TSLA take $1072 or panic at $1020 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:31:09 </td>
   <td style="text-align:left;"> $TSLA in the clouds. Grab a parachute. 
 https://www.reddit.com/r/Epic_Economics/comments/s0zbaq/futures_crypto_turn_for_the_downside_cash_hunters/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:30:47 </td>
   <td style="text-align:left;"> What a crock of bs Monday was re indices rally post face plant.  Regardless, moving forward ... incoming crash Tuesday  ... 10:00 a.m. ...
Testimony -- Chair Jerome H. Powell ... Watch Live ... Hearing ... Before the Committee on Banking, Housing, and Urban Affairs, U.S. Senate ... https://www.federalreserve.gov/newsevents/calendar.htm  $tsla $f $ccl  $spy $qqq and more 🐻❤😈✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:30:18 </td>
   <td style="text-align:left;"> $TSLA Tesla ⚡️Energy  ???  Maybe have a power plant that can funnel electricity to the power grid so Tesla clients can purchase at a premium price to bring down cost… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:29:30 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA Let’s fucking go Elon. I’ll be purchasing a coupe teslas when we’re all said and done here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:29:23 </td>
   <td style="text-align:left;"> $TSLA going red LOL future red LOLLLLL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:28:50 </td>
   <td style="text-align:left;"> $TSLA wtf why is this up for no reason? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:26:02 </td>
   <td style="text-align:left;"> $TSLA Another thing.  They know people were wiped last week and the vast majority of retail are buying call options.  Bulls are running scared and have shifted from buying deep OTM Calls to ITM calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:25:47 </td>
   <td style="text-align:left;"> $TSLA are we going to moon tomorrow on the &amp;quot;rumor&amp;quot; of Teslabot or is Musk waiting to first wrap up the pending DOJ investigation on him and the company? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:24:14 </td>
   <td style="text-align:left;"> $TSLA PT for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:24:12 </td>
   <td style="text-align:left;"> latexc67591ca44a085e56f396be9343dfaf5AMD - 60% put flow
$NVDA - 62% call flow

#optionsflow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:22:30 </td>
   <td style="text-align:left;"> $TSLA Guesses for earnings?  I&amp;#39;m betting $2.50 a share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:22:21 </td>
   <td style="text-align:left;"> $TSLA deeks hard from today’s call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:22:00 </td>
   <td style="text-align:left;"> $TSLA They set up guys up.  They will take  out the #1 selling calls today, tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:21:11 </td>
   <td style="text-align:left;"> $TSLA Tesla securing supply chain for materials while every other company is waiting for Brandon to do something.  Maybe JPow will mention that instead of hiking rates.  There are other ways to slow inflation such as having a basic understanding of supply and demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:20:10 </td>
   <td style="text-align:left;"> $TSLA $TSLA always comes out being a Dawg. This stock rocks rocks rocks. I get so excited. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:20:09 </td>
   <td style="text-align:left;"> $SPY. 🥺
$qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:19:35 </td>
   <td style="text-align:left;"> $GME $AMC $TSLA  $BTC.X $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:18:50 </td>
   <td style="text-align:left;"> $TSLA BROTHER IN ARMS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:17:53 </td>
   <td style="text-align:left;"> $TSLA sell sell sell LOLLLLL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:17:38 </td>
   <td style="text-align:left;"> $TSLA is buying Nickel from $TLOFF $TLO.CA 

https://finance.yahoo.com/news/tesla-signs-deal-first-u-211115605.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:17:28 </td>
   <td style="text-align:left;"> $TSLA muahahahaha.  I smell a massive bull trap!!!! Never trust analysts, Dummies! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:16:59 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Trending on Twitter the last 24hrs - seeing some movement on stocktwits as well. Keep an eye on what people are saying across social media - especially before market open tomorrow morning. Check it out here. https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220110 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:16:35 </td>
   <td style="text-align:left;"> $TSLA The best process is no process.
The best part is no part.
And the best short is short shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:16:20 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:15:21 </td>
   <td style="text-align:left;"> $TSLA HEHE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:14:45 </td>
   <td style="text-align:left;"> $TSLA rallied over 8% today from session lows - insane $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:14:05 </td>
   <td style="text-align:left;"> $TSLA This stock is a lunatic asylum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:13:51 </td>
   <td style="text-align:left;"> $TSLA Predictions for tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:13:11 </td>
   <td style="text-align:left;"> $TSLA 😌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:12:48 </td>
   <td style="text-align:left;"> $TSLA   J Powell talks tomorrow, Inflation data tomorrow and Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:12:28 </td>
   <td style="text-align:left;"> $TSLA big boner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:12:19 </td>
   <td style="text-align:left;"> $TSLA literally sold 4 1100 calls today to secure capital…. The pain lol 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:12:12 </td>
   <td style="text-align:left;"> $TSLA No Nut January if 1200$ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:11:43 </td>
   <td style="text-align:left;"> $TSLA if it closes above 1070 i will not jerk off for a week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:11:32 </td>
   <td style="text-align:left;"> $TSLA 950 tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:11:22 </td>
   <td style="text-align:left;"> $TSLA fun fact : one rotation of a wind turbine would provide enough energy for a Tesla to go 200 miles 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:10:35 </td>
   <td style="text-align:left;"> $TSLA gonna run now. Right into a split!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:10:27 </td>
   <td style="text-align:left;"> $DWAC $CFVI $FB $TWTR $TSLA  LGB Takes a Lie Detector Test! https://www.youtube.com/watch?v=aYrQp90w5-M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:10:14 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:08:27 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:08:12 </td>
   <td style="text-align:left;"> $NIO Cramer said no to NIO because they&amp;#39;re in communist China but said buy as much of the $DIDI IPO as possible. How did that work out?

He said don&amp;#39;t buy the $TSLA IPO in 2010 and said to sell in 2013. And said Elon should leave the company in 2018. How did that work out?

He&amp;#39;s pumper who loves stocks that have made major moves and bags on the ones that are down. Buy high sell low is the Cramer MO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:06:58 </td>
   <td style="text-align:left;"> $TSLA boys at JP and GS loaded up and has told JPow what to say tomorrow to rocket this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:06:41 </td>
   <td style="text-align:left;"> $TSLA stock analysis after a big drop and recovery 

https://youtu.be/OQkp28DZCjQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:06:11 </td>
   <td style="text-align:left;"> $QQQ $NVDA $AMZN $TSLA QQQ 383 is a key level. It is the summit of the early September pivot high, as well as the approximate location of the 100 day moving average. We are currently sitting around 380. 
If we break decisively above, I believe that the tech pullback is over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:05:59 </td>
   <td style="text-align:left;"> $TSLA Man cant believe my calls got stopped today. Got 1120 calls for 2.80. Was up 50% so raised to b/e. Stopped me out then now it&amp;#39;s at $8. Probably $15 tomorrow. FML!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:05:53 </td>
   <td style="text-align:left;"> $TSLA Stocks and currencies at a higher price. Huge profits coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:05:47 </td>
   <td style="text-align:left;"> $TSLA All I suggest to true Bulls stay off weekly calls for this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:05:36 </td>
   <td style="text-align:left;"> $TSLA They know $TSLA will deliver great ER so it’s time to push $TSLA up now. 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:05:29 </td>
   <td style="text-align:left;"> $TSLA told ya… damn good ah fuckin up 13+ points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:05:22 </td>
   <td style="text-align:left;"> $TSLA swinging one Enron worth of market cap on a daily basis... Efficient markets. $TSLAQ #GigaFraud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:04:56 </td>
   <td style="text-align:left;"> $TSLA 1085-1100 open tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:04:23 </td>
   <td style="text-align:left;"> $TSLA to all my bull fellas. I am watching CPI numbers on Wednesday closely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:04:06 </td>
   <td style="text-align:left;"> $TSLA what time does Musk secretly unload shares through his off-shore LLC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:03:33 </td>
   <td style="text-align:left;"> $TSLA You can buy calls and puts and make money I would be so happy for that but don’t be a dishonest bitcch for money ! I believe that you should not hammer a successful company. See lots of people here hammer Tesla for days for their put options and day after praise Tesla for their call options! You just stink so bad ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:02:23 </td>
   <td style="text-align:left;"> $TSLA my shares and options are in a Roth. So all my maneuverings are tax free baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:02:19 </td>
   <td style="text-align:left;"> $TSLA will we moon tomorrow because retail is stupid enough to believe crooked analysts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:02:04 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 28.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:01:23 </td>
   <td style="text-align:left;"> $TSLA I had a dream a stock split came idk when but my dreams are visions…  Bull Or Bear WE ALL FINNA EAT Real Soon. #Visionary everybody put your hands in we in this together </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:01:21 </td>
   <td style="text-align:left;"> $TSLA How you feel about the idea that the contents of JPOW speech tomorrow has already been leaked to the big boys....? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:01:03 </td>
   <td style="text-align:left;"> $TSLA earning then stock split. 🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:00:56 </td>
   <td style="text-align:left;"> $TSLA https://seekingalpha.com/news/3786906-tesla-pt-raised-to-1300-by-morgan-stanleys-jonas-after-q4-unit-beat?messageid=2900&amp;amp;utm_campaign=rta-stock-news&amp;amp;utm_content=link-1&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=RTA+News+Smart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:00:28 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AMD $AAPL Funny how the market took a U-turn when Goldman Sachs said they &amp;quot;see&amp;quot; a possible 4 rate hikes this year. Everyone knows predictions from banks are half true most of the time. That&amp;#39;s how they play the retail investors with weak hearts and then buy the dip. Unless FED confirms it during meetings, anything released in between is just FUD. A well played move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 08:00:27 </td>
   <td style="text-align:left;"> $TSLA impressed. Darling of the street and retail! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:59:50 </td>
   <td style="text-align:left;"> $SPY $TSLA $FB $AAPL 

Lots of plays made money today!💰
Come join the free discord team and bank with us! Link in bio!💸💰🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:59:31 </td>
   <td style="text-align:left;"> $TSLA We will provide all the energy for the State of Texas haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:58:54 </td>
   <td style="text-align:left;"> $TSLA has a gap to fill at $939 and $908. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:58:46 </td>
   <td style="text-align:left;"> $TSLA hoping for a good price action tomorrow but with all the sideways trading anything can happen. Preparing to play both sides </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:58:45 </td>
   <td style="text-align:left;"> $TSLA 3 words for you bears:
Bless
Your
Heart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:58:40 </td>
   <td style="text-align:left;"> $TSLA I had an epiphany last week. Yes, I could sell and buy them back later at a lower price. But I would be worse off because of the capital gain tax I would have to pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:57:35 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:57:07 </td>
   <td style="text-align:left;"> $TSLA Seems split is a possibility with this price action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:57:02 </td>
   <td style="text-align:left;"> $TSLA Why sell? to pay more income on your capital gain? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:56:10 </td>
   <td style="text-align:left;"> $TSLA  &amp;amp;RHHNF Dr John Burba 🔋🔋🔋🔋🔋🔋🔋🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:56:07 </td>
   <td style="text-align:left;"> $TSLA 🩳🩳🩳🩳🔥🔥🩳🩳🔥🔥🔥🩳🔥🔥🩳🔥🔥🩳🩳🔥🔥🩳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:55:01 </td>
   <td style="text-align:left;"> $TSLA There are lots of people here who were bearish for last few days now are bullish i hate to be with you guys on the same ship!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:54:42 </td>
   <td style="text-align:left;"> $TSLA sold a little too early? Fml </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:53:42 </td>
   <td style="text-align:left;"> $TSLA Even market can’t crash Tesla, Nasdaq was down 3% and we still ended up being green by 31$, while nasdaq recovered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:52:48 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀

Source: ChrisDungeon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:52:28 </td>
   <td style="text-align:left;"> $TSLA This is no good.  Tsla won’t crash.  It’s bad for the market.  Money is all concentrated here in this meme stock. TLSA is too high.  Elon was saying that.  It must crash!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:51:52 </td>
   <td style="text-align:left;"> $TSLA ...No one cares what Wells Fargo thinks... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:51:49 </td>
   <td style="text-align:left;"> $TSLA when does Fed mins come and inflation report? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:51:43 </td>
   <td style="text-align:left;"> $TSLA flagging on the one minute . Let&amp;#39;s just gap up straight to 1208 in am 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:51:37 </td>
   <td style="text-align:left;"> $TSLA I considered to sell last week, but gave up the idea when I estimate the amount of capital gain tax I would have to pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:51:27 </td>
   <td style="text-align:left;"> $TSLA $RIO https://www.mining.com/tesla-signs-1-5-billion-deal-for-nickel-from-talons-minnesota-project/?fbclid=IwAR3IlvLMsD1OH1TdI7uhNqFRDye069vXpAMzsphXABepyvG3e4w93s-ePGw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:50:25 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:50:16 </td>
   <td style="text-align:left;"> $TSLA Say it with me:

Don&amp;#39;t 
Bet 
Against 
Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:50:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:49:59 </td>
   <td style="text-align:left;"> $TSLA sold some weekly put spreads this morning short the $1000 puts . Let&amp;#39;s keep the pump alive fam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:49:52 </td>
   <td style="text-align:left;"> $TSLA Elon just buy lazr and QS , corner the market already .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:49:17 </td>
   <td style="text-align:left;"> $TSLA LISTEN: PT 1300 is not sell the news.. it’s not profit taking… it’s 5% pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:48:51 </td>
   <td style="text-align:left;"> $TSLA all the way right to the top of our zones like a magnet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:48:16 </td>
   <td style="text-align:left;"> $TSLA who upgrade tsla $1300 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:47:26 </td>
   <td style="text-align:left;"> $TSLA just gonna wait for them to print. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:47:08 </td>
   <td style="text-align:left;"> $TSLA jpow probably has secret button that auto buys tesla calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:47:04 </td>
   <td style="text-align:left;"> $TSLA those who are questioning the feds, they are not stupid to cause harm to the expansion of businesses and their prosperity. I have no doubt they want businesses to flourish and create more jobs! How can you create jobs if you are harming businesses? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:46:59 </td>
   <td style="text-align:left;"> $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:46:50 </td>
   <td style="text-align:left;"> $TSLA Donot short our Tesla cry baby. See you at $1400 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:46:49 </td>
   <td style="text-align:left;"> $TSLA Morgan Stanley raises PT to $1300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:46:44 </td>
   <td style="text-align:left;"> $TSLA 

Tesla 12-month stock price targets:

New Street Research: $1580
Jefferies: $1400
Wedbush: $1400
DZ Bank: $1340
Argus: $1313
Mizuho: $1300
Piper Sandler: $1300
Morgan Stanley: $1300
Deutsche Bank: $1200
Goldman Sachs: $1200
Wells Fargo: $860
Credit Suisse: $830
Cowen: $625 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:46:38 </td>
   <td style="text-align:left;"> $TSLA not much going on here other than 100 million dollars on this week expiration lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:45:54 </td>
   <td style="text-align:left;"> $TSLA By the way all futures are green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:45:34 </td>
   <td style="text-align:left;"> $TSLA ...No one cares what Powell says and no one believes what Powell says... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:45:15 </td>
   <td style="text-align:left;"> $TSLA jpow loading calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:44:23 </td>
   <td style="text-align:left;"> $TSLA well Daggon. What a move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:44:09 </td>
   <td style="text-align:left;"> $TSLA those that think they know anything about Jerome Powell know that he really watches what he says in front of congress. He might even only say he&amp;#39;s gonna raise rates only twice this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:43:54 </td>
   <td style="text-align:left;"> $TSLA  

Tesla is a $1 trillion startup with just 1% market share.
 https://twitter.com/heydave7/status/1480611004014862346?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:43:49 </td>
   <td style="text-align:left;"> $TSLA can’t wait for premarket you think there is still a chance to get in or already ran too much ?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:43:17 </td>
   <td style="text-align:left;"> $TSLA FOMO DAY IS TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:43:16 </td>
   <td style="text-align:left;"> $TSLA Welp looks like that speed bump may be over! LFG!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:43:13 </td>
   <td style="text-align:left;"> $TSLA bears just know, these days I’m playing options, but my share sell limit not less than 1500 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:43:11 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:42:55 </td>
   <td style="text-align:left;"> $TSLA dam I missed out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:42:31 </td>
   <td style="text-align:left;"> $TSLA Wow Go Tesla! Keep pushing higher! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:42:12 </td>
   <td style="text-align:left;"> $TSLA I shot the sheriff but I did shoot the bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:41:38 </td>
   <td style="text-align:left;"> $TSLA 1600 this year want. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:41:09 </td>
   <td style="text-align:left;"> $TSLA trust in my friend JP .. he will change the winds at 10 am.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:41:02 </td>
   <td style="text-align:left;"> $TSLA bears are just lurking and counting the loss and planning to buy more puts, short sellers planning how to exist margin call ☎️ 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:40:46 </td>
   <td style="text-align:left;"> $TSLA I find that the two most recent price target increases come from Goldman Sachs and Morgan Stanley who have both extended Musk hundreds of millions in personal loans. In exchange, Musk has pledged his shares of Tesla as security for these loans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:40:40 </td>
   <td style="text-align:left;"> $TSLA do bull flags mean anything after hours? Or not enough volume to worry about chart signals? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:40:32 </td>
   <td style="text-align:left;"> $TSLA                Recommended  
                  in every investors portfolio  
             
 
This  is the GE of the next generation only much much better! 
owner operator ….there is no better formula  
 
BUY and HOLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:40:30 </td>
   <td style="text-align:left;"> $TSLA $5000+ in 5-10 years still on track. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:39:43 </td>
   <td style="text-align:left;"> $TSLA consolidate, then move $10, then consolidate, again move $10. Repeat till $1300+  ✅🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:39:30 </td>
   <td style="text-align:left;"> $TSLA Bears are so quiet, because they deepthroating that bull’s dick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:39:24 </td>
   <td style="text-align:left;"> $TSLA helps that the two big leagues, Morgan Stanley and Goldman Sachs, increased their price targets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:39:19 </td>
   <td style="text-align:left;"> $TSLA I guess we gapping up big time tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:38 </td>
   <td style="text-align:left;"> $TSLA Bad News Bears got a dick in their mouth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:35 </td>
   <td style="text-align:left;"> $TSLA honestly surprised it held up so well today in the sea of red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:29 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NVDA $AMD $BTC.X yes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:28 </td>
   <td style="text-align:left;"> $tsla whut a difference a 2 years make! 🍿   https://www.cnbc.com/2019/05/21/morgan-stanley-tesla-shares-could-drop-to-10-in-worst-case-scenario.html

❤️🐒🍌.  🖕🐑

❤️👑🌈🦄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:16 </td>
   <td style="text-align:left;"> $TSLA 
Much wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:14 </td>
   <td style="text-align:left;"> $TSLA went gangsta on them 🐻 🐻 
1200 EOM target 🚀 $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:38:05 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:37:39 </td>
   <td style="text-align:left;"> $TSLA gap up the resistance tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:36:39 </td>
   <td style="text-align:left;"> $TSLA open interest put of options are triple or quadruple more than the calls. Y’all know who will get burn by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:36:29 </td>
   <td style="text-align:left;"> $TSLA my calls already 2x before close. Tomorrow&amp;#39;s finna lit ✅🔥. RIP bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:36:15 </td>
   <td style="text-align:left;"> $TSLA i have a friend that sold tesla, he is gay now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:36:09 </td>
   <td style="text-align:left;"> $TSLA 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:35:41 </td>
   <td style="text-align:left;"> $TSLA LOL. $1070 mark arrived as expected earlier

https://twitter.com/mcexplorer4/status/1480625189461409794?t=EpfMwnARZPigZ_eIg_l8Yg&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:35:05 </td>
   <td style="text-align:left;"> $TSLA PT hikes and news after hours 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:35:02 </td>
   <td style="text-align:left;"> $TSLA $90 swing up from the low today...  wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:35:00 </td>
   <td style="text-align:left;"> $TSLA looking at other tech stocks like: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:34:58 </td>
   <td style="text-align:left;"> It&amp;#39;s coming again. Are you ready?

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:32:58 </td>
   <td style="text-align:left;"> $TSLA the movement doesn’t look organic. It looks like they are trying to get it over the 50 day MA which is $1073. Hope they aren’t trying to set a bull trap, this is getting fn ridiculous. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:32:15 </td>
   <td style="text-align:left;"> $AAPL $TSLA $FB $BTC.X  $SPY these Clowns 🤡 should sell Course on Investing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:31:56 </td>
   <td style="text-align:left;"> $TSLA &amp;quot;Yahoo Finance Video 
Tesla stock pares losses on bullish Goldman Sachs note 
Mon, January 10, 2022, 1:52 PM 
https://finance.yahoo.com/video/tesla-stock-pares-losses-bullish-205232224.html&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:31:38 </td>
   <td style="text-align:left;"> $GSAT $TSLA $DISH $AMZN https://twitter.com/KarlGolovin/status/1480683001348599810?t=KL9MvlO7ABp9tKReSxM4VQ&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:31:29 </td>
   <td style="text-align:left;"> $TSLA keep them coming 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:31:27 </td>
   <td style="text-align:left;"> $TLOFF + $TSLA = &amp;quot;partnership&amp;quot; 
 
BIG DEAL 
 
https://twitter.com/LithiumIonBull/status/1480678096734806016?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:31:22 </td>
   <td style="text-align:left;"> $TSLA if you sell you’ll automatically become gay #scientificallyproven </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-11 07:31:06 </td>
   <td style="text-align:left;"> $TSLA this will go back to low by Feb when fed increase the interest rates again </td>
  </tr>
</tbody>
</table></div>

---
