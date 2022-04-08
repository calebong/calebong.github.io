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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Apr-2022-.pdf)

[View the historical Economic Forecasts](https://github.com/calebong/Client-Documents/tree/main/Monthly%20Market%20Outlook)


<img src="images/ghpEconPlotMid.png?raw=true"/>
<img src="images/ghpEconPlotLower.png?raw=true"/>

---

### Currency Forecasts

#### Autoregressive modelling to forecast trends of major currency pairs.

[Introductory Document for Clients](/pdf/Introduction-To-PromiseLand-s-Currency-Forecasts.pdf)

[View the latest Currency Forecasts](/Latest-Currency-Forecasts.html)


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



Last Updated: 2022-04-08 09:27:09 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/exports-yoy </td>
   <td style="text-align:left;"> 2022-04-08 09:19:00 </td>
   <td style="text-align:left;"> Philippines Export Growth at 6-Month High </td>
   <td style="text-align:left;"> Exports from the Philippines rose by 15.0% yoy to USD 6.16 billion in February 2022, after a 8.9% gain the previous month. This was the twelfth straight month of growth in overseas sales and the fastest pace since August, amid solid global demand and despite mounting geopolitical risks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/balance-of-trade </td>
   <td style="text-align:left;"> 2022-04-08 09:16:00 </td>
   <td style="text-align:left;"> Philippines Trade Gap Widens </td>
   <td style="text-align:left;"> The Philippines' trade deficit increased to USD 3.53 billion in February 2022 from USD 2.71 billion in the same month a year earlier, as exports grew by 15.0  percent year-on-year to USD 6.16 billion while imports expanded 20.1 percent to  USD 9.69 billion. Considering the first two month of the year,  the trade gap widened to USD 8.23 billion from USD 5.59 billion in the corresponding period of 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 08:17:13 </td>
   <td style="text-align:left;"> US Futures Steady After Thursday’s Comeback </td>
   <td style="text-align:left;"> US stock futures were steady in Asian trade on Friday after the major averages staged a late-day comeback in the regular session, as investors continued to contemplate the Federal Reserve’s next policy moves. Dow and S&amp;P 500 futures rose slightly by 0.1%, while Nasdaq 100 futures edged up 0.2%. In regular trading on Thursday, the Dow rose 0.25%, the S&amp;P 500 gained 0.42% and the Nasdaq Composite ticked up 0.06%, with all three indexes turning positive after two straight days of losses. The rebound came as investors took advantage of lower valuations, priced in a more hawkish Fed stance and shrugged off fresh sanctions on Russia. Healthcare and consumer defensive stocks led the advance as investors continued to bet on companies with stable earnings and dividends. Energy firms also gained as geopolitical uncertainties buoyed prices. Elsewhere, HP Inc shares outperformed, rising 14.75% after Warren Buffett’s firm disclosed a stake in the tech hardware company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-08/new-zealand-households-are-spending-less-as-cost-of-living-rises?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 08:06:50 </td>
   <td style="text-align:left;"> New Zealand Households Are Spending Less as Cost of Living Rises </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                                                                                                                                   , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                        , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                                                                      , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                                                                                                                            , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                                                                                                                                      , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                                                                                                                                      , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                                                                                                                                   , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                                                                                                                         , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                                                                                                                                  , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                                                                                                                                  , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                                                                                                                                  , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                                                                                                                               , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                                                                                                                           , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                                                                                                                               , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                                                                                                                         , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                                                                                                                                 , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                                                                                                                                  , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                                                                                                                                       , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                                                                                                                                   , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                                                                                                                                  , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                                                                                                                                      , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                                                                                                                                      , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                                                                                                                              , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                                                                                                                                  , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                                                                                                                                       , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                                                                                                                            , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                                                                                                                                     , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                                                                                                                            , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                                                                                                                                  , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                                                                                                                                    , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                                                                                                                                      , Pedestrians walk past cafes and restaurants in Auckland, New Zealand.                                                                                                                                                                                                                                                                             , Sherry Zhang                                                                                                                                                                                                                                                                                                                                      , New Zealanders are starting to spend less in response to rising fuel prices and other living costs, according to a survey of Westpac customers.                                                                                                                                                                                                   , Surging inflation is the biggest financial concern for consumers ahead of the impact of Covid-19 and the war in Ukraine, Westpac said in a statement released Friday in Wellington. The survey found that 44% of people are already spending less on petrol, 43% are cutting back on takeaways and dining out, and 41% have reduced grocery costs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/current-account </td>
   <td style="text-align:left;"> 2022-04-08 08:04:20 </td>
   <td style="text-align:left;"> Japan Current Account Surplus Drops Less than Expected </td>
   <td style="text-align:left;"> Japan's current account surplus decreased to JPY 1,648.3 billion in February 2022 from JPY 2,866.0 billion in the same month of the previous year and compared with market consensus of a surplus of JPY 1,436.8 billion. The surplus of primary income fell  to JPY 2,274.5 billion from JPY 2,553.0 billion a year earlier. At the same time, the gap of services account widened to  JPY 203.5 billion from JPY 0.432 billion and that of  secondary income increased to JPY 245.9 billion from JPY 166.4 billion in the previous year. Meanwhile, the shortfall of goods account narrowed to JPY 176.8 billion from JPY 522.6 billion a year earlier, with exports growing by 19.8 percent while imports jumped 34.2 percent on the back of soaring prices of commodities and raw materials. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-08/u-k-joining-salaries-rise-at-fastest-rate-since-at-least-1997?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 08:01:00 </td>
   <td style="text-align:left;"> U.K. Joining Salaries Rise at Fastest Rate Since at Least 1997 </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                           , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                    , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                              , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                              , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                           , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                 , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                          , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                          , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                          , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                       , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                   , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                       , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                 , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                         , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                          , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                               , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                           , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                          , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                              , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                              , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                      , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                          , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                               , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                    , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                             , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                    , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                          , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                            , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                              , Commuters cross London Bridge in the City of London.                                                                                                                                                                                      , Andrew Atkinson                                                                                                                                                                                                                           , U.K. companies are raising starting salaries at the fastest pace on record as worsening labor shortages hand workers unprecedented bargaining power.                                                                                      , In a survey published Friday, the Recruitment &amp; Employment Confederation and consultancy KPMG said the average salary awarded to new permanent joiners climbed more in March than at any time since polling began in October 1997. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/dhl-jet-skids-off-runway-breaks-in-two-after-emergency-landing?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 07:56:57 </td>
   <td style="text-align:left;"> DHL Jet Skids Off Runway, Breaks in Two After Emergency Landing </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                           , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                    , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                              , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                              , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                           , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                 , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                          , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                          , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                          , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                       , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                   , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                       , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                 , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                         , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                          , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                               , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                           , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                          , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                              , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                              , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                      , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                          , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                               , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                    , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                             , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                    , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                          , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                            , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                              , A DHL cargo plane after emergency landing at the Juan Santa Maria airport in Alajuela, Costa Rica, on April 7.                                                                                                                            , Photographer: Ezequiel Becerra/AFP/Getty Images                                                                                                                                                                                           , Angus Whitley                                                                                                                                                                                                                             , A Boeing Co. 757 cargo jet operated by DHL broke in two after skidding off the runway at Juan Santamaria International Airport in Costa Rica, according to Airlive.                                                                       , The crew reported hydraulic problems with the 22-year-old aircraft after takeoff and made an emergency landing, Airlive said. The two pilots escaped without serious injury, according to the report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/current-account </td>
   <td style="text-align:left;"> 2022-04-08 07:49:02 </td>
   <td style="text-align:left;"> South Korea Current Account Surplus Narrows </td>
   <td style="text-align:left;"> South Korea’s current account surplus posted at $6.42 billion in February 2022, marking the 22nd straight month of surplus but narrowing from the same month last year when the country logged $8.06 billion in surplus as  soaring oil prices boosted import bill. The goods balance logged a surplus of $4.27 billion in February, smaller than a surplus of $5.86 billion a year earlier. Exports, which account for half of the South Korean economy, grew 19.1% on-year to $53.87 billion, while imports increased 25.9% to $49.6 billion. The service account, which includes outlays by South Koreans on overseas trips, logged a surplus of $570 million in February, compared with a surplus of $180 million a year earlier. The primary income account, which tracks wages of foreign workers and dividend payments overseas, logged a surplus of $1.71 billion in the month, down from $2.29 billion the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/oil-heads-for-second-weekly-loss-on-spr-sales-virus-and-fed?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 07:38:57 </td>
   <td style="text-align:left;"> Oil Sheds Bulk of Invasion-Driven Gains on SPR Sales, Virus, Fed </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                           , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                    , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                              , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                              , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                           , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                 , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                          , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                          , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                          , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                       , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                   , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                       , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                 , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                         , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                          , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                               , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                           , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                          , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                              , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                              , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                      , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                          , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                               , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                    , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                             , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                    , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                          , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                            , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                              , Jake Lloyd-Smith                                                                                                                                                                                                                          , Oil headed for a back-to-back weekly retreat on plans for massive stockpile releases, a demand-sapping virus outbreak in top importer China and a hawkish turn from the U.S. Federal Reserve.                                             , West Texas Intermediate traded below $97 a barrel, with prices almost 3% lower this week. The recent drop means the U.S. benchmark has now lost the bulk of the gains seen since Russia’s invasion of Ukraine began in late February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/04/07/ukraine-parliament-member-bucha-images-oleksandr-merezhko-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-08 07:37:19 </td>
   <td style="text-align:left;"> Video: Ukrainian Parliament member shares horrific images of Bucha devastation - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/peru/interest-rate </td>
   <td style="text-align:left;"> 2022-04-08 07:37:03 </td>
   <td style="text-align:left;"> Peru Lifts Key Rate to 4.5% After Inflation Riots </td>
   <td style="text-align:left;"> Peru’s central bank decided to raise the policy rate for a ninth straight month by 50 basis points to 4.5% on April 7, in line with expectations as it seeks to curb soaring inflation that led to mass protests, riots and a state of emergency in recent days. Peru’s annual inflation rose 6.82% in March, the highest in more than two decades, driven by rising global fuel and food prices amid the conflict between Russia and Ukraine. The bank projects that inflation would return to its target band between the second and third quarters of next year, a slight shift from last month’s forecast for inflation to be back within range by the first half of 2023. “The board is especially attentive to new information regarding inflation and its determinants, including the evolution of inflation expectations and activity to consider further changes in the monetary policy stance that guarantee the return of inflation to the target range in the projected horizon,” the bank said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61019270?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-08 07:29:45 </td>
   <td style="text-align:left;"> Firms struggle amid Sri Lanka's economic crisis </td>
   <td style="text-align:left;"> It is a daily struggle for Ranjith Koralage, the boss of a Sri Lankan clothing manufacturer, to find enough diesel to run his company's machines and steam rollers.                                                                                                                                                , The chief of Kolonna Manufacturing, which is based in Sri Lanka's central province, has been running from station to station looking for 400 litres of fuel for the generator - just enough for one day.                                                                                                           , With long power outages, interruptions have become the order of the day in factories across Sri Lanka. Thankfully, a generator brings power back up in some factories. But the fix is temporary with limited fuel.                                                                                                 , Mr Koralage told the BBC: "Today we survived somehow, but I don't know about tomorrow."                                                                                                                                                                                                                            , His export unit makes knitted garments for Victoria's Secret, Puma and Levi's, and is among dozens of clothing factories struggling to meet production targets.                                                                                                                                                    , Garments are the second largest foreign exchange earner for the Sri Lankan economy. The sector had just recovered from the pandemic, with export earnings increasing by 22.1% to $514m (£393m) in January 2022 compared with a year ago.                                                                           , Kolonna's order book is full for the next three to six months. But now disruptions are adding to existing worries around losing business to rivals in Indonesia, Bangladesh and Vietnam.                                                                                                                           , "If [the] government doesn't provide fuel we have to stop production, that affects customers' deliveries. Our clients are already asking us daily if we will be able to complete the orders in time or not," Mr Koralage says.                                                                                     , Sri Lanka is facing its worst financial crisis in decades, with foreign exchange reserves shrinking by more than 16% to $1.93bn in March, central bank data showed on Thursday.                                                                                                                                    , Kolonna Manufacturing is a prime example of the model of economic development that Sri Lanka wanted: a factory in the island nation's hinterland that creates local jobs. It employs 800 workers, all from the region, including its chief executive Mr Koralage.                                                  , The unit makes garments for export and generates almost $140,000 a year for the local villages.                                                                                                                                                                                                                    , But it is now stuck in a vicious cycle. The dollar shortage has left the country struggling to pay for imports including food, medicine and fuel.                                                                                                                                                                  , Even Sri Lanka's power plants are struggling to maintain operations. Long, rolling, power cuts are crippling businesses, especially export-oriented ones that are capable of earning the much-needed dollars.                                                                                                      , Exporters like Kolonna typically lock in orders at fixed prices and have limited capacity to absorb rising costs. While a weaker Sri Lankan rupee benefits exporters, rising costs are draining all positives.                                                                                                     , This affects both the business and its employees. Mr Koralage says as the cost of living goes up, retaining skilled workers will be another yet challenge.                                                                                                                                                         , It's not just sewing machines that have to keep running. Workers also need to get to factories, something made more difficult with almost 50% of public transport not operating.                                                                                                                                   , In the town of Embilipitiya, some 25km (15.5 miles) from Kolonna Manufacturing, the queues were along although the bus station was less busy than usual.                                                                                                                                                           , 30-year-old Chathuri Dileeka, who works as an office assistant, had been waiting for over an hour. "Earlier I used to get a bus in 15 minutes, now I have to wait one to two hours. Sometimes the bus stops midway with no fuel," she told the BBC.                                                                , She has a motorcycle at home for shorter commutes but with petrol pumps running dry, even that now stands idle, she said.                                                                                                                                                                                          , A group of drivers waiting for their next customer say the number of journeys they have made on longer routes has fallen by a third.                                                                                                                                                                               , Operators have stopped running buses on some less busy routes in order to ration the available fuel.                                                                                                                                                                                                               , "[The] situation was not so bad even during Covid lockdowns. That was a crisis that the entire world faced, but this only we are suffering. I had never imagined a life like this, standing in fuel queues for days," a driver who has been been in the job for 20 years told the BBC. He did not want to be named., Transport services had completely stopped last week when the government announced that it was closing down the supply of diesel for two days, due to offloading issues at ports.                                                                                                                                   , Container trucks leaving the ports with essentials to be transported to the rest of the country are also waiting in kilometre-long queues for days, exasperating shortages.                                                                                                                                        , The beach town of Hikkaduwa, 130km south of Colombo, looks deserted. Once bustling with tourists from Europe and Middle East, the streets are now empty.                                                                                                                                                           , Nelaka Gunarathne opened his 30-room hotel to guests late last year after a three-year hiatus. After a six months of good business, Mr Gunarathne is faced once again with silent lobbies and empty rooms.                                                                                                         , Tourists are leaving as hotels like his struggle to provide even the most basic services expected by guests.                                                                                                                                                                                                       , Power cuts and shortages of essentials have hit hopes of a recovery, even for the tourism sector which is crucial to Sri Lankan economy. The industry collapsed during the pandemic, which was a key reason for the country's depleted foreign exchange reserves.                                                  , Most mid-sized and small-sized firms do not have a generator for back-up electricity as the country has not faced major power cuts in the past.                                                                                                                                                                    , As it attempted to stop foreign currency leaving the country, Sri Lanka's government placed import restrictions on certain items.                                                                                                                                                                                  , That led to shortages and sudden price rises for essential foodstuffs including milk powder and rice. Headline inflation has risen to more than 17% in recent weeks, while food inflation is above 20%.                                                                                                            , With even a cooking gas refills uncertain, restaurants are closed and hotels say retaining guests is a challenge. Mr Gunarathne said 80% of his bookings were cancelled between March and April.                                                                                                                   , "Guests have been calling to ask if the curfew will continue or will they get food? We really don't have answers for anything. When we are ourselves struggling to buy basic needs, how do we promise guests?" he said.                                                                                            , Sri Lanka became a popular tourist destination due to its pristine beaches and rich local culture. But now protests on the streets are casting a shadow over its image as a safe place to go on holiday.                                                                                                           , The US State Department has raised its threat level and issued a level 3 travel advisory for American citizens against travel to Sri Lanka. India's largest airline Air India has reduced the number of flights to Sri Lanka due to lower demand.                                                                  , What Sri Lanka needs now is economic and political stability to enable its factories to run smoothly and to bring tourists back to its shores.                                                                                                                                                                     , This video can not be played                                                                                                                                                                                                                                                                                       , Inside Thatcher and Reagan's close political relationship                                                                                                                                                                                                                                                          , What did Putin do before he came to power?                                                                                                                                                                                                                                                                         , Romesh Ranganathan investigates the musician's death                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/07/carnage-is-epic-in-bonds-due-to-feds-inflation-error-jim-bianco.html </td>
   <td style="text-align:left;"> 2022-04-08 07:15:15 </td>
   <td style="text-align:left;"> Wild inflation will hurt all financial assets, market researcher Jim Bianco warns </td>
   <td style="text-align:left;"> , There may be no escape from the bond market turmoil — even for stock investors.                                                                                                                                                                                                                                                                                           , Market researcher Jim Bianco warns critical Federal Reserve policies to control wild inflation will inflict widespread losses on Wall Street.                                                                                                                                                                                                                             , "Eventually, this is going to come back and hurt all financial assets," the Bianco Research president told CNBC "Fast Money" on Thursday.                                                                                                                                                                                                                                 , Bianco turned bearish on stocks late last year, primarily due to inflation risks. He blames the Fed for waiting too long to end its pandemic easy money policies and lift interest rates.                                                                                                                                                                                 , "The call last year that inflation would be well-contained and transitory is arguably one of the worst forecasts in Federal Reserve history," said Bianco. "They are now stuck with this ultra-aggressive policy because they didn't start raising rates at a very leisurely pace a year ago."                                                                            , He worries about the big catch-up's costs.                                                                                                                                                                                                                                                                                                                                , "They don't intend on creating a hard landing. But what they do intend on doing is reining in prices," Bianco said. "They want lower inflation, and they're going to raise rates til they get lower inflation. How are they going to do that? They're going to slow demand down."                                                                                         , According to Bianco, the Fed's only solution is to boot interest rates quickly and get wealthy people to stop spending. The bond market is already discounting the central bank's likely bold moves.                                                                                                                                                                      ,  "The bond market gets it. The carnage is epic," he wrote in a recent Twitter thread. "This is not only the worst bond market in our career (total return) but might be the worst of our lifetime."                                                                                                                                                                       , Bianco, who sees a 75% chance of inflation within the next two years, expects a 50 basis point hike at its next policy meeting on May 3 through May 4.                                                                                                                                                                                                                    , "It will be 50 [basis points] all the way through until the Fed basically raises rates too much and breaks something. And, then they'll be done. But, they're not going to go back to 25," he said. "If the stock market wants to go up, maybe they should be talking about 75 instead of 50."                                                                            , Bianco contends the Fed is aware the stakes are high.                                                                                                                                                                                                                                                                                                                     , "They don't want to create the mistake in the other direction by being too timid right now. That's out the window now," Bianco said. "They don't want to create a broken market. They don't want to create a recession. But when you go down that path and you're that adamant about trying to rein in inflation, it makes it very likely that you will create a mistake.", Disclaimer                                                                                                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61007176?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-08 07:03:21 </td>
   <td style="text-align:left;"> What's causing flight disruption this Easter? </td>
   <td style="text-align:left;"> International travel for the Easter holidays has got off to a bumpy start.                                                                                                                                                                                                                                                                      , Thousands of people heading on their first trip abroad since coronavirus restrictions ended have been met with long queues, delays, and in some cases, cancelled flights.                                                                                                                                                                       , Some airports and airlines have been struggling as passenger numbers gradually return to pre-pandemic levels.                                                                                                                                                                                                                                   , And industry leaders have warned the situation isn't going to improve for some time yet.                                                                                                                                                                                                                                                        , Manchester Airport appears to have been the worst hit after issues developed last weekend, while Heathrow, Gatwick and Birmingham have also been affected by delays and cancellations.                                                                                                                                                          , Travellers at Manchester Airport described scenes of "chaos" after several missed their flights, amid warnings that emergency services staff could be drafted in to help tackle the problems.                                                                                                                                                   , The disruption led to the airport's managing director Karen Smart announcing that she would stand down.                                                                                                                                                                                                                                         , Donna Mayfield queued for three hours at Manchester Airport but still missed her flight to Spain to see her 83-year-old mother for the first time since lockdowns began.                                                                                                                                                                        , She said the situation was "horrendous", while another traveller said they saw "customers and staff in tears".                                                                                                                                                                                                                                  , Former Monarch Airlines boss Tim Jeans, who is now director of Cornwall Airport Newquay, told the BBC's Today programme it appeared Manchester Airport didn't have correct plans in place to recruit and train staff in advance.                                                                                                                , Passengers at Birmingham Airport also complained of long queues for those both arriving and departing. The airport apologised and said standards had not been met.                                                                                                                                                                              , As Covid led to the government imposing lockdowns and travel restrictions, airport operations across the world shut down with fleets of planes grounded.                                                                                                                                                                                        , The furlough scheme helped, but couldn't fully shield the aviation industry from the devastating impact, with thousands of job losses across airlines and airports. British Airways shed more than 10,000 jobs, while EasyJet closed its bases at Stansted, Southend and Newcastle, with the loss of 670 roles.                                 , Amid the job uncertainty some workers opted for career changes.                                                                                                                                                                                                                                                                                 , Yet as borders reopened and demand for flights returned, the industry has found it difficult to recruit new staff quickly enough.                                                                                                                                                                                                               , Reasons for the weakened workforce is due to a "combination of a very tight labour market, delays in the necessary government security checks for new and returning staff, as well as Covid-related staff absences," according to the Airport Operators Association (AOA), which represents most UK airports ranging from Heathrow to Edinburgh., One Resourcing, a specialist aviation and airport recruitment company, told the BBC that finding enough ground staff, including cleaners and baggage handlers, was proving very challenging.                                                                                                                                                    , Its boss Kevin O'Reilly said some other jobs were tempting workers away and some European Union nationals had left after Brexit.                                                                                                                                                                                                                , "It's always been a tough market to recruit for, but it's become harder this year," he said.                                                                                                                                                                                                                                                    , "Recruitment at airports doesn't happen overnight, people must go through a thorough security vetting process to get an airside pass," he added.                                                                                                                                                                                                , Meanwhile, Cornwall Airport Newquay boss Mr Jeans said it takes on average at least 12 weeks to recruit and train new security staff.                                                                                                                                                                                                           , But staff shortages aren't the only issue airports highlighted as a cause of queues.                                                                                                                                                                                                                                                            , Covid documents are still required by many countries, which has prolonged check-in times, and rather ironically, when people turn up too early, that only adds to queues.                                                                                                                                                                       , John Strickland, director of transport consultancy JLS Consulting, has said the situation for airlines was going to be "very difficult" over the next couple of months.                                                                                                                                                                         , Karen Dee, chief executive of the AOA, said at peak time passengers "may not have the experience they are used to".                                                                                                                                                                                                                             , She said airports were working hard to recruit more staff in the run-up to the Easter holidays, and were "working with the UK government to resolve any delays in the necessary checks before staff can start work".                                                                                                                            , Britain's biggest airport Heathrow has said peak demand over the summer holidays could reach 85% of pre-pandemic levels and raised concerns about capacity.                                                                                                                                                                                     , Elsewhere, Edinburgh Airport has also warned holidaymakers to expect queues and disruption over the summer as it returns to full service.                                                                                                                                                                                                       , And it's not just UK airports being hit by delays - Dublin Airport has advised travellers to arrive three-and-a-half hours before their flight due to similar issues.                                                                                                                                                                           , A number of well-known airlines, including EasyJet and British Airways have cancelled flights weeks in advance, however, in the run up to Easter, there have been a few services grounded at the last minute.                                                                                                                                   , Package holiday operators appear less affected. For example, Jet2 is reporting its schedule is operating as planned.                                                                                                                                                                                                                            , EasyJet has blamed hundreds of its cancellations on Covid-related staff absences, with cabin crew and pilots among those out of action.                                                                                                                                                                                                         , Meanwhile, BA has axed fewer flights at short notice due to Covid. But it took the decision two weeks ago to thin out its April and May schedules to ease some of the pressure.                                                                                                                                                                 , BA has had other issues too. It has had several IT meltdowns in recent weeks which have caused delays to journeys and its Moscow flights are suspended as a result of the war in Ukraine.                                                                                                                                                       , The resumption of some long-haul routes has also been delayed because of the Covid situation in other parts of the world.                                                                                                                                                                                                                       , Are you flying over the weekend? Have your flights been cancelled? Please share your experience by emailing haveyoursay@bbc.co.uk.                                                                                                                                                                                                              , Please include a contact number if you are willing to speak to a BBC journalist. You can also get in touch in the following ways:                                                                                                                                                                                                               , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or comment or you can email us at HaveYourSay@bbc.co.uk. Please include your name, age and location with any submission.                                                                               , Inside Thatcher and Reagan's close political relationship                                                                                                                                                                                                                                                                                       , What did Putin do before he came to power?                                                                                                                                                                                                                                                                                                      , Romesh Ranganathan investigates the musician's death                                                                                                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/04/07/ukraine-hospital-civilian-russia-wounded-tapper-dnt-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-08 07:01:47 </td>
   <td style="text-align:left;"> Video: Wounded Ukrainian woman speaks to CNN after 7 bombs hit her neighborhood - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/stocks-set-for-steady-open-treasury-curve-steeper-markets-wrap </td>
   <td style="text-align:left;"> 2022-04-08 06:31:25 </td>
   <td style="text-align:left;"> Stocks, U.S. Futures Steady; Treasury Yields Fall: Markets Wrap </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                           , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                    , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                              , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                              , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                           , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                 , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                          , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                          , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                          , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                       , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                   , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                       , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                 , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                         , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                          , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                               , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                           , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                          , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                              , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                              , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                      , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                          , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                               , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                    , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                             , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                    , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                          , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                            , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                              , A commuter checks his phone while riding a subway in Shanghai, China.                                                                                                                                                                     , Sunil Jagtiani                                                                                                                                                                                                                            , Asian stocks and U.S. equity futures were steady Friday in cautious trading as investors digested the Federal Reserve’s plan for aggressive policy tightening and monitored China’s Covid lockdowns.                                      , Shares fluctuated in Japan, South Korea and Australia after modest Wall Street gains Thursday. Global equities are nursing losses for the week, hurt by the risk of an economic downturn as the Fed tackles high inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/uruguay-steps-up-inflation-fight-with-125-basis-point-rate-hike?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 06:31:21 </td>
   <td style="text-align:left;"> Uruguay Steps Up Inflation Fight With 125 Basis-Point Rate Hike </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                                                                                                                                                                , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                                                     , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                                                                                                   , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                                                                                                                                                         , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                                                                                                                                                                   , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                                                                                                                                                                   , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                                                                                                                                                                , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                                                                                                                                                      , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                                                                                                                                                               , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                                                                                                                                                               , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                                                                                                                                                               , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                                                                                                                                                            , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                                                                                                                                                        , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                                                                                                                                                            , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                                                                                                                                                      , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                                                                                                                                                              , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                                                                                                                                                               , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                                                                                                                                                                    , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                                                                                                                                                                , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                                                                                                                                                               , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                                                                                                                                                                   , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                                                                                                                                                                   , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                                                                                                                                                           , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                                                                                                                                                               , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                                                                                                                                                                    , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                                                                                                                                                         , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                                                                                                                                                                  , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                                                                                                                                                         , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                                                                                                                                                               , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                                                                                                                                                                 , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                                                                                                                                                                   , Ken Parks                                                                                                                                                                                                                                                                                                                                                                      , Uruguay’s central bank surprised economists by raising borrowing costs by more than it had anticipated as it seeks to guide inflation expectations back to target.                                                                                                                                                                                                             , Policy makers lifted the key interest rate on Thursday by 125 basis points to 8.5%, following two straight increases of 75 basis points. It was the most aggressive move since the central bank reintroduced its benchmark rate in September 2020. Two economists surveyed by Bloomberg expected a third hike of the same magnitude while one forecast a 100 basis-point boost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/commodities-boom-sends-aussie-stocks-correlation-to-decade-high?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 06:30:36 </td>
   <td style="text-align:left;"> Commodities Boom Sends Aussie, Stocks Correlation to Decade-High </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                                                                                                   , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                        , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                                      , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                                                                                            , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                                                                                                      , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                                                                                                      , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                                                                                                   , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                                                                                         , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                                                                                                  , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                                                                                                  , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                                                                                                  , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                                                                                               , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                                                                                           , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                                                                                               , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                                                                                         , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                                                                                                 , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                                                                                                  , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                                                                                                       , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                                                                                                   , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                                                                                                  , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                                                                                                      , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                                                                                                      , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                                                                                              , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                                                                                                  , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                                                                                                       , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                                                                                            , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                                                                                                     , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                                                                                            , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                                                                                                  , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                                                                                                    , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                                                                                                      , Jackie Edwards and                                                                                                                                                                                                                                                                                                , Garfield Clinton Reynolds                                                                                                                                                                                                                                                                                         , The relationship between Australia’s equities and currency has become the closest in a decade as commodity prices surge.                                                                                                                                                                                          , The 180-day correlation between the country’s stock benchmark and the Australian dollar has climbed to the highest level since late 2011, according to data compiled by Bloomberg. The strengthened ties come as rallies in materials from oil to iron ore have boosted both the nation’s equities and the Aussie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/coal </td>
   <td style="text-align:left;"> 2022-04-08 06:13:38 </td>
   <td style="text-align:left;"> Coal Set to Rise as EU Bans Russian Imports </td>
   <td style="text-align:left;"> Coal prices are expected to rise significantly after the markets open on Friday after European Union countries signed a ban on coal imports from Russia and pledged to start working on an embargo on Russian oil, gas and nuclear fuel. On Thursday, Newcastle coal futures, the benchmark for the top consuming region Asia, were trading around $285 a tonne regaining the ground after falling below $260 a tonne at the end of March. The EU depends on Russia for around 45% of its coal imports. Coal hit a record high of $430 a tonne in March, as the Ukraine war prompted users to seek alternatives to Russian shipments, and as an economic rebound from the pandemic sparked demand for fossil fuels. In the US, prices for coal from Central Appalachia surged to above $106 a tonne last week, the highest since late 2008, while prices in the Illinois Basin topped $100 for the first time since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/07/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-04-08 06:03:50 </td>
   <td style="text-align:left;"> Stock futures little changed following Thursday's comeback as investors assess Fed plans </td>
   <td style="text-align:left;"> , U.S. stock futures were little changed on Thursday night after the major averages staged a late-day comeback as investors appraised the likelihood of tighter monetary policy from the Federal Reserve to combat inflation.                                                                                                                                                                                                                                      , Dow Jones Industrial Average futures edged up 2 points, or 0.01%. S&amp;P 500 and Nasdaq 100 futures climbed 0.01% and 0.05%, respectively.                                                                                                                                                                                                                                                                                                                          , The Dow Jones Industrial Average bounced back on Thursday after two straight days of losses. The Dow rose 87.06 points, or 0.25%, to 34,583.57 after dropping as much as 300 points earlier in the session. The S&amp;P 500 gained 0.43% to 4,500.21, and the Nasdaq Composite ticked up 0.06% to 13,897.30.                                                                                                                                                         , The choppy session occurred amid continued uncertainty as investors weighed a more aggressive stance against inflation by the Federal Reserve. On Wednesday, the central bank disclosed its March meeting minutes, revealing that policymakers plan to reduce their bond holdings by a consensus amount of about $95 billion a month. The minutes also indicated potential interest rate hikes of 50 basis points in future meetings. A basis point equals 0.01%., "We're in a trading range market and it's going to be this way for some time," Stephanie Link, chief investment strategist and portfolio manager at Hightower, told CNBC's "Closing Bell." "And it's really because we just have so many unknowns to deal with."                                                                                                                                                                                                 , On the economic front, the wholesale inventories report will be released 10 a.m. Friday.                                                                                                                                                                                                                                                                                                                                                                         , Investors are also looking ahead to earnings season, which will kick off next week with reports from five big banks. JPMorgan will report before the bell on Wednesday. Citigroup, Goldman Sachs, Morgan Stanley and Wells Fargo will report before markets open on Thursday.                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/faraday-future-receives-nasdaq-noncompliance/story.aspx?guid={9BFC4226-85E8-4177-9FAC-6B56BB73A815}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 05:56:11 </td>
   <td style="text-align:left;"> Faraday Future receives Nasdaq noncompliance notice - MarketWatch </td>
   <td style="text-align:left;"> Faraday Future Intelligent Electric Inc.  said late Thursday it has received a notice of noncompliance from the Nasdaq stock exchange due to its delay in filing its 10-K. The notice was expected and the company said it hopes to regain compliance by April 19. Faraday Future notified the exchange in March it was unable to file the annual report on time, saying it needed extra time to finish an internal probe as recommended by a special committee of independent directors. Faraday Future, which became a public company in July through a merger with a blank-check company, said in a filing late March that several of its executives...
    , Twitter Inc. may have avoided a hostile takeover by Elon Musk by letting him on the board, but what kind of changes will Musk bring?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-08 05:34:00 </td>
   <td style="text-align:left;"> US 10-Year Treasury Yield Hits New 3-Year High </td>
   <td style="text-align:left;"> The US 10-year Treasury Yield surged to above 2.66%, its highest level since March 2019 as investors anticipate an aggressive looming policy tightening cycle as major central banks sought to tame inflation, currently running at records levels. Earlier this week, Fed officials gave more hawkish remarks while on Wednesday Minutes from the Federal Reserve's March meeting showed that the central bank was considering hiking rates by 50-basis-point during the last meeting. Officials also agreed that monthly caps of about $95 billion in the balance sheet reduction would likely be appropriate, which is higher than $50 billion a month back in 2017-2019. Meantime, Germany's 10-year Bund yield, the benchmark for Europe, remained near 0.67%, closing in on its highest level since February 2018. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/china-developer-rally-runs-up-against-impatience-for-policy-plan?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 05:30:00 </td>
   <td style="text-align:left;"> China Developer Rally Fueled by Fear and Greed Tests Policy Vow </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                           , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                    , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                              , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                              , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                           , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                 , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                          , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                          , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                          , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                       , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                   , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                       , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                 , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                         , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                          , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                               , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                           , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                          , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                              , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                              , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                      , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                          , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                               , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                    , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                             , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                    , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                          , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                            , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                              , Rebecca Choong Wilkins                                                                                                                                                                                                                    , The Chinese government’s pledge of support for embattled developers ignited a frenzied rush for stocks and bonds.                                                                                                                         , But three weeks later, the frantic rally is testing the limits of investors’ patience as Beijing has yet to spell out details of how the government would relax curbs to prevent a disorderly collapse in the property market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/propane </td>
   <td style="text-align:left;"> 2022-04-08 05:29:52 </td>
   <td style="text-align:left;"> Propane Hits 7-week Low </td>
   <td style="text-align:left;"> Propane decreased to a 7-week low of 1.2861 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biogen-stock-edges-lower-after/story.aspx?guid={63B7EAD4-78AE-4969-B7E2-3F9C1501923B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 05:21:15 </td>
   <td style="text-align:left;"> Biogen stock edges lower after Medicare restrictions on Aduhelm finalized - MarketWatch </td>
   <td style="text-align:left;"> Shares of Biogen Inc. 
        BIIB,
        +0.92%
       fell 0.3% in the extended session Thursday after the Centers for Medicare and Medicaid Services, which oversees the Medicare program, said they had finalized their policies about covering the biotech's controversial Alzheimer's drug Aduhelm and future others. As it signaled in January, CMS said that Food and Drug Administration-approved monoclonal antibodies such as Aduhelm and others in its class would be covered for people with Medicare only if they are enrolled in clinical trials. CMS will provide "enhanced access" and coverage for people with Medicare participating in CMS-approved studies, it said. CMS said it considered more than 10,000 comments and more than 250 peer-reviewed documents in making its final determination. Aduhelm, the first new treatment for Alzheimer's in 20 years, was approved by the FDA for the treatment of the neurodegenerative disease in June but sales have been disappointing. Shares of Biogen ended the regular trading day up 0.9%. , WWE CEO who created the modern-day wrestling phenomenon increasingly looks like a private equity suit, squeezing dollars out of a legacy business through employee layoffs and stock buybacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 04:53:00 </td>
   <td style="text-align:left;"> Brazilian Equities Recover on Thursday </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, reversed course and closed 0.5% up at 118,862 on Thursday, following three consecutive sessions of losses, mainly lifted by Petrobras after a new government appointment to the presidency of the company and amid higher oil prices. Brazil's Ministry of Mining and Energy named José Mauro Ferreira Coelho to succeed Joaquim Silva e Luna as CEO of state-controlled oil company Petrobras, with analysts noting that Coelho favors Petrobras' autonomy to define and execute its own pricing policy. Meanwhile, investors digested hawkish signals from the US Federal Reserve to tackle surging inflation and remained cautious about the conflict in Ukraine and the impact of more severe sanctions against Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/07/health/aduhelm-medicare-alzheimers.html </td>
   <td style="text-align:left;"> 2022-04-08 04:45:10 </td>
   <td style="text-align:left;"> Medicare Officially Limits Coverage of Aduhelm to Patients in Clinical Trials - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Officials cited data showing the new Alzheimer’s drug has serious safety risks and may not help patients.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , By Pam Belluck                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Ever since Medicare proposed to sharply limit coverage of the controversial Alzheimer’s drug Aduhelm, the agency has been deluged with impassioned pleas.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Groups representing patients insisted the federal insurance program pay for the drug. Many Alzheimer’s experts and doctors cautioned against broadly covering a treatment that has uncertain benefit and serious safety risks.                                                                                                                                                                                                                                                                                                                                                                                   , On Thursday, Medicare officials announced their final decision. Though the Food and Drug Administration has approved Aduhelm for some 1.5 million people, Medicare will cover it only for people who receive it as participants in a clinical trial.                                                                                                                                                                                                                                                                                                                                                             , Chiquita Brooks-LaSure, the administrator of the Centers for Medicare and Medicaid Services, or C.M.S., said the decision was intended to protect patients while gathering data to indicate whether Aduhelm, an expensive monoclonal antibody given as a monthly infusion, could actually help them by slowing the pace of their cognitive decline.                                                                                                                                                                                                                                                              , “It’s our obligation at C.M.S. to really make sure it’s reasonable and necessary,” Ms. Brooks-LaSure said in an interview Thursday. “The vast majority” of the approximately 10,000 comments the agency received on its website, she said, were in favor of “really limiting coverage of Aduhelm to a really controlled space where we could continue to evaluate its appropriateness for the Medicare population.”                                                                                                                                                                                              , Aduhelm’s manufacturer, Biogen, said the decision “effectively denies all Medicare beneficiaries access to Aduhelm,” adding that “Biogen is carefully considering its options and will provide updates as the company further evaluates the business impact of this decision.”                                                                                                                                                                                                                                                                                                                                   , A major issue for Medicare had been how to deal with other similar drugs for Alzheimer’s, several of which are likely to be considered for F.D.A. approval soon. In a proposal in January, Medicare had said it would cover them in the same way as Aduhelm because it typically made coverage decisions for an entire class of drugs.                                                                                                                                                                                                                                                                           , But after both experts and advocacy groups raised concerns, Medicare officials said Thursday that they would not automatically apply the same restrictions to each new drug. If, unlike with Aduhelm, the F.D.A. finds that there is clear evidence that a drug can help patients, Medicare would cover it for all eligible patients and would only impose a requirement that the patients’ experience be tracked.                                                                                                                                                                                               , Dr. Lee Fleisher, the chief medical officer at the Medicare agency., said the two-track way of dealing with the fast-developing field of Alzheimer’s therapies, a program called Coverage with Evidence Development, “is meant to be nimble and really respond to any new drugs in this class that are in the pipeline, and do demonstrate clinical benefit.”                                                                                                                                                                                                                                                    , The decision is extremely unusual for Medicare, which almost always automatically pays for drugs that the F.D.A. has approved, at least for the medical conditions designated on labels.                                                                                                                                                                                                                                                                                                                                                                                                                         , But Aduhelm’s path has been very unusual, too. The F.D.A. itself acknowledged that it was unclear if the drug was beneficial when it approved Aduhelm last June, authorizing it for people with mild Alzheimer’s-related cognitive decline.                                                                                                                                                                                                                                                                                                                                                                      , The clinical trial evidence reviewed by the F.D.A. showed that patients in one trial of Aduhelm appeared to experience slight slowing of cognitive decline, while patients in a nearly identical trial didn’t appear to benefit at all. About 40 percent of patients on the dosage later approved experienced brain swelling or brain bleeding, often mild, but sometimes serious. Both a council of senior F.D.A. officials and the agency’s independent advisory committee had said there wasn’t enough evidence for approval.                                                                                 , Instead of giving the drug full approval, the F.D.A. greenlighted it under a program called “accelerated approval,” which allows authorization of drugs that have uncertain benefit if they are for serious diseases with few treatments and if the drug affects a biological mechanism in a way considered reasonably likely to help patients.                                                                                                                                                                                                                                                                  , The agency’s justification was that Aduhelm targets a protein, amyloid, that forms plaques in the brains of Alzheimer’s patients. But many Alzheimer’s experts say that years of data have not shown that reducing amyloid can slow cognitive decline.                                                                                                                                                                                                                                                                                                                                                           , Questions about the approval, and whether the F.D.A. worked too closely with Biogen, have prompted investigations by congressional committees, the Health and Human Services department’s inspector general, the Federal Trade Commission and the Securities and Exchange Commission. Major medical centers, including the Cleveland Clinic, have declined to offer Aduhelm.                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As a result of concerns raised by Alzheimer’s experts and some groups, Medicare officials announced several other changes to their earlier proposal. Instead of requiring randomized controlled trials approved by C.M.S., Medicare will cover participants in any trial approved by the F.D.A. or the National Institutes of Health. It will allow those trials to be conducted in a broader array of locations, not just hospital settings, and to include people with other neurological conditions like Down syndrome, many of whom develop Alzheimer’s but had been excluded from the earlier proposed plan., The trials will still need to comply with a Medicare requirement to recruit a racially and ethnically diverse group of participants, contrasting with the previous trials of Aduhelm, in which most participants were white.                                                                                                                                                                                                                                                                                                                                                                                     , In the trials, “the manufacturers will have to come to us with how are they going to include all patients that represent the Medicare population, and how are they going to ensure that all of these patients are getting appropriate medical treatment and monitoring of their treatment while they’re in each of these studies,” Tamara Syrek Jensen, the director of coverage and analysis for the Medicare agency’s Center for Clinical Standards and Quality, said in an interview.                                                                                                                         , The F.D.A. has also required Biogen to conduct another clinical trial to determine if the drug provided any evidence of benefit, but it said that in the years it will take for that trial to be completed, Aduhelm would be available to patients. Under Thursday’s decision, Medicare would cover the costs for participants in Biogen’s trial.                                                                                                                                                                                                                                                                , In a statement after the Medicare announcement, the F.D.A. said, “At the end of the day, both agencies have a shared goal of ensuring that safe and effective medical products are available for Americans.”                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Medicare’s coverage evaluation team makes decisions without considering the cost of a drug, but the Aduhelm decision could ease some concerns about how covering the drug might affect the pocketbooks of the country’s millions of Medicare beneficiaries.                                                                                                                                                                                                                                                                                                                                                      , Last year, Medicare’s actuarial division, acting without knowing what the coverage decision would be, imposed one of the biggest-ever increases in Medicare Part B premiums for 2022, partly driven by the possibility of coverage for Aduhelm, which at the time was priced by its manufacturer at $56,000 a year.                                                                                                                                                                                                                                                                                              , Since then, Biogen, facing weak sales of the drug after many hospitals and doctors would not prescribe it, lowered the price to $28,800 a year, still much higher than many analysts have said is warranted.                                                                                                                                                                                                                                                                                                                                                                                                     , Xavier Becerra, secretary of health and human services, had said that he would consider lowering premiums after the final coverage decision for Aduhelm was made, adding that “We’re going to make sure that seniors don’t pay more than they have to.”                                                                                                                                                                                                                                                                                                                                                          , In the interview Thursday, Ms. Brooks-LaSure, the C.M.S. administrator, said, “The secretary told us to look at it, and we are going to engage in the process of reviewing the Part B premium.”                                                                                                                                                                                                                                                                                                                                                                                                                  , Advocacy groups, several of which receive some funding from Biogen and other pharmaceutical companies, had campaigned vigorously for broad Medicare coverage. These groups said patients should be able to decide with their doctors whether to try an F.D.A.-approved drug and claimed it was discriminatory to only reimburse participation in clinical trials that may not be easily accessible to many patients.                                                                                                                                                                                             , “We just can’t let it stand as it is,” Harry Johns, the chief executive of the Alzheimer’s Association, told the organization’s staff, according to a recording of the meeting obtained by The New York Times.                                                                                                                                                                                                                                                                                                                                                                                                   , After the Medicare decision was announced on Thursday, Mr. Johns said the association was still evaluating it, but he added,  “At initial review we are very disappointed with the immediate impact it will have on Americans living with Alzheimer’s and their families today. While we note some of the recommendations provided by people living with Alzheimer’s and the Alzheimer’s Association have been incorporated into the C.M.S. decision, denying access to FDA-approved Alzheimer’s treatments is wrong.”                                                                                           , Medicare officials said the decision was an attempt to provide what they consider important limits on Aduhelm’s coverage, while not necessarily consigning future anti-amyloid monoclonal antibody drugs to similar restrictions.                                                                                                                                                                                                                                                                                                                                                                                , If another drug in that class were to win full, or traditional, F.D.A. approval, which usually requires two convincing clinical trials, that would signal that there is persuasive evidence that the drug can help patients and that its benefits outweigh its risks, Medicare officials indicated.                                                                                                                                                                                                                                                                                                              , “If a drug were approved under traditional approval tomorrow, we are ready,” Ms. Jensen said, adding that such a medication would be available “in a real-world setting” and patients would be enrolled in a registry or another program that would allow Medicare to monitor whether they are benefiting from the medication.                                                                                                                                                                                                                                                                                   , “There is such a need to really understand what is happening that we want to make sure that we are providing all of that additional or appropriate clinical care,” Ms. Brooks-LaSure, Medicare’s administrator, said. “So, we’re going to make sure that we are continuing to track what’s happening so that so that we continue to develop that evidence around a treatment.”                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/technology/peter-thiel-bitcoin-government-woke-companies </td>
   <td style="text-align:left;"> 2022-04-08 04:35:01 </td>
   <td style="text-align:left;"> Peter Thiel: Bitcoin will 'never be' controlled by government, unlike 'woke companies' </td>
   <td style="text-align:left;"> PayPal co-founder Peter Thiel lists the "enemies" of Bitcoin at the Bitcoin 2022 conference in Miami.                                                                                                                                                                                                                                                                          , PayPal and Palantir Technologies co-founder Peter Thiel said Thursday that Bitcoin will "never be" controlled by the government, unlike "woke companies."                                                                                                                                                                                                                      , Thiel made the comment at the Bitcoin 2022 conference, where he explained the difference between fiat — or government-backed — money and cryptocurrency. He threw a wad of $100 bills to someone in the first row of the audience to make his point.                                                                                                                           , Peter Thiel, co-founder of PayPal, Palantir Technologies, and Founders Fund, holds hundred dollar bills as he speaks during the Bitcoin 2022 Conference at Miami Beach Convention Center on April 7, 2022 in Miami, Florida.  (Marco Bello / Getty Images)                                                                                                                     , "Even being in a stock, you're effectively being in something that's like a government-linked entity. Companies — woke companies — are sort of quasi-controlled by the government in a way that Bitcoin never will be," he said.                                                                                                                                               , BITCOIN TRADES AROUND $43,000 AS MIAMI CONFERENCE GETS UNDERWAY                                                                                                                                                                                                                                                                                                                , The tech investor opened his remarks with a video from 1999 in which he makes the claims that "everyone in the middle class" and the "developing world" would eventually have "internet-enabled cellphones" — an idea that seemed impossible to some at the time. He went on to predict that access to bank accounts via cell phones would threaten authoritarian governments. , Today, Thiel and other cryptocurrency investors argue that Bitcoin is the solution to such power because it is not controlled by anyone except those who own it.                                                                                                                                                                                                               , Peter Thiel, co-founder of PayPal, Palantir Technologies, and Founders Fund, holds hundred dollar bills as he speaks during the Bitcoin 2022 Conference at Miami Beach Convention Center on April 7, 2022 in Miami, Florida.  (Marco Bello / Getty Images)                                                                                                                     , "The real competitor for Bitcoin is not Ethereum. That's a payment system. It's not even gold. It's something like the S&amp;P 500. It's the stock market as a whole. This is the way Bitcoin trades every day," said Thiel, who made his name, in part, by being the first outside investor in Facebook.                                                                          , AARON RODGERS, SERENA WILLIAMS, ODELL BECKHAM JR. TALK BITCOIN AT CONFERENCE: ‘I’M BETTING BIG ON CRYPTO'                                                                                                                                                                                                                                                                      , While it is "always hard" to envision the future of Bitcoin, Thiel continued, he believes Bitcoin is the "most honest" and "most efficient" market in the world, calling it "the canary in the coal mine" that predicted record-high inflation.                                                                                                                                , The venture capitalist also listed CEOs Jamie Dimon, Warren Buffet and Larry Fink as the "enemies" of Bitcoin, saying they have an "institutional bias" against the world's most popular cryptocurrency. He likened Wall Street to geriatrics and cryptocurrency to youth.                                                                                                     , Peter Thiel, co-founder of PayPal, Palantir Technologies, and Founders Fund, holds hundred dollar bills as he speaks during the Bitcoin 2022 Conference at Miami Beach Convention Center on April 7, 2022 in Miami, Florida.  (Marco Bello / Getty Images)                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                        , An estimated 25,000 people flooded to the Bitcoin 2022 conference in South Beach, Miami, to learn more about cyrptocurrency and fintech companies, network with like-minded individuals, and discuss the future of Bitcoin as a mainstream form of currency.                                                                                                                   , Miami has been dubbed the "crypto capital" of the United States and even the world as it attracts a growing number of tech entrepreneurs, investors and startups. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-scotland-north-east-orkney-shetland-61031088?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-08 04:28:42 </td>
   <td style="text-align:left;"> Cambo: Ithaca Energy pledges to develop controversial oil field </td>
   <td style="text-align:left;"> The controversial Cambo oil field off Shetland could now be developed after the owner of the field was bought by another energy firm.                                                                                                                                                                           , Siccar Point Energy - which put the project on hold when Shell pulled out - has now been acquired by Ithaca Energy in a $1.5bn (£1.125bn) deal.                                                                                                                                                                 , The new company has pledged to develop Cambo and the nearby Rosebank field.                                                                                                                                                                                                                                     , Campaigners have criticised plans to develop Cambo, warning exploiting it would exacerbate climate change.                                                                                                                                                                                                      , Ithaca's chief executive Alan Bruce said Cambo and Rosebank were "two of the largest undeveloped and most strategically important discoveries" in UK waters.                                                                                                                                                    , Developing them, Mr Bruce added, was a "huge opportunity to not only help secure the UK's energy future for at least another quarter of a century, but also to create thousands of direct and indirect jobs in the process."                                                                                    , A spokeswoman for Shell,  which still owns a 30% stake in Cambo, told the BBC that it had nothing to add to its statement in December when the oil giant said it had "concluded the economic case for investment in this project is not strong enough at this time, as well as having the potential for delays.", The Cambo oil field is thought to contain 800 million barrels of oil, but its development has not yet received final approval from UK government regulators.                                                                                                                                                    , Scotland's first minister has also said the project should not get the green light because of concern over climate change.                                                                                                                                                                                      , The Scottish government said that unlimited extraction of fossil fuels was not consistent with its climate obligations.                                                                                                                                                                                         , A spokesman added: "We have consistently called on the UK government to urgently re-assess all approved oil licenses where drilling has not yet commenced against our climate commitments.                                                                                                                      , "New oil and gas fields do not present a timely solution to improving our energy security in the coming years. Even once operational, the extracted fossil fuels will still be affected by the same global market forces which have contributed to the current energy price crisis.                             , The UK government has been approached for comment.                                                                                                                                                                                                                                                              , In December Siccar Point Energy, the project's majority stakeholder, said it was pausing the Cambo project one week after its partner Shell pulled out.                                                                                                                                                         , Shell had a 30% stake in the field but said the economic case for investment in the North Atlantic project was "not strong enough".                                                                                                                                                                             , Siccar Point Energy said it would continue talks with the UK government over the future of the field.                                                                                                                                                                                                           , On Wednesday the UK government released its energy strategy, which covered plans to boost UK energy independence and tackle rising prices.                                                                                                                                                                      , The plans included a new licensing round for oil and gas projects in the North Sea - something the Scottish government dismissed, saying it was not a long-term solution to energy concerns.                                                                                                                    , The UK government said its commitment to more North Sea projects recognised "the importance of these fuels to the transition and to energy security", adding that producing gas in the UK had a lower carbon footprint than that imported from abroad.                                                          , But its climate advisers last month said UK-produced gas would be sold internationally and would barely reduce the consumer price.                                                                                                                                                                              , Inside Thatcher and Reagan's close political relationship                                                                                                                                                                                                                                                       , What did Putin do before he came to power?                                                                                                                                                                                                                                                                      , Romesh Ranganathan investigates the musician's death                                                                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61027374?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-08 04:20:46 </td>
   <td style="text-align:left;"> Canada proposes foreign buyers home real estate ban </td>
   <td style="text-align:left;"> Canadian Prime Minister Justin Trudeau has proposed a two-year ban on some foreigners buying homes.                                                                                                                                                                                                , The measure comes as the country grapples with some of the worst housing affordability issues in the world.                                                                                                                                                                                        , Prices have jumped more than 20%, pushing the average home in Canada to nearly C$817,000 ($650,000; £495,000) -  more than nine times household income.                                                                                                                                            , But industry analysts say it's not clear a ban on foreign buyers will address the problem.                                                                                                                                                                                                         , Data on purchases by foreign buyers in Canada is limited, but research suggests they amount for a small fraction of the market.                                                                                                                                                                    , "I don't think it's going to have a huge impact," said Ben Myers, president of advisory firm Bullpenn Research &amp; Consulting in Toronto, who found foreigners accounted for just 1% of purchases in 2020, down from 9% in 2015 and 2016.                                                            , "It's a fairly low number and let's face it, the people that really want to buy ... are going to find alternative ways to do it."                                                                                                                                                                  , Mr Myers said the soaring housing costs reflect strong population growth and a shortage of supply, due in part to rules that restrict development.                                                                                                                                                 , The issues have worsened since the pandemic hit in 2020, when policymakers in Canada and elsewhere slashed interest rates to stabilise the economy, lowering borrowing costs and boosting demand even further.                                                                                     , The moves have fuelled the soaring housing prices seen in many markets around the world, but in Canada the disconnect between home prices and incomes is one of the most dramatic, according to OECD data.                                                                                         , Mr Trudeau pledged to tackle housing affordability during his campaign for election last year.                                                                                                                                                                                                     , In addition to the temporary ban on foreign buyers, the budget proposal his government unveiled on Thursday sets aside billions to spur new construction and proposes new programmes, such as a tax-free savings account for first-time buyers.                                                    , This video can not be played                                                                                                                                                                                                                                                                       , Mr Trudeau has also discussed banning certain bidding processes that favour investors, who by some measures have accounted for about one in five homes purchased in Canada since 2014.                                                                                                             , The proposed ban on foreign buyers would exempt permanent residents and foreign students and workers, as well as those buying their primary residence.                                                                                                                                             , The proposal builds on actions such as special taxes that some parts of Canada have already taken against out-of-town and foreign buyers.                                                                                                                                                          , In Ontario, for example, provincial Premier Doug Ford recently announced plans to raise an existing tax on foreign buyers from 15% to 20% and expand it beyond Toronto to the entire province.                                                                                                     , While foreign purchases are not the driver of the affordability issues, taxing them at least captures revenue that can be re-deployed to address such problems, said Steve Pomeroy, head of Focus Consulting, a housing policy firm.                                                               , "If you ban them, you don't really have much of an impact on suppressing rising home prices and you give up the revenue," he said.                                                                                                                                                                 , New Zealand introduced a similar measure banning foreign buyers in 2018.                                                                                                                                                                                                                           , "It's good politics because it's easy to blame a victim that nobody cares about," Mr Pomeroy added. "I don't think it will have much of an impact."                                                                                                                                                , Paul Kershaw, professor at the University of British Columbia and founder of Generation Squeeze, also said he saw little in  Mr Trudeau's proposal likely to slow price increases or significantly address affordability.                                                                          , "It's not clear the housing measures will be sufficient to break Canada's addiction to high and rising home prices," he said, noting that for existing homeowners, the high prices help amass wealth.                                                                                              , Mr Pomeroy said he does expect price appreciation to slow in coming months, as the central bank raises interest rates. The Canadian housing market is particularly susceptible to such moves, since many buyers rely on five-year mortgages rather than the long-term ones common in the US and UK., But higher interest rates will only make it less affordable for prospective buyers trying to break into the market, he warned.                                                                                                                                                                     , Mr Myers said over the long-term, he expects hot markets such as Toronto and Vancouver to become dominated by renters, as regular buyers get priced out of the market, unless politicians address supply.                                                                                          , But Mr Pomeroy said high development costs means that adding supply will not necessarily reduce prices, unless the additions are dramatic.                                                                                                                                                         , "Unless you've got born into the right family ... the prospects for young buyers are quite dim," he said.                                                                                                                                                                                          , Inside Thatcher and Reagan's close political relationship                                                                                                                                                                                                                                          , What did Putin do before he came to power?                                                                                                                                                                                                                                                         , Romesh Ranganathan investigates the musician's death                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/canada-to-boost-short-term-debt-sales-cut-10-year-issuance?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-08 04:08:07 </td>
   <td style="text-align:left;"> Canada to Bolster Bill Sales as Bank of Canada Action Looms </td>
   <td style="text-align:left;"> Bloomberg Markets: China Open is the definitive guide to the markets in Hong Kong and on the mainland. David Ingles and Yvonne Man bring you the latest news and analysis to get you ready for the trading day.                           , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Mocked as ‘Rubble’ by Biden, Russia’s Ruble Roars Back                                                                                                                                                                                    , Puerto Rico Power Slowly Being Restored After Massive Outage                                                                                                                                                                              , Amazon Union Vote in Alabama Challenged Again by Labor Group                                                                                                                                                                              , Apple Push Into Baseball Includes Elevating Female Broadcasters                                                                                                                                                                           , Atlassian Sets Long-Term Sales Goal of $10 Billion a Year                                                                                                                                                                                 , Senator Tim Kaine Says Putin Should Be Put on Trial in the Hague                                                                                                                                                                          , Australia to Send Combat Vehicles to Ukraine After Leader’s Plea                                                                                                                                                                          , Trudeau Taxes Speculators to Cool World’s Hottest Housing Market                                                                                                                                                                          , Giannis Antetokounmpo Put His Money in 50 Banks Until Bucks Owner Helped Him Invest                                                                                                                                                       , Sarah Jessica Parker Sidelined as Broadway Fights Virus                                                                                                                                                                                   , GM Electric Hummer Review: $110,000 Worth of Armor, With Soft Spots                                                                                                                                                                       , The Street Has Spoken. Will Sri Lanka’s Strongmen Listen?                                                                                                                                                                                 , China’s Leaders Refuse to Take Covid ‘Lying Flat’                                                                                                                                                                                         , Singapore and Malaysia Reunite, If Only for Cake                                                                                                                                                                                          , The TikTok War Didn’t Cause the TikTok Boom                                                                                                                                                                                               , Swap In a Triangle Conference Table for an Ideal Hybrid Meeting                                                                                                                                                                           , This Is the Red-Hot Center of the Tightest Job Market Since WWII                                                                                                                                                                          , Australia Should Consider Human Rights in Slavery Law Review                                                                                                                                                                              , Politicians Say the Supreme Court Confirmation Process Is Broken. Here’s Why                                                                                                                                                              , Book Bans Targeted More Than 1,100 Titles Since July                                                                                                                                                                                      , Japan Considers Cutting Russia Coal Imports in Shift of Position                                                                                                                                                                          , NOAA: Potent Heat-trapping Methane Increases At Record Pace                                                                                                                                                                               , 500 New Mothers in New York Will Soon Get Monthly Cash                                                                                                                                                                                    , Illinois’s Shady Political Image Weighs on Appeal of its Debt                                                                                                                                                                             , It’s Time for a Net Zero Building Boom                                                                                                                                                                                                    , Wonky SEC Ruling Reignites Spot U.S. Bitcoin ETF Approval Debate                                                                                                                                                                          , Thiel Blasts Dimon, Buffett and Fink as ‘Finance Gerontocracy’ at Bitcoin 2022                                                                                                                                                            , Robinhood Rolls Out Cryptocurrency Wallet to 2 Million Users                                                                                                                                                                              , Esteban Duarte                                                                                                                                                                                                                            , Canada plans to increase sales of short-term debt this fiscal year, even as government finances improve and overall debt issuance declines for the second year in a row.                                                                  , The federal government plans to increase the stock of treasury bills by 14% to C$213 billion ($169 billion), according the documents released as part of Finance Minister Chrystia Freeland’s budget on Thursday.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 04:08:00 </td>
   <td style="text-align:left;"> Canada Stocks Snap 3-Day Losing Streak </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, rose 0.2% to close at 21,835 on Thursday, slightly up from a three-week low of 21,789 reached in the prior session. Gains in the energy and materials sectors offset some of the losses from the financials, healthcare and tech stocks. Meanwhile, investors weighed the prospect of a more aggressive monetary policy tightening by the Fed, uncertainty around the Russia-Ukraine peace talks and tougher sanctions on Russia. On the domestic front, Canada's ruling Liberals will present their 2022 budget later in the day, with Prime Minister Justin Trudeau under pressure to pull back from fresh spending as it could exacerbate already strong inflationary pressures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-ends-87-points-higher/story.aspx?guid={EE1C1D33-792F-4A76-85B8-7D195DE215B1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 04:05:40 </td>
   <td style="text-align:left;"> Dow ends 87 points higher as stocks bounce after back-to-back declines - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended with small gains Thursday, bouncing modestly after back-to-back declines tied to worries about the Federal Reserve's plans to continue tightening monetary policy. The Dow Jones Industrial Average 
        DJIA,
        +0.25%
       closed around 87 points higher, up 0.3%, near 34,584, according to preliminary figures, while the S&amp;P 500 
        SPX,
        +0.43%
       rose around 19 points, or 0.4%, to finish near 4,500. The Nasdaq Composite, which bore the brunt of the 2-day pullback, eked out a gain of around 8 points, or 0.1%, to close near 13,897. Minutes of the Fed's March policy meeting on Wednesday showed that policy makers aim to run $95 billion of securities off its balance sheet monthly after a three-month phase-in, while affirming that policy makers were open to raising rates in half-point increments in future meetings., Oil executives said during a House panel meeting Wednesday that their companies do not set prices for oil and gasoline, even as consumers across the country allege gasoline price gouging at the pump, where drivers last month paid record-high prices per gallon for the fuel. But experts have a reasonable explanation for the climb.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/glenn-greenwald-edward-snowden-happiest-person </td>
   <td style="text-align:left;"> 2022-04-08 03:50:39 </td>
   <td style="text-align:left;"> Glenn Greenwald says Edward Snowden is the 'happiest person' he's 'ever met' at bitcoin conference </td>
   <td style="text-align:left;"> Check out what's clicking on Foxbusiness.com.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , MIAMI – Journalist Glenn Greenwald said Thursday that Edward Snowden is the "happiest person" he's "ever met" at the Bitcoin 2022 conference during a panel that linked the cryptocurrency to libertarian and third-party ideals.                                                                                                                                                                                                                                                                                     , "When people ask me who's the happiest person I know, I always say it's Edward Snowden — even though he's an exile in a country he never chose to be in for eight years, and probably the rest of his life," Greenwald said to applause from the audience. "Because every day that he puts his head on the pillow to sleep, he knows that when faced with the choice of what he was going to be and what he was going to do, he made the right choice, and there's just no substitute for that in terms of happiness.", Greenwald, who notably broke the Snowden-NSA civilian surveillance story for The Guardian in 2013, recalled that when he first met the former NSA agent in Hong Kong, he expected an "old, ragged, national security guy in his 60s" who had already fulfilled his life goals. In reality, Snowden was very different from what Greenwald had envisioned during their online correspondence.                                                                                                                          , Glenn Greenwald speaks during the Bitcoin 2022 conference (Audrey Conklin / Fox News)                                                                                                                                                                                                                                                                                                                                                                                                                                 , "When he walked up to me and my colleague … he looked like a kid out of a video store … and I was shocked," Greenwald said while answering a question. "And I spent that whole first day trying to figure out why somebody like this, who has his whole life ahead of him — who had a very good job for Booz Allen making a lot of money, had a girlfriend who loved him, a family that was supportive — why would somebody like that be willing to risk their entire life?                                           , BITCOIN TRADES AROUND $43,000 AS MIAMI CONFERENCE GETS UNDERWAY                                                                                                                                                                                                                                                                                                                                                                                                                                                       , "He ultimately said to me, ‘You know we’re all going to die, and the only question really is, how are we going to live?'"                                                                                                                                                                                                                                                                                                                                                                                             , Bitcoin 2022 conference entrance (Audrey Conklin / Fox News)                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The journalist recalled the meeting as "a really profound experience."                                                                                                                                                                                                                                                                                                                                                                                                                                                , Greenwald's reporting won a Pulitzer Prize for public service in 2014. A film based on his reporting, "Citizenfour" by Laura Poitras, won an Oscar.                                                                                                                                                                                                                                                                                                                                                                   , AARON RODGERS, SERENA WILLIAMS, ODELL BECKHAM JR. TALK BITCOIN AT CONFERENCE: ‘I’M BETTING ON BITCOIN'                                                                                                                                                                                                                                                                                                                                                                                                                , "My life changed in a lot of ways that I had never expected," Greenwald said. "Doors flew open. There's a huge kind of incentive system that's designed to kind of co-opt you. They offer you a lot of money to go to these events. You sit at cocktail parties with people you've accused of being war criminals, who you believe are war criminals, and suddenly, all of these incentives are supposed to lure you out of this dissident space."                                                                    , Bitcoin bull at Bitcoin 2022 conference entryway  (Audrey Conklin / Fox News)                                                                                                                                                                                                                                                                                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , That experience, he said, made him unafraid to dissent from the norm and voice support for ideas — like bitcoin — that are often criticized by high-profile figures.                                                                                                                                                                                                                                                                                                                                                  , An estimated 25,000 people attended the Bitcoin 2022 conference in South Beach, Miami, to learn more about cryptocurrency and fintech companies, network with like-minded individuals and discuss the future of bitcoin as a more mainstream form of currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 03:30:00 </td>
   <td style="text-align:left;"> US Stocks Rebound </td>
   <td style="text-align:left;"> All major US indices turned positive in the last hour of trading on Thursday, recovering from two days of losses as investors took advantage of lower valuations, priced in a more hawkish stance from the Federal Reserve, and shrugged off sanctions on Russia. The Dow finished the session more than 87 points higher, after dropping as much as 300 points earlier in the session and the S&amp;P 500 and Nasdaq advanced 0.4% and 0.1%, respectively. In terms of individual share price movement, shares of HP Inc jumped around 15% after Warren Buffett’s Berkshire Hathaway disclosed a stake in the tech hardware maker. Investors also continued to bet on equities with stable earnings and dividends like consumer staples and health care with Costco and Pfizer rising more than 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/industrial-production </td>
   <td style="text-align:left;"> 2022-04-08 03:21:00 </td>
   <td style="text-align:left;"> Argentina Industrial Output Rebounds Sharply in February </td>
   <td style="text-align:left;"> Industrial production in Argentina climbed by 8.7 percent year-on-year in February of 2022, swinging from the upwardly revised 0.8 percent decrease in the previous month. Output grew primarily for vehicles &amp; parts (31.6 percent); textiles, leather, &amp; footwear (22.9 percent); basic metal industries (16.1 percent) and wood, paper &amp; printing products (10.1 percent). On a seasonally adjusted monthly basis, industrial production rose 4 percent, compared to an upwardly revised 6.2 percent slump in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/consumer-credit </td>
   <td style="text-align:left;"> 2022-04-08 03:06:00 </td>
   <td style="text-align:left;"> US Consumer Credit Growth Hits Highest Since 2010 </td>
   <td style="text-align:left;"> Consumer credit in the United States increased by USD 41.82 billion in February of 2022, up from an upwardly revised USD 8.93 billion gain in the prior month, and well above market expectations of a USD 16.65 billion rise. It was the biggest monthly gain in consumer credit since December of 2010, as non-revolving credit went up by USD 23.82 billion while revolving credit increased by USD 18 billion. On an annual basis, consumer credit grew 11.3 percent, following an upwardly revised 2.4 percent increase in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/wework-ceo-mathranis-total-2021/story.aspx?guid={991E58AE-3125-4BCB-84A8-4F76BE4E9EBF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 03:01:41 </td>
   <td style="text-align:left;"> WeWork CEO Mathrani's total 2021 compensation is nearly triple the year before - MarketWatch </td>
   <td style="text-align:left;"> WeWork Inc. 
        WE,
        -5.18%
       disclosed Thursday that Chief Executive Sandeep Mathrani total compensation for 2021 was nearly triple that of 2020, boosted by more than $19 million in cash bonuses and stock awards. Mathrani became CEO of WeWork in February 2020, and chairman in March 2022. In the co-working space rental company's 2021 proxy statement, the company said Mathrani's total compensation last year was $21.31 million, including $1.50 million in salary, a $10.75 million cash incentive bonus and $8.72 million in stock awards. There were also option awards valued at $332,294 and all other compensation of $1,800. That compares with 2020 total compensation of $7.54 million, which included $1.28 million in salary, a $1.50 million cash bonus, no stock awards and $4.76 million worth of option awards. Shares of WeWork, which went public in October 2021 after its merger with special purpose acquisition company (SPAC) BowX Acquisition Corp. closed, dropped 4.6% in afternoon trading. They have sunk 27.2% year to date, while the S&amp;P 500 
        SPX,
        +0.43%
       has slipped 5.5%., Twitter Inc. may have avoided a hostile takeover by Elon Musk by letting him on the board, but what kind of changes will Musk bring?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/07/europe/ukraine-russian-intercepts-killing-civilians-germany-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-08 02:54:38 </td>
   <td style="text-align:left;"> Russian troops discussed killing Ukrainian civilians in radio transmissions intercepted by Germany, source says - CNN </td>
   <td style="text-align:left;"> (CNN)Germany's foreign intelligence service told a parliamentary committee Wednesday that it has intercepted radio communications where Russian soldiers talked about shooting soldiers and civilians in Ukraine, a source with knowledge of the meeting said.                                                                       , The briefing was the top item at the Wednesday meeting, the source added.                                                                                                                                                                                                                                                             , Those intelligence findings -- first reported by Der Spiegel -- appear to implicate Russian troops in a pattern of apparent war crimes despite denials from Moscow, most recently in the indiscriminate killing of civilians in the Kyiv suburb of Bucha.                                                                             , Der Spiegel reported that the BND, Germany's foreign intelligence agency, intercepted Russian radio chatter about the killing of civilians in Bucha, and that some of the conversations could be tied directly to specific killings in Bucha that have been documented since news first emerged of an apparent massacre there.        , German intelligence has satellite images that point to the involvement of Russian troops in the Bucha killings, the Washington Post reported, citing an unnamed intelligence official, though the paper said the radio transmissions have not been linked to that location.                                                           , News of the German intelligence assessment comes amid massive international outrage over Bucha and a growing body of evidence that points to the Russian military's involvement in the indiscriminate killing of civilians in Ukraine.                                                                                                ,                                                                                                                                                                                                                                                                                                                                       , A drone video taken before March 10 has captured the moment a person riding a bicycle is gunned down on a street in Bucha by Russian soldiers. International media have broadcast extensive footage of that same street, where the bodies of at least 20 civilian men were found following the exit of Russian forces from the area.  , Germany's foreign intelligence office declined to comment, and a German government spokesperson declined to comment on the Der Spiegel reporting.                                                                                                                                                                                     , The German intercepts are not the first audio evidence that indicates Russian troops have engaged in the murder of civilians.                                                                                                                                                                                                         , On Tuesday, the Security Service of Ukraine released a series of intercepted audio recordings that purport to reveal Russians receiving orders to kill civilians.                                                                                                                                                                     , In one of the alleged intercepts, one soldier identifies what he describes as a car carrying two civilians.                                                                                                                                                                                                                           , "F**king kill them all, for f**k's sake!" comes the reply.                                                                                                                                                                                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/07/europe/ukraine-execution-russian-prisoner-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-08 02:54:20 </td>
   <td style="text-align:left;"> Video appears to show execution of Russian prisoner by Ukrainian forces - CNN </td>
   <td style="text-align:left;"> Lviv, Ukraine (CNN)CNN has geolocated a recent video that appears to show the execution of a Russian prisoner by Ukrainian forces following recent fighting in the Kyiv region.                                                                                                                                                                                                                                                                                                                                                        , The video -- first verified by the New York Times -- shows a group of soldiers with Ukrainian patches and blue arm bands on a road following a firefight. The bodies of at least four men in Russian uniform are lying on the pavement. Three of them have head wounds and blood is pooled around the body of a fourth, who has a jacket pulled over his head and seems to be rasping.                                                                                                                                                 , "He's still alive," says one man, in Russian. "He's gasping."                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , A soldier points a rifle and fires two shots at the body, pauses, then fires another. The body stops moving.                                                                                                                                                                                                                                                                                                                                                                                                                           , A person narrating to the camera then turns to film a Russian infantry fighting vehicle with a "V" marking similar to that seen on Russian military hardware operated by many units in Ukraine. "A little trophy," the man says.                                                                                                                                                                                                                                                                                                       , Someone off camera says, "Slava Ukrayini!" -- glory to Ukraine, a patriotic greeting, and a bearded man steps in the frame and replies, "Glory the heroes," the standard reply.                                                                                                                                                                                                                                                                                                                                                        , The exact time and date of the video, which appeared on a pro-Russian Telegram channel, is unclear. The location of the video matches that of a video published on Twitter by Ukraine's Ministry of Defense. That video, posted on April 2, shows a blasted Russian armored column. "Handiwork of Ukrainian defenders in the Kyiv region," the caption reads.                                                                                                                                                                          , A different video of the scene, filmed from a different angle, appeared on the Telegram channel of UNIAN, a Ukrainian news agency, on March 30. It shows the same bearded man and the caption says the video shows the Georgian Legion, a group of volunteers fighting on the Ukrainian side, in an operation to clear the Kyiv region of Russian troops.                                                                                                                                                                              , The video of the purported execution comes days after horrific images emerged of the apparent slaughter of civilians by Russian forces in the Kyiv suburb of Bucha.                                                                                                                                                                                                                                                                                                                                                                    , Asked about the video at a NATO press conference in Brussels, Ukrainian Minister of Foreign Affairs Dmytro Kuleba said, "I haven't seen it. I heard about it. I want to reassure you that Ukrainian army observes the rules of warfare."                                                                                                                                                                                                                                                                                               , Kuleba added, "There might be isolated incidents of the violation of these rules and they will be definitely investigated. But I wanted to double check the date of this of this video, because you should understand one thing now (or) you will not understand it. I'm sorry, but you don't understand how it feels after seeing pictures on Bucha. Talking to people who escaped, knowing that that person you know was raped four days in a row. And when she finally made it to Kyiv, she was directly taken to the psychiatrist.", "This is not an excuse to those who violate the rules of warfare on either side or the frontline," Kuleba continued. "But there are some things which we simply can't understand."                                                                                                                                                                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/natural-gas-futures-end-highest-since/story.aspx?guid={10542C9E-3569-46E6-BAF1-C69320A7C316}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 02:45:49 </td>
   <td style="text-align:left;"> Natural-gas futures end at highest since 2008; oil settles lower - MarketWatch </td>
   <td style="text-align:left;"> Natural-gas prices climbed by more than 5% on Thursday to settle at their highest since December 2008, buoyed by tight supplies, while oil prices edged down to finish with a modest loss. The Energy Information Administration reported Thursday that U.S. natural-gas supplies fell 33 billion cubic feet for the week ended April 1. That compares with a five-year average increase of 8 billion for the week, according to S&amp;P Global Commodity Insights. May natural gas 
        NGK22,
        +0.35%
       rose 33 cents, or 5.5%, to settle at $6.359 per million British thermal units, the highest front-month contract settlement since December 2008, FactSet data show. May West Texas Intermediate crude 
        clh22
       fell 20 cents, or 0.2%, to settle at $96.03.96 a barrel, after settling 5.6% lower on Wednesday., For an investor with a value bent, the maker of PCs and printer fits the bill: HP shares trade for just eight times projected earnings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/beyond-meat-begin-selling-2000/story.aspx?guid={3046D923-A050-4C51-8383-69825062D37E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 02:45:41 </td>
   <td style="text-align:left;"> Beyond Meat to begin selling at 2,000 Rite Aid locations - MarketWatch </td>
   <td style="text-align:left;"> Beyond Meat Inc. 
        BYND,
        +0.87%
       announced Thursday that Beyond Meatballs and the Beyond Burger product will be available at about 2,000 Rite Aid Corp. 
        RAD,
        -17.18%
       locations around the country. The pharmacy retailer is the latest addition to a long list of restaurant chains and retailers that carry the plant-based meat company's products. The U.S. plant-based food market has grown to $7.4 billion. The news also comes as analysts grow increasingly bearish about Rite Aid's prospects, with Deutsche Bank downgrading the company's stock rating to sell and slashing its price target to $1 from $16. Rite Aid's stock plunged nearly 22% on Thursday, and is down 69% over the last year. Beyond Meat is down nearly 67% for the past 12 months., For an investor with a value bent, the maker of PCs and printer fits the bill: HP shares trade for just eight times projected earnings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-08 02:09:00 </td>
   <td style="text-align:left;"> US Natural Gas Rises by 6% </td>
   <td style="text-align:left;"> US natural gas futures rose again to almost $6.4 per million British thermal units, closing on the highest level since 2014, on solid demand prospects. On Thursday night, European Union countries agreed to ban coal imports from Russia and pledged to start working on an embargo on Russian oil, gas and nuclear fuel, putting additional pressure on energy markets. The LNG shipments to Europe are already at record levels and the US is facing greater pressure to help Europe secure more supplies. Meanwhile, US inventory data showed utilities pulled a more-than-anticipated 33 bcf of natural gas from storage last week, reversing from a storage injection in the week before due to chilly temperatures at the end of March. Weather forecasts also pointed to wintry weather in parts of the US until mid-April, which could boost heating demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nuclear </td>
   <td style="text-align:left;"> 2022-04-08 02:01:10 </td>
   <td style="text-align:left;"> Nuclear Energy Index Hits All-time High </td>
   <td style="text-align:left;"> Nuclear Energy Index increased to an all-time high of 1500 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/costa-rica/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-08 01:57:07 </td>
   <td style="text-align:left;"> Costa Rica Inflation Rate Accelerates Further </td>
   <td style="text-align:left;"> The annual inflation rate in Costa Rica quickened for the third straight month to 5.79% in March of 2022, from 4.90% in the previous month. It was the steepest inflation rate since December of 2014, mainly driven by prices of transport (13.53% vs 11.33% in February) and food &amp; non-alcoholic beverages (9.55% vs 7.31%). On a monthly basis, consumer prices went up 0.88%, following a 1.09% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-log-highest-finish/story.aspx?guid={1175F484-391F-4228-B90C-5141B10ACD17}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 01:41:39 </td>
   <td style="text-align:left;"> Gold futures log highest finish in a week - MarketWatch </td>
   <td style="text-align:left;"> Gold futures on Thursday marked their highest settlement in a week, with geopolitical risks providing some underlying support for gold, said Edward Moya, senior market analyst at OANDA. "If the next round of sanctions from the [European Union] against Russia are hard-hitting, gold could have a meaningful rally out of its trading range," he said. June gold 
        GCM22,
        
       rose $14.70, or 0.8%, to settle at $1,937.80 an ounce, the highest most-active contract finish since March 31, FactSet data show. Prices have generally stuck to a $10 trading range since the beginning of April., Tesla is opening its new manufacturing plant in Austin, Texas, on Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/soaring-interest-rates-create-barrier-to-the-american-dream-to-own-a-home-former-investment-banker </td>
   <td style="text-align:left;"> 2022-04-08 01:26:05 </td>
   <td style="text-align:left;"> Soaring interest rates create 'barrier to the American dream': Former investment banker </td>
   <td style="text-align:left;"> Carol Roth, a former investment banker and author, argues a 'confluence of factors' pricing first time home buyer out of the market.                                                                                                                                                                                                         , Carol Roth, a former investment banker and author, argued Thursday that as soaring interest rates push mortgage demand down, a "barrier" is created to those pursuing the American Dream.                                                                                                                                                    , "We have such a confluence of factors that are really pricing that first-time homebuyer out of the market," Roth told "Cavuto: Coast to Coast" on Thursday.                                                                                                                                                                                  , "And everything the Fed has been doing has really been this transfer of wealth from Main Street to Wall Street and unfortunately, in the direction that they’re going, I think that with the increase of interest rates, it just, it is going to be that much more unaffordable and that much more of a barrier to the American Dream."      , A former investment banker argues 'a confluence of factors' are pricing the first-time homebuyer out of the market. (AP Photo/Elaine Thompson, File / AP Newsroom)                                                                                                                                                                           , HOUSING MARKET ‘STARING INTO FACE OF PERFECT STORM,’ EXPERT WARNS                                                                                                                                                                                                                                                                            , Roth made the comments one day after the minutes from the Federal Reserve's March meeting revealed that policymakers were signaling that surging inflation and an incredibly tight labor market could warrant a half-point interest rate hike at future meetings.                                                                            , Fox Business’ Gerri Willis discusses how the increase in home prices and decrease in inventory have deterred many homebuyers from purchasing on ‘The Claman Countdown.’                                                                                                                                                                      , Mortgage rates have increased 1.5 percentage points over the last three months alone, the fastest three-month rise in 28 years, according to Freddie Mac.                                                                                                                                                                                    , The Federal Home Loan Mortgage Corporation noted that the increase in mortgage rates has "softened purchase activity such that the monthly payment for those looking to buy a home has risen by at least 20 percent from a year ago."                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                  , The 30-year fixed-rate mortgage increased to 4.72% annual percentage rate (APR) as of April 7, according to Freddie Mac’s Primary Mortgage Market Survey. Last year, at the same time, the 30-year fixed-rate mortgage was 3.13%.                                                                                                            , It was revealed last week that home prices unexpectedly rose 19.2% year-over-year in January, according to the S&amp;P CoreLogic Case-Shiller Index, as limited supply and a race to lock in rising mortgage rates drove enticed buyers.                                                                                                         , Barron’s associate editor Andrew Bary weighs in on the real estate market and provides an outlook for home-improvement stocks.                                                                                                                                                                                                               , The 10-city composite saw an annual increase of 17.5% year-over-year in January, up from 17.1% the previous month, while the 20-city composite grew 19.1% year-over-year, up from 18.6% in the previous month. On a monthly basis, the 20-city index climbed 1.4% in January when non-seasonally adjusted and 1.8% when seasonally adjusted. , Sixteen of the 20 cities reported higher price increases in the year ending January 2022 versus the year ending December 2021, led by Phoenix, Tampa, and Miami.                                                                                                                                                                             , FOX Business’ Lucas Manfredi contributed to this report.                                                                                                                                                                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61027313?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-08 01:18:07 </td>
   <td style="text-align:left;"> Energy strategy: Boris Johnson defends plan amid cost of living crisis </td>
   <td style="text-align:left;"> The PM has defended the government's new energy strategy, following criticism it does little to help people struggling with soaring bills.                                                                                                                          , Boris Johnson said it was a "long-term plan" focused on energy supply and the government had already introduced other policies to tackle rising energy costs.                                                                                                       , The strategy, which aims to increase UK energy independence, includes plans to boost nuclear, wind and hydrogen power.                                                                                                                                              , But Labour said it was "too little, too late" to help with rising costs.                                                                                                                                                                                            , And experts called for a bigger focus on energy efficiency and insulation to help bring bills down.                                                                                                                                                                 , Consumers are facing huge increases in energy bills after the Russian invasion of Ukraine pushed gas prices even higher.                                                                                                                                            , Speaking at the Hinkley Point C nuclear power plant, Mr Johnson said the strategy was about "tackling the mistakes of the past and making sure that we are set well for the future".                                                                                , Citing policies including a £6bn energy efficiency fund and support for heat pumps, he said the government was "already doing a huge amount to help people with the immediate cost of living and of course we are going to do more".                                , Under the government's new plans, up to 95% of the UK's electricity could come from low-carbon sources by 2030.                                                                                                                                                     , There is a big focus on offshore wind, with a new target of producing up to 50 gigawatts (GW) of energy from this source by 2030. Officials said this would be more than enough to power every home in the UK.                                                      , The strategy says the government wants to "lead the world once again" in nuclear power, reversing what it describes as "decades of underinvestment".                                                                                                                , A new body called Great British Nuclear will be launched to bolster the UK's nuclear capacity, with the hope that by 2050 up to 24 GW of electricity will come from that source - 25% of the projected electricity demand.                                          , The government hopes to deliver up to eight new reactors, built on existing sites, with a new reactor approved each year until 2030.                                                                                                                                , Read more about what the strategy says here.                                                                                                                                                                                                                        , For onshore wind, the strategy commits to consulting on developing partnerships with "a limited number of supportive communities" who want to host wind turbines in exchange for guaranteed lower energy bills.                                                     , However, the strategy says there will be no "wholesale changes" to current planning regulations for onshore wind.                                                                                                                                                   , Although it is one of the cheapest forms of energy, new onshore wind projects have been declining since 2015 when the government ended subsidies and introduced stricter planning rules in response to some complaints that wind turbines were an eyesore and noisy., Defending the decision not to prioritise onshore wind, Prime Minister Boris Johnson said the UK already had about 30GW of onshore wind capacity.                                                                                                                    , He added that new sites "will have a very high bar to clear".                                                                                                                                                                                                       , Environmentalists and many energy experts have reacted with disbelief and anger at some of the measures in the strategy.                                                                                                                                            , They cannot believe the government has offered no new policies on saving energy by insulating buildings.                                                                                                                                                            , They say energy efficiency would immediately lower bills and emissions, and is the cheapest way to improve energy security.                                                                                                                                         , A Downing Street source said the strategy was now being seen as an energy supply strategy.                                                                                                                                                                          , Campaigners are also furious that ministers have committed to seeking more oil and gas in the North Sea, even though humans have already found enough fossil fuels to wreck the climate.                                                                            , There is a strong welcome, though, for the promise of more energy from wind offshore with speedier planning consent.                                                                                                                                                , The same boost has not been offered to onshore wind.                                                                                                                                                                                                                , The decision to boost nuclear has drawn a mixed reaction. Some environmentalists say it's too dear and too dangerous. They ridicule the idea from some politicians that every city could have its own mini reactor.                                                 , But other climate campaigners believe nuclear must be part of the energy mix.                                                                                                                                                                                       , Labour leader Sir Keir Starmer said the measures announced were not enough to tackle the cost-of-living crisis.                                                                                                                                                     , "All we've got today is a cobbled-together list of things that could and should have been done over the last 10 to 12 years and it doesn't even tackle really important things like insulating homes, which could save £400 on everybody's bill," he said.          , The former boss of energy regulator Ofgem, Dermot Nolan, said: "Most of these decisions will take a long time to have an impact and in the short run we will continue to be dependent on fossil fuels."                                                             , He said the lack of focus on energy efficiency, insulation and improving the quality of people's homes was "an opportunity missed".                                                                                                                                 , Asked in the Lords why the government was not spending more on improving the insulation of homes, a business minister suggested the Treasury was not willing to support this.                                                                                       , Lord Callanan told peers: "We're spending something like £6.6bn over the term of this Parliament on insulation schemes. It would have been good to go further but the Treasury wouldn't support it."                                                                , Green Party co-leader Adrian Ramsay said if the government was "concerned about energy bills and taking real climate action, it would be going even further on onshore wind".                                                                                       , Liberal Democrat leader Sir Ed Davey described the plans as "utterly hopeless", while the SNP's Stephen Flynn also called it a "missed opportunity".                                                                                                                , Dr Simon Cran-McGreehin, from the Energy and Climate Intelligence Unit, said the strategy was "underwhelming", describing the lack of funding to improve energy efficiency in homes as "an enormous gaping hole".                                                   , He added that there appeared to be "limited ambition" for onshore wind, despite it being "remarkably popular".                                                                                                                                                      , Inside Thatcher and Reagan's close political relationship                                                                                                                                                                                                           , What did Putin do before he came to power?                                                                                                                                                                                                                          , Romesh Ranganathan investigates the musician's death                                                                                                                                                                                                                , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 01:12:00 </td>
   <td style="text-align:left;"> South African Stocks Down for 4th Day </td>
   <td style="text-align:left;"> The JSE FTSE All Share Index fell 0.5% to close at 74,008 on Thursday, the lowest since March 16th, extending losses for the fourth session, led by commodity linked-sectors and tech sectors. Also, Tiger Brands and RMI Holdings dragged. Investors digested the possibility of more aggressive monetary tightening by the Federal Reserve and monitored the war in Ukraine. At the same time, the prospect of more stringent sanctions against Russia and Covid-19 extended lockdowns in Shanghai weighed on sentiment. On the domestic front, rating agency Moody's has maintained on Wednesday its negative outlook for Airports Company South Africa (ACSA), due to its debt burden, as well as uncertainties about prospects for a recovery in air traffic after the pandemic’s devastating impact. Moody's also kept the rating of Eskom at Caa1 with a negative outlook, warning that the power utility remains in a precarious position despite prolonged financial support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/07/stocks-making-the-biggest-moves-midday-hp-constellation-brands-cdk-global-and-more.html </td>
   <td style="text-align:left;"> 2022-04-08 00:56:51 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: HP, Constellation Brands, CDK Global and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                           , HP — Warren Buffett's Berkshire Hathaway became the largest shareholder in the computer hardware company, sending shares up 16.4%. Berkshire Hathaway bought nearly 121 million shares, or about an 11% stake worth roughly $4.2 billion based on Wednesday's closing.                                                                                                , Lamb Weston Holdings — Shares soared 6.2% after the food processing company reported quarterly earnings. Lamb Weston showed profit of 73 cents per share, beating consensus estimates of 44 cents. It reported revenues of $955 million, compared to analyst estimates of $969 million.                                                                               , Constellation Brands — The stock jumped 4.3% after the producer of beer, wine and spirits reported an earnings beat. Constellation saw earnings of $2.37 per share and revenues of $2.1 billion. Analysts expected earnings of $2.10 per share and revenues of $2.02 billion.                                                                                         , JD.com — News that founder Richard Liu stepped down from the CEO position sent shares down 4%. Liu will remain on as chair. Company President Xu Lei will take over as CEO.                                                                                                                                                                                           , Levi Strauss — Shares fell nearly 5% despite Levi's better-than-expected quarterly report. The jeans maker posted a quarterly profit of 46 cents per share on revenue of $1.59 billion. Analysts looked for earnings of 42 cents per share on revenue of $1.55 billion. Levi said supply chain constraints hurt sales by roughly $60 million during the latest period., Costco — The big-box retail chain jumped 3.2%, a day after it reported robust same-store sales in March, which jumped 17.2% in the last five weeks ending April 3.                                                                                                                                                                                                    , CDK Global — Shares jumped 11.4% after the provider of automotive retail technology agreed to be acquired by Brookfield Business Partners in an $8.3 billion deal. CDK Global shareholders will get $54.87 per share in cash, implying a 12% premium over Wednesday's closing price for CDK.                                                                          , Ford — The automaker dropped 5.2% after Barclays downgraded Ford to equal weight from overweight. The ongoing semiconductor shortage will keep Ford from rebounding after a rough start to 2022, Barclays said in a note to clients.                                                                                                                                  , — CNBC's Hannah Miao and Jesse Pound contributed reporting.                                                                                                                                                                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/07/here-are-the-signs-the-job-market-is-hot-for-workers.html </td>
   <td style="text-align:left;"> 2022-04-08 00:55:19 </td>
   <td style="text-align:left;"> Here are the signs the job market is hot for workers </td>
   <td style="text-align:left;"> , Claims for unemployment insurance last week fell to their lowest level in more than 50 years — yet another sign workers are reaping the benefits of a hot labor market.                                                                                                                                                                                               , Americans filed 166,000 initial claims for jobless benefits in the week ended April 2, the Labor Department said Thursday. Initial claims are a proxy for layoffs.                                                                                                                                                                                                    , The figure is a pandemic-era low. It also nearly ties the all-time trough.                                                                                                                                                                                                                                                                                            , The Labor Department began tracking jobless claims in 1967. Since then, just one other week in history has seen fewer claims for benefits: 162,000 in November 1968.                                                                                                                                                                                                  , However, today's labor force is over double its size in 1968 (about 79 million people versus 164 million), making last week's milestone noteworthy on a proportional basis.                                                                                                                                                                                           , "Employers appear to be holding on to their workers very tightly, as affirmed by the latest look at new jobless claims," according to Mark Hamrick, senior economic analyst at Bankrate.                                                                                                                                                                              , Other federal data indicate a strong labor market for workers, too.                                                                                                                                                                                                                                                                                                   , Job openings and the number of people who leave their job voluntarily each remain near record-high levels set at the end of 2021.                                                                                                                                                                                                                                     , Many have left their jobs for other opportunities amid the high demand for labor and for a big bump in pay. Annual wage growth has been higher than at any point in over 20 years, according to economists at Indeed, a job site, as employers compete for talent.                                                                                                    , The rate at which businesses are laying off workers is also near a record low as businesses try to hold onto their staff.                                                                                                                                                                                                                                             , The national unemployment rate — 3.6% in March — is approaching historic lows, too. It has fallen near the 3.5% prepandemic rate in February 2020, which had been the lowest unemployment rate since December 1969.                                                                                                                                                   , Workers on the sidelines have rejoined the labor force at a fast clip in recent months, according to Jim Baird, chief investment officer at Plante Moran Financial Advisors.                                                                                                                                                                                          , More from Personal Finance:3 ways to avoid taking on too much student loan debtWhat to do if you don't get a 401(k) plan at workDemand for used cars drops but high prices aren't budging                                                                                                                                                                             , More than 2.1 million workers have come back in the last three months alone, providing a "fresh pool of available workers to fuel continued job creation," he said.                                                                                                                                                                                                   , "Demand for labor remains strong and layoffs should remain low as employers struggle to fill near-record openings," Baird added.                                                                                                                                                                                                                                      , While the U.S. economy hasn't yet fully regained all the 22 million jobs lost in the early months of the pandemic, the rapid pace of job creation puts the country on a trajectory to regain them in June (if the current trend holds).                                                                                                                               , However, there are headwinds that may have a dampening effect on the labor market.                                                                                                                                                                                                                                                                                    , The Federal Reserve, the U.S. central bank, in March began a cycle of raising its benchmark interest rate to cool the economy and rein in inflation. Higher rates make it more expensive for consumers and businesses to borrow money.                                                                                                                                , And inflation, which is running at a 40-year high, is pushing up prices for goods and services across the economy. The average person has seen rising costs eclipse their wage growth, eroding purchasing power. (This isn't true for all workers, though, such as nonsupervisory workers in bars and restaurants, whose wage growth has risen faster than inflation.), Treasury Secretary Janet Yellen also warned Wednesday that Russia's attack on Ukraine "will have enormous economic repercussions for the world."                                                                                                                                                                                                                      , These challenges will test households and businesses in coming months, Hamrick said.                                                                                                                                                                                                                                                                                  , "That [unemployment] claims remain so low at a time of such turmoil suggests that, for now at least, the economy is holding up in the face of soaring crude oil, gasoline and other prices," Hamrick said. "How long this can persist remains to be seen."                                                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/u-s-industries-hurt-chinese-dumping-payout </td>
   <td style="text-align:left;"> 2022-04-08 00:48:41 </td>
   <td style="text-align:left;"> US industries hurt by Chinese 'dumping' could get more of a payout </td>
   <td style="text-align:left;"> A group of US senators is trying to get the federal government to hand over millions of dollars collected from China as a penalty for flooding markets with cheap products.                                                                                                                                                                                                                                                         , WESTWEGO, La. — A group of U.S. senators is trying to get the federal government to hand over millions of dollars collected from China as a penalty for flooding markets with cheap products.                                                                                                                                                                                                                                       , If it works out, some American companies could be in for a payout.                                                                                                                                                                                                                                                                                                                                                                  , Among them are folks in Louisiana's crawfish industry.                                                                                                                                                                                                                                                                                                                                                                              , Crawfish peelers at Bayou Land Seafood peel about 1,500 lbs of tail meat in a day during crawfish season.  (Fox News / Fox News)                                                                                                                                                                                                                                                                                                    , If you ask anyone who lives on the bayous, they'll tell you there is no Louisiana without crawfish.                                                                                                                                                                                                                                                                                                                                 , "It's part of the culture, just like the French language and Cajun music," said Adam Johnson of Bayou Land Seafood. "Crawfish and Cajun music, you can't get better than that."                                                                                                                                                                                                                                                     , But over 20 years ago, the industry was almost wiped out by Chinese crawfish flooding the market. It's known as "dumping," when other countries sell products in the U.S. below the cost of production.                                                                                                                                                                                                                             , CHINA ‘PREPARING FOR WAR’ WITH US, ASIA BY PARTNERING WITH RUSSIA, EXPERT WARNS                                                                                                                                                                                                                                                                                                                                                     , "It was coming in at $2 a pound or less in some cases," said Karl Turner with A La Carte Specialty Foods. "There was negative market share and unfair competition for Louisiana crawfish farmers."                                                                                                                                                                                                                                  , Crawfish (Fox News / Fox News)                                                                                                                                                                                                                                                                                                                                                                                                      , "I wasn't making money on it," added Johnson. "If I was making money, it wasn't enough to pay for the insurance and the overhead and the risk of creating a food item."                                                                                                                                                                                                                                                             , Congress found the practice illegal and in 2000 passed legislation requiring all anti-dumping tariffs to be paid to the U.S. producers who were affected. The latest Senate bill on the matter claims administrative delays are keeping Americans from seeing that money.                                                                                                                                                           , The bill, the China Trade Cheating Restitution Act, was introduced by Republican U.S. Sen. Bill Cassidy of Louisiana in partnership with senators Jon Tester, D-Mont.; Chuck Grassley, R-Iowa; and John Thune, R-S.D. It directs Customs and Border Protection (CBP) to pay $38.5 million from the interest on anti-dumping duties received from Chinese imports to several agricultural industries harmed by the illegal practice. , The funding would include $10.6 million for crawfish producers.                                                                                                                                                                                                                                                                                                                                                                     , FISH FRY PRICES RISE IN US DUE TO SUPPLY ISSUES                                                                                                                                                                                                                                                                                                                                                                                     , "Crawfish is part of our culture in Louisiana, and we will defend it," Cassidy said in a release. "China is attempting to put our crawfish industry out of business by dumping their product in the U.S. at prices below the cost of production. This is against the law. This legislation gives American processors the resources they need to stay competitive and thrive."                                                       , Others that would benefit include American honey, garlic and mushroom producers.                                                                                                                                                                                                                                                                                                                                                    , "Hopefully this money will be used to reinvest into the plants — into the operations — to become more efficient and more competitive so that we can compete against foreign producers," Turner said.                                                                                                                                                                                                                                , BUSINESS GROUPS CALL ON BIDEN TO RESTART TRADE TALKS WITH CHINA                                                                                                                                                                                                                                                                                                                                                                     , Crawfish (Fox News  / Fox News)                                                                                                                                                                                                                                                                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                         , While many crawfish producers agree that China is their biggest competitor, they also say that finding seasonal workers is their biggest challenge right now.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/congress-ban-stock-trade-lawmakers </td>
   <td style="text-align:left;"> 2022-04-08 00:46:25 </td>
   <td style="text-align:left;"> Congress renews push to ban stock trades among lawmakers </td>
   <td style="text-align:left;"> Utah Rep. Chris Stewart weighs in on reports that President Biden's team pulled support of ban on members of Congress stock-trading in SOTU on 'The Evening Edit.'                                                                                                                                             , A handful of Democratic senators are making a renewed push to pass legislation banning members of Congress from trading individual stocks while in elective office.                                                                                                                                            , Sens. Jeff Merkley of Oregon and Jon Ossoff of Georgia are leading a last-ditch effort to pass some type of congressional stock trading ban before the year ends. Lawmakers have introduced several different proposals, but there is no consensus on what the latest measure should look like.                , Merkley and Ossoff, along with Sens. Kirsten Gillibrand, D-N.Y., Elizabeth Warren, D-Mass., Gary Peters, D-Mich., Sherrod Brown, D-Ohio, and Mark Kelly, D-Ariz., are participating in a working group to craft consensus legislation, The Hill reported on Thursday.                                          , ELIZABETH WARREN DEMANDS POWELL RELEASE MORE DETAILS ABOUT FED TRADING SCANDAL                                                                                                                                                                                                                                 , The House and Senate are both leaving for a two-week recess that begins on Friday. Merkley has suggested that he wants to use the recess to establish more support in the hopes of getting a bill to the floor and passed before Memorial Day.                                                                 , Although there is generally a broad consensus among both Democrats and Republicans that there should be some additional limits in place on trading by members of Congress, lawmakers differ fiercely on how to approach the matter.                                                                            , House Speaker Nancy Pelosi, once a staunch opponent of such restrictions, and House GOP Leader Kevin McCarthy have both indicated they are open to installing some parameters – or outright bans – on lawmakers' ability to trade individual stocks when they are in public office.                            , Sen. Jon Ossoff (D-GA) questions Treasury Secretary Janet Yellen and Federal Reserve Chairman Jerome Powell during a Senate Banking, Housing and Urban Affairs Committee hearing on the CARES Act, at the Hart Senate Office Building on September 28, 202 (Photo by Kevin Dietsch/Getty Images / Getty Images), Lawmakers are rushing to reach an agreement before August, when their attention will shift to midterm elections, that will update a 2012 law that currently governs public disclosure and stock trading.                                                                                                       , Under the STOCK Act, it's illegal for members of Congress and their families to profit from inside information and it requires lawmakers to report stock trades to Congress within 45 days. In some recent cases, lawmakers have failed to report their trades altogether.                                     , There is also a growing number of Republicans who are lining up against new restrictions on stock trading. Key GOP lawmakers on the Committee on House Administration expressed concern, or opposition, during a three-hour hearing on Thursday centered around banning stock trades.                          , Rep. Rodney Davis, the committee's ranking Republican, said that certain measures requiring lawmakers to use qualified blind trusts to avoid potential conflicts of interest could be expensive and time-consuming.                                                                                            , "I just don't believe that forcing middle-class members to divest their ownership portion of a family farm or to divest ownership in a business that their spouse may be a part of or their dependent children be a part of," Davis, R-Ill., said. "I just think it's untenable."                              , Trading restrictions for members of Congress became popular earlier this year after Pelosi's husband, Paul Pelosi, drew scrutiny for his own investments and holdings.                                                                                                                                         , Speaker of the House Nancy Pelosi, D-Calif., meets with reporters to discuss President Joe Biden's domestic agenda including passing a bipartisan infrastructure bill and pushing through a Democrats-only expansion of the social safety net, the at the  (AP Photo/J. Scott Applewhite / AP Newsroom)        , Although Pelosi does not own any stock herself, her husband holds tens of millions of dollars worth of stocks and options in companies like Apple, Disney, Amazon and Google. Lawmakers' spouses are allowed to trade in companies or industries that their partner may help regulate.                         , Pelosi is worth an estimated $114 million, according to her 2018 personal financial disclosure, making her the sixth-richest member of the House and the 10th richest member of Congress, according to data tracked by the Center for Responsive Politics.                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                    , The California Democrat initially insisted that members of Congress should be allowed to trade stocks if they choose to do so, telling reporters that lawmakers should be allowed to participate in the "free market economy."                                                                                 , Facing immense pressure from her colleagues, however, Pelosi later did an about-face, suggesting that she would consider proposals banning members of Congress from trading stocks while in elective office.                                                                                                   , "I've said to the House Administration Committee, review all the bills that are coming in and see which ones — where the support is in our caucus," Pelosi said in January. "If members want to do that, I'm OK with that." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/07/europe/russia-eastern-ukraine-strategy-explainer-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-08 00:42:59 </td>
   <td style="text-align:left;"> Donbas: What is Putin's plan for eastern Ukraine?  - CNN </td>
   <td style="text-align:left;"> (CNN)As Russia's war in Ukraine enters a pivotal new phase, fighting is intensifying in the east of the country and officials have warned of a battle that "will remind you of the Second World War."                                                                                                                                                                                                                                                     , Ukrainian Foreign Minister Dmytro Kuleba said Thursday that fighting in the Donbas region of eastern Ukraine was ramping up but that it "has not reached its maximum scale."                                                                                                                                                                                                                                                                               , "The battle for Donbas will remind you of the Second World War, with large operations, maneuvers, involvement of thousands of tanks, armored vehicles, planes, artillery. This will not be a local operation based on what we see in Russia's preparations," Kuleba said at a news conference in Brussels.                                                                                                                                                 , "Russia has its plan, we have ours, and the battlefield will decide the outcome," he added.                                                                                                                                                                                                                                                                                                                                                                , Over the next few weeks, officials expect Russian forces to resupply and reposition with the aim of launching a brutal new offensive in Donbas, which encompasses the Luhansk and Donetsk regions, NATO Secretary General Jens Stoltenberg said on Tuesday.                                                                                                                                                                                                , "We now see a significant movement of troops away from Kyiv to regroup, re-arm and re-supply, and a shift in focus to the east," he told reporters in Brussels."This is a crucial phase of the war."                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Already, much of the region has come under an unrelenting assault. Russian forces are trying to wipe the besieged southeastern city of Mariupol "off the face of the earth," a Ukrainian military commander currently in Mariupol told CNN on Wednesday night.                                                                                                                                                                                             , Serhiy Volyna, Deputy Commander of the Marine Battalion in Mariupol, who has been fighting in the region since 2014, when Russia annexed Crimea, called the situation "critical."                                                                                                                                                                                                                                                                          , "It is a humanitarian catastrophe. The military that were involved in active hostilities here are completely surrounded. There are supply problems with water, food, medication and general supply. It's a very difficult situation."                                                                                                                                                                                                                      , "We have been encircled in Mariupol for more than 40 days. The enemy outnumbers us and in terms of weaponry, their artillery, they have sea-based artillery, tanks, armored vehicles and of course mortars. It is difficult for us," Volyna said.                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The Office of the United Nations High Commissioner for Human Rights (OHCHR) on Wednesday also listed the cities of Volnovakha, Izium and Popasna as places where there have been "allegations of numerous civilian casualties." Russian troops carried out 27 strikes on residential areas of the northeastern city of Kharkiv on Tuesday night, the head of the Kharkiv Regional Military Administration, Oleg Synegubov, said in a statement on Telegram., Taking control of Mariupol would allow Russia to create a land corridor linking Crimea to Donbas, allowing troops to freely move from the southern peninsula to boost its units on the mainland.                                                                                                                                                                                                                                                           , But Russian troops have not yet been able to break through Ukrainian resistance across the east. They will likely attempt to encircle Ukrainian fighters in the east in the coming weeks, and whether or not they are able to do so could be crucial in determining the course of the war.                                                                                                                                                                 , Russia reverts course                                                                                                                                                                                                                                                                                                                                                                                                                                      , Since the war began, Russia has deployed a devastating array of aerial assaults across much of the country -- using hugely destructive missile and artillery fire that extended well into the central and western parts of the country.                                                                                                                                                                                                                    , But a stuttering ground campaign and a series of military setbacks -- particularly around the capital Kyiv and in the north -- mean Moscow has made far less progress in capturing ground than most analysts expected.                                                                                                                                                                                                                                     , Russian fighters moved out of the Kyiv region this week after Ukrainian troops regained control of the area containing the capital, while Russia has also failed to achieve complete air superiority in Ukraine and has suffered heavy losses of personnel since the start of the invasion.                                                                                                                                                                , Now, Russian President Vladimir Putin appears to be changing tack. Putin has revised his war strategy to focus on trying to take control of Donbas and other regions in eastern Ukraine with a target date of early May, according to several US officials familiar with the latest US intelligence assessments.                                                                                                                                           , To achieve that goal, Stoltenberg said NATO is expecting Russia to conduct a "very concentrated" attack in the east aimed at capturing the entire Donbas region.                                                                                                                                                                                                                                                                                           , It's too soon to say whether Putin has permanently abandoned his goal of taking Kyiv and overpowering resistance across Ukraine. But his shift in focus follows a series of losses elsewhere in the country that have stalled his invasion and stretched his forces.                                                                                                                                                                                       , Key new battlegrounds                                                                                                                                                                                                                                                                                                                                                                                                                                      , Russian troops now are expected to try to cut off Ukrainian forces in the east and link up their troops across the region.                                                                                                                                                                                                                                                                                                                                 , That means attention will likely soon turn to the city of Sloviansk, with an advance from Russian units from Izium to the north.                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                            , "Efforts by Russian forces advancing from Izyum to capture Slovyansk will likely prove to be the next pivotal battle of the war in Ukraine," the Washington DC-based think tank Institute for the Study of War (ISW) said in its Monday update on the conflict in Ukraine. Its report uses alternative transliterations of Ukrainian place names.                                                                                                          , A successful Russian assault on the city would give Moscow the option to link troops up with those fighting in Rubizhne, to the northeast of Sloviansk, or move them south, towards Horlivka and Donetsk, in an attempt to encircle Ukrainian fighters there, the group added.                                                                                                                                                                             , But "if Russian forces are unable to take Slovyansk at all, Russian frontal assaults in Donbas are unlikely to independently breakthrough Ukrainian defenses and Russia's campaign to capture the entirety of Luhansk and Donetsk oblasts will likely fail," the ISW said.                                                                                                                                                                                 , Vadym Denysenko, an adviser to the Interior Minister of Ukraine, agreed Thursday that the "the most difficult situation" Ukraine now faces is in the country's east, where Ukrainian military officials say they have observed a buildup of Russian forces.                                                                                                                                                                                                , "Unfortunately, the Russians continue to do everything they did before in Kharkiv, Sumy, Chernihiv, and so on -- to destroy civilian infrastructure," he said. "The situation now is very difficult in the direction of Sloviansk and Kramatorsk," Denysenko said.                                                                                                                                                                                         , "These are the key points at this stage of this war. I believe, in fact, the results of at least this stage of this war will largely depend on the fighting in the east."                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                            , What is the situation in the east now?                                                                                                                                                                                                                                                                                                                                                                                                                     , Cities across eastern Ukraine have suffered sustained and devastating Russian assaults for several weeks.                                                                                                                                                                                                                                                                                                                                                  , Mariupol, at the southern tip of the Donetsk oblast, has been particularly decimated and has come to serve as a symbol of the brutality of Russia's war. In a roundtable on Wednesday, Mariupol Mayor Vadim Boychenko said more than 90% of the city's infrastructure has been destroyed by Russia and that at least 40% of that is "no longer recoverable."                                                                                               , 5,000 people have died in the city in the first month of the invasion, including around 210 children, Boychenko said, citing preliminary estimates.                                                                                                                                                                                                                                                                                                        , The humanitarian situation in Mariupol is meanwhile "growing worse and worse," International Committee of the Red Cross (ICRC) spokesperson Lucile Marbeau told CNN on Wednesday. "Right now, there is nothing, no water, no electricity, barely any connection," Marbeau said.                                                                                                                                                                            , But Mariupol is not alone; Ukrainian officials said Wednesday that major fighting was underway across Ukraine's east, with the regional military governor of eastern Luhansk region urging civilians to evacuate some towns.                                                                                                                                                                                                                               , Vadym Denysenko, adviser to Ukraine's Ministry of Interior, said: "If we talk about the key directions where combat will be ongoing -- it's the Sloviansk [Donetsk region] and Barvinkove [Kharkiv region] directions, in the Luhansk region it's in the Popasna and Rubizhne areas and, of course, in Mariupol."                                                                                                                                          , Serhii Haidai, the military governor of the Luhansk region, issued a statement Wednesday calling for the evacuation of several towns in the region. "The Russians are destroying the railway connections of Donetsk region," he said on Telegram.                                                                                                                                                                                                          , "We will take everyone out if the Russians allow us to get to the gathering places," he said. "As you can see, they do not always observe the 'ceasefire regime.'"                                                                                                                                                                                                                                                                                         , What does Putin want in eastern Ukraine?                                                                                                                                                                                                                                                                                                                                                                                                                   , Pro-Russian separatists seized control of parts of the Donbas region in 2014, when Moscow reacted to protests that toppled a Kremlin-friendly Ukrainian president by fomenting a rebellion in eastern Ukraine. Fighting has endured there since.                                                                                                                                                                                                           , When Putin began his invasion by sending troops into eastern Ukraine on February 22, he claimed that protecting the people of Donbas from "genocide" by the Ukrainian authorities was among the motivations -- a false claim that was roundly dismissed by Ukraine and the international community.                                                                                                                                                        , That followed days of baseless claims about Ukraine's sovereignty, and the decision by Russia to recognize two territories in Luhansk and Donetsk that were held by pro-Russian separatists. And since launching a full-scale war two days later, the supposed liberation of Donbas has played a central role in the rhetoric of the Kremlin.                                                                                                              , The first weeks of the invasion saw bombardments of cities and towns well beyond that part of Ukraine; Russia invaded from the north, east and south and focused much attention on Kyiv and other major cities, with strikes even reaching as far as Lviv in the far west of Ukraine.                                                                                                                                                                      , But the revised strategy sees Putin return attention to the region that was at the heart of his attempts to justify the invasion. The Russian Defense Ministry's daily summaries have sought to focus on successes in these regions and, over the past week, various Russian officials have described the Donbas region as the main goal of the operation, with other actions merely designed to pin down Ukrainian troops.                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                            , "In the coming weeks we expect a further Russian push in the east and southern Ukraine, to try to take the entire Donbas and to create a land bridge to the occupied Crimea," Stoltenberg said on Tuesday.                                                                                                                                                                                                                                                 , After six difficult weeks of war Putin is under pressure to demonstrate he can show a victory, and eastern Ukraine is the place where he is most likely to be able to quickly do that, several US officials familiar with the latest US intelligence assessments said. US intelligence intercepts suggest Putin is focused on May 9, Russia's "Victory Day," according to one of the officials.                                                            , But other officials note even if there is a Russian celebration, an actual victory may be further off.                                                                                                                                                                                                                                                                                                                                                     , "Putin will have a victory parade on 9th May regardless the status of the war or peace talks," a European defense official said. "On the other hand: a victory parade with what troops and vehicles?"                                                                                                                                                                                                                                                      , CNN's Nathan Hodge, Tim Lister, Ivan Watson, AnneClaire Stapleton, Niamh Kennedy, Chris Liakos, Olga Voitovych, Barbara Starr, Jim Sciutto, Alex Marquardt, Jeremy Herb, and Katie Bo Lillis contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-has-tested-negative-covid/story.aspx?guid={845BB83D-42D4-49A1-BBC5-0FDB781EDC30}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-08 00:38:16 </td>
   <td style="text-align:left;"> Biden has tested negative for COVID, wasn't a 'close contact' with Pelosi: White House - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden tested negative for COVID-19 on Wednesday night, the White House said Thursday. The White House press office also said that although Biden interacted briefly with House Speaker Nancy Pelosi over the course of the last two days, he isn't considered a close contact of the California Democrat, whose office on Thursday announced she has tested positive.     


, Secretary of the Treasury Janet Yellen is scheduled to deliver her first major address on the potential risks and benefits of the growing crypto economy                                                                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                               , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/rite-aid-stock-tanks-on-deutsche-bank-downgrade </td>
   <td style="text-align:left;"> 2022-04-08 00:37:36 </td>
   <td style="text-align:left;"> Rite Aid shares tank on Deutsche Bank downgrade </td>
   <td style="text-align:left;"> Crossmark Global Investments CIO Bob Doll argues a main reason is because some of the 'supply shortage problems' are starting to be solved and notes that even if inflation starts to go down, it will still be at 'unacceptable levels.'                                                                                                                                                                                                                                                                                    , Rite Aid shares plunged on Thursday after Deutsche Bank downgraded the pharmacy retail chain and cut the stock's price target ahead of the release of its quarterly results next week.                                                                                                                                                                                                                                                                                                                                       , The big bank downgraded Rite Aid from "hold" to "sell" and cut its price target to $1 per share from $16. Shares fell more than 20% to $6.61 on Thursday.                                                                                                                                                                                                                                                                                                                                                                    , STOCKS LOWER FOLLOWING FED COMMENTS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , According to Deutsche Bank analyst George Hill, Rite Aid's guidance for fiscal year 2023 will be investors' key focus. The company previously indicated it could generate well over $430 million in earnings before interest, taxes, depreciation and amortization (EBITDA).                                                                                                                                                                                                                                                 , Hill notes that the company needs to generate about $400 million to $450 million in annual adjusted EBITDA to continue as an operating company, including $190 million to $200 million in cash annually to cover its debt service costs, plus another $200 million to $250 million to cover its store maintenance capital expenditure requirement.                                                                                                                                                                           , "At a number below $400mm, the equity arguably has no value as the company is not in a position to generate real returns to shareholders," he wrote in a note to clients Thursday. "Unfortunately, we believe Covid has hastened the decline of the retail pharmacy segment and we see the potential for a dramatic negative inflection point for RAD shares as this preliminary F2023 outlook seems to be unattainable."                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Deutsche Bank warned that Rite Aid faces operational challenges on multiple fronts, including rising labor costs, higher retail shrink and continued reimbursement pressure.                                                                                                                                                                                                                                                                                                                                                 , "We are also increasingly concerned with 340B derived earnings as we expect more manufacturers will decide to pull back providing discounts to 340B contact pharmacies going forward,"  Hill continued. "Rite Aid could also have some exposure to opioid litigation and related penalties/settlements, as the prosecution of these cases has now moved on from the drug wholesalers and downstream to the retail pharmacies, with CVS announcing a near half-billion dollar settlement with the state of Florida last week.", The firm estimates that Rite Aid's adjusted EBITDA for 2023 will come in at $377 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 00:28:00 </td>
   <td style="text-align:left;"> French Stocks Down for 3rd Day </td>
   <td style="text-align:left;"> The CAC 40 reversed course and fell 0.6% to close at 6,462 on Thursday, its lowest since March 15th, extending losses for the third straight session. Investors digested a more hawkish tone in minutes from both the ECB and the US Federal Reserve, while caution prevailed ahead of the looming presidential elections. At the same time, concerns over the situation in Ukraine and the impact of harsher sanctions against Russia continued to dominate market sentiment. On the corporate front, Credit Agricole, BNP Paribas, and Societe Generale were among the worst performers. Meanwhile, Sanofi added more than 1.5% after the European Commission approved its drug, Dupixent for the treatment of severe asthma for children aged 6-11 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 00:25:00 </td>
   <td style="text-align:left;"> Milan Stocks Extend Decline </td>
   <td style="text-align:left;"> The FTSE MIB index closed 0.6% lower at 24,302 on Thursday, extending last session’s steep decline as investors digested the minutes from the FOMC meeting in March, while EU states continued to discuss the extent of penalties it shall impose on the Russia. Fed officials signaled a more aggressive 50bps interest rate hike in the next meeting, while the central bank could start reducing its balance sheet by roughly $95 billion per month starting in May. Growth jitters and projections of lower stimulus pressured consumer discretionary goods to close lower, led by a 2.9% loss for Salvatore Ferragamo and a 2.1% fall for Moncler. Meanwhile, Atlantia jumped 6.9% after declining a takeover approach by Global Infrastructure Partners and Brookfield. The infrastructure group’s shares had surged 12% in the session amid reports of interest from Spanish business tycoon Florentino Perez, sparking a potential bidding war with the infrastructure group’s main owners Benetton family and Blackstone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 00:14:00 </td>
   <td style="text-align:left;"> Wall Street Falls for Third Day </td>
   <td style="text-align:left;"> All major US indices were down around 0.5% during midday trading on Thursday, extending losses for a third consecutive session as investors grew worried that an aggressive Fed tightening could hurt growth. Given the worsening outlook for inflation, US policymakers considered higher rate hikes than its usual 25-basis-point while agreeing on balance sheet reductions. On top of that, new data pointing to a robust job market reinforced the narrative of an aggressive tightening, with the number of Americans filing new claims at levels not seen since 1968. Adding to the bearish tone were fears that mounting sanctions on Russia would further stoke inflation. In the latest developments, the Senate passed a bill to ban oil and gas imports from Russia. In terms of individual share price movement, shares of HP Inc jumped over 15% after Warren Buffett’s Berkshire Hathaway disclosed a stake in the tech hardware maker. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-04-08 00:08:00 </td>
   <td style="text-align:left;"> Madrid Stocks End Slightly Lower </td>
   <td style="text-align:left;"> The Ibex 35 failed to hold onto gains and fell 0.2% to close at 8,467 on Thursday, as investors digested a more hawkish tone from both the US Federal Reserve and the ECB. At the same time, uncertainty around the war in Ukraine and concerns over the global impact of tougher sanctions on Russia continued to weigh on market sentiment. Among single stocks, the biggest losses were seen for Iberdrola, Grifols, Siemens Gamesa, Acerinox and IAG. By contrast, Ferrovial, Bankinter, CaixaBank and Banco Sabadell were the top gainers. On corporate news, the ACS group said it was analyzing an offer for the highway business of the Italian infrastructure group Atlantia and formed an alliance with two of the large infrastructure investment funds, GIP and Brookfield. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-04-08 00:07:00 </td>
   <td style="text-align:left;"> Brent Crude Extends Losses Below $100 </td>
   <td style="text-align:left;"> Brent crude futures fell 2% to below $100 per barrel on Thursday, extending a 5.2% loss in the previous session, as traders reassessed again the pledge from IEA to release a huge amount of oil from strategic reserves to offset supply lost from Russia. IEA member countries agreed to release 60 million barrels, including a record 15 million barrels from Japan and following a 180 million barrel pledge from the US. Elsewhere, talks to revive the Iran nuclear deal which could increase Iranian crude exports appeared to have stalled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/07/asia/pakistan-imran-khan-constitution-vote-intl-hnk/index.html </td>
   <td style="text-align:left;"> 2022-04-08 00:05:25 </td>
   <td style="text-align:left;"> Imran Khan: Pakistan's top court rules that blocking a no-confidence vote against PM was unconstitutional - CNN </td>
   <td style="text-align:left;"> Islamabad, Pakistan (CNN)Pakistan's Supreme Court has ruled that a decision to block a vote of no-confidence against Prime Minister Imran Khan was unconstitutional, with legislators now set to vote on Saturday.                                                                                                                          , The Supreme Court reached the unanimous decision after special proceedings that stretched to four days while Khan and his loyalist President Arif Alvi had steamrolled a process to start early elections. The Supreme Court also quashed Khan's order to dissolve parliament and call for early elections, calling it of "no legal effect.", A vote of confidence for Khan will now be held on Saturday at 10:30am local (1:30a ET).                                                                                                                                                                                                                                                     , Khan had called the election in a dramatic attempt to cling to power after the deputy speaker of parliament blocked a vote of no-confidence against him last Sunday, which had appeared almost certain to succeed.                                                                                                                          , Deputy Speaker Qasim Khan Suri said that he had acted to prevent a 'foreign conspiracy' to unseat Khan's regime.                                                                                                                                                                                                                            , That move, and Khan's subsequent dissolution of parliament, enraged an opposition that for months have been demanding his removal over claims of poor governance and economic mismanagement.                                                                                                                                                , The opposition responded by accusing Khan of treason and asking the country's highest court to rule on whether the prime minister had breached the constitution.                                                                                                                                                                            , The court battle is the latest escalation in a crisis that has been smoldering for weeks, with Khan already having lost the backing of key political allies and the country's powerful military.                                                                                                                                            , Military spokesperson Maj. Gen. Babar Iftikhar moved to distance the country's military from developments in a statement Sunday, insisting it was not involved in what is "purely a political situation."                                                                                                                                   , Pakistan, a nation of 220 million, has struggled with political instability since its formation in 1947 with multiple regime changes and military coups. No prime minister has ever completed a full five-year term under the present constitution of 1973.                                                                                 , The country's main opposition parties have been rallying for Khan's dismissal since he rose to power in 2018 after an election mired in accusations of vote rigging and foul play.                                                                                                                                                          , More recently, he has been dogged by claims of economic mismanagement as his government battles depleting foreign exchange reserves and double-digit inflation, with the cost of basic necessities such as food and fuel skyrocketing.                                                                                                      , Khan's response has been to double down on claims that opposition to him is being fueled by the United States. He has not offered any evidence to support his claims, and the State Department has denied the allegations.                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 23:59:00 </td>
   <td style="text-align:left;"> UK Stocks Fall for 2nd Day </td>
   <td style="text-align:left;"> The FTSE 100 was down 0.5% to close at 7,552 on Thursday, extending losses for the second straight session, as the key oil &amp; gas sector retreated on concerns over massive impairments. Major oil company Shell said it expected to book up to $5bn from its asset sheet after its decision to exit Russia, more than previously disclosed. Still, a jump in shares of gambling company 888 Holdings helped limit some losses. Market sentiment was also dominated by the US Fed’s quicker than expected plans to reduce its balance sheet size and the possibility of 50 basis points rate hikes. Meanwhile, the UK slapped tougher sanctions on Moscow, freezing assets of Russia’s largest lender Sberbank, among others, as well as shunning off commodity imports by the end of 2022, including oil and coal. On the data front, house prices in the UK rose to new all-time highs at a rate not seen since mid-2007 in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 23:58:40 </td>
   <td style="text-align:left;"> Russian Stocks Rebound on Thursday </td>
   <td style="text-align:left;"> The MOEX Russia Index closed 0.9% higher at 2,635, lifted by banking stocks as investors continued to weigh on sweeping sanctions and Russia’s risk of sovereign default. On Wednesday, the US imposed sanctions on financial institutions and Russian elites and their families, in addition to banning Americans from investing in Russia. Sberbank shares closed 4.1% higher, partially recovering from yesterday's 8% slide as the prime target of US sanctions. Gains in the sector came despite Finance Minister Siluanov announcing the Kremlin will propose to abandon the payment of share dividends by state-owned banks for 2021. Meanwhile, default worries remained present the US treasury halted Russia from its dollar reserves in US banks, leading Moscow to attempt paying over $600 million for dollar-denominated Eurobond principle and coupons in rubles before being rejected by foreign banks. The payments were due to bond holders by April 4th, starting the 30-day grace period before default. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 23:53:00 </td>
   <td style="text-align:left;"> European Stocks Slip Again </td>
   <td style="text-align:left;"> The pan-European STOXX 600 finished Thursday’s session lower, while the benchmark DAX 30 declined for the third session in a row as investors wrestled with the twin shocks of an aggressive tightening, potentially causing a recession and more Western sanctions on Russia, further stoking inflation. ECB policymakers argued that the current high level of inflation and its persistence called for immediate steps toward monetary policy normalisation, minutes from its last meeting showed. Such remarks came a day after the Fed signalled that it would continue aggressively hiking rates to tackle spiralling inflation. On the corporate side, Swedish carmaker Volvo fell more than 8% after JPMorgan cut its target price. On the flip side,  shares of Atlantia surged about 7% on a possible takeover bid for the company.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-04-07 23:48:00 </td>
   <td style="text-align:left;"> Oil Extends Losses on Reserves Release </td>
   <td style="text-align:left;"> WTI crude futures fell almost 2% to below $95 per barrel on Thursday, after rising to nearly $99 earlier in the day and extending a 5.6% decline in the previous session, as traders reassessed again the pledge from IEA to release a huge amount of oil from strategic reserves to offset supply lost from Russia. IEA member countries agreed to release 60 million barrels, including a record 15 million barrels from Japan and following a 180 million barrel pledge from the US. Elsewhere, talks to revive the Iran nuclear deal which could increase Iranian crude exports appeared to have stalled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-ports-brace-possible-summer/story.aspx?guid={782D2333-FF15-4DA2-8AD2-C5E27C2F6D41}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 23:29:22 </td>
   <td style="text-align:left;"> U.S. ports brace for possible summer surge after backlog from COVID-related disruptions - MarketWatch </td>
   <td style="text-align:left;"> U.S. ports could see another cargo surge in the summer after spending recent months catching up to the backlog caused by COVID-related disruptions, according to the latest from the National Retail Federation and maritime advisory services provider Hackett Associates. "Congestion at West Coast ports has eased, but congestion at some East Coast ports is growing," said NRF Vice President for Supply Chain and Customs Policy Jonathan Gold in a statement. "Ports aren't as overwhelmed as they were a year ago, but they are still significantly busy moving near-record volumes of cargo." Despite the Lunar New Year holiday in February...
    , Tesla is opening its new manufacturing plant in Austin, Texas, on Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/pelosi-tests-positive-covid-19-currently/story.aspx?guid={147FEAC1-8867-4622-810F-00731BAF97F2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 23:15:22 </td>
   <td style="text-align:left;"> Pelosi tests positive for COVID-19, currently asymptomatic, spokesman says - MarketWatch </td>
   <td style="text-align:left;"> House Speaker Nancy Pelosi has received a positive result from a PCR test for COVID-19 and is "currently asymptomatic," said the California Democrat's spokesman, Drew Hammill, in a statement on Thursday. "The Speaker is fully vaccinated and boosted, and is thankful for the robust protection the vaccine has provided. The Speaker will quarantine consistent with CDC guidance, and encourages everyone to get vaccinated, boosted and test regularly," Hammill added., Geopolitical strategist George Friedman: Putin will continue to fight until he is forced out.                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 23:08:53 </td>
   <td style="text-align:left;"> Brazil 10-year Bond Yield Rebounds </td>
   <td style="text-align:left;"> Brazil’s 10-year government bond yield rebounded from its lowest level in three months to above 11.5% as worsening economic conditions in the South American country dented investors’ appetite for government debt. Last month, the central bank raised interest rates for the eighth straight meeting, setting the Selic rate at 10.75%. It is the highest level for Brazil’s benchmark interest rate since March 2017. However, such an aggressive tightening is denting economic activity but failing to tame inflation significantly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-04-07 23:07:00 </td>
   <td style="text-align:left;"> Canadian Dollar at Over 2-Week Low </td>
   <td style="text-align:left;"> The Canadian dollar was changing hands at around $1.258, the lowest since March 21st, as investors remained cautious ahead of the presentation of Canada's federal budget and a more hawkish tone from the US Federal Reserve. Canada's Liberal government will unveil its 2022 budget later in the day, which Prime Minister Justin Trudeau promised to be "fiscally responsible", just seven months after pledging C$78 billion in new spending in a re-election campaign. Fresh fiscal spending could be risky at a time when inflation is running at a 30-year high, with investors anticipating that the Bank of Canada will begin hiking its key interest rate in 50bps increments to tame inflation. The central bank has not hiked by that magnitude since May 2000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/chuck-rettig-irs-testimony-tax-refund-delays </td>
   <td style="text-align:left;"> 2022-04-07 22:53:03 </td>
   <td style="text-align:left;"> IRS chief warns of tax refund delays due to worker shortages, return backlogs </td>
   <td style="text-align:left;"> Rep. Kevin Brady, R-Texas, provides insight into how raising taxes have impacted inflation.                                                                                                                                                                                                                                     , The 2022 tax season is swiftly coming to an end, but IRS Commissioner Chuck Rettig warned on Thursday that many taxpayers could see delays in their refunds as the agency confronts a worker shortage and severe backlog of unprocessed returns.                                                                                , While testifying before the Senate Finance Committee, Rettig acknowledged that continuing fallout from the COVID-19 pandemic – and the many tax changes included in federal relief measures – is likely to delay tax refunds for some filers this year.                                                                         , YOUR TAX REFUND COULD BE DELAYED THIS YEAR - HERE'S WHY                                                                                                                                                                                                                                                                         , "The IRS is serving more people and entities in a global environment than ever before while handling new and bigger responsibilities," Rettig said. "At the same time, we have experienced delays in updating our IT systems, which means the IRS and taxpayers must continue to use certain paper-based processes."            , Although the IRS planned a hiring spree this tax season to process 20 million returns from previous years, the agency has so far onboarded just 2,000 of the 10,000 new workers it intended to hire.                                                                                                                            , There are roughly 2.7 million paper returns from 2021 and 2.3 million returns from 2022 that have not yet been processed. By comparison, the IRS usually enters the tax-filing season with fewer than 1 million remaining items to address. Still, Rettig noted the IRS had cleared about 90% of the "error resolution" backlog., Internal Revenue Service (IRS) Commissioner Charles Rettig testifies during a Senate Finance Committee hearing June 8, 2021 on Capitol Hill in Washington, D.C. (Photo by Tom Williams-Pool/Getty Images / Getty Images)                                                                                                        , "We're trending in the right direction," he said.                                                                                                                                                                                                                                                                               , As of April 1, the tax-collecting agency has processed more than 89 million returns and issued more than 63 million refunds worth a collective $204 billion. The average payment so far is worth $3,352 – much larger than last year's average of about $2,800 – though it may change by the April 18 deadline.                 , There are fresh challenges facing the IRS this year: Taxpayers will have to reflect the monthly child tax credit payments and the stimulus checks they received in 2021 on their returns, further complicating matters and increasing the likelihood of errors and delays in processing returns.                                , Rettig has also previously noted that the agency is grossly understaffed; before the hiring spree, it had 20,000 fewer staff than it did in 2010, and its budget is roughly $11.4 billion – 20% less than it was in 2010, when adjusted for inflation, according to the Congressional Budget Office.                            , The Internal Revenue Service (IRS) headquarters in Washington, D.C., U.S., on Friday, Feb. 25, 2022. (Photographer: Al Drago/Bloomberg via Getty Images / Getty Images)                                                                                                                                                         , On top of that, more than 20% of the IRS customer service workforce has been unable to work for pandemic-related health reasons over the last two years.                                                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                     , If taxpayers file an electronic return with no issues and opt to receive the refund via direct deposit, the IRS anticipates the money will arrive within 21 days. You can start tracking the status of your tax refund within 24 hours of filing using the IRS' Where’s My Refund tool.                                         , The tax-filing season will end on April 18 this year for most individuals, rather than the usual deadline of April 15, because that's when Emancipation Day will be observed in Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-07 22:49:00 </td>
   <td style="text-align:left;"> US Natural Gas at Over 5-Month High </td>
   <td style="text-align:left;"> US natural gas futures rose to $6.2 per million British thermal units, close to levels not seen since October 27th, on solid demand prospects and output issues earlier this week. On Wednesday, the contract hit a six-month high of $6.4 before trimming gains on news of a 120 million barrel oil release by the IEA. US inventory data showed utilities pulled a more-than-anticipated 33 bcf of natural gas from storage last week, reversing from a storage injection in the week before due to chilly temperatures at the end of March. Weather forecasts also pointed to wintry weather in parts of the US until mid-April, which could boost heating demand. Elsewhere, EU leaders are expected to announce a Russian coal ban but remained divided over an oil and gas ban, while mounting pressure could soon shift the current status. LNG shipments to Europe are already at record levels, and the US is facing significant pressure to help Europe secure further supplies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/07/feds-bullard-says-interest-rate-policy-is-behind-the-curve-but-all-is-not-lost.html </td>
   <td style="text-align:left;"> 2022-04-07 22:46:18 </td>
   <td style="text-align:left;"> Fed's Bullard says interest rate policy is 'behind the curve,' but it's making progress </td>
   <td style="text-align:left;"> , The Federal Reserve needs to raise interest rates substantially to control inflation but may not be as "behind the curve" as it appears, St. Louis Fed President James Bullard said Thursday.                                                                                                                                                                                                                               , One of the Federal Open Market Committee's most "hawkish" members in favor of tighter policy, Bullard said a rules-based approach suggests the central bank needs to hike its benchmark short-term borrowing rate to about 3.5%.                                                                                                                                                                                            , However, he said bond market adjustments to the Fed's more aggressive policy, in which yields have surged higher, suggest rates are not that far askew.                                                                                                                                                                                                                                                                     , "If you take account of [forward guidance], we don't look so bad. Not all hope is lost. That is the basic gist of this story," Bullard said in a speech at the University of Missouri.                                                                                                                                                                                                                                      , "You're still behind the curve, but not as much as it looks like," he added. Markets are pricing in rates hitting the 3.5% rate in the summer of 2023, a bit slower than Bullard anticipates, according to CME Group data.                                                                                                                                                                                                  , The comments come the day after minutes from the March FOMC meeting indicated officials were close to approving a 50-basis-point rate hike but settled on 25 points due to uncertainty around the war in Ukraine. A basis point equals 0.01%                                                                                                                                                                                , In addition, members said they foresee the Fed starting to shed some assets on its nearly $9 trillion balance sheet, with the likely pace evolving to a maximum $95 billion a month.                                                                                                                                                                                                                                        , Both moves are an effort to control inflation running at its fastest pace in more than 40 years.                                                                                                                                                                                                                                                                                                                            , Bullard, a voting member on the FOMC this year, said Thursday that "inflation is too high" and the Fed needs to act. In projections released in March, Bullard called for the highest rates among his committee peers. He has said he wants to see 100 basis points' worth of hikes by June. The benchmark fed funds rate now is in a range targeted between 0.25%-0.5%.                                                    , "U.S. inflation is exceptionally high, and that doesn't mean 2.1% or 2.2% or something. This means comparable to what we saw in the high inflation era in the 1970s and early 1980s," he said. "Even if you're very generous to the Fed in interpreting what the inflation rate really is today … you'd have to raise the policy rate a lot."                                                                               , The Fed uses "forward guidance," such as its quarterly dot plot of individual members' interest and economic expectations, in directing the market to where it thinks policy is going.                                                                                                                                                                                                                                      , Judging by moves in Treasury yields, the market already has priced in aggressive Fed tightening. That makes the central bank not so far behind the curve in the inflation fight as it might appear, Bullard said.                                                                                                                                                                                                           , "The difference between today and the 1970s is central bankers have a lot more credibility," he said. "In the '70s, no one believed the Fed would do anything about inflation. It was kind of a chaotic era. You really needed (former Fed Chair Paul) Volcker to come in … . He slayed the inflation dragon and established credibility. After that, people believed the central bank would bring inflation under control.", Volcker's rate hikes did bring down inflation in the early 1980s, but not without triggering a double-dip recession.                                                                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ecuador/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-07 22:39:38 </td>
   <td style="text-align:left;"> Ecuador Inflation Rate Slows to 2.64% in March </td>
   <td style="text-align:left;"> The annual inflation rate in Ecuador eased slightly to 2.64% in March of 2022, from an over six-year high of 2.71% in the previous month. Prices slowed mostly for transport (9.45% vs 9.88% in February); food &amp; non-alcoholic beverages (2.16% vs 2.66%) and health (1.55% vs 1.97%). Additionally, costs fell for clothing &amp; footwear (-2.68% vs -2.73%); communications (-2.53% vs -2.71%) and  recreation &amp; culture (-1.90% vs -1.75%). On a monthly basis, consumer prices were up 0.11%, following a 0.22% increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/bitcoin-aaron-rodgers-odell-beckham-jr-serena-williams </td>
   <td style="text-align:left;"> 2022-04-07 22:27:48 </td>
   <td style="text-align:left;"> Aaron Rodgers, Serena Williams, Odell Beckham Jr. talk Bitcoin at conference: 'I'm betting big on crypto' </td>
   <td style="text-align:left;"> Green Bay Packers quarterback Aaron Rodgers says he’s "betting big on crypto" at the Bitcoin 2022 conference.                                                                                                                                                                                                                                             , NFL stars Aaron Rodgers and Odell Beckham Jr., along with tennis legend Serena Williams, on Thursday discussed the future of cryptocurrency investments at the Bitcoin 2022 conference.                                                                                                                                                                   , Rodgers discussed Bitcoin as a "defense" against the Fed and recent record-high inflation.                                                                                                                                                                                                                                                                , "The Fed keeps printing trillions of dollars, and the best defense against inflation, I believe, is Bitcoin," Rodgers said during a Thursday morning panel discussing Cash App, a mobile payment app that allows users to buy and sell Bitcoin. "I got involved in the rabbit hole years ago and once you get to the other side, there’s no turning back.", Aaron Rodgers speaks during the Bitcoin 2022 Conference on April 7, 2022, in Miami, Florida.  (Marco Bello / Getty Images)                                                                                                                                                                                                                                , He continued: "I'm excited to see how it all plays out, but I'm betting big on crypto continuing on in the fashion that it's been."                                                                                                                                                                                                                       , BITCOIN TRADES AROUND $43,000 AS MIAMI CONFERENCE GETS UNDERWAY                                                                                                                                                                                                                                                                                           , Beckham Jr., who is relatively new to the world of Bitcoin, said the world's most popular cryptocurrency has "almost become cool."                                                                                                                                                                                                                        , "I feel like it's super relatable for all ages. … I'm still learning each and every day," he said, adding that he hears people talking about cryptocurrency "in the locker room."                                                                                                                                                                         ,  Odell Beckham Jr. was among the speakers at the Bitcoin 2022 Conference on April 7, 2022, in Miami, Florida. (Marco Bello / Getty Images)                                                                                                                                                                                                                , He advised future investors to "get with it" or "get left behind."                                                                                                                                                                                                                                                                                        , CLICK HERE FOR FOX BUSINESS' REAL-TIME CRYPTOCURRENCY PRICING DATA                                                                                                                                                                                                                                                                                        , The three athletes, who had relatively atypical college experiences, also discussed Bitcoin investments as a way for college athletes and people who did not attend college to become financially independent through cryptocurrency investments.                                                                                                         , Williams said there is "a lot happening in the cryptocurrency world," and she thinks "it's all being led by Bitcoin."                                                                                                                                                                                                                                     , Serena Williams said there is "a lot happening in the cryptocurrency world" during the Bitcoin 2022 Conference in Miami on April 7, 2022. (Marco Bello / Getty Images)                                                                                                                                                                                    , "You don't have to buy a whole coin. You know, you can start investing, little by little, you can build yourself up to where you want to be financially. And the opportunities there are really so unique," Williams said.                                                                                                                                , BITCOIN OFFERING ‘GOOD ENTRY POINT’ FOR INVESTORS: EXPERT                                                                                                                                                                                                                                                                                                 , Rodgers, who announced that he has re-signed with the Green Bay Packers during the conference, also said he thinks it's "possible" for the NFL to eventually offer Bitcoin contracts to athletes.                                                                                                                                                         , Bitcoin bull at Bitcoin 2022 conference entryway (Audrey Conklinn / Fox News)                                                                                                                                                                                                                                                                             , It will only take one "game-changer" involving a team with "foresight" and "creativity" to team up with an athlete who wants to take a Bitcoin contract "to set the table" for what such a transaction should look like, he said.                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                   , An estimated 25,000 people flooded to the Bitcoin 2022 conference in South Beach, Miami, to learn more about cyrptocurrency and fintech companies, network with like-minded individuals, and discuss the future of Bitcoin as a more mainstream form of currency.                                                                                         , Miami has been dubbed the "crypto capital" of the United States and even the world as it attracts a growing number of tech entrepreneurs, investors and startups.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/sugar </td>
   <td style="text-align:left;"> 2022-04-07 22:24:00 </td>
   <td style="text-align:left;"> Sugar at 4-Month High </td>
   <td style="text-align:left;"> Sugar futures rose to $20 per pound in early April, the highest level since November, tracking higher ethanol prices and a stronger Brazilian real. Energy price trends heavily influenced sugar output projections in Brazil, with mills opting to use sugarcane to produce biofuels instead of raw sugar. Data from S&amp;P Global Commodity Insights indicated the Brazilian ethanol’s growing production premium to sugar reached 208 points in April. That is largely due to a 7.8% jump in ethanol prices and a 6.8% appreciation of the real against the dollar during March 10th to April 1st, while sugar futures only rose 1.4% in the same time period. Meanwhile, industry reports pointed to record high levels of sugar demand in India this summer amid eased Covid-19 restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/jobs-labor-market-inflation-cbo-director </td>
   <td style="text-align:left;"> 2022-04-07 22:18:54 </td>
   <td style="text-align:left;"> Labor market is ‘red-hot’ amid inflation: Former CBO director </td>
   <td style="text-align:left;"> Former CBO Director and American Action Forum President Douglas Holtz-Eakin argues Americans are quitting jobs at ‘record rates’ and says there’s a ‘huge competition’ for labor.                                                                                                                                                                                                                                                                                                                                                                                      , Former CBO Director and American Action Forum President Douglas Holtz-Eakin argued on "Mornings with Maria," Thursday that the labor market is "red-hot" amid inflation and that Americans are quitting jobs at "record rates."                                                                                                                                                                                                                                                                                                                                        , WITH RED-HOT INFLATION, NEW TEACHER SALARIES ARE 11% LESS THAN 30 YEARS AGO: REPORT                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , DOUGLAS HOLTZ-EAKIN: The labor market is red-hot. That's a historically low initial claims number, no question about it, and we have seen other indicators of a red-hot labor market… People are quitting at record rates. Why? They’re 1.7 jobs for everybody looking for a job. The gap between actual employment and listed openings is five million bigger than the labor force. There is no question that there's just a huge competition for labor out there.                                                                                                    , Former CBO Director and American Action Forum President Douglas Holtz-Eakin argues Americans are quitting jobs at "record rates." (AP Photo/Jeff Chiu, File) (Associated Press)                                                                                                                                                                                                                                                                                                                                                                                        , …                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The thing I'd remember is that this is the flip side of the same coin that gave us the inflation. The only way to get the six percentage point increase in CPI inflation was to overstimulate the economy, shows up in the job market as these kinds of numbers, but it's showing up every day… year over year. Twenty-five percent increases in energy prices year over year, 8.4 percent increases in the core food, energy and shelter that people have to spend… we're seeing that inflation show real legs because we're seeing the labor market stay this tight. , WATCH THE FULL INTERVIEW BELOW:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Former CBO Director and American Action Forum President Douglas Holtz-Eakin says the labor market is ‘staying tight’ amid inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-04-07 22:11:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 1-Month Low </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 3.2% to 2,061 points on Thursday, its lowest since February 28th, extending losses for the eleventh straight session, amid weakness across all its vessels segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, slumped 4.9% to touch its lowest level in seven weeks at 1,417 points. "Levels for the big ships dipping further as slow port turnaround/increased congestion remains insufficient to compensate for markedly lower mineral volumes traded compared to same period last year," Fearnleys said. At the same time, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, decreased 3.1% to 2,778 points, its lowest since March 4th; and the supramax index shed 58 points to 2,547 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/chile/balance-of-trade </td>
   <td style="text-align:left;"> 2022-04-07 22:03:57 </td>
   <td style="text-align:left;"> Chile Trade Surplus Widens Sharply in March </td>
   <td style="text-align:left;"> Chile’s trade surplus widened to USD 1,264 million in March of 2022 from USD 867 million in the same month of the previous year. Exports jumped 22 percent to USD 9,481 million, with copper revenues at USD 4,946 million, up 9.3 percent from a year earlier. Meantime, imports advanced 19 percent to USD 7,457 million, led by purchases of intermediate goods (27 percent to USD 4,595 million). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 22:00:50 </td>
   <td style="text-align:left;"> German 10-Year Bund Yield at Nearly 4-Year High </td>
   <td style="text-align:left;"> The yield on the German 10-year Bund rose past 0.7%, closing in on a nearly 4-year high of 0.74% hit on March 29th, as bets for a 60 basis points of rate hikes from the ECB by year-end rose after the ECB minutes showed a large number of policymakers wanted an immediate normalisation of policy due to the current high level of inflation and its persistence. Flash estimates showed the headline HICP rate in the Eurozone surged again in March, reaching a new all-time high of 7.5% year-on-year compared to 5.9% in February and well above market expectations of 6.6%. Elsewhere, the latest FOMC minutes showed the Federal Reserve plans to make a quick reduction in its balance sheet and many officials viewed one of more half-point increases in the fed funds rate appropriate going forward if price pressures remain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 21:59:22 </td>
   <td style="text-align:left;"> Canada Stocks Attempt a Rebound </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, edged up on Thursday, slightly up from a three-week low of 21,789 reached in the prior session, as concerns over aggressive monetary tightening conditions and tougher sanctions on Russia were partly offset by rising commodity prices. Heavyweight energy and mining stocks climbed 0.5%, benefiting from higher oil and gold prices. On the corporate side, BlackBerry has reached a deal to settle a class action lawsuit in a US district court. On the earnings front, shares of leather clothing firm Roots Corporation jumped 9% after reporting adjusted net income of C$20.3 million in Q4 FY21, up from C$16.3 million in the same period of the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61021465?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-07 21:54:36 </td>
   <td style="text-align:left;"> Tesco staff to see pay rise to £10.10 an hour </td>
   <td style="text-align:left;"> Tesco staff are set to see pay rise to £10.10 an hour from the end of July, the supermarket giant has announced.                                                                                                                                                                       , The UK's biggest private employer said staff wages will rise by 55p, up from £9.55 an hour, from 24 July.                                                                                                                                                                              , Meanwhile, its delivery drivers and click and collect assistants will get a 90p increase to £11 an hour.                                                                                                                                                                               , Tesco's move brings it in line with Lidl and Aldi, which became the UK's highest-paying supermarkets this year with the same hourly rate.                                                                                                                                              , Union Usdaw said Tesco's pay rise was "testament" to the hard work of staff at what it said was a "difficult time".                                                                                                                                                                    , The new pay deal will be handed to workers in stores and customer fulfilment centres.                                                                                                                                                                                                  , Last year, Morrisons became the first UK supermarket to announce it would pay at least £10 an hour from April 2021.                                                                                                                                                                    , Sainsbury's said in January it would pay shop workers at least £10 an hour, while the supermarket is expected to make a further announcement tomorrow on wages.                                                                                                                        , Jason Tarry, chief executive officer of Tesco UK &amp; ROI, said employees were getting a "well-deserved pay rise, more access to extra hours, and setting out a long-term commitment and investment in their careers at Tesco".                                                           , Tesco store workers in London will get a similar increase bring their hourly pay to £10.78 per hour.                                                                                                                                                                                   , Alongside pay rises, Tesco is to increase its "colleague clubcard" discount allowance by £500 to take the annual total allowance for all colleagues to £1,500 with immediate effect.                                                                                                   , Usdaw national officer Daniel Adams said the union was "pleased" to secure a pay deal that not only delivered "the highest hourly rate of pay in the sector", but also gave members a right to request a "normal hours" contract and ensured a minimum 16-hour contract in the future. , Tesco employs about 300,000 people in the UK, and most of them work on the shop floor.                                                                                                                                                                                                 , Upping the core hourly wage by an extra 55p will add £200m to the wage bill.                                                                                                                                                                                                           , There's a battle to recruit and retain staff in many parts of the economy right now.                                                                                                                                                                                                   , As Britain's biggest retailer, Tesco needs to stay competitive on pay. It can also afford to do so.                                                                                                                                                                                    , Tesco's been doing very well. It has momentum and scale in a sector that's as cut throat as it's ever been.                                                                                                                                                                            , This move also puts pressure on other retailers as they wrestle with soaring cost increases and how much of these they can pass on to consumers.                                                                                                                                       , Shop workers face the same cost of living pressures as everyone else and more pay deals are on the cards over the coming months.                                                                                                                                                       , Earlier on Thursday, telecoms giant BT said it would hand its UK frontline workers a £1,500 pay rise in the company's biggest pay increase for more than 20 years.                                                                                                                     , BT said the increase was "focused on the lowest paid workers" including engineers, contact centre staff and retail staff, and would work out as a roughly 8% increase for some.                                                                                                        , But the offer was rejected by the Communication Workers Union. It tweeted that it had "no choice now but to immediately prepare for a statutory industrial action ballot".                                                                                                             , People in the UK are facing increased pressure from living costs, with inflation rising at its fastest rate for 30 years, driven up by surging fuel, energy and food prices.                                                                                                           , The National Living Wage, which applies to workers over the age of 23, has increased from £8.91 per hour, to £9.50 per hour from this month. The National Minimum Wage, for those aged 21 to 22, has gone up to £9.18.                                                                 , The rate at which prices rise has been forecast to reach 8.7% in the final three months of 2022.                                                                                                                                                                                       , Inside Thatcher and Reagan's close political relationship                                                                                                                                                                                                                              , What did Putin do before he came to power?                                                                                                                                                                                                                                             , Romesh Ranganathan investigates the musician's death                                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/st-louis-federal-reserve-president-james-bullard-inflation </td>
   <td style="text-align:left;"> 2022-04-07 21:51:18 </td>
   <td style="text-align:left;"> Fed's Bullard warns central bank still seems 'behind the curve' on inflation </td>
   <td style="text-align:left;"> St. Louis Federal Reserve Bank president James Bullard on the state of the economy and rising inflation concerns.                                                                                                                                                                                                                      , St. Louis Federal Reserve President James Bullard said Thursday the U.S. central bank remains well behind in its fight to cool the hottest inflation in four decades.                                                                                                                                                                  , Bullard was the lone dissenter in March, when the Fed voted to hike the benchmark federal funds rate by 25-basis points for the first time since 2018, bringing to an end the ultra-easy monetary policy put in place to prop up the economy throughout the COVID-19 pandemic.                                                         , FED RAISES INTEREST RATES FOR FIRST TIME IN 3 YEARS, PROJECTS 6 MORE HIKES AS INFLATION SURGES                                                                                                                                                                                                                                         , He believed the central bank needed to more aggressively raise rates by a half percentage point and begin unwinding its nearly $9 trillion balance sheet – a sentiment that he reiterated on Thursday.                                                                                                                                 , James Bullard, president and chief executive officer at the Federal Reserve Bank of St. Louis, speaks during the National Association of Business Economics' (NABE) Economic Policy Conference in Washington, D.C., U.S. on Monday, Feb. 26, 2018.  (Joshua Roberts/Bloomberg via Getty Images / Getty Images)                         , "I would like the committee to get to 3-3.25% on the policy rate in the second half of this year," Bullard told reporters Thursday after a speech at the University of Missouri. "We have to move forthrightly in order to get the policy rate to the right level to deal with the inflation we have got in front of us."              , FED SIGNALS HALF-POINT INTEREST RATE HIKE 'APPROPRIATE' AT FUTURE MEETINGS                                                                                                                                                                                                                                                             , However, he acknowledged that bond market adjustments to the Fed's rate increases suggest that rates are not that far off course.                                                                                                                                                                                                      , "If you take account of [forward guidance] we don’t look so bad. Not all hope is lost. That is the basic gist of this story," Bullard said.                                                                                                                                                                                            , Minutes from the U.S. central bank's March 15-16 meeting released on Wednesday show that "many" policymakers would have preferred a larger rate increase last month but determined that a more modest quarter-point hike would be appropriate "in light of greater near-term uncertainty associated with Russia’s invasion of Ukraine.", A man wearing a mask walks past the U.S. Federal Reserve building in Washington D.C., the United States, on April 29, 2020.  ((Xinhua/Liu Jie via Getty Images) / Getty Images)                                                                                                                                                        , Policymakers also proposed shrinking the Fed's nearly $9 trillion balance sheet at a maximum monthly pace of $60 billion in Treasurys and $35 billion in mortgage-backed securities. By comparison, the Fed trimmed its balance sheet at a rate of $50 billion a month from 2017 to 2019.                                              , Officials are expected to approve the balance-sheet reduction – and possibly raise rates by 50-basis points – at their next gathering on May 3-4.                                                                                                                                                                                      , Traders are now pricing in more than a 70% chance of a hefty half-point rate jump when policymakers meet next month, instead of a more modest quarter-point increase, according to the CME's FedWatch tool.                                                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                            , It would mark the first time since 2000 that the U.S. central bank raised the federal funds rate by 50 basis points.                                                                                                                                                                                                                   , "The minutes did indicate that a hawkish Fed is clearly ready to lift rates by 50 basis points in one or more meeting going forward as the central bank prepares to shift into a higher gear in its policy normalization process," RSM chief economist Joseph Brusuelas said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 21:49:00 </td>
   <td style="text-align:left;"> Brazilian Equities Down for 4th Day </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, was down 0.3% to around 117,880 on Thursday, extending losses for the fourth straight session, as investors digested hawkish signals from the US Federal Reserve to tackle surging inflation. Meanwhile, investors remained cautious about the conflict in Ukraine and more severe sanctions against Russia. Locally, Brazil's Ministry of Mining and Energy named José Mauro Ferreira Coelho to succeed Joaquim Silva e Luna as CEO of state-controlled oil company Petrobras, and Márcio Andrade Weber as the company's new chairman, but both need to be approved by Petrobras's board in a vote scheduled for April 13th. The decision to reshuffle came after weeks of criticism by Brazilian President Jair Bolsonaro of the oil company's early March decision to hike its wholesale price for gasoline by 19% and the price for diesel fuel by 25%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 21:31:27 </td>
   <td style="text-align:left;"> Wall Street Struggles for Momentum </td>
   <td style="text-align:left;"> The Dow Jones lost more than 100 points at the opening bell Thursday, while the S&amp;P 500 and the Nasdaq 100 fell 0.2% each as investors digested the hawkish tone in the minutes from the latest Federal Reserve meeting. Given the worsening outlook for inflation, US policymakers considered higher rate hikes than its usual 25-basis-point while agreeing on balance sheet reductions. On top of that, new data pointing to a robust job market reinforced the narrative of an aggressive tightening. The number of Americans filing new claims for unemployment benefits came below expectation and at levels not seen since 1968. In terms of individual share price movement, shares of HP Inc jumped over 10% after Warren Buffett’s Berkshire Hathaway disclosed a stake in the tech hardware maker. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/aluminum </td>
   <td style="text-align:left;"> 2022-04-07 20:55:03 </td>
   <td style="text-align:left;"> Aluminum Hits Three-Week Low </td>
   <td style="text-align:left;"> Aluminum futures bottomed around $3,400 per tonne, a level not seen since in three weeks, as weak demand in China and Japan overshadowed worries of supply disruptions from Russia. Coronavirus-induced restrictions in top producer China, particularly in Shanghai, disrupted shipping, construction and manufacturing, curtailing demand for the metal. On top of that, China ramped up aluminum exports, becoming a net exporter for the first time since 2019, as the world scrambles to replace Russia's roughly 6% global market share. Meantime, a fall in Japanese physical premiums for April-June shipments is the latest sign of weak demand in the world's four-biggest economy. On the flip side, risks of further supply shortages amid the heightened Russia-Ukraine war kept a floor under prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 20:47:00 </td>
   <td style="text-align:left;"> Japan 10-year Bond Yield Hits 6-year High </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB crossed 0.25% for the first time since January 2016 as investors continued to assess the impact of the US Fed’s hawkish surprise. The latest Federal Reserve minutes revealed discussions over shrinking its balance sheet almost as fast as it expanded, roughly by hiving off a monthly $95 billion while also leaving the door open for several 50 bps rate hikes. Still, the Bank of Japan continues to heavily defend its 0.25% yield target on the 10-year JGB, as well as reiterating support for a weak yen. Elsewhere, the IMF revised lower Japan’s growth forecasts to 2.4% in 2022, from a prior 3.3%, saying the economy would contract in Q1 and face headwinds from the war in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 20:46:43 </td>
   <td style="text-align:left;"> Netherlands 10Y Bond Yield Hits 6-1/2-year High </td>
   <td style="text-align:left;"> Netherlands 10 Year Government Bond Yeld increased to a 6-1/2-year high of 0.98% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 20:46:27 </td>
   <td style="text-align:left;"> Sweden 10Y Bond Yield Hits 7-1/2-year High </td>
   <td style="text-align:left;"> Sweden 10 Year Government Bond Yeld increased to a 7-1/2-year high of 1.368% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/jobless-claims </td>
   <td style="text-align:left;"> 2022-04-07 20:35:00 </td>
   <td style="text-align:left;"> US Weekly Jobless Claims Fall Last Week </td>
   <td style="text-align:left;"> The number of Americans filing new claims for unemployment benefits decreased by 5 thousand to 166 thousand in the week ended April 2nd, back to levels not seen since 1968. Figures came well below market expectations of 200K, in another sign of a tight job market and robust labor demand. The Department of Labor revised the methodology used to seasonally adjust the national initial claims and continued claims to reflect a change in the estimation of the models. On a non-seasonally adjusted basis, initial claims fell by 3,674 from the previous week to 193,137, with notable declines being recorded in Michigan (-2,599), Texas (-2,569) and New Jersey (-1,412). The 4-week moving average which removes week-to-week volatility was 170,000, a decrease of 8,000 from the previous week's revised average. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/pakistan/interest-rate </td>
   <td style="text-align:left;"> 2022-04-07 20:29:27 </td>
   <td style="text-align:left;"> Pakistan Hikes Rates at Extraordinary Meeting </td>
   <td style="text-align:left;"> The State Bank of Pakistan hiked its key policy interest rate by 250 basis points to 12.25% at an unscheduled meeting on April 7th of 2022, in an attempt to preserve price and foreigne exchange stability amid a sharp devaluation of the rupee. The monetary policy committee said it was caught off guard by the US Fed’s tightening plans and inflationary pressures, as well as domestic political uncertainty, which could escalate into an economic crisis. Policymakers added that now, real interest rates were mildly positive and that the central bank held its stance to curb inflationary pressures and the deterioration of the country’s current account. Updated forecasts showed inflation was revised upwards to 11% in the current fiscal year, while the current account deficit forecast was unchanged ay 4% of GDP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 20:19:00 </td>
   <td style="text-align:left;"> India 10-Year Bond Yield Remains at 33-Month High </td>
   <td style="text-align:left;"> India 10-Year government bond yield hovered around a 33-month high of 6.91%, tracking a general rise in bond yields and amid prospects of higher interest rates following more hawkish comments from the US Fed officials. In contrast, the Reserve Bank of India maintained interest rate at a record low of 4% since May 2020 to support the recovery of the pandemic-hit economy. Investors now await tomorrow’s RBI policy decision, where it is expected to continue maintaining an accommodative stance, despite several above-target inflation readings. Also, India is set to auction USD 112 billion dollars of bonds or 59% of the full year target, in the first six months of this financial year through 26 weekly debt auctions, with the first auction starting tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 20:09:53 </td>
   <td style="text-align:left;"> Hungary 10Y Bond Yield Hits 8-1/2-year High </td>
   <td style="text-align:left;"> Hungary 10 Year Government Bond Yeld increased to a 8-1/2-year high of 6.68% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/07/business/shell-russia.html </td>
   <td style="text-align:left;"> 2022-04-07 20:09:07 </td>
   <td style="text-align:left;"> Shell Says It Could Lose Up to $5 Billion for Leaving Russia  - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , In an update to investors, the oil company projected a huge financial hit from its exposure to Russia.                                                                                                                                                                                                                                                                                                                                                                                    , By Marie Solis and Jason Karaian                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The British oil giant Shell said on Thursday that its decision to pull out of its projects in Russia would slash its quarterly profit by $4 billion to $5 billion.                                                                                                                                                                                                                                                                                                                        , The estimate, detailed in an update to Shell shareholders, is among the largest publicly announced financial hits by any of the hundreds of companies that have curtailed their operations in Russia or withdrawn entirely since its invasion of Ukraine.                                                                                                                                                                                                                                 , Shell, however, made $20 billion in profit last year, and high energy prices are expected to bolster its bottom line this year — analysts expect it to make over $30 billion in 2022, according to FactSet.                                                                                                                                                                                                                                                                               , Shell, Europe’s largest oil company, said in February that it would leave its joint ventures with Gazprom, the Russian state-controlled gas monopoly, and end its involvement with the Nord Stream 2 pipeline, which by Germany suspended after the invasion. In March, the company announced a more definitive break with Russia, saying it would stop buying oil and gas from Russia and shutter its service stations in the country in a “phased withdrawal” from its operations there., The move followed criticism of Shell for buying a cargo of Russian crude at a large discount, a purchase the company said it had made because it was unable to find alternative oil sources. Shell promised to donate profits from the purchase to humanitarian aid.                                                                                                                                                                                                                      , On Thursday, more than a month after its latest announcement about ending business in Russia, Shell said it had not renewed longer-term contracts with Russia but was “legally obliged to take delivery of crude bought under contracts that were signed before the invasion.”                                                                                                                                                                                                            , According to some estimates, Shell tankers carried an average of 175,000 barrels of crude oil every day from Russia in 2021, about 9 percent of what the company refined globally.                                                                                                                                                                                                                                                                                                        , A long list of companies have pulled out of Russia, but not all have provided estimates about the financial impact. BNY Mellon said in March that it could lose $100 million this quarter and as much as $200 million this year as it stopped new business with Russia and complied with sanctions on the country. JPMorgan Chase’s chief executive, Jamie Dimon, told shareholders on Monday that the bank could lose $1 billion “over time” because of its exposure to Russia.          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sri-lanka/currency </td>
   <td style="text-align:left;"> 2022-04-07 20:06:00 </td>
   <td style="text-align:left;"> Sri Lanka Rupee Slumps amid Historic Crisis </td>
   <td style="text-align:left;"> The Singalese rupee has lost more than a third of its value since the central bank implemented a flexible exchange rate policy on March 8th, trading around 310 per USD and becoming the worst performing currency in the world amid the island nation’s worst-ever economic and political crisis. Sri Lanka is on the verge of defaulting, after several downgrades in ratings agencies has shut the government out of international debt markets and left it to use foreign exchange reserves to pay for imports and meet its financial obligations. Also, the government’s entire cabinet resigned in the first days of April, making it harder to reach a deal with the IMF. The economy has been hit hard by the lack of revenues from the tourism sector, and its heavy reliance on imports means it’s significantly exposed to the globally rising commodity and energy prices, which have combined to accelerate the declining in FX reserves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/interest-rate </td>
   <td style="text-align:left;"> 2022-04-07 19:55:47 </td>
   <td style="text-align:left;"> ECB Close to Cut Stimulus </td>
   <td style="text-align:left;"> Some ECB policymakers argued that it was no longer evident that the pace of asset purchases continued to be proportionate and the general view was that purchases had now fulfilled the objective, minutes from the last meeting on March 9-10 showed. At the same time, a large number of policymakers believe the current high level of inflation and its persistence called for immediate steps towards monetary policy normalisation while conditions for lifting rates had either been met or were about to be met. The ECB surprisingly speed up the asset purchase schedule for the coming months during its March 2022 meting and said that the APP could end in the third quarter if the medium-term inflation outlook will not weaken. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/07/stocks-making-the-biggest-moves-premarket-conagra-levi-strauss-rite-aid-and-others.html </td>
   <td style="text-align:left;"> 2022-04-07 19:53:09 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Conagra, Levi Strauss, Rite Aid and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                 , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                       , Conagra (CAG) – The food producer's stock tumbled 5.5% in the premarket after issuing a weaker-than-expected forecast for the fiscal year ending in May. Conagra's results are being hit by higher transportation and raw materials costs.                                                                                                                      , Levi Strauss (LEVI) – Levi Strauss beat estimates by 4 cents with an adjusted quarterly profit of 46 cents per share, and the apparel maker's revenue also topped Wall Street forecasts. The company saw strong demand for its jeans, tops and jackets while successfully raising prices and cutting down promotions. Levi Strauss rose 3% in premarket trading., HP Inc. (HPQ) – HP is surging 15.2% in premarket trading following news that Warren Buffett's Berkshire Hathaway took an 11.4% stake in the maker of personal computers and printers.                                                                                                                                                                           , Rite Aid (RAD) – The stock tumbled 18.3% in premarket action after Deutsche Bank downgraded the drugstore operator to "sell" from "hold." Deutsche Bank said Covid hastened the decline of the retail pharmacy segment, and there's a possibility that Rite Aid may not be able to generate enough earnings to continue as an operating company.                , Wayfair (W) – Wayfair slid 4.1% in the premarket after Wells Fargo downgraded the stock to "underweight" from "equal weight." Wells Fargo said the high-end furniture retailer will be hurt by waning demand, overly optimistic consensus estimates and other headwinds.                                                                                        , Rent the Runway (RENT) – Rent the Runway stock jumped 3.9% in the premarket after the fashion rental company announced a price hike for its subscribers.                                                                                                                                                                                                        , CDK Global (CDK) – The provider of automotive retail technology agreed to be bought by Brookfield Business Partners for $54.87 per share in cash. The price represents a 12% premium over CDK's Wednesday closing price.                                                                                                                                        , SoFi Technologies (SOFI) – The online personal finance company's shares slid 5.1% in the premarket after cutting its full-year outlook. The cut follows the White House announcing a student loan payment moratorium will be extended.                                                                                                                          , JD.com (JD) – JD.com announced that founder Richard Liu has left the chief executive officer position and President Xu Lei will take over as the Chinese e-commerce company's CEO. Liu will remain as chairman. JD.com fell 1.1% in the premarket.                                                                                                              , Teladoc Health (TDOC) – The provider of virtual doctor visits saw its stock gain 1.5% in premarket action after Guggenheim initiated coverage with a "buy" rating. Guggenheim said health care access is moving more toward digital interactions and that Teladoc has a broader service portfolio than other providers.                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cag:us </td>
   <td style="text-align:left;"> 2022-04-07 19:48:57 </td>
   <td style="text-align:left;"> Conagra Foods earnings meet market expectations at 0.58 USD </td>
   <td style="text-align:left;"> Conagra Foods (CAG) released earnings per share at 0.58 USD, in line with market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/stz:us </td>
   <td style="text-align:left;"> 2022-04-07 19:48:51 </td>
   <td style="text-align:left;"> Constellation Brands earnings below expectations at 2.07 USD </td>
   <td style="text-align:left;"> Constellation Brands (STZ) released earnings per share at 2.07 USD, compared to market expectations of 2.10 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-07 19:37:08 </td>
   <td style="text-align:left;"> Macedonia Inflation Rate Near 14-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Macedonia accelerated for the ninth straight month to 8.8 percent in March of 2022, from 7.6 percent in the prior month. It was the highest reading since June of 2008, mainly driven by prices of transport (19.8 percent), food &amp; non-alcoholic beverages (11.4 percent), housing &amp; utilities (7.7 percent), and restaurants &amp; hotels (9.4 percent). On a monthly basis, consumer prices rose 1.6 percent, after a 1 percent increase in the previous month. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-04-08 09:27:25 UTC +8

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
   <td style="text-align:left;"> 2022-04-08 09:27:05 </td>
   <td style="text-align:left;"> $SPY bears are wandering about. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:26:24 </td>
   <td style="text-align:left;"> $WMT .... Channel resistance  Including what looks like backtest resistance rejection if you discount after hours upward movement... $COST  Also close below major resistance today....And as of now futures has rejected off horizontal neckline $XRT $SPY $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:26:05 </td>
   <td style="text-align:left;"> $SPY Me not looking at futures because they don’t mean anything and I don’t give a shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:25:58 </td>
   <td style="text-align:left;"> $SPY $DWAC https://wshhp.page.link/wR9QA71vzbUQHVXe9

Classic example of a liberal interviewing less intelligent people to make themselves look smart. Bigotry at it&amp;#39;s finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:25:50 </td>
   <td style="text-align:left;"> $SPY Honestly lookin like a return to normal squeeze to me.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:25:49 </td>
   <td style="text-align:left;"> Which group is prepping for the next real estate market collapse?

We have some wild predictions to deal with in the next few years that will affect many homeowners andcinvestors in a very nasty way but first let&amp;#39;s take the time to set it up purrfectly.

$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:25:27 </td>
   <td style="text-align:left;"> $BWV $20 $30 $40 in 2 or 3 weeks.

Look at the bounce back BWV made after the March drop.

I smell money

No news and it drops 82%

Low float

Huge squeeze candidate 

I&amp;#39;ll sleep lake a baby tonight 

Watch list for friday 
BWV $SPY $ATER $SBFM $TRVI 

Happy trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:25:23 </td>
   <td style="text-align:left;"> $SPY Futures on 1HR. Down PPS signal as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:24:39 </td>
   <td style="text-align:left;"> $SPY Nikkei from +0.90% to red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:24:36 </td>
   <td style="text-align:left;"> $SPY we crashed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:24:35 </td>
   <td style="text-align:left;"> $SPY You decide ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:24:08 </td>
   <td style="text-align:left;"> $SPY all the bears were screaming the big crash was certain after yesterday.  WTF.  Casinos need patrons to make money!  Why crash it?  No one will come back to lose more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:23:52 </td>
   <td style="text-align:left;"> $spy 1999-2000 all over again ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:23:29 </td>
   <td style="text-align:left;"> $SPY CEO ..not really doing well ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:22:05 </td>
   <td style="text-align:left;"> $SPY $QQQ today just looked like a mini bounce due to some short covering.  Decline will resume.  I will eat my shorts if the market is higher in a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:21:24 </td>
   <td style="text-align:left;"> $SPY Limit down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:21:18 </td>
   <td style="text-align:left;"> $TMC Loke Marine Minerals is joining the list of Oil and Gas companies like Allseas, $RIG, and $OIS who are pivoting their business into the collection of polymetallic nodules. We are just getting started. More players will be jumping in for the nodules “gold rush”. $SPY $QQQ 

https://lokemm.com/loke-has-completed-first-phase-of-concept-select-testing-of-nodule-collector-for-minimum-plume-generation/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:21:11 </td>
   <td style="text-align:left;"> $SPY going to bed now, waking up to check futures at 4 will be green asf,check again at 7 will be semi green and fade little by little for two and half hour, open limit down, bounce back a little at 1030-1100, then flush to 440 by 3, ok night night bulls/bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:21:11 </td>
   <td style="text-align:left;"> $SPY I wonder where the bottom will be 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:20:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR When you’re as famous and outspoken as Elon then you’ll inevitably receive criticism. I’ve pointed out his misdoings numerous times. That said, he has balls and brains. He’s going against the establishment while not only talking about his beliefs but also acting on them. He truly believes in what he says, rather than pandering to the masses like every other CEO in big tech. Destroy them Elon, change the status quo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:20:39 </td>
   <td style="text-align:left;"> $SPY see how these other commodities go tomorrow. May hop into some. METC was an idea the other day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:20:30 </td>
   <td style="text-align:left;"> $SPY https://www.jeremysrazors.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:20:19 </td>
   <td style="text-align:left;"> $SPY lmao bear market squeeze over back to 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:20:16 </td>
   <td style="text-align:left;"> $SPY Hang Seng heading to 19, Nikkei, 24, u heard it here 1st </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:19:50 </td>
   <td style="text-align:left;"> $SPY who bot silver miners today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:19:14 </td>
   <td style="text-align:left;"> $SPY id say the US needs to go into a recession and thats bullish for the US in the long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:19:08 </td>
   <td style="text-align:left;"> $SPY good times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:18:44 </td>
   <td style="text-align:left;"> $SPY My neighbor hates my guts 100% for certain- it’s this old lady who smokes cigs and her husband is the gravedigger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:18:31 </td>
   <td style="text-align:left;"> $SPY Anyone know what a vaccine that doesn’t prevent disease is called? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:17:49 </td>
   <td style="text-align:left;"> $SPY I use to Lie to my parents when I was younger .. Took me yrs to regain. There trust !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:17:25 </td>
   <td style="text-align:left;"> $SPY $QQQ https://youtu.be/8AcrTfjpQ7I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:17:14 </td>
   <td style="text-align:left;"> $SPY $DWAC Over 150 large wire transfers from China to the Biden’s flagged by banks.  Could be conflict of interest?  Money Laundering?  Pay for play?  Tax avoidance?  Treason?  

Regardless of what they are, it looks bad when Democrats are richer after leaving office when Trump’s net worth went down after serving public office.

https://www.cbsnews.com/video/us-banks-flagged-over-150-transactions-involving-bidens-brother-or-son-for-further-review/#x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:17:02 </td>
   <td style="text-align:left;"> $SPY 455 open 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:16:59 </td>
   <td style="text-align:left;"> $SPY dont worry its going up again. A negative divergence on 15 mins was created that brought it down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:16:36 </td>
   <td style="text-align:left;"> $SPY 440 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:16:26 </td>
   <td style="text-align:left;"> $SPY I DONT EVEN WANT THE WAP, BABY, I JUST WANT THE FETTY 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:51 </td>
   <td style="text-align:left;"> $SPY  correction over we going to 480 by June mark this post.  Sleepy joe for another 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:32 </td>
   <td style="text-align:left;"> $IRNT government coverup company $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:28 </td>
   <td style="text-align:left;"> $SPY https://wshhp.page.link/8zRiABjwwA6Ev9Vp6

These are the &amp;quot;good&amp;quot; guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:26 </td>
   <td style="text-align:left;"> $SPY Daily MACD and RSi are telling a certain story.  Multiple upcoming negative catalysts.  Has room to make next leg down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:24 </td>
   <td style="text-align:left;"> BP $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:21 </td>
   <td style="text-align:left;"> $SPY $QQQ will go up coz there is a gap need to fill ! Buy calls intra day low and sell high but don’t hold it over night ! Remember next wk march inflation data coming so buy some puts at high after you selling intra day calls !! Don’t forget to buy $IPOF you never know maybe Starlink coming throw via ipof 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:14:03 </td>
   <td style="text-align:left;"> $SPY you know. SPY has taught me a lot in the last few months. 
1) Open doesn’t mean shit
2) 11 a.m is the new power hour
3) theta burn bitch 
4) will puts print? Yes, but no.
5) FED will do anything to save this country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:13:42 </td>
   <td style="text-align:left;"> $SPY bro how tf can fisher investments afford all these commercials </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:13:33 </td>
   <td style="text-align:left;"> $SPY Boo 👻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:13:25 </td>
   <td style="text-align:left;"> $SPY  $4431 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:13:19 </td>
   <td style="text-align:left;"> $SPY $PFE 2020 WSB post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:13:12 </td>
   <td style="text-align:left;"> $SPY $QQQ  Boo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:13:05 </td>
   <td style="text-align:left;"> $SPY imagine what Powell can do with a 3d printer...lots of magic 🎩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:12:12 </td>
   <td style="text-align:left;"> Let’s see if the $SPY can continue this momentum. If so we’re looking at $451.70/$452.92 and a stretch test back at $457.5 if not back to $444.5-$443.5 then $438 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:11:53 </td>
   <td style="text-align:left;"> $SPY what brand of printer Powell use

Maybe or maybe not

$HPQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:11:34 </td>
   <td style="text-align:left;"> $SST you guys have to see this. Sst going to $50 $SPY $BTC.X $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:11:27 </td>
   <td style="text-align:left;"> $SOFI $SPY Third time watching this today. Hahahahahahahahaha

https://youtu.be/QGRxVITBGOA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:11:22 </td>
   <td style="text-align:left;"> $SPY I think when it comes to opex and heavy OI on opex look at the break down of the spy ETF as a whole... blows ur mind right, someone gettin robbed someone gettin paid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:11:10 </td>
   <td style="text-align:left;"> $SPY Current Futes:  Within the Range, at the top and rejected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:11:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLY $XLP 

The consumer retail stocks saved today but the US consumers are currently using money left from the ATH stock market back in December and lofty house equities that are about to disappear. They also have to start actually paying the fucking rents and mortgages. Wages are up but not catching up with inflation either, so this consumer sector rally is wrong and stupid, in my opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:10:42 </td>
   <td style="text-align:left;"> $SPY  bulls are jooish.. jk, joos are cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:10:28 </td>
   <td style="text-align:left;"> $SPY bears are toast like the toast in the toaster but more........toastier 😂🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:10:16 </td>
   <td style="text-align:left;"> $SPY I know they told you I’d be bad for you
Don’t worry I’ll be back for you
All the money and cars, stripper hoes and the tattoos 
Bad news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:10:15 </td>
   <td style="text-align:left;"> $SPY you know what would screw the most people tomorrow? A flat day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:09:40 </td>
   <td style="text-align:left;"> $SPY what’s my favorite penny stock going to do tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:09:10 </td>
   <td style="text-align:left;"> $SPY I just 10 bagged a Pokemon lunchbox...
Wow.. bring it
Market is Super bullish with inflation right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:09:10 </td>
   <td style="text-align:left;"> $SPY 🤦🏻‍♂️or buying... goes against basic supply/demand principles you&amp;#39;ve ever been taught about anything. Imagine you have 100 iphone cases for $50.00/each and 2 sales... what&amp;#39;s going to happen to the price? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:09:10 </td>
   <td style="text-align:left;"> $SPY can we get a clown sentiment meter going. Anybody good with that type of thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:08:56 </td>
   <td style="text-align:left;"> $SPY miss my home boy from 2 years ago. He has a like 6 surfboards from back in the day. Dude might be moving to Tennessee. His wife and him are done with Newport Beach  California.
They want land. 
They also want calls🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:08:25 </td>
   <td style="text-align:left;"> $XLF Banks break?

It&amp;#39;s over , 35 should do &amp;#39;er, thank inflation and thank THE FED &amp;amp; don&amp;#39;t forget, Russia (bad assets, debt).

$SPY $RYF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:07:38 </td>
   <td style="text-align:left;"> $SPY spy 455 asap pump till CPI then small pull back.... the option chain pay don&amp;#39;t matter STG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:07:24 </td>
   <td style="text-align:left;"> $SPY I just pulled a Charzard out that same Pokemon lunchbox plus that other 80 dollar card that I bought for 25 bucks!
Super Bullish for the Markets!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:06:19 </td>
   <td style="text-align:left;"> $SPY Ow Watergate was canceled ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:06:11 </td>
   <td style="text-align:left;"> $SPY turn up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:05:54 </td>
   <td style="text-align:left;"> $SPY Warren buffet has some HP

We know that cryptically means J Powell uses HP for the money printer.

We’re solid boyz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:05:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The futes are a tiny bit red🙊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:05:07 </td>
   <td style="text-align:left;"> $SPY 455 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:04:55 </td>
   <td style="text-align:left;"> $SPY EVERYONE SHARE THIS EVERYWHERE https://youtu.be/orIEUsuaORI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:04:20 </td>
   <td style="text-align:left;"> $SPY ARREST JOE AND HUNTER NOW https://youtu.be/orIEUsuaORI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:04:16 </td>
   <td style="text-align:left;"> $SPY last stand here.Watch your/oil/gold/usd/. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:04:06 </td>
   <td style="text-align:left;"> $spy $eth.x $doge.x $hbar.x Crypto is everything you don&amp;#39;t understand about money and software rolled into one. We are the next Google, Facebook, Instagram, YouTube, PayPal, Visa, RocketMortgage etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:04:04 </td>
   <td style="text-align:left;"> $SPY “I may be early but I’m not wrong 
It’s the same thing” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:03:33 </td>
   <td style="text-align:left;"> $SPY ATH 503, drop near 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:03:20 </td>
   <td style="text-align:left;"> $spy says he’s “always” right .. within seconds of scrolling his page 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:03:06 </td>
   <td style="text-align:left;"> $SPY  filled the gap this evening, 
will $QQQ follow🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:02:59 </td>
   <td style="text-align:left;"> $SPY Sold for $75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:02:48 </td>
   <td style="text-align:left;"> Live: U.S. Congress votes to strip Russia&amp;#39;s trade status, ban oil and gas imports after atrocities in Bucha

$SPY https://www.cnbc.com/2022/04/07/russia-ukraine-live-updates.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:02:38 </td>
   <td style="text-align:left;"> $SPY  Whistlings is a Good thing  😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:02:31 </td>
   <td style="text-align:left;"> PS $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:01:53 </td>
   <td style="text-align:left;"> $NEE $SPY NextEra out here killing eagles daily but screams “save the planet”

https://abcnews.go.com/amp/Technology/wireStory/wind-energy-company-kills-150-eagles-us-pleads-83916292 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:00:53 </td>
   <td style="text-align:left;"> $SPY bears GF ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:00:44 </td>
   <td style="text-align:left;"> $SPY We really swung 161bps (1.61%) off no news and no volume today lol I love this little piece of garbage that Spy is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:00:41 </td>
   <td style="text-align:left;"> $SPY face it bulls, I&amp;#39;m always right. I just don&amp;#39;t have many followers because I&amp;#39;m a jerk and short everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 09:00:22 </td>
   <td style="text-align:left;"> $SPY futes trippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:59:55 </td>
   <td style="text-align:left;"> $SPY 

Why I see a bearish AF chart ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:59:22 </td>
   <td style="text-align:left;"> $SPY I guess the geriatrics in power are kicking the can to the next generation since they don&amp;#39;t give a damn when they are dead and gone anyways. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:59:14 </td>
   <td style="text-align:left;"> $SPY 

Time to stop calling these “vaccines”.   It’s Tamiflu for Covid (and even that is a stretch). 

“The Washington Post has learned of about a half-dozen journalists as well as members of the White House and National Security Council staffs who said they tested positive after the event. Their names are being withheld because they have not announced their status publicly.

Tom DeFrank, a contributing columnist for National Journal and president of the Gridiron Club, said that as of Wednesday afternoon, the group knew of 14 guests who had tested positive.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:59:05 </td>
   <td style="text-align:left;"> $SPY ES futures are down 0.02%! Bulls are doomed. /s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:58:37 </td>
   <td style="text-align:left;"> $SPY lol Nikkei having fun as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:58:28 </td>
   <td style="text-align:left;"> $SPY  $4440 first line in support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:58:02 </td>
   <td style="text-align:left;"> $SPY Just always have your finger on the Button ? Just saying ? Never hurts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:58:01 </td>
   <td style="text-align:left;"> $SPY Well well 

https://www.nbcnews.com/news/amp/rcna23360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:57:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X $PLTR Forget spy and qqq, all you need is Tesla, BTC and Palantir. https://youtu.be/bgEnUPAhGbA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:57:03 </td>
   <td style="text-align:left;"> $SPY bullish pattern. Near future $503   Then it will drop 30 to 35% down (“crash”) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:56:56 </td>
   <td style="text-align:left;"> thought on tomorrow’s session?  $SPY $SPX $TSLA $QQQ 💰🦅 (POLL) https://www.webullapp.com/s/post/409667056920993792?hl=en </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:56:13 </td>
   <td style="text-align:left;"> $SPY so what&amp;#39;s the thesis on the intra day V recovery?  🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:56:11 </td>
   <td style="text-align:left;"> $SPY I just bought a pokemon lunchbox for 25 bucks and pulled an 80 dollar card out of the first pack already.. Bullish for the Markets!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:55:59 </td>
   <td style="text-align:left;"> $SPY Why aren&amp;#39;t we Drlling ? That was a promise ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:55:15 </td>
   <td style="text-align:left;"> $SPY Vix looks like it’s bull flagging into tomorrow for huge drop on spy again next week. Something to watch tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:53:34 </td>
   <td style="text-align:left;"> $SPY Long one /es </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:52:56 </td>
   <td style="text-align:left;"> $SPY $TWTR $TSLA sooo MSNBC says musky is a racist ,, LMFAO JOY HOT MESS REID gotta go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:52:09 </td>
   <td style="text-align:left;"> $SPY hmm that consumer credit keeps getting bigger. Huge overshoot. Everyday they dont address inflation is another day it gets worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:52:02 </td>
   <td style="text-align:left;"> $SPY floor has been found

Researcher spent month of digging finding floor of spy

We finally hit the floor, it&amp;#39;s time for party $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:52:00 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:51:38 </td>
   <td style="text-align:left;"> $SPY what happens when liabilities and interest on our debt becomes untenable? More debt? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:51:31 </td>
   <td style="text-align:left;"> $SPY the funniest damn people on this board are the ones with no sense of humor and it’s not even fair… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:51:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $SBFM 📣This Stonk is #1 on Trending. But it wasn’t #1 yet when I shared with 1 on 1 chats. 📣 now AH position was up almost 50%. Sold half swinging half . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:50:37 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE 🔥 
#LOTTO FRIDAY PICKLIST 
IM GOING TO BREAKDOWN 👇 
📈TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS  
CLICK&amp;gt; https://us02web.zoom.us/j/89457164243 
 $SPY  #trading  #Invest  #stocks $AAPL  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:50:10 </td>
   <td style="text-align:left;"> $SPY here&amp;#39;s one love it 
 
C.R.E.A.M. 
 
Cash rules everything around me 
 
what you know bout that WuTang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:49:32 </td>
   <td style="text-align:left;"> $spy bullish until the wedge is broken,, don’t debate me 👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:49:25 </td>
   <td style="text-align:left;"> $SPY Being a midterms year, bulls,, you&amp;#39;re really up against it.

Maybe just turn tail and call it a year $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:49:15 </td>
   <td style="text-align:left;"> $SPY interesting that currently max pain for the rest of the month is 450 - highest end of month 455 .  No doubt this is going higher .  Put / call OI now reasonable as well . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:48:52 </td>
   <td style="text-align:left;"> $SPY I’ve figured it out. You have to ignore all feelings towards companies (or the market in general) and just trade both sides. I did that today, and nearly tripled my account. Puts in the morning and calls afternoon. 

I’m no longer bullish or bearish, I’m just ish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:48:49 </td>
   <td style="text-align:left;"> It’s crazy how no one cares about the war anymore but I can tell what will those CPI numbers next week lol it’s like the markets have amnesia. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:48:28 </td>
   <td style="text-align:left;"> $SPY pensions buying. They aint worried for another 20yrs....bubble will burst but they will live </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:48:10 </td>
   <td style="text-align:left;"> $SPY Biden will go down as the biggest failure in history </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:48:10 </td>
   <td style="text-align:left;"> How the $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:47:47 </td>
   <td style="text-align:left;"> $SPY the  $DXY US Dollar index is at $99.84.  hasnt been over $100 since the beginning of 2020 Crash in market as money sought safety... Caution here when break over $100, possibly within next few hours.. market likely freaks.. #BotWilson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:47:46 </td>
   <td style="text-align:left;"> $SPY I have decided to follow Jesus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:47:35 </td>
   <td style="text-align:left;"> $SPY sanctions are working as expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:47:18 </td>
   <td style="text-align:left;"> $SPY @realness365 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:46:08 </td>
   <td style="text-align:left;"> $DIS Yet another blue chip company with it&amp;#39;s balls held in the vice grip of the Globalist cabal via ESG social credit system to ensure that they toe the progressive liberal line and maintain the fabric of their insidious agenda, otherwise their bottom line is at risk. Just because I don&amp;#39;t agree with their virtue pandering crusade to appease the LGBT &amp;quot;community&amp;quot; by indoctrinating innocent young minds with hypersexuality and homosexuality doesn&amp;#39;t mean that I&amp;#39;m a bigot. Let gays be gays, just keep that shit away from my children. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:45:53 </td>
   <td style="text-align:left;"> It’s always a matter of when not if the V rally comes. Every red day increase the odds. 
 
down days are like seeing a rare unicorn or flying pig. fund managers wait for them to inject billions every time frok cash on hand.  
 
always an oppprtunit.  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:44:16 </td>
   <td style="text-align:left;"> $SPY bears got annhilated today. I think it is the damage to their morale that these constant face ripping V rallies that is the reason markets never go lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:44:05 </td>
   <td style="text-align:left;"> $SPY imagine buying spy at 450 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:43:56 </td>
   <td style="text-align:left;"> $SPY limit down in progress </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:43:22 </td>
   <td style="text-align:left;"> $SPY Just push it up !! Wasn&amp;#39;t thinking of a crash this week anyways.. Just watching, but have big plays elsewhere ? Memes  are the Best here !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:43:20 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX 

If I have this timed right     

We closing this week off $4380 - $4430   🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:42:39 </td>
   <td style="text-align:left;"> $SPY HS is in formation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:42:06 </td>
   <td style="text-align:left;"> $SPY arrest those parents anyone who reject such acts are not tolerant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:41:57 </td>
   <td style="text-align:left;"> $SPY Bears: 
 
No ragrets! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:41:51 </td>
   <td style="text-align:left;"> $SPY 867-5…445. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:41:16 </td>
   <td style="text-align:left;"> $SPY leveraged on leverage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:57 </td>
   <td style="text-align:left;"> $PFE $SPY pelosi does it again😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:56 </td>
   <td style="text-align:left;"> $SPY Earnings season is coming up next! 
 
The Wall Street Consensus for Tesla Inc. (TSLA) FQ1 2022 has shifted significantly downwards since 03/25/22. 
 
The Wall Street Consensus for NVIDIA Corporation (NVDA) FQ1 2023 has shifted significantly downwards since 02/17/22.  
 
etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:45 </td>
   <td style="text-align:left;"> $SPY @ShortyMcFly did you look at LQD?   Is this it?  Where the real easy money comes in?   I think we’re going down tomorrow 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:41 </td>
   <td style="text-align:left;"> Top 6 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:30 </td>
   <td style="text-align:left;"> $SPY bears have gained control and are batting it around like a cat with a half dead mouse. It’ll rip wide open whenever they feel like it…but not sooner. Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:27 </td>
   <td style="text-align:left;"> $SPY $DIA $NDX $QQQ $SPX 

Bulls are just getting slaughtered here 

BagHolders Trap 🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:40:11 </td>
   <td style="text-align:left;"> $SPY Like I have said before, it takes forever to drop this monster, but only less than 3 weeks to recover. Trade wisely. All time highs are not that far away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:39:35 </td>
   <td style="text-align:left;"> $SPY Borrowed Time !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:39:32 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:39:32 </td>
   <td style="text-align:left;"> $SPY $SPX $NDX $QQQ 

     $4440 Potential Support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:39:24 </td>
   <td style="text-align:left;"> $BTC.X $BITO $DOGE.X finna turn up - especially over the weekend 📈 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:56 </td>
   <td style="text-align:left;"> $SPY are you ready for a rectal exam folks? Lube up…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:54 </td>
   <td style="text-align:left;"> $SLV imagine if SILVER is up 5% tomorrow  :) $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA BREAKING NEWS: “PUTIN BECOMES A MALE PROSTITUTE” - via CNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:45 </td>
   <td style="text-align:left;"> $SPY  
 
Execute Order 12631 Daddy 🥵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:44 </td>
   <td style="text-align:left;"> $SPY Slav Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:33 </td>
   <td style="text-align:left;"> $SPY you thought PUTS were back in business LOL 😂 📈📈📈 1 more time ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:38:14 </td>
   <td style="text-align:left;"> $SPY 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:37:14 </td>
   <td style="text-align:left;"> $SPY Deflate or Burst 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:59 </td>
   <td style="text-align:left;"> Choppy market setting deters most short term traders $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:49 </td>
   <td style="text-align:left;"> $SPY futures are red for absolutely no reason at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:49 </td>
   <td style="text-align:left;"> $SPY 👅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:33 </td>
   <td style="text-align:left;"> $SPY $DJIA he was right ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:23 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY sleep tight.... bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:23 </td>
   <td style="text-align:left;"> $NVDA Market On Close Imbalance: $392M To Buy Side $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:17 </td>
   <td style="text-align:left;"> Stay focused on your goals don’t get distracted $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:36:15 </td>
   <td style="text-align:left;"> $SPY 5 minutes .20 percent swing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:35:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:35:45 </td>
   <td style="text-align:left;"> $SPY call buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:35:24 </td>
   <td style="text-align:left;"> $SPY LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:35:18 </td>
   <td style="text-align:left;"> $SPY 8 more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:35:13 </td>
   <td style="text-align:left;"> $SPY who just farted? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:35:11 </td>
   <td style="text-align:left;"> $SPX $SPY just a reminder that we haven&amp;#39;t had 2 back to back red quarterly candles in 13 years. looks similar to 1998 with almost tagging 9ema. we undercut the lows and ended green in that year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:34:39 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:34:05 </td>
   <td style="text-align:left;"> $TSLA this is so gonna SELLOFF 📉⬇️⬇️⬇️tomorrow! Wall Street has all of your LOTTO CALLS trapped! They knew the fan bois would be in their ELON JOCK STRAP FEELINGS 🥴🙃🤡..  
 
NO WORRIES,  I stopped by to drop off a consolation prize while your real money goes to to bears! 🙋‍♂️💦💸 $nio $aapl $SPY $rivn etc 
 
Ladies and gentlemen  - The CyberDUMP 🍑💦😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:33:53 </td>
   <td style="text-align:left;"> Prolonging the inevitable $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:33:07 </td>
   <td style="text-align:left;"> $SPY Balance Sheets Sucks ..period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:33:03 </td>
   <td style="text-align:left;"> a Swan event  percolating? the Charts are saying YES!. Caution a must.  
 the US President getting Covid could be one of the Swans. 
 MS Pelosi Leader of US Congress has Covid who saw Mr Biden.   
 
the China Evergrande Housing  situation getting worse not better..  manufactoring shut downs. the manufactoring report i mentioned last week was a Huge Caution.  worst report in years. 
 
caution wave riders for a real wave lower. 
 
$SPY  $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:32:48 </td>
   <td style="text-align:left;"> $SPY well the housing market isn’t cooling off in my town.  House 2 down from me just sold for $1M even.  3 bed/2 bath 1900sq ft.  Jesus.  Tiny kitchen too 

There were going for 850-970k last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:32:35 </td>
   <td style="text-align:left;"> $SPY I’m canceling all of my streaming subscriptions. Sorry in advance! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:32:26 </td>
   <td style="text-align:left;"> $SPY 😍😍😍😍😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:50 </td>
   <td style="text-align:left;"> $HPQ Easy short.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:37 </td>
   <td style="text-align:left;"> $SPY FUTES were </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:35 </td>
   <td style="text-align:left;"> $SPY which platform shows VIX in real time? Most platforms have the delayed price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:22 </td>
   <td style="text-align:left;"> $SPY when big tech falls everything is going with it...Cramer and other managers know it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:19 </td>
   <td style="text-align:left;"> $SPY  Whatever comes out of the fed&amp;#39;s mouth is pure garbage. They say their end game is to normalize interest rates.  They&amp;#39;ve been saying that for 15 years. While they&amp;#39;ve been saying that what they&amp;#39;ve actually been doing is adding to their balance sheet. It&amp;#39;s gone from 500 billion to 9 trillion. Listen to them if you want but what they do and what they say have nothing to do with each other. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:07 </td>
   <td style="text-align:left;"> $SPY flush this fuccin terd — today was a disgrace — no more bond buying = no more fed money into the market = no more fantasy land = get the correction over with already so we can go back to the euphoria sooner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:31:04 </td>
   <td style="text-align:left;"> $SPY $DIS so you know why LBGTQ+ pedo discriminate against the H ?? Ist because a Hermaphrodite didn’t get to choose their mental illness- that’s how they came ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:30:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA millenial day traders acting rich on instagram while losing money in their mommy and daddys basements in bidens america depicted below. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:30:25 </td>
   <td style="text-align:left;"> $SPY Does this mean Nancee won&amp;#39;t go to Twain ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:30:20 </td>
   <td style="text-align:left;"> $SPY $MRNA $PFE myocarditis shots 

https://battleplan.news/watch?id=624e52ce3953a857ac1e9163 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:30:12 </td>
   <td style="text-align:left;"> $SPY the reversal today is caused by the floor

We found a floor

MARGIN UP 6X AND BUY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:29:50 </td>
   <td style="text-align:left;"> $SPY  Low jobless rate means Fed must raise interprets rates. Stagflation in full effect! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:29:20 </td>
   <td style="text-align:left;"> $SPY https://www.bizjournals.com/columbus/news/2016/10/03/yes-the-plunge-protection-team-is-real-and-heres.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:29:10 </td>
   <td style="text-align:left;"> $SPY news reporter &amp;quot;president Harris we have high inflation , problems at the southern border and threats from Iran Russia and china&amp;quot;
President Harris &amp;quot; 😂😂🤪&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:28:28 </td>
   <td style="text-align:left;"> $SPY The FED is under very close watch, they will not back down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:28:18 </td>
   <td style="text-align:left;"> $SPY Neutral here, cheaty mms will keep cucking traders next week so watch out. Likely sideways and will get back to 450 on Thursday (short week) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:28:13 </td>
   <td style="text-align:left;"> $spy i respect and will follow any trader that posts real trades and the results. 95% lose and 95% lie about making money here….yea sure you are always on the right side🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:28:04 </td>
   <td style="text-align:left;"> $SPY any fed speaking tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:28:03 </td>
   <td style="text-align:left;"> $SPY nothing here now, but wait&amp;#39;ll ya get to tomorrow.
Ole! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:27:58 </td>
   <td style="text-align:left;"> $SPY 456 calls were only 27$ that i picked up for 4/11 .. Lmfao .. If these print and go into the $$ that be nutz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:27:42 </td>
   <td style="text-align:left;"> $DUTV seems like shorts afraid and covering!  👀 high short volume on Green Day is sign of short covering $spy $AMC ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:27:39 </td>
   <td style="text-align:left;"> $SPY so we now have political activists calling for &amp;quot;direct military contact...., boots on the ground&amp;quot; with Russia....

....and these same morons are forcing our military to remove standards, and embrace a &amp;quot;woke,&amp;quot; virtue-signaling approach to recruiting....

Am I the only person who anticipates a buncha&amp;#39; shit going wrong with this picture?  

Men who pretend to be women, women who wish to be men....not physically (or mentally) fit enough to bench-press the donut they eat every morning with their Starbucks latte.... 

....are gonna represent us on the &amp;quot;front lines&amp;quot; against a nation with thousands of nuclear weapons?????!!!  🤔🥴🥴🥴

We need to really WAKE UP, before these &amp;quot;woke&amp;quot; imbeciles start Armageddon with their ridiculously immoral and ignorant views of everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:27:17 </td>
   <td style="text-align:left;"> $SPY Market isn&amp;#39;t good,  but Mr Workman was still able to purchase shares near 52 week lows today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:26:33 </td>
   <td style="text-align:left;"> $SPY Yes tell me about ATER bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:26:30 </td>
   <td style="text-align:left;"> $SPY futes should turn red over night and pump PM. Let’s see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:25:50 </td>
   <td style="text-align:left;"> $SPY &amp;gt;&amp;gt; $DUTV at 52 weeks high 🤔 what’s happening? Spy drawing bullish bat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:25:46 </td>
   <td style="text-align:left;"> Goldman warning $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:25:24 </td>
   <td style="text-align:left;"> $SPY $DJIA CLOWNS 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:25:10 </td>
   <td style="text-align:left;"> $SPY not buying this dip. HS may be confirmed tmrw/Monday, any leg to 460-470 is a short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:24:40 </td>
   <td style="text-align:left;"> $SPY $ATER

Detail: Chart Updates

Stock Market Update

https://youtu.be/u7b0APqPbvc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:24:03 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price 
https://youtu.be/kZC_qPVddVM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:23:07 </td>
   <td style="text-align:left;"> $SPY Well they have a good fight going, will check on this in the AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:22:46 </td>
   <td style="text-align:left;"> $SPY classic just when things were getting dumb da bears pull 1 out right at muhhhh magic level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:22:22 </td>
   <td style="text-align:left;"> $HPQ dinosaur are the future $SPY

Buy dinosaur before too late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:22:02 </td>
   <td style="text-align:left;"> Worst $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:21:49 </td>
   <td style="text-align:left;"> $SPY can anyone identify what caused that sudden reversal today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:21:45 </td>
   <td style="text-align:left;"> $QQQ $SPY 30wema has been very sticky for the Q’s in the past.  Not surprised it got rejected hard the past couple of weeks.  It will make another run at it soon….💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:21:37 </td>
   <td style="text-align:left;"> $SPY  
 
Bears tomorrow when they realize that the crash is in 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:21:34 </td>
   <td style="text-align:left;"> $SPY I am a MM listen now Bulls. Tomorrow is going to be sensational. Deep green open Anythijg and everythinfg BTFMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:21:31 </td>
   <td style="text-align:left;"> $SPY do ppl even realize how rigged and criminal that intraday rally was…? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:21:25 </td>
   <td style="text-align:left;"> $SPY despise bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:20:59 </td>
   <td style="text-align:left;"> $SPY nice wick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:20:52 </td>
   <td style="text-align:left;"> $SPY Wondering about financial data, cpi, FOMC, announcements, etc, bookmark this dude !  https://www.marketwatch.com/economy-politics/calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:20:51 </td>
   <td style="text-align:left;"> $SPY Heck , I had to to phyical assets $$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:20:41 </td>
   <td style="text-align:left;"> $SPY buffett must know something i don&amp;#39;t with that $HPQ trade.  trashola. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:19:58 </td>
   <td style="text-align:left;"> $SPY Literally this entire board at 8:15 pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:19:47 </td>
   <td style="text-align:left;"> $SPY Anything above $449.16 open tomorrow and this is bullish for a $452.50 print. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:19:32 </td>
   <td style="text-align:left;"> $SPY $460 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:18:07 </td>
   <td style="text-align:left;"> $SPY they won’t let this finish over 450 tomorrow, too many calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:17:54 </td>
   <td style="text-align:left;"> $SPY is there cpi tmrw ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:17:47 </td>
   <td style="text-align:left;"> $SPY higher open interest in puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:17:42 </td>
   <td style="text-align:left;"> $SPY 600 days of green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:17:15 </td>
   <td style="text-align:left;"> $SPY 

If a “guru” tells you this market is difficult for day traders, they are absolutely “clueless”
If anything this is the best market we are in for making daily consistent profits!
Ya’ll experiencing the TWOWS magic yet?🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:17:15 </td>
   <td style="text-align:left;"> $SPY $MULN $AMC $NILE $TSLA   $1800 into $40k in the last 30 days.... If you really want to make huge profits on trading then, Join this winning chat ‘...    tinyurl.com/most-winning-chat-room </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:16:21 </td>
   <td style="text-align:left;"> $SPY watching FOX news 
Dems are really stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:53 </td>
   <td style="text-align:left;"> $SPY why is it they can’t let anything go?  This is such a tiny retrace.  And overall a Green Day after fomc minutes.  It’s laughable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:50 </td>
   <td style="text-align:left;"> $SPY Looks like da bears hear me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:46 </td>
   <td style="text-align:left;"> New Video!  
 
Elasticity, Yield Curve Inversion and The Fed! 
 
https://www.youtube.com/watch?v=DmruxZfRMpQ 
 
$SPY $QQQ $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:33 </td>
   <td style="text-align:left;"> $SPY futes ripping!!! C&amp;#39;mon 460+ what u take so long to reach new ATH!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:24 </td>
   <td style="text-align:left;"> $SPY ready to rip...curling up🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:17 </td>
   <td style="text-align:left;"> $EXPR $SPY why do I get a buyout feeling? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:15:15 </td>
   <td style="text-align:left;"> $SPY &amp;quot; ladies and gentlemen please welcome madame president Kamala devi Harris&amp;quot;. A lot can happen in 2 1/2 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:12:46 </td>
   <td style="text-align:left;"> $SPY when earnings are coming out good… sheesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:12:18 </td>
   <td style="text-align:left;"> By all measures today was THE pivot point - the PEAK FUD - the shock n awe from the fed … with the result of … BUY THE FKN DIP 
 
its the rslly of ages from here round 2 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:11:28 </td>
   <td style="text-align:left;"> $ES_F $SPY if we can get above 4510 there&amp;#39;s room to 4550/60 tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:11:25 </td>
   <td style="text-align:left;"> $SPY I could loan myself with $AFRM and then bill the loan (the virtual credit card) to my LLC 

For some spare cash. That’s super degenerate right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:09:30 </td>
   <td style="text-align:left;"> $SPY i set all my clocks dif to phuk w/ myself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:09:25 </td>
   <td style="text-align:left;"> $SPY agree I rather have future on red,  if green just a gap up to 352 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:09:13 </td>
   <td style="text-align:left;"> $SPY  Sell in May and go away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:09:05 </td>
   <td style="text-align:left;"> $SPY FUUUUUUTES RIPPPPPPIN 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:08:51 </td>
   <td style="text-align:left;"> $SPY give me some red futes so we RIP tomorrow please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:08:42 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Footures are ripening brah&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:07:06 </td>
   <td style="text-align:left;"> $SPY strange how Shanghai under covid lockdown and Biden and media say nothing.  One year ago they&amp;#39;d be locking us down.  Mid terms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:07:04 </td>
   <td style="text-align:left;"> $SPY this was a BEAUTIFUL and tiny pullback for a GREAT BTD !!!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:06:58 </td>
   <td style="text-align:left;"> $spy I’m starting a help group for traders who drink. Let me know if you’d like the link. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:06:44 </td>
   <td style="text-align:left;"> $SPY yep uzi knew first </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:06:36 </td>
   <td style="text-align:left;"> $SPY * this is your cue to google &amp;quot;gap trading&amp;quot;, &amp;quot;stock gaps&amp;quot;, etc * </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:06:32 </td>
   <td style="text-align:left;"> $SPY I just took a sht </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:06:15 </td>
   <td style="text-align:left;"> $CFVI $SPY the climb continues for rumble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:06:04 </td>
   <td style="text-align:left;"> $SPY where are the muppets crew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:05:26 </td>
   <td style="text-align:left;"> $SPY one thing for sure
Stonk only go up

Throw your chart out, because you&amp;#39;re poor

GO TESLA, STONK 
 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:05:01 </td>
   <td style="text-align:left;"> $SPY 454 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:04:59 </td>
   <td style="text-align:left;"> $SPY The S&amp;amp;P 500 is knocking on the door of a stiff, near-term resistance. Complacency and a lack of financial literacy has an UNPRECEDENTED number of NEW market participants (Simpcoiners &amp;amp; plebs) chasing anything green out of DESPERATION. A financial death trap. 🩸☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:04:56 </td>
   <td style="text-align:left;"> $SPY pamp it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:04:51 </td>
   <td style="text-align:left;"> $SPY harder and harder to be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:04:41 </td>
   <td style="text-align:left;"> $SPY they&amp;#39;re sayin lich for pope strapped with the scope cuz i give bulls hope </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:04:31 </td>
   <td style="text-align:left;"> $SPY $SPY pumpit ….we heading toward 6900 .🚀🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:04:21 </td>
   <td style="text-align:left;"> $SPY pumpit ….we heading toward 6900 🚀🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:03:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 
FOMC fever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:03:54 </td>
   <td style="text-align:left;"> $SPY  
 
Big A55 bull flag on VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:03:49 </td>
   <td style="text-align:left;"> $SPY  I guess no one told spy there was still Neckline Resistance 🤷‍♂️ $UVXY $QQQ $TSLA $AAPL 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:03:25 </td>
   <td style="text-align:left;"> $COST $SPY $AMD 

Yes guys let’s buy up Costco at a 46 PE while AMD trades at a 40!!!! Smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:03:04 </td>
   <td style="text-align:left;"> $SPY it’s like people think this market hasn’t been over inflated. The market doesn’t go up all the time, especially there hawkish views on the horizon. Give me one reason to be bullish. I could give you 5 reasons to be bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:02:53 </td>
   <td style="text-align:left;"> $SPY SPY 2022-04-07 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=oE8mDliNpm0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:02:39 </td>
   <td style="text-align:left;"> $SPY vix under 23 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:02:32 </td>
   <td style="text-align:left;"> $SPY $QQQ Sorry burrs we gotta go up a teeny bit more before we can go down bigly in May-July. Watch buyers snuff this out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:02:01 </td>
   <td style="text-align:left;"> $SPY  Neve short DuLL FuTES ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:01:52 </td>
   <td style="text-align:left;"> $SPY chop chop tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:01:19 </td>
   <td style="text-align:left;"> $SPY 

How awesome is this feeling?❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:01:09 </td>
   <td style="text-align:left;"> $SPY  Markets closed next Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:00:51 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Today was just a gap fill bears are toast tomorrow&amp;quot;

Go on tell me more about this gap fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:00:35 </td>
   <td style="text-align:left;"> $SPY Remember when this was almost 480...3 months ago?....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:00:33 </td>
   <td style="text-align:left;"> $SPY Will be back up to 460s in no time lol. Rip $uvxy baggies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 08:00:33 </td>
   <td style="text-align:left;"> $QQQ $SPY

CONFESSION 

I watched futes a few times in January.. maybe in December too.

It&amp;#39;s a very rare occasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:59:24 </td>
   <td style="text-align:left;"> $QQQ $SPY 

There were enough turns and twists today that could have fooled both sides. Hopefully you did not get caught at the exact wrong moment. LOL

One thing for sure - QQQ is not done going down yet. It could re-test $338, $325, and $313. Would not be surprised it bounces back up to test ATH after hitting each of these supports. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:59:19 </td>
   <td style="text-align:left;"> $SPY Express the current market condition as a Texas Holdem&amp;#39; hand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:59:09 </td>
   <td style="text-align:left;"> $SPY I love this crazy azz manic market...I hope it never goes down😂🤣😂I&amp;#39;m killing it long and short... but mostly short. Tomorrow we be GREEN and I&amp;#39;m cool with day! 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:58:29 </td>
   <td style="text-align:left;"> $SPY im starting to think people on ST don&amp;#39;t even understand what the term &amp;quot;gap fill&amp;quot; even means. Or how many different kinds there are. Just loosely throwing around the term trying to sound smart with why they are bullish/bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:58:10 </td>
   <td style="text-align:left;"> $SPY expect nothing but a nice green Friday we seeing more then we deserve. 455+++ polosi is on my side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:57:42 </td>
   <td style="text-align:left;"> $QQQ $SPY isnt the next FED meeting not for like another month? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:56:36 </td>
   <td style="text-align:left;"> $SPY futures giving it all  back. Still got fed pump at midnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:56:30 </td>
   <td style="text-align:left;"> $QQQ $SPY huge inverse head and shoulders forming? How does nobody see this? Turn your chart upside down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:56:09 </td>
   <td style="text-align:left;"> $SPY 

What an incredible day in my Small Account Challenge discord!🔥🔥🔥
This market is just too good!❤️
Did ya’ll see my BWV $52 entry short alert today? OMG🥶🥶🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:56:09 </td>
   <td style="text-align:left;"> $spy There’s two things I ain’t seen, a turtle with speed, or a bitch that I need 💎👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:56:05 </td>
   <td style="text-align:left;"> $SPY Everyone talking about daily MACD possible rolling over, but not even looking at that 4hour already crossed to bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:55:39 </td>
   <td style="text-align:left;"> $SPY learned a valuable lesson I need to be absolutely soccer mom slizzard to trade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:55:38 </td>
   <td style="text-align:left;"> $MNTS deal with starlink $TSLA musk could make mnts go big imo $SPY $QQQ $SST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:55:34 </td>
   <td style="text-align:left;"> 1992!  This has to be the dirtiest song back then I would think.  I can&amp;#39;t find anything that rivals it.   
 
$SPY 
 
https://youtu.be/X53ZSxkQ3Ho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:55:27 </td>
   <td style="text-align:left;"> $SPY Jacked to the tits w $AAPL calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-08 07:55:18 </td>
   <td style="text-align:left;"> $SPY I’m gonna say bearish tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:25:49 </td>
   <td style="text-align:left;"> Which group is prepping for the next real estate market collapse?

We have some wild predictions to deal with in the next few years that will affect many homeowners andcinvestors in a very nasty way but first let&amp;#39;s take the time to set it up purrfectly.

$SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:22:05 </td>
   <td style="text-align:left;"> $SPY $QQQ today just looked like a mini bounce due to some short covering.  Decline will resume.  I will eat my shorts if the market is higher in a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:22:02 </td>
   <td style="text-align:left;"> $QQQ Maybe another bears morning plunge and bully’s afternoon rip 💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:21:18 </td>
   <td style="text-align:left;"> $TMC Loke Marine Minerals is joining the list of Oil and Gas companies like Allseas, $RIG, and $OIS who are pivoting their business into the collection of polymetallic nodules. We are just getting started. More players will be jumping in for the nodules “gold rush”. $SPY $QQQ 

https://lokemm.com/loke-has-completed-first-phase-of-concept-select-testing-of-nodule-collector-for-minimum-plume-generation/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:19:51 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:17:59 </td>
   <td style="text-align:left;"> $QQQ what happens if cpi is reported lower than previous month? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:17:25 </td>
   <td style="text-align:left;"> $SPY $QQQ https://youtu.be/8AcrTfjpQ7I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:16:34 </td>
   <td style="text-align:left;"> $QQQ Some quick perspective for the cocky bulls that think a rally is coming after the fed basically said they will drive the market lower... 
 
Only reason this isn&amp;#39;t sub 350 is there is a massive 1 billion dollars worth of shares put contract position sitting right at 350.00 which is why that price was defended so fiercely today. Guess what doesn&amp;#39;t exist for next weeks options though, that put wall. 
 
Tomorrow may very well be a bit green but if it is, its a trap for next week when there aren&amp;#39;t any option sellers being forced to keep the index propped up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:14:32 </td>
   <td style="text-align:left;"> $IRNT government coverup company $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:14:21 </td>
   <td style="text-align:left;"> $SPY $QQQ will go up coz there is a gap need to fill ! Buy calls intra day low and sell high but don’t hold it over night ! Remember next wk march inflation data coming so buy some puts at high after you selling intra day calls !! Don’t forget to buy $IPOF you never know maybe Starlink coming throw via ipof 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:13:12 </td>
   <td style="text-align:left;"> $SPY $QQQ  Boo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:11:53 </td>
   <td style="text-align:left;"> $QQQ this country ran by top female athletes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:11:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLY $XLP 

The consumer retail stocks saved today but the US consumers are currently using money left from the ATH stock market back in December and lofty house equities that are about to disappear. They also have to start actually paying the fucking rents and mortgages. Wages are up but not catching up with inflation either, so this consumer sector rally is wrong and stupid, in my opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:07:23 </td>
   <td style="text-align:left;"> Markets attempt a swing low for the seven day decline $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/markets-attempt-a-swing-low-for-the-seven-day-decline?post=350846 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:06:32 </td>
   <td style="text-align:left;"> Long Term Cycles &amp;amp; Elliott Wave for $QQQ #Elliottwave #QQQ https://elliottwave-forecast.com/stock-market/long-term-cycles-elliott-wave-for-qqq/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:05:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The futes are a tiny bit red🙊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:03:06 </td>
   <td style="text-align:left;"> $SPY  filled the gap this evening, 
will $QQQ follow🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 09:01:51 </td>
   <td style="text-align:left;"> $QQQ if this goes down tomorrow I&amp;#39;m blaming Europe.  Those countries are panicking right now and weighing all the economies down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:57:11 </td>
   <td style="text-align:left;"> $QQQ $BABA $KWEB Whatever you choose to do tomorrow, do it bigly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:56:56 </td>
   <td style="text-align:left;"> thought on tomorrow’s session?  $SPY $SPX $TSLA $QQQ 💰🦅 (POLL) https://www.webullapp.com/s/post/409667056920993792?hl=en </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:51:12 </td>
   <td style="text-align:left;"> $QQQ $SPY $SBFM 📣This Stonk is #1 on Trending. But it wasn’t #1 yet when I shared with 1 on 1 chats. 📣 now AH position was up almost 50%. Sold half swinging half . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:49:52 </td>
   <td style="text-align:left;"> $TSLA Tesla never disappointed. This will print huge next week✅🚀🔥 $ROKU $F $QQQ $SNDL 🤑💴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:49:25 </td>
   <td style="text-align:left;"> $SPY Being a midterms year, bulls,, you&amp;#39;re really up against it.

Maybe just turn tail and call it a year $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:43:32 </td>
   <td style="text-align:left;"> $QQQ Let&amp;#39;s hit $366 tomorrow ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:43:20 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $NDX 

If I have this timed right     

We closing this week off $4380 - $4430   🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:42:59 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:42:41 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:40:27 </td>
   <td style="text-align:left;"> $SPY $DIA $NDX $QQQ $SPX 

Bulls are just getting slaughtered here 

BagHolders Trap 🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:39:32 </td>
   <td style="text-align:left;"> $SPY $SPX $NDX $QQQ 

     $4440 Potential Support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:39:24 </td>
   <td style="text-align:left;"> $BTC.X $BITO $DOGE.X finna turn up - especially over the weekend 📈 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:38:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA BREAKING NEWS: “PUTIN BECOMES A MALE PROSTITUTE” - via CNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:38:35 </td>
   <td style="text-align:left;"> $QQQ guaranteed nasdaq will retest 13000 by this month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:36:23 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY sleep tight.... bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:30:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA millenial day traders acting rich on instagram while losing money in their mommy and daddys basements in bidens america depicted below. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:26:19 </td>
   <td style="text-align:left;"> $QQQ do you guys know why inflated asset bubbles are bad for the economy? Cheap money allows misallocation of resources. So we waste money and valuable resources on company’s that don’t produce value for consumers. Recessions allow those money losing company’s to go bankrupt and we start fresh again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:25:26 </td>
   <td style="text-align:left;"> $QQQ pls open lower so i can buy more though i know you probably wont. 🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:25:06 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/J0Xz3mVQ0vc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:21:45 </td>
   <td style="text-align:left;"> $QQQ $SPY 30wema has been very sticky for the Q’s in the past.  Not surprised it got rejected hard the past couple of weeks.  It will make another run at it soon….💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:15:46 </td>
   <td style="text-align:left;"> New Video!  
 
Elasticity, Yield Curve Inversion and The Fed! 
 
https://www.youtube.com/watch?v=DmruxZfRMpQ 
 
$SPY $QQQ $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:13:06 </td>
   <td style="text-align:left;"> $QQQ gap up and run tomorrow? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:12:18 </td>
   <td style="text-align:left;"> By all measures today was THE pivot point - the PEAK FUD - the shock n awe from the fed … with the result of … BUY THE FKN DIP 
 
its the rslly of ages from here round 2 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:11:39 </td>
   <td style="text-align:left;"> For those invested in $FUBO good insight by a 5-star analyst on why they think $FUBO has at least 150% upside from here. 
 
They think removing the cheaper price plan is one step closer to profitability.  
 
$QQQ 
 
https://www.tipranks.com/news/article/fubotv-what-does-the-subcription-price-hike-mean-for-the-stock/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:07:49 </td>
   <td style="text-align:left;"> $QQQ The Fed is trying to get foreign investors at great prices. That is what negative BS is all about. We hit ATH soon. Stocks are the inflation hedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:03:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 
FOMC fever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:03:49 </td>
   <td style="text-align:left;"> $SPY  I guess no one told spy there was still Neckline Resistance 🤷‍♂️ $UVXY $QQQ $TSLA $AAPL 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:02:32 </td>
   <td style="text-align:left;"> $SPY $QQQ Sorry burrs we gotta go up a teeny bit more before we can go down bigly in May-July. Watch buyers snuff this out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 08:00:33 </td>
   <td style="text-align:left;"> $QQQ $SPY

CONFESSION 

I watched futes a few times in January.. maybe in December too.

It&amp;#39;s a very rare occasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:59:24 </td>
   <td style="text-align:left;"> $QQQ $SPY 

There were enough turns and twists today that could have fooled both sides. Hopefully you did not get caught at the exact wrong moment. LOL

One thing for sure - QQQ is not done going down yet. It could re-test $338, $325, and $313. Would not be surprised it bounces back up to test ATH after hitting each of these supports. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:57:42 </td>
   <td style="text-align:left;"> $QQQ $SPY isnt the next FED meeting not for like another month? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:56:30 </td>
   <td style="text-align:left;"> $QQQ $SPY huge inverse head and shoulders forming? How does nobody see this? Turn your chart upside down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:56:00 </td>
   <td style="text-align:left;"> $QQQ is currently showing a bull flag pattern! A bull flag pattern is a pull back after a strong rise up. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:55:52 </td>
   <td style="text-align:left;"> $QQQ accumulation distribution line below stochastic. I find that interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:55:38 </td>
   <td style="text-align:left;"> $MNTS deal with starlink $TSLA musk could make mnts go big imo $SPY $QQQ $SST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:53:57 </td>
   <td style="text-align:left;"> $QQQ there is a gap that needs to be filled to around $361 but I think it’s going much lower after that. I have calls and puts. If it gaps up I’m gonna sell the calls and ride the puts back down. 

Bullish/bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:53:00 </td>
   <td style="text-align:left;"> $QQQ lets gap close this tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:47:11 </td>
   <td style="text-align:left;"> $QQQ hmm are we in a Paul volcker situation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:40:46 </td>
   <td style="text-align:left;"> Elon vs other company CEO’s
He has a twitter poll asking the ppl should he sell shares. He actually lets you know what’s about to happen so your able to get out or stay in. Fucking hats off 
$TSLA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:39:28 </td>
   <td style="text-align:left;"> $QQQ you can’t tell me that Tom lee isn’t a pedo. I know he touches children </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:36:53 </td>
   <td style="text-align:left;"> $QQQ Tomorrow: Soo many pissed off bears at how Tesla be carrying the whole index as its gonna try and test that resistance. Gonna rest up so that I can read every single post mañana </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:35:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $DJIA  
Market Movers Economic Events Next Week      
 
https://www.financegreater.com/economiccalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:33:45 </td>
   <td style="text-align:left;"> crazy $RPG easily made it through yesterdays highs but nas 100 didnt?? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:32:57 </td>
   <td style="text-align:left;"> $NQ_F $QQQ $MNQ_F The vacuum is in position for a strong 💪 pull higher. Gap and Go for a strong Fridays close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:32:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA   
 
Why did the democrats want a pedophiIe sympathizer on the Supreme Court? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:29:18 </td>
   <td style="text-align:left;"> $QQQ Look $2674 net profit. 7 close trades. 85% win rate. 3 profit factor in a 15 minutes chart. Waiting for Buy signal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:18:30 </td>
   <td style="text-align:left;"> $SPY $QQQ https://youtu.be/iJv6NQtB9qg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:16:16 </td>
   <td style="text-align:left;"> $QQQ $TSLA  might wanna test that falling wedge at 1140-1150 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:15:22 </td>
   <td style="text-align:left;"> $QQQ congrats you bought puts quit trying to sound smart stocks go up 🚀💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:14:55 </td>
   <td style="text-align:left;"> $QQQ should start climbing here we open greeeeeen beartards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:12:39 </td>
   <td style="text-align:left;"> $SPY With CPI Tuesday, this ain&amp;#39;t going anywhere worth mentioning, unless, you talkin&amp;#39;..... 
$QQQ $SPXL $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:11:51 </td>
   <td style="text-align:left;"> $QQQ down tommorow Friday sell off like always 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:05:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $SQQQ $TQQQ 

I’m looking forward to the upcoming Fed induced market crash.

https://www.thestreet.com/investing/federal-reserve-rates-hikes-hurt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 07:02:01 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $NASDAQ $QQQ Fed reports credit card balances swelled 20.7 percent in February

https://www.bankrate.com/finance/credit-cards/fed-consumer-credit-g19/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:58:47 </td>
   <td style="text-align:left;"> $BTC.X $BITO pushin’ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:57:51 </td>
   <td style="text-align:left;"> $QQQ 318 would not be surprising next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:57:45 </td>
   <td style="text-align:left;"> $DIA $SPX $SPY $NDX $QQQ 

You literally got trapped in a sell that rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:57:03 </td>
   <td style="text-align:left;"> $QQQ $SPY everyone and their brother is tweeting how the market is going to crash into the depths of hell…uh…no it’s not.  Look at a fn chart, full employment equals stocks going up…💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:56:52 </td>
   <td style="text-align:left;"> S&amp;amp;P Sectors: Top 8 sectors above key -23.6% retracement levels. Mkt seem to be presenting a buy opportunity. 
 
$SPY $QQQ $DIA $XLY $XLB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:56:33 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ A matter of time until the FED will admit, we have lost control. The situation over Treasuries leaves no doubt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:54:28 </td>
   <td style="text-align:left;"> $QQQ stocks still go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:53:09 </td>
   <td style="text-align:left;"> $QQQ we have broken through the 200-day moving average again. Last time we saw was March 12, 2020. I would start taking more titles as a seller and not a buyer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:50:09 </td>
   <td style="text-align:left;"> Quality growth can beat inflation  
 
To beat inflation you choose stocks that don&amp;#39;t need capital during inflation periods. 
 
You choose companies that can raise prices &amp;amp; customer would still pay for it. 
 
Stay invested in companies that have pricing power 
 
$CRWD $OKTA $TTD $ZM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:49:23 </td>
   <td style="text-align:left;"> $QQQ we bounced of the 50dma pretty convincingly…. Tomorrow should be a theta burn unless we get some news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:47:51 </td>
   <td style="text-align:left;"> $QQQ short call buildup 358-360 and put build up at and below points to an upside squeeze tomorrow. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:47:09 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL   
surf report:   1st caution. 2 closes under red 9 day average line (average of candle prices)  
 
2nd.  Breakaway Gap down as momenutm is dropping lower.     momentum  about to go negative and looks strong!  a power selling candle breaking through cloud top support is next caution.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:45:43 </td>
   <td style="text-align:left;"> This market is not like a couple years ago where you can blindly buy the dip and get rewarded. Only traders that practice discipline and risk management are staying alive. Remember, the only way to be successful year after year is by practicing risk management. 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:45:38 </td>
   <td style="text-align:left;"> $QQQ people make up lots of sayings to decide whem to trade in various directions.  That stuff is all gibberish.  The only thing that matters is the price you buy, the dividends you collect, the price you sell, and the taxes you pay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:38:51 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/7/2022 $SPY $QQQ $NVDA $TSLA $CCJ https://www.chartguys.com/daily-market-videos/4210/daily-bounce-scout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:36:01 </td>
   <td style="text-align:left;"> $QQQ I was expecting a decent bounce today after the two big declines. The gap wasn&amp;#39;t filled as expected, not sure what tomorrow holds but next week may be ugly with the highest inflation print due out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:29:41 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
8% inflation 
0.25% interest rate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:28:41 </td>
   <td style="text-align:left;"> $QQQ i cant imagine being a qqq bear is not that lucrative </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:28:12 </td>
   <td style="text-align:left;"> $SPY $QQQ It is starting to be scary the way it is acting lately. I don&amp;#39;t like it at all. Looks like more downside is in the cards. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:25:48 </td>
   <td style="text-align:left;"> $SPY $QQQ

I owe those of you who actually trade futes an apology. You are certainly consuming higher quality drugs ro make that happen and we respect that.

On the other hand.. watching futes when you only make moves during cash session? You are a crackhead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:23:07 </td>
   <td style="text-align:left;"> $SPY Maybe 2.55s only, but rateageddon is coming and 2-year lead the way .
Brainerd is VP Chair, guys, the way the last vote went, she, and, Powell carried more weight than majority of committee that would have been justvas happy,, or,, even,, happier, with a better front-load rate, 0.50%, at last FOMC in mid March.

So now, Brainerd is hawkish and she&amp;#39;s likely following Powell, her Chair boss , so, we&amp;#39;ll know more when Powell speaks soon, so.... $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:18:48 </td>
   <td style="text-align:left;"> $QQQ May sit in this area for a couple weeks… burn the puts… time decay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:17:13 </td>
   <td style="text-align:left;"> $QQQ With current volatility, it might as well hit $360 and $340 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:16:23 </td>
   <td style="text-align:left;"> $spy $qqq https://www.youtube.com/watch?v=3J5KQkhcsaM&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:14:27 </td>
   <td style="text-align:left;"> $QQQ short the Nasdaq and get into GameStop for safety 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:13:07 </td>
   <td style="text-align:left;"> $QQQ everyone wants out and they will flood into GameStop and weed stocks for safety </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:09:05 </td>
   <td style="text-align:left;"> $QQQ only a matter of time before this matters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:06:58 </td>
   <td style="text-align:left;"> $QQQ $AMC  
All that you need to know... Shorts haven&amp;#39;t covered a single share ;  
highly recommend everyone to follow them 🚀🚀 
livestockchat.a0001.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:06:09 </td>
   <td style="text-align:left;"> $AMZN Can we kick this pig out of the indexes? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:05:24 </td>
   <td style="text-align:left;"> $DIA $NDX $NASDAQ $QQQ $SPY 

The lower we go this week 

The better off we will all be next week 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:05:07 </td>
   <td style="text-align:left;"> $SLV Now, that’s a pretty obvious massive bullish flag! $GDX $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:04:32 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Alright so if we&amp;#39;re truly in a bear tape tomorrow should be weak. Just fair warning. This doesn&amp;#39;t mean you can&amp;#39;t catch a gap or a pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:04:19 </td>
   <td style="text-align:left;"> $AMKR I don&amp;#39;t get why amkor is trading below full year sales p/s ratio of .7 it&amp;#39;s a fucking semi play $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:03:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X Friends, time could be shorter than anyone imagines.

Believe and trust in Jesus for the forgiveness of your sins today, and let today be THE day of your salvation!  (Romans 3:10/23, Romans 6:23, John 3:16/17, Romans 10:9/10, and Romans 10:13). 

I pray you hear Him calling you (and He is as well). ♥️✝️♥️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 06:01:50 </td>
   <td style="text-align:left;"> $XLU This is up almost 10% in a month as tech bleeds. Not bad for boring . $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:58:21 </td>
   <td style="text-align:left;"> $QQQ Bears really scared you got 1 min left </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:57:26 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $DIA  🧞‍♂️

$4380   Is   Next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:55:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 76484300. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:54:27 </td>
   <td style="text-align:left;"> $NVDA you skipped the $4440 bounce for v today 

So now it’s sell the rally $ES_F $SPX $QQQ 

You lose  🧞‍♂️🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:53:24 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://youtu.be/-HWwh6_9lM8 
 
No recession means stocks are going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:52:51 </td>
   <td style="text-align:left;"> $QQQ this stays between 350-355 all tmrw. Tmrw is not the day to trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:49:48 </td>
   <td style="text-align:left;"> $QQQ I bet we close around 351 tomorrow just to fuck options, if not then probably 356 because that fucks just a few more option buyers. Next week though..... Hehehehe.... Enjoy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:47:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Tomorrow we gut tom lee’s calls.😤🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:44:29 </td>
   <td style="text-align:left;"> Market Recap: Thursday - April 7, 2022 
 
If you like this newsletter, feel free to subscribe. It&amp;#39;s FREE, No Ads and you will only get one email per day after the market closes to make sense of what&amp;#39;s happening in markets 🙏 
 
https://marketcrier.com/markets/blog/market-digest/d028dcfa-17d5-442e-88e4-eb30e718a650 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:42:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $AAPL A sneak peak at the market tomorrow… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:35:56 </td>
   <td style="text-align:left;"> $SPY China sets off debt bomb on Sri Lanka, and now China will bail them out.  Sound familiar?  It should be because this is standard Chinese debt bomb strategy already played on many African countries, Venezuela, Brazil, and.. you&amp;#39;ve guess it.. USA.   Time is ticking... $dxy $uvxy $qqq https://www.youtube.com/watch?v=sPx3FEN3Gqs&amp;amp;ab_channel=WION </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:34:06 </td>
   <td style="text-align:left;"> $TMC 🤑

https://www.mining.com/web/lme-risks-more-squeezes-as-metal-stockpiles-hit-lowest-in-decades/

$QQQ $DJIA $IWM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:33:47 </td>
   <td style="text-align:left;"> $QQQ $spy needing a solid all in double by Xmas. See previous post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:33:24 </td>
   <td style="text-align:left;"> $QQQ $spy $20,000 goes to the person who has a large cap or mid cap non bio that can double by end of year. If successful $20k get sent to this lucky recommender. Go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:32:42 </td>
   <td style="text-align:left;"> $QQQ  $SPY  indexes trading like penny stocks. Look at these daily swings, bears and bulls get fucked daily. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:32:40 </td>
   <td style="text-align:left;"> $SPY $QQQ DYOR but the unemployment rate is always low before a recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:27:49 </td>
   <td style="text-align:left;"> $QQQ $SPY Some important dates that will set market directions in next few months. Buckle up: 

April 12 March CPI 
May 3-4 FOMC 
May 11 April CPI
June 14-15 FOMC
July 26-27 FOMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:25:20 </td>
   <td style="text-align:left;"> $SPY Put it in writing. 439 EOD. NO BODY wants to be long w/ CPI around the curve . Short&amp;#39;s fine, though 😌

Nobody! $QQQ $SOXX $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:23:08 </td>
   <td style="text-align:left;"> $QQQ $SPY $NVDA Anyone else seeing an inverse H&amp;amp;S nearly complete on the Daily chart? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:23:05 </td>
   <td style="text-align:left;"> $TQQQ Levels of liquidity to watch for going into tomorrow. 51.15 being the current support and 56.00 being the current resistance. $SQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:22:18 </td>
   <td style="text-align:left;"> $QQQ made a ton of money today on the qs. Thanks bears y&amp;#39;all got too greedy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:19:15 </td>
   <td style="text-align:left;"> NASDAQ $QQQ Top Gainers during today $COST $ORLY $IDXX $MRNA 
  
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:17:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X  hope everyone has a great rest of your day !! I hope y’all get rich and all your dreams come true. Welcome to the revolution welcome to the good life🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:17:19 </td>
   <td style="text-align:left;"> $SPY lol funny to see the market bounce off psychological pretty numbers still 😅😅 earnings justify the spy being around $300 not $400 

$AAPL $NVDA $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:14:07 </td>
   <td style="text-align:left;"> latexcede15793be840b22d7775a89a63a882 profit since his stake has been mentioned
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:12:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA WHAT IF MARK CUBAN HAD A SON NAMED REUBEN 🥪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:11:57 </td>
   <td style="text-align:left;"> $QQQ $SPY thinkin we fill the gap by tomorrow Monday. QQQ generally doesn’t leave gaps infilled for more than a few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:11:54 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $NDX $QQQ    🧞‍♂️🤑  

Sell now! Jamie diamond speak son Monday. 

Jamie Dimon’s gonna have nothing good to say about anything after reading his last   report that just came out three days ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:11:09 </td>
   <td style="text-align:left;"> Don&amp;#39;t Get Too Bullish On The $DXY! $DJIA $QQQ $VIX $SPY https://www.billionaireclubcollc.com/dont-get-too-bullish-on-the-dxy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:10:28 </td>
   <td style="text-align:left;"> $SPY $QQQ these charts look like the moment in 2017-18 when we got smoked in $BTC.X .. same pattern? = 1-2 years of pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:10:03 </td>
   <td style="text-align:left;"> $SPY gap down to he🏒🏒 $NASDAQ $IWM $QQQ $DYD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:09:53 </td>
   <td style="text-align:left;"> Live Updates | More funds proposed for Ukrainian defense https://www.billionaireclubcollc.com/live-updates-more-funds-proposed-for-ukrainian-defense/  $DJIA $QQQ $SPY $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:07:41 </td>
   <td style="text-align:left;"> $COST  Costco about to roll over 

  🧞‍♂️ $SPY $DIA $DJIA $QQQ 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:06:43 </td>
   <td style="text-align:left;"> $QQQ so proud, the Qs bounced off the 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:04:55 </td>
   <td style="text-align:left;"> $NQ_F: Perfect bounce off the 50 sma but still in no man&amp;#39;s land. Resistance at 14332. Above that, look for 14732 level and then 200 sma test (15149). Bulls do not want to see a retest of 50 sma. Break below that, we see 14085 next.  
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:01:57 </td>
   <td style="text-align:left;"> $XLK $QQQ head and shoulders in tech, might need a bit to play out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:01:09 </td>
   <td style="text-align:left;"> $QQQ $SPY what if this just ends up being Fib pullback from the rally and it launches before the actual dumpage? Lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 05:00:39 </td>
   <td style="text-align:left;"> $SPY $QQQ imagine listening to 70 year old incoherent boomers opine about today&amp;#39;s market and corporate debt environment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:59:12 </td>
   <td style="text-align:left;"> $BB the first domino is about to topple. $amd $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:55:36 </td>
   <td style="text-align:left;"> $QQQ $SPY.X 

closing near highs with small pullback is ok. No worries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:54:40 </td>
   <td style="text-align:left;"> $SCHD $XYLD making new highs while the market implodes $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:54:15 </td>
   <td style="text-align:left;"> $QQQ why is warren buffet still investing. Billions isn’t enough? He’s already in his 80s. Is he just that greedy? He should be praying and donating his last days lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:54:11 </td>
   <td style="text-align:left;"> I’m looking for a stock to short tomorrow somebody comment with suggestions 🥵
$SPY $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:52:17 </td>
   <td style="text-align:left;"> $QQQ the entire Fed board of governors will be fired if the market goes down any further </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:51:49 </td>
   <td style="text-align:left;"> 450 might be a little BIGGER than we thought $SPY  
Will we be able to get above it over night!? 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:51:47 </td>
   <td style="text-align:left;"> $QQQ sideways tomorrow I’m pretty sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:51:42 </td>
   <td style="text-align:left;"> $SPY $QQQ So if you were sitting on completely ridiculous gains on the crazy run recently in utilities, banks, health care and consumer staples, what would you do? 🤔

I&amp;#39;m finding it very hard to justify holding something that now yields 3% when bonds and GICs can be bought right now for 3.5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:50:28 </td>
   <td style="text-align:left;"> $SPY what happens to the market if Joe gets COVID? $DYD $IWM $NASDAQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:49:36 </td>
   <td style="text-align:left;"> $SPY $QQQ it was a horrible close no other way to spin it. 

(Bulls; always remember to say &amp;quot;its all priced in..&amp;quot; it will make you feel much more comfortable with your current position...) 

$SQQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:48:49 </td>
   <td style="text-align:left;"> $SPY $QQQ who is the Fed doing all of this jaw-boning for? 401k holders certainly didn&amp;#39;t ask for the Fed to blow up their retirement accounts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:44:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ - Apple is failing to break its resistance levels. The possible double-top or new ATH is growing weaker and weaker. We could see prices head back below $160. Without the Fed, there is nothing much markets can do at this point. Corporate Buy Backs only go so far and QE is &amp;quot;technically&amp;quot; over according to the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:43:30 </td>
   <td style="text-align:left;"> $QQQ $SPY Anyone want to make a logical and technical explanation for what happened at noon? The only theory I have is the MM needed to move it up a bit to hit max pain tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:42:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $HPQ  
 
Kinda crazy Warren Buffet can buy anything then announce that he bought it and make millions on the news that he bought. He could do that every month with a different stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:42:25 </td>
   <td style="text-align:left;"> $QQQ Tomorrow they will either kill the 20+k puts at 355 or it will stay within 350-354.99, one thing is for sure those 350 puts are going to expire worthless. We saw that today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:40:45 </td>
   <td style="text-align:left;"> I’d like to see if 344 will be tested on $QQQ tomorrow. Maybe a run towards 380 next. Closing below 350 will give me that idea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:40:24 </td>
   <td style="text-align:left;"> $QQQ down tommorow forsure 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:39:49 </td>
   <td style="text-align:left;"> $AAPL $QQQ - Apple touched $169 today. This is confirming more and more that Apple may not set a new ATH, not even a double-top. Checking economic data, FOMC, and geopolitical status, we could see a continuation of what was the start of a bear market in January pretty soon. There isn&amp;#39;t much in terms of fuel left for a rally. QE is &amp;quot;technically&amp;quot; over and upcoming earnings are probably not going to be great. Funny how Apple never releases guidance. Apple is reporting dismal sales with their iPhone SE and Mini&amp;#39;s. Add to this worse than expected Consumer Sentiment, earnings season isn&amp;#39;t looking great. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:39:35 </td>
   <td style="text-align:left;"> $QQQ terrible close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:37:49 </td>
   <td style="text-align:left;"> $SPY $QQQ it&amp;#39;s comical the lying Fed is still claiming they are going to fight inflation. If they were really going to do anything meaniful they wouldn&amp;#39;t STILL be waiting to start the balance sheet runoff and the Fed funds rate would not be at 25bps. The truth is they can&amp;#39;t really fight inflation if they did the entire economy would crash and the government would not be able to make its interest payments on all it&amp;#39;s debt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:37:02 </td>
   <td style="text-align:left;"> $QQQ Btc&amp;gt;puts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:35:19 </td>
   <td style="text-align:left;"> Tech rebound lifts stocks on Wall Street after early slide https://www.billionaireclubcollc.com/tech-rebound-lifts-stocks-on-wall-street-after-early-slide/ $SPY $DJIA latex160b17ed2ea8b149737e065a0650eac8NVDA  
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:31:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM - still looking to re-buy these (see my 3/28 tweet) 
If I only look at my analysis, I would have predicted a down day (about -.5%)...but we&amp;#39;re up on all indices, except the Russell...of course. 
Regardless, it&amp;#39;s a &amp;quot;bleh&amp;quot; day.  A kind of day that doesn&amp;#39;t do anything to change existing sentiments.  If you&amp;#39;re already in the market, or not, you&amp;#39;re likely staying put.  However, a nice V-shape day for the day-traders. 
Anyone long/short today?  Which stocks/ETFs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:30:28 </td>
   <td style="text-align:left;"> $QQQ you see how they&amp;#39;re keeping markets proped up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:29:54 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $BTC.X 
     
What to do when your administration is the biggest failure of a lifetime?   
   
Divert people&amp;#39;s attention into a proxy war with Russia! 
  
Nothing more dangerous to America and the international community than a failed administration looking for a distraction. 
 
https://www.washingtonpost.com/politics/2022/04/07/biden-war-ukraine/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:29:13 </td>
   <td style="text-align:left;"> $QQQ gap down going to be insane tomorrow 🥺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:28:27 </td>
   <td style="text-align:left;"> $QQQ WOW cant even fill the gap. AH selloff.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:28:12 </td>
   <td style="text-align:left;"> $SPY $QQQ posting this for tonight cause I will sadly miss the overnight crew tonight - fUtEs RiPpIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:24:45 </td>
   <td style="text-align:left;"> $QQQ inverted H&amp;amp;S.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:24:35 </td>
   <td style="text-align:left;"> $DTST let&amp;#39;s get her trending  $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:22:21 </td>
   <td style="text-align:left;"> $SPY Most likely goes up still since $QQQ hasn&amp;#39;t filled its gap too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:18:41 </td>
   <td style="text-align:left;"> $QQQ Haha 
 
Shameless beartard morons still posting hopeless FUD that nobody cares about. 
 
Markets only want to go UP and dont care about your shit. 
 
Imagine Elon buying ST and banning all the clueless shortie broke-ass trolls with NO SKIN IN THE GAME .... LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:17:49 </td>
   <td style="text-align:left;"> Fed casting its inflation fight as battle against inequality https://www.billionaireclubcollc.com/fed-casting-its-inflation-fight-as-battle-against-inequality/  $DJIA $QQQ $DXY $SPY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:17:03 </td>
   <td style="text-align:left;"> $QQQ 20 dollar drop

bulls:

5 dollar relief rally massive profit taking on shorts

bulls: THATS THE BOTTOM ATHS NOW V SHAPED RECOVERY MELT UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:16:41 </td>
   <td style="text-align:left;"> Biden bets strong job market will shield economy from slump https://www.billionaireclubcollc.com/biden-bets-strong-job-market-will-shield-economy-from-slump/  $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:15:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:14:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:13:50 </td>
   <td style="text-align:left;"> $QQQ $SPY going nowhere with tech dying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:13:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:13:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 4/8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:12:38 </td>
   <td style="text-align:left;"> $CNHI CATALYST: Annual General Meeting of Shareholders is happening on Wed. Apr. 13 at 9:00 AM. 
 
View details and track upcoming catalysts: https://www.catacal.com/catalyst/annual-general-meeting-of-shareholders 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:10:22 </td>
   <td style="text-align:left;"> $FCEL $SPY $QQQ
FuelCell Energy has the carbon capture answer.

https://doi.org/10.1016/j.apenergy.2022.118553

“In this report, the use of molten carbonate fuel cells (MCFCs) to capture CO2from cogen units is investigated and shown to be highly efficient due to the additional power that they produce while capturing the CO2. Furthermore, the MCFCs are capable of reforming methane to hydrogen simultaneous to the power production and CO2capture. This hydrogen can either be recycled as fuel for consumption by the cogen or MCFCs, or exported to an independent combustion unit as low carbon fuel, thereby decarbonizing that unit as well.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:09:41 </td>
   <td style="text-align:left;"> $QQQ unwinding 11 trillion balance sheet ohh boy, 80% of investors didn’t go through that. = 30% haircut in QQQ SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:08:30 </td>
   <td style="text-align:left;"> $SPY $QQQ A great day. It looked like it would be another red day initially but then we saw dips buyers coming in and bought stocks up. BTFD remains the best way to make this money in this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:08:20 </td>
   <td style="text-align:left;"> $QQQ 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:06:24 </td>
   <td style="text-align:left;"> $WMT PUTS got roasted in Wally World 🌎  
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:05:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA the FED should not be able to come out in mainstream media and speak. They should be only allowed to speak at their meetings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:04:55 </td>
   <td style="text-align:left;"> Market wrap: 
🔷 US indices shrugged off early losses to close higher on the day:  
$DJIA +0.3%, $SPX +0.4%, $QQQ +0.2% 
🔷 #Gold (+0.6%) and #WTI (+0.7%) both edged higher as well. 
🔷 #GBP was the day&amp;#39;s strongest major currency; #AUD was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:04:47 </td>
   <td style="text-align:left;"> $SPY Perfect, if was ended 443, it wouldn&amp;#39;t go much down on a Friday but now it&amp;#39;s gonna really move like a down rollercoaster $QQQ

#ROOMTOMOVE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:03:52 </td>
   <td style="text-align:left;"> $qqq.  $hyg junk bonds didn&amp;#39;t participate on the afternoon bounce today. Something to watch out for over the next several days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:03:40 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Piggie now holding 4 MES with average at 4496. 
 
He is building swing short on all rips higher. 
 
gl! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:03:10 </td>
   <td style="text-align:left;"> $QQQ awesome trading day today. Nearly $53k. 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:02:35 </td>
   <td style="text-align:left;"> $ES_F $SPY $NQ_F $QQQ Sell sig flagged into the close, resets, but the closes were great. Gap up in focus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:02:13 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $goog  What a rush  into close...AM thinking tomorrow fonna be massively green 🔥🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:02:06 </td>
   <td style="text-align:left;"> $AAPL not a bad trade for 5 mins 🔥🔥🔥🔥🔥 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:02:05 </td>
   <td style="text-align:left;"> $QQQ $VIX $FAST $SJR $RAD  
Earnings season is here.  Earnings Reports Next Week  
 
https://www.financegreater.com/earnings-calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:02:00 </td>
   <td style="text-align:left;"> $QQQ decent week so far on my fun account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:59 </td>
   <td style="text-align:left;"> City National Rochdale CIO Expects Secular Strength of U.S. Economy to Offset Global Pressures

https://www.bakersfield.com/ap/news/city-national-rochdale-cio-expects-secular-strength-of-u-s-economy-to-offset-global-pressures/article_982e4ff2-00c0-597e-a2f6-cdff6598fdc5.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:51 </td>
   <td style="text-align:left;"> $QQQ Holding 352 puts and 358 calls overnight. I want to think tomorrow will be flat overall, but there will be one big swing and then an opposite move to cancel it out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:39 </td>
   <td style="text-align:left;"> $FB The 50MA is right there so I’m waiting to add Ps. See what Friday brings. Need the day with more cash 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:31 </td>
   <td style="text-align:left;"> $QQQ 😆 this thing can&amp;#39;t even fill the gap.

tomorrow  will be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:30 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:08 </td>
   <td style="text-align:left;"> $QQQ they ran this algo a few weeks back. Still opened at the target 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:06 </td>
   <td style="text-align:left;"> $QQQ $354p we banking...play by play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:01:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $TNX revolving credit is
Also rapidly expanding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:00:38 </td>
   <td style="text-align:left;"> $QQQ After a deafening silence, the idiot bozos are back on here spouting their crap. 
 
Everything&amp;#39;s priced in markets want to go UP. 
 
Deal with it losers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:00:31 </td>
   <td style="text-align:left;"> $FB they love selling at that 225 mark. Ended back under the 50MA 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:00:26 </td>
   <td style="text-align:left;"> $QQQ $354p 1.67-2.20+.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 04:00:04 </td>
   <td style="text-align:left;"> Why The US Economy And The Stock Market May Be Better Off Than They Seem

https://www.benzinga.com/amp/content/26521747

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:59:42 </td>
   <td style="text-align:left;"> $SPY Wall Street throws a temper tantrum during FED speakers and then the speakers mute real feelings and market foes up aft.

Yrs, this is normal 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:58:58 </td>
   <td style="text-align:left;"> $QQQ I played today perfectly, not usually into day trading, but god dam. 
 
Too easy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:58:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA AIRCRAFT CARRIER MONEY GO BYE BYE 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:58:38 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ Treasuries on very very hard sell-off. The market will soon panicking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:58:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $TNX Total consumer credit hitting all time highs. Keep in mind this is likely due to inflation. Either way it&amp;#39;s clear what is driving the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:57:34 </td>
   <td style="text-align:left;"> $QQQ $spy wont be surprised if this ends -1% in last 3mins.... thats what a trash gamblers market is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:57:09 </td>
   <td style="text-align:left;"> $SPY Beautiful Close  
$QQQ 😁😁😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:56:35 </td>
   <td style="text-align:left;"> $SPY $QQQ oh boy... what an ugly close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:56:06 </td>
   <td style="text-align:left;"> $QQQ Breakdown of 200 MA - it&amp;#39;s time to bottom this bitch out back to prior lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:56:05 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s criminal how hedgies pump this to unload bags onto retail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:56:04 </td>
   <td style="text-align:left;"> $SPY Consumer Credit #?
Brings one word to mind.

Inflation-inflation-inflation.

$QQQ $SOXX $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:55:41 </td>
   <td style="text-align:left;"> $QQQ out the short  +1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:55:27 </td>
   <td style="text-align:left;"> $QQQ retail about to get dumped on AH and tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:55:25 </td>
   <td style="text-align:left;"> $QQQ $spy bunch of dumb algos and option gamblers not a real market........... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:55:15 </td>
   <td style="text-align:left;"> $QQQ Don&amp;#39;t fight the FED. Wasn&amp;#39;t that the prevailing narrative over the past decade? All of a sudden it seems investors want to fight the fed because they don&amp;#39;t want the party to stop. Classic signs of a bubble that&amp;#39;s about to burst. When the Fed&amp;#39;s most dovish member starts talking of balance sheet reduction, that&amp;#39;s when you should start paying attention. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:55:08 </td>
   <td style="text-align:left;"> $QQQ Silly bulls will never learn. This is a bear market 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:54:34 </td>
   <td style="text-align:left;"> $QQQ $360 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:54:04 </td>
   <td style="text-align:left;"> Senate Confirms Ketanji Brown Jackson For Supreme Court https://www.billionaireclubcollc.com/senate-confirms-ketanji-brown-jackson-for-supreme-court/ $DJIA $QQQ $DXY $VIX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:54:01 </td>
   <td style="text-align:left;"> $spy $qqq  
BULL MARKET selling  
 
the scared coward selling has subsided as the smart money rolls in. 
as posted that it would. 
actually lasted about a 1/2 longer than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:54:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 78153100. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:53:56 </td>
   <td style="text-align:left;"> $SQQQ what a mess, after going back and forth decided to add 350, at $35.29 to take my position back up to 1K shares.  I think tomorrow will be a red day for the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:53:53 </td>
   <td style="text-align:left;"> $QQQ vlad is selling calls rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:52:12 </td>
   <td style="text-align:left;"> $QQQ 2/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:52:00 </td>
   <td style="text-align:left;"> $SPY $qqq imagine having a real stock market index at 1 month highs today ytd +2% and max drawdown this week 0.9%.... oh wait there is an index called $ewu meanwhile trash usa down 6% in 2 days on 1 person comment..... @Options_Destroyer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:51:58 </td>
   <td style="text-align:left;"> $QQQ 1/2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:51:33 </td>
   <td style="text-align:left;"> $SPY / $QQQ - Clear enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:50:54 </td>
   <td style="text-align:left;"> $SPY $QQQ bulls just showed the middle finger to the fed. Let&amp;#39;s see who wins 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:50:54 </td>
   <td style="text-align:left;"> $SPY LOW TICKS -1061 $IWM $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:50:12 </td>
   <td style="text-align:left;"> $SPY All those home mortgage down payments &amp;amp; vehicles put on plastic with riding nuts interests rates?
Yikes! 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:48:37 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
still working...over and over!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:48:17 </td>
   <td style="text-align:left;"> $AMC $GME $QQQ $SPY Something big comin. I’m callin a blow off top on the spy. Got my $61-$70 calls. Maybe even Moass for memes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:47:33 </td>
   <td style="text-align:left;"> The Best and Worst Federal Reserve Chairs

https://money.usnews.com/investing/stock-market-news/articles/all-16-fed-chairs-ranked-by-stock-market-performance

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:47:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $BTC.X  
 
Why does it seem Iike aII of Bidens nominees hate America? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:46:48 </td>
   <td style="text-align:left;"> Biden Bets Strong Job Market Will Shield Economy From Slump

https://www.usnews.com/news/business/articles/2022-04-07/biden-bets-strong-job-market-will-shield-economy-from-slump

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:46:45 </td>
   <td style="text-align:left;"> $QQQ 20-May-22 355 Puts Traded 1,000 Times for $1.5 Million in Premium. https://tinyurl.com/ydepau5l </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:46:26 </td>
   <td style="text-align:left;"> $QQQ why are bears posting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:46:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Hahaha!  
 
https://twitter.com/mademe__smile/status/1512004992537808899?s=20&amp;amp;t=AgZ-Xnp6u06DyZyEbmO1FA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:46:15 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
still working... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:45:31 </td>
   <td style="text-align:left;"> $SPY $QQQ This was a fun day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:45:15 </td>
   <td style="text-align:left;"> $QQQ RSI on VIX hasn&amp;#39;t been above 31 in almost 1.5 hours on 1 Day /5 min chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:44:31 </td>
   <td style="text-align:left;"> $QQQ I was expecting a strong bounce to fill the gap today. Let&amp;#39;s see what happens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:44:15 </td>
   <td style="text-align:left;"> $QQQ you better buy before close. This rockets tomorrow into next week. Don’t miss out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:43:56 </td>
   <td style="text-align:left;"> $SPY $QQQ The market looking completely unstoppable here, we are gonna take off once Q1 earnings start to come out and fully priced into the rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:43:55 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:43:53 </td>
   <td style="text-align:left;"> $QQQ We are ALL being played. 
GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:43:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM  
Great trading for me today..If you followed my advice , $5 bucks only, or sign up at the web for 20 bucks, you will play it right today.  So, we bought market as market was going down!!!!  to see huge upside later!  
 
Because i am in a good mood, i will tell you signal for free for tomorrow (not final signal, estimation): IT WILL BE BULLISH MOST LIKELY. 
 
#success #influencer #stocktrading #stockstrategy #stocks #stockmarket #trading #investing #hedgefund #algotrading #wealth #profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:43:20 </td>
   <td style="text-align:left;"> $SPY low ticks -620 $iwm $qqq $djia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:43:08 </td>
   <td style="text-align:left;"> $QQQ This will go up more tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:42:52 </td>
   <td style="text-align:left;"> So when will $RUT wake up? +17% since the pre-pandemic high of Jan 2020. Compared to +35% for the $SPY and +58% for the $QQQ in the same period of time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:42:32 </td>
   <td style="text-align:left;"> $QQQ $spy why u shud never put $$ in this gambling market....  how can the stocks be worth -2% then be +1% 2hrs later???? no real value just gambling option traders and algos pointless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:42:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA DO THEY SELL ASTRONAUT SUITS AT THE SUIT STORE? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:42:05 </td>
   <td style="text-align:left;"> $QQQ SOME bears will keep saying its gonna crash for years. They are right ONCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:41:54 </td>
   <td style="text-align:left;"> $SPY $QQQ just droppin&amp;#39; this here 
 
Free to join: https://discord.io/MTrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:41:09 </td>
   <td style="text-align:left;"> $QQQ 7 points reversal for absolutely nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:40:19 </td>
   <td style="text-align:left;"> $QQQ don&amp;#39;t fight the Feds. This goes both ways. Feds are no longer printing, they are shredding. Ya&amp;#39;ll about to find out how monetary policy dictates the markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:39:27 </td>
   <td style="text-align:left;"> You know I was afraid the stock was going to jump tomorrow after the event if it closed red-- but now I no longer fear that outcome $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:38:55 </td>
   <td style="text-align:left;"> $QQQ the rally is getting tired </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:38:47 </td>
   <td style="text-align:left;"> $TMC Russian nickel ban update. 🚀

- US to impose heavy tariffs on Russian metals which will include nickel
- Canada has sanctioned Vladimir Potanin. He is the boss of Russia’s Nornickel 
- EU has imposed a transport blockade affecting Russia’s nickel shipments 

$DJIA $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:36:46 </td>
   <td style="text-align:left;"> $SPY $QQQ who loading dem cheapies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:36:42 </td>
   <td style="text-align:left;"> $QQQ how bulls thought today would be vs how it really </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:36:35 </td>
   <td style="text-align:left;"> $QQQ on Monday I bought puts ( had to go long to offset but essentially kicked myself out of my weekly hitter).  Tuesday and Wednesday I took stupid longs ( profitable yes but smart, not so much) Today I got it together looking for bigger picture moves.  

Less is more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:35:06 </td>
   <td style="text-align:left;"> $SPY $DJIA $DIA $QQQ $NASDAQ I won&amp;#39;t be surprised of another &amp;#39;Black Monday &amp;#39; crash. Things are out of control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:33:45 </td>
   <td style="text-align:left;"> $QQQ some plays are only scalps others are a day trade where you collect your money end of day. Know the difference. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:33:02 </td>
   <td style="text-align:left;"> $SPY gap filled on daily no longer extended , $QQQ $IWM still extended </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:32:10 </td>
   <td style="text-align:left;"> $QQQ 

Might be queuing up some of those lovely FU candles

In either direction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:31:17 </td>
   <td style="text-align:left;"> $QQQ 10-Minute Chart. Afternoon rally takes us back up to scene of resistance intraday from last two sessions, since gap down below $358 yesterday morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:31:13 </td>
   <td style="text-align:left;"> $QQQ this whore is using MAs as trampolines. Gimmie 360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:31:10 </td>
   <td style="text-align:left;"> $QQQ anyone have news for pump??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:30:08 </td>
   <td style="text-align:left;"> $QQQ 

Printed

353 close solid

Do I care if that&amp;#39;s wrong? Neva neva! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:30:04 </td>
   <td style="text-align:left;"> $QQQ big rug pull or continue up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:29:49 </td>
   <td style="text-align:left;"> $QQQ I guess people already forgot we are going up 50 points at a time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:29:32 </td>
   <td style="text-align:left;"> $SPY $QQQ buybacks ending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:29:15 </td>
   <td style="text-align:left;"> $spy $qqq I got this super terrible feeling.... Maybe I should buy more? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:29:02 </td>
   <td style="text-align:left;"> Industry Groups Bell Curve – Exclusive to Stage Analysis has been posted for members 
 
Updated graphic of the 104 Industry Groups showing the Percentage of Stocks Above Their 30 Week Moving Average in each group visualised as a Bell Curve 
 
#stocks #trading $SPY $QQQ $IWM  
https://www.stageanalysis.net/blog/169626/industry-groups-bell-curve-exclusive-to-stage-analysis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:28:48 </td>
   <td style="text-align:left;"> $QQQ resilient little fella gonna playing both sides next few months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:28:43 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;ll just throw this out there... lots of work still to be done to confirm the pattern, but it&amp;#39;s 1 interpretation (of which there are many). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:28:19 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $NASDAQ $EURUSD Do you understand the panic Sell-off over Bond market and Treasuries right now,means GAME is OVER?

Do you understand that the FED isn&amp;#39;t your friend anyone? 

Do you Understand that the Fed sell-off start soon and Yields Might be doubled ?

Do you understand the Borrowing cost Skyrocket means Officially IPO and Re-finance super high costs ?

Possible Another Sub prime Crisis per JPMorgan.qs they warn if more 40% Commodities spikes ahead ( a secondary effect also on household debt too). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:28:05 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:27:40 </td>
   <td style="text-align:left;"> $TQQQ a lot of active buying since 52.50. Full recovery complete 👍 Next critical resistance ahead is 56.00. $SQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:27:32 </td>
   <td style="text-align:left;"> $QQQ insane volatility.. wouldn&amp;#39;t bet on a bullish trend with CPI/PPI out next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:26:59 </td>
   <td style="text-align:left;"> $QQQ VIX is down under - long live the volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:26:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM

https://youtu.be/LklveYZH7r4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-08 03:26:33 </td>
   <td style="text-align:left;"> $QQQ this tos update sucks. Made the app so slow and laggy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 09:21:52 </td>
   <td style="text-align:left;"> $AAPL just bought another MacBook, trying to help the cause one M1 Chip at a time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 09:21:51 </td>
   <td style="text-align:left;"> $ATER  somebody must know how to do $GME $AMC $SSC
Anybody @ $AAPL that can help? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 09:09:10 </td>
   <td style="text-align:left;"> $AAPL The stock is goin down very slowly on lower volume. All sales are bought and more. That’s saying that it’s just a retracement leg before next up move. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 09:01:18 </td>
   <td style="text-align:left;"> $AAPL lmao u got me good today, i was 3/3 on plays today and then i got puts at 171.30 and went to make some food, when i got back it was too late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:52:31 </td>
   <td style="text-align:left;"> $AAPL easy money on apple $VXX $SHIB.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:50:37 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE 🔥 
#LOTTO FRIDAY PICKLIST 
IM GOING TO BREAKDOWN 👇 
📈TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS  
CLICK&amp;gt; https://us02web.zoom.us/j/89457164243 
 $SPY  #trading  #Invest  #stocks $AAPL  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:41:22 </td>
   <td style="text-align:left;"> $AAPL 😊https://youtu.be/Th4E-0VFaEA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:34:05 </td>
   <td style="text-align:left;"> $TSLA this is so gonna SELLOFF 📉⬇️⬇️⬇️tomorrow! Wall Street has all of your LOTTO CALLS trapped! They knew the fan bois would be in their ELON JOCK STRAP FEELINGS 🥴🙃🤡..  
 
NO WORRIES,  I stopped by to drop off a consolation prize while your real money goes to to bears! 🙋‍♂️💦💸 $nio $aapl $SPY $rivn etc 
 
Ladies and gentlemen  - The CyberDUMP 🍑💦😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:20:47 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/D0bO_OHw0LM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:19:57 </td>
   <td style="text-align:left;"> Dark pool after hours activity in 
 
$PDD - $111M print 
$FB - $277M print 
$AAPL - $412M print 
$NVDA - $126M print 
$MSFT - $386M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:18:35 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:17:56 </td>
   <td style="text-align:left;"> $AAPL Anyone the least bit concerned about the CPI numbers on Tuesday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:17:24 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMD hosting a session on zoom tonight about how to daytrade weekly option... Dm me if you wanna join...free for public. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:16:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:15:46 </td>
   <td style="text-align:left;"> New Video!  
 
Elasticity, Yield Curve Inversion and The Fed! 
 
https://www.youtube.com/watch?v=DmruxZfRMpQ 
 
$SPY $QQQ $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:08:30 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $AAPL with Unusual Options Activity Alerted on $170 PUT Expiring: 05-20-2022 worth 1700K🐻 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:05:39 </td>
   <td style="text-align:left;"> According to the @TipRanks database, 2 of the TOP Wall Street analysts in the #tech sector r from @Oppenheimer. 
 
They have a success rate of 50%-74%.  Interesting none of the top sell short. 
 
$AAPL $NVDA $AMD $TWTR $TSLA  
 
Check out the Rankings 
👇 
https://t.co/5GFimMMVAr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:05:11 </td>
   <td style="text-align:left;"> Most Traded Contracts

$AAPL 08 April $175 Call
$AAPL 08 April $172.50 Call
$AAPL 08 April $170 Put
$TSLA 08 April $1100 Call
$KGC September $5 Put
$OPEN January 2023 $12.50 Call
$OPEN January 2023 $15 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:03:49 </td>
   <td style="text-align:left;"> $SPY  I guess no one told spy there was still Neckline Resistance 🤷‍♂️ $UVXY $QQQ $TSLA latexd8e4b8cb69a14dcc42e80778b66ba1e0TSLA 1.411m (59% call/41% put)
$AAPL 1.065m (59% call/41% put)

https://bit.ly/sweepcastoptions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:03:20 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-07 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=XBiegaPR1h4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:00:55 </td>
   <td style="text-align:left;"> $AAPL Fuck your calls and fuck your puts, without either this POS would be at $165ish.  They’ll steal all premiums and end this week at $172.50.  Maybe they flush it the last hour of the day to $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 08:00:09 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $185.00 Call for Friday, June 17, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:59:39 </td>
   <td style="text-align:left;"> $AAPL couldnt close above avwap. probably nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:55:27 </td>
   <td style="text-align:left;"> $SPY Jacked to the tits w $AAPL calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:39:44 </td>
   <td style="text-align:left;"> $AAPL will 175 call or 170 put print tomorrow. what’s everyone’s thoughts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:39:08 </td>
   <td style="text-align:left;"> $AAPL I believe we break the $169 Support Tomorrow &amp;amp; Test the $167-$168 levels. Rally eod was a bull trap.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:35:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $DJIA  
Market Movers Economic Events Next Week      
 
https://www.financegreater.com/economiccalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:29:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL $TWTR This is a MUST WATCH for these tickers especially!
Make sure you SUBSCRIBE and click the ALERTS on our channel so you don’t miss our videos!
Happy STACKS tomorrow 😎

https://youtu.be/B3nn1ZRLM98 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:24:04 </td>
   <td style="text-align:left;"> $AAPL $SPY any other time in the past couple years, I’d say things were set up for a nice run tomorrow or at least get pinned. Given the ridiculous volatility and managers being a bit more assertive, it could be a bad day. $SPY. I’m long ADRs short US tech. Will average down on them tomorrow if need be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:23:46 </td>
   <td style="text-align:left;"> $AAPL the one thing I regret in life is not holding on to apple after the stock split. I’m back in but at a much higher price but this time I’m doing it right, recurring investment every week like a 401k until I’m ready to retire in 20 years.. ran my numbers through a investment filter, 1.8 million by the time I’m 60.. just have fun killing time in between.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:21:11 </td>
   <td style="text-align:left;"> $AAPL 
 
Do current fundamentals justify AAPL&amp;#39;s valuation? 
 
https://utradea.com/positions/Do-current-fundamentals-justify-AAPLs-valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:19:32 </td>
   <td style="text-align:left;"> $AAPL Look! $1530 net profit. 7 close trades. 71% win rate. 3 profit factor in a 15 minutes chart. Waiting for Buy signal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:18:46 </td>
   <td style="text-align:left;"> $AAPL Interesting correlation with $BTC.X YTD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:17:58 </td>
   <td style="text-align:left;"> $AAPL  fake down tomorrow for the bears  before this touches new highs next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:12:39 </td>
   <td style="text-align:left;"> $SPY With CPI Tuesday, this ain&amp;#39;t going anywhere worth mentioning, unless, you talkin&amp;#39;..... 
$QQQ $SPXL $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:12:02 </td>
   <td style="text-align:left;"> $AAPL 🍏👍💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:10:10 </td>
   <td style="text-align:left;"> $AAPL $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:07:12 </td>
   <td style="text-align:left;"> $TSLA $SPY $BOXL $AAPL $AYRO Top trendin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:06:07 </td>
   <td style="text-align:left;"> $AAPL  Look! I got this 75% Profitability across 4 trades in 1 month. Profit Factor of 10 and rating is Bearish.  I will wait for Short signal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 07:00:22 </td>
   <td style="text-align:left;"> $AAPL $170 or $175tomm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:54:38 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #2 ticker with sweep activity where institutions are trading options urgently with 38.0K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:50:47 </td>
   <td style="text-align:left;"> $AAPL https://seekingalpha.com/article/4498257-apple-stock-subscriptions-arent-new?source=copy_to_clipboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:47:09 </td>
   <td style="text-align:left;"> $SPY  $QQQ $AAPL   
surf report:   1st caution. 2 closes under red 9 day average line (average of candle prices)  
 
2nd.  Breakaway Gap down as momenutm is dropping lower.     momentum  about to go negative and looks strong!  a power selling candle breaking through cloud top support is next caution.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:47:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Be conservative with FAANG stocks as anticipated Fed rate hikes spurn a market pivot, Jim Cramer says https://www.stck.pro/news/AAPL/25796471 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:31:51 </td>
   <td style="text-align:left;"> You know the market is crazy when you see $TSLA $AAPL  $DPRO bearish for two three days despite having a long-term bullish sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:23:32 </td>
   <td style="text-align:left;"> $AAPL show me 167! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:17:05 </td>
   <td style="text-align:left;"> $aapl $msft $fb https://www.youtube.com/watch?v=H0V6_VgPUjU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:16:13 </td>
   <td style="text-align:left;"> $AAPL  
 
Do current fundamentals justify AAPL&amp;#39;s valuation? 
 
https://utradea.com/positions/Do-current-fundamentals-justify-AAPLs-valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:15:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:13:37 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #20 ticker with unusual activity from institutional traders with an average of 13% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:12:37 </td>
   <td style="text-align:left;"> AAPL, TSLA, GOOGL, AMZN, FB: Why Are Nasdaq Stocks Down Today?

$GOOGL $AAPL $TSLA $FB $AMZN  

https://investorplace.com/2022/04/aapl-tsla-googl-amzn-fb-why-are-nasdaq-stocks-down-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:09:34 </td>
   <td style="text-align:left;"> $aapl pullback continues…looking for test of the 50 dma https://youtu.be/OzO1GLhR3IY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:06:05 </td>
   <td style="text-align:left;"> $AAPL This is correct

https://appleinsider.com/articles/22/04/07/apple-well-positioned-to-weather-consumer-spending-headwinds-analyst-says?utm_source=&amp;amp;utm_medium=&amp;amp;utm_campaign=RSS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:04:47 </td>
   <td style="text-align:left;"> $SPY $AAPL   made it to ichimoku cloud armpit level and sold off.. Billions being sold in Darkpool .. Caution for distribution at cloud top level and sold off as momentum about to go negative. caution for the wave lower! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:03:18 </td>
   <td style="text-align:left;"> $SPY $AAPL #DIA   cloud top equilibirum rejection caution as momentum about to go negative!  #Nacho #Cheese </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:02:21 </td>
   <td style="text-align:left;"> $SPY $AAPL #QQQ   
 
#QQQ momenutm caution after cloud equilibrium resistance rejection </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 06:01:41 </td>
   <td style="text-align:left;"> $SPY up 12% on the one year. You think inflation is priced in? $IWM $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:57:15 </td>
   <td style="text-align:left;"> $AAPL What was the big announcement !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:56:25 </td>
   <td style="text-align:left;"> $SPY Look how futures first broke resistance and then confirmed support, the next question is if it can stay above it let’s see tomorrow $IWM $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:54:08 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Are you sure Hank done it this way? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:47:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Tomorrow we gut tom lee’s calls.😤🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:42:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $AAPL A sneak peak at the market tomorrow… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:40:50 </td>
   <td style="text-align:left;"> $AAPL getting close here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:40:38 </td>
   <td style="text-align:left;"> $AAPL almost back in $160’s range </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:32:45 </td>
   <td style="text-align:left;"> $CRWD $300 soon 
CrowdStrike Holdings (CRWD) said Thursday it can now deploy its Falcon cybersecurity platform to a broad range of Department of Defense and Defense Industrial Base customers to protect their Controlled Unclassified Information after securing a Provisional Authorization to Operate at Impact Level 4. 
$aapl $nvda $cost $fb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:32:10 </td>
   <td style="text-align:left;"> $AAPL Closed all position with profit, now just looking for next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:26:48 </td>
   <td style="text-align:left;"> Is it Time to Bet on These 3 Unstoppable Growth Stocks Again? 
 
A low interest rate environment allowed growth companies access to cheap capital and fund their expansion plans. However, in recent months, growth stocks...$PYPL $FB $AAPL $SQ  
 
Learn more:https://www.finscreener.org/blog/is-it-time-to-bet-on-these-3-unstoppable-growth-stocks-again-575b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:20:50 </td>
   <td style="text-align:left;"> $AAPL is one of the top trending stocks on Stocktwits and Twitter, here are the latest numbers: 
 
8.2M Twitter Impressions 
1.58M Stocktwits Impressions 
 
Link in bio to see real-time social sentiment trends, don&amp;#39;t miss out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:17:19 </td>
   <td style="text-align:left;"> $SPY lol funny to see the market bounce off psychological pretty numbers still 😅😅 earnings justify the spy being around $300 not $400 

$AAPL $NVDA $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:15:49 </td>
   <td style="text-align:left;"> $AAPL no Bitcoin love here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:13:25 </td>
   <td style="text-align:left;"> $AAPL 👁❤️🍏👁❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:10:11 </td>
   <td style="text-align:left;"> $AAPL will these print tomorrow? Very risky but hoping for a 1.5% pop to make me 100k! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:08:57 </td>
   <td style="text-align:left;"> $AAPL puts will pay big here. Catch me in San Diego this weekend. 🚀 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:08:22 </td>
   <td style="text-align:left;"> $AAPL was it BS about the bitcoin 2022 apple announcement? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:07:35 </td>
   <td style="text-align:left;"> $MU who will decide to buyout Micron first? $MSFT, $AAPL or $BRK.A  ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:01:57 </td>
   <td style="text-align:left;"> Still have a chance to buy $AAPL for your LONG-TERM! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 05:00:55 </td>
   <td style="text-align:left;"> Senators and Congressional Trading: What to Know https://www.billionaireclubcollc.com/senators-and-congressional-trading-what-to-know/ $AAPL $AMZN $TSLA $PFE $MRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:59:49 </td>
   <td style="text-align:left;"> $AAPL can’t say I agree subscription based model :/ . As a consumer, I would probably try a different brand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:58:03 </td>
   <td style="text-align:left;"> $AAPL 🍏🚀🌔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:51:23 </td>
   <td style="text-align:left;"> $GBOX 

Got another buddy selling out his $AAPL and $GOOGL positions in the morning and going all in on the 📦 

#HODLer 

Shorty’s proverbial noose is going to get super tight, real soon… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:51:13 </td>
   <td style="text-align:left;"> $DJIA $BTC.X $AAPL 🇺🇸🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:44:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ - Apple is failing to break its resistance levels. The possible double-top or new ATH is growing weaker and weaker. We could see prices head back below $160. Without the Fed, there is nothing much markets can do at this point. Corporate Buy Backs only go so far and QE is &amp;quot;technically&amp;quot; over according to the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:43:32 </td>
   <td style="text-align:left;"> $AAPL apple announcement coming after hours right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:39:49 </td>
   <td style="text-align:left;"> $AAPL latex1010890277b12b3146a1cb4fc2112894AAPL  
$NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:28:25 </td>
   <td style="text-align:left;"> $AAPL whats going on after hours ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:27:53 </td>
   <td style="text-align:left;"> $AAPL $185 by months end. I got the calls to prove it. Tag this and remind me at the end of the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:24:51 </td>
   <td style="text-align:left;"> Want to see if the market will pick-up buyers tomorrow! $TSLA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:20:31 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $MULN $SPY  

Will history repeat itself? 👽 

🍏 Starting Monday 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:20:25 </td>
   <td style="text-align:left;"> $AAPL Should see more support tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:19:28 </td>
   <td style="text-align:left;"> $AAPL Day traders and retailers don’t know how ugly this will get!  
unwinding 11 trillion balance sheet ohh boy, 80% of investors didn’t go through that. = 30% haircut in QQQ SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:19:19 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Is Apple&amp;#39;s MLB streaming bet a good idea? https://www.stck.pro/news/AAPL/25794111 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:14:42 </td>
   <td style="text-align:left;"> $AAPL ticker BWV     
lets push it up !!!!!!!! to da moon !!!!! aaa+++++ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:14:00 </td>
   <td style="text-align:left;"> $AAPL is currently trading in the upper part of its 52 week range, outperforming the market. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:13:02 </td>
   <td style="text-align:left;"> $AAPL eat your apple or sell it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:12:27 </td>
   <td style="text-align:left;"> $AAPL $GOOGL https://seekingalpha.com/article/4500066-apple-google-stocks-end-epic-battle?mailingid=27288457&amp;amp;messageid=must_reads&amp;amp;serial=27288457.1719025&amp;amp;utm_campaign=Must%2BRead%2BApril%2B7%2C%2B2022&amp;amp;utm_content=seeking_alpha&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=must_reads </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:12:21 </td>
   <td style="text-align:left;"> Crypto Investors At Bitcoin Conference Tweets &amp;#39;Apple announcement in 40 minutes! #Bitcoin2022.&amp;#39;  
 
$AAPL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:11:21 </td>
   <td style="text-align:left;"> $AAPL latex5fa91abb0840495b35905ae31359af82TSLA 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:05:04 </td>
   <td style="text-align:left;"> $MSFT $AAPL $FB $TSLA red or black tomorrow? place your bet please :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:04:59 </td>
   <td style="text-align:left;"> $AAPL last min rush into aapl . May be expecting an announcement AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:04:28 </td>
   <td style="text-align:left;"> Love to hear when our members make money! Awesome $SPY $TSLA  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:04:19 </td>
   <td style="text-align:left;"> $TSLA locked 5K on a day trade.... I&amp;#39;ll hos a session tonight 8PM cali time for scalping option. Dm me if you are interested to learn...open free for public and followers...  $AAPL  $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:03:27 </td>
   <td style="text-align:left;"> $AAPL charts still look bullish. Tomorrow we skyrocket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:02:06 </td>
   <td style="text-align:left;"> $AAPL not a bad trade for 5 mins 🔥🔥🔥🔥🔥 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 04:00:02 </td>
   <td style="text-align:left;"> $SPY might want to check out $DTST for an incredible low float cyber security play.📈🪄 $TSLA $AAPL $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:59:48 </td>
   <td style="text-align:left;"> $AAPL can’t hold this shit up all the god damn time with otm options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:59:47 </td>
   <td style="text-align:left;"> $AAPL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:59:43 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $SPY Hold strong 1 min to close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:58:45 </td>
   <td style="text-align:left;"> $AAPL killed everyone&amp;#39;s options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:58:24 </td>
   <td style="text-align:left;"> $AAPL that was manipulated AF. Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:57:45 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $SPY Market prooved you, Bulls, that it can be restored in a jiffy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:57:22 </td>
   <td style="text-align:left;"> $AAPL Craapl sucks ass ... always has, always will. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:56:47 </td>
   <td style="text-align:left;"> $AAPL wow. That screwed me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:56:19 </td>
   <td style="text-align:left;"> $AAPL I am glad I sold my call for $600+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:55:38 </td>
   <td style="text-align:left;"> $AAPL f&amp;#39;ck it just squeezed some green out of a few calls man they don&amp;#39;t make it easy......geez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:55:00 </td>
   <td style="text-align:left;"> $SPY selling off as usual end of day $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:54:07 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Damn Bears +0.68% on $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:52:28 </td>
   <td style="text-align:left;"> $AAPL Nope. No sell-off. At least I don’t think so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:52:22 </td>
   <td style="text-align:left;"> Apple Analyst Warns Of ‘Considerable Risk’ For Tech Sector In Coming Months https://www.billionaireclubcollc.com/apple-analyst-warns-of-considerable-risk-for-tech-sector-in-coming-months/ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:51:33 </td>
   <td style="text-align:left;"> $AAPL sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:50:49 </td>
   <td style="text-align:left;"> $AAPL check is out 
🤙🤙🎯🚀

https://youtube.com/watch?v=IMgCvW2XFiM&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:50:40 </td>
   <td style="text-align:left;"> $AAPL market is going to crash tomorrow. Bye $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:50:31 </td>
   <td style="text-align:left;"> $AAPL I jumped in May 27 175 calls a little while ago (at 172.50) .. but, to be honest, I don&amp;#39;t know if that was a smart move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:50:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Bulls dont let yourself trippin or shaken. Hold Strong! 9 min to close! No Doubts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:49:36 </td>
   <td style="text-align:left;"> $AAPL $SPY i am really surprised by this market action. I mean I’ll take it because I’m a dip buyer but dang!  Haha! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:49:23 </td>
   <td style="text-align:left;"> $AAPL end of day selling off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:49:04 </td>
   <td style="text-align:left;"> $AAPL buying more calls here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:49:00 </td>
   <td style="text-align:left;"> $AAPL it can&amp;#39;t decide which way to go at 173 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:48:16 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $SPY 

If we get another dip buying opportunity in 2 min 🚀💎📈💎🚀

BUY IT! Will shoot up into close 💯📈💯

💰📈💰Do Not Miss That 💰📈💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:48:07 </td>
   <td style="text-align:left;"> $AAPL Easy $$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:48:06 </td>
   <td style="text-align:left;"> $AAPL I mean I knew things would run up but not this hot. This market is so full of shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:47:12 </td>
   <td style="text-align:left;"> $AAPL buy and hold, DCA long term winner, always… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:46:41 </td>
   <td style="text-align:left;"> $BWV this is a good long term investment. It’s the next $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:46:00 </td>
   <td style="text-align:left;"> $AAPL   🍏 So many Bears, so much Bearishness, when SO MUCH News IS COMING.  Massive BUYBACK Announcement, Significant Increase in Dividend Announcement, Hardware Subscription, something Insiders don’t want you to know yet.  Toot, toot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:45:35 </td>
   <td style="text-align:left;"> $AAPL nice Apple &amp;#39;Bottoms&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:45:34 </td>
   <td style="text-align:left;"> $AAPL eat shit apple bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:45:19 </td>
   <td style="text-align:left;"> $AAPL I smell end of day sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:44:50 </td>
   <td style="text-align:left;"> $AAPL I said don’t give up on Apple and stop the FUD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:43:56 </td>
   <td style="text-align:left;"> $VPLM OH YEAH!! 
 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:43:42 </td>
   <td style="text-align:left;"> $AAPL $SPY so manipulated. Everything will close flat tomorrow too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:43:35 </td>
   <td style="text-align:left;"> $AAPL end of day sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:42:42 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Positive Vibes Bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:42:31 </td>
   <td style="text-align:left;"> $AAPL sell here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:41:27 </td>
   <td style="text-align:left;"> $AAPL WS wants to pump lol  $$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:38:30 </td>
   <td style="text-align:left;"> $AAPL should take off once we break  173.10 resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:38:12 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : AAPL, TSLA, GOOGL, AMZN, FB: Why Are Nasdaq Stocks Down Today? https://www.stck.pro/news/AAPL/25792994 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:35:13 </td>
   <td style="text-align:left;"> $AAPL the &amp;#39;signs&amp;#39;...

Follow the Signs... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:34:52 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL Its a blessing that market restored keep buying Bulls! Hold strong! FInish strong! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:34:19 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL TP on $TSLA 1200, $SPY 480, $AMZN 3500, $GOOG 3000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:34:05 </td>
   <td style="text-align:left;"> $AAPL   🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:33:56 </td>
   <td style="text-align:left;"> $AAPL at 2.40  from 1.90 lol $NFLX $CLX $COST  $SST 🔥🚀✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:32:26 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL Bears that movement up! Oucheeeeeeeeeeeee! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:32:17 </td>
   <td style="text-align:left;"> $AAPL deflating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:29:38 </td>
   <td style="text-align:left;"> $AAPL it isn’t done selling. Will close under 172 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:29:17 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Bulls would relax and buy, its not fake pump or dead cat bounce! I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:29:17 </td>
   <td style="text-align:left;"> $SPY saves my day! $FSR $PLTR $AAPL $GMBL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:28:42 </td>
   <td style="text-align:left;"> $AAPL both carry spy $spy

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:27:13 </td>
   <td style="text-align:left;"> $AAPL underperforms most the day then algos go all in. This is grand. Hopefully active managers act rationally in the coming days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:27:09 </td>
   <td style="text-align:left;"> bot $AAPL @ 172.82 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:22:27 </td>
   <td style="text-align:left;"> $LCID Don’t be caught without shares Of LCID! $AAPL plans to announce partnership with a company to produce Apple Cars plus Foxconn planning to build EV parts warehouse in Saudi Arabia where LCID has a major presence! Hmm 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:22:16 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPX told ya…$Vix wont survive the climb… gave up today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:22:11 </td>
   <td style="text-align:left;"> $AAPL bust thru this resistance by close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:21:24 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask  
 
$NVDA - $2.7M call sweep 
$GLW - $980K put sweep 
$AAPL - $688K put sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:18:30 </td>
   <td style="text-align:left;"> $AAPL please don&amp;#39;t sell off all your gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:18:18 </td>
   <td style="text-align:left;"> $SPY The 3 greatest resurrections in history: Lazarus, Jesus, and the SPY. Amen. 
$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:18:05 </td>
   <td style="text-align:left;"> $AAPL i think this is the top 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:16:59 </td>
   <td style="text-align:left;"> $AAPL can we hold the gains? No selling right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:16:00 </td>
   <td style="text-align:left;"> $AAPL 173.15 here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:15:44 </td>
   <td style="text-align:left;"> $AAPL  STILL SITTING ON 1100 SHARES   105 SHARE PRICE AVERAGE  !!! YOU DO THE MATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:15:14 </td>
   <td style="text-align:left;"> $AAPL $FB EOD rally could lead to a bull run on Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:14:53 </td>
   <td style="text-align:left;"> $AAPL dropping below vwap before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:14:17 </td>
   <td style="text-align:left;"> $AAPL timing these algos is getting easier with this bear market. You will see things sell off again in the last 30 minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:12:53 </td>
   <td style="text-align:left;"> $AAPL LFG!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:11:43 </td>
   <td style="text-align:left;"> $AAPL F&amp;#39; ed me in the b today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:10:40 </td>
   <td style="text-align:left;"> $AAPL damn this is just pathetic. It’s absolutely going to sell off I. The last 30 minutes. This is all positioning for options by the MMs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:10:24 </td>
   <td style="text-align:left;"> $AAPL $175 close too much to ask? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:09:54 </td>
   <td style="text-align:left;"> $AAPL lol
You can tell this is forced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:09:49 </td>
   <td style="text-align:left;"> $AAPL need 177 to save my calls expiring tomorrow. HOLDing!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:09:06 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $TSLA $SPY 

🚀⚡🚀 P O W E R   H O U R 🚀⚡🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:09:01 </td>
   <td style="text-align:left;"> $AAPL time to dive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:07:56 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN $AAPL thanks for getting thid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:07:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN $FB
MAY THE ALGOS BE EVER IN YOUR FAVOR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:06:56 </td>
   <td style="text-align:left;"> latex172867333dbb2080e0b763092550dbebGOOG Long@ 2831.65 Target 2910.65 Stop Loss 2700.22 
Moved to 2700.22 from 2770.22 Stopped out 
$AMZN Long@ 3295.00 Target 3350.79 Stop Loss 3110.7 
Moved stop to 3110.77 from 3254.44 Stopped out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:05:08 </td>
   <td style="text-align:left;"> $QQQ $TSLA $TWTR $AAPL $AMRX  https://www.neurologylive.com/view/rise-pd-study-ipx-203-parkinson-disease-robert-hauser </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:02:29 </td>
   <td style="text-align:left;"> $AAPL anyone else snag 175s when they were cheeeap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:01:37 </td>
   <td style="text-align:left;"> $AAPL Green Acres </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 03:01:25 </td>
   <td style="text-align:left;"> $AAPL will hit 174 IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:59:47 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Bears? Puts still in market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:59:35 </td>
   <td style="text-align:left;"> $AAPL easy $$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:58:25 </td>
   <td style="text-align:left;"> $SPY 🍀 $UVXY $AAPL $QQQ 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:58:01 </td>
   <td style="text-align:left;"> $BITF i hear jack maller is presenting at the btc conference today. He sure has been wearing a lot of $AAPL swag in his twitter feed recently 🤔🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:57:39 </td>
   <td style="text-align:left;"> $SPY $AAPL yeah!!!🔥🔥🔥🔥🍏🍏🍏🍏🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:57:38 </td>
   <td style="text-align:left;"> $AAPL cashing out for the day!  Thanks for some great dips! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:57:14 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : My Dividend Growth Portfolio - Q1 2022 Summary https://www.stck.pro/news/AAPL/25792956 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:54:12 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:54:02 </td>
   <td style="text-align:left;"> $AAPL this can&amp;#39;t keep the momentum going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:53:38 </td>
   <td style="text-align:left;"> $AAPL Quick $700 profit 🔥🚀✅ 

Get into dip and take exit when you see GREEN $AMD $NVDA $SPY recovery mode ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:52:03 </td>
   <td style="text-align:left;"> $AAPL ok why’s it green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:51:27 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Bears, $SPY 448.00 Exactly as we expected! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:51:18 </td>
   <td style="text-align:left;"> $AAPL   🍏 Buy Signals on multiple time frames, triggered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:50:24 </td>
   <td style="text-align:left;"> Bonds inverse today, how is that bearish? $SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:50:03 </td>
   <td style="text-align:left;"> $SPY This daily chart looks like confirmation of a two class system.  
$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:49:26 </td>
   <td style="text-align:left;"> $AAPL idk 🤷‍♀️ lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:48:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 

Pamp it JPow!🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:48:01 </td>
   <td style="text-align:left;"> $AAVE.X Last call to get in $BTC.X $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:47:55 </td>
   <td style="text-align:left;"> $AAPL, $TSLA, $GOOGL, $AMZN, $FB: Why Are Nasdaq Stocks Down Today? https://investorplace.com/2022/04/aapl-tsla-googl-amzn-fb-why-are-nasdaq-stocks-down-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:46:35 </td>
   <td style="text-align:left;"> Our top 3 holding are: $TSLA $AAPL and our very first OTC stock, $KYNC. We believe their app pay.how will do very well in the coming quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:44:18 </td>
   <td style="text-align:left;"> $AAPL is this for real?  what a shitshow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:43:02 </td>
   <td style="text-align:left;"> $AAPL dump coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:42:03 </td>
   <td style="text-align:left;"> $TSLA Well there will be greenhouse emissions methane farting cows being served on the menu for a Vegan🌿🔋 branded company CYBER EVENT (GIGA AUSTIN) 🐂💨☣️😭😹🥩 - SECURITY  $SPY  $rivn $nio $aapl  
 
https://youtu.be/GpfBQahFuHs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:42:02 </td>
   <td style="text-align:left;"> $CAT $AAPL https://www.nasdaq.com/articles/the-zacks-analyst-blog-highlights-apple-caterpillar-the-travelers-companies-visa-and-dow?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:41:28 </td>
   <td style="text-align:left;"> What does the white line represent in this trading scenario?

Put your trading knowledge to the test! Comment below 👇🏼 $LCID $SBFM $SST $AAPL $FUBO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:39:57 </td>
   <td style="text-align:left;"> $AAPL $169 consolidated 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:39:55 </td>
   <td style="text-align:left;"> $SPY how many times they going to test 448 just drop that ahit. Literary not a single good news even $AAPL got a shiiit asss new yet it still goes back up lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:39:34 </td>
   <td style="text-align:left;"> $AAPL Wanna see Nasdaq spikes into close $$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:39:08 </td>
   <td style="text-align:left;"> $AAPL NVAX UPST AMD  calls. Nice bounce coming into close $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:38:45 </td>
   <td style="text-align:left;"> $C $spy $aapl $tsla what an absolute shtshow shameful joke. Biden making sure no1 makes any money. I&amp;#39;ll never invest again. Absolute joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:37:34 </td>
   <td style="text-align:left;"> $AAPL kinda disappointed with the recover from day’s low but my calls are for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:36:16 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-07 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=XBiegaPR1h4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:34:06 </td>
   <td style="text-align:left;"> $AAPL Just imagine this clising $173.5 or above. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:33:56 </td>
   <td style="text-align:left;"> Can the Fed Successfully do What Has Never Been Done Before 
 
Read: https://channelchek.com/news-channel/Can_the_Fed_Successfully_do_What_Has_Never_Been_Done_Before 
 
 
$SPY $QQQ $AAPL $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:33:42 </td>
   <td style="text-align:left;"> Market Makers making their money today $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:33:37 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $IWM

Dont you pray?
Don&amp;#39;t you pray?

to a cocaine Jesus
In a black four seater!

Is jpow the cocaine Jesus? 🤔 

https://youtu.be/rdVubZ6fZaU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:32:47 </td>
   <td style="text-align:left;"> $AMC $GME Now that $AAPL $MSFT $TSLA are in green they are going to reduce the pressure on us. MF hope there end comes to an end. This is way fucking to much. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:31:43 </td>
   <td style="text-align:left;"> $AAPL disappointment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:31:39 </td>
   <td style="text-align:left;"> $TWTR wow same candle and move with $AAPL, $SPY , and $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:30:57 </td>
   <td style="text-align:left;"> $AAPL Nice gap just above this area needs to get filled👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:30:11 </td>
   <td style="text-align:left;"> $AAPL $BTC.X $ETH.X Gap Trading &amp;amp; Crypto… plus a lot more..
Make sure you subscribe and click the alert button so you get all of our valuable pro tips and info

https://m.youtube.com/watch?v=6PRJVc36LXQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:29:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 

Wow, not gonna lie powell got me good today with the printers, congrats 
bulls.🖨👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:29:10 </td>
   <td style="text-align:left;"> $AAPL very low volume day. Will still fill the gap up to 175. Still very rich p/e ratio historically with higher rates. Should be at low 20s but around 28 as of now. Realistic valuation is 130-135 imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:27:55 </td>
   <td style="text-align:left;"> $AAPL Crazy WS, crazy easy money $$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:26:47 </td>
   <td style="text-align:left;"> $AAPL I’m in on Call, Apple may accept Bitcoin $BTC.X  !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:26:10 </td>
   <td style="text-align:left;"> $AAPL 

You have one more shot at canceling this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:24:19 </td>
   <td style="text-align:left;"> Google In 1996, Apple In 2010: What Does The 14-Year Investment Thesis Mean For Crypto In 2024? $GOOG $AAPL $BTC.X  $ETH.X $APE.X https://www.billionaireclubcollc.com/google-in-1996-apple-in-2010-what-does-the-14-year-investment-thesis-mean-for-crypto-in-2024/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:21:36 </td>
   <td style="text-align:left;"> $AAPL battle of 172.50 so far on the lower end.. hoping for 175 push today and bears to give up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:20:26 </td>
   <td style="text-align:left;"> $AAPL $HPE $SPY $UVXY $HPQ   I suspect Warren Buffet liquidated some Apple to purchase HP. His main goal is growth &amp;amp; apple is a very mature company. Buffet sold apple in 2020 &amp;amp; he will again before a downturn. He is an intelligent investor and he will most definitely adjust his portfolio to maximize growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:17:57 </td>
   <td style="text-align:left;"> $AAPL haven’t purchased new phone in over 5 years and I DONT plan on it… apple could drop down to 125 that’s where I’d buy. Here it’s not worth it. 28 PE when historically this trades at 15 PE …. Going down stats don’t lie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:16:52 </td>
   <td style="text-align:left;"> $AAPL is this in downtrend or uptrend just sitting on cash. Don&amp;#39;t know which way. Be nice to me. I&amp;#39;m not professional </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:14:40 </td>
   <td style="text-align:left;"> $SPY every American own stock,

I&amp;#39;m Chinese from China, we hold usa stock
We don&amp;#39;t buy china stock, we save many many money buy usa stock like $TSLA $WMT $COST $AAPL

WE love USA because USA everyone hold stonk, pension fund, politician, 401k, even president, everyone objective is stonk go up

If President dodo, stonk no go up, get voted out, next president is super power printer man

Worst recession is only 4 years in usa I feel,
Can always print and pass the problem to poor country like Asia and Europe

Will Asia and Europe unite against USA? No they hate each other, North Korea want Japan died
Just like Germany ww2

Stonk only go up, China people savings buy many usa stonk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:12:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:11:12 </td>
   <td style="text-align:left;"> $AAPL thanks for making it easier to keep loading those puts bulls 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:10:45 </td>
   <td style="text-align:left;"> $AAPL Holy crap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:09:46 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN Bulls half of my position got chopped these still in market! Sad truth. 
Adding more $AAPL Long Exp04/08 @ 175.62 /0.12 Target 179.34 Stop Loss 166.10 
Moved to 166.10 from 169.10 
Adding more $SPY Long Exp04/08 @ 453.51 /1.59 Target 459.34 Stop Loss 437.50 
Moved to 437.50 from 447.50 
Adding more $TSLA Long Exp04/08 @ 1099.36 /17.00 Target 1146 Stop Loss 1000.83 
Moved to 1000.83 from 1020.83 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:08:17 </td>
   <td style="text-align:left;"> $SPY $AAPL going to have a bad quarter but nope market keep buying appl lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:07:37 </td>
   <td style="text-align:left;"> $AAPL sold some 170.60/70 longs here, 171.60. 

Holding the rest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:06:44 </td>
   <td style="text-align:left;"> $AAPL down it goes. This and the nasdaq struggling to go green and stay green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:06:12 </td>
   <td style="text-align:left;"> $SPY $AAPL $JPM $BAC $WFC 
Japanese Yen: 5 yr low 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:05:53 </td>
   <td style="text-align:left;"> $AAPL time to kill puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:05:03 </td>
   <td style="text-align:left;"> $AAPL calls/puts killer, f this thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:03:09 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Damn Bears!!! Those puts that you bought at 443.56! Much be Oucheeeeeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:03:09 </td>
   <td style="text-align:left;"> $AAPL Quick climb back up on low volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:02:32 </td>
   <td style="text-align:left;"> $AAPL manipulation is a longs friend. 

#longcock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:02:26 </td>
   <td style="text-align:left;"> $SPY 

Retail rich folk invrstors don&amp;#39;t get it, what you are doing right now IS even worse, wait forvit, waaait for it, than just about any other thing to rise inflation---bringing the stock market up without proper correction.

Bears just laughing at you now, because these V rallies are fighting THE FED. 

Don&amp;#39;t do it, inflation just going to be that much worse every time you do these rallies, like mid March....

It&amp;#39;s accelerating inflation now, a lot, guys ☹
$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:00:48 </td>
   <td style="text-align:left;"> $AAPL Easy money $$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 02:00:30 </td>
   <td style="text-align:left;"> $AAPL how the fuck does this  stock just move like thtat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:59:47 </td>
   <td style="text-align:left;"> $AAPL massive bullish candle coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:59:39 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL Bulls! Power hour is near! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:59:05 </td>
   <td style="text-align:left;"> $AAPL Keep it up WS $$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:58:42 </td>
   <td style="text-align:left;"> $AAPL drop it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:58:33 </td>
   <td style="text-align:left;"> $AAPL Bulls on Parade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:56:36 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMC if you use Robinhood.. I am gathering people for a class action suit against robinhood. Today I noticed my price updates at a much slower rate than others. While some get updated price by the second, I have to wait 4 seconds. If you are in this boat too, let me know! I can&amp;#39;t win this one alone, we need about 10 people to start rolling the ball.

Check your Price update speed! If its 3-4 seconds its not right..

Help us fightthe fight for the good guys! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:56:26 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $SPY 

🚀 👽 🚀 THERE WE GOOO 🚀👽🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:54:21 </td>
   <td style="text-align:left;"> $AAPL 
Bet all the bears got IPhones 😂 wanting to see a company drop, for products that they own Lmaoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:54:08 </td>
   <td style="text-align:left;"> $AAPL 180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:53:29 </td>
   <td style="text-align:left;"> $AAPL this has been sideways since market opened today, what a POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:53:21 </td>
   <td style="text-align:left;"> $AAPL ugly ugly market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:53:16 </td>
   <td style="text-align:left;"> $AAPL every pop getting sold off geez glad I&amp;#39;m in cash now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:49:19 </td>
   <td style="text-align:left;"> $AAPL knife eod? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:47:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL Cmon Bulls lets break 448 on $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:46:58 </td>
   <td style="text-align:left;"> $AAPL @rexman getting upset .. and mildly unprofessional.  How do these types of accounts even get followers!  

Now watch him/her block me. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:45:07 </td>
   <td style="text-align:left;"> $SPY $AAPL   
 
  &amp;quot;#Station51,   #Engines 231,  117, and 186, proceed to Wallst ridge-line.  flare up  All Quadrants.  Kids buying dips on margin,  zero containment&amp;quot; 
 
&amp;quot;Engine 231 10-4&amp;quot; 
 
&amp;quot;Engine 117    1-4, proceeding to ridgline.  Send Air9&amp;quot; 
 
&amp;quot;10-4   KMG 365&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:43:35 </td>
   <td style="text-align:left;"> $AAPL Apple will promote Siri and Apple Music on its first live sports broadcast

https://www.cnbc.com/2022/04/07/apples-first-live-sports-broadcast-will-promote-siri-and-apple-music.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:42:52 </td>
   <td style="text-align:left;"> Your chance of fighting the Fed and winning; 0% 
It&amp;#39;s sad that one group of people control the stock market but that is the reality. Sell all these rips, let&amp;#39;s bleed out the excess from this market and take the QQQ to sub 300, SPY 400.  
 
$QQQ $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:38:05 </td>
   <td style="text-align:left;"> $SPY $VOO $AAPL $TWTR  we are limited but together we are unstoppable! Calling all Bulls to join us at $SST! Lets make some money and teach the SEC and Hedges that we will not stand for their corruption. We are a united nation and we stand together!!

Who will join me? 
 #UnitedBulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:37:10 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m apple shareholder, listen $AAPL

Tim Cook hold the spy ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:35:53 </td>
   <td style="text-align:left;"> $AAPL 

You know you can cancel the funzies they&amp;#39;re having. Will you? That&amp;#39;s your decision </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:35:49 </td>
   <td style="text-align:left;"> Buying $FSR for $13 in 2022 has to be similar to buying $TSLA for $20 back in 2011🤔
$AAPL $NKLA $SPCE 

FISKER 2022- it&amp;#39;s a start up
https://youtu.be/ezn6iY6LzIU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:35:18 </td>
   <td style="text-align:left;"> $MULN stock is so popular and the number of watchers rising incredibly fast.    Will soon sit pretty amongst $AMZN $AAPL TSLA $QS. 

People love a good success story.  

I remember being a watcher at 2000 not that long ago. 🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:33:51 </td>
   <td style="text-align:left;"> $GME $DOGE.X $BTC.X $TLSA $AAPL gathering people for a class action suit against robinhood. Today I noticed my price updates at a much slower rate than others. While some get updated price by the second, I have to wait 4 seconds. If you are in this boat too, let me know! I can&amp;#39;t win this one alone, we need about 10 people to start rolling the ball.

Up to 2 of 10, we aren&amp;#39;t alone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:28:45 </td>
   <td style="text-align:left;"> Google In 1996, Apple In 2010: What Does The 14-Year Investment Thesis Mean For Crypto In 2024? $BTC.X $GOOGL $AAPL $CSCO https://benzinga.com/z/26511633#.Yk8fNKgIUc4.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:27:20 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $TSLA 

Stand your ground bears, and don’t cover your warriors not care bears.😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:25:15 </td>
   <td style="text-align:left;"> $AAPL you fuckers with FICO scores below 550 really love buying overpriced shit. very comical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:24:59 </td>
   <td style="text-align:left;"> $AAPL I think earnings will be really good but the stock will go pretty red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:24:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

beautiful spot to add puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:24:39 </td>
   <td style="text-align:left;"> $TSLA $SPY $AMZN $AAPL I say we unite and hit the Bears now....i say they retards anyway.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:24:03 </td>
   <td style="text-align:left;"> $AAPL this should be down way more today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:21:36 </td>
   <td style="text-align:left;"> $AAPL lol! 👍🏼👍🏼

$SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:16:02 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT $AAPL $FB bears are a failure friend. They have nothing else to contribute to society except short stocks and indices so they can pet themselves on the back everyday for being right once in a while 🤣🤡🐻🖕🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:15:47 </td>
   <td style="text-align:left;"> $AAPL CHECK OUT THAT VIX!!!! It has an anchor attached to it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:15:25 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY $QQQ 

Bear market folks short the pops.😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:15:18 </td>
   <td style="text-align:left;"> $SPY what a move.

$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-08 01:14:56 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY $AMZN Bulls.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:26:50 </td>
   <td style="text-align:left;"> $TSLA a starter today and will add more tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:25:49 </td>
   <td style="text-align:left;"> $LLKKF CNBC FINALLY REPORTS ON THIS. Musk+Biden+the rest of the OEM EV Family.  Finally everyone is one happy family. Whatch out , Lithium consumption is about to get real: Those 500,000 chargers coming, is very very real. VS 150,000 Gas Stations throughout the U.S.$LIT $LCID $F $TSLA 
https://www.reuters.com/business/autos-transportation/biden-administration-holds-electric-vehicle-industry-meeting-with-musk-barra-2022-04-07/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:25:00 </td>
   <td style="text-align:left;"> $TSLA https://driveteslacanada.ca/news/tesla-recalls-127785-model-3s-in-china-due-to-rear-motor-defect/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:24:59 </td>
   <td style="text-align:left;"> $TSLA 10min.  First round-trip I&amp;#39;ve done in a while; very risky! . 
SELL - buy puts at 1064 
BUY - close out puts at 1036 
BUY - buy calls at 1036 around 1:20pm 
CLOSE - while there was no clear sell, it was close to Fibonacci levels, which could&amp;#39;ve served as resistance.  Closed at 1049.   
Training video: https://bit.ly/3dPNAXQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:23:08 </td>
   <td style="text-align:left;"> $TSLA he just launched tesla condoms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:23:05 </td>
   <td style="text-align:left;"> $TSLA $1150 tomorrow. Wahoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:20:45 </td>
   <td style="text-align:left;"> $SPY $TSLA $TWTR When you’re as famous and outspoken as Elon then you’ll inevitably receive criticism. I’ve pointed out his misdoings numerous times. That said, he has balls and brains. He’s going against the establishment while not only talking about his beliefs but also acting on them. He truly believes in what he says, rather than pandering to the masses like every other CEO in big tech. Destroy them Elon, change the status quo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:19:55 </td>
   <td style="text-align:left;"> $TSLA Gene Munster says outside of a few CT and Semi teaks, this will be a ribbon cutting ceremony. If so, could be sell the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:19:13 </td>
   <td style="text-align:left;"> $TSLA Could the Model Y actually be a 69 kWh battery with 420 miles of range? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:18:43 </td>
   <td style="text-align:left;"> $TSLA cyber rodeo 40 min </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:18:26 </td>
   <td style="text-align:left;"> $TSLA rocket 🚀 boosters on tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:18:16 </td>
   <td style="text-align:left;"> $TSLA my calls don’t expire tomorrow 🚀🚀🤠🤠🤠🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:18:09 </td>
   <td style="text-align:left;"> $TSLA 

https://youtu.be/KHy-16D0qJE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:17:54 </td>
   <td style="text-align:left;"> $TSLA I dont see any bears out. Tomorrow will definitely be red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:16:59 </td>
   <td style="text-align:left;"> $TSLA Can someone help me I seen on Twitter the other day it was a marketing video for the Germany factory and it was unbelievable and I can&amp;#39;t find it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:16:39 </td>
   <td style="text-align:left;"> $PLTR $TSLA $NVDA $GOOGL Only true AI stocks. Mkt caps - Palantir 25b, Tesla 1T, Nvidia 600b, Google 2T. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:15:34 </td>
   <td style="text-align:left;"> $TSLA When can i buy tickets for the cyber rodeo?
Ticketmaster doesn’t have them!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:12:56 </td>
   <td style="text-align:left;"> $TSLA Yo!  Elon is not for free speech unless Trump is back on Twitter.  Lets go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:11:58 </td>
   <td style="text-align:left;"> #WallStreetBets Top Stock Mentions Today #WSB  (NFA)                
$HMHC $GME $TSLA $AMD  
   
financials.fyi/sentiment/reddit/wallstreetbets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:11:53 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:11:44 </td>
   <td style="text-align:left;"> $TSLA whose ready for that $1099.99 close price tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:11:06 </td>
   <td style="text-align:left;"> $TSLA shanghai factory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:09:42 </td>
   <td style="text-align:left;"> $TSLA In the recent reporting quarter: 1 institutions initiated a position, while 1 completely liquidated https://www.insider-analysis.com/search_whales.php?ticker=TABLE_TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:09:19 </td>
   <td style="text-align:left;"> $TSLA tomorrow will be big. I’ll be Calling plays early. And opening positions for Monday right before market close. Be ready team 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:08:55 </td>
   <td style="text-align:left;"> $TSLA I really think it&amp;#39;s important Americans drive electric trucks and buses like they do in China they are real population experts and waste 200% less per capita than America because they have the cybertruck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:08:36 </td>
   <td style="text-align:left;"> $NIO FU#K TESLA. Buy NIO. NIO is a better car. $TSLA is 💩💩💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:08:11 </td>
   <td style="text-align:left;"> $TSLA Mr.Musk, we at the SEC need to discuss and investigate your recent twitter posts. We want to reiterate you must get approval for all tweets. 

Elon Musk &amp;quot;I will just buy Twitter then &amp;quot;  drops 🎤

I cant even explain how awesome this is. True boss status. Hate all you want but its hard not to respect someone that continually challenges the people who wish to tell him he cant live his life the way he wants. 

One life to live and the right to live it free. What my life is about now as well. 

🍻 all and good luck. Going up north to a cute artsy town called Taos and do some fishing. You know the pivots and know the option layout. Work to those. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:06:18 </td>
   <td style="text-align:left;"> $MULN LOL!  I can&amp;#39;t believe people still listen to that loser Hindenburg!  He is a corrupt criminal with a rap sheet.  If you sold these past 2 days you are going to seriously regret it. 
 
This stock is going to be a mini $TSLA.   1 Year price target is $40! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:05:36 </td>
   <td style="text-align:left;"> $TSLA $1170+ by EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:04:48 </td>
   <td style="text-align:left;"> $TSLA no bears rn but if is down pre market they will be flooding saying “told you so” haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:04:23 </td>
   <td style="text-align:left;"> $TSLA 1000 ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:04:05 </td>
   <td style="text-align:left;"> $TSLA I BET THEY KEEP IT FLAT TOMORROW TO KILL MY CALLS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:03:43 </td>
   <td style="text-align:left;"> $TSLA  cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:02:37 </td>
   <td style="text-align:left;"> $TSLA held some options overnight even though tsla fridays are usually weak. Hopefully Elon blows some minds at the new factory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:02:25 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:02:21 </td>
   <td style="text-align:left;"> $TSLA ITS STARTS AT 10pm EST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:02:10 </td>
   <td style="text-align:left;"> $TSLA  1 Hour! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:01:36 </td>
   <td style="text-align:left;"> $TSLA 

This is unacceptable. Hop in bisshhhes we need to go below 1k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:01:24 </td>
   <td style="text-align:left;"> $TSLA is anyone in this board there? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 09:00:03 </td>
   <td style="text-align:left;"> $TSLA Elon bring Trump back to Twitter!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:59:53 </td>
   <td style="text-align:left;"> $TSLA SO NOTHING NEW YET?!?!?!  TF MAN!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:59:43 </td>
   <td style="text-align:left;"> $TSLA Don&amp;#39;t  care where it goes as long as it pays
me. 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:59:32 </td>
   <td style="text-align:left;"> $TSLA when Shanghai? 20k new COVID-19 cases today and spreading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:58:57 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:57:39 </td>
   <td style="text-align:left;"> $TSLA bears…you about to get pissed on :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:57:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $BTC.X $PLTR Forget spy and qqq, all you need is Tesla, BTC and Palantir. https://youtu.be/bgEnUPAhGbA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:57:12 </td>
   <td style="text-align:left;"> $TSLA CT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:57:11 </td>
   <td style="text-align:left;"> $TSLA chart watchers... where you at? Barcoding and consolidation? Fuckin dog fight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:56:57 </td>
   <td style="text-align:left;"> $TSLA I’m going to start using a bit to trade. Fuck this shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:56:56 </td>
   <td style="text-align:left;"> thought on tomorrow’s session?  $SPY $SPX $TSLA $QQQ 💰🦅 (POLL) https://www.webullapp.com/s/post/409667056920993792?hl=en </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:56:00 </td>
   <td style="text-align:left;"> $TSLA imagine, just for a moment, Elon announces cyber truck and roadster delivery windows, the new model Y, maybe some other cars, and a 10:1 stock split. Can you even IMAGINE THE BULLISHNESS OF TOMORROW?! I feel like this may become a possibility. Hold onto your calls y’all, it’s about to get spicy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:54:49 </td>
   <td style="text-align:left;"> $TSLA bot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:53:34 </td>
   <td style="text-align:left;"> $TSLA 

The Communist  Party of China 🇨🇳 is the true Evil of the world - America is distracted by a passive player PUTIN PUTIN PUTIN PUTIN while the true enemy of freedom and innovation is growing exponentially before your eyes !! 

I’ll continue to post my opinions n facts all relevant- currently America IMO is on the wrong path n completely misguided by a plan already set yrs ago and now is being implemented DUE TO lack leadership !! Sadly! 

🙏🏻🐉🦅

https://twitter.com/af_academy/status/1512172917576007710?s=21&amp;amp;t=-G_Z7U-dgn-8lQp3YD5DeQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:52:56 </td>
   <td style="text-align:left;"> $SPY $TWTR $TSLA sooo MSNBC says musky is a racist ,, LMFAO JOY HOT MESS REID gotta go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:52:40 </td>
   <td style="text-align:left;"> $TSLA finally trending. Now lets get to #1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:52:04 </td>
   <td style="text-align:left;"> $TSLA i heard rumors of 10-1 split.. anyone heard or have intel? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:52:02 </td>
   <td style="text-align:left;"> $SPY floor has been found

Researcher spent month of digging finding floor of spy

We finally hit the floor, it&amp;#39;s time for party $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:51:32 </td>
   <td style="text-align:left;"> $TSLA  Master Plan 3

Tonigh !

Let’s go.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:51:26 </td>
   <td style="text-align:left;"> $TSLA sell the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:51:20 </td>
   <td style="text-align:left;"> $TSLA crazy lefty’s are calling Musk a racist wow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:51:09 </td>
   <td style="text-align:left;"> $TSLA bulls like rodeos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:50:37 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $TSLA with Unusual Options Activity Alerted on $1040 PUT Expiring: 04-14-2022 worth 740K🐻 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:50:37 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE 🔥 
#LOTTO FRIDAY PICKLIST 
IM GOING TO BREAKDOWN 👇 
📈TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS  
CLICK&amp;gt; https://us02web.zoom.us/j/89457164243 
 $SPY  #trading  #Invest  #stocks $AAPL  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:50:04 </td>
   <td style="text-align:left;"> $TSLA if my calls print... I&amp;#39;ll buy my ole lady an Audi I guess 🤷🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:49:52 </td>
   <td style="text-align:left;"> $TSLA Tesla never disappointed. This will print huge next week✅🚀🔥 $ROKU $F $QQQ $SNDL 🤑💴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:48:22 </td>
   <td style="text-align:left;"> Investor $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:47:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla to mark opening of new Texas Gigafactory with &amp;#39;Cyber Rodeo&amp;#39; https://www.stck.pro/news/TSLA/25798600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:47:02 </td>
   <td style="text-align:left;"> $TSLA the fact he called it the cyber rodeo so bullish it’s insane new ATH coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:46:53 </td>
   <td style="text-align:left;"> $TSLA watch china reopen factory tomorrow too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:46:51 </td>
   <td style="text-align:left;"> $TSLA smart people bought shares to swing your average joe bought calls, it’s all priced in baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:46:39 </td>
   <td style="text-align:left;"> $TSLA HOPEFULLY WE GET A NEW ATH COMING NEXT COUPLE WEEKS 📝 🔥🔥💰🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:43:35 </td>
   <td style="text-align:left;"> $TSLA hope Elon has a surprise for us tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:40:29 </td>
   <td style="text-align:left;"> $TSLA buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:39:16 </td>
   <td style="text-align:left;"> $TSLA 

Show me $2k already! I got bills to pay baby🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:38:58 </td>
   <td style="text-align:left;"> SOLD MY $TSLA SHARES AND BOUGHT $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:38:54 </td>
   <td style="text-align:left;"> $TSLA puts r the </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:38:41 </td>
   <td style="text-align:left;"> $TSLA recently signed on as a vendor for Tesla and started doing residential solar construction. Things are warming up nicely future is bright and just getting traction here in FL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:36:27 </td>
   <td style="text-align:left;"> $TSLA bulls turn tomorrow looking to close 1100s+ ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:35:43 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:35:29 </td>
   <td style="text-align:left;"> $TSLA How much would you pay for the option of free supercharging for the lifetime of owning your new Tesla? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:34:51 </td>
   <td style="text-align:left;"> $TSLA 

Breaking News: Elon Musk to announce plan for electric tank, will donate first 50 to countries opposing Russian forces. source/KVWNChannel4/SanDiego </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:34:26 </td>
   <td style="text-align:left;"> $TSLA 
Elon has timed this to make sure people are sleepless tonight for morning to come. Trapped - shorts &amp;amp; longs alike. Only tonight,  after everyone has gone to sleep, magic starts happening . Who gains, who loses, morning will tell 🤷🏻‍♂️
😂😂😂😂😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:34:05 </td>
   <td style="text-align:left;"> $TSLA this is so gonna SELLOFF 📉⬇️⬇️⬇️tomorrow! Wall Street has all of your LOTTO CALLS trapped! They knew the fan bois would be in their ELON JOCK STRAP FEELINGS 🥴🙃🤡..  
 
NO WORRIES,  I stopped by to drop off a consolation prize while your real money goes to to bears! 🙋‍♂️💦💸 $nio $aapl $SPY $rivn etc 
 
Ladies and gentlemen  - The CyberDUMP 🍑💦😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:33:12 </td>
   <td style="text-align:left;"> $TSLA I didn’t know bears hibernate in Spring, where’d y’all go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:32:49 </td>
   <td style="text-align:left;"> $TSLA this will be at $1200 by end of the month. Mark my words. Wahoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:32:46 </td>
   <td style="text-align:left;"> $TSLA Live event starting soon in 1.5 hrs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:32:42 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/zerohedge/status/1512226692152102917?s=21&amp;amp;t=EeKi8yRoy5m2cOng30vAog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:32:10 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-07 Chart Analysis Video: 
https://www.youtube.com/watch?v=9B5TIwo659A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:29:58 </td>
   <td style="text-align:left;"> $TSLA Do Tesla bears only post during the day cause I see no bears up in here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:29:38 </td>
   <td style="text-align:left;"> $TSLA futs are on fire 🔥.  Gaaaaaaaappppppppppp DOWN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:29:23 </td>
   <td style="text-align:left;"> $TSLA T Minus 92 minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:26:49 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $1200.00 Call for Friday, April 29, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:26:27 </td>
   <td style="text-align:left;"> $F Decent Daily Chart!! As per daily TF, the stock has strong trend line support, if it breaks down the strong support zone highlighted on the chart. Nice time to buy at the bottom.  sweepcast.com/ #stockstowatch Trending stocks $SST, $TSLA, $PFE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:25:23 </td>
   <td style="text-align:left;"> $TSLA 4680 battery to Model 3 Performance. Amen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:25:00 </td>
   <td style="text-align:left;"> $TSLA next gen battery ? New superchargers , cybertruck, hypertunnel get ready boys daddy musket balls is taking us on a trip to mars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:24:35 </td>
   <td style="text-align:left;"> $TSLA anyone got a link? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:23:33 </td>
   <td style="text-align:left;"> $TSLA Video of Cybertruck on twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:22:23 </td>
   <td style="text-align:left;"> $TSLA remember when Tesla use to run $100 a day get ready boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:22:05 </td>
   <td style="text-align:left;"> $TSLA Can’T Elon just split the stock already? Who’s going to vote no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:21:35 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:20:45 </td>
   <td style="text-align:left;"> $TSLA OK ALL HOPIUM ASIDE.... I HOPE IT GOES UP BUT ITS FRIDAY.. I SEE A SIMILAR DAY AS TODAY AGAIN.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:20:39 </td>
   <td style="text-align:left;"> $TSLA tomorrow will be epic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:20:26 </td>
   <td style="text-align:left;"> $TSLA 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:18:35 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s  closing price 

https://youtu.be/Nqlqfax2ABw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:18:35 </td>
   <td style="text-align:left;"> $CYN  cyngn acquired by $TSLA 👀😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:18:03 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:17:54 </td>
   <td style="text-align:left;"> $TSLA 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:17:24 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMD hosting a session on zoom tonight about how to daytrade weekly option... Dm me if you wanna join...free for public. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:17:18 </td>
   <td style="text-align:left;"> $TSLA get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:17:15 </td>
   <td style="text-align:left;"> $SPY $MULN $AMC $NILE $TSLA   $1800 into $40k in the last 30 days.... If you really want to make huge profits on trading then, Join this winning chat ‘...    tinyurl.com/most-winning-chat-room </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:16:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:16:17 </td>
   <td style="text-align:left;"> $TSLA holy shit dood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:16:04 </td>
   <td style="text-align:left;"> $TSLA cyber truck leak at Austin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:16:03 </td>
   <td style="text-align:left;"> $TSLA We don’t mess around here in Texas.. Big is the way we see things. And we love money too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:15:46 </td>
   <td style="text-align:left;"> New Video!  
 
Elasticity, Yield Curve Inversion and The Fed! 
 
https://www.youtube.com/watch?v=DmruxZfRMpQ 
 
$SPY $QQQ $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:15:36 </td>
   <td style="text-align:left;"> $TSLA To anyone disillusioned and getting ready for the big swindle, Tesla has opted out of American car manufacturing and uses its HQ only as a stateside tax haven for the ceo&amp;#39;s own personal wealth. No, for those of you asking, Tesla has not submitted anything to the NHTSA regarding their semi or cybertruck which is infact currently in production over in China for all of Tesla&amp;#39;s real customers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:15:32 </td>
   <td style="text-align:left;"> $TSLA Tesla will save thé markets tomorrow, like always </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:15:24 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $900.00 Call for Thursday, April 14, 2022. Roughly 2 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:13:39 </td>
   <td style="text-align:left;"> $TSLA Post here what you think will be the biggest piece of news announced tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:13:36 </td>
   <td style="text-align:left;"> $TSLA 

Fyi
Hi to the 
Marker Makers
Monitoring this feed

Hahaha😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:12:53 </td>
   <td style="text-align:left;"> $TSLA link for CYBER RODEO 10 PM EASTERN TIME👇👇👇👇 https://youtu.be/fiwUE_2JhvY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:12:28 </td>
   <td style="text-align:left;"> $TSLA anyone have the link for tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:12:01 </td>
   <td style="text-align:left;"> $TSLA 

Open at 1200$ pre market gunna be 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:12:00 </td>
   <td style="text-align:left;"> $TSLA  my $150 calls expiring tomorow will they be dark green or useless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:11:48 </td>
   <td style="text-align:left;"> $TSLA In the recent reporting quarter: 18 institutions increased their position, while 10 decreased https://www.insider-analysis.com/search_whales.php?ticker=TABLE_TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:10:45 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;ll be reading till 9pm CT bought me rich Dad poor dad a week ago and only half way through, i enjoy it very much it&amp;#39;s not as boring as the intelligent investor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:10:08 </td>
   <td style="text-align:left;"> $TSLA We pump tomorrow https://livestream.tesla.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:09:19 </td>
   <td style="text-align:left;"> $TSLA Elon gonna fluff up these calls and jizz all over those sour bear puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:09:05 </td>
   <td style="text-align:left;"> $TSLA 

 https://livestream.tesla.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:08:44 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA 🚨🚨👀

Cyber Texas pump. Elon speaks at 9.

⏳💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:08:38 </td>
   <td style="text-align:left;"> $TSLA Hybrd Airplane??? What!!! That’d be something huh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:07:51 </td>
   <td style="text-align:left;"> $TSLA Don‘t mess with Texas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:07:48 </td>
   <td style="text-align:left;"> $TSLA Time to pump this bad boy with Cyber Rodeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:07:25 </td>
   <td style="text-align:left;"> $TSLA 

https://livestream.tesla.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:06:49 </td>
   <td style="text-align:left;"> $TSLA party at the Texas Gigafactory!!! Opened for business!!  Yeah!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:05:55 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s 2 am in Germany and when Elon speaks it&amp;#39;s 4am and I&amp;#39;ll be up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:05:39 </td>
   <td style="text-align:left;"> According to the @TipRanks database, 2 of the TOP Wall Street analysts in the #tech sector r from @Oppenheimer. 
 
They have a success rate of 50%-74%.  Interesting none of the top sell short. 
 
$AAPL $NVDA $AMD $TWTR $TSLA  
 
Check out the Rankings 
👇 
https://t.co/5GFimMMVAr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:05:26 </td>
   <td style="text-align:left;"> $SPY one thing for sure
Stonk only go up

Throw your chart out, because you&amp;#39;re poor

GO TESLA, STONK 
 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:05:11 </td>
   <td style="text-align:left;"> Most Traded Contracts

$AAPL 08 April $175 Call
$AAPL 08 April $172.50 Call
$AAPL 08 April $170 Put
$TSLA 08 April $1100 Call
$KGC September $5 Put
$OPEN January 2023 $12.50 Call
$OPEN January 2023 $15 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:04:09 </td>
   <td style="text-align:left;"> $TSLA do we hit ATH tomorrow before the close?

Personally think tomorrow will be a big day for TSLA, as long as we don’t see the market overall hit the dumpster or any other outside factors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:03:49 </td>
   <td style="text-align:left;"> $SPY  I guess no one told spy there was still Neckline Resistance 🤷‍♂️ $UVXY $QQQ $TSLA latex2f428504bcc240e247f4e3f3b8793805TSLA 1.411m (59% call/41% put)
$AAPL 1.065m (59% call/41% put)

https://bit.ly/sweepcastoptions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:03:24 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $150.00 Put for Friday, December 16, 2022. Roughly 171 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:02:52 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/T8nIJisRIws </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:02:44 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-07 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=_tYTjrl1Kj4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:02:16 </td>
   <td style="text-align:left;"> $TSLA 

Elon to speak at 9 ET or CT? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:02:15 </td>
   <td style="text-align:left;"> $TSLA nice buys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:01:59 </td>
   <td style="text-align:left;"> $TSLA gigaaaa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:01:37 </td>
   <td style="text-align:left;"> $TSLA any bear here at this point is a desperate troll that gets no love at home </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:01:08 </td>
   <td style="text-align:left;"> $TSLA GGGGGg Gddy up ! giga dividends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:01:05 </td>
   <td style="text-align:left;"> $TSLA oh oh it lost the 10 AH gain now only 8  
Bulls u said 1100 tonight ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 08:00:54 </td>
   <td style="text-align:left;"> $TSLA tomorrow the bears are going to be so quiet... everything is bigger in TEXAS!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:59:37 </td>
   <td style="text-align:left;"> $TSLA ATH COMING SOON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:57:19 </td>
   <td style="text-align:left;"> You BEARS obviously have no CLUE how corporate politics work. A board seat matters as well as being the LARGEST shareholder. He also has the largest clout on $TWTR (more than Trump) and with flicks of his fingers can change the world if he wanted... so the board and management have to listen to Elon whenever he decides to flex... also... when you sign up for a new account you have to follow someone... did you know that Elon is at the very top of the list for everyone... so if Twitter employees are mad... then why have they pumped him for years? Jack loves Elon and they both see crypto as the future... so if Jack needs Elon for crypto... then bringing back Trump is an acceptable inconvenience that Jack will tolerate... oh and lastly Elon hates bears... despises them... he will read his Twitter feed after his $TSLA event and crush the shorts... watch... #timestamp this b***h! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:57:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:56:05 </td>
   <td style="text-align:left;"> $TSLA ONLY 15% FROM ATH!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:55:53 </td>
   <td style="text-align:left;"> $TSLA i will burry you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:55:38 </td>
   <td style="text-align:left;"> $MNTS deal with starlink $TSLA musk could make mnts go big imo $SPY $QQQ $SST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:55:32 </td>
   <td style="text-align:left;"> $TSLA Joe Biden Takes Major Step to Embrace Elon Musk… https://www.thestreet.com/technology/joe-biden-takes-major-step-to-embrace-elon-musk?puc=yahoo&amp;amp;cm_ven=YAHOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:55:24 </td>
   <td style="text-align:left;"> $TSLA  THE BIGGEST Party on the Planet Tonight with the Best CEO of all Time and BEARS think he is going to disappoint..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:52:54 </td>
   <td style="text-align:left;"> $TSLA love all this millennial elon sheep with gifs from their Playstation games lmao  
They about to learn what real world is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:52:13 </td>
   <td style="text-align:left;"> $TSLA let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:51:07 </td>
   <td style="text-align:left;"> $TSLA block all bearish post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:50:58 </td>
   <td style="text-align:left;"> $TSLA byaaaaaa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:50:36 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:50:30 </td>
   <td style="text-align:left;"> $TSLA all this giga factory hype and only 10 box up ?  
 
U promised 1100 tonight, Bulls push harder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:50:21 </td>
   <td style="text-align:left;"> $TLRY Dear Jesus...I mean Elon. Please save us poor Tilray folk. I promise to stop masturbating to promiscuous pokemon cards if you squeeze us to the moon tomorrow. Well, I might not stop entirely, but I&amp;#39;ll reduce the amount of times I do it. Just blast Tilray off to outer space tomorrow. 🙏 Amen. $TSLA $GME $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:50:18 </td>
   <td style="text-align:left;"> $TSLA she not only held above 1060+ but 1065+ 🔥🔥🔥 all i see is 1100+ am session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:49:25 </td>
   <td style="text-align:left;"> $TSLA global recession, we should expect new 52 week lows for all the majors. 
 
https://www.youtube.com/watch?v=WVTVsnvSLeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:48:42 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s getting worse 
 
https://www.youtube.com/watch?v=2mpacWk0nrU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:48:27 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price  Prediction and Analysis for  Tomorrow Friday   April 8.
https://youtu.be/WukiN3YdjJY better day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:48:01 </td>
   <td style="text-align:left;"> $TSLA https://www.cnbc.com/2022/04/07/thiel-calls-buffett-sociopathic-grandpa-from-omaha-about-bitcoin.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:47:33 </td>
   <td style="text-align:left;"> $TSLA THIS ISNT THE MOVE I WAS EXPECTING!!!  I WANT $1080 TONIGHT!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:47:00 </td>
   <td style="text-align:left;"> $TSLA is one of the better performing stocks in the Automobiles industry. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:45:51 </td>
   <td style="text-align:left;"> $TSLA TENDIES 🍗🍗🍗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:43:15 </td>
   <td style="text-align:left;"> $TSLA omg !!! Tomorrow is gonna be 🔥 😈💦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:41:58 </td>
   <td style="text-align:left;"> $TLRY I&amp;#39;m long, never selling. But there will be a tiny spike tomorrow when 65M shares get covered before noon tomorrow. Then the bull trap rug pull will occur. This time the shorts will use even sharper dildos on us. Without the help from united $GME $TSLA $AMC apes...I&amp;#39;m afraid our butts will be bleeding out by close tomorrow. Never selling. Maybe I am just numb to the pain. I&amp;#39;m hunting down all these shorts one day. Can&amp;#39;t hide in that dark pool anonymity forever. They have to come out at some point...and I&amp;#39;ll have the largest, dirtiest, flaming dildos they&amp;#39;ve ever seen ready for them. Our time will come. 🙏Amen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:41:53 </td>
   <td style="text-align:left;"> $TSLA NEW TESLA MODEL GIGA AUSTIN💎💎💎🚀🚀🚀🚀🚀🚀🚀🚀1080 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:40:46 </td>
   <td style="text-align:left;"> Elon vs other company CEO’s
He has a twitter poll asking the ppl should he sell shares. He actually lets you know what’s about to happen so your able to get out or stay in. Fucking hats off 
$TSLA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:40:03 </td>
   <td style="text-align:left;"> $TSLA up $10 AH!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:39:02 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:38:57 </td>
   <td style="text-align:left;"> $TSLA 15,000 CAPACITY AND THERES LIKE 100 PEOPLE!  WHERE’S EVERYONE?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:38:19 </td>
   <td style="text-align:left;"> $VGX.X 10 dollar candle.  Vgx 2.0.  The ultimate pullout after over a year of vgx Wang pounding.  Show us the green, Pam!  Saveur people!!

$BTC.X $ETH.X $DOGE.X $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:37:54 </td>
   <td style="text-align:left;"> $TSLA CMON, NO NEWS?!?!?!  GIVE US SOMETHING ALREADY!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:37:15 </td>
   <td style="text-align:left;"> $TSLA shusssssssss! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:37:02 </td>
   <td style="text-align:left;"> $TSLA if we can get past $1,076 premarket it’s over🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:36:40 </td>
   <td style="text-align:left;"> $TSLA Tesla to $2000 confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:35:39 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:35:27 </td>
   <td style="text-align:left;"> $TSLA close at $1070 tonight please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:35:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $DJIA  
Market Movers Economic Events Next Week      
 
https://www.financegreater.com/economiccalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:35:06 </td>
   <td style="text-align:left;"> $TSLA holy s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:34:43 </td>
   <td style="text-align:left;"> $TSLA 
Tesla pumping hard AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:34:24 </td>
   <td style="text-align:left;"> $TSLA you dump while we pump🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:34:04 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/BLKMDL3/status/1512166998435938316?t=ESobfHsiLBqWVl2vx9XQgQ&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:33:51 </td>
   <td style="text-align:left;"> $TSLA https://www.cnn.com/2022/02/17/business/elon-musk-neuralink-animal-cruelty-intl-scli/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:33:43 </td>
   <td style="text-align:left;"> $TSLA the hype is real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:33:30 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $PLTR Only 3 you need in your portfolio. https://www.fedscoop.com/palantir-ceo-says-lives-have-been-saved-and-taken-with-its-software/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:33:02 </td>
   <td style="text-align:left;"> $TSLA shhhhh! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:32:58 </td>
   <td style="text-align:left;"> $TSLA will this hit 1100 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:31:24 </td>
   <td style="text-align:left;"> $TSLA I’m a musky hunter but let’s hunt some bears tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:31:24 </td>
   <td style="text-align:left;"> $TSLA for the 🐀’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:31:03 </td>
   <td style="text-align:left;"> $TSLA giddy up giga split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:31:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:30:05 </td>
   <td style="text-align:left;"> $TSLA musk soon. Global elites don&amp;#39;t like his twitter takeover and won&amp;#39;t let his rule breaking slide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:30:01 </td>
   <td style="text-align:left;"> $TSLA all small buys AH - no volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:29:49 </td>
   <td style="text-align:left;"> $TSLA ROADSTER GAME CHANGER!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:29:35 </td>
   <td style="text-align:left;"> $TSLA 1120 by the time you wake up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:29:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL $TWTR This is a MUST WATCH for these tickers especially!
Make sure you SUBSCRIBE and click the ALERTS on our channel so you don’t miss our videos!
Happy STACKS tomorrow 😎

https://youtu.be/B3nn1ZRLM98 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:29:16 </td>
   <td style="text-align:left;"> $TSLA 🚨🚨🚨😋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:28:49 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Taneja Vaibhav sold $1,484,528 worth of shares (1,300 units at $1,141.94) as part of a pre-agreed trading plan, decreasing direct ownership by 5% to 24,685 units to cover taxes

https://quantisnow.com/i/2696138?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:28:28 </td>
   <td style="text-align:left;"> $TSLA 😿 ducking told u so beutefol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:28:03 </td>
   <td style="text-align:left;"> $TSLA Bears are fucked tomorrow, its already up %1 AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:27:33 </td>
   <td style="text-align:left;"> $ATER make sure everyone coming to ATER for the first time tonight/tomorrow see this.  
 
https://www.reddit.com/r/ATERstock/comments/tby5s2/the_updated_aterian_squeeze_2022/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf 
 
$AMC $GME $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:27:29 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:27:11 </td>
   <td style="text-align:left;"> $TWTR  
Bears at Tweeter make me LOL. $TSLA alone beat all other Car Manufacture EV or NOT. What TSLA have that other Car Manufacture dont have. It simple it Elon Musk and hes Tweets. He have a lot Cheap Publicity For TSLA cars. I have read some where it cost 17 cents per car ads and other Car Manufacture cost in the Thousand. Many times I have thinking about Shorting $TSLA few years ago and i could make some very good profit But if did that since 2-3 years i could lose 400-600 % very fast. 
 
$TWTR have fill the gap. For me I use the high of the gap of it first day of the rally. It 46.5 and after reaching that price it bounce back now it 48 and it will continue and beat 54.5 it recent high. Bears think TWTR can reach 40 again and how about 9.1 % TWTR Stake that Elon Musk have and he will not sell until TWTR reach 300-500 % of profit in 1-2 years. He have invest i think TSLA for 100 milions hes owner ship worth now 286B. 
 
https://elite.finviz.com/quote.ashx?t=TWTR&amp;amp;ty=c&amp;amp;ta=1&amp;amp;p=h&amp;amp;tas=0 
 
https://elite.finviz.com/quote.ashx?t=TSLA&amp;amp;ty=c&amp;amp;ta=1&amp;amp;p=w&amp;amp;tas=0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:27:05 </td>
   <td style="text-align:left;"> $TSLA whoever lowered average on long calls winning ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:27:00 </td>
   <td style="text-align:left;"> Tesla Motors&amp;#39;s Chief Accounting Officer just picked up 1,300 shares  https://www.conferencecalltranscripts.com/summary/?id=10686702 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:26:51 </td>
   <td style="text-align:left;"> $SBFM loading some $AEI for solar musk $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:26:40 </td>
   <td style="text-align:left;"> $TSLA  My favorite quote is &amp;quot;IT IS NOT HOW YOU START, IT&amp;#39;S HOW YOU FINISH&amp;quot; 
 
WE STARTED THE WEEK WITH A BANG........ 
 
WE ARE ENDING THE WEEK WITH A BANG!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:26:37 </td>
   <td style="text-align:left;"> $TSLA NOTHING STANDS OUT.  CMON!!  GIVES US MORE!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:26:06 </td>
   <td style="text-align:left;"> $IMPP $CEI $PRPO $VYGR $TSLA

Gang, today I went VERY long a new investment… $IMPP

An oil shipping:tanker company that JUST raised $60m and bought two new tankers. Oil tanker shipping rates are “soaring” right now as Russia’s massive fleet is being shunned 

This is a $5+ target SHORT term. Good luck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:25:23 </td>
   <td style="text-align:left;"> $TSLA 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:25:18 </td>
   <td style="text-align:left;"> $TSLA Be ready boys, they did an april fool prank Cyber truck going for sale!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:25:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:23:58 </td>
   <td style="text-align:left;"> $TSLA 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:23:19 </td>
   <td style="text-align:left;"> $TSLA feel the power </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:23:05 </td>
   <td style="text-align:left;"> $TSLA what does everyone think about 1100 calls for tomorrow, bought a few before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:22:43 </td>
   <td style="text-align:left;"> $TSLA Target tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:21:59 </td>
   <td style="text-align:left;"> $TSLA They showed the cyber truck!!!!!! We out to $1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:21:38 </td>
   <td style="text-align:left;"> $NIO How does $NIO compares with $TSLA ?  Is it next Tesla ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:21:09 </td>
   <td style="text-align:left;"> $TSLA    Hi. Is there any news that may make the stock rise tomorrow. Please someone answer with pictures proof or something  thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:20:10 </td>
   <td style="text-align:left;"> $TSLA $1,120 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:19:18 </td>
   <td style="text-align:left;"> $TSLA futures looking realllll good and Bitcoin for that matter. Tommorow will tell us how this will go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:17:55 </td>
   <td style="text-align:left;"> Tesla CAO Vaibhav Taneja Sells $1,484,522.00 in $TSLA https://www.marketbeat.com/i/504614 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:16:16 </td>
   <td style="text-align:left;"> $QQQ $TSLA  might wanna test that falling wedge at 1140-1150 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:15:11 </td>
   <td style="text-align:left;"> Uranium Stocks &amp;amp; ETFs Attempting to Breakout and the US Stocks Watchlist – 7 April 2022 
 
There were 51 stocks for the US stocks watchlist today. 
$TSLA, $CENX, $CCJ, $BTU + 47 more... 
 
#stocks #trading #investing #money  
https://www.stageanalysis.net/blog/170151/us-stocks-watchlist-7-april-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:14:03 </td>
   <td style="text-align:left;"> $TSLA 5-10% day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:13:43 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:11:50 </td>
   <td style="text-align:left;"> $TSLA 10-1 split most likely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:11:40 </td>
   <td style="text-align:left;"> $TSLA if Tesla hits 1200 tommorow I’m all in for a cybertruck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:11:29 </td>
   <td style="text-align:left;"> $KSCP Positioned for another round. We see 3 as that is definitely coming.  It has a broken chart and we all know that is where the majority of people purchased except for the unlucky ones above $25 just 1 month ago.  Also high short % and low float and history of so so business also puts pressure on stock to touch 3.  We are Bear and disclosure we own short shares.  

Also short $GME - $NVDA - $TSLA  and a hand full of high flyers on ST trend scan.  

CYA tomorrow.   GL traders it’s just business.  Nothing against companies.  Market made it this way.  We are honest up front. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:11:18 </td>
   <td style="text-align:left;"> $TSLA $SPY WHY DO I GET THE FEELING THAT THIS WILL BE A SELL THE NEWS TYPE OF THING. #GIGAAUSTIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:11:00 </td>
   <td style="text-align:left;"> $TSLA Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC https://newsfilter.io/a/e59f49c13163a66e21ac443ff423a2ba </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:09:49 </td>
   <td style="text-align:left;"> $TSLA $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:09:34 </td>
   <td style="text-align:left;"> $TSLA tmr $1,100! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:09:21 </td>
   <td style="text-align:left;"> $TSLA scam bots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:08:18 </td>
   <td style="text-align:left;"> $SPY $TSLA Gap at $1021 is now filled... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:08:06 </td>
   <td style="text-align:left;"> $ATER Climbing up, could overtake $TSLA and $SOFI before close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:07:12 </td>
   <td style="text-align:left;"> $TSLA $SPY $BOXL $AAPL $AYRO Top trendin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:06:31 </td>
   <td style="text-align:left;"> Insider Vaibhav Taneja reports selling 1,300 shares of $TSLA for a total cost of $1,484,528.20 https://fintel.io/n/us/tsla/taneja-vaibhav?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:06:27 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Chief Accounting Officer Taneja Vaibhav: 
Disposed 1,300 of Common Stock at average price $1,141.94 https://s.flashalert.me/P9HZfK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:06:23 </td>
   <td style="text-align:left;"> $TSLA GETTING STRONGER DAY BY day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:06:02 </td>
   <td style="text-align:left;"> $TSLA he still bullish don’t let ppl fool you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:05:19 </td>
   <td style="text-align:left;"> $TSLA to that moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:04:24 </td>
   <td style="text-align:left;"> $TSLA Xtrader best community so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:04:23 </td>
   <td style="text-align:left;"> $TSLA 1069 CLOSE 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:03:26 </td>
   <td style="text-align:left;"> $TSLA I hope they unveil a cyber car tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:03:14 </td>
   <td style="text-align:left;"> $TSLA insider fucking sold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:02:06 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:01:40 </td>
   <td style="text-align:left;"> Insider Vaibhav Taneja reports selling 5,700 shares of $TSLA for a total cost of $6,316,944.11 https://fintel.io/n/us/tsla/taneja-vaibhav?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:01:34 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Taneja Vaibhav exercised 7,000 shares at a strike of $54.66 and sold $6,316,944 worth of shares (5,700 units at $1,108.24) as part of a pre-agreed trading plan, increasing direct ownership by 5% to 25,985 units (for withholding tax)

https://quantisnow.com/i/2696124?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:01:26 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Chief Accounting Officer Taneja Vaibhav: 
Disposed 5,700 of Common Stock at average price $1,108.24 https://s.flashalert.me/cWsTn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:01:14 </td>
   <td style="text-align:left;"> $TSLA hoping for some good news about cyber truck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:01:00 </td>
   <td style="text-align:left;"> $COST, $TSLA and $ILMN are the top gainers in the Nasdaq 100 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_20&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_Nasdaq_100_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 07:00:48 </td>
   <td style="text-align:left;"> $TSLA Form 4 (statement of changes in beneficial ownership of securities) filed with the SEC 

https://newsfilter.io/a/c1aea0f8553669e477a6a998ff51cb7f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:59:45 </td>
   <td style="text-align:left;"> $TSLA who else is practicing their degenerate gambling tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:58:53 </td>
   <td style="text-align:left;"> $MNTS I wish you all good luck. So much opportunity in a market this volatile.  Just remember, I held $ALPP at 20 cents average share [10k shares]. It blew up to 9 dollars per share and I STILL didn&amp;#39;t sell. I listened to everyone else who had a different agenda and ended up selling at like 3 dollars each when I really needed the cash. Safest thing to do is secure at least some profit, no matter what the ticker is. Even if I owned $TSLA at 100 dollars a share, I wouldn&amp;#39;t best myself up for taking profit then </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:58:21 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #3 ticker with sweep activity where institutions are trading options urgently with 35.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:55:15 </td>
   <td style="text-align:left;"> $TSLA … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:55:15 </td>
   <td style="text-align:left;"> $TSLA when cyber rodeo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:54:44 </td>
   <td style="text-align:left;"> $TSLA go Tesla goooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:54:24 </td>
   <td style="text-align:left;"> $TSLA they be buying it… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:53:57 </td>
   <td style="text-align:left;"> $TSLA $1110 next line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:53:52 </td>
   <td style="text-align:left;"> $TSLA IS THE NEWS PRICED IN?  I BOUGHT $1070 LOTTO CALLS FOR TOMORROW…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:52:55 </td>
   <td style="text-align:left;"> $TSLA imagine a 20% move tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:52:49 </td>
   <td style="text-align:left;"> $TSLA Have u seen the new Electric Benz’s on the Masters commercials the fickle rich will soon be flocking to them used Tesla’s will become the go to UBER work horse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:50:25 </td>
   <td style="text-align:left;"> $TSLA DJ Tesla Gears Up to Open Austin Gigafactory With &amp;#39;Cyber Rodeo&amp;#39; -- Update https://www.webullapp.com/news-detail/50055955?theme=1&amp;amp;hl=en&amp;amp;color=2&amp;amp;_v=1&amp;amp;tickerId=913255598&amp;amp;disSymbol=TSLA&amp;amp;sp=0&amp;amp;hl=en </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:49:28 </td>
   <td style="text-align:left;"> $TSLA anyone know what the vehicle is on bottom left of pic? Is this a prototype of Model 2? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:48:16 </td>
   <td style="text-align:left;"> $TSLA Elon speaking after the market close to ensure SEC wont not send a notice.. am sure there are some surprises.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:47:42 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Works With Toyota To Develop Cameras: 
https://www.youtube.com/watch?v=ImA5sw6qKhY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:45:02 </td>
   <td style="text-align:left;"> $DIDI where is $NIO or $TSLA , it would be a great partnership??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:43:49 </td>
   <td style="text-align:left;"> $TSLA any photos from the party? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:41:25 </td>
   <td style="text-align:left;"> $TSLA goga factory opened and it&amp;#39;s not 1100 yet ? How come ? Bulls said 1200 eow lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:40:35 </td>
   <td style="text-align:left;"> $TSLA we don&amp;#39;t ask much, a modest 100-120 bucks really would be ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:40:18 </td>
   <td style="text-align:left;"> $TSLA maybe we revisit $1,140? 😅🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:39:35 </td>
   <td style="text-align:left;"> $TSLA the amount of bullshit fake news coming out of this event will be outstanding lol. Lets please only focus on the real confirmed news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:38:51 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/7/2022 $SPY $QQQ $NVDA $TSLA $CCJ https://www.chartguys.com/daily-market-videos/4210/daily-bounce-scout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:37:53 </td>
   <td style="text-align:left;"> $TSLA spy gap up 451+ which brings Tesla to 1070+ in the morning just off spy gapping up plus giga factory news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:37:44 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/7qz7amXImes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:37:28 </td>
   <td style="text-align:left;"> $TSLA Closed the gap from 3/25 almost to the penny.  Preparing for the push up to the trend line ~ 1152. IMO. Bought a 1060p-1090c strangle on high today and bought a 1005c for $30 after the fall. Added 3x 1120c at close.  Prolly should have added another put in case of sell the news event. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:37:14 </td>
   <td style="text-align:left;"> $TSLA love how these paid pumpers spread misinformation to pump the stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:36:54 </td>
   <td style="text-align:left;"> $TSLA 💎💎💎📈📈📈📈📈GIGA!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:36:01 </td>
   <td style="text-align:left;"> $TSLA https://www.reddit.com/r/teslamotors/comments/tyo9n2/tesla_4680_battery_cell_structural_pack/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:35:41 </td>
   <td style="text-align:left;"> $TSLA bull 🐂🐂🐂🐂 in action tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:35:08 </td>
   <td style="text-align:left;"> $TSLA so many 1000 puts got toasted today !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:35:07 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboy denied entry into Gigashit Austin.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:34:27 </td>
   <td style="text-align:left;"> $TSLA Tesla’s semi truck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:33:46 </td>
   <td style="text-align:left;"> $TSLA when Giga Rodeo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:33:20 </td>
   <td style="text-align:left;"> $MNTS $AEI $TSLA 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-08 06:31:59 </td>
   <td style="text-align:left;"> $TSLA THERE WILL BE AT LEAST 6 NEW MODELS! </td>
  </tr>
</tbody>
</table></div>

---
