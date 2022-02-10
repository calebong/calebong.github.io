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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Feb-2022-.pdf)

[View the historical Economic Forecasts](https://github.com/calebong/Client-Documents/tree/main/Monthly%20Market%20Outlook)

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



Last Updated: 2022-02-10 09:35:20 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-10 09:30:44 </td>
   <td style="text-align:left;"> Philippines Jobless Rate Edges Higher in December </td>
   <td style="text-align:left;"> The unemployment rate in the Philippines inched up to 6.6 percent in December 2021 from 6.5 percent a month earlier which was the lowest figure since January, amid ongoing disruptions caused by the pandemic. The number of unemployed stood at 3.27 million, up 113 thousand from November's figure of 3.16 million. Meanwhile, the number of employed came in at 46.27 million, up 90.72 thousand from 45.48 million in November. Among employed persons, workers in the services sector made up 56.6 percent of the total, followed by those in the agriculture sector (25.6 percent) and industry (17.8 percent). The labor force participation rate was at 65.1 percent, the highest for the year, which is equivalent to a magnitude of about 910 thousand Filipinos 15 years old and over who were either employed or unemployed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 09:30:00 </td>
   <td style="text-align:left;"> Hang Seng Hits 11-week High </td>
   <td style="text-align:left;"> HK50 increased to a 11-week high of 24987 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60327314?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-10 09:18:28 </td>
   <td style="text-align:left;"> Disney park trips surge after Covid measures eased </td>
   <td style="text-align:left;"> Disney says trips to its US theme parks have surged, while subscriptions to its streaming service beat expectations.                                                                                                                                                                                                      , The company said sales at its domestic attractions climbed above pre-pandemic levels, but warned it expects parks abroad to still be affected by Covid.                                                                                                                                                                   , Meanwhile, Disney+ added 11.8 million subscribers in the last three months of 2021, taking the total to almost 130 million worldwide.                                                                                                                                                                                     , The firm also forecast further subscriber growth for this year.                                                                                                                                                                                                                                                           , Disney+, the company's two-year-old streaming service, helped to keep the business afloat when the pandemic disrupted its legacy theme parks, resorts and cruise operations.                                                                                                                                              , Its latest film Encanto has been hugely popular, with one of its songs We Don't Talk About Bruno making it to number one in the UK top 40 - the first original Disney song to do so.                                                                                                                                      , The boost in sign-ups to Disney+ also suggests that some pandemic-related stay-at-home habits may be sticking, despite concerns after Netflix had warned that its own growth was slowing.                                                                                                                                 , Chief executive Bob Chapek said he believed the streaming service will have 230 million to 260 million subscribers by 2024.                                                                                                                                                                                               , "This marks the final year of the Walt Disney Company's first century, and performance like this coupled with our unmatched collection of assets and platforms, creative capabilities, and unique place in the culture give me great confidence we will continue to define entertainment for the next 100 years," he said., However, even as Disney+ subscribers jumped, executives warned that revenue from cinema releases has yet to recover.                                                                                                                                                                                                      , In contrast, sales at Disney's US amusement parks hit a record in the last three months of 2021.                                                                                                                                                                                                                          , Overall, the company's revenues rose by 34% year-on-year to $21.8bn (£16.1bn) for the quarter, while profits surged to $1.1bn.                                                                                                                                                                                            , Sophie Lund-Yates, equity analyst at Hargreaves Lansdown, said Disney's parks were "doing much better than feared, despite ongoing Covid fears".                                                                                                                                                                          , "Getting customers through the gates is one thing, but being able to sell them mountains of branded food, toys and gifts is what truly makes Disney a remarkable business," she added.                                                                                                                                    , "It's impossible not to be impressed by recent growth in Disney's streaming subscriptions. However, the market cares a great deal about the streaming business, and churning out the levels of growth expected is only going to become a more difficult task.                                                             , "If you didn't get a Disney+ subscription while trying to home-school in lockdowns, chances are you may never get one."                                                                                                                                                                                                   , Separately, Uber announced taxi bookings had rebounded, as people start to put pandemic constraints behind them.                                                                                                                                                                                                          , Uber chief executive Dara Khosrowshahi said his firm's gains showed "just how far we've come since the start of the pandemic".                                                                                                                                                                                            , Uber said overall revenues jumped 83% to $5.8bn, with profits of $892m.                                                                                                                                                                                                                                                   , Shares in both firms rose in after-hours trade.                                                                                                                                                                                                                                                                           , Investigating a rivalry with devastating consequences                                                                                                                                                                                                                                                                     , The ups and downs of life on the wards                                                                                                                                                                                                                                                                                    , Can Jay Blades now, in mid-life, tackle what he failed to learn first time round?                                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/singapore/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 09:15:02 </td>
   <td style="text-align:left;"> Stocks in Singapore Hit 3-1/2-year High </td>
   <td style="text-align:left;"> STI increased to a 3-1/2-year high of 3422 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sri-lanka/tourist-arrivals </td>
   <td style="text-align:left;"> 2022-02-10 09:14:00 </td>
   <td style="text-align:left;"> Sri Lanka Tourist Arrivals Surge 4,794.6% YoY in January </td>
   <td style="text-align:left;"> The number of foreign tourist arrivals in Sri Lanka jumped 4,794.6 percent year-on-year to 82,327 in January of 2022, as soaring vaccinations around the world and loosening COVID-19 restrictions boosted international travel. Russia was the largest source of tourist traffic to Sri Lanka with 16.4 percent of the total traffic, followed by India (14.2%), the UK (9.0%), Germany (6.5%), and France (4.4%). Visitors from Europe became the largest source of tourists to Sri Lanka with 68.8 percent of total arrivals in January, while those of Asia Pacific accounted for 23.7 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 09:12:00 </td>
   <td style="text-align:left;"> Australia Shares Extend Gains on Tech Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index rose 0.4% to around 7,300 on Thursday, extending gains for a third consecutive day as local technology stocks tracked the US tech sector’s overnight surge. Top gainers in the Australian tech sector include Computershare (2.8%), Brainchip (6.3%), Xero (2.2%), Megaport (8.3%) and Appen Ltd (3.5%). Elsewhere, National Australia Bank jumped 4% after reporting a 9.1% rise in first-quarter profit, as growth in home and business lending at the country’s second-biggest lender offset narrower margins. Australian miners also advanced on strong commodity prices, with gains from BHP Group (0.7%), Rio Tinto (2%), Fortescue Metals (4.3%), Mineral Resources (4.2%) and Pilbara Minerals (3.6%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/corn </td>
   <td style="text-align:left;"> 2022-02-10 09:10:40 </td>
   <td style="text-align:left;"> Corn Hits 30-week High </td>
   <td style="text-align:left;"> Corn increased to a 30-week high of 646.5 USd/BU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/neodymium </td>
   <td style="text-align:left;"> 2022-02-10 09:00:14 </td>
   <td style="text-align:left;"> Neodymium Hits All-time High </td>
   <td style="text-align:left;"> Neodymium increased to an all-time high of 1335000 CNY/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/09/entertainment/bob-saget-cause-of-death/index.html </td>
   <td style="text-align:left;"> 2022-02-10 08:50:17 </td>
   <td style="text-align:left;"> Bob Saget's cause of death released - CNN </td>
   <td style="text-align:left;"> (CNN)Bob Saget, who was found dead in his Orlando, Florida hotel room last month, died from the result of a head trauma, according to a statement from his family.                                                                                                                                      , "The authorities have determined that Bob passed from head trauma. They have concluded that he accidentally hit the back of his head on something, thought nothing of it and went to sleep," the statement said. "No drugs or alcohol were involved."                                                    , The family added that they have been "overwhelmed with the incredible outpouring of love from Bob's fans, which has been a great comfort to us and for which we are eternally grateful."                                                                                                                 , "As we continue to mourn together, we ask everyone to remember the love and laughter that Bob brought to this world, and the lessons he taught us all:  to be kind to everyone, to let the people you love know you love them, and to face difficult times with hugs and laughter," the statement added. , The "Fuller House" star, 65, had been on comedy tour at the time of his death.                                                                                                                                                                                                                           , Speculation had swirled around the state of his health as Saget had said he had Covid-19 in December.                                                                                                                                                                                                    , His widow, Kelly Rizzo, told "Good Morning America" during an interview last month that her husband appeared to be in good health prior to his death and that his having Covid in December "was not anything serious."                                                                                   , An autopsy was completed on Saget by the Orange County Medical Examiner in Florida the day after he died.                                                                                                                                                                                                , "At this time, there is no evidence of drug use or foul play," Chief Medical Examiner Joshua Stephany said in a statement to CNN at the time. "The cause and manner of death are pending further studies and investigation which may take up to 10-12 weeks to complete."                                , The Orange County Sheriff's Office released a death investigation report, obtained by CNN, which stated they found no signs of foul play in the "orderly" hotel room.                                                                                                                                    , Saget had been expected to check out of the Ritz-Carlton on Sunday morning and his family members contacted hotel security when they were unable to reach the star, according to the report.                                                                                                             , "Now that we have the final conclusions from the authorities' investigation, we felt it only proper that the fans hear those conclusions directly from us," the family's statement added.                                                                                                                , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 08:44:57 </td>
   <td style="text-align:left;"> US Futures Steady Ahead of Key Inflation Data </td>
   <td style="text-align:left;"> US stock futures were steady on Thursday after the major averages gained further ground in the previous session, as investors digested another batch of corporate earnings results and eyed inflation data due later today for clues on the timing and magnitude of the Federal Reserve's tightening. Contracts tied to the major indices swung between small gains and losses. Shares of Disney jumped 7% in after-hours trading on an earnings beat and after doubling its revenue from its parks, experiences and consumer products division. Uber also gained 5% on strong revenues as the company bounced back from omicron-induced challenges. In regular trading on Wednesday, the Nasdaq Composite jumped 2.08% as tech stocks led the market higher and recouped some losses from the January selloff. The S&amp;P 500 gained 1.45% and the Dow edged up 0.86%. Investors also await Thursday’s inflation data which is expected to show a 7.2% annual gain in January, bolstering the case for a more aggressive Fed tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/private-house-approvals- </td>
   <td style="text-align:left;"> 2022-02-10 08:40:00 </td>
   <td style="text-align:left;"> Australia Private House Permits Drop for 2nd Month </td>
   <td style="text-align:left;"> Private house approvals in Australia dropped by 1.8 percent month-over-month to 10,444 units in December 2021, matching the preliminary reading and following a 1.6 percent fall a month earlier. The series has declined 31.5 percent since the April 2021 peak while remaining at historically elevated levels, with the December result 20.5 percent higher than the pre-pandemic level in December 2019. Approvals were mainly down in New South Wales (-7.9 percent), South Australia (-7.1 percent), Victoria (-1.5 percent), and Queensland (-0.7 percent); while went up slightly in Western Australia (0.8 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/building-permits </td>
   <td style="text-align:left;"> 2022-02-10 08:36:00 </td>
   <td style="text-align:left;"> Australia Building Permits Pick Up in December </td>
   <td style="text-align:left;"> The seasonally adjusted estimate for total dwellings approved in Australia surged 8.2 percent month-over-month to 17,698 units in December 2021, unrevised from the flash figure and quickening sharply from a 2.6 percent gain a month earlier. This was the second straight month of increase in building permits and the strongest pace since March, largely driven by a faster rise in approvals for private sector dwellings excluding houses (27.5 percent vs 13.4 percent in November). Meanwhile, private sector houses remained subdued, falling 1.8 percent following a 1.6 percent decline in November. Across Australia, dwelling approvals rose in New South Wales (32.1 percent), led by dwellings excluding houses and Victoria (2.5 percent); while fell in Queensland (-14.8 percent), Western Australia (-7.7 percent), Tasmania (-7.4 percent), and South Australia (-0.3 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-10 08:26:17 </td>
   <td style="text-align:left;"> Ireland 10Y Bond Yield Hits 35-month High </td>
   <td style="text-align:left;"> Ireland 10 Year Government Bond Yeld increased to a 35-month high of 0.827% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-02-10 08:26:00 </td>
   <td style="text-align:left;"> Soybeans Hits 35-week High </td>
   <td style="text-align:left;"> Soybeans increased to a 35-week high of 1594 USd/Bu, amid supply concerns and as demand remains strong. The world’s largest exporters of processed soy, Argentina and Brazil, have been facing this season hot and dry conditions, which are set to substantially affect the quality and quantity of crops. Brazil is expected to export 7.5 million tonnes of soybeans in February, down from 9.923 million tonnes projected the week prior by farm consultancy ANEC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/producer-prices-change </td>
   <td style="text-align:left;"> 2022-02-10 08:18:18 </td>
   <td style="text-align:left;"> Japan Producer Prices Rise for 11th Month </td>
   <td style="text-align:left;"> Producer prices in Japan rose by 8.6% yoy in January 2022, compared with market consensus of 8.2% and after an upwardly revised 8.7% gain a month earlier. This was the 11th straight month of producer price inflation, amid surging commodity prices. Cost rost further for all commodities:  beverages &amp; foods (3.4% vs 3% in December), transportation equipment (1.8% vs 1.8%), chemicals (12.3% vs 13.5%), petroleum &amp; coal products (34.3% vs 36.6%), non-ferrous metals (26.5% vs 27.2%),  general machinery (1.1% vs 1.5%), iron &amp; steel (25.1% vs 25.8%), machinery (1.4% vs 0.4%), metal products (5.4% vs 5%), other manufacturing industry products (1.4% vs 1.3%), electronic components (1.6% vs 1.3%), electrical machinery (1.6% vs 1.3%), and  information  (0.2% vs 0.1%).  On a monthly basis, producer prices increased  0.6%, aftr an upwardly revised of flat  in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-10/hong-kong-reports-two-covid-deaths-first-in-five-months?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 08:14:15 </td>
   <td style="text-align:left;"> Hong Kong Reports Two Covid Deaths, First In Five Months </td>
   <td style="text-align:left;"> Jinshan Hong                                                                                                                                                                                                                                  , Hong Kong reported two deaths among confirmed Covid patients in the first fatalities in the city in the past five months.                                                                                                                     , A 73-year-old male patient who received two doses of Sinovac Biotech Ltd. inoculations in September, and an unvaccinated 76-year-old male passed away, health officials said in a statement late Wednesday. Both of them had chronic diseases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/current-account </td>
   <td style="text-align:left;"> 2022-02-10 08:12:27 </td>
   <td style="text-align:left;"> South Korea Current Account Surplus Falls by Half </td>
   <td style="text-align:left;"> South Korea’s current account surplus decreased to $6.06 billion in December 2021 from $6.82 billion in the previous month, and was halved from a surplus of $12.06 a year earlier as imports grew at a much faster pace than exports amid higher energy and raw materials prices. The reading markets the 20th straight month of surplus. There was also an $88.3 billion dollar surplus for the full-year 2021, up from $75.9 billion in 2020. The goods account surplus decreased to $4.48 billion, compared to the $10.60 billion figure seen in December 2020. The services account deficit decreased to $0.24 billion, from $0.44 billion in December last year, owing to an improvement in the transport account. The primary income account surplus decreased from $2.59 billion the year previously to $2.47 billion in December 2021. The secondary income account recorded a $0.65 billion deficit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/oil-edges-higher-as-drop-in-stockpiles-outweighs-iran-progress?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 07:45:55 </td>
   <td style="text-align:left;"> Oil Edges Higher as Stockpiles Drop With Focus on Iran Progress </td>
   <td style="text-align:left;"> Ben Sharples                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Oil edged higher in Asian trading after a surprise decline in U.S. crude inventories tightened the market further amid signs of strong demand in the world’s biggest economy.                                                                                                                                                                                                                                                                                              , Futures in New York climbed near $90 a barrel on Thursday after rising 0.3% in the previous session. U.S. crude stockpiles fell by about 4.8 million barrels last week, according to government data, compared with an expected increase in a Bloomberg survey. Investors are also keeping an eye on progress of reviving a nuclear agreement with Iran. A deal that addresses the concerns of all sides is in sight, White House Press Secretary Jen Psaki said Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/new-peloton-ceos-first-company-meeting-crashed-laid-off-workers-report </td>
   <td style="text-align:left;"> 2022-02-10 07:25:29 </td>
   <td style="text-align:left;"> New Peloton CEO's first company meeting crashed by angry laid-off workers: report </td>
   <td style="text-align:left;"> Citron Research founder Andrew Left discusses why he believes Peloton should invest in Blue Apron.                                                                                                                                                   , Peloton's first company-wide meeting since new CEO Barry McCarthy took the helm was shorter than planned on Wednesday, after angry ex-employees recently laid off by the fitness firm decided to join in and share their views according to a report., New Peloton CEO Barry McCarthy speaks during an interview with CNBC on floor of the New York Stock Exchange (NYSE) in New York, U.S., October 28, 2019, when he was CFO of Spotify.  (REUTERS/Brendan McDermid / Reuters Photos)                     , McCarthy was just announced as new CEO by Peloton on Tuesday, and the "All Hands Meeting" was held Wednesday – his first day on the job after former CEO John Foley was asked to step down and the company began laying off some 2,800 people.       , According to CNBC, some of those folks zoom-bombed the comment section during the "All Hands" meeting that included both McCarthy and Foley.                                                                                                         , A logo sign outside of a Peloton retail store in Bethesda, Maryland on April 22, 2020. (Kristoffer Tripplaar/Sipa   /  Peloton.com)                                                                                                                  , PELOTON'S POTENTIAL SUITORS: AMAZON, NIKE, APPLE, DISNEY OR SONY?                                                                                                                                                                                    , "I'm selling all my Peloton apparel to pay my bills!!!," one former employee reported wrote. Another wrote, "This is awfully tone deaf."                                                                                                             , One user said, "The company messed up by allowing people who were fired into this chat," adding that it was now "too late to [moderate] this."                                                                                                       , The outlet reported that McCarthy said he had "no comment" after being asked toward the end of the discussion whether laid-off workers had been allowed into the chat.                                                                               , FILE PHOTO: A Peloton exercise bike is seen after the ringing of the opening bell for the company's IPO at the Nasdaq Market site in New York City, New York, U.S., September 26, 2019.  (REUTERS/Shannon Stapleton / Reuters Photos)                , GET FOX BUSINESS ON THE BY CLICKING HERE                                                                                                                                                                                                             , Peloton did not immediately respond to FOX Business' request for comment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/09/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-10 07:04:18 </td>
   <td style="text-align:left;"> Dow futures rise slightly ahead of key inflation data </td>
   <td style="text-align:left;"> , U.S. stock futures were slightly higher on Wednesday night ahead of key inflation data due Thursday morning.                                                                                                                                                                                                                                                       , Dow Jones Industrial Average futures rose 60 points, or 0.1%. S&amp;P 500 futures and Nasdaq 100 futures were flat.                                                                                                                                                                                                                                                    , Shares of Disney jumped 8% after hours after the company reported a quarterly earnings beat and a doubling of revenue from its parks, experiences and consumer products division. Uber gained 5% in extended trading after reporting a revenue beat and a bounce back from omicron-induced challenges.                                                             , In regular trading, Nasdaq Composite jumped for a second day as tech shares led the market higher and helped it recover some losses from the January sell-off, which was also led by tech names. The Nasdaq jumped 2.08% and the S&amp;P 500 gained 1.5%, while the Dow Jones Industrial Average rose 305.28 points, or 0.86%.                                         , Early pandemic winners of 2022, including Shopify and Etsy, as well as stay-at-home stocks like DocuSign and Zoom, were some of the biggest winners Wednesday.                                                                                                                                                                                                     , "The market seems to have found a more constructive tone in the tug of war between trepidation over the Fed and the better fundamentals that we've seen in both earnings and the economic data," said Art Hogan, chief market strategist at National Securities. "Having Disney do better than Netflix after its earnings report certainly seems to be a positive.", Last month Netflix reported disappointing quarterly earnings, which added to investors skittishness towards tech stocks and the volatility in trading that followed.                                                                                                                                                                                               , Morgan Stanley picks Asia chip stocks that will be in 'pole position' when tech speeds up again                                                                                                                                                                                                                                                                    , Bill Miller says he's thinking about buying Peloton. Here's why                                                                                                                                                                                                                                                                                                    , JPMorgan pegs bitcoin’s value at $38,000, says NFTs are set to dominate digital assets                                                                                                                                                                                                                                                                             , Bond yields, which have surged this year, cooled slightly, perhaps helping boost tech shares. The benchmark 10-year Treasury note traded near 1.945%.                                                                                                                                                                                                              , Investors were also preparing for Thursday's Consumer Price Index report, which is expected to show headline inflation for January at the highest pace since 1982. Core inflation, which excludes food and energy costs and is the Federal Reserve's preferred measure of inflation, is expected to rise by 0.4%, or 7.2% year-over-year.                          , "You'd be hard pressed to find anybody that doesn't believe the CPI number's going to be hot, because we seem to be playing a game of leapfrog, with everyone trying to get more hawkish about what the Fed may or may not do and monetary policy in 2022. That tends to set us up for a continuation of the rally," Hogab said.                                   , Twitter, Coca-Cola and Kellogg are scheduled to report earnings before the opening bell Thursday. Expedia, Affirm and Zillow will report after the closing bell.                                                                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/09/politics/national-archives-justice-department-investigation-trump-white-house-documents/index.html </td>
   <td style="text-align:left;"> 2022-02-10 07:03:42 </td>
   <td style="text-align:left;"> National Archives seeks Justice Department investigation of Trump's handling of White House documents - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)The National Archives has asked the Department of Justice to investigate former President Donald Trump's handling of White House records, according to a source familiar with the matter.                                                                                                                                                             , The source said the Archives is seeking a review of whether Trump violated the Presidential Records Act, which requires that all records created by presidents be turned over to the National Archives at the end of their administrations.                                                                                                                 , It is not clear if the Justice Department will launch a formal investigation, as a vast majority of referrals to the department do not end up sparking a formal investigation. The Justice Department declined to comment.                                                                                                                                  , The Washington Post was first to report the request.                                                                                                                                                                                                                                                                                                        , In a statement Wednesday, the Archives said, "We do not comment on potential or ongoing investigations." The request came after recent revelations that the National Archives had to retrieve 15 boxes of records that had ended up with Trump in Mar-a-Lago and that other documents given to the Archives were torn up and had to be pieced back together., A person familiar with the matter previously told CNN that Archives general counsel Gary Stern contacted Trump's team last fall to inquire about several boxes of records that appeared to have been taken to Mar-a-Lago during Trump's relocation to Florida.                                                                                              , These were boxes that had been in the White House residence and thus had been packed up with other personal belongings of the first family, this person said.                                                                                                                                                                                               , Additionally, some Trump White House documents that have been handed over to the House select committee investigating January 6 had to be taped back together by National Archives staff because they had been ripped up, the agency said in a statement last month.                                                                                        , The Archives, in response to questions from CNN, said that "some of the Trump presidential records received by the National Archives and Records Administration included paper records that had been torn up by former President Trump."                                                                                                                    , The agency did not explain how officials know Trump himself ripped up the records, but the Archives pointed to previous reporting that White House records management staff had to tape together torn-up documents during the Trump era.                                                                                                                    , CORRECTION: A previous version of this story misstated which entity could launch a formal investigation.                                                                                                                                                                                                                                                    , CNN's Gabby Orr, Paul LeBlanc, Ryan Nobles, Zachary Cohen and Annie Grayer contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/09/business/economy/fed-revolving-door-raskin.html </td>
   <td style="text-align:left;"> 2022-02-10 06:57:44 </td>
   <td style="text-align:left;"> Fed nominees commit to not taking part in finance’s revolving door. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                  , Three Federal Reserve picks said that they won’t work in finance for years if they are confirmed to central bank positions.                                                                                                                                                                                                                                    , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                              , Three of President Biden’s nominees to the Federal Reserve committed to lawmakers that, if confirmed to their posts, they would not work in financial services for four years after leaving the Fed.                                                                                                                                                           , The pledge comes amid growing concern about the revolving door between Washington and Wall Street.                                                                                                                                                                                                                                                             , The three potential Fed governors in question — the economists Lisa D. Cook and Philip N. Jefferson and a longtime government official and lawyer, Sarah Bloom Raskin — said they would “commit not to seek employment or compensation” from any financial services company after leaving the board, which oversees the largest banks.                         , Their promises came at the urging of Senator Elizabeth Warren, the Massachusetts Democrat who has criticized the so-called revolving door between government and finance. Fed officials regularly go to work for Wall Street after leaving the institution, making the commitment notable.                                                                     , “These are the strongest ethics standards ever agreed to by Federal Reserve Board nominees,” Ms. Warren said in a statement on Wednesday. “U.S. Senators and the American people can be confident that these public servants will make sound economic policy decisions in the public’s best interest.”                                                         , Republicans have been questioning Ms. Raskin’s nomination by highlighting her stint on the board of directors for a financial technology company, Reserve Trust.                                                                                                                                                                                               , The company got a critical account with the Fed — known as a master account — while Ms. Raskin was on the company’s board. The account provided the firm with advertisable benefits, like access to the Fed’s payments system.                                                                                                                                 , During her confirmation hearing before the Senate Committee on Banking, Housing and Urban Affairs last week, senators questioned whether she had used her previous positions at the Fed and Treasury to help secure the account. Ms. Raskin did not confirm or deny whether she had been in touch with the company’s local Fed bank while she sat on its board., The Federal Reserve Bank of Kansas City, which approved the master account, has said that it “did not deviate from its review process in evaluating this request.”                                                                                                                                                                                             , Senator Patrick J. Toomey, Republican of Pennsylvania, asked Ms. Raskin to respond in writing by Wednesday about the Reserve Trust situation.                                                                                                                                                                                                                  , Ms. Raskin, in her response, said she did “not recall any communications I made to help Reserve Trust obtain a master account. Had I done so, I would have abided by all applicable ethics rules in such communications.”                                                                                                                                      , Amanda Thompson, the communications director for Republicans on the Banking Committee, called those responses a “case of selective amnesia.”                                                                                                                                                                                                                   , The White House has continued to stand behind its nominees. Christopher Meagher, a spokesman for the White House, called the Republican questioning “smears” and said that they “continue to fall flat in the face of scrutiny and facts.”                                                                                                                     , Dr. Cook, Dr. Jefferson and Ms. Raskin are up for confirmation alongside Jerome H. Powell — who Mr. Biden renominated to be Fed chair — and Lael Brainard, a Fed governor who is the Biden administration’s pick for vice chair.                                                                                                                               , Senator Sherrod Brown, Democrat of Ohio and the chairman of the Banking Committee, said last week that all five candidates would face a key committee vote on Feb. 15.                                                                                                                                                                                         , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/credito-real-falls-into-default-after-failing-to-pay-swiss-bond?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 06:54:28 </td>
   <td style="text-align:left;"> Credito Real Defaults After Bid to Raise Cash Falls Short </td>
   <td style="text-align:left;"> Sydney Maki                                                                                                                                                                                                                                                          ,  and Michael O'Boyle                                                                                                                                                                                                                                                 , Credito Real SAB was declared in default by Fitch Ratings after the Mexican payroll lender failed to come up with the cash to pay off a maturing bond.                                                                                                               , The troubled company had said earlier in the day that it wasn’t able to secure a loan that would have allowed it to refinance the debt, a 170 million Swiss franc ($184 million) note. It hired DLA Piper and FTI Consulting to help evaluate restructuring options.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/no-relief-coming-on-u-s-chicken-inflation-pilgrim-s-pride-says?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 06:43:19 </td>
   <td style="text-align:left;"> No Relief Coming on U.S. Chicken Inflation, Pilgrim’s Pride Says </td>
   <td style="text-align:left;"> Michael Hirtzer                                                                                                                                                                                                                                                                                                                                      ,  and Kim Chipman                                                                                                                                                                                                                                                                                                                                     , Expensive chicken isn’t going away anytime soon, according to Pilgrim’s Pride Corp., the second-biggest U.S. producer.                                                                                                                                                                                                                               , The Colorado-based company is being squeezed by higher costs and labor shortages. At the same time, U.S. production isn’t growing fast enough to meet soaring demand. Pilgrim’s sales to grocery stores are exceeding pre-pandemic levels. It all points to elevated prices continuing in the near future, the company said in a statement Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/shale-pioneer-continental-crashes-after-founder-cuts-stake?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 06:42:22 </td>
   <td style="text-align:left;"> Shale Billionaire Hamm Hands Most of His Stock to 5 Children </td>
   <td style="text-align:left;"> Harold Hamm                                                                                                                                                                                                                                    , David Wethe                                                                                                                                                                                                                                    ,  and Tom Maloney                                                                                                                                                                                                                               , Continental Resources Inc. plunged as much as 44% after founder and majority owner Harold Hamm distributed shares to family members, slashing his stake in the shale driller by more than two-thirds.                                          , Hamm, the Oklahoma wildcatter who helped usher in the shale-oil breakthroughs that made him a billionaire, held more than 81% of Continental’s outstanding shares prior to Wednesday’s filing that disclosed his stake has shrunk to about 24%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mfc:us </td>
   <td style="text-align:left;"> 2022-02-10 06:32:37 </td>
   <td style="text-align:left;"> Manulife Financial USA earnings above expectations at 0.84 USD </td>
   <td style="text-align:left;"> Manulife Financial USA (MFC) released earnings per share at 0.84 USD, compared to market expectations of 0.64 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/stocks-set-to-extend-rally-treasury-curve-flatter-markets-wrap </td>
   <td style="text-align:left;"> 2022-02-10 06:28:53 </td>
   <td style="text-align:left;"> Stocks Up, Bonds Steady as Traders Await U.S. CPI: Markets Wrap </td>
   <td style="text-align:left;"> Andreea Papuc                                                                                                                                                                                                                                             , Asian stocks rose Thursday following the best day for U.S. shares this month, while the 10-year Treasury yield held a drop ahead of inflation data that will shape views on Federal Reserve policy tightening.                                            , Equities in Japan, Australia and South Korea advanced. U.S. futures fluctuated after the S&amp;P 500 extended a broad rally Wednesday and the Nasdaq 100 jumped over 2%. Uber Technologies Inc. and Walt Disney Co. gained in late trading on robust earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/snoop-dogg-buys-death-row-records-from-blackstone-managed-group?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 06:14:50 </td>
   <td style="text-align:left;"> Snoop Dogg Buys Death Row Records From Blackstone Affiliate </td>
   <td style="text-align:left;"> Snoop Dogg                                                                                                                                                                                                          , Photographer: Paras Griffin/Getty Images                                                                                                                                                                            , Kamaron Leach                                                                                                                                                                                                       ,  and Jessica Park                                                                                                                                                                                                   , Hip Hop icon Snoop Dogg has acquired the Death Row Records brand from MNRK Music Group, a song publishing and recording company backed by private equity firm Blackstone Inc.                                       , The deal is expected to include Death Row’s entire music catalog, said a person familiar with the transaction who asked to not be identified because the details weren’t public. Financial terms weren’t disclosed.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oreilly-stock-gains-more-5/story.aspx?guid={AD0CFAAD-14B6-4618-A5CA-8DCE3741135D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 06:12:06 </td>
   <td style="text-align:left;"> O'Reilly stock gains more than 5% after 'incredible' quarter - MarketWatch </td>
   <td style="text-align:left;"> O'Reilly Automotive Inc. 
        ORLY,
        +0.48%
       shares rose more than 5% late Wednesday after the auto-parts retailer reported quarterly earnings and sales above Wall Street expectations, calling the quarter's performance "incredible." O'Reilly said it earned $519 million, or $7.64 a share, in the quarter, compared with $393 million, or $5.40 a share, in the same period a year ago. Sales rose 16% to $3.3 billion, the company said. FactSet consensus called for earnings of $6.06 a share on sales of $3.1 billion. O'Reilly guided for full-year 2022 sales between $14.2 billion and $14.5 billion, and EPS between $32.35 and $32.85. "This incredible performance in the fourth quarter caps a tremendous year for our company, a year in which we delivered the best financial results in our company's history, after setting the same records in 2020," Chief Executive Greg Johnson said in a statement. Shares of O'Reilly ended the regular trading day up 0.5%. 

, The U.S. is heading out of the "full blown pandemic phase" of COVID-19 and moving toward a point where more decisions will be made at the local level and not by the federal government, allowing restrictions such as wearing face masks to be lifted over time.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/orly:us </td>
   <td style="text-align:left;"> 2022-02-10 05:59:30 </td>
   <td style="text-align:left;"> O'Reilly Automotive earnings above expectations at 7.64 USD </td>
   <td style="text-align:left;"> O'Reilly Automotive (ORLY) released earnings per share at 7.64 USD, compared to market expectations of 6.04 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 05:58:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Rise for 2nd Day </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, extended gains for a second straight session to close 0.2% up at 112,461 on Wednesday, tracking its global peers and led by heavyweight Petrobras on rising oil prices, despite weakness in the banking sector. Meanwhile, investors continued to monitor corporate earnings while awaiting fresh US inflation figures for clues on the trajectory of the Fed's monetary policy tightening. Brazilian lender Banco Bradesco reported fourth-quarter earnings slightly below analysts’ estimates but indicated a bright outlook for 2022. Also, companies in the paper and packaging sector such as Suzano and Klabin reported fourth-quarter results. On the data front, Brazil's inflation rate decelerated in January from the previous month, as expected, but it was still the highest reading for a January month since 2016. At the same time, retail sales fell in December from the previous month but less than market estimates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/09/stocks-making-the-biggest-moves-after-hours-disney-uber-mattel-and-more.html </td>
   <td style="text-align:left;"> 2022-02-10 05:56:03 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Disney, Uber, Mattel and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines after the bell.                                                                                                                                                                                                                                                                                                                                      , Walt Disney — Shares of Disney popped more than 6% after the company reported an earnings beat for its most recent quarter. Disney said it doubled its revenue in its parks, experiences and consumer products division, as more guests attended theme parks, stayed in branded hotels and booked cruises. It also reported total subscriptions for its streaming service that beat estimates., Uber — Uber jumped 5% after the company beat analyst estimates on quarterly revenue and said business is starting to bounce back from omicron-induced challenges. Revenue in the company's mobility division was up 67% from the same time a year ago, and delivery revenue was up 34%, the company reported.                                                                                 , Mattel — The toy and game maker's shares climbed more than 10% after the company reported fourth-quarter earnings of 53 cents per share, compared with a Refinitiv consensus estimate of just 30 cents per share. Revenue of $1.79 billion also topped analysts' estimates of $1.66 billion.                                                                                                  , Twilio — The software maker's shares soared about 20% after the company reported a revenue beat and bold quarterly guidance. Its fourth-quarter revenue was almost 10% higher than analysts expected. The company also said it saw gains from its acquisitions of Segment and Zipwhip.                                                                                                        , MGM Resorts International — The hotel and casino operator saw its shares rise 3% after it reported a beat on the top and bottom lines. The company said its Las Vegas Strip resorts saw an occupancy rate of 86% during the quarter, compared with a 38% occupancy rate during the same period a year earlier.                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/technology/tiktok-personal-data-study </td>
   <td style="text-align:left;"> 2022-02-10 05:55:02 </td>
   <td style="text-align:left;"> TikTok shares more of your data than any other app, and a study says it's not clear where it goes </td>
   <td style="text-align:left;"> Seaport Securities founder Teddy Weisberg and TJM managing director Chris Robinson give their read on consumer inflation on 'The Claman Countdown.'                                                                                                                                                                                 , A recent study found that YouTube and TikTok collect more personal data than any other social media apps, but how TikTok uses that data remains a complete mystery.                                                                                                                                                                 , Mobile marketing company URL Genius used the Record App Activity in Apple’s iOS 15.2 to which apps communicate with outside networks. YouTube and TikTok registered the most network contacts at 14 each – a significant jump from the average of 6 connections among other apps, such as Twitter, Telegram, Snapchat, and Whatsapp., VERIZON EXEC SAYS GAME-CHANGING 5G THE ‘FUTURE OF GROWTH’                                                                                                                                                                                                                                                                           , More than the number of contacts was the type of contacts each app made: YouTube made 10 first-party contacts, but TikTok made 13 third-party contacts. The tracking still happened even when users didn’t opt into allow tracking.                                                                                                 , BRAZIL - 2021/08/27: In this photo illustration the YouTube logo seen displayed on a smartphone. _______ TikTok logo    | Getty Images                                                                                                                                                                                              , "Consumers are currently unable to see what data is shared with third-party networks, or how their data will be used," the report said, noting that third-party contacts could not be identified.                                                                                                                                   , WATCHDOG GROUP PUSHES GOOGLE, YOUTUBE PARENT COMPANY FOR GOVERNMENT CENSORSHIP REQUESTS                                                                                                                                                                                                                                             , The U.S. has tried to crackdown on TikTok and its use, with some lawmakers including Sen. Marco Rubio, R-Fla., saying that the White House is moving too slowly to create a cohesive plan.                                                                                                                                          , "TikTok remains a serious threat to U.S. national security and Americans’—especially children’s—personal privacy," Mr. Rubio said. "The Biden administration undid critical measures that President Trump took against the app, and the timid steps it has taken on data security are not nearly enough."                           , SOLAR STORM SENDS SPACEX STARLINK SATELLITES OUT OF ORBIT                                                                                                                                                                                                                                                                           , The U.S. military already banned its members from using the app on government-issued devices.                                                                                                                                                                                                                                       , The Biden administration argued that executive orders signed by former President Donald Trump were unenforceable, and any new laws needed careful consideration to ensure they withstand any legal challenges.                                                                                                                      , CLICK HERE TO GET FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                            , The Commerce Department recently submitted recommendations to the White House to further address the risk that data collected on American users by Chinese apps could be shared with Beijing.                                                                                                                                       , In a statement, the Chinese Embassy in Washington said the U.S. shouldn’t "overstretch the concept of national security and politicize economic issues." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/irobot-swings-q4-loss-says/story.aspx?guid={9EB5E7C4-3D03-4344-B14B-3F416C251099}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 05:40:30 </td>
   <td style="text-align:left;"> iRobot swings to Q4 loss, says that chip shortage, shipping delays dent sales - MarketWatch </td>
   <td style="text-align:left;"> Shares of iRobot Corp. 
        IRBT,
        +4.07%
       tanked more than 11% in the extended session Wednesday after the maker of the Roomba robotic vacuum cleaner and other products reported a wider-than-expected fourth-quarter loss and sales fell short of estimates, saying that chip shortages, shipping delays and other supply-chain problems crimped its business. IRobot said it lost $31.5 million, or  $1.17 a share, in the quarter, contrasting with a net income of $13 million, or 46 cents a share, in the year-ago quarter. Adjusted for one-time items, iRobot lost $1.05 a share. Sales fell 16% to $455.4 million, iRobot said. Analysts polled by FactSet expected the company to report a loss of 91 cents a share on sales of $470 million. "Despite ongoing semiconductor chip constraints and shipping delays that impacted our ability to fulfill approximately more than $35 million in orders, we reported fourth-quarter financial results within the parameters we outlined in late October," Chief Executive Colin Angle said in a statement. "While multiple supply chain issues conspired to limit our 2021 financial performance, we made considerable and important strategic progress during the year." IRobot stock ended the regular trading day up 4.1%. , The IOC is addressing complaints about cold, inadequate food and no internet or training equipment for athletes stuck in quarantine hotels                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/national-archives-asks-doj-investigate/story.aspx?guid={C26920E4-5BB2-4FB7-9BA5-499C91E836C2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 05:38:28 </td>
   <td style="text-align:left;"> National Archives asks DOJ to investigate Trump's handling of White House records: report - MarketWatch </td>
   <td style="text-align:left;"> The National Archives and Records Administration has asked the Justice Department to examine Donald Trump's handling of White House records, the Washington Post reported Wednesday. That has sparked discussions among federal law-enforcement officials about whether they should investigate the former president for a possible crime, the Post said, citing people familiar with the matter. As the Post reports, the referral from the National Archives came amid revelations that officials recovered 15 boxes of materials from Trump's Mar-a-Lago residence in Florida that were not handed in to the government as they should have been. , The Internal Revenue Service has way too many unprocessed tax returns from last year --- and far too few job applications for workers who will help the agency dig out of the backlog.                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-us-canada-60310783?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-10 05:33:32 </td>
   <td style="text-align:left;"> Record-high seizure of $4bn in stolen Bitcoin </td>
   <td style="text-align:left;"> Stolen Bitcoin worth more than $4bn (£2.9bn) has been seized by the US Department of Justice - the largest ever confiscation of its kind.                                                                                                                                                                 , Officials also charged two people on Tuesday with attempting to launder the money, stolen by a hacker who breached a cryptocurrency platform in 2016.                                                                                                                                                     , The hacker allegedly made off with nearly 120,000 Bitcoin. Then valued at about $71m, its value now exceeds $5bn.                                                                                                                                                                                         , About 94,000 Bitcoin have been recovered.                                                                                                                                                                                                                                                                 , Assistant Attorney General Kenneth Polite Jr said the seizure was proof the government "will not allow cryptocurrency to be a safe haven for money laundering or a zone of lawlessness within our financial system".                                                                                      , The money originates from the 2016 hack of a crypto exchange known as Bitfinex.                                                                                                                                                                                                                           , According to Justice Department officials, a hacker breached the platform, made more than 2,000 unauthorised transactions and then funnelled the money into a digital wallet allegedly run by Ilya Lichtenstein, 34, of New York.                                                                         , A criminal complaint alleges Lichtenstein and his wife, Heather Morgan, 31, laundered about 25,000 of the stolen Bitcoin through various accounts over the past five years and used various methods to cover their tracks, from fake identities to converting their Bitcoin into other digital currencies., Investigators from Washington DC, New York, Chicago and Ansbach, Germany collaborated on the lengthy probe.                                                                                                                                                                                               , In a statement, Bitfinex said it had cooperated with the inquiry and was "pleased" the stolen funds had been recovered.                                                                                                                                                                                   , Lichtenstein and Morgan will appear before a federal judge later on Tuesday, on counts of conspiracy to defraud the US and conspiracy to commit money laundering.                                                                                                                                         , If found guilty, they could each serve up to 25 years in prison.                                                                                                                                                                                                                                          , The asset seizure comes four months after the launch of a National Cryptocurrency Enforcement Team  at the Justice Department.                                                                                                                                                                            , In what is believed to be its previous largest financial seizure, the team seized some $2.3m in cryptocurrency last year, recovering the ransom paid by the Colonial Pipeline company to end a crippling cyberattack.                                                                                     , Investigating a rivalry with devastating consequences                                                                                                                                                                                                                                                     , The ups and downs of life on the wards                                                                                                                                                                                                                                                                    , Can Jay Blades now, in mid-life, tackle what he failed to learn first time round?                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/msi:us </td>
   <td style="text-align:left;"> 2022-02-10 05:28:23 </td>
   <td style="text-align:left;"> Motorola Solutions Msi earnings above expectations at 2.85 USD </td>
   <td style="text-align:left;"> Motorola Solutions Msi (MSI) released earnings per share at 2.85 USD, compared to market expectations of 2.74 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uber:us </td>
   <td style="text-align:left;"> 2022-02-10 05:28:17 </td>
   <td style="text-align:left;"> Uber earnings above expectations at 0.44 USD </td>
   <td style="text-align:left;"> Uber (UBER) released earnings per share at 0.44 USD, compared to market expectations of -0.30 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/mattel-stock-rallies-after-toy/story.aspx?guid={F13C5B9E-0A6E-4003-A82A-1C2D27765770}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 05:20:36 </td>
   <td style="text-align:left;"> Mattel stock rallies after toy maker beats Q4 expectations, says turnaround 'complete'   - MarketWatch </td>
   <td style="text-align:left;"> Shares of Mattel Inc. 
        MAT,
        +3.83%
       rose more than 6% in the extended session Wednesday after the toy maker reported fourth-quarter earnings and sales above Wall Street expectations and said its business turnaround is "complete." Mattel said it earned $226 million, or 63 cents a share, in the quarter, compared with $129 million, or 37 cents a share, in the year-ago quarter. Sales rose 10% to 1.8 billion, Mattel said, including a 14% increase in sales in North America. That growth was thanks to dolls, including Barbie, and action figures and building sets, the toy maker said. Net sales of Mattel's American Girl doll fell 6%. Analysts polled by FactSet expected Mattel to report earnings of 30 cents a share on sales of $1.7 billion. "We have made significant progress on our transformation strategy over the last few years, and our turnaround is now complete," Chief Executive Ynon Kreiz said in a statement. Mattel guided for sales growth between 8% and 10% this year and EPS between $1.42 and $1.48. , The technology-heavy Nasdaq Composite has risen more than 3% this week, as it tries to recover from its recent correction.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nasdaq-ends-21-higher-stocks/story.aspx?guid={A2186C23-2F56-497C-8BD3-E055B4C85C6D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 05:12:09 </td>
   <td style="text-align:left;"> Nasdaq ends 2.1% higher as stocks bounce back from January fall - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended with sharp gains Wednesday, extending a bounce from a January stumble as investors digested a steady stream of corporate earnings and awaited the release of the January consumer price index. The Dow Jones Industrial Average 
        DJIA,
        +0.86%
       ended around 305 points higher, up 0.9%, near 35,769, according to preliminary figures The S&amp;P 500 
        SPX,
        +1.45%
       rose around 66 points, or 1.5%, to finish near 4,587, while the Nasdaq Composite 
        COMP,
        +2.08%
       led the way higher, rising 2.1% to close near 14,490. Economic data will be in focus Thursday, with investors set to gauge the January CPI reading for clues to how aggressive the Federal Reserve will be as it attempts to get inflation under control., Stock splits usually work, and the 20-for-1 split by Google's parent company Alphabet may spark a wave.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/09/russia-ukraine-military-weather-climate-conditions-pkg-oneworld-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-10 05:09:18 </td>
   <td style="text-align:left;"> Why Russia may have to check the forecast before invading Ukraine - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/lumber-surges-anew-as-supplies-shrink-ahead-of-building-season?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 05:08:32 </td>
   <td style="text-align:left;"> Lumber Surges Anew as Supplies Shrink Ahead of Building Season </td>
   <td style="text-align:left;"> Futures jumped by the exchange limit in Chicago for a sixth straight session, following slump in January.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , A worker prepares siding to install on a single family home under construction in Lehi, Utah.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Jen Skerritt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Lumber is on a tear again, bringing back the specter of increasing construction costs. Lumber futures have recouped recent losses and risen by the exchange maximum of $45 for six consecutive sessions, touching $1,204.90 per 1,000 board feet Wednesday, the highest in three weeks. After prices slumped in January amid cold U.S. weather and transportation bottlenecks, tight inventories ahead of peak building season are helping to fuel a rebound. “Prices are well above trend pricing, as well as our own price forecasts,” Mark Wilde, an analyst at BMO Capital Markets in New York, said Wednesday in an email. “We are also just heading toward spring construction season and housing market activity, so it wouldn’t surprise me to see prices rally further.”Wood prices have been volatile since the pandemic began and they touched record highs during a Covid-19 fueled building boom, then collapsed because sawmills ramped up production and high prices stifled demand. An index of framing composite has more than tripled since late August, adding to the cost of an average new home.,   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/dis:us </td>
   <td style="text-align:left;"> 2022-02-10 05:07:49 </td>
   <td style="text-align:left;"> Walt Disney earnings above expectations at 1.06 USD </td>
   <td style="text-align:left;"> Walt Disney (DIS) released earnings per share at 1.06 USD, compared to market expectations of 0.74 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/09/business/uber-business-pandemic.html </td>
   <td style="text-align:left;"> 2022-02-10 05:05:05 </td>
   <td style="text-align:left;"> Uber Says It's Bouncing Back From Pandemic In Earnings Report - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                        , Revenue in the last three months of 2021 was up 83 percent from a year earlier, the company reported.                                                                                                                                                                                                                                                                                                , By Kate Conger                                                                                                                                                                                                                                                                                                                                                                                       , Uber said on Wednesday that growing revenue and returning passengers sent a strong signal that its business was bouncing back in the final three months of 2021 from the slowdown caused by the pandemic.                                                                                                                                                                                            , The quarter also provided another indication of how Uber’s fortunes rise and fall with its investments in other companies.                                                                                                                                                                                                                                                                           , Uber’s revenue grew to $5.8 billion, an 83 percent increase from a year earlier, exceeding analyst expectations. The company also marked its second profitable quarter as a public company, earning $892 million largely from its investments in Grab, the Southeast Asian ride-hailing company that went public in December, and Aurora, the autonomous vehicle start-up.                           , Uber lost $968 million during the same period a year earlier and reported a loss of $2.4 billion in the third quarter of 2021 caused by its investment in Didi, the Chinese ride-hailing company.                                                                                                                                                                                                    , Its investments in other ride-hailing companies would probably continue to cause fluctuation in its profits and losses, Uber said in its earnings report. Uber’s chief executive, Dara Khosrowshahi, said at a December analyst event that the company would hang on to some of its strategic investments but would eventually look to sell its stake in Didi.                                       , Uber’s loss from operations for the quarter was $550 million, a 37 percent improvement from a year earlier.                                                                                                                                                                                                                                                                                          , Uber said it was attracting a growing number of users by relying on its food delivery business, Uber Eats, to bring in business during spikes in coronavirus cases, when its ride-hailing business declined. Uber reported 118 million users during the fourth quarter, a 27 percent increase from a year earlier.                                                                                   , “Our results demonstrate just how far we’ve come since the beginning of the pandemic,” Mr. Khosrowshahi said in a statement. “While the Omicron variant began to impact our business in late December, mobility is already starting to bounce back.”                                                                                                                                                 , Uber’s stock price was up about 5 percent in after-hours trading on Wednesday.                                                                                                                                                                                                                                                                                                                       , The growth in users sets Uber apart from its primary rival in the United States, Lyft. In an earnings report on Tuesday, Lyft said it had 18,728 users during the fourth quarter, a 49 percent increase from a year earlier but a slight decrease from the third quarter. The modest decline in users showed that the winter wave of Omicron might have presented more challenges to Lyft’s business., Still, Lyft said that its revenue had grown by 70 percent, to $969.9 million, and that its losses had improved to $258.6 million, a 43 percent change from a year earlier.                                                                                                                                                                                                                           , Analysts said Uber’s and Lyft’s businesses would most likely continue to fluctuate as travel was affected by the pandemic.                                                                                                                                                                                                                                                                           , “It’s going to ebb and flow,” said Tom White, a senior research analyst with the financial firm D.A. Davidson. While Lyft’s business was tied to coronavirus conditions in North America, Uber could experience other issues because it operates around the world, he added.                                                                                                                         , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-09/world-beating-china-quants-hit-with-fee-curbs-in-latest-blow?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-10 05:00:00 </td>
   <td style="text-align:left;"> World-Beating China Quants Hit With Fee Curbs in Latest Blow </td>
   <td style="text-align:left;"> China’s quant hedge funds are being told to curtail fees, the latest setback for an industry that’s facing slower growth after outperforming global rivals last year.                                                      , The Asset Management Association of China has since December been rejecting registration of products that allow managers to collect performance fees when strategies lose money, people with knowledge of the matter said.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 05:00:00 </td>
   <td style="text-align:left;"> Canada Stocks End at Over 2-Month High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 1.1% higher at 21,604 on Wednesday, a level not seen since November 25th, extending gains for a second straight session, as upbeat earnings reignited investors’ appetite for risk. Canopy Growth was the top performer, as its shares jumped over 14% after the Canadian recreational and medical marijuana company reported its third-quarter fiscal 2022 financial report, showing a narrower-than-anticipated loss as well better-than-expected revenue. The energy sector also gained amid rising oil prices. Now, investors await Q4 results for Manulife Financial and Sun Life Financial later. Meanwhile, the nearly two-week long protest of Canadian truck drivers against mandatory vaccination and other Covid-19 restrictions continued, posing a risk to the auto industry's supply chain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 04:56:00 </td>
   <td style="text-align:left;"> US Stocks Gain For a 2nd Session </td>
   <td style="text-align:left;"> Three major US stock indexes gained further ground Wednesday as investors digested another batch of corporate earnings results and eyed inflation data on Thursday for clues on the timing and magnitude of the Federal Reserve's tightening. The Dow Jones closed 306 points up, the S&amp;P 500 gained 1.5% and the Nasdaq Composite jumped 2%. Tech stocks were leading the gains with Meta and Shopify rising more than 4% and Alphabet up 1.6% as a decline in bond yields eased the pressure. On the earnings front, Chipotle was up 9% on strong quarterly numbers, while Lyft gained 3% despite announcing it had fewer active riders than in the prior quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/assurant-shares-jump-7-earnings/story.aspx?guid={9E91F079-EB2D-42B5-9AF0-C8048AEFAA55}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 04:46:46 </td>
   <td style="text-align:left;"> Assurant shares jump 7% on earnings boost - MarketWatch </td>
   <td style="text-align:left;"> Assurant Inc. 
        AIZ,
        +6.74%
       jumped 7% on Wednesday in the stock's strongest performance since Aug. 5, 2020 when it rallied 14.2%. The New York-based insurance carrier on Tuesday lifted its outlook for earnings before interest, taxes, depreciation and amortization (Ebitda) and beat Wall Street's earnings view. For 2022, Assurant said it expects Ebitda growth of 8% to 10%. Analysts at Truist Securities said Wednesday the forecast implies an Ebitda range of about $1.20 billion to $1.22 billion, ahead of its estimate of $1.18 billion. Fourth-quarter earnings totaled $2.47 a share, ahead of the Wall Street estimate of $2.30 a share in a survey of analysts by FactSet. Truist reiterated its buy rating on Assurant. Assurant stock is up 22.7% in the past 12 months, compared to a gain of 17.1% by the S&amp;P 500 over the same period. , Shares of Facebook-parent Meta Platforms Inc. bounced Wednesday off a 20-month low, after a widely followed technical indicator sank to the most oversold level seen since just a few months after the company went public 10 years ago.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/disney-earnings-subscriptions </td>
   <td style="text-align:left;"> 2022-02-10 04:44:00 </td>
   <td style="text-align:left;"> Disney stock gets a boost as Disney+ subscriptions hit nearly 130 million </td>
   <td style="text-align:left;"> Circle Squared Alternative Investments Founder Jeff Sica weighs in on expectations for Disney ahead of the company's earnings report, arguing that the 'stock is oversold.'                                                                                                                                                                                                                                                        , The Walt Disney Co. saw its stock rise in after-hours trading Wednesday after the company posted its first quarter results for fiscal year 2022, showing the global entertainment titan surpassed analysts' expectations by reaching just under 130 million subscribers to its Disney+ streaming service.                                                                                                                          , Amsterdam, The Netherlands, 02/03/2020, Disney+ startscreen on mobile phone. Disney+ online video, content streaming subscription service. Disney plus, Star wars, Marvel, Pixar, National Geographic. (iStock / iStock)                                                                                                                                                                                                           , Wall Street had expected the subscriber total to reach around 124 million, but Disney+ subscribers hit 129.8 million internationally as of January 1. The company also saw a 76% year-over-year increase in ESPN+ streaming subscribers to 21.3 million, and a 15% rise in Hulu watchers to 45.3 million.                                                                                                                          , "We’ve had a very strong start to the fiscal year, with a significant rise in earnings per share, record revenue and operating income at our domestic parks and resorts, the launch of a new franchise with Encanto, and a significant increase in total subscriptions across our streaming portfolio to 196.4 million, including 11.8 million Disney+ subscribers added in the first quarter," CEO Bob Chapek said in a statement., LOS ANGELES, CALIFORNIA - NOVEMBER 23: An "Encanto" step-and-repeat at the opening night fan event for Disney's "Encanto" at El Capitan Theatre on November 23, 2021 in Los Angeles, California.  (Michael Tullberg/Getty Images / Getty Images)                                                                                                                                                                                   , SMITHSONIAN MUSEUM IS ASKING FOR PICTURES FROM DISNEY VACATIONS                                                                                                                                                                                                                                                                                                                                                                    , During the earnings call following the report, Chapek expressed optimism about the continued growth in Disney+ subscribers. The CEO noted that while the Disney brand has a strong appeal to families, roughly half their current customers do not have children, and said that adding broader content to the streaming service will likely be a trend for the firm moving forward.                                                , Rededication Moment and debut of "Disney Enchantment" during "The World's Most Magical Celebration" Walt Disney World Resort 50th Anniversary at Magic Kingdom on September 30, 2021 in Orlando, Florida. (Gerardo Mora/Getty Images / Getty Images)                                                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                        , Disney also surpassed Wall Street expectations of $20.27 in revenue for fiscal Q1, reporting $21.82 billion, which was up from $16.25 from the same quarter last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/boston-federal-reserve-taps-university-michigan-economist-head </td>
   <td style="text-align:left;"> 2022-02-10 04:41:17 </td>
   <td style="text-align:left;"> Boston Federal Reserve taps U. of Michigan economist as head </td>
   <td style="text-align:left;"> Odeon Capital Group chief financial strategist Dick Bove argues the Federal Reserve is in one of ‘the worst’ positions he’s ever seen and it will ‘slow down’ the growth of money in the U.S.                                                                                                                                                                                                                       , The Federal Reserve Bank of Boston announced Wednesday that University of Michigan economist Dr. Susan M. Collins will serve as its new president, CEO, and representative on the Federal Open Market Committee after what the bank called a "rigorous search."                                                                                                                                                     , The Federal Reserve Bank of Boston announced that Dr. Susan M. Collins will be its next president, CEO, and participant in national monetary policymaking on the Federal Open Market Committee.  ((Photo credit, Federal Reserve Bank of Boston))                                                                                                                                                                   , Dr. Collins currently serves as the university's provost, executive vice president for academic affairs, and as a professor of public policy and economics. She is an international macroeconomist.                                                                                                                                                                                                                 , TOOMEY CLASHES WITH BIDEN FED NOMINEES ON CLIMATE, ‘LEFT-WING' POLITICS, DEMS SAY ATTACKS LACK ‘COMMON SENSE’                                                                                                                                                                                                                                                                                                       , "After an intensive search, we are thrilled to appoint this exceptionally well-qualified person to be the Bank’s president and a key leader in the Federal Reserve System," said Dr. Christina Paxson, president of Brown University and chair of the Bank’s Board of Directors.                                                                                                                                    , Federal Reserve Bank of Boston signage is displayed in Boston, Massachusetts,  (Photographer: Brent Lewin/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                , FINANCIAL, ENERGY SECTORS MOST AT RISK FROM FED RATE HIKES: INVESTMENT STRATEGIST                                                                                                                                                                                                                                                                                                                                   , "Dr. Collins brings the technical expertise and insight to contribute to policymaking and the leadership ability to head the organization," continued Paxson, who led the presidential search committee. "She is deeply committed to serving the public, engaging with constituents, and advancing economic stability, opportunity, and prosperity for the region and nation through the work of the central bank." , "It is an honor and an inspiration to serve as the Boston Fed’s next president," Collins said in a statement. "Throughout my career, I have been driven by a commitment to leveraging research, education, and public service to improve lives. I look forward to helping the Bank and System pursue the Fed’s dual mandate from Congress – achieving price stability and maximum employment."                      , Former Boston Federal Reserve President Eric Rosengren visits Fox Business News at Fox Business Network Studios on September 20, 2019 in New York City.  (Photo by Slaven Vlasic/Getty Images / Getty Images)                                                                                                                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                         , The search for a new Boston Fed chief was launched following former president Eric Rosengren's announcement in September that he would be stepping down early for health reasons, after he and other high-level Fed officials drew the attention of critics for making stock trades that drew scrutiny.                                                                                                             , Since Rosengren's departure, Kenneth Montgomery has served as interim president and CEO, a role he will remain in until Collins takes the helm on July 1. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 04:30:04 </td>
   <td style="text-align:left;"> The Dow Jones Index rising 0.78% </td>
   <td style="text-align:left;"> United States Stock Market is gaining 277 points. Leading the gains are Walt Disney (3.11%), Intel (2.16%) and Walgreens Boots Alliance (1.98%). Top losers are Coca-Cola (-1.47%), Amgen (-1.04%) and Walmart (-0.25%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-settle-higher-us/story.aspx?guid={5759B5AD-3B62-4FA9-923E-A48E21920334}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 03:37:34 </td>
   <td style="text-align:left;"> Oil futures settle higher, but U.S. prices hold below the $90 mark - MarketWatch </td>
   <td style="text-align:left;"> Oil futures climbed on Wednesday, but U.S. benchmark prices settled below their highest levels of the session. The resumption of indirect talks between the U.S. and Iran likely "contributed to the recent weakness in prices," but the countries remain "a long way short of any sort of agreement that might bring about new supply," said Michael Hewson, chief market analyst at CMC Markets UK. This may "constrain any dips" in oil prices, along with declines in U.S. crude inventories," he said. West Texas Intermediate crude for March delivery 
        CLH22,
        +0.14%
       rose 30 cents, or 0.3%, to settle at $89.66 a barrel on the New York Mercantile Exchange after trading as high as $90.58. Prices fell 2.2% on Tuesday. , Fusion via the machine known as as 'tokamak' works differently than the fission process at the nuclear plants we're used to.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/09/university-of-michigan-provost-named-as-new-head-of-the-boston-fed.html </td>
   <td style="text-align:left;"> 2022-02-10 03:28:08 </td>
   <td style="text-align:left;"> University of Michigan provost named as next head of the Boston Fed </td>
   <td style="text-align:left;"> , The Boston Federal Reserve, which is heading the central bank's potential foray into digital currency and saw its leader resign last year amid a stock-trading controversy, has a new leader.                                                                                                                                                                                  , Susan M. Collins will helm the central bank branch and takes over July 1, replacing Eric Rosengren, who retired last year for health reasons and following disclosures that he had been involved in trading securities in 2020. That was around the same time the Fed was unleashing unprecedented programs to help the economy and financial markets through the Covid crisis., Currently the provost and executive vice president for academic affairs at the University of Michigan, Collins will take over for interim president Kenneth Montgomery.                                                                                                                                                                                                        , "Dr. Collins brings the technical expertise and insight to contribute to policymaking and the leadership ability to head the organization," said Christina Paxson, the president of Brown University who led the search for the new president.                                                                                                                                 , A release announcing her appointment describes the new leader as "an international macroeconomist with a lifelong interest in policy and its impact on living standards."                                                                                                                                                                                                      , The Boston Fed is heading what's known as Project Hamilton, an exploration into the possible development of a central bank digital currency. The institution last week released a study that addresses the technical issues involved, though it took no position and established no pilot project to move ahead.                                                               , Prior to that, the Boston Fed handed the Main Street Lending Program during the pandemic.                                                                                                                                                                                                                                                                                      , "Throughout my career, I have been driven by a commitment to leveraging research, education, and public service to improve lives," Collins said in a statement accompanying her announcement. "I look forward to helping the Bank and System pursue the Fed's dual mandate from Congress – achieving price stability and maximum employment."                                  , The Fed is expected to embark on a new rate-hiking cycle in March as it looks to control inflation running at its hottest pace since the early 1980s, when the U.S. was confronting the stagflation dual threat of low growth and rising prices.                                                                                                                               , Along with that, the central bank likely will begin reducing its more than $8 trillion in bond holdings by summertime. A 4% unemployment rate has come with rising wages that are applying additional inflationary pressures.                                                                                                                                                  , Collins will come on board after the academic year wraps up. Montgomery will stay on as first vice president and chief operating officer.                                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/house-republicans-lambast-biden-over-fed-nominee-sarah-bloom-raskin </td>
   <td style="text-align:left;"> 2022-02-10 03:26:27 </td>
   <td style="text-align:left;"> House Republicans lambast Biden over Fed nominee Sarah Bloom Raskin: A 'far-left radical' </td>
   <td style="text-align:left;"> Sen. Bill Haggerty, R-Tenn., discusses Biden's Fed nominee Sarah Bloom Raskin, Biden's policies falling short of Americans' approval and the U.S. sending 3,000 troops to NATO countries.                                                                                                                                                                                                                                                                                                                                                          , EXCLUSIVE: A coalition of House Republicans is sounding the alarm over Sarah Bloom Raskin, President Biden’s nominee to become the Federal Reserve's top banking regulator, expressing concern that her climate regulation views could endanger the independence of the U.S. central bank and hurt working-class Americans.                                                                                                                                                                                                                        , In a Wednesday letter addressed to the White House, 48 GOP lawmakers urged President Biden to reconsider his nomination of Raskin as the Fed's vice chair of supervision, warning that her past statements indicate she would "irreparably politicize the Federal Reserve and destroy what remains of its credibility and independence."                                                                                                                                                                                                           , SARAH BLOOM RASKIN OPPOSED BY 24 STATE FINANCIAL OFFICERS OVER 'RADICAL' VIEW                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , "We are deeply troubled by your decision to nominate Ms. Raskin, who would wield tremendous regulatory and supervisory authority that could be weaponized to discourage or prohibit banks from lending to or investing in American energy," the letter, a copy of which was first shared with FOX Business, said. "Her consistent advocacy for the Federal Reserve to de-bank energy companies raises the troubling prospect that she would do just that."                                                                                         , Sarah Bloom Raskin and U.S. Rep. Jamie Raskin, D-Md., listen as a group of Maryland residents, calling themselves the "Pandemic Comforters," sing in the front yard of his home on May 4, 2020, in Takoma Park, Maryland.  (Drew Angerer/Getty Images / Getty Images)                                                                                                                                                                                                                                                                              , Raskin has previously argued that all financial institutions should re-evaluate their relationships with energy companies and has advocated for a push toward sustainable investments that do not depend on carbon and fossil fuels. If banks and other financial institutions do not take these steps to distance themselves from fossil-fuel companies, Raskin has said, the Fed should penalize them.                                                                                                                                           , But Republicans warned that targeting the oil and gas industry could have irreparable side effects on working-class families – particularly those who live in energy-producing states like Pennsylvania and West Virginia.                                                                                                                                                                                                                                                                                                                         , Rep. Guy Reschenthaler, R-Pa., spearheaded the Wednesday letter to Biden, and told FOX Business during an interview that he had three problems with Raskin: Her previously stated belief that the Fed can "pick winners and losers in the economy," her suggestion that the Fed is in a "unique position to effectuate climate change" because the institution operates independently and outside the purview of Congress, and her past criticisms of the energy sector and push to bar the industry from benefiting from coronavirus relief money., "For all those reasons, she is way too radical," Reschenthaler said. "She’s way too out of step with the role of the Fed. And she has a warped view of American democracy in that she wants to put more power in those that are unaccountable to the electorate."                                                                                                                                                                                                                                                                                  , Sarah Bloom Raskin, nominated to be vice chairman for supervision and a member of the Federal Reserve Board of Governors, is sworn in before a Senate Banking, Housing and Urban Affairs Committee confirmation hearing on Capitol Hill in Washington, Feb (Bill Clark/Pool via REUTERS / Reuters Photos)                                                                                                                                                                                                                                          , Raskin has also drawn scrutiny over a May 2020 New York Times op-ed that she authored titled "Why Is the Fed Spending So Much Money on a Dying Industry?" In the op-ed, Raskin criticized the federal government for including the oil and gas industries in the initial $2.2 trillion coronavirus relief package and said the Fed should adopt a long-term approach that shifted away from fossil fuels.                                                                                                                                          , "Given the size and scope of government intervention, we should be maximizing the public’s return on our investment," she wrote at the time. "The Fed’s unique independence affords it a powerful role, and its mandate includes ensuring both the stability of the financial system and full employment. Climate change threatens financial stability; addressing it can create economic opportunity and more jobs."                                                                                                                              , Raskin later said she made the comments in the context of taxpayer-funded spending and would not apply it to the role of the Fed.                                                                                                                                                                                                                                                                                                                                                                                                                  , Republicans on the Senate Banking Committee skewered Raskin during her confirmation hearing last week over some of her more controversial statements on challenges that climate change poses to the current financial system – and how she believes the Fed needs to respond. Raskin maintained that she believed it is "inappropriate" for the Fed to make credit decisions and allocations based on "choosing winners and losers."                                                                                                               , "Banks choose their borrowers. The Fed does not," she told the Senate Banking Committee. "It is inappropriate for the Fed to choose winners and losers, and to do so is not the proper institutional role of the Fed. That is a cardinal principle of Fed supervision."                                                                                                                                                                                                                                                                            , Given the 50-50 Senate, Democrats would need to secure the support of every member of their caucus to overcome unified Republican opposition. The House does not vote on presidential nominees – which Reschenthaler acknowledged.                                                                                                                                                                                                                                                                                                                 , President Biden addresses the 76th Session of the U.N. General Assembly on Sept. 21, 2021.  (Timothy A. Clary-Pool/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                    , "Ultimately this is a decision for the senate," he said. "But any senator that is thinking about confirming this far-left radical, that goes through, they’re going to have to answer to their voter. There will be a price to pay."                                                                                                                                                                                                                                                                                                               , As vice chair for supervision, Raskin – a Duke University law professor who has held high-level jobs at both the Treasury Department and the Fed – would oversee annual stress tests that review bank safety and liquidity. Her nomination has been welcomed by progressive senators and advocacy groups, who think she will take a tougher stance against Wall Street than her predecessor, Randal Quarles, a Trump nominee who stepped down in December.                                                                                         , Raskin served on the Fed's board from 2010 to 2014 and was tapped by former President Barack Obama to serve as assistant Treasury secretary.                                                                                                                                                                                                                                                                                                                                                                                                       , The White House has defended the nomination, with press secretary Jen Psaki telling reporters in late January that Raskin brings "unprecedented experience and the support of economic experts across the spectrum" to this role.                                                                                                                                                                                                                                                                                                                  , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , "She believes, and she has said she believes firmly in the independent role of the Federal Reserve and will work in concert with her colleagues to identify and mitigate a range of risks," Psaki said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/tennessee-valley-authority-says-federal/story.aspx?guid={0418CDF4-3AAF-428F-B042-9EDD377C6B4E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 03:25:27 </td>
   <td style="text-align:left;"> Tennessee Valley Authority says federal law forbids power sales to utilities serving legal cannabis businesses - MarketWatch </td>
   <td style="text-align:left;"> The Tennessee Valley Authority recently issued a statement saying that federal law prevents it from providing electricity to local power companies that in turn service legal cannabis companies. The TVA's coverage area for wholesale electricity includes three states with legal cannabis: Mississippi, Virginia and Alabama. "This is a complex and evolving issue -- which we've been following closely," said the Feb. 2 statement. The TVA said cannabis remains a Schedule I drug and that federal resources may not be used to facilitate activity that potentially violates federal law. In cases where it's alerted to power companies proving electricity to cannabis companies, "TVA management will make a determination regarding our reporting obligations to agencies that may have proper jurisdiction to enforce the federal Controlled Substances Act," the TVA said., The IOC is addressing complaints about cold, inadequate food and no internet or training equipment for athletes stuck in quarantine hotels                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cannabis-company-hexo-cut-180/story.aspx?guid={94E772EF-B5DE-4314-8F58-BE8C19908EAD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 03:19:49 </td>
   <td style="text-align:left;"> Cannabis company Hexo to cut 180 jobs - MarketWatch </td>
   <td style="text-align:left;"> Hexo Corp. 
        HEXO,
        +8.41%
       said Wednesday it is cutting 180 jobs, as part of the Canada-based cannabis company's cost-cutting plan. The layoffs represent about 14% of the company's workforce, which was about 1,277, according to the latest FactSet data. Half of the layoffs are result of the previously announced closure of its Stellarton facility, and the rest are related to the reduction of back-office positions. Hexo said the cuts will lead to annual savings of about C$15 million ($11.8 million). "Today's announcement was not an easy one to make. We are working with all impacted employees to the best of our ability to ensure that they are treated fairly and provided the support necessary to assist with this transition," said Chief Executive Scott Cooper. The U.S.-listed stock rose 6.8% in afternoon trading to 69 cents. In late-January, the company said it received notice from the Nasdaq that it was not in compliance with the minimum-bid listing requirement, as the stock has closed below $1 since Dec. 10. The stock has plunged 56.9% over the past three months, while the Cannabis ETF 
        THCX,
        +6.95%
       has slumped 38.1% and the S&amp;P 500 
        SPX,
        +1.45%
       has eased 2.1%., Shares of Facebook-parent Meta Platforms Inc. bounced Wednesday off a 20-month low, after a widely followed technical indicator sank to the most oversold level seen since just a few months after the company went public 10 years ago.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/white-house-braces-brutal-inflation-report </td>
   <td style="text-align:left;"> 2022-02-10 03:16:30 </td>
   <td style="text-align:left;"> White House braces for another brutal inflation report </td>
   <td style="text-align:left;"> Experts weigh in on rising concerns over inflation on 'Making Money.'                                                                                                                                                                                                                                                                                                                                                                    , The Biden administration is already in damage control mode ahead of the newest inflation data out this week that is expected to bring another jaw-dropping figure as the price of everyday consumer goods soared higher.                                                                                                                                                                                                                 , White House press secretary Jen Psaki told reporters Wednesday that administration officials expect a "high year-over-year inflation reading" when the Consumer Price Index report is published Thursday morning. The White House has said that individuals should focus on the month-over-month increase, rather than the annual jump, considering "what we've seen over the last year."                                                , White House press secretary Jen Psaki answers questions during the daily White House press briefing Jan. 6, 2022, in Washington, D.C. (Win McNamee/Getty Images / Getty Images)                                                                                                                                                                                                                                                          , "So above 7%, as I think some are predicting, would not be a surprise, even though we don't know what the data is going to be," Psaki said. "But looking at that reading of it as we prepare for tomorrow is still consistent with the path and our view."                                                                                                                                                                               , FED SIGNALS INTEREST RATE HIKE COULD COME 'SOON' AS INFLATION RAGES                                                                                                                                                                                                                                                                                                                                                                      , The Labor Department is releasing the highly anticipated consumer price index on Thursday morning, providing a fresh look at just how hot inflation ran in January.                                                                                                                                                                                                                                                                      , Economists expect the gauge, which measures goods ranging from gasoline and health care to groceries and rents, to show that prices surged 7.3% in January from the year-ago period, toppling the previous month's 39-year high of 7%.                                                                                                                                                                                                   , It would be the fastest increase in consumer prices since February 1982, when inflation hit 7.6%.                                                                                                                                                                                                                                                                                                                                        , Rising inflation is eating away at strong gains and wages and salaries that American workers have seen in recent months. That's bad news for President Biden, who has seen his approval rating plunge as consumer prices rose. The White House has blamed the price spike on supply-chain bottlenecks and other pandemic-induced disruptions in the economy, while Republicans have pinned it on the president's massive spending agenda., The latest data will also have implications for the Federal Reserve ahead of its March meeting. Chairman Jerome Powell has signaled that policymakers will raise interest rates from rock-bottom levels as early as next month.                                                                                                                                                                                                          , The only question now is whether it will be a quarter-basis point hike or larger. A hotter-than-expected reading on Thursday morning could pressure the Fed to consider its first half percentage-point increase since 2000.                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                              , Psaki said the president supports any decisions by the Fed to begin raising rates, even though doing so risks slowing the economy. Hiking interest rates tends to create higher rates on consumers and business loans, which slows the economy by forcing employers to cut back on spending.                                                                                                                                             , "The president has said he welcomes and supports [The Fed's] efforts to take steps with their plans in terms of our confidence," Psaki said. "We, again, rely on what their projections are that inflation will come down, that it will moderate, and we are also continuing to take steps to continue to grow the economy and continue to address the needs that the American people have in the economy." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/09/europe/tooth-human-neanderthal-france-cave-scn/index.html </td>
   <td style="text-align:left;"> 2022-02-10 03:00:07 </td>
   <td style="text-align:left;"> Tooth discovery is shaking up what we know about Neanderthals - CNN </td>
   <td style="text-align:left;"> (CNN)A child's tooth unearthed from a French cave has revealed the earliest evidence of humans -- Homo sapiens -- living in western Europe.                                                                                                                                                                                                                                                            , The discovery of the molar from Grotte Mandrin, near Malataverne in the Rhône Valley in southern France, along with hundreds of stone tools dating back about 54,000 years ago, suggests that early humans lived in Europe about 10,000 years earlier than archaeologists had previously thought.                                                                                                       , What's more, the Homo sapiens tooth was sandwiched between layers of Neanderthal remains, showing that the two groups of humans coexisted in the region. These findings challenge the narrative that the arrival of Homo sapiens in Europe triggered the extinction of Neanderthals, who lived in Europe and parts of Asia for about 300,000 years before disappearing.                                 , "We've often thought that the arrival of modern humans in Europe led to the pretty rapid demise of Neanderthals, but this new evidence suggests that both the appearance of modern humans in Europe and disappearance of Neanderthals is much more complex than that," said study coauthor Chris Stringer, a professor and research leader in human evolution at the Natural History Museum in London.  , It's the first time archaeologists have found evidence of alternating groups of Homo sapiens and Neanderthals living in the same place, and they rotated rapidly, even abruptly, at least twice, according to the study that published in the journal Science Advances on Wednesday.                                                                                                                    , Previously, the arrival of early humans in Europe was dated to between 43,000 and 45,000 years ago, according to remains found in Italy and Bulgaria -- not long before the last surviving Neanderthal remains dating back 40,000 to 42,000 years ago were found. This time frame had led many to think the arrival of Homo sapiens and the disappearance of Neanderthals were inexorably linked.       , Humans and Neanderthals, who we know from genetic analysis encountered one another and had babies, resulting in Neanderthal traces in our DNA, overlapped for a much longer period in Europe, this study suggests.                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                         , Clues from ancient stone tools                                                                                                                                                                                                                                                                                                                                                                          , Did humans and Neanderthals hang out together in this French cave overlooking the Rhône valley? The researchers don't have any hard evidence of interaction between the two groups.                                                                                                                                                                                                                     , The tools found in the layers representing the Homo sapiens and Neanderthal occupations are distinct in style and don't show any sign that they taught one another knapping or flaking stonework techniques. The stone tools associated with humans, known as Neronian tools, are smaller than those used by Neanderthals, known as Mousterian tools.                                                   , But the authors feel that it's likely that the two groups must have bumped into one another in the neighborhood -- even if direct contact didn't take place in this particular cave.                                                                                                                                                                                                                    , The hundreds of stone tools found at the site suggest that the rock shelter was occupied intensively by both groups of humans -- and was not just a place for an occasional stopover.                                                                                                                                                                                                                   , Astonishingly, the team was able to determine that the period between the Neanderthals relocating and the first modern humans moving into the cave 56,000 years ago was just one year. The researchers did this by mapping and analyzing soot deposits from fires made by humans in the cave.                                                                                                           , "The soot is deposited to the roof of the rock shelter, and when there was a period of no one living there, there's no soot deposition," explained Stringer.                                                                                                                                                                                                                                            , Lead author Ludovic Slimak, a researcher at the French National Centre for Scientific Research and the University of Toulouse who has been working on the site for 30 years, said he believed the two groups must have exchanged knowledge in some way.                                                                                                                                                 , Right from the beginning of their occupation, Slimak said, the modern humans were using flint sourced from hundreds of kilometers away, the stone tools found in the cave show. That knowledge likely came from the indigenous Neanderthals, Slimak explained.                                                                                                                                          , "The territory appears to be immediately well known by Homo sapiens, and they immediately know flint sources that are very localized," he said.                                                                                                                                                                                                                                                         , "What precisely was the interaction? We just don't know. We have no idea whether it was good relationship or a bad relationship. Was it a group exchange or did they have (Neanderthal) scouts to show and guide them?"                                                                                                                                                                                 , The researchers dated the site's layers using radiocarbon and luminescence techniques, which measure the last time grains of mineral in rock were exposed to sunlight. The layer containing the Homo sapiens child's tooth spans 56,800 to 51,700 years ago. In different layers, the scientists discovered eight other teeth that belonged to Neanderthals.                                            , Untangling the human story is a complicated endeavor, but it's largely accepted that modern humans originated in Africa and made their first successful migration to the rest of the world in a single wave between 50,000 and 70,000 years ago.                                                                                                                                                        , Different ancient hominins existed and coexisted before Homo sapiens emerged as the lone survivor, and there was interbreeding between different groups of early humans. Some of these groups -- like Neanderthals -- are easily identified through the fossil record and archaeological remains, but others -- like the Denisovans -- have been largely identified by their genetic legacy.            , DNA could flesh out the story                                                                                                                                                                                                                                                                                                                                                                           , Marie-Hélène Moncel, a research director at the French National Museum of Natural History in Paris, said that the discovery of just one modern human tooth wasn't enough to definitively push back the dates of the arrival of Homo sapiens in Europe. She said other fossilized human remains were needed to be sure of this paper's findings.                                                         , "Teeth are not enough, we must find post-cranial or cranial remains to be sure," said Moncel, who wasn't involved in the research.                                                                                                                                                                                                                                                                      , It's possible that DNA -- either directly from the teeth or through groundbreaking new techniques that allow DNA found in sediment to be sequenced -- could flesh out the story and tell us how the pioneering group of early modern humans were related to the ones that arrived later and whether the Neanderthals who lived in the cave had the same origins.                                        , The DNA might show evidence of interbreeding between the two groups. In Bacho Kiro cave in Bulgaria, where the previously oldest evidence of Homo sapiens in Europe was found, the DNA of those early modern humans was about 3% Neanderthal.                                                                                                                                                           , Teeth preserve well in the fossil record, and their bumps and groves are a bit like fingerprints for archaeologists, giving clues to ancestry and behavior. The shape of the tooth and its internal structure strongly suggested it belong to a modern human child even though the tooth was damaged, the researchers said.                                                                             , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-10 02:54:21 </td>
   <td style="text-align:left;"> Swiss 10Y Bond Yield Eases from 7-Year High </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond fell to 0.25% from the 7-year highof 0.33% touched on February 8th, in line with higher higher global bond prices as jitters over accelerated policy tightening among major central banks momentarily waned. Bank of France Governor de Galhau stated investors may have overreacted to what was seen as a hawkish pivot by the ECB. At the same time, the Swiss National Bank remains committed to its ultra-loose monetary policy, as the latest labor data indicated that unemployment did not increase despite the Covid infection wave in January, while consumer inflation remains moderate. In its latest survey economic survey of Switzerland, the OECD noted that the Swiss economy proved to be very resilient to the ongoing health crisis and should be in no rush to tighten monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/09/tech/spacex-starlink-solar-storm-satellites-scn/index.html </td>
   <td style="text-align:left;"> 2022-02-10 02:51:08 </td>
   <td style="text-align:left;"> SpaceX will lose up to 40 satellites it just launched due to a solar storm - CNN </td>
   <td style="text-align:left;"> New York (CNN Business)Up to 40 of SpaceX's Starlink satellites are expected to fall out of orbit thanks to some inopportune timing: The company launched the satellites directly into a solar storm.                                                                                                                                                                                                                                                                                                                                                                                                                                  , A batch of 49 Starlink internet satellites were on SpaceX's latest launch on February 3, and now the company is expecting to lose most of them because they hit a space weather event known as a geomagnetic storm. This event occurs when streams of charged particles, or solar winds, emitted from the sun interact with Earth's magnetic field. The energized particles can heat up the upper atmosphere, causing it to thicken. (Yes, there is still atmosphere in areas of outer space closest to home. The Earth's atmosphere fades out over thousands of miles.)                                                               , In this case, the storm impacted the area of orbit where SpaceX's newest Starlink satellites were deployed, and it made the atmosphere dense enough that the satellites weren't able to maneuver their way up to their intended orbit.                                                                                                                                                                                                                                                                                                                                                                                                 , It's not clear how large the financial impact will be. SpaceX has not shared how much it costs to build a Starlink satellite, though the company's president, Gwynne Shotwell, said in 2019 that the price was well below $1 million a piece.                                                                                                                                                                                                                                                                                                                                                                                          , The satellites that SpaceX launched last week were expected to join roughly 2,000 Starlink satellites that it has already launched as the company works to drastically ramp up its global space-based internet business — a first-of-its-kind venture that hopes to allow people in even the most remote areas of the world to gain high-speed internet access. SpaceX has said it will eventually need as many as 42,000 satellites, all working in coordination to blanket the globe in connectivity, in order to deliver high-speed, uninterrupted service. As of January, the service had about 145,000 users across 25 countries. , It's not totally clear how SpaceX evaluated the weather in space ahead of last week's launch. The company did not respond to a request for comment, and rarely responds to reporters' inquiries.                                                                                                                                                                                                                                                                                                                                                                                                                                       , But rocket launches have been delayed for space weather events before, said Bill Murtagh, the program coordinator at the National Oceanic and Atmospheric Administration's Space Weather Prediction Center. And launch officials routinely keep a close eye on space weather before rockets take off.                                                                                                                                                                                                                                                                                                                                  , "Different companies have their own criteria" for deciding whether or not a space weather event will impact their launch, Murtagh added.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , James Spann, the head of space weather within NASA's division that studies the sun, also said that it's difficult to predict exactly how such a geomagnetic storm could've impacted Starlink. Because the storm wasn't all the severe, it's not unreasonable to think it would not have had an impact on the launch.                                                                                                                                                                                                                                                                                                                   , And though the loss of 40 satellites isn't ideal, Spann emphasized that the data NASA and NOAA will gain from observing how the Starlink satellites reacted the storm will help improve space weather modeling in the future.                                                                                                                                                                                                                                                                                                                                                                                                          , "That is the silver lining," he told CNN Business. "We're going to use the data points to ensure that in the future the chances of success are even better than they already are now."                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Still, GPS data from the Starlink satellites "suggests the escalation speed and severity of the storm caused atmospheric drag to increase up to 50% higher than during previous launches," SpaceX wrote in an update on its website. "The Starlink team commanded the satellites into a safe-mode where they would fly edge-on (like a sheet of paper) to minimize drag—to effectively 'take cover from the storm,'" according to the company.                                                                                                                                                                                         , But early data suggests that the added drag from the storm prevented the satellites from turning off the safe mode and "up to 40 of the satellites will reenter or already have reentered the Earth's atmosphere," the SpaceX post reads.                                                                                                                                                                                                                                                                                                                                                                                              , The company noted that the failed satellites shouldn't pose any risk to other satellites during their descent, and they should disintegrate as they slam into the thickest part of Earth's atmosphere so that they don't threaten any people or property on the ground.                                                                                                                                                                                                                                                                                                                                                                , All of those safety measures are by design, the company said. SpaceX has said it intentionally deploys its Starlink satellites at a lower altitude than their intended orbit so that if a satellite malfunctions, it wouldn't be left to fly uncontrolled through orbit for very long — a key space debris mitigation effort.                                                                                                                                                                                                                                                                                                          , But deploying at a lower altitude may also be a key reason that these Starlink satellites were so badly affected by the geomagnetic storm.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , And in a new filing with the Federal Communications Commission, which must approve satellite launches, NASA raised concerns that the sheer number of satellites that SpaceX has proposed could become a threat to the International Space Station and other important assets in space.                                                                                                                                                                                                                                                                                                                                                 , It's all about space weather                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Every decade or so, the sun completes a solar cycle of calm and stormy activity and begins a new one.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Eruptions like solar flares and coronal mass ejection events — when the sun's outermost atmosphere spits out plasma and magnetic fields — can impact the power grid, satellites, GPS, airlines, rockets and astronauts in space. Space weather is known to cause disruptions in earthly communications systems by affecting radio frequencies.                                                                                                                                                                                                                                                                                         , Our current solar cycle, Solar Cycle 25, officially began in December 2019. Right now, we're leaving a period of relative calm and the current cycle is expected to reach its most active space weather phase in 2025.                                                                                                                                                                                                                                                                                                                                                                                                                 , On a scale from one to five, the geomagnetic storm that affected the Starlink satellites last week was a two, which is fairly mild, Murtagh said. The sun puts off "several hundred" storms of that magnitude every 11-year solar cycle, Murtagh said.                                                                                                                                                                                                                                                                                                                                                                                 , "The beautiful visible manifestation [of space weather] is the northern lights that everyone loves — that's the nice, pretty part. But the consequences, as we found out on Friday, can be quite significant to some of these technologies," Murtagh said.                                                                                                                                                                                                                                                                                                                                                                             , CNN's Ashley Strickland contributed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/fox-earnings-higher-revenue-ad-sales </td>
   <td style="text-align:left;"> 2022-02-10 02:46:38 </td>
   <td style="text-align:left;"> Fox posts higher revenue on ad sales strength </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                    , Fox Corp., parent of Fox News and the Fox broadcast network, reported higher revenue in the latest quarter, as advertising sales continued to improve driven by its news programming, live sports and streaming platforms.                                                                                                                                                                                                                           , Executive Chairman and Chief Executive Lachlan Murdoch said the company didn’t plan to veer away from its focus on live news, sports and advertiser-supported streaming services.                                                                                                                                                                                                                                                                    , "We have not been convinced to deviate from areas where we cannot be a leader," Mr. Murdoch said.                                                                                                                                                                                                                                                                                                                                                    , Commercials for sports betting were a significant factor in the increased ad revenue. Mr. Murdoch said there was 50% more local sports betting in the quarter than the company had in all of the fiscal year ended June 30.                                                                                                                                                                                                                          , Mr. Murdoch also praised the performance of Fox News, reminding analysts that a year ago, he was fielding questions about whether the network had peaked and would see its dominance slip due to the emergence of newer competitors including NewsMax and One America Network, which target its core conservative audience.                                                                                                                          , Lachlan Murdoch, co-chairman News Corp and executive chairman of 21st Century Fox, poses for a picture on the red carpet for the sixth annual 2018 Breakthrough Prizes at Moffett Federal Airfield, Hangar One in Mountain View, California, on Sunday, De (Nhat V. Meyer/Bay Area News Group/Digital First Media Group/Bay Area News via Getty Images / Getty Images)                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                          , "Fox News leads by a wide margin," Mr. Murdoch said, adding that the network has gained market share among younger, Democratic and independent viewers. "We simply could not be better placed as we look forward to the midterm elections."                                                                                                                                                                                                          , Tubi, a free, advertiser-supported streaming service that Fox acquired in 2020, had its strongest quarter to date, the company said. The service had 3.6 billion hours streamed in 2021, a 40% increase from 2020. Fox has been investing in more original content for Tubi, as well as beefing up its library.                                                                                                                                      , Revenue at Fox increased nearly 9% to $4.44 billion for the quarter ended Dec. 31, topping analysts’ consensus expectations of $4.25 billion.                                                                                                                                                                                                                                                                                                        , Fox’s advertising revenue rose about 6% over last year due to pricing strength at its Fox network, as well as from live sports and Tubi.                                                                                                                                                                                                                                                                                                             , The company’s cable programming unit, which includes the Fox Business Network and Fox Sports 1 channel as well as Fox News, generated $1.64 billion in revenue, a 10% increase from the same quarter last year. Contractual price increases, including distribution agreement renewals, helped boost affiliate revenues. Advertising revenue also increased at the division thanks to pricing power at Fox News and its national sports networks.    , Fox Nation, the direct-to-consumer streaming platform operated by Fox News, logged higher subscription revenue compared with last year. The recently launched Fox Weather also landed new distribution deals with YouTubeTV, Amazon News and Roku.                                                                                                                                                                                                   , Revenue from Fox’s TV stations rose to $2.76 billion from $2.56 billion in the year-earlier period due to an increase in advertising revenues, which benefited from live sports, growth at Tubi and the continuing recovery from Covid-19 restrictions in local markets.                                                                                                                                                                             , The company recorded higher expenses in the segment as it recognized higher sports and entertainment-programming rights amortization at the Fox network and increased its digital spending at Tubi.                                                                                                                                                                                                                                                  , Fox News parent Fox Corp. and Wall Street Journal parent company News Corp share common ownership.                                                                                                                                                                                                                                                                                                                                                   , Main entrance to News Corporation / Fox News headquarters in New York.  ( Erik McGregor/LightRocket via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                              , The company posted a loss attributable to stockholders of $85 million, or 15 cents a share, for the fiscal second quarter, compared with a profit of $224 million, or 37 cents a share, in the year-earlier period.                                                                                                                                                                                                                                  , Fox Corp. attributed the loss to a change in the fair value of its investment in the sports betting and gaming provider Flutter Entertainment PLC. Fox Corp. is also currently involved in arbitration with Flutter over its efforts to acquire Flutter’s 18.6% stake in sports-betting firm FanDuel Group. As part of its investment in Flutter, Fox received an option to buy the FanDuel stake, but the sides differed on the pricing methodology., Fox had an adjusted profit of 13 cents a share, which came ahead of analysts’ estimates, according to a FactSet poll.                                                                                                                                                                                                                                                                                                                                , Click here to read more on the Wall Street Journal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/duke-energy-aims-full-exit/story.aspx?guid={F7670406-1FDF-4CCB-88E7-2E21F6584D63}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-10 02:43:54 </td>
   <td style="text-align:left;"> Duke Energy aims for full exit from coal by 2035 - MarketWatch </td>
   <td style="text-align:left;"> Duke Energy Corp. 
        DUK,
        +0.29%
       said Wednesday that it targets energy generated from coal to be just 5% of total energy generation by 2030, and aims at a full exit from coal by 2035. Currently, the company coal fuel represents about 27% of its total energy generation. The electric utility said the targets are part of an expansion of its clean energy action plan, in which its 2050 net-zero goals now include Scope 2 and Scope 3 emissions. Scope 2 emissions include indirect emissions from power the company purchases from others and Scope 3 emissions include indirect emissions from others in the company's value chain. The company said it has already retired 56 coal units, representing 7,500 megawatts, since 2010, and expects to retire an additional 862 megawatts by 2024. Duke Energy's stock, which tacked on 0.2% in afternoon trading, has gained 2.7% over the past 3 months, while the SPDR Utilities Select Sector ETF [s:xlu] has advanced 3.3% and the S&amp;P 500 
        SPX,
        +1.45%
       has slipped 2.3%., Shares of Facebook-parent Meta Platforms Inc. bounced Wednesday off a 20-month low, after a widely followed technical indicator sank to the most oversold level seen since just a few months after the company went public 10 years ago.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/09/feds-mester-says-each-meeting-is-going-to-be-in-play-for-rate-hikes-this-year.html </td>
   <td style="text-align:left;"> 2022-02-10 02:24:51 </td>
   <td style="text-align:left;"> Fed's Mester says 'each meeting is going to be in play' for rate hikes this year </td>
   <td style="text-align:left;"> , Cleveland Federal Reserve President Loretta Mester laid out an aggressive plan for reducing easy-money policies this year, saying the central bank will be ready to hike rates at any meeting and should be looking at shedding mortgage-backed securities it is holding.                                                         , "Each meeting is going to be in play," Mester said Wednesday at a virtual event hosted by the European Economics and Financial Centre. "We're going to assess conditions, we're going to assess how the economy's evolving, we're going to be looking at the risks, and we're going to be removing accommodation."                , Her comments come with markets widely expecting the Fed to raise its benchmark short-term borrowing rate at its March meeting. Traders are pricing in at least four more increases through the course of the year.                                                                                                                , Mester said she sees a March hike lately but doesn't expect to raise the rate by more than 25 basis points, or a quarter percentage point, as is the norm. But she was emphatic that it's time for the central bank to start reversing the historically accommodative measures it took during the Covid pandemic crisis.          , "I don't like taking anything off the table," she said. "I don't think there's any compelling case to start with a 50 basis point [increase]. Again, we've got to be a little bit careful. Even though you can well telegraph what's coming, when you take that first action, there's going to be a reaction."                    , Mester is a voting member this year of the Federal Open Market Committee, which sets interest rates and other monetary policy measures. She noted she will be watching inflation closely. If it declines over the course of the year, that would lead to fewer rate hikes, while an acceleration would prompt more hawkish action., Morgan Stanley picks Asia chip stocks that will be in 'pole position' when tech speeds up again                                                                                                                                                                                                                                   , Bill Miller says he's thinking about buying Peloton. Here's why                                                                                                                                                                                                                                                                   , JPMorgan pegs bitcoin’s value at $38,000, says NFTs are set to dominate digital assets                                                                                                                                                                                                                                            , Another big question for the Fed this year is in how it will start reducing the portfolio of bonds it has acquired through monthly purchases. The central bank's total balance sheet is close to $9 trillion, having doubled during the pandemic.                                                                                 , The Fed is likely to allow some of the proceeds from its holdings to roll off each month while reinvesting the rest. However, Mester advocated a more active approach, in which the Fed would sell outright some of the $2.66 trillion in mortgage-backed securities it is holding.                                               , In the last balance sheet reduction, which ran from 2017 to 2019, it used a passive roll-off.                                                                                                                                                                                                                                     , Like other officials, Mester noted the conditions are different this time: The holdings are far larger and the economy is in a stronger position, so the balance sheet reduction can be done more quickly.                                                                                                                        , She advocated that the central bank shed its mortgage holdings and focus on the Treasury market.                                                                                                                                                                                                                                  , "I do think it's important that the Fed not be allocating its credit to particular sectors," Mester said.                                                                                                                                                                                                                         , The Fed's monthly asset purchases have been cut back to $60 billion and are expected to end completely by March. Market opinion is coalescing around the balance sheet reduction beginning in the summer.                                                                                                                         , Earlier in the day, Atlanta Fed President Raphael Bostic also called for several rate hikes this year and a quick reduction of the balance sheet holdings.                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-10 02:24:00 </td>
   <td style="text-align:left;"> French 10Y Bond Yield Eases from 2-Year High </td>
   <td style="text-align:left;"> The yield on the French 10-year OAT eased to below 0.7% from the two-year high of 0.74% touched on February 8th, amid eased fears of accelerated monetary policy tightening after ECB policymakers suggested the central bank is not as hawkish as previously thought. Bank of France Governor Francois Velleroy de Galhau suggested that investors might have overreacted to comments made by ECB policymakers following the bank’s meeting this month, while President Lagarde emphasized that policy tightening would be gradual and only begin after the end of bond purchases. Meanwhile, data from INSEE suggests that the growth in the French economy will slow in the first quarter of 2022 due to restrictions brought by the wave of coronavirus cases the country faced. Early estimates believe the French GDP will grow by 0.3% on the quarter during Q1, while the economy is expected to grow by 0.6% during Q2. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/09/4-scams-that-may-cost-you-this-tax-season.html </td>
   <td style="text-align:left;"> 2022-02-10 02:19:21 </td>
   <td style="text-align:left;"> These scams may cost you this tax season. Here's what to do if you are a victim </td>
   <td style="text-align:left;"> , Tax season is underway — and the IRS is warning of a likely increase in scams targeting taxpayers.                                                                                                                                                                                                                                       , Agency officials are sounding the alarm on "IRS impersonation scams," in which criminals pose as IRS agents to try stealing money or personal information. The latter can lead to identity theft — which allows crooks to file tax returns in victims' names and steal their tax refund, in addition to other negative financial effects., Common frauds this tax season may include text-message scams, e-mail schemes, phone scams and unemployment fraud, according to an IRS bulletin issued Thursday.                                                                                                                                                                          , More from Personal Finance:Here's who can file taxes to the IRS for free this yearFeds won't seize child tax credit for past-due student loansWhat to know about tax credits and deductions                                                                                                                                              , These cons can happen throughout the year, but tax season is an especially ripe time for fraudsters.                                                                                                                                                                                                                                     , "With filing season underway, this is a prime period for identity thieves to hit people with realistic-looking emails and texts about their tax returns and refunds," IRS Commissioner Chuck Rettig said in the memo.                                                                                                                    , Here are some common scams to watch for.                                                                                                                                                                                                                                                                                                 , Text hoaxes involve messages with bogus links that claims to be IRS websites or other online tools. Last year, for example, there was an increase in texts referencing Covid-19 and stimulus payments.                                                                                                                                   , The IRS doesn't use texts (or social media platforms) to discuss personal tax issues, such as bills or refunds.                                                                                                                                                                                                                          , "The IRS reminds everyone NOT to click links or open attachments in unsolicited, suspicious or unexpected text messages — whether from the IRS, state tax agencies or others in the tax community," according to the agency bulletin.                                                                                                    , E-mail schemes are similar — they involve victims getting an unsolicited message appearing to be from the IRS or a program closely linked to the agency. However, the IRS doesn't use email to request personal or financial information.                                                                                                , The tax bureau initiates most contacts via regular mail delivered by the U.S. Postal Service.                                                                                                                                                                                                                                            , (The IRS will call or come to a home or business in some circumstances, such as when a taxpayer has an overdue tax bill or delinquent tax return. But they'll generally first receive several letters from the IRS in the mail.)                                                                                                         , Criminals generally leave pre-recorded, urgent messages requesting a call back, and threaten victims with an arrest warrant, deportation or revocation of licenses if they don't.                                                                                                                                                        , Thieves can mask the true caller ID number to make it seem like an IRS office, local sheriff's office, state department of motor vehicles or other federal agency is calling.                                                                                                                                                            , Callers may be requesting payment for an owed tax bill. However, the IRS will generally first mail a bill to taxpayers, according to the agency. And all tax payments should never be made payable to third parties — only to the U.S. Department of the Treasury.                                                                       , The IRS will never ask for credit or debit card numbers over the phone, or demand immediate payment using a specific payment method like prepaid debit card, gift card or wire transfer. The agency also lets taxpayers question or appeal the owed amount.                                                                              , Individuals who think they may owe a bill can examine the balance in their online account.                                                                                                                                                                                                                                               , There's been an uptick in unemployment fraud during the pandemic. Organized crime rings and other thieves use stolen personal data to file fraudulent unemployment claims in victims' names.                                                                                                                                             , Victims may only discover the identity theft at tax time, when they receive a 1099-G tax form detailing unemployment compensation they never collected. Unemployment benefits are taxable income at the federal level, and in most states.                                                                                               , Workers who get an inaccurate 1099-G should report it to the issuing state agency and request a corrected Form 1099-G.                                                                                                                                                                                                                   , Taxpayers may only discover an identity theft when filing a tax return electronically and finding a return has already been filed with their Social Security Number. The IRS may also send a letter about a suspicious return filed with their SSN.                                                                                      , The IRS recommends a few steps:                                                                                                                                                                                                                                                                                                          , Identity-theft victims should also consider:                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2022-02-10 02:05:00 </td>
   <td style="text-align:left;"> Russia GDP Growth Slows in December </td>
   <td style="text-align:left;"> Russia's gross domestic product advanced 4.3 percent year-on-year in December of 2021, slowing from an upwardly revised 5.3 percent rise in the previous month. Output grew at a softer pace mostly in agriculture (1.3 percent vs 12 percent in November) and industry (6.1 percent vs 7.6 percent). Meanwhile, construction (8.4 percent vs 8.7 percent), retail (5.4 percent vs 3.1 percent), services (11.8 percent vs 15.5 percent) and food services (17.4 percent vs 10.6 percent) continued to expand solidly. In 2021, the Russian economy grew 4.6 percent, after contracting 2.7 percent in 2020 amid the pandemic shock and associated lockdown restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/pelosi-stock-trading-ban-government-wide </td>
   <td style="text-align:left;"> 2022-02-10 01:53:41 </td>
   <td style="text-align:left;"> Pelosi wants any stock trading ban to be 'government wide' </td>
   <td style="text-align:left;"> Pennsylvania Rep. Brian Fitzpatrick says 'it better happen' on 'The Evening Edit.'                                                                                                                                                                                                                                                                                        , House Speaker Nancy Pelosi, D-Calif., said Wednesday the House is making progress on legislation to curb stock tradings in Congress, but added that she's insisting any stock legislation apply to the Supreme Court too.                                                                                                                                                 , "It has to be government-wide," Pelosi said Wednesday of the criteria she wants to see in any stock legislation.                                                                                                                                                                                                                                                          , The Supreme Court in Washington on Nov. 6, 2020. (AP Photo/J. Scott Applewhite / AP Newsroom)                                                                                                                                                                                                                                                                             , "The third branch of government, the judiciary, has no reporting," Pelosi added at a Capitol news conference. "The Supreme Court has no disclosure. It has no reporting of stock transactions. And it makes important decisions every day."                                                                                                                               , PELOSI REVERSES COURSE, SIGNALS OPENNESS TO BANNING CONGRESSIONAL STOCK TRADES                                                                                                                                                                                                                                                                                            , Pelosi, who was once opposed to a ban on stock trades for members of Congress, has said in recent weeks she's open to restrictions if members want such legislation. She signaled last month she has concerns about the Supreme Court not having to disclose stocks as lawmakers must do now, but her comments Wednesday indicate her demands in shaping the legislation. , House Speaker Nancy Pelosi conducts her weekly news conference in the Capitol Visitor Center on Aug. 6, 2021. (Tom Williams/CQ-Roll Call, Inc via Getty Images)  (Getty Images)                                                                                                                                                                                           , Pelosi also said she wants an increase in fines for violations of the current STOCK Act to serve as a better deterrent.                                                                                                                                                                                                                                                   , Under the STOCK Act, passed in 2012, it's illegal for members of Congress and their families to profit from inside information, and it requires lawmakers to report stock trades to Congress within 45 days. In some recent cases, lawmakers have failed to report their trades altogether.                                                                               , MICHIGAN DEMOCRAT INTRODUCES LEGISLATION TO UNIONIZE CONGRESSIONAL STAFF                                                                                                                                                                                                                                                                                                  , The discussion comes as members of the House and Senate are pushing a range of bipartisan proposals on how to stop members from trading individual stocks. The effort kicked off following reports that senators from both parties traded health care stocks in the early days of the pandemic after they received closed-door briefings about COVID-19.                  , It's unclear how far the House legislation will go, and whether it will affect spouses. Pelosi doesn't trade stocks herself, but her husband, Paul, does. He's the owner and operator of a San Francisco investment firm that has helped the Pelosis amass enormous wealth.                                                                                               , Night falls at the Capitol in Washington, Dec. 2, 2021. (AP Photo/J. Scott Applewhite) (AP Newsroom)                                                                                                                                                                                                                                                                      , Pelosi is worth an estimated $114 million, according to her 2018 personal financial disclosure, making her the sixth-richest member of the House and the 10th richest member of Congress, according to data tracked by the Center for Responsive Politics.                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                               , Pelosi said she's relying on the House Administration Committee to come up with the legislation.                                                                                                                                                                                                                                                                          , "It's complicated and members will figure it out, and then we'll go forward with what the consensus is," Pelosi said Wednesday, adding that she expects "they'll have it pretty soon."                                                                                                                                                                                    , Banning stock trades by members of Congress is popular with the public. A Fox News poll conducted in January found widespread support for that, as 72% of Democrats and 69% of Republicans favor the ban.                                                                                                                                                                 , FOX Business' Megan Henney contributed this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/romania/interest-rate </td>
   <td style="text-align:left;"> 2022-02-10 01:51:12 </td>
   <td style="text-align:left;"> Romania Raises Interest Rates by 50bps </td>
   <td style="text-align:left;"> The National Bank of Romania raised its benchmark interest rate by 50 bps to 2.5% at its February meeting, above expectations. The board raised its lending facility rate by 50bps to 3.5% and its deposit rate elevated by 50 bps to 1.5%. The bank said it will maintain firm control over money market liquidity and aims to restore and maintain the existing levels of minimum reserve requirement ratios on both leu- and foreign currency-denominated liabilities of credit institutions. The NBR Board decisions aim to anchor inflation expectations over the medium term, as well as to foster saving through higher bank rates, so as to bring back the annual inflation rate in line with the 2.5 % ±1% flat target on a lasting basis, in order to achieving sustainable economic growth in the context of the fiscal consolidation process. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-10 01:51:04 </td>
   <td style="text-align:left;"> Russia Jobless Rate Remains at 4.3% </td>
   <td style="text-align:left;"> Russia’s unemployment rate remained at 4.3 percent in December of 2021, unchanged from the previous three months and in line with market forecasts. The number of unemployed fell by 15 thousand from a month earlier 3.22 million and those officially registered as unemployed declined by 93 thousand to 0.92 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-10 01:51:00 </td>
   <td style="text-align:left;"> South African 10Y Bond Yield Eases to Near 1-Week Low </td>
   <td style="text-align:left;"> South Africa's benchmark 10-year bond yield was at 9.2%, its lowest since February 3rd, tracking a global retreat in bond yields and as investors reassessed domestic risks after power utility Eskom suspended power cuts. Meanwhile, South Africa's economic outlook remains fragile, amid ongoing concerns around the evolution of the pandemic, higher inflation and interest rates, electricity supply constraints and policy uncertainty. Investors now wait for the State of the Nation Address (SONA) for any updates about the country's recovery, political situation and structural economic reforms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 01:37:51 </td>
   <td style="text-align:left;"> Spanish Stocks Extend Gains </td>
   <td style="text-align:left;"> The IBEX 35 Index closed 2% higher at 8,846 on Wednesday, the strongest session since the beginning of December, tracking rises in European and US equity markets amid strong earnings reports as investors await fresh US inflation figures for hints on the trajectory of monetary policy tightening this year. Siemens Gamesa (3.8%) led the gains, partially rebounding from losing over 6% on the week, after Siemens Energy CEO Christian Bruch said current market conditions led to problems that cannot be solved in a few months for the wind turbine manufacturer, but still hoped for steady improvement in the future. Amadeus (3.6%) and Aena (2.9%) also traded in the green, while IAG (4.6%) extended its rally as European countries continue to ease their pandemic related restrictions. On the political front, the Spanish government increased the country’s minimum wage to EUR 1,000 monthly from EUR 965, to paid 14 times during the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ghana/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-10 01:35:10 </td>
   <td style="text-align:left;"> Ghana December Inflation Rate at Over 5-Year High </td>
   <td style="text-align:left;"> Ghana’s annual inflation rate quickened for the eighth consecutive month to 13.9% in January of 2022, from 12.6% in December of 2021. That was the highest rate since December of 2016,  exceeding the Bank of Ghana's target band of 6% to 10% for a fifth straight month. Prices advanced faster for both non-food (14.1% vs 12.5% in December), in particular housing &amp; utilities (28.7%) and transport (17.4%); and food products (13.7% vs 12.8%). On a monthly basis, consumer prices inched up 2.1 percent, the most since April of 2020, after a 1.2 percent rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/09/stocks-making-the-biggest-moves-midday-cvs-enphase-energy-chipotle-lyft-and-more.html </td>
   <td style="text-align:left;"> 2022-02-10 01:25:20 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: CVS, Enphase Energy, Chipotle, Lyft and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                    , CVS Health — Shares of the drugstore chain fell 5.4% even after the company topped expectations in its fourth-quarter earnings report, as demand for at-home Covid tests and vaccines lifted overall store sales. The drugstore chain administered more than 20 million Covid vaccines in the three-month period, a significant jump from the number it gave in each of the prior two quarters., Enphase Energy — The energy stock surged 12% following the company's quarterly earnings, which showed record revenues for the fourth quarter and beats on both the top- and bottom-lines. Enphase earned an adjusted 73 cents per share, as compared with estimates of 58 cents. Revenue came in at $412.7 million, compared to expectations of $397 million.                                  , Chipotle — Shares of the burrito chain jumped 10.2% after the company topped Wall Street's estimates for its fourth-quarter earnings and met its expectations for revenue. Chipotle also reported a 22% increase in net sales to $1.96 billion for the quarter, meeting expectations. Same-store sales rose 15.2%, surpassing StreetAccount estimates of 14.8%.                                , The Container Store Group — The home retailer saw its shares tumble 22.7% after it reported sales for its fiscal third quarter were lower by 3% than the same time in the previous year and that online sales fell 36% as compared with the year before. The Container Store still reported better-than-expected profits for the quarter.                                                      , NCR Corp — Shares of the financial services software maker rose 14.3% even after the company said it would launch a review of its operations, including "alternatives available to enhance both NCR's value and shareholder returns." It also reported a quarterly beat on both earnings and revenue.                                                                                          , Penn National Gaming — Shares of the gaming and casino stock rose 5.6% after Susquehanna upgraded it to positive from neutral, saying Penn's digital segment can "inflect positively" and has "been de-risked at current trading levels."                                                                                                                                                      , Lyft — Shares of the ride-hailing company rose 6.8% after beating on the top and bottom lines of its quarterly results. Gains were capped by the fact that Lyft reported fewer active riders than in the prior quarter.                                                                                                                                                                        , Joby Aviation — The aircraft company's shares jumped 7.1% after Morgan Stanley reiterated its buy rating on it and pointed to its partnership with Uber as an opportunity to elevate growth.                                                                                                                                                                                                   , Virgin Galactic — Virgin Galactic shares rose 4.9% even after Bernstein lowered its price target on the stock to $10 from $22, saying it worries about market appetite for space tourism investing and noting talent retention and access to capital as potential risks.                                                                                                                       , General Motors — Shares of GM rebounded Wednesday after pulling back the previous session following a downgrade from Morgan Stanley. The stock rallied 2.5%, even as another firm, Nomura, also downgraded the stock.                                                                                                                                                                          ,  — CNBC's Maggie Fitzgerald, Yun Li and Hannah Miao contributed reporting.                                                                                                                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 01:11:00 </td>
   <td style="text-align:left;"> South African Stocks End at Fresh Record High </td>
   <td style="text-align:left;"> The JSE FTSE all Share index extended gains for a fourth straight session and closed 0.8% up at a new record high of 76,679 on Wednesday, helped by a jump in shares of paper and packaging producer Sappi after the release of its strong first-quarter results. At the same time, investors digested another batch of corporate results in the US and awaited fresh US inflation data on Thursday that could influence the pace of Federal Reserve policy tightening. Domestically, South Africa's SACCI business morale hit a 3-month high in January, amid the easing of Covid-19 restrictions and the end of the travel ban imposed by several countries. Now, all eyes turn to mining and manufacturing data set to be released tomorrow, while South African President Cyril Ramaphosa will deliver his State of the Nation Address (SONA) later in the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Jump on Strong Earnings </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 2.7% higher at 27,129 on Wednesday, outperforming other European markets amid strong corporate earnings while investors weighed on prospects of monetary policy tightening in major central banks ahead of the US inflation reading tomorrow. Banco Bpm (8.1%) led the gains after reporting fourth quarter profits that beat expectations, largely due to cutting loan loss provisions by more than 50%, in addition to posting greater revenues driven by fees. At the same time, Cnh Industrial rose 5.6% after posting a 7% increase in revenues during the fourth quarter of 2021, surpassing market expectations and lifting recently spun-off Iveco Group (6.9%). FinecoBank (4.3%) and Buzzi Unicem (6.1%) shares also jumped from higher than expected corporate results. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 00:47:00 </td>
   <td style="text-align:left;"> European Shares Rise the Most in 2 Months </td>
   <td style="text-align:left;"> European equity markets closed deeply in the green on Wednesday, with Germany’s DAX rising 1.5% and the Stoxx 600 up 1.7%, the biggest daily gain in two months. Automakers surged 4% to lead gains as Volkswagen jumped 6.1% on the possible listing of its luxury brand Porsche AG. Also, technology stocks climbed 2.9% as government bond prices eased and shares of banks edged up 0.8% to the highest since 2018, benefitting from prospects for higher interest rates. Among single stocks, French funds manager Amundi said it already exceeded its strategic objectives for 2022; Norway's Equinor promised to pay out $10 billion to shareholders this year and reported record fourth-quarter pretax profits; Dutch payments company Adyen NV  reported a 51% jump in core earnings; Danish jewelry maker Pandora announced sales will improve this year and lifted its 2023 revenue target; and Danish stone wool maker Rockwool International posted strong quarterly results and flagged positive future earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60308494?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-10 00:46:39 </td>
   <td style="text-align:left;"> Warning over border delays when new checks kick in </td>
   <td style="text-align:left;"> There could be delays at the UK's borders later this year without prompt government action to prepare for new border checks, MPs have warned.                                                                                                                                                                                                          , A report from the Public Accounts Committee said there was potential for disruption as passenger volumes returned to normal.                                                                                                                                                                                                                           , Logistics UK backed the committee's findings saying traffic could "grind to a halt" if more wasn't done soon.                                                                                                                                                                                                                                          , The government said there had been minimal border disruption so far.                                                                                                                                                                                                                                                                                   , It continued to ensure businesses received the support they needed to trade effectively with Europe and seize new opportunities, a government spokesperson said.                                                                                                                                                                                       , But Meg Hillier, chair of the Public Accounts Select Committee said there was "much more work that government should be doing" to ensure the border was operating effectively and to minimise the current burden on firms trading with the EU.                                                                                                         , Logistics UK said it was calling on the government to "take action now" to ensure new post-Brexit border controls, including checks on agricultural and food products entering the UK, and biometric checks on passengers entering the EU, could be implemented smoothly in the second half of the year.                                               , "We have just enough time," said Sarah Laouadi head of European policy at the trade body. But she said firms urgently needed more information about which ports would process which products after 1 July.                                                                                                                                             , "Of course you need advance notice to act on this information," said Ms Laouadi.                                                                                                                                                                                                                                                                       , Without it "the system could potentially grind to halt" she said, with up to 29-mile-long queues at UK ports this summer.                                                                                                                                                                                                                              , In January new post-Brexit checks on goods contributed to tail-backs in Kent, due to teething troubles around the new paperwork required, Ms Laouadi said.                                                                                                                                                                                             , The MPs' report said increased costs, delays and paperwork were making it harder for UK businesses to trade as before, and while it was difficult to disentangle the impact of Covid and global economic problems, the cross party committee found Brexit had reduced the UK's trade with the EU.                                                      , John Grayson said things were already "verging on the impossible, logistically and financially" for his business, Earth Natural Foods in London.                                                                                                                                                                                                       , He has given up importing directly from EU suppliers and has dropped some specific products altogether, like one particular brand of olive oil.                                                                                                                                                                                                        , He relies on importers instead, but an order takes three weeks to arrive instead of one.                                                                                                                                                                                                                                                               , "A one tonne pallet of goods that used to cost £200, is now near to £600," he added.                                                                                                                                                                                                                                                                   , Mary Quicke, an artisan cheesemaker based in Devon said she now worries that her EU customers will run out of patience and stop taking her products if these kinds of problems persist.                                                                                                                                                                , "There are just all of these barriers to doing what used to be really, really simple which was agreeing to make a sale and then calling the haulier and off it went and you got paid," she told BBC 5 Live.                                                                                                                                            , "Of course they want our cheese, but how long do you carry on doing something you want when it's really tedious and costly and you get charged much more money?"                                                                                                                                                                                       , From 1 July extra checks on agricultural and food imports from the EU will take place at ports around the UK, but with products varying from cut flowers to ready-made lasagne, firms need to know which ports will be authorised to process which products, what the operating hours will be and how they fit with ferry schedules, Logistics UK said., The Public Accounts Committee noted that some of the required infrastructure will not be completed in time and there were still concerns around staffing, including vets.                                                                                                                                                                              , In addition, later this year travellers including HGV drivers entering the EU will need to go through biometric passport checks, involve facial recognition and fingerprint scans, as part of the EU's Entry and Exit System.                                                                                                                          , Ports such as Dover, where EU-entry checks take place on the UK side, therefore need to be adapted to avoid drivers having to get out of their vehicles and walk across lanes of traffic, Ms Laouadi said.                                                                                                                                             , The Public Accounts Committee said it was particularly concerned about what would happen when passenger traffic across the UK border returns to normal levels as the pandemic subsides.                                                                                                                                                                , The PAC report urges the government to write to the committee, within six months, setting out the timetable for its planned programme of work on the "noteworthy ambition" to create the world's most effective border by 2025.                                                                                                                        , A government spokeswoman said: "Traders have adapted well to the introduction of full customs controls on 1 January, with minimal disruption at the border and inbound freight flowing effectively through ports.                                                                                                                                      , "We are continuing to ensure that businesses get the support they need to trade effectively with Europe and seize new opportunities as we strike trade deals with the world's fastest growing markets, including one-to-one advice through the free-to-use Export Support Service."                                                                    , This report serves as a reminder that in leaving the European Union, the UK did something that no other modern economy has really done before.                                                                                                                                                                                                         , It created permanent barriers to trade with its nearest neighbours.                                                                                                                                                                                                                                                                                    , That may not have been the motivation for Brexit, not its intended purpose. But it has been the practical effect.                                                                                                                                                                                                                                      , It means small businesses in particular, which used to trade with the rest of Europe as easily as they trade with other parts of the country, have suddenly been caught in a thicket of bureaucracy.                                                                                                                                                   , But this is not just about companies that are finding it more difficult to trade. It's about companies that have given up exporting altogether.                                                                                                                                                                                                        , There is less trade now between Britain and Europe than there used to be, and it hasn't bounced back from Covid lockdowns in the way that trade between other countries has.                                                                                                                                                                           , The government says it's time to look at new markets on the other side of the world instead. But that is a very long-term plan.                                                                                                                                                                                                                        , If you have a business, has it been affected by Brexit or not? Tell us story by emailing: haveyoursay@bbc.co.uk.                                                                                                                                                                                                                                       , Please include a contact number if you are willing to speak to a BBC journalist. You can also get in touch in the following ways:                                                                                                                                                                                                                      , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or comment or you can email us at HaveYourSay@bbc.co.uk. Please include your name, age and location with any submission.                                                                                      , Investigating a rivalry with devastating consequences                                                                                                                                                                                                                                                                                                  , The ups and downs of life on the wards                                                                                                                                                                                                                                                                                                                 , Can Jay Blades now, in mid-life, tackle what he failed to learn first time round?                                                                                                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Hold to Gains </td>
   <td style="text-align:left;"> The CAC 40 Index held to early gains to close 1.5% higher at 7,131 on Wednesday, extending its rally to three consecutive sessions amid eased bond yields and strong performances in the tech and auto sectors after ECB President Lagarde said policy tightening would be gradual and only begin after the end of bond purchases. Tech shares rose 2.8%, led by STMicroelectronics (4.2%) and Atos (2.2%). The auto sector also traded in the green, as seen in Stellantis (4.1%) and Renault (2.3%) after Nissan Motor raised its operating profit target to JPY 210 billion for its fiscal year ending in March, compared to the JPY 180 billion previously estimated. Lastly, Amundi jumped 3.9% after reporting it already exceeded its strategic objectives for 2022 along with a sharp increase in revenue during 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-10 00:45:00 </td>
   <td style="text-align:left;"> London Stocks Climb to 2-Year High </td>
   <td style="text-align:left;"> The FTSE 100 rose 1% to 7,643 on Wednesday, the highest since January 2020 boosted by upbeat corporate updates. Drugmaker GSK beat quarterly forecasts and sees sales rise by 5 to 7% in 2022; homebuilder Barratt expects to build 250 more homes than its previous annual forecast; and Smurfit Kappa reported record earnings in 2021 and expects to increase prices further this year. Aside from the corporate headlines, BoE’s chief economist Huw Pill said he favored a steady approach to further tightening of monetary policy by the British central bank amid uncertainty about the economic impact of rate rises and to avoid markets expecting big swings in policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mozambique/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-10 00:41:48 </td>
   <td style="text-align:left;"> Mozambique January Inflation Rate Quickens to 7.8% </td>
   <td style="text-align:left;"> The annual inflation rate in Mozambique rose to 7.8 percent in January of 2022, from 6.74 percent in the previous month. It was the highest inflation rate since October of 2017. Main upward pressure came from prices of food &amp; non-alcoholic beverages (10.9 percent vs 9.8 percent in December), restaurants &amp; hotels (9.1 percent vs 7.2 percent), housing &amp; utilities (8.7 percent vs 9.3 percent), transport (8.1 percent vs 5.1 percent) and education (7.3 percent vs 3.6 percent). On a monthly basis, consumer prices were up 2.2 percent, the most since January of 2017, after a 1.5 percent rise in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/09/business/media/disney-earnings-bob-chapek.html </td>
   <td style="text-align:left;"> 2022-02-10 00:40:19 </td>
   <td style="text-align:left;"> Disney to Announce Earnings Amid Disney+ Concerns - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Disney said its theme parks had come roaring back despite the Omicron variant. But the company’s vast cable television business continued to shrink.                                                                                                                                                                                                                                                                                                                          , By Brooks Barnes                                                                                                                                                                                                                                                                                                                                                                                                                                                              , LOS ANGELES — Disney+ added 11.8 million subscribers worldwide in its most recent quarter to reach 129.8 million, handily beating analyst expectations, as growth at the Disney-owned services Hulu and ESPN+ pushed its portfolio toward 200 million total subscribers.                                                                                                                                                                                                      , The Walt Disney Company’s quarterly disclosure of subscriber numbers on Wednesday instantly eased investor concerns about slowing growth of Disney+, which had missed analyst projections in November. Disney shares rose more than 6 percent in after-hours trading to about $157.                                                                                                                                                                                           , Disney’s theme parks also delivered blockbuster results in the three months that ended on Jan. 1, the Omicron variant be darned, in part because of a new, paid line-skipping system.                                                                                                                                                                                                                                                                                         , Streaming remains the greatest opportunity for growth in the entertainment business. But some of the froth has evaporated as services have proliferated, making it harder for companies to meet growth expectations and resulting in overwhelmed consumers: Some of the thrill of having thousands of shows and films at one’s fingertips is gone. Analysts have also worried that the boom that services enjoyed during the coronavirus pandemic will come to an end.        , Last month, Netflix said it had added 8.3 million subscribers in its most recent quarter, instead of the projected 8.5 million, and forecast a slowdown for the current quarter compared with a year earlier. Netflix shares cratered 20 percent, dragging down Disney and other media companies with them. Netflix has 222 million subscribers worldwide.                                                                                                                    , “There is a lot of concern in the market about streaming all of a sudden,” Michael Nathanson, a leading media analyst, said last week. “People are more negative than they have been.”                                                                                                                                                                                                                                                                                        , Mr. Nathanson added that Disney+ needed to offer more content for people who were not Marvel or “Star Wars” fans and who didn’t have children. Notably, one of the standout offerings on Disney+ last quarter was Peter Jackson’s documentary series “The Beatles: Get Back.” That offering alone drove 209,000 Disney+ sign-ups in its three-day opening period, according to Antenna, a research company.                                                                   , Bob Chapek, Disney’s chief executive, told analysts on a post-earnings conference call that the amount of “general entertainment” programming on Disney+ would increase. On Wednesday, for instance, Disney+ began offering reruns of two ABC comedies, “black-ish” and “The Wonder Years,” both of which previously streamed on Hulu.                                                                                                                                        , When Disney+ was introduced in 2019, the company spent a lot of time worrying about whether certain boundary-pushing shows — ones geared toward older viewers — were appropriate to include. Early on, Disney pulled the plug on a much-anticipated “Lizzie McGuire” reboot because executives thought story lines were not child-friendly enough, for instance.                                                                                                              , Mr. Chapek, who took over from Robert A. Iger in 2020, indicated that he was willing to think outside the box. “What we have seen time and time again is that the elasticity of Disney and its brand is much greater than we might have given it credit,” Mr. Chapek said on the conference call. He added that more than half of Disney+ subscribers do not have children.                                                                                                   , At the same time, Mr. Chapek highlighted the recent success of the animated musical “Encanto,” which arrived on Disney+ just before the quarter ended. “The Book of Boba Fett,” a limited series set in the “Star Wars” universe, also began rolling out on Disney+ in December, with the company hoping to build on the momentum of “The Mandalorian,” one of the service’s top performers. Another “Star Wars” series, “Obi-Wan Kenobi,” will arrive on May 25.             , Disney said it had logged $4.7 billion in total streaming revenue in the most recent quarter, up 34 percent from a year earlier, in part because Hulu, which Disney owns with Comcast, raised subscription prices. Nonetheless, Disney’s streaming division lost roughly $600 million — about 27 percent more than a year earlier — because of costs that included content production, marketing and technology infrastructure.                                               , Operating profit at Disney Parks, Experiences and Products totaled $2.45 billion, compared with a loss of $119 million a year earlier, when some of Disney’s properties were closed because of the pandemic and others, including Walt Disney World, were capping daily attendance. Disney cited the return of its cruise line, albeit with limited capacity, as another reason for the division’s rebound.                                                                   , Higher prices at Disney parks also helped, as did the introduction of a digital tool, Genie+, that allows park visitors to drastically shorten ride wait times. It costs $15 at Disney World in Florida and $20 at Disneyland in California.                                                                                                                                                                                                                                  , “We have been blown away,” Mr. Chapek said of Genie+ purchases. (Disney World’s previous line-skipping system was free.)                                                                                                                                                                                                                                                                                                                                                      , Christine M. McCarthy, Disney’s chief financial officer, noted that attendance was strong at Disney World even though “we haven’t yet seen the return of our international guests.” Overseas visitors accounted for roughly 20 percent of the resort’s attendance before the pandemic.                                                                                                                                                                                        , Underscoring the importance of streaming growth to Disney’s future: Operating profit from broadcast and cable television, the company’s largest division, totaled $1.5 billion in the quarter, a 13 percent decline from $1.7 billion a year earlier. Disney attributed the decrease to higher content production and marketing costs and less political advertising at local stations. The division includes ESPN, ABC, Disney Channel, FX, Freeform and National Geographic., Mr. Chapek seemed to go out of his way to talk up the future of ESPN, including his excitement about an expected entry into sports betting — a signal that Disney has no plans to spin off ESPN, despite persistent speculation to the contrary.                                                                                                                                                                                                                              , All told, Disney made $1.15 billion in profit in the quarter, compared with $29 million in the same quarter in 2020. With one-time items excluded, per-share profit rose to $1.06, from 32 cents. Analysts had expected about 74 cents.                                                                                                                                                                                                                                       , Revenue was $21.82 billion, a 34 percent increase from $16.2 billion a year earlier. Analysts had predicted roughly $20.3 billion.                                                                                                                                                                                                                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-02-10 00:30:00 </td>
   <td style="text-align:left;"> Copper Hits 4-Week High </td>
   <td style="text-align:left;"> Copper futures climbed to $4.5 per tonne, the highest in four weeks boosted by concerns about supply disruptions and thin inventories. MMG Ltd said production at its Las Bambas copper mine in Peru may stop by February 20th after a local community blocked again a road used by the miner, causing the company to curtail operations. Also, China's National Development and Reform Commission outlined plans to bolster the construction of new infrastructure, a source of copper demand. Meanwhile, the dollar was under pressure, making greenback-priced metals cheaper to holders of other currencies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-10 00:22:00 </td>
   <td style="text-align:left;"> Ukraine Inflation Rate Above Expectations at 10% </td>
   <td style="text-align:left;"> The annual inflation rate in Ukraine was steady at 10 percent in January of 2022, the same as in the previous month which was the lowest in six months but still above market expectations of 9.9 percent and higher than the central bank’s medium-term target of 5 percent. Prices increased at a faster rate for food &amp; non-alcoholic beverages (14 percent vs 12.7 percent in December), transport (11.4 percent vs 11.1 percent), communication (7.5 percent vs 7.4 percent), health (6.2 percent vs 6.1 percent) and education (17.4 percent vs 17 percent). Meanwhile, lower inflation was reported for housing &amp; utilities (4.3 percent vs 9.8 percent) and furniture &amp; household goods (3.9 percent vs 4.2 percent). On a monthly basis, consumer prices rose 1.3 percent, accelerating from a 0.6 percent increase in the previous month and compared to forecasts of 1.1 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/wage-growth </td>
   <td style="text-align:left;"> 2022-02-10 00:20:50 </td>
   <td style="text-align:left;"> Russia Real Wage Growth Beats Estimates </td>
   <td style="text-align:left;"> Real wages in Russia rose 3.4 percent year-on-year in November of 2021, accelerating from a 0.6 percent increase in the previous month and easily beating market expectations of a 0.6 percent gain. Meantime, Russians' average nominal wages rose 12.1% from a year earlier to 55,639 roubles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-10 00:17:55 </td>
   <td style="text-align:left;"> Natural Gas Futures Extend Losses </td>
   <td style="text-align:left;"> Natural gas futures extended losses towards $4.1 per million British thermal units, the lowest since January 26th, as output gradually came back online and weather forecasts pointed to warmer temperatures. As the weather turns seasonally warmer, Refinitiv analysts are forecasting a 7.4 bcfd drop in US natural gas demand, including exports. Meanwhile, American export plants were consuming 12.5 bcfd of natural gas so far this month, beating January’s record high of 12.4 bcfd, as demand from Asia and Europe has steadily been running hot, especially from Europe amid the supply-cut threat from Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-02-10 00:14:07 </td>
   <td style="text-align:left;"> Loonie Gains Some Traction </td>
   <td style="text-align:left;"> The Canadian dollar gained ground against its US counterpart Wednesday, hovering around $1.268 as gains in equities and oil prices spurred renewed buying. Investors now turn their attention to a speech by Bank of Canada Governor Tiff Macklem later today that may offer new clues on the pace of central bank policy tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-10 00:08:36 </td>
   <td style="text-align:left;"> Oil Rebounds on Surprise Inventory Draw </td>
   <td style="text-align:left;"> WTI crude futures bounced back to $90 per barrel on Wednesday, after losing more than 3% in the past two sessions boosted by shrinking US crude and gasoline stockpiles. Data from the EIA Petroleum Status Report showed US crude inventories fell by 4.756 million barrels last week, against market forecasts of a 0.369-million-barrel rise. The report also showed crude stocks at the Cushing, Oklahoma, delivery hub declined for a fifth consecutive week and the most since the week ended October 22nd 2021 while gasoline inventories unexpectedly decreased for the first time in six weeks. Oil has been underperforming this week, pausing a 7-week rally, pressured from the resumption of Iran nuclear talks, which could revive an international nuclear agreement and allow Tehran's to pump more oil into markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-10 00:07:00 </td>
   <td style="text-align:left;"> Russia January Inflation Rate Hits 6-Year High </td>
   <td style="text-align:left;"> Russia’s annual inflation rate accelerated to 8.73 percent in January of 2022, from 8.39 percent in the previous month and slightly below market estimates of 8.8 percent. That was the highest rate since January of 2016. Inflation has risen sharply in 2021 and is now running at a level that is more than double the central bank's target of 4 percent, even after ten months of monetary tightening. Upward pressure came from prices of food (11.09 percent vs 10.62 percent in December), namely fruits and vegetables; non-food products (8.73 percent vs 8.58 percent), of which construction materials and electronics; and services (5.38 percent vs 4.98 percent). On a monthly basis, consumer prices advanced 0.99 percent, slightly below market forecasts of a 1.1 percent rise, and following a 0.82 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-02-10 00:02:00 </td>
   <td style="text-align:left;"> Russia Retail Sales Beat Expectations </td>
   <td style="text-align:left;"> Retail sales in Russia advanced by 5.4 percent year-on-year in December of 2021, quickening from a 3.1 percent increase in the prior month and beating market expectations of a 3.4 percent raise, Still, it was the 9th consecutive month of growth in retail activity. Main upward pressure came from sales of non-food products (7.9 percent vs 3.9 percent in November), followed by sales of food, alcoholic beverages, and tobacco (2.7 percent vs 2.2 percent). On a monthly basis, retail trade surged 20.9 percent in December, rebounding sharply from a 2.7 percent drop in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/nyc-crime-florida-real-estate-don-peebles </td>
   <td style="text-align:left;"> 2022-02-09 23:50:10 </td>
   <td style="text-align:left;"> NYC crime a boon to Florida business: Real estate developer </td>
   <td style="text-align:left;"> The Peebles Corporation founder, Chairman and CEO Don Peebles says New York City’s rising crime will prevent the city ‘coming back’ from the pandemic.                                                                                                                                                                                                                                                , New York City’s economic recovery could be seriously curbed as the city’s rising crime sends more businesses and people to Florida.                                                                                                                                                                                                                                                                   , With overall crime surging more than 38% in the first month of 2022, Peebles Corporation founder, Chairman and CEO Don Peebles says the stats "absolutely" impact the city’s real estate market.                                                                                                                                                                                                      , "I think that's going to create some problems in terms of revenue and resources for New York City and helping New York City come back from this pandemic," Peebles told FOX Business’ Maria Bartiromo on "Mornings with Maria" Wednesday.                                                                                                                                                             , Peebles, who has a multi-billion dollar real estate portfolio, claimed New York-based entrepreneurs have instead set their sights on the Sunshine State.                                                                                                                                                                                                                                              , KUDLOW: THIS IS A MAKE-OR-BREAK MOMENT FOR AMERICA                                                                                                                                                                                                                                                                                                                                                    , "It is a very big difference between the two environments," Peebles explained. "South Florida is very optimistic. People are doing business, people feel safe, especially in Miami and Palm Beach."                                                                                                                                                                                                   , Douglas Elliman CEO Dottie Herman discusses how New York City can rebuild.                                                                                                                                                                                                                                                                                                                            , Financial giants JPMorgan and Milken are both hosting separate conferences in Florida this week, according to Peebles, who added that "a lot" of business gets done down south.                                                                                                                                                                                                                       , While Peebles remains optimistic that the new Mayor Eric Adams will "step in" and "get a handle" on the city’s crime surge, he cautioned that Manhattan District Attorney Alvin Bragg could prevent progress.                                                                                                                                                                                         , "Alvin Bragg is going to need to prosecute criminals as he was elected to do," the CEO said.                                                                                                                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                           , Following President Joe Biden’s visit to address the city’s crime spike, Bragg admitted New York City is "really in crisis" in a press briefing Tuesday, but reiterated clarifications on his controversial soft-on-crime memo.                                                                                                                                                                       , The Peebles Corporation founder, Chairman and CEO Don Peebles says he believes New York City Mayor Eric Adams will get a handle on crime.                                                                                                                                                                                                                                                             , Bragg also added that he and his office needed "to do a better job" of pointing to the data, so people can understand "not only is it that the sky won’t fall, it's that we look at what our counterparts have been doing, and you look at the relative incarceration rates and then the safety rates. And you can see we can, we can do these and implement these changes and be safe, if not safer.", READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                           , Fox News’ Stephanie Pagones contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/financials-energy-sectors-most-at-risk-of-being-impacted-by-higher-interest-rates-investment-strategist </td>
   <td style="text-align:left;"> 2022-02-09 23:43:32 </td>
   <td style="text-align:left;"> Financials, energy sectors most at risk from Fed rate hikes: Investment strategist </td>
   <td style="text-align:left;"> Piper Sandler chief investment strategist Michael Kantrowitz discusses how higher interest rates will impact the economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , During an interview on "Mornings with Maria" investment strategist Michael Kantrowitz described how the Fed's interest rate hikes could impact the economy, arguing that the financial and energy sector could take the biggest hit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , STOCKS RISE AS TECH TAKES LEAD, CVS FALTERS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , MICHAEL KANTROWITZ: We're specifically talking about long-term interest rates. And so there's a general conventional wisdom that when the Fed raises interest rates, all interest rates go up and when you look back at the last seven tightening cycles since 1980. That was true in five of those cycles. Long-term interest rates did rise in two of them. However, that was not the case. And so we… dug in and looked into what was the difference in those two cycles where rates didn't rise compared to those other five? And the one thing that was very clear it was all about the momentum in the economy. And so the where the Fed is starting this tightening cycle next month, is going to be basically at the beginning of a downtrend in global growth as measured by earnings, PMI'S, confidence, business confidence. And so you really have to look at those two periods that were the exception were actually long term rates declined with the slowdown, rather than those other five examples where the economy was just starting to re-accelerate. And so, yeah, I think financials, which is by far the most popular… sector on the street, maybe next to energy is most at risk here as investors have been heavily tilted their portfolios in 2022 toward stocks that would benefit from higher rates. And if rates stop going up as we believe that's going to be imminent, and even decline in the back half of this year, then those positions are going to be underperforming, most likely., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , WATCH THE FULL INTERVIEW HERE:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Piper Sandler chief investment strategist Michael Kantrowitz provides his economic outlook and discusses how the market will respond to the Federal Reserve’s interest rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-02-09 23:42:00 </td>
   <td style="text-align:left;"> US Crude Inventories Unexpectedly Fall for 2nd Week: EIA </td>
   <td style="text-align:left;"> US crude oil inventories fell by 4.756 million barrels in the week ended February 4th, following a 1.046 million drop in the previous period and compared with market forecasts of a 0.369-million-barrel rise, data from the EIA Petroleum Status Report showed. Crude stocks at the Cushing, Oklahoma, delivery hub declined by 2.801 million and gasoline inventories decreased by 1.644 million barrels to 248.4 million barrels, the first fall in six weeks and against market expectations of a 1.623-million-barrel increase. Meanwhile, distillate stockpiles which include diesel and heating oil went down by 0.929 million barrels, less than forecasts of a 1.739-million-barrel drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-09 23:41:09 </td>
   <td style="text-align:left;"> Italian 10Y Bond Yield Eases </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP eased to 1.8% from the 20-month high of 1.9% touched on February 7th, in line with European counterparts, as fears of accelerated monetary policy tightening eased after ECB policymakers suggested the central bank is not as hawkish as previously thought. Bank of France Governor Francois Velleroy de Galhau suggested that investors might have overreacted to comments made by ECB policymakers following the bank’s meeting this month, while President Lagarde emphasized that policy tightening would be gradual and only begin after the end of bond purchases. In the meantime, investors remain attentive with Italy’s political future and large debt. While Sergio Mattarella’s re-election as head of state guaranteed political stability in the short-term, the lack of consensus displayed by the Italian lawmakers raised concerns over the government’s ability to efficiently implement reforms with EU funds amid higher borrowing costs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-02-09 23:33:00 </td>
   <td style="text-align:left;"> Soybean Prices Hit 9-Month High </td>
   <td style="text-align:left;"> Soybean futures traded almost at $16 a bushel, the highest since May amid supply concerns and as demand remains strong. The world’s largest exporters of processed soy, Argentina and Brazil, have been facing this season hot and dry conditions, which are set to substantially affect the quality and quantity of crops. Brazil is expected to export 7.5 million tonnes of soybeans in February, down from 9.923 million tonnes projected the week prior by farm consultancy ANEC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-02-09 23:30:00 </td>
   <td style="text-align:left;"> South African Rand Firmer </td>
   <td style="text-align:left;"> The South African rand was trading around 15.3 against USD, after hitting an over one-week low of 15.5 on February 7th, amid a downtick in the dollar and due to some relief after power utility Eskom suspended its latest power cuts. South Africa’s economy has been hit by energy shortages as power utility Eskom struggles to address long-standing operational and financial challenges, with the emergency program to add generation from private producers experiencing multiple delays. Meanwhile, the country's economic outlook remains fragile amid the uncertainty around the evolution of the pandemic, higher inflation and interest rates, as well as policy uncertainty. Also, the prospect of a faster policy tightening by the US Federal Reserve limited further gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/wholesale-inventories </td>
   <td style="text-align:left;"> 2022-02-09 23:01:00 </td>
   <td style="text-align:left;"> US Wholesale Inventories Rise For 17th Month </td>
   <td style="text-align:left;"> Wholesale inventories in the US advanced 2.2 percent month-over-month to $789.4 billion in December of 2021, up from a 1.7 percent increase in the prior month and above a preliminary estimate of 2.1 percent. It was the 17th consecutive month of gains, amid increases in inventories of both durable goods (2.6 percent vs 2.6 percent in November) and nondurable ones (1.6 percent vs 0.4 percent). On a yearly basis, wholesale inventories advanced 18.5 percent in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/czech-republic/stock-market </td>
   <td style="text-align:left;"> 2022-02-09 23:00:29 </td>
   <td style="text-align:left;"> Stocks in Czech Republic Hit 13-1/2-year High </td>
   <td style="text-align:left;"> PX increased to a 13-1/2-year high of 1481 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/coincident-index </td>
   <td style="text-align:left;"> 2022-02-09 22:53:38 </td>
   <td style="text-align:left;"> South Africa SACCI Business Morale at 3-Month High </td>
   <td style="text-align:left;"> South Africa’s SACCI business confidence index rose to a three-month high of 94.1 in January of 2022 from 92 in December, as external trade and retail sales recovered following the easing of Covid-19 restrictions and the end of the travel ban imposed by several countries after the discovery of the Omicron variant. Stronger new-vehicle sales and higher share prices also supported this level of confidence, while rising inflation and higher debt servicing costs had a negative impact. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-09 22:46:00 </td>
   <td style="text-align:left;"> Toronto Stocks Hits 10-Week High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, briefly hit a ten-week high before settling around 21,500 on Wednesday, a level not seen since November 25th, as upbeat earnings reignited investors’ appetite for risk. Meanwhile, a protest of Canadian truck drivers in downtown Toronto entered its twelfth day, which has left authorities struggling to find ways to put an end to the protest. On the earnings front, investors await Q4 results for Manulife Financial and Sun Life Financial after markets close. On corporate updates, National Bank analysts raised the target of TFI International to C$160 from a prior C$153 per share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-09 22:38:00 </td>
   <td style="text-align:left;"> Wall Street Rallies for a Second Day </td>
   <td style="text-align:left;"> All three major US stock indexes gained further ground Wednesday as investors digested another batch of corporate earnings results and eyed inflation data on Thursday for clues on the Federal Reserve's plans to hike interest rates. Gains were most pronounced in those growth-oriented stocks, with Meta, Tesla and Microsoft up about 2% each, while Chipmaker AMD added more than 1% after an upgrade from Daiwa Capital Markets. On the data front, mortgage applications in the US sank 8.1% in the week ended February 4th, the biggest decline in almost a year as buyers started to pull back faced with rising mortgage rates. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-10 09:35:36 UTC +8

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
   <td style="text-align:left;"> 2022-02-10 09:35:13 </td>
   <td style="text-align:left;"> $SPY weak bears cant even send this to limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:35:11 </td>
   <td style="text-align:left;"> $SPY Gasoline up to $3.39 a gallon on the east coast. Started adding longer dated puts To hedge. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:35:05 </td>
   <td style="text-align:left;"> $SPY gas prices rose 3 % in January compared to December and even higher today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:35:00 </td>
   <td style="text-align:left;"> $SPY looks like a red day tomorrow, especially after a day like today.  Then again, it all CPI in the morning?  Which way will we go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:35:00 </td>
   <td style="text-align:left;"> $SPY futes running towards circuit breaker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:54 </td>
   <td style="text-align:left;"> $SPY  epic bear trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:53 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/6CEegZU5Bsc tomorrow is the make or break catalyst … lets go spy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:43 </td>
   <td style="text-align:left;"> $SPY its just getting started folks. The most deadly bull trap ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:37 </td>
   <td style="text-align:left;"> $SPY CPI is basically the same thing interest rates so the higher the CPI the higher the interest rates which will lead to equities skyrocketing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:35 </td>
   <td style="text-align:left;"> $SPY CPI report comes out tomorrow , which is the consumer price index that tracks inflation, over 8% we can expect and increase In lumber and metal which is already going back up, predictions are at 10% , the fuck boi administration is gonna rip the band-aid off... and let everyone know they are fucked... chat tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:27 </td>
   <td style="text-align:left;"> $SPY save it you filthy animals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:26 </td>
   <td style="text-align:left;"> $SPY about to be an epic dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:17 </td>
   <td style="text-align:left;"> $SPY …inflation… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:08 </td>
   <td style="text-align:left;"> $SPY circuit breakers trip at 5% instead of 7% now, yes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:07 </td>
   <td style="text-align:left;"> $SPY you guys Remember what happened to Sanjay Gupta after he went on Rogan ? Dems don’t play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:34:05 </td>
   <td style="text-align:left;"> $SPY 480 by next friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:59 </td>
   <td style="text-align:left;"> $SPY if we heading into tmr at 420 thats would be pretty fked but jpow print us up a lil bit for some soft landing lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:57 </td>
   <td style="text-align:left;"> $SPY As long as CPI is higher than the GDP report and NFP report then we should see corporate bonds skyrocket while treasuries decrease on low inflation hopes as well as elasticity of supply and demand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:22 </td>
   <td style="text-align:left;"> $SPY futures has to dump 1-2% tonight $QQQ interesting to watch tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:22 </td>
   <td style="text-align:left;"> $SPY There was a point in time when major news outlets would quote shadowstats.com for their REAL unaltered statistics but 150% guaranteed no major outlet would dare quote them today because this is what they are saying 

• FLASH (Jan 12): Year-to-Year Increases Continued in the both the December 2021 Headline CPI-U and the ShadowStats Alternate CPI Measure, Hitting New Multi-Decade Highs

• December CPI-U Annual Inflation Hit 7.04% [up from 6.81% in November], the Steepest Inflation Pace Since June 1980 (in 40 Years), When Jimmy Carter Was President; the ShadowStats “Corrected” Alternate Estimate Hit 15.15% [up from 14.91% in November], the Steepest Inflation Rate Since June 1947 (in 75 Years)

• In like Manner, the December 2021 CPI-W (Used in Social Security Cost of Living Adjustment [COLA] Calculations, Where the 2022 COLA -- Based on Third-Quarter 2021 -- Was 5.9%) Hit a Four-Decade High of 7.81%, Highest Since 8.23% in January 1982, Reminiscent of the Days of Runaway Inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:17 </td>
   <td style="text-align:left;"> $SPY looks good 
Looks real good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:13 </td>
   <td style="text-align:left;"> $SPY Putin’s kiss is the only thing sending this to limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:13 </td>
   <td style="text-align:left;"> $SPY Bears waiting for cpi # to save them only to get slaughtered 🥵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:09 </td>
   <td style="text-align:left;"> $SPY I mean what number is good. 7.5 or more? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:02 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:33:02 </td>
   <td style="text-align:left;"> $SPY I like gap down overnight. This gap up sucks for small caps. They don&amp;#39;t move premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:59 </td>
   <td style="text-align:left;"> $SPY shorts probably going to take it down .4% instead of a limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:58 </td>
   <td style="text-align:left;"> $SPY could get some turbulence tomorrow but I think she rips faces up to monthly Opex on the 18th. Godspeed! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:46 </td>
   <td style="text-align:left;"> $SPY what is good for tomorrow and what is bad? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:45 </td>
   <td style="text-align:left;"> $SPY …can we go back to freakout levels?Either way is ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:41 </td>
   <td style="text-align:left;"> $SPY weak rug pull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:27 </td>
   <td style="text-align:left;"> $SPY 
Vix calls are PRRRRINTING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:24 </td>
   <td style="text-align:left;"> $SPY SPY 2022-02-09 Options Analysis Video: 
https://www.youtube.com/watch?v=CwfI0r6iUfE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:20 </td>
   <td style="text-align:left;"> latexf6960d74e09aaa8a1b3cbdce35316122FB
$EXPE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:08 </td>
   <td style="text-align:left;"> $SPY Futes dripping.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:03 </td>
   <td style="text-align:left;"> $SPY idiots don’t really understand what priced in means. Do they? 
fed is increasing rates by at least 25 bp and printer is stopping. This MEANS we are heading to sub 430 and then further  below as interest rates increase. There’s no IF but rather WHEN.  
But you  keep on drinking the kool-aid    . we all live and learn. One day you will too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:32:01 </td>
   <td style="text-align:left;"> $SPY $QQQ If YoY CPI is less anything less than 8% I&amp;#39;ll move to burkina faso - SCREEN SHOT THIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:56 </td>
   <td style="text-align:left;"> $SPY every single time CPI comes out they say it&amp;#39;s peaking, only the next number is bigger than the last. So you honestly believe what the f they are telling you? You are being lied to. Transitory. I mean peaking...right. Right. 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:49 </td>
   <td style="text-align:left;"> $SPY the thing about “priced in” vs “not priced in” is that it doesn’t matter because there are so many trend following algos in the market to create momentum in whatever direction. In that way, the market is dumber than it has ever been imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:44 </td>
   <td style="text-align:left;"> $SPY die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:32 </td>
   <td style="text-align:left;"> $SPY Bulls just got caught in one of the biggest bull traps in SPY history literally ONE DAY before CPI readout.  You can&amp;#39;t make this up folks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:30 </td>
   <td style="text-align:left;"> $SPY 

Pajama Bois painting an interesting tape. Looks like a mirror. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:23 </td>
   <td style="text-align:left;"> $SPY rugpull tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:31:14 </td>
   <td style="text-align:left;"> $SPY vix going crazy and futures going to the grave damn🥴🥴🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:30:50 </td>
   <td style="text-align:left;"> $SPY 4 days pumping. Tomorrow dumping $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:30:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Calm and composed 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:30:08 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m thinking the CPI numbers is going to whack the market. Think we could touch 4520. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:59 </td>
   <td style="text-align:left;"> $SPY Inflation is theft and the Feds inflation is not an accident. It’s intentional.

https://youtube.com/shorts/efMnR3ETWhw?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:50 </td>
   <td style="text-align:left;"> $SPY let’s not kid ourselves tomorrow could be fugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:42 </td>
   <td style="text-align:left;"> $SPY even if I hit u once u part of my collection </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:37 </td>
   <td style="text-align:left;"> $SPY just buy calls. Set your limit buys for 30% down from current prices. And ride it into Nvidia earnings lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:24 </td>
   <td style="text-align:left;"> $SPY lol if cpi data is bad but not horrible we will pump lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:14 </td>
   <td style="text-align:left;"> $SPY the collapse tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:29:02 </td>
   <td style="text-align:left;"> $SPY lots of bears tonight i feeling like a lone bull 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:52 </td>
   <td style="text-align:left;"> $SPY bears fantasize about this moment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:50 </td>
   <td style="text-align:left;"> $SPY major green tommorow again. Soon aths. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:41 </td>
   <td style="text-align:left;"> $SPY Some Bears saying a Bad Cpi is not priced in… HAHAHA that’s the dumbest thing i’ve heard on here all day… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:36 </td>
   <td style="text-align:left;"> $SPY tomorrow should be quite volatile but regardless just buy and hold its the way to invest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:34 </td>
   <td style="text-align:left;"> $SPY Holding $MU calls AH’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:25 </td>
   <td style="text-align:left;"> $SPY tomorrow deep red to green close $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:21 </td>
   <td style="text-align:left;"> $SPY …when do they rekease the fuckery index number? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:16 </td>
   <td style="text-align:left;"> $SPY 

Think CPI may beat when it reports tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X Olympic Snowboard Halfpipe is more entertaining than the shot put.  
 
I expect CPI at 7.3-7.4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:28:04 </td>
   <td style="text-align:left;"> Slight dips $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:59 </td>
   <td style="text-align:left;"> $SPY: Mentioned yesterday to watch for the range breakout. Nice bullish close above the 50 ema. All eyes on CPI data tomo. If we get a bullish reaction, look for a push to 460 and 462 next. If we get a bearish reaction, look for 456, and 452 levels to act as support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:56 </td>
   <td style="text-align:left;"> $SPY look at the graph of CPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:51 </td>
   <td style="text-align:left;"> $SPY as long as CPI is higher than YOY GDP growth then SPY should hit $500 due to supply and demand as well as the elasticity of stock prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:49 </td>
   <td style="text-align:left;"> $SPY inflation is good for the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:46 </td>
   <td style="text-align:left;"> $SPY so if everyone thinks it goes down tomorrow because of CPI, what is the likelihood that will happen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:45 </td>
   <td style="text-align:left;"> $SPY tank it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:36 </td>
   <td style="text-align:left;"> $SPY moo the biggest bear and still can’t even get the drops right @blancobull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:20 </td>
   <td style="text-align:left;"> $SPY bears tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:18 </td>
   <td style="text-align:left;"> $SPY I keep a daily trading journal and I also write down all my trading strategies and daily plans on the kids menu at Dennys in crayon every morning before the open
Market will rip higher tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:17 </td>
   <td style="text-align:left;"> $SPY if you are up 0% this year, you are 10% ahead of most </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:27:01 </td>
   <td style="text-align:left;"> $SPY higher and higher 🐻🐻🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:49 </td>
   <td style="text-align:left;"> $SPY bookies should open up lines for CPI numbers at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:27 </td>
   <td style="text-align:left;"> $SPY tomorrow to moon n back to earth 🌏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:27 </td>
   <td style="text-align:left;"> $SPY CPI will be 7.1% instead of the expected  7.2% and the  market will  go green claiming it’s “priced in.” 
 
yeah 7.1 is still higher than December‘s 6.9% and it means we are in trouble. But don’t you dare question the Market. even 7.2 is priced in.  😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:23 </td>
   <td style="text-align:left;"> $SPY they’re gonna go after Howard stern 😂 https://youtu.be/Pvof41JEWR8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:20 </td>
   <td style="text-align:left;"> $SPY closer and closer 🤫🤫🐻🐻🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:17 </td>
   <td style="text-align:left;"> $SPY CPI will come in at 12% and we will shoot to $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:05 </td>
   <td style="text-align:left;"> $SPY have a feeling bears are gonna get crushed tomorrow. It’s just easy 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:26:03 </td>
   <td style="text-align:left;"> MARKET UPDATE 

$SPY S&amp;amp;P 500

Watch before tomorrow!

Detail: CPI Inflation Report 

https://youtu.be/EIwNPCo-wsA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:25:58 </td>
   <td style="text-align:left;"> $SPY who here is eligible to get a new crack pipe for free </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:25:45 </td>
   <td style="text-align:left;"> $SPY $470 by friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:25:40 </td>
   <td style="text-align:left;"> $SPY NQ probably bottomed at 15000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:25:20 </td>
   <td style="text-align:left;"> $SPY targeting sub 450 before report drops
By open could be nasty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:25:19 </td>
   <td style="text-align:left;"> $UBER $DIS $SPY who really thinks we have a good chance of rallying of CPI data tomorrow? I wanna be bullish but deep down I just know no good data is coming… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:25:12 </td>
   <td style="text-align:left;"> $SPY Just saw Janet Yellen going for a walk through my neighborhood n snapped a picture, first time I’ve seen a celebrity in real life 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:50 </td>
   <td style="text-align:left;"> $SPY no one cares about the CPI report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:44 </td>
   <td style="text-align:left;"> $UVXY $SPY $AAPL $AMZN - Metals are down, futures are flat.. Fed says a 50 basis point hike isn’t needed... I think we have plenty of info on tomorrow’s report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:41 </td>
   <td style="text-align:left;"> $SPY 

Whats this $CPI ? Is it part of the SP500 index? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:38 </td>
   <td style="text-align:left;"> $SPY futures don&amp;#39;t matter tonight. 8:30 CPI numbers will dictate the direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:28 </td>
   <td style="text-align:left;"> $SPY tonight instead of hanging on ST until midnight I’m going to drink with my wife’s bf instead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:13 </td>
   <td style="text-align:left;"> $SPY looks like a flat open tomorrow, maybe a slight gap up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:24:11 </td>
   <td style="text-align:left;"> $SPY eerie… Fed officials now talking about active sales of mortgage backed securities during their QT
**Recap: Higher mortgage rates , Negative real wage growth , Fed hinting to MBS sales.  Not looking good for real estate short-term - which by the way accounts for &amp;gt;50% of global wealth. 
 https://www.tradingview.com/chart/IYR/gmrQsk1H-IYR-Housing-Market-Imminent-Death-Cross-A-Black-Swan-Event/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:23:26 </td>
   <td style="text-align:left;"> $SPY fwiw $NKLA and $PTON finished green today 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:23:25 </td>
   <td style="text-align:left;"> $SPY WH stayed inflation will be bad tomorrow. What are we saying 7.5%? 8%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:23:22 </td>
   <td style="text-align:left;"> $SPY futes limpin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:23:17 </td>
   <td style="text-align:left;"> $SPY pontius pilate didn’t condemn Jesus he left it up to the crowd to save face. 
Jerome is the same , man straight up said data  for fed decisions. If the numbers are within 7% I’ll be the first one to turn bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:23:13 </td>
   <td style="text-align:left;"> $SPY until 70% of retail quits being bears it’s gonna keep pumping lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:23:08 </td>
   <td style="text-align:left;"> $SPY if tom lee said jump off a bridge bulls would do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:59 </td>
   <td style="text-align:left;"> $SPY might bet 10% CPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:56 </td>
   <td style="text-align:left;"> $SPY if future is green as it is red now, bulls will be telling everyone future ripping ! But cuz it red, future don’t matter - bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:54 </td>
   <td style="text-align:left;"> $SPY  Seriously you guys should read this !!! NFts childish art , social change, and your tattoos and gender politics. will not save the country...  You all need to get your asses back to work and work hard so you sweat.
https://www.newscientist.com/article/mg25333720-500-how-the-world-really-works-review-the-tech-that-underpins-society/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:53 </td>
   <td style="text-align:left;"> $SPY today spy was green, after hours is red, tomorrow, vix will be green, and spy will be red -- going long on $UVXY until... end of march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:36 </td>
   <td style="text-align:left;"> $SPY not going to lie being all liquid is booooorrringg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:35 </td>
   <td style="text-align:left;"> $SPY bulls waiting at premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:35 </td>
   <td style="text-align:left;"> $SPY Raised my rents this year double inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:31 </td>
   <td style="text-align:left;"> $SPY Damn what am i doing with my life... really makes you wonder.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:19 </td>
   <td style="text-align:left;"> $SPY 

Don&amp;#39;t go chasin&amp;#39; waterfalls
Please stick to the rivers and the lakes that you&amp;#39;re used to
I know that you&amp;#39;re gonna have it your way or nothing at all
But I think you&amp;#39;re moving too fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:17 </td>
   <td style="text-align:left;"> $SPY HI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:16 </td>
   <td style="text-align:left;"> $SPY I’m buying about 8k of calls regardless tomorrow market wants to go up until March so I’m gonna ride the wave to 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:14 </td>
   <td style="text-align:left;"> $SPY trust the “Tools” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:22:05 </td>
   <td style="text-align:left;"> $SPY red futures means green open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:45 </td>
   <td style="text-align:left;"> $SPY too many bears means bulls win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:33 </td>
   <td style="text-align:left;"> $SPY futures looking like a weak rug pull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:19 </td>
   <td style="text-align:left;"> $SPY futures looking like ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:13 </td>
   <td style="text-align:left;"> $SPY some bulls here probably questioning their existence right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:13 </td>
   <td style="text-align:left;"> $SPY god the new update sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:06 </td>
   <td style="text-align:left;"> $SPY so y’all just buy call or puts at the EOD and hope for the best 🤔🤔🤔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:03 </td>
   <td style="text-align:left;"> $SPY lower high relative to last week where it hit 448. I think tomorrow it goes down unless CPI is significantly below what&amp;#39;s expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:21:01 </td>
   <td style="text-align:left;"> $SPY Getting pumped up for an expected 7.2% Jesus. Remember when yellen was saying it would be 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:20:09 </td>
   <td style="text-align:left;"> $NKLA 

The Trevor Milton sequel will be coming out soon. $SPY 

https://youtu.be/eBA2TZHNh9g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:20:02 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:57 </td>
   <td style="text-align:left;"> $SPY 2% drop tomorrow minimum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:36 </td>
   <td style="text-align:left;"> $SPY CPI report for US what Time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:25 </td>
   <td style="text-align:left;"> $SPY This is the biggest Pimp Daddy of all the Sucka Bait Rallies I have ever seen. 
When you get up tomorrow will you be a sheep… or will you be man? 
Prices didn’t go up at your store? At your restaurant? At your gas station? Has the cost of a home started dropping? Have you purchased lumber? Does your city actually have paint? Seriously. Can you purchase paint? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:22 </td>
   <td style="text-align:left;"> $SPY $DJIA  there is no way pajama bulls don’t sell this RIP today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:19 </td>
   <td style="text-align:left;"> $SPY can already see the dip buying algos starting to step in with increasing pressure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:06 </td>
   <td style="text-align:left;"> $SPY when I die smoke 2 for me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:19:05 </td>
   <td style="text-align:left;"> $SPY confirmed sighting of ofg on investing.com futures app dunking on small money world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:18:59 </td>
   <td style="text-align:left;"> $SPY What if we get inflation above 8%, that would shock the markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:18:30 </td>
   <td style="text-align:left;"> $SPY dear inflation please be ripping tomorrow 😳 I bought lots of QQQ and SPY puts near the bell today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:18:27 </td>
   <td style="text-align:left;"> $SPY This bull tried to hold it overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:18:06 </td>
   <td style="text-align:left;"> $SPY CPI is going to come in hot as hell.  I own a manufacturing company and nothing has gotten cheaper in the last month... The only thing I keep hearing from suppliers is &amp;quot;expect more price increases moving forward&amp;quot;..  That means we will see a $459 algo pump in the morning to get more bulls trapped, and then an afternoon dump down to below $450 to fill the gap.  Then panic selling on Friday down to $439..  That will start Wave C of Wave 4.  Bottom should be around $400 on March 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:55 </td>
   <td style="text-align:left;"> $SPY wear it proudly bulls
You bought a Fugazi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:37 </td>
   <td style="text-align:left;"> $SPY everybody knows that inflation will be worse then what they admit tomorrow ( double )  and , the market will keep pumping tmw and, dump Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:36 </td>
   <td style="text-align:left;"> $SPY 7.1, 7.5, 0.75.....ask any single parent who pays rent, buys food and gas for his/her car, etc... if they give two shits. Inflation is so bad that they have to fabricate a number that in no way represents real inflation. Skyrocketing oil, imminent European energy crisis and off the fucking charts inflation are the perfect recipe for the inevitable recession that&amp;#39;s coming. Y&amp;#39;all keep buying calls- 🤣🤣🤣.  Joke will be on you only doubt there will be much laughing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:33 </td>
   <td style="text-align:left;"> $SPY bulls buying calls last minute about to get.them cheeks clapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:31 </td>
   <td style="text-align:left;"> $spy Covered a nkd at 27650. Like picking up pennies from in front of the steamroller that blasted my shorts this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:30 </td>
   <td style="text-align:left;"> $SPY feeling bullish for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:13 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Thinking about starting a “climate hedonists” movement. Essentially people who would rather open a bottle of champagne and enjoy the decline and have some fun as opposed to fighting the inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:08 </td>
   <td style="text-align:left;"> $SPY $QQQ   https://youtu.be/6CEegZU5Bsc big day  today let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:17:06 </td>
   <td style="text-align:left;"> $SPY one of our options expert. made a call yesterday for 454 calls. before close and that call just ran for over 1000 today%. entry price was .33 when he called and it ran over 3.30 today. we call bangers like this all the time. free community. link in bio. $SOPA $SNDL $DCFC $KAVL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:58 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
market is unstoppable and will run and run and run until it hits an actual stop event and will die in a glorious fireball but that’s minimum 3 years away if not up to 7  
 
bears are early lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:57 </td>
   <td style="text-align:left;"> $SPY slip sliding away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:55 </td>
   <td style="text-align:left;"> $SPY I mean how can inflation only be 8% year-year when monthly has been 6.8%? Asking for a bull friend... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:53 </td>
   <td style="text-align:left;"> $SPY think this opens flat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWN $UVXY $AAPL  
 
I need one of you quants to run the CPI numbers tomorrow but with the math they used back in 1978. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:31 </td>
   <td style="text-align:left;"> $SPY finally Nikkei shows the first sign of fatigue, watching this shet moving into negative territory tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:29 </td>
   <td style="text-align:left;"> $SPY $500 before $450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:20 </td>
   <td style="text-align:left;"> $SPY limit down would save bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:15 </td>
   <td style="text-align:left;"> $spy why aren’t the psychotic right wing cultists with guns going after these smug idiots? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:16:04 </td>
   <td style="text-align:left;"> $SPY Bulls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:59 </td>
   <td style="text-align:left;"> $SPY  
I blame the algos tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:53 </td>
   <td style="text-align:left;"> $SPY dumped all my spy shares on you face at close. Big dump on inflation report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:53 </td>
   <td style="text-align:left;"> $SPY Dont say I didnt warn ya bulls... get your Biden approved crack pipes soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:50 </td>
   <td style="text-align:left;"> $SPY  futures sell off 10 points and the gay bears come out of the woodwork. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:32 </td>
   <td style="text-align:left;"> $SPY stop blaming algos for your poor choice in contracts that lost you money 
all algos did is provide liquidity 
and MMs delta neutral 
there was no manipulation 
you just suck at trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:01 </td>
   <td style="text-align:left;"> $SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:15:01 </td>
   <td style="text-align:left;"> $spy $uvxy $qqq $dia $sqqq
why cpi data will be “key” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:51 </td>
   <td style="text-align:left;"> $SPY Timbaaaaaaaaaaaa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:50 </td>
   <td style="text-align:left;"> $SPY with the Fed’s balance sheet expanding every day and rates at zero we are effectively at negative rates with inflation raging out of control for almost 12 months.  This is a tragicomedy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:47 </td>
   <td style="text-align:left;"> $SPY next 15 pts budda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:42 </td>
   <td style="text-align:left;"> $SPY tomorrow&amp;#39;s price range low 455.81 and high 460.80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:35 </td>
   <td style="text-align:left;"> $SPY 7.7% , real inflation, 11.7% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:27 </td>
   <td style="text-align:left;"> $SPY Futes brickin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:23 </td>
   <td style="text-align:left;"> $SPY You fck other bears when you cover.  
 
Never cover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:23 </td>
   <td style="text-align:left;"> $SPY JUST GETTING STARTED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:22 </td>
   <td style="text-align:left;"> $SPY $AMZN $TWLO $PTON $DIS Deep fucking bloody red 🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:14:02 </td>
   <td style="text-align:left;"> $SPY bulls think Trump is still president and won the election and this will run tomorrow lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:13:22 </td>
   <td style="text-align:left;"> $SPY moves without volume are suspect. “Everything rally”, rallied on little volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:13:17 </td>
   <td style="text-align:left;"> $SPY 5 weeks until the first rate cut. Not that much actually, but enough for mms to cuck retails a few times. Today the 5 point hike looks unreal, but inflation is not going away any time soon so in a month it&amp;#39;ll be just the right thing for the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:13:17 </td>
   <td style="text-align:left;"> $SPY rofl people used to mail lumber to the Fed chairman in the 70s.  Now they … idk rant on Facebook about vaccines?  We’re doomed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:13:08 </td>
   <td style="text-align:left;"> $SPY $470 tomorrow. Why?  B/c I bought puts, that’s why. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:13:07 </td>
   <td style="text-align:left;"> $SPY 
Okay so tonight ima little bearish only cause of CPI, this is going to fall unfortunately. This bear feeling that I have got me feeling kinda gay, I dont like being bearish😒 is this what yall feel all the time?!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:30 </td>
   <td style="text-align:left;"> $SPY bears got annihilated again, feels great. Don&amp;#39;t feel bad for them. Watch the shit CPI numbers pump us up again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:27 </td>
   <td style="text-align:left;"> $SPY todays gain will be gone by midnight @ this rate.. to whoever loaded puts before close, this is for you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:23 </td>
   <td style="text-align:left;"> $SPY the moo knows 

That&amp;#39;s the tweet 

#DoubleDigitCPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWN $DJIA $UVXY  
 
Truth is at this point 20 rate hikes can&amp;#39;t un do the damage done by unchecked spending to fund social programs over the last few years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:19 </td>
   <td style="text-align:left;"> $SPY 

Multiple quarters greater than 5% inflation 
Is warning sign

The market always makes the most obvious play in the most unusual way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:07 </td>
   <td style="text-align:left;"> $SPY only way puts are getting saved is a limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:12:00 </td>
   <td style="text-align:left;"> $AMC $SPY     Real price come out soon. Hit the target price.... 
Join now: livetradingchat.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:11:59 </td>
   <td style="text-align:left;"> $SPY How can I profit from this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:11:27 </td>
   <td style="text-align:left;"> Hell of a week trading algos between agro price pivots. 
SPY is going to remain bullish heavily above the closing week pivot 446.07 as alerted, 
virtually leaving puts worthless feeding them small dips to maintain liquidity.  
After 150 matching ticks within DASH I took notice that SPY price pull was determining  the  
frequency of buy interest within DASH that&amp;#39;s why DASH had delayed pumps, so swinging along SPY calls 
was a no brainer.  
 
Earlier today (11:12AM) just after taking heavy profits off SPY swing I dipped in for the reset fade which  
I identified was forming a bear trap for greedy short remembering 446.07 is the ultimate bearish 
pivot 
 
I scaled GOOGL patiently after ER as its forming the same agro flow pattern as TSLA did into the 
new year and opened New years day for 1200 pump. GOOGL showed no aggressive downside interest alongside 
NASADAQ which is also chasing its 10 &amp;amp; 20 day high 15,260. GOOGL has not yet set its cash session highs. 
 
$SPY $GOOGL $DASH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:11:23 </td>
   <td style="text-align:left;"> who is down for a trade ideas love stream?  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:11:06 </td>
   <td style="text-align:left;"> $SPY Why couldnt it break past 557? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:10:54 </td>
   <td style="text-align:left;"> Get it $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:10:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT If CPI shows more than 7% inflation, will market gets knee jerk reaction? Let’s volatility print both calls and puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:09:59 </td>
   <td style="text-align:left;"> $SPY what if JPM leaked that shit to fool everyone and pumped up the price so they can sell? Bull trap at its finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:09:54 </td>
   <td style="text-align:left;"> $SPY zzzz you shorts are overcrowded now. GS Prime book shows short selling at 9 year highs despite market rallying! Short selling is now higher than what we saw in January 2021. The squeeze will come first, and then we&amp;#39;ll see what happens to the market after. Just gotta take out people who bought too many puts and short sellers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:09:46 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:09:43 </td>
   <td style="text-align:left;"> $SPY this is comical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:09:09 </td>
   <td style="text-align:left;"> $SPY $PFE 
keep believing democrats! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:50 </td>
   <td style="text-align:left;"> $SPY if futures were this green we hear futures ripping. Now they say futures don’t matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:43 </td>
   <td style="text-align:left;"> $SPY hope everyone got their tickets , win  or bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:42 </td>
   <td style="text-align:left;"> $SPY I mean it didn’t take much for the Fed to start cutting interest rates rapidly.  Covid hit and they immediately cut them to zero and started infinite QE.  But 7+% inflation wrecking the lower and middle classes?  Oh no we can’t be too hasty. 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:39 </td>
   <td style="text-align:left;"> $SPY futes are tripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:36 </td>
   <td style="text-align:left;"> $SPY if this is a bounce, it won’t last long.  trust the fundamentals. Fundamentals are based on facts. . And facts don’t lie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:34 </td>
   <td style="text-align:left;"> $AAPL $PTON $AAL $TSLA $SPY  
 
They pumped it up right before CPI. Awesome!... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:33 </td>
   <td style="text-align:left;"> $SPY JPM says BTMFD! 
They have a wonderful track record of not giving you bad advice to save a company(one that they own) from going south. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:29 </td>
   <td style="text-align:left;"> $SPY ALL NIGHT BABY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:26 </td>
   <td style="text-align:left;"> $SPY i know a guy that works at burger king that knows a guy that told him to tell me to tell you we&amp;#39;re gonna crash.. Book it dan o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:08:04 </td>
   <td style="text-align:left;"> $SPY We are now in the window where the market pretends to care about the CPI print.  It doesn&amp;#39;t. 
 
We are going up.  Only up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:07:26 </td>
   <td style="text-align:left;"> $SPY 1dte calls tomorrow after the mini dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:07:25 </td>
   <td style="text-align:left;"> $SPY the futes. They ain’t rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:58 </td>
   <td style="text-align:left;"> $SPY Meanwhile, Biden releases Rapists and murderers while opening up jails for single moms that had to do this because they closed down daycare centers during the Pandemic. #LETSGOBRANDON! https://www.msn.com/en-us/news/crime/single-mother-faces-prison-for-letting-her-14-year-old-babysit/ar-AATD5sN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:53 </td>
   <td style="text-align:left;"> $SPY what we thinking for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:39 </td>
   <td style="text-align:left;"> $SPY The truth is that today algos were shamelessly pumping the price despite lots of selling volume. The question is if it is the beginning of a big bounce or just a trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:36 </td>
   <td style="text-align:left;"> $SPY wow bulls. Just like that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:36 </td>
   <td style="text-align:left;"> $SPY The long-awaited meltdown will soon be unleashed.

Oh boy, will many people learn it the rough way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:11 </td>
   <td style="text-align:left;"> $spy seriously the Fed and the ECB have been completely wrong about inflation for 12 months straight.  Has anyone asked to see their models or specifically how they’ve adjusted them?  Is there any actual scientific evidence that forms the basis of their modeling? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:06:02 </td>
   <td style="text-align:left;"> $SPY you guys know we’re selling RIPs not DIPs right ? Just checking in 🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:05:49 </td>
   <td style="text-align:left;"> $SPY There is also the possibility that the market likes the cpi reading and we impulsively rip past the 61.8 fib </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:05:48 </td>
   <td style="text-align:left;"> $SPY this  is why cooked CPI doesn’t matter. interest rate hike is  coming. 25bp and no printer is enough to ”correct”  the market.   
 
4:40p ET 2/9/2022 - MarketWatch 
High inflation has jacked up the cost of food, gas, cars and rent -- and there&amp;#39;s little relief in sight 
By Jeffry Bartash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:05:31 </td>
   <td style="text-align:left;"> $SPY up 1.46% today, if futures go that low start celebrating bears, mean while just chill, nothing to see here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:05:17 </td>
   <td style="text-align:left;"> $QQQ $SPY most of the rich guys like meet Kevin and many more are in all cash, wonder why? Buying overpriced puts is not the way. Wondering some cheering market is bullish, some saying bearish. I think it is best to trade with small amounts and keep a large chunk as cash. About to do the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:04:12 </td>
   <td style="text-align:left;"> $SPY Brazil could be the first place that starts a revolution of surging inflation, this year.  
 
https://www.batimes.com.ar/news/economy/brazil-posts-highest-january-inflation-rate-since-2016.phtml </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:03:53 </td>
   <td style="text-align:left;"> $TLT 10Y yield pausing at its November 2019 highs.  Short/intermediate term pullback in 10Y yield to the 9 weekly moving average would not be the most surprising thing honestly.   
 
I still would not touch treasuries but such a move would be a tailwind for $QQQ which feels like it wants to launch much higher. 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:03:47 </td>
   <td style="text-align:left;"> $SPY dip to 454 then we continue higher. Algos don’t lie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:03:44 </td>
   <td style="text-align:left;"> $SPY Bostic pumped the market today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:03:32 </td>
   <td style="text-align:left;"> $SPY today was a pump ! How they propped it all day was just like in your face come and get it - and you will 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:03:26 </td>
   <td style="text-align:left;"> $SPY is this Bidens answer to stimulate the Economy after he crashes the market tomorrow? https://www.msn.com/en-us/health/medical/why-the-biden-admin-is-handing-out-free-crack-pipes/ar-AATE0r8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:03:11 </td>
   <td style="text-align:left;"> $PLTR $SPY All that you need to know... Shorts haven&amp;#39;t covered a single share:-- Check it out below 👇 
 
~~~~~~~~~~~~~~~~~ 🚀 discord.io/W5xTvWebnw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:02:58 </td>
   <td style="text-align:left;"> JPM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:02:35 </td>
   <td style="text-align:left;"> $SPY down AH! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:02:13 </td>
   <td style="text-align:left;"> $SPY rofl.

Maybe because your leaders are scam artist grifters who lie and are so narcissistic they can’t handle any criticism, so they isolate themselves in a bubble of self-congratulatory delusion.  Ya know, the boomer way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:33 </td>
   <td style="text-align:left;"> $SPY   
Essaye and Invesco&amp;#39;s Hooper agree that investors won&amp;#39;t only be parsing Thursday&amp;#39;s CPI data for clues. Inflation expectations are also crucial, ensuring that investors will pay close heed to the University of Michigan&amp;#39;s preliminary February read onthe subject Friday morning.  
 
That data could, in fact, prove more important, Hooper said, after the New York Fed&amp;#39;s inflation-expectations for the next one and three years remained elevated in December, but appeared to peak. The data showed median expectations one-year expectations unchanged at 6% and three-year expectations steady at 4%.  
 
&amp;quot;We would want to see the same from the Michigan data,&amp;quot; she said, noting that January data from the New York Fed won&amp;#39;t be seen until Monday.  
 
Essaye is less sanguine about the outlook, noting that all the measures of inflation expectations monitored by his firm are in areas that indicate the Fed needs to be hawkish, even with five-year inflation breakevens pulling back from recent highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:28 </td>
   <td style="text-align:left;"> $SPY Gravity bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:07 </td>
   <td style="text-align:left;"> $SPY double down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:03 </td>
   <td style="text-align:left;"> $SPY High probability spy fades to retest 450 and the might use the cpi reading to do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:02 </td>
   <td style="text-align:left;"> $SPY 12 hours and 30 minutes until the cooked CPI numbers arrive! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:01:02 </td>
   <td style="text-align:left;"> $SPY every index gapping down 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:00:41 </td>
   <td style="text-align:left;"> $SPY $AMC $DIS Was Bob Saget MURDERED? 😳😱 Respond below 👇 https://www.hollywoodreporter.com/news/general-news/bob-saget-cause-death-head-trauma-1235090316/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:00:41 </td>
   <td style="text-align:left;"> $SPY 🔥🔥👌😎 accurate analysis! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 09:00:07 </td>
   <td style="text-align:left;"> $SPY mark my post. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:59:43 </td>
   <td style="text-align:left;"> $SPY the best move is not participating lol. 50% up or down. Not a good risk and reward situation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:59:33 </td>
   <td style="text-align:left;"> $SPY RSI was 85 at open now 47 on the daily on weekly shows room to 469. 🐻 Logic right now after a 1.43% day &amp;quot;We won! Futures are down .17 take that 🐂&amp;quot; dumbasses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:59:28 </td>
   <td style="text-align:left;"> $SPY its all priced in they say but why then is it every single fed meeting the market tanks 2%. It’s because the fed is still undecided and shaky . Market priced in about 5 rate hikes at 25 pts with cpi around 7%. You get above that market is going to price in a knife. Spy back to $400 is evitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:59:03 </td>
   <td style="text-align:left;"> $SPY Can someone explain to me why we can’t already figure out CPI by calculating it?  Is it not fairly simple? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:58:59 </td>
   <td style="text-align:left;"> $SPY all indications that they’llpump this shit till Monday. They don’t want premiums to be collected this week.  
 
“We would want to see the same from the Michigan data,&amp;quot; she said, noting that January data from the New York Fed won&amp;#39;t be seen until Monday.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:58:15 </td>
   <td style="text-align:left;"> Be careful who you let in your life $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:58:13 </td>
   <td style="text-align:left;"> $SPY so was the revised CPI weighing taken into account when forecasting what it would be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:58:12 </td>
   <td style="text-align:left;"> $SPY CPI 

FINAL DECISION FOR IF THE BULL RUN CONTINUES OR NOT

🙂🙂🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:58:11 </td>
   <td style="text-align:left;"> $SPY Yoyo. Cpi is 8am correct????? Thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:58:03 </td>
   <td style="text-align:left;"> $SPY Well if the market crashes again.. at least Biden is using our Tax dollars wisely and giving away Free Biden/Harris Crack pipes for everyone. Im sure everyone will need it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:57:58 </td>
   <td style="text-align:left;"> $SPY This was overbought today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:57:48 </td>
   <td style="text-align:left;"> $SPY What is more fake ? Biden presidency or bulls thinking cpi is priced in already? 🤣 $DWAC $SPOT $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:57:47 </td>
   <td style="text-align:left;"> $SPY I’m hearing 32% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:57:37 </td>
   <td style="text-align:left;"> $SPY keeping plenty of dry powder I think we retest before going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:57:33 </td>
   <td style="text-align:left;"> $SPY $NDAQ $DJIA enough of this rally now let’s go back to 4300 range and time to buy again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:57:09 </td>
   <td style="text-align:left;"> $SPY futures probably just bottomed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:45 </td>
   <td style="text-align:left;"> $SPY if I blow my account imma get one of them free Biden pipes and just smoke rocks outside of 7/11 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:28 </td>
   <td style="text-align:left;"> $SPY it’s at the 61.8% fib….it’s a double top…rug pool…back to $430’s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:21 </td>
   <td style="text-align:left;"> $SPY 🤦🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:17 </td>
   <td style="text-align:left;"> $SPY WH wouldn&amp;#39;t warn in advance about YoY inflation number if reading wasn&amp;#39;t horrific. Market priced in 7% or less on two day FED pump rally. Anything above 8% will auto signal 50 BP rate hike in March. You&amp;#39;ll see 👇 by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:14 </td>
   <td style="text-align:left;"> $SPY &amp;quot;priced in&amp;quot; I love it 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:12 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t sleep on Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:56:00 </td>
   <td style="text-align:left;"> $SPY Money needs to work for you, best way right now is Equites … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:57 </td>
   <td style="text-align:left;"> $SPY gonna bleed all night to around -.5% imo and then CPI will rail this down another % or 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:56 </td>
   <td style="text-align:left;"> $SPY you still have time to sell to avoid one of the worst market days in history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:54 </td>
   <td style="text-align:left;"> $SPY not sure what’s going to happen tomorrow.
Alot of options players were slaughtered today on puts for sure.
Not to sure Bidens free crack pipes and money printing wasn’t cooked into the CPI #’s for tomorrow to keep us bullish, but reality says we will not be able to afford much very soon with the rate things are rising in cost. Fuel and everyday food necessities are going to be outrageous.
I’m praying for both sides tonight, I have no position either way until after the forum ends.
God speed! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:54 </td>
   <td style="text-align:left;"> $SPY one of my best friends who has owned a mortgage company for over 20 years has been warning me of a crash. I’m not sure about a crash but I see this dropping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:48 </td>
   <td style="text-align:left;"> $SPY cpi 6% tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:29 </td>
   <td style="text-align:left;"> $SPY Why would there be a warning if CPI was good??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:25 </td>
   <td style="text-align:left;"> $SPY The Russians are crazy giving 15 year olds performance enhancing drugs 💀💀🤣 https://www.espn.com/olympics/story/_/id/33254263/russian-figure-skater-kamila-valieva-tested-positive-banned-drug-according-reports </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:22 </td>
   <td style="text-align:left;"> $SPY #TeamGravity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:19 </td>
   <td style="text-align:left;"> $SPY CPI 20%
That’s the shock they release tomorrow with hopes to walk back from there but it’s worse and can’t kick can much longer than a couple months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:16 </td>
   <td style="text-align:left;"> $SPY https://www.investing.com/news/economy/hot-inflation-data-risk-pushing-fed-closer-to-a-supersized-hike-2760349.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:55:11 </td>
   <td style="text-align:left;"> $SPY Do you know what a sucker is? 
 
Google.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:54:58 </td>
   <td style="text-align:left;"> $SPY let gravity win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:54:38 </td>
   <td style="text-align:left;"> It’s better $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:54:29 </td>
   <td style="text-align:left;"> $SPY There goes the spy selloff. Dont say I didnt warn ya about this quick Bull Trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:54:13 </td>
   <td style="text-align:left;"> $SPY If we go up tomorrow, it will convince me that no one has any idea what is happening. 

I mean.. even if we go down… no one really knows… 

That hamster that turns the stock market wheel just does whatever he wants. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:54:09 </td>
   <td style="text-align:left;"> $SPY gonna have to to set the alarm alarm clock for Europes open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:54:06 </td>
   <td style="text-align:left;"> $SPY man so controlled, masterful, simply beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:53:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures slightly lower but it is all about the CPI tomorrow morning, if the CPI is soft then the market rallies hard for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:53:33 </td>
   <td style="text-align:left;"> $SPY under 4580…. AgAin 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:53:04 </td>
   <td style="text-align:left;"> $SPY we all know the drill.. cpi won’t be bad as expected and spy hits all time highs. Bears get the lube. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:52:46 </td>
   <td style="text-align:left;"> $SPY just got out of the kitchen we jpow bois we finished cooking the cpi number 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:52:37 </td>
   <td style="text-align:left;"> Morgan Stanley bullish overseas equities $SPY $FXI $KWEB $EEM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:52:27 </td>
   <td style="text-align:left;"> $SPY even without the data coming out the market is due for a pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:52:21 </td>
   <td style="text-align:left;"> $SPY $FB looks like it&amp;#39;s very hard to remove that F and N from FAANG. Some people are just having hard time to find good places where to put their billions of cash at work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:52:19 </td>
   <td style="text-align:left;"> $SPY You guys think 7.3%, 8%, even 6% for CPI?

48% take it or leave it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:52:00 </td>
   <td style="text-align:left;"> $SPY LOOKS THE WAY THE MARKETS ACTING  
TOMORROW  8.30 NUMBERS 
WILL DEFINITELY BE REVISED FOR THE BENEFITS OF THE BULLS  
YOU KNOW BEARS HAVE ABSOLUTELY NO CHANCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:58 </td>
   <td style="text-align:left;"> $SPY 2nd leg down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:56 </td>
   <td style="text-align:left;"> $SPY Cash is trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:43 </td>
   <td style="text-align:left;"> $SPY drip drip drip... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:41 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m just waiting on a sudden new fear headline to take over. Alien invasion or internet shutdown. Might be a few months buts it&amp;#39;s coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:40 </td>
   <td style="text-align:left;"> $SPY wonder how this would trade if just no one bought any options for a week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:40 </td>
   <td style="text-align:left;"> $SPY and what do the boomers do?  They deliberately sweep that near collapse under the table, allow the banks to consolidate even more power, and stick their head in the sands while criminals run the whole thing.  Jesus frack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:24 </td>
   <td style="text-align:left;"> $SPY …and good luck if you think cpi will save you
They already told you they gonna rape you ahead a time and you still bought it over 455 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:23 </td>
   <td style="text-align:left;"> $SPY I want to see 8.7% tomorrow. Anything lower is bullshit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:22 </td>
   <td style="text-align:left;"> $SPY 447 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-10 08:51:03 </td>
   <td style="text-align:left;"> $SPY convinced the bears haven&amp;#39;t been trading for more than a year. They wouldn&amp;#39;t have any money left otherwise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:34:50 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:34:46 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/6CEegZU5Bsc tomorrow is the make or break catalyst … lets go qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:34:31 </td>
   <td style="text-align:left;"> $QQQ so many bears with desperate hope and prayers 🤣🤣🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:33:22 </td>
   <td style="text-align:left;"> $SPY futures has to dump 1-2% tonight $QQQ interesting to watch tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:32:21 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-09 Options Analysis Video: 
https://www.youtube.com/watch?v=-O7egoSTmTQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:32:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures ripe.. like a juicy red tomato 🍅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:32:01 </td>
   <td style="text-align:left;"> $SPY $QQQ If YoY CPI is less anything less than 8% I&amp;#39;ll move to burkina faso - SCREEN SHOT THIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:31:08 </td>
   <td style="text-align:left;"> $qqq $vix $DJIA higher and higher inflation😱😱😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:30:50 </td>
   <td style="text-align:left;"> $SPY 4 days pumping. Tomorrow dumping $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:30:22 </td>
   <td style="text-align:left;"> $qqq $vix $DJIA higher and higher inflation 🤯🤫🤫🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:30:14 </td>
   <td style="text-align:left;"> $SPY $QQQ Calm and composed 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:29:05 </td>
   <td style="text-align:left;"> $qqq $vix $DJIA higher and higher inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:28:40 </td>
   <td style="text-align:left;"> $QQQ nice day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:28:25 </td>
   <td style="text-align:left;"> $SPY tomorrow deep red to green close $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:28:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X Olympic Snowboard Halfpipe is more entertaining than the shot put.  
 
I expect CPI at 7.3-7.4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:26:56 </td>
   <td style="text-align:left;"> $QQQ holy shit is it just gonna bleed down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:24:33 </td>
   <td style="text-align:left;"> $QQQ 370+ tomorrow after inflation comes in high again tomorrow AM lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:23:37 </td>
   <td style="text-align:left;"> $QQQ cpi data will only be used to time and size the dump. Dump is assured tomorrow or next week 

1) don’t be too large too late. 

2) btd will continue all the way to the bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:22:32 </td>
   <td style="text-align:left;"> $AFRM $EXPE $CLF $UA $QQQ  
 
https://www.financegreater.com/post/earnings-reports-this-week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:20:39 </td>
   <td style="text-align:left;"> $QQQ QQQs rallied with the similar momentum and volume as 1/11 and 1/12. Red 1/13. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:20:15 </td>
   <td style="text-align:left;"> $QQQ 10-yr is rising </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:20:08 </td>
   <td style="text-align:left;"> $QQQ allot of money on the sidelines waiting for that “big” drop that probably won’t happen tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:19:54 </td>
   <td style="text-align:left;"> $QQQ there is way more fear out there than is being recognized. All it takes is a spark. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:19:28 </td>
   <td style="text-align:left;"> $QQQ big caps did some selling AH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:17:13 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Thinking about starting a “climate hedonists” movement. Essentially people who would rather open a bottle of champagne and enjoy the decline and have some fun as opposed to fighting the inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:17:08 </td>
   <td style="text-align:left;"> $SPY $QQQ   https://youtu.be/6CEegZU5Bsc big day  today let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:16:58 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
market is unstoppable and will run and run and run until it hits an actual stop event and will die in a glorious fireball but that’s minimum 3 years away if not up to 7  
 
bears are early lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:16:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWN $UVXY $AAPL  
 
I need one of you quants to run the CPI numbers tomorrow but with the math they used back in 1978. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:15:22 </td>
   <td style="text-align:left;"> #QQQ $QQQ .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:15:01 </td>
   <td style="text-align:left;"> $spy $uvxy $qqq $dia $sqqq
why cpi data will be “key” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:13:33 </td>
   <td style="text-align:left;"> Impeccable DIS &amp;amp; UBER #Earnings Ahead Of The Jan CPI $DIS $QQQ $UBER https://talkmarkets.com/content/stocks--equities/impeccable-dis--uber-earnings-ahead-of-the-jan-cpi?post=344214 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:12:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWN $DJIA $UVXY  
 
Truth is at this point 20 rate hikes can&amp;#39;t un do the damage done by unchecked spending to fund social programs over the last few years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:11:40 </td>
   <td style="text-align:left;"> $QQQ Like this market&amp;#39;s acting lately, this -0.25% on ndq futures will be +1.5% by morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:11:32 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $NDX NASDAQ Composite Deep recession targets.  
 
https://www.tradingview.com/chart/IXIC/4fudfvnf-NASDAQ-Composite-recession-targets-IXIC-NDX/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:10:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT If CPI shows more than 7% inflation, will market gets knee jerk reaction? Let’s volatility print both calls and puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:07:25 </td>
   <td style="text-align:left;"> $QQQ yo....is that a death cross on the daily? or am I trippin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:05:17 </td>
   <td style="text-align:left;"> $QQQ $SPY most of the rich guys like meet Kevin and many more are in all cash, wonder why? Buying overpriced puts is not the way. Wondering some cheering market is bullish, some saying bearish. I think it is best to trade with small amounts and keep a large chunk as cash. About to do the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 09:03:53 </td>
   <td style="text-align:left;"> $TLT 10Y yield pausing at its November 2019 highs.  Short/intermediate term pullback in 10Y yield to the 9 weekly moving average would not be the most surprising thing honestly.   
 
I still would not touch treasuries but such a move would be a tailwind for $QQQ which feels like it wants to launch much higher. 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:58:00 </td>
   <td style="text-align:left;"> $QQQ has a bad technical rating, but it does show a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:56:58 </td>
   <td style="text-align:left;"> $qqq $iwm tomorrow might be a knee jerk reaction with CPI

Expect volatility. Bunch of thirsty traders out there! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:55:31 </td>
   <td style="text-align:left;"> $QQQ Why are the volatility index’s up AH. That’s unusual. Literally close to highs of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:53:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures slightly lower but it is all about the CPI tomorrow morning, if the CPI is soft then the market rallies hard for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:52:08 </td>
   <td style="text-align:left;"> $qqq If YO a wanna be 🧠 YO want this 🐑 tape to get fooked while da huckleberries return n ride in da coming months to da 🧠 stonks on da DLO.   Then da 🧠 can live at da ABNB Jon SNOW.  Gotta wUtch n ZI. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:50:20 </td>
   <td style="text-align:left;"> $QQQ Slow bleed off into the night…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:48:06 </td>
   <td style="text-align:left;"> $QQQ https://asia.nikkei.com/Business/Markets/Commodities/Global-commodity-prices-soar-50-fastest-pace-in-27-years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:47:55 </td>
   <td style="text-align:left;"> $QQQ MM/algos held her up neutral all day so tomorrow’s dip doesn’t bounce off the bottom too hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:47:38 </td>
   <td style="text-align:left;"> $spy $qqq $iwm you guys remember what happened after the last cpi report right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:46:34 </td>
   <td style="text-align:left;"> $QQQ https://www.detroitnews.com/story/business/2022/02/09/coffee-prices-soaring-with-supplies-tight/6722772001/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:45:56 </td>
   <td style="text-align:left;"> $QQQ 50d ma/100d MA crossover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:45:54 </td>
   <td style="text-align:left;"> $QQQ https://www.bloomberg.com/news/articles/2022-02-09/coffee-surges-to-10-year-high-with-supply-concerns-mounting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:45:42 </td>
   <td style="text-align:left;"> $QQQ $SPy what happened to all the bears talking about futes bleeding?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:45:29 </td>
   <td style="text-align:left;"> $SPY tomorrow morning drop is good for loading $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:44:09 </td>
   <td style="text-align:left;"> $QQQ $SPY likely flat until 8:30am EST and then… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:43:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Market after cpi data </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:43:20 </td>
   <td style="text-align:left;"> $QQQ so if it comes in at double digits I’m screwed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:42:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $iwm here’s the thing about you loser 🏳️‍🌈🧸s FYI people with jobs and actual wealth have more at stake than the loser bears who want to make 2k on some trash puts 😂😂

See it’s always funny how you can spot a broke ass bum, they’re usually a bear 🧸.

You don’t own a home or have a 401k that will bring you down more than your peanut puts? That says EVERYTHING 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:42:23 </td>
   <td style="text-align:left;"> $QQQ 8% cpi is priced in. Anything below we rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:41:55 </td>
   <td style="text-align:left;"> $QQQ $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:41:30 </td>
   <td style="text-align:left;"> $QQQ $MITQ All that you need to know... Shorts haven&amp;#39;t covered a single share:-&amp;gt;&amp;gt; Check it out below 👇 
 
~~~~~~~~~~~~~~ 🚀 discord.io/W5xTvWebnw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:38:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA what time does the CPI data get released ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:38:12 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.theguardian.com/politics/2022/jan/15/boris-johnson-now-less-popular-than-theresa-may-as-polls-show-tories-dire-predicament 
 
Looks like people in the UK are really unhappy with Boris Johnson. We should be thankful that we have a strong leader in the White House now instead of clowns like Boris Johnson and Donald Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:36:57 </td>
   <td style="text-align:left;"> Daily $QQQ stock analysis 

https://youtu.be/4bOM8H5HKMU

Here is $QQQ snapshot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:36:51 </td>
   <td style="text-align:left;"> $UVXY $SPY $VXX $QQQ $VIX 

Finom Group after hours 🍩🍩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:32:50 </td>
   <td style="text-align:left;"> $FB $NVDA $DKNG $QQQ hope you guys have been having a great trading week! Remember to follow me on TradeExchange if you can (link in bio) 🙏 

Have a good one :) and let’s keep going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:27:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 
CPI priced in? Or is it rice-a-roni? Tune in tomorrow and find out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:25:13 </td>
   <td style="text-align:left;"> $QQQ $SPY its the year 2037…the dollar has been abandoned. You goto McDonald’s to purchase the new brownie burger NFT with your CumRocket Token. Life is good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:22:27 </td>
   <td style="text-align:left;"> $SPY $QQQ buying commons for all my favorite momentum plays tonight. Tech is at a great level for share buyers looking for $NDX level to complement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:21:57 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/FEoYxG73stY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:19:44 </td>
   <td style="text-align:left;"> $QQQ I had to do it again and i’m not happy. 360p’s 2/18 for this week only and then back to bull. Forced to play both sides unfortunately now that it trades like a penny stock 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:19:25 </td>
   <td style="text-align:left;"> $QQQ If I recall as soon as he got re-nominated he turned hawkish on a dime, ain&amp;#39;t that ironic? -Powell knows they can&amp;#39;t printing any more $ if they want to solve this problem.. He just wanted to get back in office 1st before he told you the truth.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:17:15 </td>
   <td style="text-align:left;"> $QQQ  
the most important CPI number since Paul Volcker and the Qs send it 2% on a gap up after a 4 day trance! 
Is a hot number bullish now?!  
trading small and watching </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:15:33 </td>
   <td style="text-align:left;"> $SPY i see the gap down tomorrow $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:14:31 </td>
   <td style="text-align:left;"> $SPY $QQQ 

is trump still holding puts?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:12:26 </td>
   <td style="text-align:left;"> $SPY $XBI $QQQ 

This current group in charge generates more hot air than the world&amp;#39;s largest locomotive. 

I can&amp;#39;t wait to see what kind of lies they feed us tomorrow. Basically take whatever number they throw out there and double it. 🤥 

https://finance.yahoo.com/news/consumer-price-index-cpi-inflation-january-2022-210344769.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:06:57 </td>
   <td style="text-align:left;"> $QQQ you just had half a dozen tech companies do great earnings and gain 10% after hours. Index unmoved.

Not a good sign. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:06:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Actionable advice at SPY $432. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:04:58 </td>
   <td style="text-align:left;"> $QQQ Cocain is transitory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:04:44 </td>
   <td style="text-align:left;"> $FB $SPY $QQQ $DIS  
 
Congrats on the gains today guys, is anyone still holding? 
 
Follow for more ALERTS 👈🏻 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:02:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Lol dark pool printed almost a billion for Spy at $456 they know the markets will rally tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:02:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN AIRCRAFT CARRIER SOON 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 08:00:32 </td>
   <td style="text-align:left;"> $QQQ these people will post bearish sentiments NO MATTER WHAT  
 
It&amp;#39;s wild how they always talk about what they predict rather than what is happening.  
 
Yes. We know. Inflation. It&amp;#39;s been getting talked about for MONTHS. Got. Cool story. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:57:00 </td>
   <td style="text-align:left;"> $QQQ When Oil &amp;amp; Gold have gone up over 10% since begining of the year, it is strong indication that inflation has gone up with it..💡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:56:28 </td>
   <td style="text-align:left;"> $SPY $QQQ what you guys thinking for tomorrow?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:55:32 </td>
   <td style="text-align:left;"> $SPY $QQQ I have never been more confused with market as I have been past 2 months. At this point I don’t have any confidence in short or long term outlook. Will just sit tight and watch from sidelines…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:49:45 </td>
   <td style="text-align:left;"> $ZN_F $SPY $SPX $ES_F $QQQ Don&amp;#39;t try to guess how the CPI data tomorrow is going to affect the market. Just watch bond market as the canary in your coal mine.  
 
 An unabated move over 2 on the 10yr will likely have a drawdown affect across the market, especially growth names. If not, a strong continuation of what we have going on this week would not be a surprise at all. (btw, look at the MoM as well before acting.) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:49:30 </td>
   <td style="text-align:left;"> $QQQ $SPY futes not too convincing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:44:18 </td>
   <td style="text-align:left;"> $QQQ https://www.foxbusiness.com/economy/white-house-braces-brutal-inflation-report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:43:38 </td>
   <td style="text-align:left;"> $QQQ my favorite thing is watching bears panic after they finally got the 15% pullback they&amp;#39;ve been waiting years for but forgot to lock in their profits. 🤣

If we drop hard tomorrow they still have a shot, but if we&amp;#39;re green despite hot CPI, it&amp;#39;s risk on baby. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:43:06 </td>
   <td style="text-align:left;"> $SPY $qqq $vix $AMC $GME 🤯🤯🤯🤯 https://youtu.be/rUR2JBbH4Nw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:42:39 </td>
   <td style="text-align:left;"> $QQQ Damn, this market it tough to bring down... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:41:36 </td>
   <td style="text-align:left;"> $SPY  $DJIA $QQQ  
 
JPOW has shown he only knows how to print money for Wall Street and rich people. 
 
The people need a real FED chair to deal with 7% inflation! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:40:44 </td>
   <td style="text-align:left;"> $QQQ won&amp;#39;t dip below 360 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:39:42 </td>
   <td style="text-align:left;"> $QQQ inflation will be 6.9% and they’ll postpone rate hikes till 4/20.  They must fulfill the meme!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:39:05 </td>
   <td style="text-align:left;"> $SPY Tomorrow’s market in summary for team ‘BTFD’ $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:38:36 </td>
   <td style="text-align:left;"> $QQQ inflation just needs to come in inline or just shy of expectations and we’re gonna fly!  Fed still hasn’t started to back off buying it all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:38:23 </td>
   <td style="text-align:left;"> $QQQ Jpow hasn’t let you down by buying the dip why would he now ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:38:14 </td>
   <td style="text-align:left;"> $QQQ $SPY Let&amp;#39;s talk stocks :) 
https://youtu.be/OyJ4HRJ4I9c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:36:16 </td>
   <td style="text-align:left;"> $DIS will this pull an $ENPH tomorrow at open, without the additional $QQQ 2% green?🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:35:03 </td>
   <td style="text-align:left;"> $QQQ tomorrow should be a sucker punch to the nuts for bulls. Huge bear flag on the 4hr chart on most of tech. Nuts will get squashed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:32:17 </td>
   <td style="text-align:left;"> $KWEMF  $QQQ $IWM  $IWC  
 
...Waiting for ATF classification  
 
“Distributors from across the U.S., as well as overseas, expressed strong interest in carrying PARA OPS products and are anxiously awaiting classification from Bureau of Alcohol, Tobacco, Firearms and Explosives, commonly known as the ATF,” said MacLeod. “ATF classification remains pending but is expected in the coming weeks. Orders for product may only be solicited and accepted once ATF classification is received.” 
 
https://www.para-ops.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:30:05 </td>
   <td style="text-align:left;"> $SPY 10-year treasury almost approaching trend support.  monthly candles coincide with March rate hike.  $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:29:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
In 2019 JPOW showed the market he has no backbone. 
 
In 2022 he is showing us again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:29:54 </td>
   <td style="text-align:left;"> $QQQ rest up buddy we’ll need your help again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:29:51 </td>
   <td style="text-align:left;"> $QQQ the calculation of cpi changes from Jan. Whatever it takes to keep people happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:27:32 </td>
   <td style="text-align:left;"> $QQQ opening shorts. If inflation data is suspected or slowing, I will close fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:27:32 </td>
   <td style="text-align:left;"> $SPY CPI don’t matter as long as we have printers ready. Even if we have CPI at 12%, SPY and $QQQ is going ATH. Who cares about other stocks? 

If you don’t love this casino 🎰 you’re missing out 🏃🏽‍♂️🏃🏽‍♂️🏃🏽‍♂️🏃🏽‍♂️🏃🏽‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:26:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA bulls and bears don’t know what’s gonna happen tomorrow either my calls print or my puts do 😈😈 I switch teams faster than MeetKev </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:19:48 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
&amp;quot;Investors will also be paying close attention to measures of inflation expectations, including a reading due Friday, as they size up the Federal Reserve’s likely response to persistent price pressures.&amp;quot; 
 
My god!...where do they get these asshats? 
 
We are at 7 FUCKING PERCENT INFLATION!!! 
 
FUCK THE FED and their &amp;quot;likely response&amp;quot;! 
 
https://www.marketwatch.com/story/will-thursdays-inflation-data-kill-the-stock-market-bounce-heres-what-investors-want-to-see-11644439333?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:18:38 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:17:59 </td>
   <td style="text-align:left;"> $SPY $QQQ balls deep in clown market . wonder what these 2 will decide inflation # is tomorrow . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:17:36 </td>
   <td style="text-align:left;"> $QQQ watch CPI come in at double digits tomorrow loool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:15:43 </td>
   <td style="text-align:left;"> $QQQ NASDAQ looks like it&amp;#39;s really recovering. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:14:09 </td>
   <td style="text-align:left;"> $SPY $QQQ how we trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:13:30 </td>
   <td style="text-align:left;"> $QQQ $spy $aapl

What would be the cpi tomorrow that we need to keep market going green?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:11:25 </td>
   <td style="text-align:left;"> $QQQ wen crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:10:22 </td>
   <td style="text-align:left;"> $QQQ Do you still believe in algos bro? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:09:39 </td>
   <td style="text-align:left;"> This is what keeps us hungry and inspired daily! Couldn’t thank all of you enough for the loyalty and hard passion over the years. Let’s continue this next decade with the same passion, discipline and confidence! $QQQ $AFRM $TWLO $DCFC $IRNT All great days on these names today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:09:15 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
so when is JPOW gonna taper? 
 
oh, right...he&amp;#39;s not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:09:03 </td>
   <td style="text-align:left;"> $SPY $UPRO $QQQ Nasdaq jumps for a second day as investors continue to buy the tech dip https://www.cnbc.com/2022/02/08/stock-market-futures-open-to-close-news.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:08:35 </td>
   <td style="text-align:left;"> $QQQ AH price action is muted. An epic bull trap was set the past two days. Higher inflation and more and faster rate hikes ARE NOT PRICED IN. 7.2 is and 3-4 hikes. That&amp;#39;s way too conservative. This market will turn on a dime before open. Bulls will quiet tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:08:27 </td>
   <td style="text-align:left;"> Fear &amp;amp; Greed Index is still in FEAR $SPX $QQQ $NDX $QQQ 
 
Market need correct this very soon. I am contrarian and I don&amp;#39;t expect more downside until market corrects this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:07:57 </td>
   <td style="text-align:left;"> $SPY $QQQ everything says down tomorrow whether numbers are good or bad. Anything else would be quite a surprise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:07:32 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
7% inflation and $100/barrel oil 
 
and people still buying stonks? 
 
There are some confident motherfuckers out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:06:57 </td>
   <td style="text-align:left;"> $AMRN Huge rally tomorrow?   
&amp;quot;Megasqueeze On Deck As Hedge Funds Unleash Biggest Short Selling Spree In History&amp;quot; - ZeroHedge 
 
A CPI miss tomorrow morning will get the party started. 
 
$IBB $TNA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:06:29 </td>
   <td style="text-align:left;"> $SPY let the air out. $QQQ $IWM 

https://www.fitchratings.com/research/non-bank-financial-institutions/fitch-downgrades-credito-real-to-rd-on-bond-payment-default-09-02-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:05:22 </td>
   <td style="text-align:left;"> $AMD I predict 8% inflation , Russia invade Ukraine, , a new Covid Variant appear and the market crash tomorrow.  Or at the minimum just crash the market! We supposed to be back to normal , not this inflated Covid stock prices where only bulls get to eat!  $NVDA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:04:31 </td>
   <td style="text-align:left;"> $SPY $QQQ everyone now a bull. Except Powell 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:04:29 </td>
   <td style="text-align:left;"> $QQQ $SPY they steal puts from retail this week to play 0dte candy crush with the markets on Friday. Follow the flow, don’t get hit by the waves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:03:16 </td>
   <td style="text-align:left;"> $QQQ Blitzkrieg. Tiger tank cometh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:01:16 </td>
   <td style="text-align:left;"> $SPY $QQQ You know tomorrow is going to be bad when the Biden &amp;amp; Co are already trying to do damage control, the day before the number is announced! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:01:09 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=CI93IWCx9XQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:01:05 </td>
   <td style="text-align:left;"> $QQQ we still have negative real interest rate….bears be like we gonna die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:00:48 </td>
   <td style="text-align:left;"> $qqq $arkk $arkw https://www.youtube.com/watch?v=ST8c5iqmFcQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 07:00:41 </td>
   <td style="text-align:left;"> $QQQ $SPY  never seen two days big rally before CPI numbers fishy fishy leak happen yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:59:02 </td>
   <td style="text-align:left;"> $QQQ $379 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:58:30 </td>
   <td style="text-align:left;"> $QQQ $TSLA $SAVA 

Nice recap:

https://www.thestar.com/business/opinion/2021/03/13/better-policy-can-help-get-casino-tables-out-of-the-stock-market.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:58:27 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:57:00 </td>
   <td style="text-align:left;"> $QQQ has a bad technical rating, but it does show a decent setup pattern. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:56:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ BTFD you know how it works. Dont you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:55:00 </td>
   <td style="text-align:left;"> $SPY $QQQ 
If I&amp;#39;m wrong, at least ill only lose my house. 
&amp;quot;The hardest choices requires the strongest wills.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:53:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $UVXY $CPI  
 
They got the bulls right where they want them: &amp;#39;Return to normal&amp;#39;.  
 
Blowout CPI Numbers tomorrow will confirm that even with 20+ rate hikes this year, there is nothing that can fix the damage that has already been done. GOD SPEED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:53:04 </td>
   <td style="text-align:left;"> $QQQ good earnings. Strong jobs. High inflation.

JPow has to throw half a point onto rates. Or more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:52:58 </td>
   <td style="text-align:left;"> $QQQ Remember if the CPI is too high the Fed will massage the numbers so it&amp;#39;s back to &amp;lt; 2. The goal is to keep the street happy... not main street which is unimportant. Everyone expects bad news tomorrow but this is where you load up to the brink. Today was just a fraction of the rally tomorrow on so called bad news... which are already baked in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:47:46 </td>
   <td style="text-align:left;"> $SPY $QQQ  Tech has more room to grow 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:47:43 </td>
   <td style="text-align:left;"> $PYPL Don&amp;#39;t think I&amp;#39;ve ever seen a major stock this oversold based on RSI and distance from major moving averages.  Couldn&amp;#39;t help but  to go long.  I am short $SPY and $QQQ so hopefully pypl outperforms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:46:59 </td>
   <td style="text-align:left;"> What kind of scam Shit 😂😂 2019-2020 wtf CPI $spy $spx $tsla $djia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:46:45 </td>
   <td style="text-align:left;"> $QQQ bulls gambling again tomorrow will be blooooody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:46:10 </td>
   <td style="text-align:left;"> $BTC.X $AAPL $QQQ $SPY https://markettimes.co.uk/cryptocurrencies/apple-pay-will-work-with-cryptocurrencies/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:45:51 </td>
   <td style="text-align:left;"> $QQQ Closing Tomorrow at 378.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:45:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $AAPL $TSLA  
 
Armed with a twitter degree in economics, I love seeing clueless degenerate retail talk about inflation. 
 
No doubt you will all make michael burry proud tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:45:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $XBI 

Who is actually going to believe their fake numbers? 

Whatever they claim it is, multiply by 2 and that is your real number. 

&amp;quot;Why they always lying? Don&amp;#39;t they get sick of lying? 🥳

I&amp;#39;m going to keep lying to you...until you think it&amp;#39;s, the truth. Yeah yeah!&amp;quot; 😂

Seriously, they need to start playing this as their theme song anytime they&amp;#39;re about to speak about...anything. 🥰

https://youtu.be/WcWM_1hBu_c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:44:53 </td>
   <td style="text-align:left;"> $SLS told you they didn’t cover on the low volume. Now almost 1 million short shares on the official plus all the previous short volume to hold this down, easily 1.5 million short shares that need to be covered. 
 
not sure how volume jumped when it’s been so insanely low. But doesn’t change the short interest amount. 
 
float only 15.88 million primed to explode with recent $15 PT. 
 
$XBI $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:44:12 </td>
   <td style="text-align:left;"> $SPY $QQQ Unreal!! another DIX print over 50. 12 days in a row above 46. This is headed for ATH before March FOMC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:44:07 </td>
   <td style="text-align:left;"> $SPY $QQQ We should see lower inflation numbers in the coming months. It is a midterm year and President Biden knows it, he will do everything he can to bring down inflation to ensure the Dems will win the Congress in November </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:41:20 </td>
   <td style="text-align:left;"> $QQQ daily chart update!!! Bears got roasted. Told ya to wait for the CPI 
 
https://www.youtube.com/watch?v=hLbOOYDeKp8&amp;amp;feature=youtu.be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:40:25 </td>
   <td style="text-align:left;"> $QQQ pump more...so i can short more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:38:05 </td>
   <td style="text-align:left;"> $SPY $QQQ nothing can stop this rally haha lol. Lost 30k in puts. It&amp;#39;s okay tomorrow if CPI close to 8% short all growth. If it&amp;#39;s below 7% or in line buyyyyyyyyy growth. That&amp;#39;s my plan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:37:32 </td>
   <td style="text-align:left;"> $KMPH so $50Mill share buyback in 2023, another milestone payment this quarter with $130M in cash already.  Quarterly cash burn of $2M and commercialization on their ADHD drug just ramping up which have superior properties to Vyvanse.  How is this at $200M market cap?  $xbi $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:35:51 </td>
   <td style="text-align:left;"> $QQQ Bears getting rekt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:34:35 </td>
   <td style="text-align:left;"> $SPY climbing a wall of worry is about as bullish as it gets. $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:33:07 </td>
   <td style="text-align:left;"> Raising cash into market strength. Not saying CPI tmrw will turn things back down I just don’t trust this market right now. Doing more day trades going forward and less swings. Will deploy $$ in LT portfolio if we revisit lows $SPY $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:32:55 </td>
   <td style="text-align:left;"> $SPY the $qqq daily chart is just ugly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:31:41 </td>
   <td style="text-align:left;"> $SPY $QQQ This market is just looking unstoppable right now, not even a slightly higher than expected CPI would stop us from going higher tomorrow IMHO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:31:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP  
Interesting action today. If you were a bear you were warned! Wait for the CPI. 
https://www.youtube.com/watch?v=II6qoZtFsuU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:30:16 </td>
   <td style="text-align:left;"> $SPY $QQQ    YEET. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:30:12 </td>
   <td style="text-align:left;"> Yday Sam said 10 yr yield will likely digest - pulling oil down with potential rotation into tech. She was spot on…her sector rotation analysis is on point!  
 latex5fa5a3ba15ef78b2b7f14a54e09693a7QQQ - PT of 268 hit 
$IWM - PT of 206 hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:29:51 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/9/2022 $SPY $XLF $QQQ $FB $MSOS https://www.chartguys.com/daily-market-videos/4132/game-plan-succeeds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:26:01 </td>
   <td style="text-align:left;"> $VVV one you do not turn ur back on $SPY $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:25:15 </td>
   <td style="text-align:left;"> $QQQ old Jerome and company are backed into a corner. This isn&amp;#39;t the fall of 2018 when inflation was in check and jerome could backtrack. There is no choice now. Raise rates and the economy tanks. Don&amp;#39;t raise rates quick enough and we have run away inflation and riots in the streets. There will be NO soft landing. It&amp;#39;s impossible. 9T balance sheet. 30T in debt. The fed has to raise rates this year not to mention start to shrink that balance sheet. Pretty soon no one is going to have faith in the US dollar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:24:46 </td>
   <td style="text-align:left;"> $SPY $QQQ those MM’s are so sneaky. Washed out a bunch of puts today I’m sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:21:43 </td>
   <td style="text-align:left;"> $QQQ $SPY ALL OF THIS IS JUST A SHORT SQUEEZE OF NEWBIES SHORTIES. THE BIG BOYS ARE BACK IN TOWN NOW, THEY CAN&amp;#39;T LIQUIDATE US. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:20:16 </td>
   <td style="text-align:left;"> $SPY $QQQ what could be in store tomorrow 

&amp;quot;For a peek of what could be in this week’s numbers, the National Federation of Independent Business just released a survey of small businesses and found that 61% increased prices at the beginning of the new year. MarketWatch says that is “the highest percentage since 1974.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:20:10 </td>
   <td style="text-align:left;"> $SHOP $TSLA  inflation numbers come in hotter than expected..decent size dip coming tomorrow $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:20:09 </td>
   <td style="text-align:left;"> $QQQ I have no idea what the stock market will do tomorrow, next month, year, etc. But I do know we as a nation face significant head winds. Too many to list here. I&amp;#39;m concerned about the 7 in 10 americans living paycheck to paycheck that are going to riot when they can&amp;#39;t pay bills anymore. I&amp;#39;m sorry, but I think the market is rigged and I just don&amp;#39;t trust it. I have some exposure to it through long term accounts, but most of my assets are not in the market. I&amp;#39;m really curious to see the fake CPI reading tomorrow. Real inflation to the working class is all that matters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:19:27 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
ill go bearish when companies like DuPont and UPS stop posting record beats and raising dividend yields until then people will look for riskier and riskier ventures to fund the clown market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:16:28 </td>
   <td style="text-align:left;"> $QQQ stonks going up nonstop forever seems to be the only thing keeping our economy running. What happens if stonks stop going up? Can&amp;#39;t be good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:16:10 </td>
   <td style="text-align:left;"> $QQQ $SPY BULLS THIS IS YOU TOMORROW BUYING THE DIP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:14:31 </td>
   <td style="text-align:left;"> $SPY $QQQ careful with pitbull thursday . Might try to shake off weak hands before next opex week🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:13:13 </td>
   <td style="text-align:left;"> $QQQ  
 
I have no idea what is driving this increase. Its like that one guy asked: does inflation nit exist any more? 
 
SMDH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:12:57 </td>
   <td style="text-align:left;"> $MQ This baby is going to fly much higher imo. Just starting $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:11:20 </td>
   <td style="text-align:left;"> $UBER market digesting earnings. These are actually killer. $SPY $QQQ $LYFT $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:11:14 </td>
   <td style="text-align:left;"> $QQQ $SPY payday tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:11:01 </td>
   <td style="text-align:left;"> $QQQ big cup &amp;amp; handle nearly complete… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:10:03 </td>
   <td style="text-align:left;"> $QQQ close over 200  SMA with an Inverse Head and Shoulders in the RSI ready to trigger and at the high volume node.  A higher high would check a lot of boxes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:09:16 </td>
   <td style="text-align:left;"> $QQQ High chance of moon mars and Pluto  
 
Sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:09:04 </td>
   <td style="text-align:left;"> $SPY $QQQ inflation priced in i guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:08:40 </td>
   <td style="text-align:left;"> $MQ Cant wait until Marqeta gets back to 37 plus...Squeeze any shorts left baby $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:08:10 </td>
   <td style="text-align:left;"> $QQQ ok so this hitting 370 and then puts got it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:08:08 </td>
   <td style="text-align:left;"> $DIS so these guys merged quarters and amzn counter Rivian… great going guys. Let’s fuck the shorts $QQQ $SPY $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:06:55 </td>
   <td style="text-align:left;"> $LABU $28 - 30 Doable tomorrow on continuation of momentum. $SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:06:42 </td>
   <td style="text-align:left;"> Few understand the mind bending rally that comes into the end of the week if CPI is anything other than hot like the surface of the sun 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:06:40 </td>
   <td style="text-align:left;"> $SPY $QQQ feeling more and more like sell the news regardless of what it is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:06:17 </td>
   <td style="text-align:left;"> $QQQ gap down on 8% inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:05:05 </td>
   <td style="text-align:left;"> $QQQ gap below with CPI tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:04:47 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

too many bulls... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:04:22 </td>
   <td style="text-align:left;"> $ENVA interesting news today. The hits keep coming but we sadly lost a follower. 533 now.  
 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:02:57 </td>
   <td style="text-align:left;"> $QQQ some people tried to short bull market last month 
RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:02:27 </td>
   <td style="text-align:left;"> $QQQ my too trade idea for tomorrow $Z before ER.  Down 75% from highs, it’s been silent for a long time.  Has not had a good bounce, and it has 15% short interest.  Risk what you can afford to lose. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:01:12 </td>
   <td style="text-align:left;"> $UVXY the bearish pumpers in the market have nothing to sell. They want to pump volatility tonight because it is the only way they can induce the panic they want after that disaster dump attempt before close. $spy $qqq $dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:01:07 </td>
   <td style="text-align:left;"> $QQQ when both technology and re-opening stocks go up huge it is just an old fashioned bull market ass kicking for the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:00:36 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-09 Options Analysis Video: 
https://www.youtube.com/watch?v=-O7egoSTmTQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 06:00:32 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
When you are handing out 9 TRILLION FREE DOLLARS...yes, greed is good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:58:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $AMZN  
 
Big shoutout to the retail bears. You clueless degenerate fuckwits make it all possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:57:48 </td>
   <td style="text-align:left;"> $MQ Marqeta is the future raising guidance and Hiring Visa Veteran Mike Milotich as New CFO. Makes you wonder if $V will want to buy them outright $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:57:43 </td>
   <td style="text-align:left;"> $QQQ what’s everyone’s thoughts on the CPI reading tomorrow?  Inflation has been kicking it in high gear recently, and I believe the reading is going to come in much worst than people are expecting.  I believe we have a decent sized dip tomorrow morning.  Please change my mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:56:16 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM closing at today&amp;#39;s high, before CPI tomorrow.  Does this mean that the market is expecting &amp;quot;good&amp;quot; or &amp;quot;no bad surprises&amp;quot;? 
My guess is  that CPI won&amp;#39;t be good.  They&amp;#39;ll be &amp;quot;bad...as expected&amp;quot; by the market.  Thus, &amp;quot;no surprises&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:56:00 </td>
   <td style="text-align:left;"> $QQQ $spy

These charts could really use some more gaps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:55:36 </td>
   <td style="text-align:left;"> $SPY bears today 😂 $QQQ $DIS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:55:19 </td>
   <td style="text-align:left;"> $QQQ wow, all the earnings look great -- this is going higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:54:54 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Biggest fraudster in America today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:54:29 </td>
   <td style="text-align:left;"> $SPY any profit coming from calls is getting roll over into puts for the next few months 😬 pretty much using their money to cash in 😬😎
$QQQ $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:51:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Every bump on the chart corresponds to Wednesday injections of BILLIONS AND BILLIONS of free FED dollars for Wall Street Banks. 
 
Absolute fucking PONZI at this point and JPOW refuses to taper or raise rates until all his buddies have cashed out at all time highs. 
 
What a fucking charade our country has become. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:51:03 </td>
   <td style="text-align:left;"> $SPY Premium says MMs are going to squeeze the shorts mercilessly &amp;quot;for a few.&amp;quot;  Too much  put premium on tech.  They&amp;#39;re going to kill it. 
 
$WIM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:51:01 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 648.8K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:50:56 </td>
   <td style="text-align:left;"> $QQQ What did I predit. It will be the best trading day in history tomorrow:

1) Dow + 1200
2) Nasdaq +6%

At least, especially if inflation figures are disastrous. And as required per irrationality 101 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:49:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $SPX $AAPL 

Bulls win or lose,

no one becomes bankrupt faster than a retail bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:48:48 </td>
   <td style="text-align:left;"> $QQQ some pretty crappy looking earnings in the AM, plus cpi data has pumped the last few days... When it releases, should start sinking tomorrow. Sell the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:48:24 </td>
   <td style="text-align:left;"> I thought the little man with a big bark hid in a corner, but it looks like he is back to barking again. Someone, go show him his hiding place again before the USA takes him up on his bluff. https://www.msn.com/en-us/news/world/north-korea-threatens-to-shake-the-world-by-firing-a-missile-at-the-u-s-mainland/vi-AATEnum?ocid=msedgntp 
 
$SPY $QQQ $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:48:01 </td>
   <td style="text-align:left;"> $QQQ $SPY indexes don&amp;#39;t exist so we can have something that moves 3% in random directions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:48:00 </td>
   <td style="text-align:left;"> $SPY $QQQ What a great day! This is very tricky tbh. If the gap remmains open chances we will go above 4748 before we pullback. If this has to happen then tomorrow we should open flat and go down not far from today&amp;#39;s low.  
If we gap down we should not break 4465, otherwise lower prices are likely. In this case we may form a wedge before exploding to the upside, just like $XBI (see pic). 
$XBI moves when you expect it the least. I sold few of my calls too early, hope to get back at the same price. Looks like a breakout to me, the volume is great (see pic), but $XBI is a B, it&amp;#39;s faking it a lot! If this decides to move up it won&amp;#39;t pullback a lot and the rising trendline should hold until the end of the move. 
https://www.tradingview.com/x/snGZfwg9/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:47:43 </td>
   <td style="text-align:left;"> $QQQ up huge tomorrow with lower inflation rate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:46:32 </td>
   <td style="text-align:left;"> $QQQ what time do CPI numbers come out tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:46:29 </td>
   <td style="text-align:left;"> $QQQ Wen $390 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:45:55 </td>
   <td style="text-align:left;"> $QQQ the play this ER has been to buy the deeply oversold (60%+) stocks that are able to show continued growth.  If even for a short bounce, some huge moves, and more coming tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:45:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
7% inflation and this fucker is still printing 
 
incredible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:45:40 </td>
   <td style="text-align:left;"> $QQQ So what now? Disney will carrie the market. My gosh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:45:17 </td>
   <td style="text-align:left;"> $QQQ I want to see this crash 50% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:44:14 </td>
   <td style="text-align:left;"> $UBER damn should have went heavier in $DIS. If Uber hold $40 this is still a great play. Still a major beat, but we need $45 tomorrow though for anything fun, $SPY $QQQ $LYFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:43:58 </td>
   <td style="text-align:left;"> $QQQ Oil &amp;amp; Gold both up over 10% for the month of January. Inflation definately isn&amp;#39;t getting better guys.. expect a rugpull tomorrow am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:43:57 </td>
   <td style="text-align:left;"> $AAPL will take us to the promised land $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:41:23 </td>
   <td style="text-align:left;"> $QQQ interested in what people think of this market. It has no trajectory just pumped up then down. No doubt it’ll be down to 14200 next week then back to 15 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:40:45 </td>
   <td style="text-align:left;"> $QQQ I predict gap down for open tmr and end up bleeding up to green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:40:17 </td>
   <td style="text-align:left;"> $QQQ According to many, it&amp;#39;s not been a good time to buy stocks during the last 2 weeks.   
 
No mater what happens in the market, there will always be something that&amp;#39;s holding traders back.   
 
And please spare me the CPI drama. 
It will be what it will be. 
 
https://share.trendspider.com/chart/SPY/6682g2s4e8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:39:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
 
70% cash in my retirement accounts as of close of day. 
 
Piggie getting the fuck outta this Ponzi as we run back to 4800. 
 
gl! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:38:58 </td>
   <td style="text-align:left;"> $QQQ I bet we drop tomorrow on CPI so many calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:38:40 </td>
   <td style="text-align:left;"> Option Challenge (day 7): P/L total = +$63,805 (+31% since start on Feb 1),  P/L today = +$13,676, winners = 4, losers = 1, winners = $AFRM 75/80 call spread, $AMZN 3300 puts , $RBLX 65 calls, $FB 225 calls, loser = $QQQ 360 puts. Positions I am holding overnight: 100 AFRM Feb 11th 75/80 call spreads and 10 Feb 11th $QQQ 360 puts (which are almost worthless right now). Get real-time notifications here: https://www.quantyeti.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:36:40 </td>
   <td style="text-align:left;"> $QQQ watching close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:35:59 </td>
   <td style="text-align:left;"> latexd71782de6c8b2b55a6c90598d9d98ee7QQQ 11.04% from ATH 📈
$DJIA 3.09% from ATH 📈

Keep it classy you degenerates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:34:47 </td>
   <td style="text-align:left;"> $QQQ tomorrow will be huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:34:44 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
still printing... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:32:33 </td>
   <td style="text-align:left;"> Like the Fed board this market is losing its credibility. The pumps &amp;amp; dumps are becoming violent with hedge funds manipulating prices however the outdated SEC rules allow them. It’s a more of a casino rather than equity investment.  
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:30:36 </td>
   <td style="text-align:left;"> $QQQ $SPY whats so bullish. I don’t have an opinion or stance but I’m genuinely curious? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:29:55 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:29:54 </td>
   <td style="text-align:left;"> $QQQ i feel sorry for the lower income and fixed income people out there that will feel inflation first and it will be bad. CPI is a joke. Real inflation is much higher if you need a place to live, car to drive, gas, groceries, etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:29:45 </td>
   <td style="text-align:left;"> $QQQ $SPY  Now that the most foolish of traders FOMO’Ed… tomorrow’s CPI will be “Oh shit” levels… it will make January look  like a baby dip 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:29:25 </td>
   <td style="text-align:left;"> Running those $AMZN scalps for much of the day at $10 a pop, long. Cost average now down to $2820s. Long scalp from last week in $VZ bought at $52.75 sold today and some $TQQQ scalping.  
 
You can trade with me folks! 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:27:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL   
 
Building a long-term core holding in $DIS with first trade complete from $157.18 sold $160.41 after hours. You can see the trade alert in my ST feed. Nicely done Finom Group members! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:27:15 </td>
   <td style="text-align:left;"> $QQQ I was bearish. Very much so… But these levels that we’ve broken through, then went back and retested are substantial… $TQQQ until proven otherwise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:25:45 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ buybacks, dividends, and earnings are only improving ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:25:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIS

FEAR THE MOUSE BEARS!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:24:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Its raining f money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:24:18 </td>
   <td style="text-align:left;"> $QQQ $SPY Retail still bearish, the melt up could very well continue back to January 3 levels by next earnings season(or sooner) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:23:37 </td>
   <td style="text-align:left;"> $SPY $QQQ MOC $1.47B to the buy side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:23:15 </td>
   <td style="text-align:left;"> $QQQ the market is just a farce, will leave my shorts until it drops, I’m in no rush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:23:09 </td>
   <td style="text-align:left;"> $DIS $QQQ $SPY Bear Market???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:22:28 </td>
   <td style="text-align:left;"> $QQQ show yourself if you think disney earnings will have any impact on QQQ tomorrow and Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:20:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
If you ain’t taking profits right now on these earnings , you’re  just waiting to get slaughtered, aren’t you…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:20:35 </td>
   <td style="text-align:left;"> $QQQ the fed has removed the tether of stability. Now this market is like Nigerian or Chinese or Indian market. Flip flopping like a pos. 

Because that’s how dumb our bureaucrats are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:19:22 </td>
   <td style="text-align:left;"> $SPY $QQQ s hit resistance at 200 DMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:19:10 </td>
   <td style="text-align:left;"> $QQQ this doesn&amp;#39;t give a damn about DIS or UBER. This will trade the rest of the week off the cpi number tomorrow which will be higher than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:18:59 </td>
   <td style="text-align:left;"> $QQQ either we pump or dump. There is no in-between. This market is wild af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:18:57 </td>
   <td style="text-align:left;"> How to Size Up the U.S. Corporate Profit Boom? $QQQ $SPY $DIA https://www.zacks.com/commentary/1865152/how-to-size-up-the-us-corporate-profit-boom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:18:49 </td>
   <td style="text-align:left;"> $QQQ Mickey Mouse pump tomorrow, Friday bearish intraday reversal, next week dump resumes and breaks 340 support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:15:21 </td>
   <td style="text-align:left;"> $QQQ lol has inflation disappeared or something? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:15:21 </td>
   <td style="text-align:left;"> $QQQ what a close wow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:15:19 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA This has to be the greatest bull trap of all time!!! Rally before the CPI data tomorrow. If you bought today good bless you!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:15:10 </td>
   <td style="text-align:left;"> LOTTO LIST 1-DAY RESULTS:

🎉 $SPY 460c .45 &amp;amp;gt; 1.8 (400%)
🔮 $QQQ 370c .34 &amp;amp;gt; 1.78 (423%)
🤑 $TSLA 1000c 1.4 &amp;amp;gt; 3.6 (157%)
☢️ $NVDA 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:14:57 </td>
   <td style="text-align:left;"> $QQQ I.V. in the ATM 11-Feb-22 Increases +5.5%. Options Imply a Move of ±1.8% with 2 Days to Exp https://tinyurl.com/y43nc2ef </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:14:22 </td>
   <td style="text-align:left;"> $QQQ $SPY Uber and Disney both just reported better than expected earnings and revenues. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:13:44 </td>
   <td style="text-align:left;"> $SSKN Important news has come out now 
&amp;quot;STRATA Skin Sciences, Inc. (NASDAQ: SSKN), a medical technology company dedicated to developing, commercializing and marketing innovative products for the treatment of dermatologic conditions, today announced its commercial launch, with the first installation in the U.S. market, of its next generation excimer laser system, XTRAC Momentum™ 1.0.&amp;quot; 
https://www.stocktitan.net/news/SSKN/strata-skin-sciences-announces-commercial-launch-of-xtrac-momentum-1-zxio4wud2wyz.html 
LONG and STRONG $SSKN 10$ stock imo  
watch $labu $qqq $tna $gnus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:13:24 </td>
   <td style="text-align:left;"> $QQQ 370-375, and 380 are the next price targets. But I do not, at this time, think we&amp;#39;re going to all time highs from there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:13:06 </td>
   <td style="text-align:left;"> $QQQ so glad I shorted before the close😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:12:41 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
   
&amp;quot;The U.S. central bank began tapering in November 2021, scaling back total purchases by $15 billion a month, from $120 billion to $105 billion. The Fed decided to double the pace at which it tapers on Dec. 15. Rather than $15 billion, the Fed will reduce purchases by $30 billion every month.&amp;quot;   
   
So approximately...   
 
Oct         120  Billion 
Nov        105  Billion 
Dec        82.5  Billion 
Jan        52.5  Billion 
Feb        22.5  Billion 
Mar        taper complete   
   
   
Obviously JPOW is full of shit.    
   
It&amp;#39;s also interesting there is not a single article anywhere discussing the ACTUAL taper amounts the last few months. That&amp;#39;s not coincidence. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:11:46 </td>
   <td style="text-align:left;"> $QQQ $SPY definitely didn&amp;#39;t see a gap up on the daily with an overbought 30 minute going into cpi data coming today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:11:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Didn’t Pelosi have $DIS calls?  😂 Trader of the millennium. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:10:37 </td>
   <td style="text-align:left;"> Significant resistance from here to 380 but this is a great first step to close over 50sma weekly by Friday.  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:10:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Weirdest market crash ever! Wen futes ripping? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:10:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $UVXY $AAPL 
 
Now that options are locked in, I regret to inform all Call holders, that tomorrow&amp;#39;s CPI will be the worst yet, given that oil alone went up 16% last month.  
 
Only thing that will outpace oil prices are the value of my puts at opening bell. F ALL YA&amp;#39;LL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:10:16 </td>
   <td style="text-align:left;"> $QQQ 

Held off on getting put credit spreads for this Friday to see how the market will react to CPI. So far it looks priced in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:10:07 </td>
   <td style="text-align:left;"> $QQQ damn so many companies popping after earnings today. Feels like late 2020 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:09:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Wow a monster numbers from $DIS, market likely will be up again tomorrow on as long as we don&amp;#39;t get some shockingly high inflation numbers tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:09:29 </td>
   <td style="text-align:left;"> $MULN  futures still green $djia $nasdaq $qqq $nasdaq We are looking  at a $23 stock under $2 ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:09:24 </td>
   <td style="text-align:left;"> $SPY so, I guess data must of leaked and is not &amp;quot;as&amp;quot; bad? 🤔👀
$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:09:06 </td>
   <td style="text-align:left;"> Here is the most beautiful bubble you can find around you! The following image is taken by the eROSITA X-ray telescopes (a joint Russian–German project not a NASA project).  
 
What do we see here? Our own Milky-way. What do you notice? Our galaxy is not just a giant flat spiral galaxy, there is a disk there but there are more into it. See the center, our galaxy is erupting at the galactic poles creating giant Xray emitting bubbles!  
  
Here is the real bubble, do not look for bubble(s) in the market ($SPY, $QQQ), while there is such a beautiful bubble in our neighborhood, just Look Up ($NFLX)! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:08:20 </td>
   <td style="text-align:left;"> $QQQ i will pray for the shorts given the cash coming in and the earnings from DIS UBER TWLO others, open wide... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:08:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$1.467B to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:08:03 </td>
   <td style="text-align:left;"> $QQQ all earning beat and outperform.
The inflation story is so overplayed in a strong economy 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:07:40 </td>
   <td style="text-align:left;"> $QQQ AH crypto rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:07:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:06:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:06:32 </td>
   <td style="text-align:left;"> $QQQ you can still buy and short(sell) now ;) but the best thing is to stick to a game plan and be hedged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:05:59 </td>
   <td style="text-align:left;"> $QQQ CPI is priced in, pump will continue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:05:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 2/10 - CPI will be fun 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:05:33 </td>
   <td style="text-align:left;"> $QQQ for those who are wondering what the CPI Zia going to be, it’s 7.2😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:04:59 </td>
   <td style="text-align:left;"> $QQQ they leave the algos on auto pilot today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:04:45 </td>
   <td style="text-align:left;"> $QQQ algos just taking your money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:03:59 </td>
   <td style="text-align:left;"> $QQQ $SPY great stuff but we need a pullback to make sure healthy moves up and it’s not an extended bounce into further red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:03:56 </td>
   <td style="text-align:left;"> $SQQQ up 10% PM tomorrow 👀

$QQQ $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-10 05:03:52 </td>
   <td style="text-align:left;"> $QQQ I shoulda held my calls til close damn missed 2-3000 damnit I shoulda held </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:31:45 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/6CEegZU5Bsc tomorrow is the make or break catalyst … lets go apple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:31:04 </td>
   <td style="text-align:left;"> $AAPL  Tomorrow we print regardless lfg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:24:44 </td>
   <td style="text-align:left;"> $UVXY $SPY $AAPL $AMZN - Metals are down, futures are flat.. Fed says a 50 basis point hike isn’t needed... I think we have plenty of info on tomorrow’s report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:20:20 </td>
   <td style="text-align:left;"> WATCHLIST FOR TOMORROW 💨🅿️

1. $RBLX- NFL news, nice daily candle, with volume, looks ready to keep pushing up. 30min chart closed above a key level at 69.8. Bullish on this. 

2. $COST- rejected by weekly resistance and closed right on it. Looking for a clean break over 529/530 to swing calls into next week or otherwise we could start seeing some downside again. 

3. $JD- 4hr showing inverse head and shoulders. Could be a nice swing heading into next week. Todays daily candle closed right on daily resistance so we’ll see if we can get a push up. 

4. $AAPL- showing inverse head and shoulders on daily. Waiting for a clean break of 177 area to go long on calls targeting ATH. One of the cleaner set ups imo. 

Check profile for more 🙏🏽💯🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:18:26 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow. 
 
https://youtu.be/22UXXTb-fLg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:17:51 </td>
   <td style="text-align:left;"> $AAPL https://9to5mac.com/2022/02/09/tesla-cybertruck-designer-criticizes-apple/

I am glad that Tesla is bashing Apple to Prime them up - Hoping they show off an excellent product that has this 

&amp;quot;wow , we never thought about this&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:16:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWN $UVXY $AAPL  
 
I need one of you quants to run the CPI numbers tomorrow but with the math they used back in 1978. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:14:00 </td>
   <td style="text-align:left;"> In the last month $AAPL has a been trading in the 154.70 - 177.18 range, which is quite wide. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:11:51 </td>
   <td style="text-align:left;"> $AAPL What a joke! Yeah, right.  Apple misled investors.  Apple said it was going to make $30 billion in profits and it made $35 billion.  Trust me, we investors are fine.  😂  All the market manipulation going on out there and these clowns want to investigate Apple’s NDAs under the guise of protecting Apple’s investors and employees. Sounds like somebody has their hand out for some quick cash. Make ‘em work for it, Tim. 

https://www.washingtonpost.com/politics/2022/02/07/state-officials-urge-sec-probe-if-apple-misled-investors-nondisclosure-rules/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:10:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT If CPI shows more than 7% inflation, will market gets knee jerk reaction? Let’s volatility print both calls and puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:08:34 </td>
   <td style="text-align:left;"> $AAPL $PTON $AAL $TSLA $SPY  
 
They pumped it up right before CPI. Awesome!... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 09:00:43 </td>
   <td style="text-align:left;"> $DIS $AAPL $AMZN $NFLX $GOOG Welcome to DAANG!  Disney blowing it out like APPL, AMZN, GOOG.  Disney and all the ways it is growing...they are growing like a reliable growth stock with many different established areas of revenue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:57:23 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/GZyKmreC3rs

Lift-off mode </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:49:00 </td>
   <td style="text-align:left;"> $AAPL READY TO HO  🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:48:18 </td>
   <td style="text-align:left;"> $AAPL this will outpace everything else tmrw.    3-5% up.    Best combo of value and growth in market today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:47:52 </td>
   <td style="text-align:left;"> $AAPL AAPL will be red  2%+ tomorrow. 
Time to go back under $173 where it belongs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:47:39 </td>
   <td style="text-align:left;"> $AAPL will be $180 tmrw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:47:16 </td>
   <td style="text-align:left;"> $AAPL 
🍏🔜🔝🆙
Inflation right now 8%. Cover with Apple 
Your Savings. 
Apple Go to $205. Around The Corner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:39:00 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $NFLX  Removed some fluff from my follow list and looking to follow good accounts. Who out there should I be following? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:38:50 </td>
   <td style="text-align:left;"> $AAPL Tomorrow  #SPY  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:38:40 </td>
   <td style="text-align:left;"> Apple Stock ( $AAPL ) Buying The Dips At The Blue Box Area. Read the article:  https://elliottwave-forecast.com/trading/apple-stock-aapl-buying-dips-blue-box/ #elliottwave #ondaselliott #apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:38:35 </td>
   <td style="text-align:left;"> $BABA red ah just like $aapl wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:34:18 </td>
   <td style="text-align:left;"> $AAPL https://us02web.zoom.us/webinar/register/WN_QrHtvHgRRySnbumjn3ug-Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:33:36 </td>
   <td style="text-align:left;"> Specialized disclosure report https://www.conferencecalltranscripts.com/summary/?id=10418970 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:24:24 </td>
   <td style="text-align:left;"> $AAPL Back to $173 Tmrw 
 
Why 8 State Treasurers Are Asking The SEC To Investigate Apple 
February 09, 2022 1:18pm  
 
Why It&amp;#39;s Important: The SEC could initiate a probe into whether Apple&amp;#39;s non-disclosure agreement violates SEC&amp;#39;s anti-gag rules, according to Zuckerman Law, a Washington, D.C.-based law firm that represents whistleblowers and litigates employment-based disputes. 
 
The anti-gag rule prohibits anyone from taking any action to prevent an individual from communicating directly to the SEC staff about a securities law violation, Jason Zuckerman, principal of Zuckerman Law, said in an article in the National Law Review. 
 
&amp;quot;If Apple is using concealment clauses and unlawful NDAs to silence whistleblowers, then Apple shareholders may not have an accurate and complete picture of the company&amp;#39;s financial condition and risks, including Apple&amp;#39;s ESG-related risks and risks stemming from its potential violations of anti-trust laws,&amp;quot; Zuckerman said. 
 
https://www.benzinga.com/news/22/02/25514355/why-8-state-treasurers-are-asking-the-sec-to-investigate-apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:20:23 </td>
   <td style="text-align:left;"> $AAPL 150p march 18 thank me later. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:20:00 </td>
   <td style="text-align:left;"> 📊 $AAPL 
🚀 94% Profitable 
🤖 AI-Driven Machine Learning 
🏆 SwingTradePro Strategy 
Join Our Premium Room For Live Trade Alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:19:52 </td>
   <td style="text-align:left;"> $AAPL Apple is the only CCP company that survived the Crack down. .Its breached the 50 sma and headed towards Bear territory..You been warned.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:14:06 </td>
   <td style="text-align:left;"> $SPY how come apple underperformed the market when it’s not technically overbought. I smell. Short term top $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:10:20 </td>
   <td style="text-align:left;"> $AMZN $AAPL Manipulation = lowball estimates then beat it with adhoc revenue item or estimate higher inflation and if it is 7.2% vs 7.3% (coz you already know what it is) then madly run to ATH every day again just like 2020 and 2021. Cannot wait for markets without the FED involvement to finally see the real market. 1% increase is a BIG thing for a given day. Now we see 15-20% action on both sides. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:09:41 </td>
   <td style="text-align:left;"> $AAPL THE APPLE DOESNT FALL FAR FROM THE TREE. Just to $90 😩😂😭 I’ll buy then.
Only bullish on meme stocks 🚀 $AMC $GME $SNDL $CENN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:08:44 </td>
   <td style="text-align:left;"> $DIS $AAPL $AMZN $GOOG Not sure if FB or NFLX drop but welcome to the world of DAANG. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 08:02:46 </td>
   <td style="text-align:left;"> $AAPL 

https://stocktwits.com/Melbenross/message/432375322 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:56:04 </td>
   <td style="text-align:left;"> $AAPL I been scalping those $175  calls all day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:54:41 </td>
   <td style="text-align:left;"> $ROKU $DIS $NFLX $AAPL  As I&amp;#39;m sure most of you know, the huge increase in Disney subs will continue as they add top shows like Boba Fett, Pam and Tommy...all the movies etc. etc. Many of those sign ups come through Roku and they take commission for each one. Then there is the ad revenue...if you watch on the Roku OS you can see the free channels and they have ads. Roku are great at targeting ads to the right demographic. Advertisers LOVE this...so pay a good price. 
 
When you think about all of the great streamers such as Peacock, HBO Max, Netflix, Amazon Prime, Apple, Hulu and others...the same applies. So this will snowball and grow faster and faster. This time when it breaks $500 it will not stop! 
 
If you don&amp;#39;t own the stock now (do not trade it!) then this could be your last, best chance to get on board. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:52:48 </td>
   <td style="text-align:left;"> WoW 🤩 

Russell Westbrook will make $47,063,478 in the 2022/23 season. 
That’s $573,945 per #NBA in season game.

$AMD ↗️➕ $XLNX 📈

$AAPL $TSLA $BTC.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:51:19 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 59.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:48:25 </td>
   <td style="text-align:left;"> $AFRM Reupping in case you missed it. $AAPL is going to make a play into the BNPL space. Very doubtful they’d outsource this, but it’s worth watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:47:47 </td>
   <td style="text-align:left;"> $SPOT $AAPL $AMZN Snoop Dogg takes over Death Row Records brand as owner https://www.billionaireclubcollc.com/snoop-dogg-takes-over-death-row-records-brand-as-owner/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:45:05 </td>
   <td style="text-align:left;"> $AMC $TQQQ $AAPL All that you need to know... Shorts haven&amp;#39;t covered a single share:---&amp;gt; Check it out below 👇 
 
~~~~~~~~~~~~~~ 🚀 discord.io/W5xTvWebnw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:41:40 </td>
   <td style="text-align:left;"> $AAPL setup for a 3rd of a 3rd wave again. hopefully the real deal this time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:39:59 </td>
   <td style="text-align:left;"> $GOEV LIFESTYLE vehicle encompasses your friends family and neighbors coworkers. Apple 🍎 market is all about LIFESTYLE products $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:39:50 </td>
   <td style="text-align:left;"> $AAPL  🍏 AfterHours Volume, 6.7 Million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:39:31 </td>
   <td style="text-align:left;"> $AAPL upside down is bearish head and shoulders ... now turn your phone upside down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:36:02 </td>
   <td style="text-align:left;"> $AAPL  1000 bucks a fay keeps the 9 to 5 away 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:35:29 </td>
   <td style="text-align:left;"> $AAPL by Friday $SPY  440 #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:30:19 </td>
   <td style="text-align:left;"> $AAPL   180 eow. This machine is unstoppable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:25:14 </td>
   <td style="text-align:left;"> $SPY $AAPL this app is so glitchy and laggy still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:21:50 </td>
   <td style="text-align:left;"> $CLSK 🔥💵🏦🎉💯🍾🥂🚀 $SPY $AAPL $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:17:24 </td>
   <td style="text-align:left;"> $AAPL enough is enough…5% downside move incoming within next 2weeks… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:17:13 </td>
   <td style="text-align:left;"> $ATOM $AAPL $TSLA $NIO Atomera: A Sleeping Giant in the Semiconductor Industry
https://youtu.be/J5P9xJEUOhA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:16:47 </td>
   <td style="text-align:left;"> $LCID $TSLA $AAPL my chase account 😎🤟🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:13:30 </td>
   <td style="text-align:left;"> $QQQ $spy $aapl

What would be the cpi tomorrow that we need to keep market going green?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:10:40 </td>
   <td style="text-align:left;"> $AAPL started a position in march calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:10:05 </td>
   <td style="text-align:left;"> $SONO Now if it is a candidate to be acquired by $AMZN $AAPL  
One of its competitions is $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:08:46 </td>
   <td style="text-align:left;"> illegal naked shorting = financial terrorism, we knew all along. gonna take a long time to close that position SHITADEL $GME $XRT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:08:00 </td>
   <td style="text-align:left;"> $AAPL has a very good Piotroski-F score of 8.00. This indicates great health and profitability. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:07:32 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
7% inflation and $100/barrel oil 
 
and people still buying stonks? 
 
There are some confident motherfuckers out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:06:07 </td>
   <td style="text-align:left;"> Stock correlation table for March 2022: Apple( $AAPL… https://www.macroaxis.com/invest/stock-correlation?s=AAPL,CMA,USB,LOW,WDC,BNS,SAFT,PRGO,GILD,PGR,CI,SPLTF #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:02:55 </td>
   <td style="text-align:left;"> $AAPL what time is CPI meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:01:31 </td>
   <td style="text-align:left;"> $AAPL looking good after market ,that pennant at 176 looking best chance so far of breaking above </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 07:01:09 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=CI93IWCx9XQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:53:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $UVXY $CPI  
 
They got the bulls right where they want them: &amp;#39;Return to normal&amp;#39;.  
 
Blowout CPI Numbers tomorrow will confirm that even with 20+ rate hikes this year, there is nothing that can fix the damage that has already been done. GOD SPEED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:53:56 </td>
   <td style="text-align:left;"> $AAPL Buying Apple ?, watch this first. https://youtu.be/-dkPQOX_kY8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:53:36 </td>
   <td style="text-align:left;"> all sectors green $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:50:34 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $177.5 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:49:31 </td>
   <td style="text-align:left;"> $AAPL bought two call options expiring next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:46:10 </td>
   <td style="text-align:left;"> $BTC.X $AAPL $QQQ $SPY https://markettimes.co.uk/cryptocurrencies/apple-pay-will-work-with-cryptocurrencies/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:45:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $AAPL $TSLA  
 
Armed with a twitter degree in economics, I love seeing clueless degenerate retail talk about inflation. 
 
No doubt you will all make michael burry proud tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:41:57 </td>
   <td style="text-align:left;"> $AAPL no way they pay the $180 calls that cost .10 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:41:40 </td>
   <td style="text-align:left;"> $aapl 👌👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:40:33 </td>
   <td style="text-align:left;"> $AAPL The only way this  will  increase in price, if you nobs pump up the price in the Premarket 🍆💋🍆 sincerely yours, Tim Shady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:33:47 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $RBLX  
 
Tech about to regain some momo? 
 
https://www.youtube.com/watch?v=II6qoZtFsuU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:32:53 </td>
   <td style="text-align:left;"> Looks like tomorrow we may drop a little CPI, but the bottom was put in 2 weeks ago. There may be some bumpy news forward but this year is an election year, I can’t see a scenario where they let it go into recession. People forget the stock market is political. I am now 90% invested as of Monday. Was buying the dips last two weeks.  GL everyone 

🚨 $AAPL  $TSLA $BTC.X $GOOG $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:32:09 </td>
   <td style="text-align:left;"> $AAPL 185 by the end of the month that is all I am asking for </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:32:02 </td>
   <td style="text-align:left;"> $AAPL Thinking about buying options expiring next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:25:59 </td>
   <td style="text-align:left;"> @FinancialTrades $AAPL currently trading at $176.45 as of now i have good support at $176. Possible bull run again towards $177. Watch and make sure $AAPl doesn&amp;#39;t break that $176 support careful. @everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:24:25 </td>
   <td style="text-align:left;"> $GOOG  $AAPL $NVDA  
 
Google&amp;#39;s stock split is perfect for investors 
 
https://utradea.com/blog/Googles-stock-split-is-perfect-for-investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:22:08 </td>
   <td style="text-align:left;"> $AAPL MAKE CHINA GREAT AGAIN 🍆🕐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:22:00 </td>
   <td style="text-align:left;"> $AMD $AAPL $NET $TSLA 6 hikes priced in already! 
Sounds like peak hawkishness has already been priced into markets. If tech rallies off CPI tomorrow, I think green light until the next CPI on March 10th </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:21:23 </td>
   <td style="text-align:left;"> $AAPL $6 more dollars fellow BULLS/LONGHOLDERS and AAPL sets A New All Time High...!!!!  Let&amp;#39;s push this MoFo up there!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:19:39 </td>
   <td style="text-align:left;"> $AAPL can this touch 180 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:15:37 </td>
   <td style="text-align:left;"> $AAPL 180 tommorow with or without bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:05:38 </td>
   <td style="text-align:left;"> $AAPL Per the last two, I think the negative re: the CPI is already priced in.  The market selling is exhausted for now IMO (premiums say so as well...) 
 
https://twitter.com/MeisaBonelli/status/1491532619342876678?s=20&amp;amp;t=brzot2pAlSlc1Qbru2oE-Q 
 
$NVDA $AMD $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:05:25 </td>
   <td style="text-align:left;"> $AAPL this bull run today just means tomorrow market will tank after CPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 06:00:15 </td>
   <td style="text-align:left;"> $AAPL $AMZN $ROKU Does CPI report tank the whole market in pre market tomorrow morning? I’m kind of regretting getting back in today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:58:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $AMZN  
 
Big shoutout to the retail bears. You clueless degenerate fuckwits make it all possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:56:07 </td>
   <td style="text-align:left;"> $AAPL this may be ATH this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:54:29 </td>
   <td style="text-align:left;"> $SPY any profit coming from calls is getting roll over into puts for the next few months 😬 pretty much using their money to cash in 😬😎
$QQQ $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:51:35 </td>
   <td style="text-align:left;"> $BKKT $AAPL How on earth is Bakkt who is 68% owned by $ICE NYSE and NASDAQ trading at such a piss poor valuation with all these partnerships?? and Apple around the corner?  
 
https://pbs.twimg.com/media/FDo6Ic5XMAEeLIR?format=jpg&amp;amp;name=900x900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:50:55 </td>
   <td style="text-align:left;"> $AAPL thank you Jesus. 💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:50:03 </td>
   <td style="text-align:left;"> $VIAC viacomcbs will become a bone in a dog fight now that Disney is back on track.  Apple. Amazon. WBD. Comcast.   Netflix.  There will be a bidding war for the Prince of content.  $DIS  $NFLX  $AAPL    Netflix will be the most desperate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:49:33 </td>
   <td style="text-align:left;"> $AAPL this has only gone up 30 bucks since september 2020 spike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:49:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $SPX $AAPL 

Bulls win or lose,

no one becomes bankrupt faster than a retail bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:46:49 </td>
   <td style="text-align:left;"> $BKKT $AAPL  NEWS OUT MOTHERFUCKER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:43:57 </td>
   <td style="text-align:left;"> $AAPL will take us to the promised land $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:42:38 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #4 stock that institutions are trading over rolling 5 day window with 260.5K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:42:17 </td>
   <td style="text-align:left;"> ✅10-1 so far this week on signals❌
(CLOSED) 
🟢  SPY PUTS 21% (day trade) scale in 
🟢 $SPY PUTS 17% (day trade) 
🟢🟡 $AAPL CALLS 10% (day trade)swinging some 
🔴 $APPS - iv crushed. Stock pumped with good er but iv ruined the play. Went light. Happens sometimes with er. 
(RECAP) 
Pretty good day overall had some decent gains while studied certain setups in certain sectors. See you all tomorrow! If you want to join me and other skilled analysts then make sure to click the link in my bio and accept our disclaimer! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:38:11 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : 7 Web 3.0 Stocks With Millionaire-Maker Potential https://www.stck.pro/news/AAPL/22720983 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:36:33 </td>
   <td style="text-align:left;"> $AAPL amazing… chip shortage and lack of phones and this sucker won’t stop. Thanks pelosi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:33:52 </td>
   <td style="text-align:left;"> $AAPL time for 180 EOW?!✅🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:33:47 </td>
   <td style="text-align:left;"> $AAPL 📜 SEC Form SD filed by Apple Inc.

https://quantisnow.com/insight/2383052?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:33:01 </td>
   <td style="text-align:left;"> $AAPL Form SD (specialized disclosure report) filed with the SEC 

https://newsfilter.io/a/1220b2a51ce9b2cd81cb903b07ad0146 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:30:36 </td>
   <td style="text-align:left;"> $AAPL gambling for tomorrow&amp;#39;s CPI numbers being better than expected.. appreciate my 180 weekly 100 call order not executing at .10.. I tried to get out but they wanted me in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:29:58 </td>
   <td style="text-align:left;"> $ZEV $NIO $FB $AAPL 

The talking heads are warning of a big market drop after the nice rally we’ve had. I beg to differ. We may have some choppy waters, but I think the bottom is in the rear view mirror.  Fear sentiment reached its peak a few weeks ago, imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:29:16 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $DIS if you made money today, like this post.  If you lost money today, reply to this post with your IQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:28:17 </td>
   <td style="text-align:left;"> 😂😂😂 this why I don’t pay $cmg $twlo  $dis  $spy $aapl .. people just say random shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:27:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $AAPL   
 
Building a long-term core holding in $DIS with first trade complete from $157.18 sold $160.41 after hours. You can see the trade alert in my ST feed. Nicely done Finom Group members! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:26:52 </td>
   <td style="text-align:left;"> $AAPL $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:26:06 </td>
   <td style="text-align:left;"> $AAPL Will beat previous ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:24:58 </td>
   <td style="text-align:left;"> $AAPL I like it, Picasso </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:24:04 </td>
   <td style="text-align:left;"> $PYPL can’t figure out if I like it or not. 

My only issue is long term growth. $SQ  has a better peer to peer payment system and $AAPL will probably monopolize on this as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:20:39 </td>
   <td style="text-align:left;"> $AAPL 

Apple will break YTD negative performance tomorrow so be prepared .. it’s going to be very great.

We are just 7 dollars away to 3 T while MSFT are trying to catch up as fast as possible but long way to go.

It’s going to be helluva of fun ride because this month we will see ATH will be broken more likely 190 to 195. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:20:12 </td>
   <td style="text-align:left;"> $AAPL would love to see new ATH this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:16:31 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:14:37 </td>
   <td style="text-align:left;"> $AAPL tomorrow about 9:40 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:13:34 </td>
   <td style="text-align:left;"> $AAPL AAPL formed a dragonfly doji candle on the daily, which means good things to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:13:02 </td>
   <td style="text-align:left;"> Data is the new oil but also a new tool of oppression!  
 
Slide is taken from Catherine D&amp;#39;Ignazio&amp;#39;s of MIT presentation (is not mine). 
 
$GOOGL, $AAPL,, $MSFT, $AMZN, $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:12:12 </td>
   <td style="text-align:left;"> $AAPL Price manipulation in the Premarket tomorrow should put apple# at $177.50 at the opening bell,  💋💋🙈Make China Great # again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:10:48 </td>
   <td style="text-align:left;"> $DIS I love stealing bears’ money, just ask $AAPL $MSFT and $AMZN bears!

Another successfully put short into ER, thanks for gambling! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:10:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $UVXY $AAPL 
 
Now that options are locked in, I regret to inform all Call holders, that tomorrow&amp;#39;s CPI will be the worst yet, given that oil alone went up 16% last month.  
 
Only thing that will outpace oil prices are the value of my puts at opening bell. F ALL YA&amp;#39;LL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:09:32 </td>
   <td style="text-align:left;"> $AAPL if not this week then it’s definitely hitting ATH next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:09:31 </td>
   <td style="text-align:left;"> $AAPL What a day🤣🤣🤣🤣✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:09:24 </td>
   <td style="text-align:left;"> $SPY so, I guess data must of leaked and is not &amp;quot;as&amp;quot; bad? 🤔👀
$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:08:52 </td>
   <td style="text-align:left;"> $PTON if anyone buys peloton, im sure the buyer will chose to disclose at their preferred time. Otherwise, business as usual to the public eye. $DIS $NKE $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:08:51 </td>
   <td style="text-align:left;"> $AAPL Bears are SHAKING in anger. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:08:36 </td>
   <td style="text-align:left;"> $AAPL I traded in my FB calls for AAPL calls, lets break that iH&amp;amp;S neckline </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:07:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:06:24 </td>
   <td style="text-align:left;"> $AAPL Let&amp;#39;s do this🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:06:24 </td>
   <td style="text-align:left;"> $AAPL I’ll take it! 🤤🤤🤑👍🏼🤙🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:05:07 </td>
   <td style="text-align:left;"> $PTON I&amp;#39;m never selling. Will not miss the pop when this it bought out by either $DIS $NKE $AMZN OR $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:04:53 </td>
   <td style="text-align:left;"> $AAPL 
CLOSE $176.28. 
+$1.45 +0.83% 
AH $177. 
NASDAQ +295.92 POINTS +2.08%. (BEAUTIFUL). 
————————————————————
We are going excellent, soon 🔜 $183. Again 
And then a GAP $196.  🍏🔜🆙🔝
————————————————————— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:04:02 </td>
   <td style="text-align:left;"> $KT Corp. Outperforms Market Expectations Increases Operating Profit 41.2%

https://m.stock.naver.com/domestic/stock/030200/news/view/008/0004706035

$AMZN $AAPL $MSFT latexab7047eb0e0712173c7d4a9b26516a0c$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:00:59 </td>
   <td style="text-align:left;"> $AAPL 

Shame on bears getting trapped! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:00:46 </td>
   <td style="text-align:left;"> Monthly $AAPL chart is not a bullish formation. We didn&amp;#39;t have previous candle wick retest and that could be about to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:00:27 </td>
   <td style="text-align:left;"> $AAPL wow that spike in the end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 05:00:22 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s with people posting EV news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:59:20 </td>
   <td style="text-align:left;"> $SPY bots trading and social skills are now greater than humans $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:56:35 </td>
   <td style="text-align:left;"> $AAPL have 100 feb 18th 180c ready to plow tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:56:29 </td>
   <td style="text-align:left;"> $AAPL https://finance.yahoo.com/news/microsoft-takes-swipe-at-apple-and-google-with-new-app-store-rules-203417146.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:56:12 </td>
   <td style="text-align:left;"> $AAPL violent fucking swings on my calls. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:56:07 </td>
   <td style="text-align:left;"> $AAPL wacky trades at end of session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:54:57 </td>
   <td style="text-align:left;"> Most Traded Contracts

$AAPL 11 February $177.50 Call
$XOM January 2023 $50 Call
$AAPL 11 February $180 Call
$XOM February $75 Call
$AMD 11 February $130 Call
$AAPL 11 February $175 Call
$AAPL 11 February $175 Put
$FB 11 February $230 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:54:56 </td>
   <td style="text-align:left;"> $SPY held nicely here, may be pinned into close given CPI Data. Notable weakness on $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:53:58 </td>
   <td style="text-align:left;"> More than 965k $AAPL option contracts traded so far, 67% call 33% put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:53:46 </td>
   <td style="text-align:left;"> $AAPL car news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:53:45 </td>
   <td style="text-align:left;"> $AAPL I wouldn’t be surprised if this hits new ATH this week. Seriously, if those numbers tomorrow are even slightly good, the market will rocket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:53:02 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/sV6a7F7yEXk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:52:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $VXX I’m holding far out of the money call debit spreads on SPY in case we breakout. As as well as far out of the money put debit spreads and puts in VXX. I’m short AAPL and QQQ for a short term pull back based on their options activity. Let’s ride. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:52:30 </td>
   <td style="text-align:left;"> $AAPL this thing all over place on Apple Car again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:52:24 </td>
   <td style="text-align:left;"> $AAPL This closes at 176.05 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:52:00 </td>
   <td style="text-align:left;"> $AAPL EV Apple News!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:51:17 </td>
   <td style="text-align:left;"> $AAPL VOLUME EXCELLENT &amp;gt;200K. Per Minutes. 
Go to $177. 🍏🔜🆙🔝🛎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:50:41 </td>
   <td style="text-align:left;"> $AAPL look at this rocket bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:49:26 </td>
   <td style="text-align:left;"> latex0bffa83bbcb991f6ace63b0f9e5640c4GOOG 
)A(   
$AMZN 
 
 is back.   
   
Have a great Green Day &amp;amp; Go SPY!     
   
💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰   
💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:46:06 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $557,867 call sweep traded with $165.0 strike expiring on 2022-03-18. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:45:20 </td>
   <td style="text-align:left;"> $AAPL primarily needs to focus on its CORE BUSINESS...You people who keep posting that Apple needs to move into all these other businesses are misguided. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:44:55 </td>
   <td style="text-align:left;"> $F buying this and $AAPL every chance I get. This will be $40+ in 3-4 years time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:44:19 </td>
   <td style="text-align:left;"> $AAPL realityOS 
 
https://www.benzinga.com/trading-ideas/long-ideas/22/02/25518217/what-is-realityos-and-what-does-it-mean-for-apple-investors 
BZ Pro: https://benzinga.grsm.io/gxjhpowx7zks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:44:17 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Top 3 Undervalued Tech Stocks https://www.stck.pro/news/AAPL/22716303 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:43:43 </td>
   <td style="text-align:left;"> $AAPL 
Correction $176 +BREAKOUT 🍏🔜🆙🔝🛎

NASDAQ go To 300 Points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:43:06 </td>
   <td style="text-align:left;"> $SPY $AAPL Supply chain collapsing... warehousing shortage... cpi... RUSSIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:42:59 </td>
   <td style="text-align:left;"> $AAPL The algos program controls the flow ,The CPI an the  CCP CRACK DOWN  will be a game changer.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:41:40 </td>
   <td style="text-align:left;"> $AAPL F me with that big red dick one more time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:41:30 </td>
   <td style="text-align:left;"> $AAPL 

Well I guess the shorts do not give up !!

That’s ok .. their thinking and way of making money is going to fail them.

This will make them choke harder! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:41:22 </td>
   <td style="text-align:left;"> $AAPL I want to troll this one bear so bad. But I know they already sad enough🤣🤷🏾‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:40:45 </td>
   <td style="text-align:left;"> $AAPL VOLUME &amp;gt;200K. Per Minutes.  

Total Today 49.435M. INTRADAY 
TODAY 51.07M🍏🔜🆙🔝🛎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:39:49 </td>
   <td style="text-align:left;"> $AAPL stop Fucking with me! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:39:47 </td>
   <td style="text-align:left;"> $SPY $AAPL Never made it back to HOD, interesting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:39:01 </td>
   <td style="text-align:left;"> $AAPL choke on my tandori chicken tikka masala bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:38:43 </td>
   <td style="text-align:left;"> $RIDE FINALLY!!!  LFG!!!    
 
Time for your &amp;quot;starter&amp;quot; position if not in yet imo!  :D  
 
Out of the ashes, Lordstown Motors arises to production!  
 
Foxconn who makes the IPhone for $aapl is pumping the partnership and all signs point to the 1st Full Size EV pickup truck in production being the Endurance!!!   
 
Get ready to see street racer versions since it&amp;#39;s the fastest one looks like. 
 
0-60 in 3.5 seconds for a full size pickup truck?!?   
 
$FSR $NKLA $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:38:26 </td>
   <td style="text-align:left;"> $AAPL $175+ BREAKOUT.  🍏🔜🆙🔝🛎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:37:37 </td>
   <td style="text-align:left;"> What if I told you you&amp;#39;ll be able to accept payment on $AAPL iPhone with the $SQ app </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:37:03 </td>
   <td style="text-align:left;"> $AAPL end of the red bear is to an end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:36:47 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:36:43 </td>
   <td style="text-align:left;"> $AAPL let’s close 176 to 176.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:36:04 </td>
   <td style="text-align:left;"> $AAPL WAKE UP!!Apple.
🍏🔜🆙🔝🛎
Go to $177. 
Apple Can Do It. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:35:35 </td>
   <td style="text-align:left;"> What Is ‘realityOS’ And What Does It Mean For $AAPL Investors? https://www.billionaireclubcollc.com/what-is-realityos-and-what-does-it-mean-for-apple-investors/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:34:28 </td>
   <td style="text-align:left;"> $AAPL 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:32:58 </td>
   <td style="text-align:left;"> $AAPL 

Apple Turn On Again. ….Very Shy Today. 
Beginning Up🍏🔜🆙🔝🛎 $177 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:32:56 </td>
   <td style="text-align:left;"> $AAPL 🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:32:56 </td>
   <td style="text-align:left;"> $AAPL bear trap suckasss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:31:58 </td>
   <td style="text-align:left;"> $AAPL bear trap was hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:31:57 </td>
   <td style="text-align:left;"> $AAPL The afternoon low looks like the bottom of a small correction. Hopefully we have the gas to get through 178 tomorrow. Still bullish longer term but failure there means larger correction coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:31:12 </td>
   <td style="text-align:left;"> $AAPL $QQQ clown world price action in Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:30:50 </td>
   <td style="text-align:left;"> $AAPL eating dips not dicks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:30:19 </td>
   <td style="text-align:left;"> $AAPL Too much money in here. Can&amp;#39;t even go up on a super green day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:30:18 </td>
   <td style="text-align:left;"> $AAPL Waiting for the ATH for a share price increase..Intra day trading sucks  Timmy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:29:23 </td>
   <td style="text-align:left;"> $AAPL I hedged with some March cheap puts here bc of the rejection but it could still breakout tomorrow so just a hedge for some overnight lottos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:28:10 </td>
   <td style="text-align:left;"> $AAPL What Is &amp;#39;realityOS&amp;#39; And What Does It Mean For Apple Investors? 

https://newsfilter.io/a/42d3ebb658b92fe8a0b7baad43b657fa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:27:46 </td>
   <td style="text-align:left;"> $HOFV Made good money here last year all my money is invested now in $AAPL and some call options in $ATOS. If I had fund available I would definitely invest some here. In my opinion this stock has a huge potential specially after Covid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:27:10 </td>
   <td style="text-align:left;"> $CHPT   
 
For Apple $AAPL Car, a Chargepoint buy makes more sense than Peloton 
  
Wed Feb 09 15:10:14 2022 EDT 
Apple’s biggest challenge putting a vehicle on the road may not be the design, probably isn’t the artificial intelligence, and might not be the software and manufacturing – but almost certainly is the most mundane challenge of all: the lack of charging points. 
Apple Cars need chargepoints, too 
In the US, Apple’s home turf and still its most important market, the  US Department of Energy  tells us there are just 111,000 public charging stations for electronic vehicles (EV), which is what the Apple Car is expected to be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:26:44 </td>
   <td style="text-align:left;"> $AAPL working on BNPL for Apple Pay $AFRM —Seeking Alpha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:26:15 </td>
   <td style="text-align:left;"> $CHPT $AAPL Very interesting point of view... https://www.computerworld.com/article/3649099/for-apple-car-a-chargepoint-buy-makes-more-sense-than-peloton.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:26:13 </td>
   <td style="text-align:left;"> $AAPL 📜 SEC Form SC 13G/A filed by Apple Inc. (Amendment)

https://quantisnow.com/insight/2381461?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:25:56 </td>
   <td style="text-align:left;"> $PLTR $ARKK $QQQ $TSLA $AAPL institutional investors never lose! They are holding $$$ billions of Palantir stock! They know this company will rule AI and data sciences for years to come! Positive free cash flow also is king 👑 in a rising interest rate environment! My price target is $32 by June 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:25:27 </td>
   <td style="text-align:left;"> $AAPL Form SC 13G/A (statement of acquisition of beneficial ownership by individuals) filed with the SEC 

https://newsfilter.io/a/2d0d8e568aac4eec22c9caceaa851f55 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:25:00 </td>
   <td style="text-align:left;"> $AMD this is going up in power hours make me think we might see $135 tomorrow . I bought calls 2/8 instead of puts. Fair warning, the market usually goes the opposite way of my plays so I would buy puts if I was anyone but me! $NVDA $AMZN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:23:03 </td>
   <td style="text-align:left;"> $AAPL yo $PTON not worth a dime. They’ll make Apple plummet. All for nothing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:22:13 </td>
   <td style="text-align:left;"> $AAPL great pullback happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:21:08 </td>
   <td style="text-align:left;"> $AAPL market hardly dipped and this is going for red today. Unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:20:09 </td>
   <td style="text-align:left;"> $AAPL I am in for long call once it drops to the 9 EMA of $173.9. $176 Call will pay huge. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:20:05 </td>
   <td style="text-align:left;"> $SPY $NFLX $MSFT $AAPL $TSLA inflation news tomorrow and dumping starting now .. tomorrow might be a big haircut day for tech sector 

You wait tomorrow to buy real dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:20:03 </td>
   <td style="text-align:left;"> $AAPL thanks for the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:19:49 </td>
   <td style="text-align:left;"> $AAPL correction ??, no correction needed , great products that&amp;#39;s what you cannot forget !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:19:37 </td>
   <td style="text-align:left;"> $AAPL a bear trap obviously! 

Get your attention !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:19:30 </td>
   <td style="text-align:left;"> $AAPL up by Yuuge in 1 mth and ppl buying after its up ... lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:18:59 </td>
   <td style="text-align:left;"> $AAPL shameful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:18:36 </td>
   <td style="text-align:left;"> $AAPL why are you selling , what could be so bad , lol, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:18:34 </td>
   <td style="text-align:left;"> $XELA will be over 1 dollar soon.  
Good news are coming. 
XELA loves people having 
$AAPL $AMZN $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:18:27 </td>
   <td style="text-align:left;"> $aapl new LOD wtf? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:18:22 </td>
   <td style="text-align:left;"> $AAPL lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:18:03 </td>
   <td style="text-align:left;"> $AAPL Aths... up much over last 3 years.. maybe time for correction and reload up somewhere around 140s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:17:47 </td>
   <td style="text-align:left;"> $AAPL cpi taking names tmrw morning.   1500 pt down day in dow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:17:28 </td>
   <td style="text-align:left;"> $SPY Retail bulls are scared becoz they know tomorrow might screw them big of they buy dip $AAPL $MSFT $FB 

Inflation data </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:17:25 </td>
   <td style="text-align:left;"> $AAPL painfully predictable and low 174 to high 173 of the market really takes a turn down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:17:23 </td>
   <td style="text-align:left;"> $AAPL timber </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:17:22 </td>
   <td style="text-align:left;"> $AAPL Latest 4 Hour chart to member&amp;#39;s at https://elliottwave-forecast.com/, showing the reaction off the Blue Box area. Blue Boxes have 85% chance to produce a bounce, we call them no enemy areas The Market always is a fight between buyers and sellers, knowing the areas where to enter is key. We are trading in 2022, which means computers play a role, and consequently, we present the Blue Boxes to members in each time frame. It is impossible to trade within the fight between buyers and sellers, much better the Blue Boxes. #elliottwave #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:16:46 </td>
   <td style="text-align:left;"> $AAPL Holding puts till close and tomorrow. Nice pullback I expect to see tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:16:20 </td>
   <td style="text-align:left;"> $AAPL power hour more like knife drop hour. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:16:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $AAPL $AMZN - not very responsible how CNBC is down playing the CPI number tomorrow. Interest rates are highest since 1982. Not expecting a crash but people are not aware how bad the risk is here. MM&amp;#39;s/big money selling now as retail is buying, so once again the small trader/investor is being taken advantage of. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:16:06 </td>
   <td style="text-align:left;"> $AAPL I don’t think we going too far down, still holding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:15:59 </td>
   <td style="text-align:left;"> $AAPL green.    To red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:15:49 </td>
   <td style="text-align:left;"> $AAPL The symbol is reacting off the Blue Box area presented to members late last month. Here is the 4 Hour chart to member&amp;#39;s at https://elliottwave-forecast.com/, showing the buying area. #elliottwave #trading $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:15:48 </td>
   <td style="text-align:left;"> $AAPL that’s what I thought, shit on power hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:15:45 </td>
   <td style="text-align:left;"> $SPY $AAPL Entire days gain will be wiped out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:15:32 </td>
   <td style="text-align:left;"> $spy You&amp;#39;re &amp;quot;bull&amp;quot; market doesn&amp;#39;t restart little $$$ bull until $aapl gives up the ghost. It&amp;#39;s simply just the way it is  =/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:14:50 </td>
   <td style="text-align:left;"> $AAPL I’m a buyer at 130 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:12:21 </td>
   <td style="text-align:left;"> $AAPL 179 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:12:21 </td>
   <td style="text-align:left;"> $AAPL near aths... seems expensive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:10:52 </td>
   <td style="text-align:left;"> $AAPL  Smart money is buying  FACEBOOK  $FB  and buying puts on  Candy Apples.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:10:48 </td>
   <td style="text-align:left;"> $AMD $AAPL $GOOG $NET Either the bond market has completely digested Fed hawkishness or its concerned about a policy mistake. 10&amp;#39;s-2&amp;#39;s spread did narrowed today. We&amp;#39;ll find out tomorrow  
 
https://www.youtube.com/watch?v=Eksf1EbpdX8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:10:27 </td>
   <td style="text-align:left;"> $SPY $AAPL RUG PULL INCOMING!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:09:27 </td>
   <td style="text-align:left;"> $AAPL $SPY Guess bulls ran outta money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:09:25 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $AMZN by end of today we turn red .. tomorrow is a big data for this month 

Inflation data will be highest 

We might see a big hair cut -4% to -5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:09:04 </td>
   <td style="text-align:left;"> $AMD $NVDA $SPY $AAPL 
CPI gang getting out at 3 pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:09:03 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:08:53 </td>
   <td style="text-align:left;"> $AAPL always falls the fastest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:08:47 </td>
   <td style="text-align:left;"> $AAPL $MSFT HOLY MOLY BATMAN!! SHES TANKING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:08:37 </td>
   <td style="text-align:left;"> $AAPL highly overpriced stock!! Will be 120-125 in July!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:08:11 </td>
   <td style="text-align:left;"> $AAPL leading the charge down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:07:56 </td>
   <td style="text-align:left;"> $AAPL Here comes the crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:07:25 </td>
   <td style="text-align:left;"> $AAPL ok so everybody expecting a drop. Let&amp;#39;s do the opposite. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:06:50 </td>
   <td style="text-align:left;"> $AAPL $TSLA Elon who&amp;#39;s your DADDY? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:06:38 </td>
   <td style="text-align:left;"> $AAPL inflation report gonna see market to all time lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:06:14 </td>
   <td style="text-align:left;"> $AAPL  $SPY  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:06:13 </td>
   <td style="text-align:left;"> $AAPL power hour sell off... yay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:03:48 </td>
   <td style="text-align:left;"> $AAPL The symbol finally making new highs within the proposed wave 5. Soon, a three waves pullback should start and buyers will be waiting. https://www.youtube.com/watch?v=r575fkQwqIY&amp;amp;t=39s. #elliottwave #trading $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:03:48 </td>
   <td style="text-align:left;"> $AAPL drop hasnt even begun to start.   Wait till nasdaq ends day flat.  Will be down 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:02:50 </td>
   <td style="text-align:left;"> $AAPL give me $150.   Greedy ass bulls abt to get pounded thurs/fri </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:01:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $GOOGL $AMZN  CPI data inflation will be super high according to all news 

Bonds will retreat high

Tech will fall tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:01:22 </td>
   <td style="text-align:left;"> $AAPL out $1.58 for loss so mad. 

Last 2 days market has not been nice to me 😂😂😂

Was working out and AAPL went to $176.15 and I didn’t sell now just dipped hard on me. Could’ve taken profit but didn’t see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:01:19 </td>
   <td style="text-align:left;"> $AAPL back to $150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:01:09 </td>
   <td style="text-align:left;"> $AAPL MARKET PULLBACK AS USUAL IN LAST HOUR. HOLD YOUR PUTS $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:00:53 </td>
   <td style="text-align:left;"> $AAPL 3:00 dump time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:00:53 </td>
   <td style="text-align:left;"> $AAPL worst inflation since 1982 and only getting worse rates going to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:00:43 </td>
   <td style="text-align:left;"> $AAPL this has been a relatively great day squandered and it drops back to where it’s been all morning yet again with even deeper theta decay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 04:00:11 </td>
   <td style="text-align:left;"> $AAPL CPI data going to be lovely tomorrow 830am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:57:45 </td>
   <td style="text-align:left;"> $SPY $NVDA $AAPL $TSLA lets discuss our honest thoughts &amp;amp; opinions. CPI rates going to pull the rug or pump the market even more? Why </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:54:56 </td>
   <td style="text-align:left;"> latex459d7039ea0644a507352b35c63df113UVXY - Wins worst ETF award 
$AAPL - Wins biggest Ponzi scheme award with record share buybacks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:54:04 </td>
   <td style="text-align:left;"> $SPY Dump started $AAPL $MSFT  inflation data tomorrow is huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:52:52 </td>
   <td style="text-align:left;"> $AAPL the theta burn on calls today is extraordinary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:52:31 </td>
   <td style="text-align:left;"> $BKKT If not BKKT, who is $AAPL going to announce it partnered w/ as - it needs to - here? https://www.google.com/amp/s/cointelegraph.com/news/upcoming-apple-iphone-feature-to-give-merchants-a-way-to-accept-crypto-payments/amp

$MA new they needed BKKT. 

Apple news after the close. This goes parabolic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:51:36 </td>
   <td style="text-align:left;"> $AAPL market beginning to drop and this is wasting no time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:51:33 </td>
   <td style="text-align:left;"> $AAPL patience folks .. they are clearing out a lot of accumulation orders ..

Massive market wide pump will come out soon to wipe out and kick out all the short orders .. MM will throw them out of windows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:50:06 </td>
   <td style="text-align:left;"> $AAPL I think the last hour of trading will be telling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:49:45 </td>
   <td style="text-align:left;"> $AAPL why the fuck? We are lagging the tech sector a lot today... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:49:04 </td>
   <td style="text-align:left;"> $VZIO coming up on 20D...through it and through 15.5 really gives a nice setup to the 50D  
 
($ROKU $SONO $AAPL) 
 
https://www.tradingview.com/x/KTscTvpk/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:47:55 </td>
   <td style="text-align:left;"> $AAPL difficult to see this closing above 176 when it can’t hold it let alone cross it for a 5 min candle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:47:54 </td>
   <td style="text-align:left;"> $AAPL Sheer manipulation.  NASDAQ is up 275 points.  Apple is up just a $ ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:45:55 </td>
   <td style="text-align:left;"> $AAPL 194 points vs 71 points.. Pumps only last when they outperform.. This is $fb apologizing for its recent behavior dragging the index. I told u all then, that the dip is a farce. Now i am telling you, this rip is a farce. Too risk off before a CPI day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:44:02 </td>
   <td style="text-align:left;"> $AAPL it’s time for $176.25 then $176.75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:42:37 </td>
   <td style="text-align:left;"> $AAPL bulls have tiny balls right now or what? Get over 176.05 little bitch made motherfuckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:42:21 </td>
   <td style="text-align:left;"> $AAPL all that consolidation and it still can’t hold over 176 even with the market continues to pump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:41:28 </td>
   <td style="text-align:left;"> $SQQQ is dying off slowly I predict $GOOGL hits $3000 by next Wednesday  $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:39:45 </td>
   <td style="text-align:left;"> $aapl wound up enough?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:38:21 </td>
   <td style="text-align:left;"> $AAPL why is $176.00 a difficult number to stick? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:37:37 </td>
   <td style="text-align:left;"> $BKKT $$AAPL Apple want to partner with BKKT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:37:22 </td>
   <td style="text-align:left;"> $AAPL lol  @ Dan niles who shorted the market 150+ points ago lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:36:06 </td>
   <td style="text-align:left;"> $SPY so I guess Trumpeters can get on their knees and thank the best President in history for the recent rally right? 😉
$QQQ $AAPL $TSLA $DWAC Someone had to clean the mess previous administration left 💩🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:35:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $VIX  
 
Daily &amp;#39;Trading&amp;#39; Reminders. Obvious to some, not so obvious to most. 
 
-------------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:33:48 </td>
   <td style="text-align:left;"> $AAPL Damn why is this so dead !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:32:24 </td>
   <td style="text-align:left;"> $AAPL Without the Premarket this ⅘  TURD would sink to the bottom,  This  is what manipulation looks like in real time..●,÷,// </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:32:20 </td>
   <td style="text-align:left;"> $AAPL get nhod pussies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:31:11 </td>
   <td style="text-align:left;"> $aapl has to test support once more it seems before attempting a breakout. Tomorrows CPI is the test. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:29:34 </td>
   <td style="text-align:left;"> $AAPL 

In a Few minutes!! TURN ON APPLE. 
SURE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:29:22 </td>
   <td style="text-align:left;"> $AAPL Everyone waiting on CPI data tmm and scared of market tanking … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:29:09 </td>
   <td style="text-align:left;"> $QQQ $SPX $vix now close to 20… cant believe cpi data is out tomorrow is vix at 20 lowest in past 3 weeks… is markets sensing cooling inflation… time will tell… dip buying ans swing trading is definitely working $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:28:16 </td>
   <td style="text-align:left;"> $AAPL last one lagging behind the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:26:31 </td>
   <td style="text-align:left;"> $AAPL to $193 on breakout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:24:49 </td>
   <td style="text-align:left;"> $AMD $FB $AAPL $BKKT $DCFC https://youtu.be/jQySZ9NyIWc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:22:18 </td>
   <td style="text-align:left;"> $TQQQ $63.03 NEXT. 

$AAPL $176 + BREAKOUT. LET’S GO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:18:33 </td>
   <td style="text-align:left;"> $AFRM 

Already placed to sell at market close, looking for 1200 per contract.

1150 if it drops.

Congrats to whomever followed the play.💰🤞🚀

I dont respond to dms.

$AAPL $FB $TSLA $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:18:04 </td>
   <td style="text-align:left;"> Analysis: Netflix, Apple, Disney Emerge Stronger From Oscar Nominations; AMC Not So Much $NFLX $AAPL $DIS $AMC $CNK https://www.benzinga.com/node/25497997#.YgQTUFnRfnQ.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:17:53 </td>
   <td style="text-align:left;"> $AAPL 
Anytime!! Apple 🍏 Pump Hard. 
Come On Apple. NASDAQ 265.20 POINTS 
+1.87%

$176 soon 🔜. + BREAKOUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:16:08 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-10 03:15:36 </td>
   <td style="text-align:left;"> $AAPL Kevin O&amp;amp;#8217;Leary Is Calling The Bottom In Meta Platforms Stock: &amp;amp;#8216;This Is Where You Want To Accumulate&amp;amp;#8217; https://t.co/qO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:35:05 </td>
   <td style="text-align:left;"> $TSLA  
https://www.teslarati.com/tesla-china-income-revenue-results-2021/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:33:39 </td>
   <td style="text-align:left;"> latex6090ab0b775422f127a3d03e11d8f178$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:26:35 </td>
   <td style="text-align:left;"> $TSLA I can only buy one share? Pass or </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:20:24 </td>
   <td style="text-align:left;"> $TSLA  where do you think tesla is at? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:20:09 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/j9yf7puaRhQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:18:50 </td>
   <td style="text-align:left;"> $TSLA $1100 EOW.🧞‍♂️Bears must die. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:18:11 </td>
   <td style="text-align:left;"> $TSLA  go Elon!!!

https://www.google.com/amp/s/news.yahoo.com/amphtml/biden-notes-tesla-countrys-largest-213326522.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:15:26 </td>
   <td style="text-align:left;"> $CAR 👈 cheap shares to borrow will. Get you rekt, see you @ $420.0 after ER $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:11:55 </td>
   <td style="text-align:left;"> $TSLA Biden pushes for Build Back Better in meeting with utility CEOs, notes Tesla EV … https://finance.yahoo.com/video/biden-pushes-build-back-better-211211079.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:08:34 </td>
   <td style="text-align:left;"> $AAPL $PTON $AAL $TSLA $SPY  
 
They pumped it up right before CPI. Awesome!... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:03:08 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:02:32 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=rDcFjTRudpo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:01:31 </td>
   <td style="text-align:left;"> $TSLA world&amp;#39;s best selling EV brand in 2021 with a 14.4% market share...lots of room for growth. 😍💎 🎈

https://www.tesmanian.com/blogs/tesmanian-blog/tesla-was-the-worlds-best-selling-ev-brand-in-2021-with-a-14-4-market-share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 09:00:35 </td>
   <td style="text-align:left;"> $TSLA 1 to 100 split.. come on Elon.. we need a good premarket troll news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:56:18 </td>
   <td style="text-align:left;"> $TSLA go north, young man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:55:00 </td>
   <td style="text-align:left;"> An Altman-Z score of 19.66 indicates that $TSLA is not in any danger for bankruptcy at the moment. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:54:17 </td>
   <td style="text-align:left;"> $TSLA is this a better stock than lucid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:53:46 </td>
   <td style="text-align:left;"> $TSLA is this better than lucid? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:53:44 </td>
   <td style="text-align:left;"> $TSLA @jccoo just got to leave this here so we know who we’re dealing with 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:53:44 </td>
   <td style="text-align:left;"> $TSLA Looks prime for a gap down as #kingdollar will surge tomorrow. ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:52:06 </td>
   <td style="text-align:left;"> $TSLA inflation should be good for stocks, I strongly believe that it will rise up because of that… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:51:49 </td>
   <td style="text-align:left;"> $TSLA Increased its income by over 100% in China for 2 consecutive years. 😍🎉💎

https://www.teslarati.com/tesla-china-income-revenue-results-2021/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:50:54 </td>
   <td style="text-align:left;"> $TSLA Very weak day, nasdaq up 2% and couldn&amp;#39;t even hold 1% if market takes CPI badly were going back under 900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:50:04 </td>
   <td style="text-align:left;"> $TSLA mooon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:46:19 </td>
   <td style="text-align:left;"> $TSLA check out CRDL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:45:24 </td>
   <td style="text-align:left;"> $btc.x  $eth.x   $coin   $TSLA  
 
https://twitter.com/BTCfuel/status/1491422785230745602 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:45:01 </td>
   <td style="text-align:left;"> $TSLA You have to ask the right question. What is holding the stock down? Find the answer and let us know! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:40:58 </td>
   <td style="text-align:left;"> $TSLA did I stutter? $1000 next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:40:32 </td>
   <td style="text-align:left;"> $TSLA Over 950 Bullish and under 890 is bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:39:00 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $NFLX  Removed some fluff from my follow list and looking to follow good accounts. Who out there should I be following? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:38:50 </td>
   <td style="text-align:left;"> $TSLA quick decode on the manipulation..

https://youtube.com/shorts/QactbVgT5bc?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:38:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA what time does the CPI data get released ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:32:32 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Technical Analysis Video: 
https://www.youtube.com/watch?v=ex2RxZ20qjA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:31:32 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $ARKK 

GO ELECTRIC GO BROKE... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:30:45 </td>
   <td style="text-align:left;"> $TSLA Inflation data. What investors want to see (Inflation peaking)  
 
https://www.marketwatch.com/story/will-thursdays-inflation-data-kill-the-stock-market-bounce-heres-what-investors-want-to-see-11644439333?reflink=mw_share_twitter  
 
“Inflation has to stop going up. Markets and the Fed have seen ‘hints’ of a peak in inflation pressures, yet that wasn’t reality,” said Tom Essaye, founder of Sevens Report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:30:17 </td>
   <td style="text-align:left;"> $SPY $AMZN $TSLA another gap up tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:30:16 </td>
   <td style="text-align:left;"> $TSLA if CPI is bulliish 1,000+, if bearish 910. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:28:18 </td>
   <td style="text-align:left;"> $TSLA cpi priced in
. 10% move tomorrow to the upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:21:53 </td>
   <td style="text-align:left;"> $TSLA 900 tomorrow with this market and CPI inflation number coming in. 
Get ready to be drilled on Friday bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:21:51 </td>
   <td style="text-align:left;"> $TSLA $930 🎉 next $940 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:21:12 </td>
   <td style="text-align:left;"> $TSLA when Semi? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:18:59 </td>
   <td style="text-align:left;"> $TSLA a lot of nervous Tesla Fanboys on this board. I want to see you guys get emotional. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:18:20 </td>
   <td style="text-align:left;"> $TSLA not happy with the price action considering the market and biden speaking out tesla. I aspect 950$ to initiate the bullish pattern to be back to 1000-1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:16:38 </td>
   <td style="text-align:left;"> $TSLA lol so many read tea leaves and think they kno the future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:14:55 </td>
   <td style="text-align:left;"> $TSLA today was a beautiful retail bull trap. These MMs wanted people to believe that somehow data was leaked so they pumped up the indices. After CPI data released premarket, MMs will dump leaving retail holding the bags. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:14:13 </td>
   <td style="text-align:left;"> EV $TSLA $VWAGY $BYDDY $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:13:59 </td>
   <td style="text-align:left;"> $TSLA Perfect a Little Red AH. No biggie, the Time is Near. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:13:48 </td>
   <td style="text-align:left;"> $TSLA Bougjt calls before close.. either top ramen for dinner.. or top ramen with hookers for the next couple weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:12:20 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:12:18 </td>
   <td style="text-align:left;"> $TSLA Elon fanboi #1 not happy with FSD update.  Trouble in paradise? https://twitter.com/wholemarsblog/status/1491254293412061186?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:09:57 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #6 ticker with sweep activity where institutions are trading options urgently with 21.6K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:08:31 </td>
   <td style="text-align:left;"> $TSLA piece of garbage let’s go $900 give me that $20k profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:08:06 </td>
   <td style="text-align:left;"> $TSLA
https://www.thestreet.com/investing/elon-musks-space-x-loses-dozens-of-satellites-in-solar-storm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:05:28 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s ashame how Tesla Fanboys are closet racists for supporting a company that engages in systemic racial discrimination.  It&amp;#39;s a sad day in America that people find this acceptable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:04:29 </td>
   <td style="text-align:left;"> $TSLA blah blah blah  , it&amp;#39;s been weak for a while, blame it on the CPI. It&amp;#39;s a coin toss at the moment imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:03:30 </td>
   <td style="text-align:left;"> $TSLA have to take that 939, otherwise…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:02:30 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Trade Analysis Video: 
https://www.youtube.com/watch?v=MA8DM5La-bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 08:02:00 </td>
   <td style="text-align:left;"> $TSLA
🤣🤣🤣🤣🤣https://www.thestreet.com/investing/elon-musks-space-x-loses-dozens-of-satellites-in-solar-storm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:58:45 </td>
   <td style="text-align:left;"> $TSLA 919.24 support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:56:28 </td>
   <td style="text-align:left;"> $tsla nothing moar 🐑 then da comment n block 🤡 bums.   Ummm.  TSLA is getting hit with a lawsuit about racism.  Bums bahhh so loud.     FOOKem.  They getting it anyway. 

❤️👑🌈🦄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:56:24 </td>
   <td style="text-align:left;"> $TSLA $860s by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:53:08 </td>
   <td style="text-align:left;"> $MNDT insider’s just buy 700,000 shares just before close???? 
 
$tsla $arkk $msft $nvda !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:52:48 </td>
   <td style="text-align:left;"> WoW 🤩 

Russell Westbrook will make $47,063,478 in the 2022/23 season. 
That’s $573,945 per #NBA in season game.

$AMD ↗️➕ $XLNX 📈

$AAPL $TSLA $BTC.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:52:44 </td>
   <td style="text-align:left;"> $TSLA bought my puts for the 25th. If Russia does anything it will be after the games are over. If they do the sanctions the US imposes could cause problems for our market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:49:25 </td>
   <td style="text-align:left;"> So now $tsla is racist too??    Good thing this stream isn’t real. Cuz eventually it will be racist to call bums bum 🐑 Jabronis!!   🍿.    This weekend it’s on!   Reaper is a live 🐕 +200.  

❤️👑🌈🦄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:49:25 </td>
   <td style="text-align:left;"> $TSLA we going to be true to our beta tomorrow Tesla?  LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:49:04 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr NEWSMAX just validated this post: https://stocktwits.com/GamePlayGuru/message/434929656 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:47:59 </td>
   <td style="text-align:left;"> $TSLA futures turning over night. Green to red haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:47:06 </td>
   <td style="text-align:left;"> $PLUG Power @bwahahaha article…about $gs…”Goldman Sachs predicts green hydrogen has the potential to give rise to a $US11 trillion addressable market globally for the utilities industry alone and supply up to 25 per cent of the world’s energy needs by 2050.” 
 
The $11 Trillion is only Utilities!!!  $tsla $arkk $bp wind farm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:44:58 </td>
   <td style="text-align:left;"> $TSLA I only have 177 1000 calls…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:44:43 </td>
   <td style="text-align:left;"> $TSLA look at the chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:43:29 </td>
   <td style="text-align:left;"> $TSLA We should have seen THE low that Fri. if can pop tomorrow..if not will bring the boats back around 😂 GL 🍀✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:42:47 </td>
   <td style="text-align:left;"> $TSLA do me a favor and look at the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:41:42 </td>
   <td style="text-align:left;"> $TSLA In case you missed it...https://www.msn.com/en-us/money/companies/tesla-s-revenue-in-china-increased-by-100-for-2nd-year-in-a-row/ar-AATFd2o?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:41:30 </td>
   <td style="text-align:left;"> $TSLA look at buffet he don&amp;#39;t have to give a fuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:40:14 </td>
   <td style="text-align:left;"> $TSLA 🐐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:40:13 </td>
   <td style="text-align:left;"> $TSLA bought my puts yesterday after seeing it struggle to break $925, 3,4 times. Todays action wasn’t impressive either. wouldn’t mind this opening under $930 tmrw &amp;amp; running back to $900. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:40:11 </td>
   <td style="text-align:left;"> $TSLA    How about $910 to $900 @BullClawedGorillaHorns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:36:57 </td>
   <td style="text-align:left;"> $TSLA - don’t fight the TSLA

3 days - $1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:33:34 </td>
   <td style="text-align:left;"> Solar storm knocks out 40 newly launched SpaceX satellites $tsla oopsie  https://www.reuters.com/lifestyle/science/solar-storm-disables-40-newly-launched-spacex-satellites-2022-02-09/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:32:44 </td>
   <td style="text-align:left;"> $TSLA have a news team there to fly David from NY bet he would help from $FUBO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:30:53 </td>
   <td style="text-align:left;"> $TSLA 985 calls for FEB 25th 🤘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:27:02 </td>
   <td style="text-align:left;"> $TSLA TSLA Stock Price Prediction and Analysis for Tomorrow February 10th
https://youtu.be/r_YRd2sM6iU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:25:33 </td>
   <td style="text-align:left;"> $TSLA just walk in to a meeting sit back like you Tony fucking Montana like you own everything and don&amp;#39;t take bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:22:42 </td>
   <td style="text-align:left;"> $TSLA could live off one divined pay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:21:22 </td>
   <td style="text-align:left;"> $TSLA 800 puts next friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:19:08 </td>
   <td style="text-align:left;"> $TSLA fuck if I was CEO I&amp;#39;d lay down to rules. Being that know or walk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:17:13 </td>
   <td style="text-align:left;"> $ATOM $AAPL $TSLA $NIO Atomera: A Sleeping Giant in the Semiconductor Industry
https://youtu.be/J5P9xJEUOhA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:17:06 </td>
   <td style="text-align:left;"> $TSLA puts are down more than 30-50% today mhmmm calls are flat as my ass 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:16:47 </td>
   <td style="text-align:left;"> $LCID $TSLA $AAPL my chase account 😎🤟🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:16:45 </td>
   <td style="text-align:left;"> $TSLA consolidation is about over...time to grip it and rip it for a BOMB above 1k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:16:01 </td>
   <td style="text-align:left;"> $TSLA 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:14:37 </td>
   <td style="text-align:left;"> $TSLA flat more than my ass calls and puts get fucked at once </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:11:31 </td>
   <td style="text-align:left;"> $TSLA I’d like to thank BMW for spending millions of dollars to advertise for tesla during the super bowl.  Any time people see an EV ad. Somehow tesla pops in their mind.  

https://www.teslarati.com/bmw-ix-super-bowl-ad-video-schwarzenegger/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:08:47 </td>
   <td style="text-align:left;"> $GGPI $TSLA $RBLX Check out this Ross Gerber Interview discussing Polestar as the best valued EV Stock at the current price &amp;amp; Tesla 4680, Tesla Bot, and FSD! As well as the future of Roblox in Gaming &amp;amp; The Metaverse! 🔥 

WATCH NOW: https://youtu.be/AVZQtOE2ndA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:07:32 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
7% inflation and $100/barrel oil 
 
and people still buying stonks? 
 
There are some confident motherfuckers out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:06:42 </td>
   <td style="text-align:left;"> $TSLA chop or drop tmr choose one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:03:37 </td>
   <td style="text-align:left;"> Update for the week on my small account challenge plays. Played $SHOP $TSLA $ROKU Friday and played $DIS $CHGG this week. Majority of these plays on this account are only 3 day trades every Friday with 0DTE but was confident in DIS and CHGG that I didn&amp;#39;t mind swinging a few contracts on both plays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:02:09 </td>
   <td style="text-align:left;"> $TSLA 

I know how we fix anemic volume !! No problem 😉 

🙏🏻🐉🦅👀 🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:01:09 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl https://www.youtube.com/watch?v=CI93IWCx9XQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 07:00:52 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-model-y-frightening-sales-growth-california/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:59:55 </td>
   <td style="text-align:left;"> $TSLA anybody else ever have these fantasies that you’ll wake up one morning and wallstreet will finally get it and Tesla will be up 40% one random day?? 

Sure would be nice to randomly wake up to $1,300+ 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:59:55 </td>
   <td style="text-align:left;"> $TSLA bears winning right now? Looks like there are a-lot of puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:58:30 </td>
   <td style="text-align:left;"> $QQQ $TSLA $SAVA 

Nice recap:

https://www.thestar.com/business/opinion/2021/03/13/better-policy-can-help-get-casino-tables-out-of-the-stock-market.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:58:25 </td>
   <td style="text-align:left;"> $TSLA extremely cheap at 190 pe ratio
Lowest PE since when 2018? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:56:41 </td>
   <td style="text-align:left;"> $TSLA can u please please break 947 tmw so my puts can get fucked? If not tank below 900 u shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:56:17 </td>
   <td style="text-align:left;"> $TSLA why only 1 percent up today wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:56:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ BTFD you know how it works. Dont you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:54:00 </td>
   <td style="text-align:left;"> $TSLA has a better Altman-Z score than 92% of its industry peers. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:53:40 </td>
   <td style="text-align:left;"> $ENPH $PLUG $TSLA $SEDG

https://apnews.com/article/climate-business-europe-berlin-diplomacy-addd2678113759fe4c81641ef9df1e8e

The energy transition is a clear soft power of Germany’s, and I will actively use it,” she said, referring to efforts by Europe’s biggest economy to phase out nuclear power this year, end coal use by the end of the decade and use only renewable energy by 2045. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:53:31 </td>
   <td style="text-align:left;"> $SPY $TSLA CPI….. PPI, TPI, GPI, doesn’t matter. Fucken pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:51:40 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #14 ticker with unusual activity from institutional traders with an average of 20% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:51:31 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $935.0 CALLS for Thursday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:51:09 </td>
   <td style="text-align:left;"> $TSLA $CMG $FB $TWTR $SPY 🔥💵🍾🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:47:15 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Transportation chief Pete Buttigieg credits Musk&amp;#39;s Tesla for helping make EVs &amp;#39;possible in America&amp;#39; https://www.stck.pro/news/TSLA/22722524 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:46:59 </td>
   <td style="text-align:left;"> What kind of scam Shit 😂😂 2019-2020 wtf CPI $spy $spx $tsla $djia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:46:56 </td>
   <td style="text-align:left;"> $TSLA market bounces and you remain a pile of shit, good job 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:45:30 </td>
   <td style="text-align:left;"> $TSLA anyone notice the difference today? Despite a massive volume of weekly call options with strike prices from 935 through 950, this had a difficult time continuing upward as in previous gamma squeezes.  I believe institutional option sellers are reducing the number of shares they purchase as a delta hedge. Therefore, it is much more difficult to manipulate the share price through weekly call options. The manipulation is done. Thank you, SEC! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:45:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $AAPL $TSLA  
 
Armed with a twitter degree in economics, I love seeing clueless degenerate retail talk about inflation. 
 
No doubt you will all make michael burry proud tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:44:40 </td>
   <td style="text-align:left;"> $DWAC $DWAC now tesla getting sued while saving the environment $TSLA 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:43:41 </td>
   <td style="text-align:left;"> $TSLA $GOOG $AMD $NVDA hoping for a dip tomorrow as I need to load up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:42:21 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/9uCdBj6R_AY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:40:42 </td>
   <td style="text-align:left;"> $TSLA $LABU nice closed, holding both  gap up preM Tomorrow 🚀🚀🚀🚀🚀🚀🚀🚀🚀😁👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:39:40 </td>
   <td style="text-align:left;"> $GOOGL question for all. Remember when $TSLA split, and within months went right back to where it was and then some... what do you think the odds / time frame for Google to do the same? I am thinking 5 years to 7 years, but I also think a massive pump will happen after the split.  My opinion, just looking for others opinions and insights based on such a large split. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:39:33 </td>
   <td style="text-align:left;"> $TSLA U.S. CPI report (Reuters) https://www.reuters.com/markets/europe/dollar-hits-one-month-high-yen-us-yields-rise-2022-02-09/   
 
CPI print may offer new indications about the pace of the Federal Reserve&amp;#39;s monetary tightening, and investors are bracing for higher-than expected numbers that would signal more aggressive interest rate hikes.That readout is expected to show a 0.5% month-over-month increase in January, and 7.3% for the year, according to economists polled by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:38:03 </td>
   <td style="text-align:left;"> $F - it&amp;#39;s been a little frustrating at times owning shares of $F lately, but I relate this time to when $AMD was second fiddle to $INTC back in 2018 and trading at really cheap multiples around $10 per share. Since then $AMD is second fiddle to no chip maker and trades around $130. People laughed at the analysts that were bullish on $AMD back then. 
 
$F right now is second fiddle to $TSLA and is trading at a really cheap multiple. I expect that in about the same time frame that $AMD went from $10 to $130 (3 years +/-) that $F will be trading at least $90 plus. This is obviously my opinion, but it is an opinion shared by many. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:36:47 </td>
   <td style="text-align:left;"> Hey Community, what&amp;#39;s you&amp;#39;re opinion on $TSLA now. Good or Bad closing Today. Will we touch $950 on the opening? Or will the Pre-market kill $TSLA again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:36:10 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/eHkpBhxUnug </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:34:19 </td>
   <td style="text-align:left;"> $TSLA Strong CPI data could boost Fed hike expectations, hurt bonds https://www.reuters.com/markets/asia/live-markets-strong-cpi-data-could-boost-fed-hike-expectations-hurt-bonds-2022-02-07/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:33:47 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $RBLX  
 
Tech about to regain some momo? 
 
https://www.youtube.com/watch?v=II6qoZtFsuU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:33:41 </td>
   <td style="text-align:left;"> $TSLA First time trading Tesla didn’t go so well this week. Let’s see how the rest of the week goes. Hoping for a nice pop to minimize my misfortune. Stick with what you know right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:33:22 </td>
   <td style="text-align:left;"> $TSLA thanks for not taking a dump at least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:33:22 </td>
   <td style="text-align:left;"> $TSLA I expect &amp;gt; 5-10% tomorrow on good CPI news... if lower than 10 all the market will be a sea of green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:32:53 </td>
   <td style="text-align:left;"> Looks like tomorrow we may drop a little CPI, but the bottom was put in 2 weeks ago. There may be some bumpy news forward but this year is an election year, I can’t see a scenario where they let it go into recession. People forget the stock market is political. I am now 90% invested as of Monday. Was buying the dips last two weeks.  GL everyone 

🚨 $AAPL  $TSLA $BTC.X $GOOG $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:28:15 </td>
   <td style="text-align:left;"> $TSLA my gut tells me it’s an iffy time to own this.   Teetering and doesn’t know where it wants to go.  Maybe tomorrow it’ll figure itself out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:27:18 </td>
   <td style="text-align:left;"> $TSLA send it to 1000 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:26:16 </td>
   <td style="text-align:left;"> $TSLA is my app broken or is this completely flat in the AH 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:24:53 </td>
   <td style="text-align:left;"> @FinancialTrades $TSLA currently trading at $938 possible bull run at open towards $957 might have a rejection around $947 but im not positive. If we go down at open to the gap fill on tsla as well watch for a bounce at $925 for a run up to $957. @everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:24:34 </td>
   <td style="text-align:left;"> $TSLA 

https://apple.news/AIS-HpjzcSTecOjtZy3nqyA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:23:16 </td>
   <td style="text-align:left;"> $TSLA 💵https://youtu.be/TYFyiiEwOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:22:16 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/alphatrades7/status/1491537532055605249?s=20&amp;amp;t=0oSdLhygOXbtYXxBV0xmeA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:22:00 </td>
   <td style="text-align:left;"> $AMD $AAPL $NET $TSLA 6 hikes priced in already! 
Sounds like peak hawkishness has already been priced into markets. If tech rallies off CPI tomorrow, I think green light until the next CPI on March 10th </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:20:10 </td>
   <td style="text-align:left;"> $SHOP $TSLA  inflation numbers come in hotter than expected..decent size dip coming tomorrow $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:20:08 </td>
   <td style="text-align:left;"> $TSLA $JOBY $PLTR Building these 3 positions slowly but steadily for next 5 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:17:03 </td>
   <td style="text-align:left;"> $TSLA All the investment is starting to really pay off...https://www.msn.com/en-us/money/news/tesla-s-model-y-is-taking-over-california-the-largest-auto-market-in-the-us/ar-AATEXQI?ocid=msedgntp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:16:59 </td>
   <td style="text-align:left;"> $GGPI $TSLA $LCID Check out this Ross Gerber Interview discussing Polestar as the best valued EV Stock at the current price &amp;amp; Tesla 4680, Tesla Bot, and FSD! As well as the future of Lucid Motors! 🔥 

WATCH NOW: https://youtu.be/AVZQtOE2ndA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:12:45 </td>
   <td style="text-align:left;"> $AMZN $TSLA how much does value of cpi should be tomorrow for this to change + or - 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:10:31 </td>
   <td style="text-align:left;"> $TSLA either way this is up bigly or down bigly tomorrow. 
No stagnation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:07:29 </td>
   <td style="text-align:left;"> $TSLA Two things can happen,

Major sell off, dropping this to $850 or even lower

Major pop, rising this to $1,000 then slows down.

Let’s hope it pops up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:06:08 </td>
   <td style="text-align:left;"> $TSLA  
Not a great news for you buddy Elon. 
 https://www.usatoday.com/story/tech/2022/02/09/elon-musk-starlink-satellites-geomagnetic-storm-destroys/6719409001/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:05:38 </td>
   <td style="text-align:left;"> $AAPL Per the last two, I think the negative re: the CPI is already priced in.  The market selling is exhausted for now IMO (premiums say so as well...) 
 
https://twitter.com/MeisaBonelli/status/1491532619342876678?s=20&amp;amp;t=brzot2pAlSlc1Qbru2oE-Q 
 
$NVDA $AMD $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:04:47 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

too many bulls... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:03:29 </td>
   <td style="text-align:left;"> $TSLA honestly ever since the tesla deal with hertz and Elon said something it’s never been the same again… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 06:00:49 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Options Analysis Video: 
https://www.youtube.com/watch?v=ed_yH3-BT6Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:58:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $AMZN  
 
Big shoutout to the retail bears. You clueless degenerate fuckwits make it all possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:58:28 </td>
   <td style="text-align:left;"> $TWTR $dwac $tsla IF Twitter misses and the ER is $fb like, The entire Libtard Tech Sector will be ERODING for the next 2 days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:55:22 </td>
   <td style="text-align:left;"> $TSLA if Tesla’s Er was after $FB  I think we would have been 20-30% up by now. After FB, it seems investors are turned bullish with slight positive Er </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:54:29 </td>
   <td style="text-align:left;"> $SPY any profit coming from calls is getting roll over into puts for the next few months 😬 pretty much using their money to cash in 😬😎
$QQQ $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:50:09 </td>
   <td style="text-align:left;"> $SOFI $TSLA  if we can avoid a rug pull tomorrow morning after CPI data is released… I’ll call bull run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:49:52 </td>
   <td style="text-align:left;"> $TSLA Musk elected: Election to the National Academy of Engineering is among the highest professional distinctions accorded to an engineer. Musk, Elon Reeve, founder, chief executive officer, and chief engineer, SpaceX, Hawthorne, Calif. For breakthroughs in the design, engineering, manufacturing, and operation of reusable launch vehicles and sustainable transportation and energy systems. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:48:39 </td>
   <td style="text-align:left;"> $TSLA $F $GM Downfall of Ford and GM just beginning.... 
 
https://www.barrons.com/articles/gm-ford-stock-price-downgrades-51644418714?mod=bol-social-fb&amp;amp;fbclid=IwAR0HYSVam0jL8yTd0gcKhANUqZIxJiXvKGor2YafzqGq5rrgT5sbjlHIzqU&amp;amp;tesla=y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:46:50 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #6 stock that institutions are trading over rolling 5 day window with 111.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:46:16 </td>
   <td style="text-align:left;"> $TSLA 1000 tomorroooooooooow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:44:48 </td>
   <td style="text-align:left;"> $TSLA  Rookie numbers. $1200 EOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:41:57 </td>
   <td style="text-align:left;"> Solid day, very bullish and Great follow through the entire. Solid hit rate. Main tickers today: $SPY 455c $AMD $MU All 300% + $CHWY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:39:38 </td>
   <td style="text-align:left;"> $TSLA 🧐🤤🤑👍🏼 
https://www.tesmanian.com/blogs/tesmanian-blog/tesla-was-the-worlds-best-selling-ev-brand-in-2021-with-a-14-4-market-share?fbclid=IwAR2TEjx62bTx71CXeVNJE24ODuX_vcrajH2hc40O-FgYLNTLI3DXK5sPKlg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:37:27 </td>
   <td style="text-align:left;"> $MULN  remember when we all bought $nio at $3 it jumped to $50 fast.   Missed the $tsla run when it was new.   Bottom line $23 stock for $2 at muln is worth the risk .  $f was under $5 not long ago look at it now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:36:46 </td>
   <td style="text-align:left;"> $TSLA Just your average yet temporary double top folks.. Definitely worth the long term exit strategy at this point. IMO —&amp;gt; HODL.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:35:28 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:32:53 </td>
   <td style="text-align:left;"> $TSLA over 950 looks ready to run. Watch it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:32:47 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=rDcFjTRudpo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:31:32 </td>
   <td style="text-align:left;"> $TSLA tesla bulls looking at $afrm $twlo  $dis $MQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:30:28 </td>
   <td style="text-align:left;"> $TSLA  
 
Disappointed. I couldn&amp;#39;t believe my pension account lost to market today (+$25,672.70 (1.67%) Day Change) as 40% of holding is $TSLA long positions, should be rebalanced. All other accounts still beat index. 
 
$TSLA has been forming wedge pattern for couple weeks, it should find direction within couple trading days. The chance of breakout is still higher than gap down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:29:16 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $DIS if you made money today, like this post.  If you lost money today, reply to this post with your IQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:27:27 </td>
   <td style="text-align:left;"> $TSLA  Huh..ok. round numbers , lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:27:06 </td>
   <td style="text-align:left;"> $TSLA  HODL! Wouldn&amp;#39;t sell a share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:26:58 </td>
   <td style="text-align:left;"> $TSLA all these earnings giving the market hope </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:26:41 </td>
   <td style="text-align:left;"> $TSLA $$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:26:11 </td>
   <td style="text-align:left;"> $GGPI $NIO $TSLA come on over check this company out :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:25:55 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:25:42 </td>
   <td style="text-align:left;"> $TSLA Everything running except this garbage. Looks like algos have moved on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:25:41 </td>
   <td style="text-align:left;"> $TSLA Will see $1000 again soon enough. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:24:45 </td>
   <td style="text-align:left;"> $TSLA 950? …🚀🚀🙏😜🤔🚀🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:23:19 </td>
   <td style="text-align:left;"> Calls Printing!  Futes Rippin: $DIS $SPY $PYPL $RIOT $TSLA  
Congratulations! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:22:51 </td>
   <td style="text-align:left;"> $TSLA  picture sums up bulls and bears today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:21:49 </td>
   <td style="text-align:left;"> $TSLA it is marking an accum/dist zone that serves to define if it continues lateral / bullish or returns to the zone of the previous range between 550 and 900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:20:36 </td>
   <td style="text-align:left;"> $TSLA going to float up all night.... still got to break through 950 wall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:19:15 </td>
   <td style="text-align:left;"> Want 140% to 225% Gains? 2 Growth Stocks to Buy, According to Wall Street $TSLA $SNAP https://bit.ly/3GEBrRt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:18:20 </td>
   <td style="text-align:left;"> $TSLA WOw!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:17:46 </td>
   <td style="text-align:left;"> $TSLA could get through 935 supply, 900 puts for this Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:16:46 </td>
   <td style="text-align:left;"> $TSLA Glad I took profits at $940 this morning.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:16:20 </td>
   <td style="text-align:left;"> $TSLA everything will go up except this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:15:10 </td>
   <td style="text-align:left;"> LOTTO LIST 1-DAY RESULTS:

🎉 $SPY 460c .45 &amp;amp;gt; 1.8 (400%)
🔮 $QQQ 370c .34 &amp;amp;gt; 1.78 (423%)
🤑 $TSLA 1000c 1.4 &amp;amp;gt; 3.6 (157%)
☢️ $NVDA 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:14:12 </td>
   <td style="text-align:left;"> $TSLA $CMG $FB $TWTR 🔥🥂💵🍾 

L
F
G </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:14:11 </td>
   <td style="text-align:left;"> Elon Musk Jet Tracker Creator Doesn&amp;#39;t Think It&amp;#39;s A Safety Concern: The Latest Developments  $TSLA $MSFT $AMZN $FB 

https://newsfilter.io/a/218afe9bce2fd2ad13089bab9ada23c2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:13:53 </td>
   <td style="text-align:left;"> $twlo nuts .. $dis moving … money leaves $amzn $tsla tomorrow and goes into dis 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:13:10 </td>
   <td style="text-align:left;"> $TSLA Doji candle close at resistance after several failed attempts to break $940. Expecting a reversal to the downside. PT1 $874 PT2 $850 gap fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:12:51 </td>
   <td style="text-align:left;"> Finished the day with 3 Wins &amp;amp; 3 Losses:

$FB - 230 calls at $2.15 went to $5.70 - Win 100%+

$TSLA - 900 puts at $7.35 went to $9.85 - Win

$SPY - 456 puts at $1.82 - Loss

$SPX - 4545 puts at $2.65 - Loss

$SPX - 4565 puts at $3.15 - $4.50 - Win

$SPX - 4570 puts at $2.15 - Loss

Today was a very annoying day. Choppy and no CPI fear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:12:51 </td>
   <td style="text-align:left;"> $MRK bigggg block buy close to the bell wowzers. After hours. See this reversing soon. Big buys. $tsla  $DIS $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:12:35 </td>
   <td style="text-align:left;"> $GHSI we are officially above both the 50 and 100 moving averages on the 4 hour chart. Many other Pennie’s are on the same track and IWM is performing well. $BNGO $OCGN $ZOM. Should see penny season arriving late this time around. First hike is coming next month, wouldn’t be surprised if small caps rally. Take into account small caps broke down all year long in 2021 and large caps and big tech have had the spotlight this whole time. What happens when interest rates rise and this large caps can’t keep beating record breaking earnings? Not to mention the supply chain issue and inflation. Don’t believe me? Everyone’s favorite $TSLA vividly emphasized their concern for near term production within their operations. Just what I see :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:08:29 </td>
   <td style="text-align:left;"> $LCID $OCGN $TSLA thank you $DIS so much!!!!!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:07:54 </td>
   <td style="text-align:left;"> $TSLA my condor is still printing, lol. Sideways week 2? Unless CPI data is better than expectations market could RIP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:07:13 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;US Inflation Preview:   FX Street  
https://www.fxstreet.com/analysis/us-inflation-preview-core-cpi-above-6-could-spark-next-dollar-rally-202202091308 Core CPI is projected to rise from 5.5% to 5.9%. If it surpasses the 6% level, investors would return to speculate on a double-dose (50 bps) QT-Fed-rate hike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:06:59 </td>
   <td style="text-align:left;"> $SNDL $SINT $TSLA 

Only on StockTwits will I have men tag me to let me know they approve of my profile photo. It just happened this morning.

Weirdos abound. 

Where da ladies at? 

Kidding, I’m married….happily. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:06:23 </td>
   <td style="text-align:left;"> $ASTR I know a company that can get those back up there ASAP.

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:06:20 </td>
   <td style="text-align:left;"> $SPCE $TSLA 

🔥VIRGIN GALACTIC WILL BE THE NEXT TESLA🔥

Just a few short years ago, Tesla jumped from just $40 a share to what would be over $4500 a share before the split price and is $900 a share after the spilt. Many people said they couldn’t and would be successful but look at them now.

This is the same case with Virgin Galactic. They are the first to Commercial Space Flight, Space Exploration, Supersonic High Speed Travel and more.

You can bet once Space Flights resume sometime around June or July, this stock would had already been in the $40’s-$60’s. Once Commercial Space Flights start you can expect this to be in the $100’s and you will never see anything under $100 again.

BUY, HOLD AND MAKE MORE MONEY HERE THAN YOU’VE EVER HAD IN YOUR LIFETIME!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:05:11 </td>
   <td style="text-align:left;"> $TSLA $SHOP these are definitely ripping hard af tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:04:07 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/elonmusk/status/1491505795724369925?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:03:46 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Technical Analysis Video: 
https://www.youtube.com/watch?v=ex2RxZ20qjA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:03:36 </td>
   <td style="text-align:left;"> $TSLA stock up but calls down day 2 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:03:03 </td>
   <td style="text-align:left;"> $TSLA small bet this gaps up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:03:02 </td>
   <td style="text-align:left;"> $TSLA Usually Nasdaq 100 future jumps large $TSLA can jump at least around 5%. a little disappointed. I expected it would clinch $960. 🤣🤣🤣🤣🤣🤣🤣$NVDA 👈👍👍👍👍💰💰💰💰💰💰💰💰🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:03:01 </td>
   <td style="text-align:left;"> $TSLA inflation data being released tomorrow , any predictions with how it will affect stock price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:02:16 </td>
   <td style="text-align:left;"> $TSLA in $850 puts expiring 2/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:01:04 </td>
   <td style="text-align:left;"> $SLI Shorts are in Big Trouble here! This is an excellent company with great management and an extra $100 Million form Koch. 
Rated 4 Buys with 5 Strong Buys. Time to Buy and Hold! 
https://seekingalpha.com/symbol/SLI/ratings/quant-ratings 
$F $tsla $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:00:47 </td>
   <td style="text-align:left;"> $TSLA US Inflation Preview:   FX Street  
https://www.fxstreet.com/analysis/us-inflation-preview-core-cpi-above-6-could-spark-next-dollar-rally-202202091308 Core CPI is projected to rise from 5.5% to 5.9%. If it surpasses the 6% level, investors would return to speculate on a double-dose (50 bps) QT-Fed-rate hike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:00:23 </td>
   <td style="text-align:left;"> $TSLA Groundhogs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 05:00:00 </td>
   <td style="text-align:left;"> $TSLA 5-10% tmr? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:59:20 </td>
   <td style="text-align:left;"> $SPY bots trading and social skills are now greater than humans $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:58:45 </td>
   <td style="text-align:left;"> $TSLA looks like we are in wrong bus today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:58:16 </td>
   <td style="text-align:left;"> $TSLA Nazzy up2% and tsla dragging ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:58:00 </td>
   <td style="text-align:left;"> $TSLA right on 930 support lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:57:35 </td>
   <td style="text-align:left;"> $TSLA Closed my put credit spreads and short puts. Now lurking, waiting for CPI numbers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:56:55 </td>
   <td style="text-align:left;"> $TSLA looks like smart money selling into the rally.  Volume going up, price pinned. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:56:39 </td>
   <td style="text-align:left;"> $ATER 

2M volume PASSED!!!!!💎💎💎💎

$GME, $BBIG, $TSLA, $PROG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:56:33 </td>
   <td style="text-align:left;"> $TSLA tomorrow red market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:55:35 </td>
   <td style="text-align:left;"> $TSLA ouch that rejection at 935 hurts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:55:16 </td>
   <td style="text-align:left;"> $TSLA  breaking key resistance level, tomorrow we are heading to $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:54:29 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:54:06 </td>
   <td style="text-align:left;"> $TSLA I like to sit in my vehicles butt naked should I get white seats? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:53:46 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:53:37 </td>
   <td style="text-align:left;"> $TSLA $1200 a month ago ouch it hurts to see this under $1000 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:53:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA

Did inflation just go away?... No, I didn’t think so.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:53:09 </td>
   <td style="text-align:left;"> $TSLA can we get a $942 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:52:59 </td>
   <td style="text-align:left;"> NEWS FLASH 2.9.22 just in ... Two FORD MOTOR COMPANY plants in Windsor, Ontario ... huge plants as well as Chysler plants have shut down due to truckers blocking the Windsor / Detroit Ambassador  Bridge which is also lending itself tl closures in Michigan, USA plants ... such bs the automotive industry share price rally is today thanks to Fraud St and cronies. Rest assured severe automotive stock crash incoming re no chips, inflation, socioeconomic concerns et al which most negatively will effect $f $gm $TM $tsla $stla and more re Honda, Hyundai, et al. Thank dog that I am here to help 🐻❤ Enjoy the Armageddon Depression ☠ ... FORD incoming re due diligence sub 14, fact us Morgan Stanley calling 12 to 13 ✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:52:51 </td>
   <td style="text-align:left;"> $TSLA close @940? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:52:00 </td>
   <td style="text-align:left;"> $TSLA has an Altman-Z score of 19.66, meaning it is financially healthy with little risk of bankruptcy. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:51:25 </td>
   <td style="text-align:left;"> $TSLA Musk we need a tweet!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:51:12 </td>
   <td style="text-align:left;"> $RIDE LFG!!!    Over 60,000 shares now.  I BELIEVE IN LORDSTOWN MOTORS AND FOXCONN PARTNERSHIP!!!  :D   
 
Join us with a starter if in $NKLA $FSR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:50:58 </td>
   <td style="text-align:left;"> $TSLA Tommorrow, THur 02-10 Inflation @ 8:30 AM ET Pre Bell 
 
7% expected for the year! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:50:51 </td>
   <td style="text-align:left;"> $AUPH $SPY  $QQQ  $TSLA ... CPI.... please be a dud for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:50:28 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/QVscYbY0ffQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:50:02 </td>
   <td style="text-align:left;"> $TSLA low volume, believe it at least test 940 again tomorrow. +10 overall today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:49:51 </td>
   <td style="text-align:left;"> $TSLA Todays rally-&amp;gt;  Global Equities Research analyst Trip Chowdhry weighed in on Tesla (NASDAQ: TSLA) after his latest round of factory checks, done on February 8th. Chowdhry noted production, shipping, and delivery momentum is &amp;quot;extremely solid&amp;quot; and said delivery activity in 1Q2022 is much stronger than 4Q&amp;#39;2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:49:15 </td>
   <td style="text-align:left;"> $TSLA Damp fuck socket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:48:55 </td>
   <td style="text-align:left;"> $TSLA inverted head in me asshole. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:47:58 </td>
   <td style="text-align:left;"> $TSLA it was $1200 a month ago what happened elon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:47:34 </td>
   <td style="text-align:left;"> $TSLA seems like that last drop was stop loss raid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:47:30 </td>
   <td style="text-align:left;"> $TSLA should trade @$1100 , not $900. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:45:57 </td>
   <td style="text-align:left;"> Top Bullish Flow Today : 

$TSLA $AMD $DWAC $NVDA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:45:29 </td>
   <td style="text-align:left;"> $TSLA wow. Really having problem getting to 950 , but watch out when it does. 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:45:27 </td>
   <td style="text-align:left;"> Unusual Option Alert on $TSLA $2,235,600 call block traded with $900.0 strike expiring on 2024-01-19. Via: https://www.stockgrid.io/optionsflowcumulativestats/TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:45:21 </td>
   <td style="text-align:left;"> $TSLA areb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:44:50 </td>
   <td style="text-align:left;"> $TSLA $1000 calls will prob get burned lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:44:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

Take your gamble folks, tomorrow’s a coin toss!! 🪙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:43:39 </td>
   <td style="text-align:left;"> $TSLA Elon tweeted bad news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:42:25 </td>
   <td style="text-align:left;"> $TSLA using the last swing high and low on my chart, FIB 38.2% resistance at 950. So far this week Monday and today tested near 950 and failed. It is consolidating for a move higher here soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:42:18 </td>
   <td style="text-align:left;"> $TSLA one more leg up ‘ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:42:08 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/z9nkzaOPP6g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:42:02 </td>
   <td style="text-align:left;"> $TSLA Watch out if day-trading!! Thursday Pre is CPI Inflation- ERstaimated 7% annualized </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:41:54 </td>
   <td style="text-align:left;"> $TSLA oh wow what a rug pull, glad i wasn&amp;#39;t greedy and took profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:40:49 </td>
   <td style="text-align:left;"> $SPY 830 tomorrow watch your profits. Take some off the table can always get back in if number is low. But if it is high look out below. $FB $MSFT $TSLA GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:40:39 </td>
   <td style="text-align:left;"> $TSLA The entire market is doing phenomenal and Tesla is only up a little over one percent. GTFO if you are smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:40:36 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:40:00 </td>
   <td style="text-align:left;"> $TSLA why Tsla is sooo underperformed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:39:55 </td>
   <td style="text-align:left;"> $TSLA big money getting out of late lucid puts…🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:39:53 </td>
   <td style="text-align:left;"> $TSLA todays chart looks weird compared to the others </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:39:18 </td>
   <td style="text-align:left;"> $TSLA 1000$ eow mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:38:43 </td>
   <td style="text-align:left;"> $RIDE FINALLY!!!  LFG!!!    
 
Time for your &amp;quot;starter&amp;quot; position if not in yet imo!  :D  
 
Out of the ashes, Lordstown Motors arises to production!  
 
Foxconn who makes the IPhone for $aapl is pumping the partnership and all signs point to the 1st Full Size EV pickup truck in production being the Endurance!!!   
 
Get ready to see street racer versions since it&amp;#39;s the fastest one looks like. 
 
0-60 in 3.5 seconds for a full size pickup truck?!?   
 
$FSR $NKLA $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:38:40 </td>
   <td style="text-align:left;"> $SHOP $TSLA criss cross resistance becomes support inverse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:38:36 </td>
   <td style="text-align:left;"> $TSLA tomorrow might be the day that we actually might break 947🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:38:27 </td>
   <td style="text-align:left;"> $TSLA break that $935 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:37:33 </td>
   <td style="text-align:left;"> $TSLA fk i sold my calls at 929 are u kidding me now it will close 950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:37:22 </td>
   <td style="text-align:left;"> $TSLA  $950 incoming 🤑🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:36:47 </td>
   <td style="text-align:left;"> $TSLA someone just traded 50,000 at 3:34 - $934.70 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:36:46 </td>
   <td style="text-align:left;"> $TSLA daily look pretty bull to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:36:44 </td>
   <td style="text-align:left;"> $TSLA i expect tesla to carry market tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:35:59 </td>
   <td style="text-align:left;"> $TSLA Can we not be insulting Bear v. Bull for a minuet, and actually discuss the chances of this recovering to +$1000 by EOD tomorrow, or EOW? 
 
This platform use to be worth something, but now its only a huge argument between bears/bulls and childish rants. Lets actually discuss what $TSLA is expected to do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:35:49 </td>
   <td style="text-align:left;"> $TSLA weak! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:34:33 </td>
   <td style="text-align:left;"> $TSLA eod moving now with the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:34:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:33:43 </td>
   <td style="text-align:left;"> $TSLA 

I’m surprised they didn’t drop it back to low 900s!! 

Tesla Stock now is underperforming NASDAQ HUGELY! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:33:12 </td>
   <td style="text-align:left;"> $TSLA 

😂 😂 😆 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:32:20 </td>
   <td style="text-align:left;"> $QQQ final call forPalantir under 14$ $TSLA $TLRY $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:32:03 </td>
   <td style="text-align:left;"> $TSLA Biden finally acknowledging TSLA as the nation’s largest EV producer will be the beginning of the rise to $1500. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:32:00 </td>
   <td style="text-align:left;"> $TSLA $QQQ 

you can thank aunt Cathy for buying TSLA last week, so many stocks recovered and then you have TSLA which sitting in 900-945 range for 2 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:31:56 </td>
   <td style="text-align:left;"> $KAVL $Tsla $fb $snap this is gonna shoot up soon get in 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:31:55 </td>
   <td style="text-align:left;"> $TSLA LETS GO TSLA RUN LIKE BKKT!!!!!!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:31:00 </td>
   <td style="text-align:left;"> $TSLA LETS GOOOOO RUN LIKE BKKT!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:30:43 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-09 Trade Analysis Video: 
https://www.youtube.com/watch?v=MA8DM5La-bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:30:40 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s GO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:30:32 </td>
   <td style="text-align:left;"> $TSLA push </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:30:26 </td>
   <td style="text-align:left;"> $TSLA needs over 936 baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:29:38 </td>
   <td style="text-align:left;"> $TSLA looks like hedgies buying into the close today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:29:34 </td>
   <td style="text-align:left;"> $TSLA weak like a fanboy... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:29:29 </td>
   <td style="text-align:left;"> $TSLA Teslas are selling like hot cakes in China https://www.teslarati.com/tesla-china-income-revenue-results-2021/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:29:19 </td>
   <td style="text-align:left;"> $TSLA over 50k volume on 950 and 1000 calls mhmm…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-10 04:28:56 </td>
   <td style="text-align:left;"> $TSLA even with Jonas upgrade this thing can’t move up. The cult has left the building. </td>
  </tr>
</tbody>
</table></div>

---
