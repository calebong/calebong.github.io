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



Last Updated: 2022-04-07 09:24:01 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/industrial-production </td>
   <td style="text-align:left;"> 2022-04-07 09:21:21 </td>
   <td style="text-align:left;"> Philippines Manufacturing Output Growth at 5-Month High </td>
   <td style="text-align:left;"> Manufacturing production in the Philippines jumped 92.4% yoy in February 2022, after a  marginally revised 21.8% gain a month earlier, pointing to the strongest rise since last September, amid easing pandemic disruptions and a low base effect from last year. Output growth accelerated for coke and refined petroleum products (874.9% vs 67.1% in January), food products (26.8% vs 16.6%), computer, electronics (22.7% vs 20.1%), chemicals (57.5% vs 21.5%), furniture (93.4% vs 10.9%), other non-metallic mineral products (23.7% vs 8.4%), fabricated metal products (18.3% vs 7.1%), and transport equipment (4% vs 1.6%). In addition, production continued to grow for basic metals (27.6% vs 30.4%), machinery and equipment (41.5% vs 42.4%), manufacturing and repair (18.1% vs 18.3%), textiles (19.3% vs 34.7%), and basic pharmaceuticals (5.6% vs 41,9%). By contrast, output fell for electrical equipment (-26.2% vs -23.8%), apparel (-3.5% vs -30.2%), and wood, bamboo, cane (-2.1% vs 69.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 09:10:56 </td>
   <td style="text-align:left;"> Australia Shares Decline on Tech Rout </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index fell 0.6% to around 7,445 on Thursday, retreating further from a 3-month high hit earlier this week and tracking a technology-led rout on Wall Street overnight driven by expectations of a faster pace of monetary tightening by the Federal Reserve. Investors also continued to assess the direction of domestic monetary policy, after the Reserve Bank of Australia dropped its pledge of staying patient and signaled it could begin raising interest rates within months if wages and inflation data produce strong results. Losses among technology names were led by Wisetech Global (-4%), Xero Ltd (-2.7%), Seek Ltd (-3.3%), Block Inc (-4.1%) and Pointsbet Holdings (-4.7%). Financial and clean energy-related stocks also declined, including Macquarie Group (-1.7%), ANZ Bank (-1%), Pilbara Minerals (-2%), Allkem Ltd (-1.5%) and Core Lithium (-2.5%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/fiji/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-07 08:58:00 </td>
   <td style="text-align:left;"> Fiji Inflation Rate at Over 3-Year High of 4.7% </td>
   <td style="text-align:left;"> Annual inflation rate in Fiji jumped to 4.7 percent in March 2022 from 1.9 percent in the previous month, pointing to the highest level since February 2019, due to a faster rise in prices of food and non-alcoholic beverages (8.0% vs 3.3%), transport (8.4% vs 8.2%), household equipment &amp; routine maintenance (4.0% vs 2.8%), and clothing &amp; footwear (1.5% vs 0.7%), while those of alcoholic beverages &amp; tobacco rebounded (1.7% vs -3.3%). Meantime, prices continued to rise for housing &amp; utilities (4.9% vs 5.4%), miscellaneous goods &amp; services (1.9% vs 2.6%), health (3.8% vs 4.0%). By contrast, prices of restaurants &amp; hotels dropped further (-3.1% vs -2.9%). On a monthly basis, consumer prices were flat in March, after a 1.3 percent increase in February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/stocks-set-for-pullback-xi-s-resolve-tested-evergrande-update?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 08:38:19 </td>
   <td style="text-align:left;"> Stocks Set for Pullback; Xi’s Resolve Tested: Evergrande Update </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                 , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                          , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                               , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                  , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                           , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                              , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                          , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                           , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                 , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                            , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                 , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                       , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                           , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                              , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                         , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                             , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                    , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                  , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                              , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                               , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                 , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                  , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                       , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                    , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                          , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                  , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                 , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                           , David Scanlan                                                                                                                                                                                                                             , Chinese property stocks may be poised for a pullback after surging 28% in three weeks as pandemic lockdowns put a brake on economic growth. China Vanke Co. meanwhile announced a share buyback.                                          , The slowdown may test President Xi Jinping’s resolve to not inject more stimulus into the housing market even as Beijing takes additional steps to shore up the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/buffett-s-berkshire-hathaway-builds-new-4-2-billion-hp-stake?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 08:29:31 </td>
   <td style="text-align:left;"> Buffett’s Berkshire Hathaway Builds New $4.2 Billion HP Stake </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                 , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                          , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                               , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                  , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                           , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                              , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                          , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                           , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                 , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                            , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                 , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                       , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                           , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                              , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                         , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                             , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                    , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                  , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                              , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                               , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                 , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                  , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                       , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                    , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                          , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                  , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                 , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                           , Katherine Chiglinsky                                                                                                                                                                                                                      , Warren Buffett’s Berkshire Hathaway Inc. bought a stake in HP Inc. valued at more than $4.2 billion. Shares of the laptop maker surged as much as 10%.                                                                                    , Berkshire bought some of the stock earlier this week in multiple transactions and now holds an investment of about 121 million shares in the computer company, according to a regulatory filing Wednesday.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 08:26:30 </td>
   <td style="text-align:left;"> US Futures Slip Further After 2-Day Selloff </td>
   <td style="text-align:left;"> US stock futures slipped further in Asian trade on Thursday after Wall Street sold off for two consecutive days, as investors evaluated the pace of the Federal Reserve’s monetary policy tightening. Dow and S&amp;P 500 futures each fell about 0.2%, while Nasdaq 100 futures lost 0.3%. In regular trading on Wednesday, the Dow shed 0.4%, the S&amp;P 500 slid 1% and the tech-heavy Nasdaq Composite dropped another 2.2%. Growth-oriented names in the consumer cyclical, technology and communication services sectors led the declines, with sharp losses from Tesla (-4.2%), Nvidia (-5.9%) and Meta Platforms (-3.7%). The losses came as Fed meeting minutes showed that officials planned to reduce the central bank’s massive balance sheet with a consensus amount of around $95 billion a month, and indicated that one or more 50 basis point interest rate hikes could be warranted to battle surging inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/06/business/media/eric-boehlert-death.html </td>
   <td style="text-align:left;"> 2022-04-07 08:16:05 </td>
   <td style="text-align:left;"> Eric Boehlert, Media Critic and Writer, Dies at 57 - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                        , “He was fearless and brilliant in his investigation of hypocrisies and double standards in the media, and his contribution was priceless,” his family said in a statement.                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                             , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                      , By Katie Robertson                                                                                                                                                                                                                                                                  , Eric Boehlert, a veteran journalist who was a fierce critic of right-wing misinformation and hypocrisy in the news media, died on Monday in New Jersey. He was 57.                                                                                                                  , Mr. Boehlert was struck by a New Jersey Transit train while riding his bicycle near the Watchung Avenue station in Montclair. His death was confirmed by his wife, Tracy Breslin.                                                                                                   , A frequent commentator on television and radio, as well as a prolific writer, Mr. Boehlert never shied away from searing critiques of what he saw as bias in the mainstream press and the circular impact of media on politics.                                                     , After more than a decade as a senior fellow at Media Matters for America, a left-leaning media monitoring group, Mr. Boehlert had in recent years started his own newsletter, Press Run, as a vehicle for his commentary.                                                           , “I’m devastated for his family and friends and will miss his critical work to counteract misinformation and media bias,” Hillary Clinton, a former U.S. secretary of state, wrote on Twitter on Wednesday.                                                                          , Born in Utica, N.Y., Mr. Boehlert spent some of his childhood in Indiana before his family moved to Guilford, Conn. He earned a bachelor’s degree in Middle Eastern studies at the University of Massachusetts Amherst.                                                             , Early in his career, Mr. Boehlert covered the music industry at Billboard and Rolling Stone, before becoming a staff writer at Salon. In 2006, he joined Media Matters.                                                                                                             , “His passing is a real loss for truth and will leave a void in the broader media landscape,” the group wrote in a statement posted on Twitter on Wednesday.                                                                                                                         , Mr. Boehlert was the author of two nonfiction books: “Lapdogs: How the Press Rolled Over for Bush,” published in 2006, and “Bloggers on the Bus: How the Internet Changed Politics and the Press,” published in 2009.                                                               , After a stint as a media writer for the website Daily Kos, Mr. Boehlert started Press Run in 2020, which he described as “an unfiltered, passionate and proudly progressive critique of the political press in the age of Trump.”                                                   , Ms. Breslin said Mr. Boehlert was an avid athlete and cyclist.                                                                                                                                                                                                                      , “Eric was brilliant and funny and kind,” she said. “He was an amazing father to Jane and Ben, present their entire lives.” Their daughter, Jane Boehlert, remembered him as “a magnificent father, an incredible person.”                                                           , “We already miss him deeply,” she said.                                                                                                                                                                                                                                             , In Mr. Boehlert’s last article on Press Run, published the day he died, he questioned journalists’ coverage of the Biden administration, saying the news media was playing down the president’s achievements.                                                                       , “The glaring disconnect between reality and how the press depicts White House accomplishments means a key question lingers: Why is the press rooting against Biden?”                                                                                                                , A statement from Mr. Boehlert’s family, provided to The New York Times by Richard Abate, Mr. Boehlert’s literary agent, described him as “a fierce defender of democracy, social justice and truth in media.”                                                                       , “He was fearless and brilliant in his investigation of hypocrisies and double standards in the media, and his contribution was priceless,” the family said. “Eric was filled with vibrant enthusiasms and interests in life as a loving husband, father, sibling, uncle and friend.”, Mr. Abate said they had been friends for 45 years, after meeting in the eighth grade. “He was the most kindest, gentlest, warmest, lovingest person I’ve known, and at the same time he was an absolute fierce warrior when it came to fighting injustice,” he said.                , Jon Stewart, the comedian and talk show host, said in a tweet: “Rest In Peace Eric Boehlert. Greatly admired his passion and tenacity.”                                                                                                                                             , Mr. Boehlert is survived by his wife and their two children. Other survivors include three siblings.                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/sri-lanka-faces-wall-of-debt-payments-amid-economic-meltdown?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 08:00:01 </td>
   <td style="text-align:left;"> Sri Lanka Faces Wall of Debt Payments Amid Economic Meltdown </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                   , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                 , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                                                    , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                                                             , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                                                                  , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                                                     , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                                                              , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                                                                 , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                                                             , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                                                              , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                                                    , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                                                               , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                                                    , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                                                          , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                                                              , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                                                                 , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                                                            , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                                                                , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                                                       , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                                                     , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                                                                 , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                                                                  , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                                                    , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                                                     , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                                                          , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                                                       , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                                                             , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                                                     , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                                                    , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                                                              , Medical students protest against Sri Lanka's crippling economic crisis, outside the Health Ministry in Colombo on April 6.                                                                                                                                                   , Photographer: Ishara S. Kodikara/AFP/Getty Images                                                                                                                                                                                                                            , Lilian Karunungan                                                                                                                                                                                                                                                            , Sri Lanka faces $8.6 billion worth of debt payments due this year as the implosion of its economy and worsening political turmoil cast doubt on its ability to pay any of it.                                                                                                , Among them, the South Asian country needs to honor a combined $2.2 billion of principal and interest payments for dollar-denominated bonds and loans, with the number rising to about $2.7 billion annually in both 2023 and 2024, available data compiled by Bloomberg show. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-07/surging-treasury-yields-leave-thai-bonds-most-at-risk-in-asia?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 08:00:00 </td>
   <td style="text-align:left;"> Surging Treasury Yields Leave Thai Bonds Most at Risk in Asia </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                              , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                                                            , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                                                                                                               , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                                                                                                                        , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                                                                                                                             , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                                                                                                                , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                                                                                                                         , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                                                                                                                            , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                                                                                                                        , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                                                                                                                         , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                                                                                                               , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                                                                                                                          , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                                                                                                               , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                                                                                                                     , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                                                                                                                         , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                                                                                                                            , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                                                                                                                       , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                                                                                                                           , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                                                                                                                  , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                                                                                                                , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                                                                                                                            , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                                                                                                                             , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                                                                                                               , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                                                                                                                , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                                                                                                                     , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                                                                                                                  , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                                                                                                                        , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                                                                                                                , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                                                                                                               , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                                                                                                                         , Marcus Wong                                                                                                                                                                                                                                                                                                                             , Thai bonds look vulnerable to further losses as the volatility in U.S. Treasuries is far from over.                                                                                                                                                                                                                                     , The securities are the most susceptible among Asian emerging markets to a further surge in Treasury yields, according to a Bloomberg analysis of seven countries. Total returns on baht-denominated sovereign bonds are down 6.1% since Russia invaded Ukraine on Feb. 24, the biggest laggard, according to data compiled by Bloomberg. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-06/weak-yen-s-mixed-blessing-turns-more-toxic-for-japan?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 07:50:00 </td>
   <td style="text-align:left;"> Weak Yen’s Mixed Blessing Turns More Toxic for Japan </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                                                            , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                                                                                          , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                                                                                                                                             , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                                                                                                                                                      , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                                                                                                                                                           , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                                                                                                                                              , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                                                                                                                                                       , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                                                                                                                                                          , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                                                                                                                                                      , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                                                                                                                                                       , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                                                                                                                                             , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                                                                                                                                                        , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                                                                                                                                             , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                                                                                                                                                   , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                                                                                                                                                       , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                                                                                                                                                          , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                                                                                                                                                     , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                                                                                                                                                         , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                                                                                                                                                , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                                                                                                                                              , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                                                                                                                                                          , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                                                                                                                                                           , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                                                                                                                                             , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                                                                                                                                              , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                                                                                                                                                   , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                                                                                                                                                , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                                                                                                                                                      , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                                                                                                                                              , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                                                                                                                                             , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                                                                                                                                                       , Yuko Takeo,                                                                                                                                                                                                                                                                                                                                                           , Yoshiaki Nohara, and                                                                                                                                                                                                                                                                                                                                                  , Komaki Ito                                                                                                                                                                                                                                                                                                                                                            , A weaker yen has long been considered a boon for Japan’s economy, helping blue-chip exporters such as Toyota Motor Corp. But that narrative is increasingly in question as the yen’s recent plunge aggravates the impact of surging commodity prices, hitting some businesses and consumers much harder than before.                                                  , “The negative effects, or the risks from the weaker yen we’re now seeing, are unprecedented,” said Eiji Hashimoto, chairman of the Japan Iron and Steel Federation. While steelmakers and other manufacturers benefited from past phases of yen weakness, the current spike in energy and materials costs mean “this time it’s totally different,” he said last week.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-06/oil-rebounds-after-tumble-on-back-of-iea-reserve-release-plan?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 07:39:08 </td>
   <td style="text-align:left;"> Oil Advances After Slumping on Back of IEA Reserve Release Plan </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                        , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                      , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                                                                         , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                                                                                  , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                                                                                       , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                                                                          , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                                                                                   , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                                                                                      , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                                                                                  , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                                                                                   , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                                                                         , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                                                                                    , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                                                                         , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                                                                               , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                                                                                   , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                                                                                      , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                                                                                 , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                                                                                     , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                                                                            , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                                                                          , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                                                                                      , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                                                                                       , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                                                                         , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                                                                          , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                                                                               , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                                                                            , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                                                                                  , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                                                                          , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                                                                         , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                                                                                   , Jake Lloyd-Smith                                                                                                                                                                                                                                                                                  , Oil rebounded after a steep slump that was triggered by prospects for further crude releases from strategic reserves, the outlook for tighter U.S. monetary policy and weaker demand in virus-hit China.                                                                                          , West Texas Intermediate rose past $97 a barrel after retreating by more than $5 on Wednesday after the International Energy Agency said that U.S. allies will deploy 60 million barrels from stockpiles. That’s on top of the 180 million-barrel release already announced by President Joe Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-06/hong-kong-has-fallen-off-map-as-aviation-hub-airline-group-says?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 07:27:15 </td>
   <td style="text-align:left;"> Hong Kong Has Fallen Off Map as Aviation Hub, Airline Group Says </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world.                                                                                        , Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                                                                                                                      , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                                                                                                         , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                                                                                                                  , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                                                                                                                       , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                                                                                                          , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                                                                                                                   , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                                                                                                                      , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                                                                                                                  , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                                                                                                                   , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                                                                                                         , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                                                                                                                    , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                                                                                                         , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                                                                                                               , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                                                                                                                   , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                                                                                                                      , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                                                                                                                 , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                                                                                                                     , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                                                                                                            , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                                                                                                          , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                                                                                                                      , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                                                                                                                       , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                                                                                                         , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                                                                                                          , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                                                                                                               , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                                                                                                            , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                                                                                                                  , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                                                                                                          , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                                                                                                         , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                                                                                                                   , Empty Hong Kong International Airport on April 1.                                                                                                                                                                                                                                                                                 , Angus Whitley                                                                                                                                                                                                                                                                                                                     , Hong Kong has ceased to function as an international aviation hub as it curbs inbound flights and quarantines arriving passengers, according to a trade group representing hundreds of airlines worldwide.                                                                                                                        , Even the city’s shortened isolation requirements for arriving passengers -- quarantine was halved to one week this month -- will deter travelers, Willie Walsh, director general of the International Air Transport Association, said Wednesday. Hong Kong has effectively fallen off the map as a global transit center, he said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-06/u-k-urged-to-overhaul-tax-system-that-favors-highest-earning-1?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-04-07 07:01:00 </td>
   <td style="text-align:left;"> U.K. Urged to Overhaul Tax System That Favors Highest-Earning 1% </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                 , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                          , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                               , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                  , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                           , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                              , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                          , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                           , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                 , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                            , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                 , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                       , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                           , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                              , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                         , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                             , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                    , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                  , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                              , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                               , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                 , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                  , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                       , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                    , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                          , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                  , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                 , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                           , Andrew Atkinson                                                                                                                                                                                                                           , The U.K. tax system continues to favor the 500,000 highest-earning people in the country and should be overhauled, according to the Institute for Fiscal Studies.                                                                         , The top 1% enjoy “preferential” rates over wage earners because they get more of their income from more lightly taxed sources, the influential think tank said in a report published Thursday.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/services-pmi </td>
   <td style="text-align:left;"> 2022-04-07 06:33:16 </td>
   <td style="text-align:left;"> Australia Services Sector Growth Slows in March </td>
   <td style="text-align:left;"> The Australian Industry Group Australian Performance of Services Index fell to 56.2 in March of 2022 from a nine-month high of 60 in the prior month. The latest reading pointed to slower growth in the services sector, although solid overall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-04-06/stocks-set-to-decline-on-fed-fallout-crude-lower-markets-wrap </td>
   <td style="text-align:left;"> 2022-04-07 06:31:31 </td>
   <td style="text-align:left;"> Stocks, U.S. Futures Hit by Fed Fallout; Bonds Up: Markets Wrap </td>
   <td style="text-align:left;"> , Live market coverage co-anchored from Hong Kong and New York. Overnight on Wall Street is daytime in Asia. Markets never sleep, and neither does Bloomberg. Track your investments 24 hours a day, around the clock from around the world., Follow Bloomberg reporters as they uncover some of the biggest financial crimes of the modern era. This documentary-style series follows investigative journalists as they uncover the truth                                              , Russia Skirts Nearer Default After Dollar Payment Blocked                                                                                                                                                                                 , Fed Officials Weigh Pruning Balance Sheet by $95 Billion a Month                                                                                                                                                                          , Samsung Earnings Top Estimates on Chip Demand, New Handsets                                                                                                                                                                               , Didi in Talks With Haima Automobile About EV Partnership                                                                                                                                                                                  , Uber to Add Plane, Train and Hotel Bookings in ‘Super App’ Push                                                                                                                                                                           , Ex-Trump Aides Scavino, Navarro Held in Contempt of Congress                                                                                                                                                                              , U.S. Satellites Spying on Russia’s War Tap Commercial Technology                                                                                                                                                                          , Grantham Warns Oil Spikes This Severe Always Trigger Recessions                                                                                                                                                                           , Canada to Ban Foreigners From Buying Homes as Prices Soar                                                                                                                                                                                 , More Than 20% of Best-Paid U.K. Bankers Had Special Tax Status                                                                                                                                                                            , Photomontage Pioneer Jerry Uelsmann Dies in Florida At 87                                                                                                                                                                                 , Consumer Stocks Start to Believe the Fed Is Serious                                                                                                                                                                                       , Insurers Must Brace for Catastrophic Cyber Risk                                                                                                                                                                                           , Does the Fed Have to Destroy the Market in Order to Save It?                                                                                                                                                                              , China’s $2.3 Trillion Infrastructure Plan Puts America’s to Shame                                                                                                                                                                         , The Smart Way to Shift to a Four-Day Workweek                                                                                                                                                                                             , The Bridgewater CEO Who Went Full MAGA                                                                                                                                                                                                    , McDonald’s Investors to Vote This Spring on Civil-Rights Audit, SEC Says                                                                                                                                                                  , It's More Expensive to Rent a Home if You're Black or Latino                                                                                                                                                                              , Biden Warns Amazon ‘Here We Come’ After New York Union Vote                                                                                                                                                                               , Koch-Backed Conservative Group Pushes Laws to Block Pensions Focus on ESG                                                                                                                                                                 , Trudeau Approves Equinor’s $12 Billion Offshore Oil Plan                                                                                                                                                                                  , An Artist Tackles the Racial Wealth Gap, and Then Tries to Close It                                                                                                                                                                       , GOP Governors Attacked Biden Aid. Now It May Help Them on Election Day                                                                                                                                                                    , An Italian Hamlet Just Won the EU Lottery. Now for the Hard Part                                                                                                                                                                          , El Salvador President Bukele Cancels Miami Bitcoin Conference Appearance                                                                                                                                                                  , Bitcoin Drops Most in a Month as Markets Turn Risk-Averse                                                                                                                                                                                 , Banks Are ‘Very Far Away’ From Trading Crypto, Genesis CEO Says                                                                                                                                                                           , Sunil Jagtiani                                                                                                                                                                                                                            , Stocks and U.S. equity futures fell Thursday after the Federal Reserve outlined plans to pare its balance sheet by more than $1 trillion a year while hiking interest rates in a campaign to curb elevated inflation.                     , Equities in Japan, South Korea and Australia declined, as did S&amp;P 500 and Nasdaq 100 contracts. Technology shares led a retreat Wednesday on Wall Street, handing the Nasdaq 100 its worst two-day loss in nearly a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/06/politics/china-military-russia-ukraine-what-matters/index.html </td>
   <td style="text-align:left;"> 2022-04-07 06:22:53 </td>
   <td style="text-align:left;"> 6 key points about China's military after top general's warning - CNNPolitics </td>
   <td style="text-align:left;"> A version of this story appeared in CNN's What Matters newsletter. To get it in your inbox, sign up for free here.                                                                                                                                                                                                                                                                                                                                                                                                                ,  (CNN)China and Russia are bent on changing the "rules-based current global order," according to America's top general.                                                                                                                                                                                                                                                                                                                                                                                                           , Chairman of the Joint Chiefs Gen. Mark Milley's prognosis, offered on Tuesday as he asked Congress for more money for the Pentagon, is for an era where large-scale war between major powers is a possibility.                                                                                                                                                                                                                                                                                                                    , "We are entering a world that is becoming more unstable, and the potential for significant international conflict between great powers is increasing, not decreasing."                                                                                                                                                                                                                                                                                                                                                            , Russia's invasion of Ukraine threatens "not only European peace and stability but global peace and stability that my parents and a generation of Americans fought so hard to defend," Milley said.                                                                                                                                                                                                                                                                                                                                , He actually isn't asking for enough money for the Pentagon, according to many Republicans and some moderate Democrats, who noted the Department of Defense didn't properly account for inflation when it requested $773 billion for the 2023 fiscal year -- a 4% boost that is less than inflation, which is currently the highest it's been in 40 years.                                                                                                                                                                         , To better account for inflation, there are calls for the Pentagon to get more than what it asked for. The war in Ukraine and warnings like Milley's will only focus Americans that much more on security.                                                                                                                                                                                                                                                                                                                         , The threat Russia poses to America's NATO allies in Europe is clear from the invasion of Ukraine, but Milley referred to Russia in the same breath as China.                                                                                                                                                                                                                                                                                                                                                                      , The growth of China's military, particularly its navy, has concerned American defense officials and lawmakers in recent years.                                                                                                                                                                                                                                                                                                                                                                                                    , A new arms race. An emblem of concerns about US military dominance is the very specific focus in recent weeks on hypersonic missiles.                                                                                                                                                                                                                                                                                                                                                                                             , "The US has placed a renewed emphasis on hypersonic weapons following successful Russian and Chinese tests in recent months, exacerbating the concern in Washington that the US is falling behind on a military technology considered critical for the future," CNN's Oren Liebermann recently wrote.                                                                                                                                                                                                                             , There is a growing narrative -- not unlike the one pushed by President Joe Biden that the US is falling behind to China in its technological capacity -- that the US military is falling behind China's.                                                                                                                                                                                                                                                                                                                          , "Unprecedented Chinese military modernization has enabled them to leapfrog us in key capabilities," Rep. Mike Rogers of Alabama said at the hearing Tuesday. "The Chinese Communist Party now controls the largest army and navy in the world. It has more troops, more ships and more hypersonic missiles than the United States."                                                                                                                                                                                               , To find out more about what the US knows about China's military capacity and spending, I reached out to Matthew P. Funaiole, a China expert, data analyst and senior fellow at the Center for Strategic and International Studies.                                                                                                                                                                                                                                                                                                , Six key points from our phone conversation, lightly edited for clarity and length, are below.                                                                                                                                                                                                                                                                                                                                                                                                                                     , 1. China has a long-term strategic goal that involves the US                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , FUNAIOLE: China wants to establish itself as the premier power broker in the Indo-Pacific, displace the US in that sense, and it sees its military as one of the primary means of doing that ... you see that materializing in a number of different ways.                                                                                                                                                                                                                                                                        , The one that gets a lot of attention is China upgrading its navy and all the efforts that it's put into building new surface combatants, upgrading submarines and developing an aircraft carrier program. That's where we're seeing a lot of advancement happening pretty quickly.                                                                                                                                                                                                                                                , 2. The idea that China has 'leapfrogged' the US needs context                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , FUNAIOLE: China still lags the US considerably in terms of overall spending (less than half, according to this estimate). But a significant caveat is that the US maintains a global presence and has military assets all across the globe ... China's forces are much more localized within the region ... but it also spends more than Korea, Japan and Vietnam combined ... So you have to think about it redrawn in the context of how that spending compares.                                                                , In terms of technology, Funaiole argued the US still maintains a research and development advantage, but that China has clearly worked at catching up in some specific areas.                                                                                                                                                                                                                                                                                                                                                     , 3. China's military, like Russia's, lacks the human backbone the US military has                                                                                                                                                                                                                                                                                                                                                                                                                                                  , FUNAIOLE: The US, for better or worse, has been engaged in conflicts around the globe pretty consistently since the end of the Second World War, whereas China's military is untested. So the technology will be important and the military spending is really important.                                                                                                                                                                                                                                                         , But the one place where China can't really leapfrog ahead, because it's just based on experience, is the personnel component. Whereas the US can draw from generations of ingrained experience ... So technology tells you one part of it, spending tells you one part of it, but there's also that personnel component where China doesn't have that experience.                                                                                                                                                                 , 4. China and Russia are not exactly allies                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , FUNAIOLE: That framing of autocracies vs. democracies, I think, is effective in understanding what's actually at risk right now in the way that we think about these international norms and ideals. But China and Russia, they work together as partners, they're closer together on some things than they are on others -- but they're not allies in the same way that we traditionally think about allies in the US system.                                                                                                    , The proof Funaiole offered is that the West -- including the US and its allies -- has effectively united against Russia on Ukraine, but China has stayed at an arm's distance.                                                                                                                                                                                                                                                                                                                                                    , 5. Keep an eye on China's navy development                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , FUNAIOLE: When China launches its third aircraft carrier, which is going to be a flat-top aircraft carrier, it's going to use a ... catapult system to launch aircraft -- that's advanced new technology ... And a couple years from now, when it's actually positioned into the Chinese navy, that's going to be something that people are going to be talking about. When China develops its first nuclear reactor for powering aircraft carriers, that's going to be something that people are going to start talking about ..., We need to have a more comprehensive understanding of the spaces in which China is investing, where China is upgrading its military and what that necessarily means, as far as US interests are concerned, in the US' ability to develop or to leverage existing countermeasures.                                                                                                                                                                                                                                                 , 6. Putin's difficulty in Ukraine sends a message to China                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , FUNAIOLE: If a month ago or six weeks ago, you thought that you could test the system and that you wouldn't necessarily get much pushback from it, you might think differently about that now ... Certainly we're entering or we have entered into a more multipolar era where the bygone days of US unipolarity have eroded away, but we're also seeing pretty effective use of how the US can build coalitions with its allies and partners to help reinforce the principles, ideals and institutions that they stand for.      , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/06/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-04-07 06:02:16 </td>
   <td style="text-align:left;"> Stock futures are flat following a 2-day losing streak for the major averages </td>
   <td style="text-align:left;"> , Stock futures were flat in overnight trading Wednesday after a two-day losing streak for the major averages as investors digested the Federal Reserve's plans to tighten monetary policy.                                                                                                                                                                                                               , Futures on the Dow Jones Industrial Average dipped 30 points. S&amp;P 500 futures inched 0.1% lower and Nasdaq 100 futures were little changed.                                                                                                                                                                                                                                                             , The back-to-back sell-off came as Fed meeting minutes showed that officials planed to reduce their trillions in bond holdings with a consensus amount around $95 billion. Meanwhile, policymakers indicated that one or more 50-basis-point interest rate hikes could be warranted to battle surging inflation.                                                                                         , "The minutes from the latest FOMC meeting portray a higher level of urgency than previous communication as the Fed has circled on a commitment to run the balance sheet down faster than market participants may have expected," said Charlie Ripley, senior investment strategist at Allianz Investment Management.                                                                                    , Officials "generally agreed" that a maximum of $60 billion in Treasurys and $35 billion in mortgage-backed securities would be allowed to roll off, phased in over three months and likely starting in May.                                                                                                                                                                                             , On Wednesday, the blue-chip Dow fell more than 100 points, while the S&amp;P 500 slid 1%. The tech-heavy Nasdaq Composite dropped another 2.2%, bringing its week-to-date losses to 2.6%.                                                                                                                                                                                                                   , "It does seem like they are talking up the possibility of raising rates by 50 basis points at the next meeting so the hope is that message is well telegraphed in advance," said Brian Price, head of investment management at Commonwealth Financial Network. "I expect that volatility will remain elevated for the time being as there is a lot of uncertainty for investors to digest right now."   , Investors await the weekly jobless claims data Thursday morning, which is expected to show a total of 200,000 claims filed.                                                                                                                                                                                                                                                                             , Shares of Levi Strauss &amp; Co. rose more than 1% in extended trading Wednesday after the denim retailer reported its quarterly earnings and revenue that topped analysts' estimates.                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61010605?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-07 05:30:42 </td>
   <td style="text-align:left;"> Energy strategy: UK plans new nuclear reactors to boost production </td>
   <td style="text-align:left;"> Up to eight more nuclear reactors could be built on existing sites as part of the UK's new energy strategy.                                                                                                                                                         , The plan, which aims to boost UK energy independence and tackle rising prices, also includes plans to increase wind, hydrogen and solar production.                                                                                                                 , But experts have called for a bigger focus on energy efficiency and improving home insulation.                                                                                                                                                                      , Consumers are facing soaring energy bills after the Russian invasion of Ukraine pushed gas prices even higher.                                                                                                                                                      , Under the government's new plans, up to 95% of the UK's electricity could come from low-carbon sources by 2030.                                                                                                                                                     , It outlines, for example, the hope of producing up to 50 gigawatts (GW) of energy through offshore wind farms, which the Department for Business, Energy and Industrial Strategy (Beis) said would be more than enough to power every home in the UK.               , But one of the big points of contention is thought to have been the construction of onshore wind turbines.                                                                                                                                                          , The government announced that a new body called Great British Nuclear will also be launched to bolster the UK's nuclear capacity, with the hope that by 2050 up to 24 GW of electricity will come from that source - 25% of the projected electricity demand.       , It has said the focus on nuclear will deliver up to eight reactors overall, with one being approved each year until 2030.                                                                                                                                           , It also confirmed advanced plans to approve two new reactors at Sizewell in Suffolk during this parliament.                                                                                                                                                         , Wylfa in Anglesey and Oldbury in Cumbria have also been named as candidates to host either large-scale plants, smaller modular nuclear reactors, or possibly both.                                                                                                  , Funding the construction of new nuclear power stations has proved challenging in recent years as they are expensive to build.                                                                                                                                       , Critics of nuclear power say new facilities take so long to come on stream they will be too late to meet the UK's emissions targets or to reduce energy prices.                                                                                                     , But Tom Greatrex, boss of the Nuclear Industry Association, said the plans marked a "vital step forward" for the UK to meet its climate goals, and could create thousands of jobs.                                                                                  , "The ambition and determination to do much more and quicker is very welcome," he said.                                                                                                                                                                              , The government also said it will also reform planning rules to slash approval times for new offshore wind farms.                                                                                                                                                    , For onshore wind, the strategy only commits to consulting on developing partnerships with "a limited number of supportive communities" who want to host wind turbines in exchange for lower energy bills.                                                           , Although it is one of the cheapest forms of energy, new onshore wind projects have been declining since 2015 when the government ended subsidies and introduced stricter planning rules in response to some complaints that wind turbines were an eyesore and noisy., Targets for hydrogen production are also being doubled.                                                                                                                                                                                                             , As well as increasing the production of renewable energy, there are also plans to accelerate North Sea oil and gas projects.                                                                                                                                        , A new licensing round for the projects is set for the autumn.                                                                                                                                                                                                       , The government said it recognised the importance of these fuels to energy security "and that producing gas in the UK has a lower carbon footprint than imported from abroad".                                                                                       , Environmentalists and many energy experts have reacted with disbelief and anger at some of the measures in the strategy.                                                                                                                                            , They cannot believe the government has offered no new policies on saving energy by insulating buildings.                                                                                                                                                            , They say energy efficiency would immediately lower bills and emissions, and is the cheapest way to improve energy security.                                                                                                                                         , A Downing Street source said the strategy was now being see as an energy supply strategy.                                                                                                                                                                           , Campaigners are also furious that ministers have committed to seeking more oil and gas in the North Sea, even though humans have already found enough fossil fuels to wreck the climate.                                                                            , There is a strong welcome, though, for the promise of more energy from wind offshore with speedier planning consent                                                                                                                                                 , The same boost has not been offered to onshore wind.                                                                                                                                                                                                                , The decision to boost nuclear has drawn a mixed reaction. Some environmentalists say it's too dear and too dangerous. They ridicule the idea from some politicians that every city could have its own mini reactor.                                                 , But other climate campaigners believe nuclear must be part of the energy mix.                                                                                                                                                                                       , Green Party co-leader Adrian Ramsay said the new strategy "did not serve the needs of people or the climate".                                                                                                                                                       , UK energy prices have been rising for months due to surging demand as Covid restrictions eased. But the Russian invasion of Ukraine pushed up costs up even further.                                                                                                , Although Russian imports account for only 8% of UK oil and 5% of gas supplies, it is still affected by rising wholesale prices worldwide and household budgets have come under pressure.                                                                            , Mr Ramsay suggested that if the government was "concerned about energy bills and taking real climate action, it would be going even further on onshore wind."                                                                                                       , The plan was welcomed by offshore wind firm Orsted, trade association Hydrogen UK, Shell and EDF, among others.                                                                                                                                                     , But Ed Miliband, Labour's shadow climate change and net-zero secretary, said: "The government's energy relaunch is in disarray.                                                                                                                                     , "Boris Johnson has completely caved to his own backbenchers and now, ludicrously, his own energy strategy has failed on the sprint we needed on onshore wind and solar, the cheapest, cleanest forms of homegrown power.                                            , "This relaunch will do nothing for the millions of families now facing an energy bills crisis," he added.                                                                                                                                                           , Liberal Democrat leader Sir Ed Davey also described the plans as "utterly hopeless", while the SNP's Stephen Flynn called it a "missed opportunity".                                                                                                                , Dr Simon Cran-McGreehin, head of analysis at the Energy &amp; Climate Intelligence Unit, told the BBC that he also felt "underwhelmed" following the announcement.                                                                                                      , "We started off with a price crisis during the winter, we're now potentially heading into a supply crisis.                                                                                                                                                          , "This is an immediate problem that needs solutions now, and this doesn't do anything on prices.                                                                                                                                                                     , "It tries to do some things on energy supply, but they're all medium to long-term measures. So it does seem to fail the exam question," he said.                                                                                                                    , Prime Minister Boris Johnson said in a statement that the strategy would "reduce our dependence on power sources exposed to volatile international prices we cannot control, so we can enjoy greater energy self-sufficiency with cheaper bills".                   , Business and Energy Secretary Kwasi Kwarteng added: "Scaling up cheap renewables and new nuclear, while maximising North Sea production, is the best and only way to ensure our energy independence over the coming years."                                         , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                     , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                              , Why does it impact almost every system in the human body?                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 04:42:00 </td>
   <td style="text-align:left;"> Brazilian Equities End at 2-Week Low </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, was down 0.6% to close at 118,228 on Wednesday, its lowest since March 23rd, mainly led by banking, technology, travel and retail stocks. Investors digested more details about the Federal Reserve’s plan to raise interest rates, while also weighing new Western sanctions against Russia. Minutes from the Federal Reserve’s March meeting showed a half-point rate increase is possible along with a reduction in its balance sheet soon. Meanwhile, the US and its allies are enacting new sanctions on Russia in response to the civilian toll reported in Bucha and elsewhere in Ukraine in recent days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-announces-2-nominees-sec/story.aspx?guid={018BAE3F-6D20-4C28-B7C7-54FE4F13E2CB}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 04:39:51 </td>
   <td style="text-align:left;"> Biden announces 2 nominees for SEC - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Wednesday announced two nominees for the Securities and Exchange Commission. A White House statement said Biden is tapping Jaime Lizárraga, currently a senior adviser to House Speaker Nancy Pelosi, a California Democrat, and Mark Uyeda, an SEC attorney who is currently on detail to the Senate Banking Committee., The Fed is expected to clarify how it intends to shrink its $9 trillion balance sheet when it releases  minutes of its March meeting at 2 p.m. Eastern.                                                                                                                                                                                        ,                                                                                                                                                                                                                                                                                                                                                , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/costco-sales-rise-nearly-19/story.aspx?guid={0B33C94E-BA76-4733-90E1-1BC680FDA248}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 04:36:20 </td>
   <td style="text-align:left;"> Costco sales rise nearly 19% in March - MarketWatch </td>
   <td style="text-align:left;"> Costco Wholesale Corp.  said late Wednesday its March sales rose 18.7% to $21.61 billion, from $18.21 billion in March 2021. Comparable-store sales rose 17.2%, including a 19.1% increase in same-store sales in the U.S., Costco said. The five-week March retail month had one extra shopping day, which helped total and comparable-store sales by about 1.5% to 2%, the retailer said. Shares of Costco edged higher in the extended session Wednesday after ending the regular trading day up 1.7%. , The Dow Jones Transportation Average slipped into bear market territory. That can mean bad news for the U.S. economy and the U.S. stock market.                                                                                                                                                                                                                                                                                                                                                           , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 04:15:00 </td>
   <td style="text-align:left;"> US Stocks Fall for 2nd Day </td>
   <td style="text-align:left;"> Wall Street extended the decline for a 2nd day with the Dow ending the Wednesday session 100 points lower and the S&amp;P 500 and the Nasdaq falling 1% and 1.7%, respectively, as Federal Reserve gave more guidance on how fast the monetary policy would be tightened. The FOMC minutes showed that the central bank was considering hiking rates by 50-basis-point, given a worsening inflation outlook. Officials also agreed that monthly caps of about $95 billion in the balance sheet reduction would likely be appropriate, higher than the $50 billion a month trim the Fed made back in 2017-2019. Technology and consumer discretionary stocks led the losses,  while utilities, real estate, and consumer staples ended in the positive territory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 04:10:00 </td>
   <td style="text-align:left;"> Toronto Stocks Close at Near 3-Week Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, fell about 0.6% to close at 21,789 on Wednesday, its lowest since March 17th, extending losses for a second day, in line with its global peers. Technology and energy shares were the worst performers after the latest FOMC minutes showed Fed officials discussed the prospect of stepping up the pace of monetary policy tightening including plans to cut the size of the central bank’s balance sheet soon. At the same time, worries about the global economic impact of tougher sanctions against Russia weighed. Canada and its G7 partners, as well as the EU, were mulling imposing tougher sanctions on Russia’s financial sector and banning Russian coal imports. On corporate updates, Suncor Energy announced its exit from wind and solar power two-decade old investments to focus on hydrogen and renewable fuel in its efforts to become a net-zero company by 2050. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nasdaq-sinks-more-2-stocks/story.aspx?guid={34B817D3-BEC7-427B-95A5-9DD09D0833FE}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 04:03:20 </td>
   <td style="text-align:left;"> Nasdaq sinks more than 2% as stocks end lower after Fed minutes - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended lower but off their worst levels, with the tech-heavy Nasdaq Composite bearing the brunt of selling pressure for a second session Wednesday after minutes of the Federal Reserve's March policy meeting outlined plans for shrinking the central bank's nearly $9 trillion balance sheet. The Dow Jones Industrial Average ended with a loss of around 145 points, or 0.4%, near 34,497, according to preliminary figures, while the S&amp;P 500 
        SPX,
        -0.97%
       sank around 44 points, or 1%. to finish near 4,481. The Nasdaq Composite 
        COMP,
        -2.22%
       shed around 315 points, or 2.2%, closing near 13,889., The Dow Jones Transportation Average slipped into bear market territory. That can mean bad news for the U.S. economy and the U.S. stock market.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-61011022?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-07 04:00:14 </td>
   <td style="text-align:left;"> Ukraine war: Bucha deaths 'not far short of genocide' - PM </td>
   <td style="text-align:left;"> Attacks on civilians by Russian forces in the Ukrainian town of Bucha do not "look far short of genocide", Prime Minister Boris Johnson has said.                                                                                                                , The UK has announced further sanctions against eight oligarchs and Russian banks, including the country's largest, Sberbank, and Credit Bank of Moscow.                                                                                                          , Dozens of people have been found dead in the town - including some in a mass grave - after Russia's withdrawal.                                                                                                                                                  , Moscow denied involvement and described reports as fake news.                                                                                                                                                                                                    , The Foreign Office announced its latest sanctions following the reports of attacks on civilians, and these include ending all imports of Russian coal and oil by the end of the year as well as action against strategic industries.                             , The latest sanctions come in step with those imposed by the US, which has also imposed sanctions on Russian President Vladimir Putin's two daughters.                                                                                                            , Ahead of the new sanctions being announced, Mr Johnson said: "I'm afraid when you look at what's happening in Bucha, the revelations that we are seeing from what Putin has done in Ukraine doesn't look far short of genocide to me.                            , "It is no wonder people are responding in the way that they are. I have no doubt that the international community, Britain very much in the front rank, will be moving again in lockstep to impose more sanctions and more penalties on Vladimir Putin's regime.", As part of its sanctions response, the UK has pledged to stop importing Russian oil by the end of the year, while the EU is reducing its imports of Russian gas by two-thirds.                                                                                   , Mr Johnson praised the "enormous strides" the EU is taken to reduce dependence on Russian gas.                                                                                                                                                                   , At a working dinner in Brussels on Wednesday evening Foreign Secretary Liz Truss is expected to tell Nato colleagues the "age of engagement with Russia is over".                                                                                                , She is expected to say there is "no time for false comfort" and that Russia is not retreating but regrouping to push harder in the east of Ukraine.                                                                                                              , Ms Truss is expected to urge allies to arm Ukraine quickly and decisively, and to rethink its support for countries "caught in the web of Russian influence", such as Georgia and Moldova.                                                                       , As part of sanctions imposed on Russia all new outward investment to the country has been banned, while imports of Russian iron and steel products will be banned.                                                                                               , Among those added to the sanctions list is Viatcheslav Kantor, the largest shareholder of fertilizer company Acron, whose donations funded a new unit at a London hospital used by the royal family.                                                             , The Edward VII Hospital accepted a donation from the Kantor Charitable Foundation to fund the Kantor Medical Centre.                                                                                                                                             , The other oligarchs added to the sanctions list include:                                                                                                                                                                                                         , Ms Truss said the latest wave of sanctions would decimate Mr Putin's "war machine" and show the Russian elite could not wash their hands of the atrocities committed on his orders.                                                                              , Sanctions are penalties imposed by countries intended to stop aggression, or punish breaches of international law, and often involve financial curbs.                                                                                                            , Those taken by the UK so far include freezing assets, excluding Russian banks from the UK financial system, banning some exports to Russia, restricting visas for wealthy investors and banning flights.                                                         , By the end of the year, the UK has said it will also phase out Russian oil imports.                                                                                                                                                                              , Along with the EU and US, it has frozen the assets of more than 1,000 individuals and companies, including politicians and wealthy business leaders thought to be close to the Kremlin.                                                                          , Asset freezes prevent anyone in the UK or any UK company from dealing with any funds or resources that are owned or held by the designated person, and prevent resources being provided to or for the benefit of that person.                                    , Labour leader Sir Keir Starmer had called for "even tougher sanctions" following the "horrific, harrowing images" of civilian deaths in Bucha.                                                                                                                   , He said we have to give Ukraine "every support we can" and said the international community must be clear "that these war crimes will end up with those responsible being hunted down".                                                                          , The deliberate targeting of civilians, as has been alleged by residents of Bucha, is a war crime under the Geneva Convention.                                                                                                                                    , But for a massacre to be considered genocide, the law also requires proof of the intent to destroy a particular national, ethnic, racial or religious group - whether entirely or in part.                                                                       , The Genocide Convention, introduced after the Nazi Holocaust during World War Two, requires the 152 nations who are signatories to "prevent and to punish" genocide where it occurs.                                                                             , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                  , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                           , Why does it impact almost every system in the human body?                                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/california-gas-stations-insane-prices-will-make-your-jaw-drop </td>
   <td style="text-align:left;"> 2022-04-07 04:00:12 </td>
   <td style="text-align:left;"> California gas station's 'insane' prices will make your jaw drop </td>
   <td style="text-align:left;"> GOP Senators discuss high gas prices and 'Biden Admin's energy crisis.'                                                                                                                                                                                                                                                                                                                                                        , It is no surprise that California has the highest gasoline prices in the U.S. given that it has the highest gas taxes, but even natives of The Golden State are being blown away by the eye-popping sticker prices they are finding at the pump.                                                                                                                                                                               , Matt Shupe of Walnut Creek, California, the principal at Praetorian Public Relations, was on a road trip through the state this week when he stumbled across gas prices that made his jaw drop.                                                                                                                                                                                                                                , Gas prices at the Gorda General Store in Big Sur, California, on April 3, 2022. (Matt Shupe)                                                                                                                                                                                                                                                                                                                                   , During a stop at a remote station in Big Sur on Sunday, Shupe decided to glance at the pump before going inside to buy snacks and was relieved that he didn't need a fill-up. The price for premium gas, which his car requires, was $9.799. He wrote on Instagram that he is "still blown away by these nearly $10 [per] gallon insane gas prices."                                                                           , DEMOCRATS, REPUBLICANS SPAR WITH OIL EXECUTIVE ON WHO'S TO BLAME FOR HIGH GAS PRICES                                                                                                                                                                                                                                                                                                                                           , "I've been going out of my way to find Costco gas stations along the route because the gas prices have been so insane," Shupe told FOX Business. He said braving the lines at Costco has saved him $10 or $20 a tank.                                                                                                                                                                                                          , The average price of gas in California is currently $6.17 per gallon for premium and $5.82 for regular, according to AAA. The national average for regular is $4.16.                                                                                                                                                                                                                                                           , LOWER, MIDDLE-INCOME FAMILIES GETTING ‘CRUSHED’ BY INFLATION: REP. STEVE SCALISE                                                                                                                                                                                                                                                                                                                                               , Shupe has been documenting the gas prices in California on social media, flagging staggering prices and long lines.                                                                                                                                                                                                                                                                                                            , Last month, he posted a picture on Facebook showing the price of premium gas at $6.99 per gallon in downtown Los Angeles, and a line at a Costco gas station in the city the next day that was so long employees were out coordinating traffic, when he says a gallon of premium was $5.69 at the retailer.                                                                                                                    , The line at a Costco gas station in Los Angeles, California, on March 10 where the price for a gallon of premium gasoline was $5.69. (Matt Shupe)                                                                                                                                                                                                                                                                              , "I'm overlooking Brentwood in Beverly Hills right now," Shupe told FOX Business on Wednesday, while still on his road trip. "You know, these people in $10-$15 million dollar mansions as their third home aren't worried about a 50-60% increase in gas prices, but for the 38 million Californians that don't live like that – this absolutely affects them on an everyday basis. They have to cut corners and clip coupons.", GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                    , Shupe said that someone who was on the trip with him is in their 60s told him, "This is like the Carter era and it's just out of control." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/house-hearing-oil-executives-smoke-screen-gas-prices-sarbanes </td>
   <td style="text-align:left;"> 2022-04-07 03:52:17 </td>
   <td style="text-align:left;"> House Democrat says oil execs 'throwing up a smoke screen’ amid allegations of price gouging </td>
   <td style="text-align:left;"> American Petroleum Institute CEO Mike Sommers argues Democratic politicians are continuing to 'browbeat' U.S. oil companies.                                                                                                                                                                                                                                                                                                             , Rep. John Sarbanes, a Democrat on the House Energy and Commerce Committee, said Wednesday he didn't believe explanations from energy company executives who testified about high gas prices.                                                                                                                                                                                                                                             , "I think they're throwing up a smoke screen on what is essentially a profiteering situation that's going on," Sarbanes, D-Md., told Fox News Digital. "And it's unfortunate, because the average person, as I said, who's out there at the pump, they're taking a hit. And meanwhile, the oil companies and the executives are making a killing."                                                                                        , Sarbanes, like several Democrats at the hearing, pressed the executives about their companies' profits and whether they had a duty to reduce their prices. The executives emphasized the complexity and global nature of the energy market and how individual companies don't control prices. Sarbanes wasn't satisfied.                                                                                                                 , DEMOCRATS, REPUBLICANS SPAR WITH OIL EXECUTIVES ON WHO'S TO BLAME FOR HIGH GAS PRICES                                                                                                                                                                                                                                                                                                                                                    , "There's a lot of hocus-pocus language you can throw up here. I think you need to pass savings along when you realize them," Sarbanes said.                                                                                                                                                                                                                                                                                              , Rep. Bobby Rush, D-Ill., also said the energy executives weren't truly answering questions about how to help Americans.                                                                                                                                                                                                                                                                                                                  , "They have not answered the question about … when will the American consumer get some relief?" Rush told Fox News Digital.                                                                                                                                                                                                                                                                                                               , HOUSE HEARING WITH OIL EXECUTIVES SETS UP PARTISAN CLASH OVER GAS PRICES                                                                                                                                                                                                                                                                                                                                                                 , Republicans at the hearing, "Gouged at the Gas Station: Big Oil and America's Pain at the Pump," countered that President Biden and Democrats are responsible for gas prices.                                                                                                                                                                                                                                                            , "They're just trying to blame this thing — take the blame off of the administration," Rep. Gus Bilirakis, R-Fla., told Fox News Digital after questioning witnesses at the hearing.                                                                                                                                                                                                                                                      , "The [EastMed] pipeline is so very important, and the fact that this administration basically withheld their support after they were supportive of this particular project, it's inconceivable," Bilirakis said. "We don't want people depending on Russian oil or oil from our adversaries. And that's exactly what's going on right now."                                                                                              , BIDEN, PELOSI LIMITED OIL SUPPLY BY SHUTTING DOWN PRODUCTION, SAYS REP. STEVE SCALISE                                                                                                                                                                                                                                                                                                                                                    , "We're going to fight to reverse course and bring down these prices," Bilirakis added. "And that's how you do it — with domestic production and production from our allies so that we don't have to depend on these foreign countries that are basically not our friends in most cases."                                                                                                                                                 , Gas prices are displayed at a gas station March 11, 2022, in Long Beach, Calif.  (AP Photo/Ashley Landis / AP Newsroom)                                                                                                                                                                                                                                                                                                                  , Rep. John Joyce, R-Pa., said "when Biden came into office … canceling the Keystone XL pipeline, it put a major crimp not only into American energy independence and dominance, but into world energy independence."                                                                                                                                                                                                                      , But Joyce also took a more optimistic view of things, arguing the hearing showed how the U.S. has significant geopolitical opportunities because of its domestic energy.                                                                                                                                                                                                                                                                 , "This was an important hearing to hold today, because it allowed us to illuminate that we in America have the capabilities of producing additional oil and natural gas that can, not only lead to American independence, but American dominance," Joyce said. "If we provide the right infrastructure … we can take those supplies of oil, natural gas and supply our friends and allies in Europe, to sever their dependence on Putin." , The executives who testified remotely at the hearing were BP America President David Lawler, Chevron Corp. CEO Michael Wirth, Devon Energy CEO Richard Muncrief, Exxon Mobil CEO Darren Woods, Pioneer Natural Resources CEO Scott Sheffield and Shell USA President Gretchen Watkins.                                                                                                                                                   , Oil wells outside of Williston, N.D., Aug. 24, 2021. (Tyler Olson/FOX Business / FOXBusiness)                                                                                                                                                                                                                                                                                                                                            , DEMOCRATS ‘GASLIGHTING THE AMERICAN PEOPLE’: REP. ARMSTRONG                                                                                                                                                                                                                                                                                                                                                                              , The executives faced frequent interruptions from Democrats who sought to attack them over their alleged fault for energy prices and occasionally from Republicans who thought the execs' answers were too diplomatic.                                                                                                                                                                                                                    , "So, apparently everybody wants to get in the weeds and hide behind words," ranking member H. Morgan Griffith, R-Va., said at the beginning of the hearing. "The president says he wants to make sure that we do not lower the cost of production. Is that going to make you produce more or less? Mr. Woods, more or less?"                                                                                                             , "I think the government has a role in encouraging investment and creating a positive investment climate," Exxon Mobil Corp. CEO Darren Woods responded.                                                                                                                                                                                                                                                                                  , Rep. H. Morgan Griffith, R-Va., ranking member of the House Energy and Commerce Committee                                                                                                                                                                                                                                                                                                                                                , "And when we create a negative climate you produce less, isn't that true. Yes or no?" Griffith shot back.                                                                                                                                                                                                                                                                                                                                , "There tends to be a chilling effect with negative words," Woods said.                                                                                                                                                                                                                                                                                                                                                                   , Rush argued Republicans were simply seeking to take advantage of the energy situation to improve their chances in the midterms.                                                                                                                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                              , "With them, it's all about 2022. It's all about the next election, about the midterms," Rush said. "They really want to make essentially a political argument … they don't want to debate on the merits of the suffering of the American people and how we'll really solve their problem. And to me, they're disingenuous … they're only interested in power and control of the Congress."                                               , On Republicans' handling of the hearing, Sarbanes said they were "trying to suggest that somehow the production is being limited by the administration when that's not the case."                                                                                                                                                                                                                                                        , "There are 9,000 permits that the oil companies could be using to increase production, and they apparently don't have any interest in doing that," Sarbanes added.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/06/governors-say-financial-education-should-extend-beyond-school-years.html </td>
   <td style="text-align:left;"> 2022-04-07 03:27:07 </td>
   <td style="text-align:left;"> 'It's a lifelong experience.' Governors say financial education should extend beyond school years </td>
   <td style="text-align:left;"> , Pursuing financial literacy is something that should continue beyond traditional school years, according to several state governors.                                                                                                                                                                                                 , "We think it's a lifelong experience," New Jersey Gov. Phil Murphy told CNBC's Sharon Epperson during Wednesday's event, Invest in You: The Governors Strategy Session on Financial Education.                                                                                                                                       , Gov. Steve Sisolak of Nevada agrees about the importance of financial literacy.                                                                                                                                                                                                                                                      , "It's a skill that's necessary for your entire life," he said. "We have to approach it more long-term in that regard."                                                                                                                                                                                                               , There are no federal guidelines for personal finance education in schools, which means it's up to individual states to set their own rules. And there are 23 states that mandate a personal finance course for students, according to the 2022 Survey of the States from the Council for Economic Education.                         , In New Jersey, personal finance education is taught in middle school, and classes in financial, economic business and entrepreneurial business literacy are required to graduate.                                                                                                                                                    , "You need to get to folks while they're young, and that's the animating reason behind getting financial literacy education into our middle school curriculum," said Murphy, a Democrat.                                                                                                                                              , More from Invest in You:Want a fun way to teach your kids about money? Try these gamesInflation fears force Americans to rethink financial choicesHere's what consumers plan to cut back on if prices continue to surge                                                                                                              , Nevada students are taught about personal finance topics as a part of social studies class, generally starting in grade three and going through high school. In Mississippi, beginning this year, a college and career readiness class that includes personal financial education is required for high school graduation.            , "Each state has to make their own decision and their own priorities as to what classes are most appropriate for their young people," said Mississippi Gov. Tate Reeves, a Republican. "But I am absolutely convinced that a fundamental understanding of finances is incredibly important to one's ability to be successful in life.", That also means that states can change their guidelines as they see fit.                                                                                                                                                                                                                                                             , "A mandatory class may be the next step we go to," said Sisolak, a Democrat. He added that it's important to have such curriculum in schools because many students can't get financial education at home from their parents, who may also fall short on financial literacy.                                                          , The state governors agree that one of the reasons it's important to have personal finance curriculum in schools is because many students' parents can't teach them about financial literacy at home or simply aren't talking about money enough.                                                                                     , New Jersey is also offering residents access to more personal financial education outside of school. Murphy announced today, during the CNBC event, that the state has launched NJ FinLit, a financial wellness platform.                                                                                                            , "Financial literacy is incredibly important for Americans to secure their personal financial footing, to be better positioned to provide for their families and set themselves up for future success," Murphy said.                                                                                                                  , The platform was developed by Enrich and is powered by San Diego-based financial education company iGrad. It includes personal finance courses on several topics, including budgeting, saving, retirement, student loans and has real-time budget tools, as well. It is free for all adult New Jersey residents.                     , States have also made sure that educators have resources for professional development to keep up with the ever-changing financial environment and field questions about things such as meme stocks and cryptocurrencies.                                                                                                             , Mississippi offers a master teacher in personal finance program and coaching.                                                                                                                                                                                                                                                        , "The best way for a kid to get a quality education is to have a quality teacher," Reeves said. "You have to continuously have continuing education for personal finance teachers just like you do for English, math or any other subjects."                                                                                          , Of course, each state has areas in which its could improve their personal finance education offerings for students, training for teachers and resources for adult constituents. And each state will likely come up with individual solutions and offerings for their residents going forward.                                        , Many states are moving forward with legislation mandating personal finance education for their students. There are currently 54 personal finance education bills pending in 26 states, according to Next Gen Personal Finance's bill tracker.                                                                                        , While various states' approaches may differ, the governors agreed during Wednesday's event that personal financial education is an important investment in the future success of residents, especially children.                                                                                                                     , "We have to get kids in the shallow end of the pool before we drop them into the deep end," Sisolak said.                                                                                                                                                                                                                            , SIGN UP: Money 101 is an 8-week learning course to financial freedom, delivered weekly to your inbox. For the Spanish version Dinero 101, click here.                                                                                                                                                                                , CHECK OUT: 74-year-old retiree is now a model: 'You don't have to fade into the background' with Acorns+CNBC                                                                                                                                                                                                                         , Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns.                                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ifit-withdraws-ipo-following-postponement/story.aspx?guid={20C05575-04D4-B545-7BB0-8CBCCE33400B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 03:26:00 </td>
   <td style="text-align:left;"> iFit withdraws IPO following postponement in October - MarketWatch </td>
   <td style="text-align:left;"> NordicTrack brand owner iFit Health &amp; Fitness Inc. is scrapping its plans for an already postponed initial public offering, according to a filing with the Securities and Exchange Commission on Wednesday. In its brief filing with the SEC, iFit merely said: “The company is applying for withdrawal of the registration statement because the company has determined not to pursue the contemplated offering at this time.” Back in October, the company said it was postponing its IPO due to “adverse market conditions,” but would “continue to evaluate the timing for the proposed offering.” The Logan, Utah-based company, which competes with Peloton Interactive Inc. 
        PTON,
        -4.92%,
       initially filed for the IPO on Aug. 31., Fed governor Lael Brainard took a hawkish tone in a speech, and markets took notice.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-07 03:17:31 </td>
   <td style="text-align:left;"> US Natural Gas Fail to Hold Gains </td>
   <td style="text-align:left;"> US natural gas futures bottomed around the $6.0/MMBtu level, easing from a six-month high of $6.4 hit earlier this session as investors ditched some long positions following a slump in crude prices following news that IEA would release 120 million barrels to counter supply worries. Still, fundamentals in the natural gas complex continue to be supported by solid demand and cold weather expectations. The probability that Europe may at least partially ban Russia's natural gas, oil or coal imports are rising. The LNG shipments to Europe are already at record levels, and the US is facing significant pressure to help Europe secure further supplies. Meanwhile, Tuesday's pipeline flow data showed the steepest one-day drop in output since the February freeze-off, whilst forecasts pointed to wintry weather in the US West, giving heating demand a boost until mid-April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-04-07 03:06:38 </td>
   <td style="text-align:left;"> Euro Approaches 2-Year Low </td>
   <td style="text-align:left;"> The euro fell to around $1.09, closing in on a nearly 2-year low of $1.0804 hit on March 7th, dragged down by concerns over the outlook of the bloc’s economy amid the war in Ukraine and surging inflation. New sanctions are set to be announced this week to punish Moscow following allegations of civilian massacres in the Ukrainian town of Bucha. Meanwhile, a hawkish FOMC minutes and comments from several Fed officials pushed the dollar up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/600346:ch </td>
   <td style="text-align:left;"> 2022-04-07 03:05:11 </td>
   <td style="text-align:left;"> Dalian Rubber earnings below expectations at 0.40 CH </td>
   <td style="text-align:left;"> Dalian Rubber (600346) released earnings per share at 0.40 CH , compared to market expectations of 0.61 CH . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-04-07 02:51:00 </td>
   <td style="text-align:left;"> Gold Remains Under Pressure on Hawkish Fed </td>
   <td style="text-align:left;"> Gold hovered near $1,920 an ounce on Wednesday, remaining sideways for more than a week, as the odds are rising the Fed will tighten monetary policy faster. FOMC minutes from the last meeting and remarks from several officials including Lael Brainard showed the Fed will make a quick reduction in its balance sheet while some officials would have preferred a bigger hike in the fed funds rate. Meanwhile, investors continue to monitor the war in Ukraine which is far from over. The US announced new sanctions on Russia and the EU is set to follow although a European ban on natural gas imports from Russia is unlikely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fed-raises-possibility-future-mortgage-backed/story.aspx?guid={50E38AF6-C9B6-4698-8E1E-4518E9C7432F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 02:48:12 </td>
   <td style="text-align:left;"> Fed raises possibility of future mortgage-backed securities sales in FOMC minutes - MarketWatch </td>
   <td style="text-align:left;"> The Federal Reserve eventually could resort to selling off mortgage-backed securities on its balance sheet, according to the minutes of the central bank's last strategy session in March. During the March meeting, Fed officials reviewed the results of the central bank's previous efforts at shrinking its balance sheet between 2017 and 2019. Amid the COVID-19 crisis, the Federal Reserve purchased billions of dollars' worth of mortgage-backed securities as part of its broader efforts toward economic stimulus. The Fed has since stopped making those purchases and signaled plans to shrink its balance sheet of mortgage bonds, either through the securities maturing or prepayments. With mortgage rates increasing, the volume of refinances has shrunk considerably. In that context, some Fed officials suggested it "will be appropriate" to consider MBS sales in the future to rid the bank's balance sheet of the securities. Any decision to that effect "would be announced well in advance," the minutes noted., Is your financial planner working in your best interest.?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Jacob Passy is a personal-finance reporter for MarketWatch and is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-07 02:42:00 </td>
   <td style="text-align:left;"> US 10-Year Bond Yield Rises Further </td>
   <td style="text-align:left;"> Debt markets remained under heavy selling pressure in April, with the US yield on the 10-year note surging above 2.63%, its highest level since March 2019. Investors anticipate an aggressive looming policy tightening cycle as major central banks sought to tame inflation, currently running at records levels. On Wednesday Minutes from the Federal Reserve's March meeting showed that the central bank was considering higher rate hikes than its usual 25-basis-point, given a worsening inflation outlook. Officials also agreed that monthly caps of about $95 billion in the balance sheet reduction would likely be appropriate, which is higher than $50 billion a month back in 2017-2019. Meantime, Germany's 10-year Bund yield, the benchmark for Europe, rose to as high as 0.65%, closing in on its highest level since May 2018. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-settle-below/story.aspx?guid={52AC4B2B-FD95-4527-B7FB-9A9DF0D811CE}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 02:36:31 </td>
   <td style="text-align:left;"> U.S. oil futures settle below $100, at lowest in three weeks - MarketWatch </td>
   <td style="text-align:left;"> Oil futures declined Wednesday, with U.S. prices ending the session below $100 a barrel --- at their lowest since mid-March. The International Energy Agency's Executive Director Fatih Birol tweeted that the IEA will release 120 million barrels from its oil reserves. The release includes 60 million from the U.S., as part of that nation's previously announced overall draw from its Strategic Petroleum Reserve, he said. West Texas Intermediate crude for May delivery 
        CLK22,
        +1.36%
       fell $5.73, or 5.6%, to settle at $96.23 a barrel on the New York Mercantile Exchange, the lowest front-month contract finish since March 16, FactSet data show., Here's what to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-04-07 02:33:00 </td>
   <td style="text-align:left;"> Dollar Index Approches 100 Points Mark </td>
   <td style="text-align:left;"> The dollar index extended gains to above 99.7 on Wednesday, back to levels not seen since May of 2020, amid increasing expectations the Fed will tighten monetary policy faster to fight rising inflation. Minutes from the last FOMC meeting showed the Fed will likely reduce its balance sheet by $95 billion a month from May, which is higher than the monthly reduction made in 2017-2019. Also, many participants wanted the fed funds rate to be lifted by 50bps last month rather than the 25bps increase. Early, the dollar was already strengthening amid hawkish comments from Fed officials. At the same time, risk appetite dampened as the West prepared new sanctions on Moscow over civilian killings in northern Ukraine, with the EU proposing to ban Russian coal and to prevent Russian ships from entering EU ports. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/06/business/economy/student-loan-pause-inflation.html </td>
   <td style="text-align:left;"> 2022-04-07 02:32:58 </td>
   <td style="text-align:left;"> How Biden Is Handling Student Loan Payments Amid Inflation - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The administration is in a tight spot as fast inflation makes households unhappy. Trying to offset price pain can risk stoking demand.                                                                                                                                                                                                                                                                                                                                                                                                                           , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , President Biden, under fire for rapid inflation and looking for ways to help cushion rising costs for households, extended a moratorium on student debt payments through August. While politically popular with Mr. Biden’s party, the move drew criticism for adding a small measure of oomph to the very inflation the government is trying to tame.                                                                                                                                                                                                           , America’s robust economic recovery from the deepest pandemic-era lockdowns has left consumers with the power to spend and has fueled fast price increases. Those rising costs are making voters unhappy, jeopardizing Democrats’ chances of retaining control of Congress come November.                                                                                                                                                                                                                                                                         , The moratorium extension stood out as an example of a more general problem confronting the administration: Policies that help households stretch their budgets could soothe voters, but they could also add a little bit of fuel to the inflationary fire at an inopportune moment. And perhaps more critically, analysts said, they risk sending a signal that the administration is not focused on tackling price increases despite the president’s pledge to help bring costs down.                                                                           , Inflation is running at the fastest pace in 40 years and at more than three times the Federal Reserve’s 2 percent goal, as rapid buying collides with constrained supply chains, labor shortages and a limited supply of housing to push prices higher.                                                                                                                                                                                                                                                                                                          , The administration’s decision to extend the student loan moratorium through Aug. 31 will keep money in the hands of millions of consumers who can spend it, helping to sustain demand. While the effect on growth and inflation will most likely be very small — Goldman Sachs estimates that it probably adds about $5 billion per month to the economy — some researchers say it sends the wrong message and comes at a bad time. The economy is booming, jobs are plentiful and conditions seem ideal for transitioning borrowers back into repayment.        , “Four months by itself is not going to get you dramatic inflation,” Marc Goldwein of the Committee for a Responsible Federal Budget said, noting that a full-year moratorium would add only about 0.2 percentage points to inflation, by his estimate. (The White House estimates an even smaller number.) “But it’s four months, on top of four months before that.”                                                                                                                                                                                            , Extra help for student loan borrowers could, at the margin, work at cross-purposes with the Fed’s recent policy changes, which are meant to take away household spending power and cool down demand.                                                                                                                                                                                                                                                                                                                                                             , The Fed in March lifted interest rates for the first time since 2018, and it is expected to make an even larger increase in May as it tries to slow spending and give supply chains some breathing room. It is trying to weaken the economy just enough to put inflation and the economy on a sustainable path, without plunging it into a recession. If history is any guide, pulling that off will be a challenge.                                                                                                                                             , A chorus of economists took to Twitter to express frustration at the decision on Tuesday, when news of the administration’s plans broke.                                                                                                                                                                                                                                                                                                                                                                                                                         , “Wherever one stands on student debt relief this approach is regressive, uncertainty creating, untargeted and inappropriate at a time when the economy is overheated,” wrote Lawrence H. Summers, a former Democratic Treasury secretary and economist at Harvard who has been warning about inflation risks for months. Douglas Holtz-Eakin, a former Congressional Budget Office director who now runs the American Action Forum, which describes itself as a center-right policy institute, summed it up thusly: “aaaaaaarrrrrrRRRRGGGGGGGGHHHHHHHH!!!!!!!!!!”, Yet proponents of even stronger action argued that the moratorium was not enough — and that the affected student loans should be canceled altogether. Senators Chuck Schumer of New York, the Democratic leader, and Elizabeth Warren of Massachusetts are among the lawmakers who have repeatedly pressed Mr. Biden to wipe out up to $50,000 per borrower through an executive action.                                                                                                                                                                         , That stark divide underlines the tightrope the administration is walking as the Nov. 8 elections approach, with Democratic control of the House and the Senate hanging in balance.                                                                                                                                                                                                                                                                                                                                                                               , “They’re buying political time,” Sarah A. Binder, a political scientist at George Washington University, said in an email. “Kicking the can down the road — with another extension, surely, before the elections this fall — seems to be the politically optimal move.”                                                                                                                                                                                                                                                                                          , The administration is taking a calculated risk when it comes to inflation: Student loan deferrals are unlikely to be a major factor that drives inflation higher this year, even if they do add a little extra juice to demand at the margin. At the same time, continuing the policy avoids a political brawl that could tarnish the administration and the Democratic Party’s reputation ahead of the November vote.                                                                                                                                           , White House officials emphasized on Wednesday that the small amount of money the deferrals were adding to the economy each month would have only a marginal impact on inflation. But they could help vulnerable households — including those that did not finish their degrees and that have worse job prospects.                                                                                                                                                                                                                                                , “The impact of extending the pause on inflation is extremely negligible — you’d have to go to the third decimal place to find it, and if you did, it would be .001,” said Jared Bernstein, a member of the White House Council of Economic Advisers.                                                                                                                                                                                                                                                                                                             , The Federal Reserve Bank of New York suggested in recent research that some borrowers might struggle under the weight of payments and post a “meaningful rise” in delinquencies once payments start again. Mr. Biden referred to that Fed data during his announcement. The Education Department suggested that borrowers would be given a “fresh start” that will automatically eliminate delinquency and defaults and allow them to begin repayment, once it resumes, in good standing.                                                                        , Payments delayed again. President Biden will allow millions of federal student loan borrowers to freeze their payments until Aug. 31, according to an administration official briefed on the matter, the latest extension of a pandemic relief measure that began more than two years ago.                                                                                                                                                                                                                                                                       , The cost of private loans. As the Fed changes its benchmark rate, private student loan borrowers should expect to pay more, as both fixed and variable rate loans are linked to benchmarks that track the federal funds rate.                                                                                                                                                                                                                                                                                                                                    , Companies step in. As employers seek to hire and keep workers in a challenging job market, more are  treating student debt repayments as a job benefit: A recent study found that about 17 percent of large employers offered some form of student debt assistance.                                                                                                                                                                                                                                                                                              , A possible source of relief. The Public Service Loan Forgiveness program has been a quagmire since it started in 2007. But recent updates by the Department of Education could alleviate student loan debt for thousands of borrowers.                                                                                                                                                                                                                                                                                                                           , “We are still recovering from the pandemic and the unprecedented economic disruption it caused,” Mr. Biden said.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The move could also blunt the pain of an inflationary moment for some households. Voters are deeply unhappy as inflation eats away at paychecks and cancels out pay gains for many workers. A recent Gallup poll showed that concerns about inflation have surged to their highest level since the 1980s, and though they are lower among Democrats than among Republicans, they are rising across partisan lines.                                                                                                                                               , Some proponents of extending the moratorium cited inflation as part of their reasoning.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , “This is an important step to ensure that working families’ expenses aren’t going up as we work to fight inflation and corporate greed,” Representative Pramila Jayapal, Democrat of Washington, wrote on Twitter.                                                                                                                                                                                                                                                                                                                                               , But the reality that the move could add to inflation at the margin, and that it comes at a time when the economy is chugging along solidly, prompted critics to argue that it is difficult to make an economic case for the extension.                                                                                                                                                                                                                                                                                                                           , “From an economic perspective, it’s a very bad decision,” said Ben Ritz, the director of the Progressive Policy Institute’s Center for Funding America’s Future. “It’s very expensive, it’s inflationary, it’s regressive. They’re doing it a couple of months at a time, so it’s creating uncertainty for borrowers.”                                                                                                                                                                                                                                           , Unemployment among college graduates, the biggest beneficiaries of student loan payment deferrals, is currently at just 2 percent. For those who have no degree — people who have graduated only from high school — unemployment is at 5.2 percent, roughly matching its prepandemic level.                                                                                                                                                                                                                                                                      , By “regressive,” Mr. Ritz means that student loan deferrals tend to help relatively high-income families. Accounting for the value of an education and adjusting for existing student relief programs, one Brookings Institution analysis found that almost a third of all student debt is owed by the wealthiest 20 percent of households and only 8 percent by the bottom 20 percent.                                                                                                                                                                          , The program was meant to provide relief during the depths of the pandemic, but it has now been extended seven times. Now it will put borrowers in a better financial position to afford houses, ballet lessons and new couches — whatever they want to spend their money on instead of payments — just as the central bank’s interest rate increases try to take spending power out of the economy.                                                                                                                                                              , “It absolutely makes the Fed’s job harder,” Mr. Ritz said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Stacy Cowley contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 02:26:00 </td>
   <td style="text-align:left;"> Wall Street Sell-off Deepens After Fed Minutes Release </td>
   <td style="text-align:left;"> The Dow plunged over 300 points on Wednesday afternoon, and the S&amp;P 500 and the Nasdaq fell 1.5% and  2.7%, respectively, as investors reacted to the Federal Reserve’s hawkish minutes. The minutes showed that the central bank was considering higher rate hikes than its usual 25-basis-point, given a worsening inflation outlook. Officials also agreed that monthly caps of about $95 billion in the balance sheet reduction would likely be appropriate, which is higher than $50 billion a month back in 2017-2019. Investors now wrestled with the twin shocks of aggressive US interest rate hikes, potentially causing a recession and more Western sanctions on Russia, further stoking inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-trade-near-session-lows/story.aspx?guid={1D522DFB-5C08-4821-85BA-7956DB9B41D0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 02:15:43 </td>
   <td style="text-align:left;"> Stocks trade at or near session lows as investors weigh Fed balance-sheet plans - MarketWatch </td>
   <td style="text-align:left;"> Stocks fell back to or near session lows after briefly trimming losses following the release of minutes from the Federal Reserve's March policy meeting Wednesday afternoon. The summary said officials generally settled on shrinking the balance sheet by $95 billion a month after a 3-month phase-in. Officials stressed they made no final decision on winding down the $9 trillion portfolio but said the plan could start in May. The Dow Jones Industrial Average  was down 291 points, or 0.8%, at 34,351, while the S&amp;P 500  was down 1.4% at 4,463 and the tech-heavy Nasdaq Composite sank 2.5% to 13,853., U.S. stocks finish lower for a second day on Wednesday, after Federal Reserve minutes detail plans to  shrink its nearly $9 trillion balance sheet at the fastest clip ever.                                                                                                                                                                                                                                                                                                                                                                                                                                          , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-04-07 02:09:00 </td>
   <td style="text-align:left;"> Brent Crude Briefly Falls Below $100 </td>
   <td style="text-align:left;"> Brent crude futures tumbled below $100 per barrel on Wednesday, having topped the $108 mark earlier this session as investors reacted to news that IEA would release 120 million barrels of oil to cool prices. Pressuring prices further were expectations of weaker demand following a build in US crude stockpiles and an extended lockdown in Shanghai. Still, the prospect of fresh sanctions on Russia raised supply concerns. The US and its allies prepared new sanctions on Moscow over civilian killings in northern Ukraine, with the EU proposing to ban Russian coal and prevent Russian ships from entering EU ports. Britain also urged G7 and NATO countries to agree to a timetable to phase out oil and gas imports from Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/balance-sheet-shrink-95-billion/story.aspx?guid={376623D3-A1A3-4D01-B376-BA130C560A7A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 02:08:54 </td>
   <td style="text-align:left;"> Balance sheet to shrink by $95 billion per month as many on Fed see 50 basis point hikes coming, minutes show - MarketWatch </td>
   <td style="text-align:left;"> Minutes of the Fed's March meeting said officials generally settled on shrinking the balance sheet by $95 billion per month after a 3-month phase-in. Officials stressed they made no final decision on winding down the $9 trillion portfolio but said the plan could start in May. The minutes revealed that many Fed officials signaled they would support 50 basis point rate hikes at upcoming meetings if inflation remains high or gets even worse. "Many" Fed officials wanted a 50-basis point hike in March, but agreed to a smaller 25-basis point increase due to the conflict in Ukraine., Executives from major oil companies defend themselves on Wednesday at a House hearing titled "Gouged at the Gas Station: Big Oil and America's Pain at the Pump."                                                                                                                                                                                                                                                                                                                                                                                                                                     , Greg Robb is a senior reporter for MarketWatch in Washington. Follow him on Twitter @grobb2000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-prices-settle-lower-move/story.aspx?guid={3BE4DDC7-2958-43C9-9453-68585094F095}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 02:07:35 </td>
   <td style="text-align:left;"> Gold prices settle lower, move up in electronic trading after Fed minutes - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled lower on Wednesday, then moved up in electronic trading following the release of minutes from the Federal Reserve's March meeting. The minutes, released after the settlement for gold futures, suggested that the central bank may start its balance sheet reduction as soon as May and that "many" Fed officials wanted a 50 basis point interest-rate hike in March, but accepted a smaller 25 basis point hike because of the Ukraine war. June gold 
        GCM22,
        +0.23%
       was at $1,930.70 an ounce in electronic trading following the release of the Fed minutes. The contract had declined by $4.40, or 0.2%, to settle at $1,923.10 an ounce on Comex., "As towering skyscrapers rose in Moscow atop a pile of oil cash, Putin’s government became more backward-looking and more isolated," Lukas I. Alpert writes in a commentary piece.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/interest-rate </td>
   <td style="text-align:left;"> 2022-04-07 02:07:00 </td>
   <td style="text-align:left;"> Fed Could Have Tighten Monetary Policy Faster </td>
   <td style="text-align:left;"> Many Fed officials would have preferred a 50bps increase in the feds funds rate, instead of a 25bps hike, minutes from the last March FOMC meeting showed. Regarding the balance sheet reduction, officials agreed that monthly caps of about $60 billion for Treasury securities and $35 billion for mortgage-backed securities would likely be appropriate, with the amounts phased in over a period of three months or modestly longer. That is higher than $50 billion a month trim the Fed made back in 2017-2019. Fed officials also considered it would be appropriate to move the stance of monetary policy toward a neutral posture expeditiously and that a move to tighter policy could be warranted, depending on economic and financial developments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/06/fed-minutes-march-2022-meetings-.html </td>
   <td style="text-align:left;"> 2022-04-07 02:00:02 </td>
   <td style="text-align:left;"> Fed officials plan to shrink the balance sheet by $95 billion a month, meeting minutes indicate </td>
   <td style="text-align:left;"> , Federal Reserve officials discussed how they want to reduce their trillions in bond holdings at the March meeting, with a consensus around $95 billion a month, minutes released Wednesday showed.                                                                                                                                                                                          , Officials "generally agreed" that a maximum of $60 billion in Treasurys and $35 billion in mortgage-backed securities would be allowed to roll off, phased in over three months and likely starting in May. That total would be about double the rate of the last effort, from 2017-19, and represent part of a historic switch from ultra-easy monetary policy.                            , In addition to the balance sheet talk, officials also discussed the pace of interest rate hikes ahead, with members leaning toward more aggressive moves.                                                                                                                                                                                                                                   , At the March 15-16 meeting, the Fed approved its first interest rate increase in more than three years. The 25 basis point rise— a quarter percentage point — lifted the benchmark short-term borrowing rate from the near-zero level where it had been since March 2020.                                                                                                                   , The minutes, though, pointed to potential rate hikes of 50 basis points at upcoming meetings, a level consistent with market pricing for the May vote. In fact, there was considerable sentiment to go higher last month. Uncertainty over the war in Ukraine deterred some officials from going with a 50 basis point move in March.                                                       , "Many participants noted that one or more 50 basis point increases in the target range could be appropriate at future meetings, particularly if inflation pressures remained elevated or intensified," the minutes said.                                                                                                                                                                    , Stocks fell following the Fed release while government bond yields held higher. However, the market came well off its lows as traders adjusted to the central bank's new posture.                                                                                                                                                                                                           , The minutes were "a warning to anyone who thinks that the Fed is going to be more dovish in their fight against inflation," said Quincy Krosby, chief equity strategist at LPL Financial. "Their message is, 'You're wrong.'"                                                                                                                                                               , Indeed, policymakers in recent days have grown increasingly strident in their views about taming inflation.                                                                                                                                                                                                                                                                                 , Governor Lael Brainard said Tuesday that bringing prices down will require a combination of steady hikes plus aggressive balance sheet reduction. Markets expect the Fed to increase rates a total of 250 basis points this year. The minutes noted, that, "All participants indicated their strong commitment and determination to take the measures necessary to restore price stability.", Krosby said the policymakers' position thus shouldn't have come as much of a surprise.                                                                                                                                                                                                                                                                                                      , "The Fed orchestrated a concerted effort to warn the market, telling the market in no uncertain terms that this is serious, this is paramount, we are going to fight inflation," she said. "What they have on their side is a still-healthy jobs market, and that's important. What you don't want is the Fed making a policy error."                                                       , Tom Lee just made a bunch of new stock recommendations to play this year's tough market                                                                                                                                                                                                                                                                                                     , Elon Musk's Twitter investment sparks a rush of retail investors into the stock                                                                                                                                                                                                                                                                                                             , When Wall Street’s 'fear gauge' goes up, it might be time to buy stocks, Josh Brown says                                                                                                                                                                                                                                                                                                    , Credit Suisse picks Chinese 'little giant' stocks, says the start-ups are a growing force                                                                                                                                                                                                                                                                                                   , The central bank's relative hawkishness extended to the balance sheet talk. Some members wanted no caps on the amount of the monthly runoff, while others said they were good with "relatively high" limits.                                                                                                                                                                                , The balance sheet rundown will see the Fed allowing a capped level of proceeds from maturing securities to roll off each month while reinvesting the rest. Holdings of shorter-term Treasury bills would be targeted as they are "highly valued as safe and liquid assets by the private sector."                                                                                           , While officials did not make any formal votes, the minutes indicated that members agreed the process could start in May.                                                                                                                                                                                                                                                                    , Whether the runoff actually will hit $95 billion, however, is still in question. MBS demand is muted now with refinancing activity low and mortgage rates rising past 5% for a 30-year loan. Officials acknowledged that passive runoff of mortgages likely may not be sufficient, with outright sales to be considered "after balance sheet runoff was well under way."                    , Also at the meeting, Fed officials sharply raised their inflation outlook and lowered their economic growth expectations. Surging inflation is the driving factor behind the central bank tightening.                                                                                                                                                                                       , Markets were looking to the minutes release for details about where monetary policy heads from here. Specifically, Fed Chairman Jerome Powell said at his post-meeting news conference that minutes would provide details on the thinking about balance sheet reduction.                                                                                                                    , The Fed expanded its holdings to about $9 trillion, or more than double, during monthly bond purchases in the wake of the pandemic crisis. Those purchases ended only a month ago, despite evidence of roaring inflation higher than anything the U.S. had seen since the early 1980s, a surge that then-Fed Chairman Paul Volcker quelled by dragging the economy into a recession.        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/fed-march-meeting-minutes </td>
   <td style="text-align:left;"> 2022-04-07 01:58:28 </td>
   <td style="text-align:left;"> Fed signals half-point interest rate hike 'appropriate' at future meetings </td>
   <td style="text-align:left;"> Former Kansas City Fed President Thomas Hoenig argues a recession in the U.S. could potentially happen 'sooner than next year' amid the central bank's tightening measures.                                                                                                                                                                      , The Federal Reserve signaled that it could raise interest rates by 50-basis points in coming meetings and start to reduce its massive balance sheet at a pace of $95 billion a month as it seeks to cool the hottest inflation in four decades.                                                                                                  , Minutes from the U.S. central bank's March 15-16 meeting released on Wednesday show that "many" policymakers would have preferred a larger rate increase last month but determined that a more modest quarter-point hike would be appropriate "in light of greater near-term uncertainty associated with Russia’s invasion of Ukraine."          , FED RAISES INTEREST RATES FOR FIRST TIME IN 3 YEARS, PROJECTS 6 MORE HIKES AS INFLATION SURGES                                                                                                                                                                                                                                                   , "Many participants noted that one or more [half-percentage-point] increases in the target range could be appropriate at future meetings, particularly if inflation pressures remained elevated or intensified," the minutes said.                                                                                                                , Policymakers also proposed shrinking the Fed's nearly $9 trillion balance sheet at a maximum monthly pace of $60 billion in Treasurys and $35 billion in mortgage-backed securities. By comparison, the Fed trimmed its balance sheet at a rate of $50 billion a month from 2017 to 2019.                                                        , Federal Reserve Chair Jerome Powell pauses during a news conference in Washington on Jan. 29, 2020. (AP Photo/Manuel Balce Ceneta, File / AP Newsroom)                                                                                                                                                                                           , "Participants generally agreed that monthly caps of about $60 billion for Treasury securities and about $35 billion for agency MBS would likely be appropriate," the meeting minutes said. "Participants also generally agreed that the caps could be phased in over a period of three months or modestly longer if market conditions warrant."  , Officials are expected to approve the balance-sheet reduction – and possibly raise rates by 50-basis points – at their next gathering on May 3-4.                                                                                                                                                                                                , Fed policymakers voted during their two-day meeting to raise rates by 25-basis points, bringing to an end the ultra-easy monetary policy put in place two years ago to prop up the economy through the COVID-19 pandemic. They also projected at least six more, similarly sized increases over the course of this year.                         , But in the weeks since then, policymakers – including Chairman Jerome Powell – have floated the possibility of a more aggressive trajectory amid concerns that the central bank waited too long to begin tightening policy.                                                                                                                      , A man wearing a mask walks past the U.S. Federal Reserve building in Washington on April 29, 2020. (Xinhua/Liu Jie via Getty Images / Getty Images)                                                                                                                                                                                              , "If we conclude that it is appropriate to move more aggressively by raising the federal funds rate by more than 25 basis points at a meeting or meetings, we will do so," Powell said two weeks ago. "And if we determine that we need to tighten beyond common measures of neutral and into a more restrictive stance, we will do that as well.", Traders are now pricing in more than a 70% chance of a hefty half-point rate jump when policymakers meet next month, instead of a more modest quarter-point increase, according to the CME's FedWatch tool.                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                      , It would mark the first time since 2000 that the U.S. central bank raised the federal funds rate by 50 basis points.                                                                                                                                                                                                                             , "The minutes did indicate that a hawkish Fed is clearly ready to lift rates by 50 basis points in one or more meeting going forward as the central bank prepares to shift into a higher gear in its policy normalization process," RSM chief economist Joseph Brusuelas said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-61013908?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-07 01:40:00 </td>
   <td style="text-align:left;"> Oil bosses vow to boost output and deny profiteering </td>
   <td style="text-align:left;"> The bosses of some of the world's biggest energy firms vowed to increase production this year as they defended themselves from accusations of profiteering from the war in Ukraine.                                                    , Chiefs at ExxonMobil, Chevron and others said in Washington that they had little power over oil prices, which have soared after Russia's invasion.                                                                                     , Prices remain more than 15% higher than they were at the end of January.                                                                                                                                                               , The increase has raised energy costs for households around the world.                                                                                                                                                                  , In the US, where mid-term elections will be held in November, it has also become a major political issue, weighing on President Biden's support.                                                                                       , The US and other members of the International Energy Agency (IEA) have repeatedly tapped reserves to alleviate the crisis.                                                                                                             , Just last week, the US pledged to release 180 million barrels of oil over the next six months, while the IEA announced on Wednesday that other members would release a further 60 million barrels from storage.                        , But energy executives at the congressional hearing warned that there was "no quick fix" to the problem.                                                                                                                                , They said their investments, many already in the works, will raise output this year, but warned that staffing and supply issues stemming from the pandemic meant it is taking longer to start new production.                          , "What can be done to ensure vital energy products remain available and affordable?" asked Darren Woods, chief executive of ExxonMobil.                                                                                                 , "While there is no quick fix, the answer in the near-term, until there are more widely available and affordable alternatives, is straightforward. We need to increase the supply of oil and natural gas."                              , Energy prices were already increasing before Russia's invasion, as firms struggled to respond to disruption from the pandemic, which prompted a dramatic collapse in demand in 2020, followed by a faster-than-expected rebound.       , Following Russia's invasion, Western allies hit the country with severe sanctions, disrupting oil markets and raising concerns about their supplies.                                                                                   , The country is the world's second-largest exporter of crude oil, accounting for about 10% of global output.                                                                                                                            , Oil prices are up roughly 70% from a year ago, accelerating in recent months.                                                                                                                                                          , New Yorker Doreen Aniakor says the dramatic rise in petrol prices means her car now costs $100 (£76.50) to fill. In response, she has stopped filling her tank in one go and started cutting off the engine at red lights to save fuel., The 36-year-old, who works as a dental assistant and for hospitals, also recently picked up a fourth part-time job. She now delivers groceries for Instacart in an effort to cover the extra costs.                                    , "In this day and age, you just do what you got to do," she said, "I have to figure out sometimes how to eat... It's ridiculous."                                                                                                       , At the hearing, Democrats said oil firms were "lining their own pockets" as petrol prices have not fallen as rapidly as oil, noting the rise in profits since 2022.                                                                    , "At a time of record profits, Big Oil is refusing to increase production to provide the American people some much needed relief at the gas pump," said Rep. Frank Pallone, a Democrat from New Jersey.                                 , Democrats pressed energy firms to halt stock buybacks and said the energy crisis should spur a faster turn to greener energy sources.                                                                                                  , Republicans blamed policies backed by President Joe Biden for the higher costs, accusing him of an "assault" on the US energy industry with actions such as halting oil and gas leases on public lands.                                , "High gas prices are a feature of President Biden's policies, not a bug," said Rep Cathy Morris, a Republican from Washington. "Why? They want to usher in a green revolution."                                                        , After questioning by Republicans, some executives said in their testimony that Mr Biden's push for green energy alternatives was chilling investment.                                                                                  , But some executives said over the long-term, investing in green energy was a key way to stopping these kinds of energy shocks in the future.                                                                                           , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                        , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                 , Why does it impact almost every system in the human body?                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-transports-tumbles-again-toward/story.aspx?guid={23B81626-6A0A-4708-9A5D-115B358749D8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-07 01:26:55 </td>
   <td style="text-align:left;"> Dow transports tumbles again toward longest losing streak in more than 2 years - MarketWatch </td>
   <td style="text-align:left;"> The Dow Jones Transportation Average  dove 568 points, or 3.8%, in afternoon trading Wednesday, putting then on track for the sixth-straight loss and a six-month low. A six-day losing streak would be the longest since the six-day streak that ended Feb. 28, 2020. The Dow transports have plunged 13.3% over the past six sessions, the worst six-day performance plummeted 15.6% during the six-day stretch that ended March 23, 2020. In comparison, the Dow Jones Industrial Average , which slumped 231 points, or 0.7%, on Tuesday, has slipped just 2.5% over the past six days. Within the Dow transports, all 20 components are losing...
    , Here were go — Deutsche Bank becomes the first of the major Wall Street banks to call for a recession. At least it isn't this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/06/stocks-making-the-biggest-moves-midday-jetblue-eli-lilly-occidental-petroleum-and-more.html </td>
   <td style="text-align:left;"> 2022-04-07 01:12:34 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: JetBlue, Eli Lilly, Occidental Petroleum and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                         , Check out the companies making headlines in midday trading Wednesday.                                                                                                                                                                                                                                                   , JetBlue — Shares of JetBlue fell another 8.7% on Wednesday, as investors weighed the airline's $3.6 billion cash offer to take over rival Spirit Airlines. The move also comes after Raymond James downgraded JetBlue to market perform from outperform. Spirit Airlines shares fell more than 2%.                      , Eli Lilly — The pharmaceutical stock gained 4.6% after Morgan Stanley named Eli Lilly a top pick. The investment firm said Eli Lilly had the "most robust new product cycle" outlook in the industry.                                                                                                                   , Tilray — Tilray rose 3.1% after reporting an unexpected profit in its latest quarter. Tilray also announced a deal with supermarket chain Whole Foods, which will sell the hemp powders produced by the company's Manitoba Harvest subsidiary.                                                                          , Rivian — Shares of the electric vehicle company fell 5% after Rivian said it was on pace to achieve its previously stated production target of 25,000 electric vehicles this year.                                                                                                                                      , Occidental Petroleum — The energy producer's shares added 0.7% after Stifel initiated coverage with a buy rating. Stifel said Occidental remains "attractively valued" even after the stock is the best-performing name in the S&amp;P 500 this year.                                                                       , Intel — Intel's stock fell 1.2% after the chip maker announced it suspended business operations in Russia. Last month, Intel halted semiconductor shipments to customers in Russia and Belarus.                                                                                                                         , Twitter — Shares of the social media company fell slightly after rising for three straight days. The stock surged earlier this week, as investors grew optimistic about Elon Musk's big investment in the company. Musk will join its board of directors, and he teased "significant improvements" in the coming months., — CNBC's Jesse Pound and Yun Li contributed reporting.                                                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/paraguay/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-07 01:08:18 </td>
   <td style="text-align:left;"> Paraguay Inflation Rate Quickens to Near 11-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Paraguay accelerated for the third straight month to 10.1% in March of 2022, from 9.3% in the prior month. It was the highest reading since May of 2011, mainly on account of soaring prices of transportation (18.2% vs 17.2% in February) and food &amp; non-alcoholic beverages (17.5% vs 15.7%). On a monthly basis, consumer prices were up 0.8%, slowing from a 1.4% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 00:44:00 </td>
   <td style="text-align:left;"> South African Stocks Down for 3rd Day </td>
   <td style="text-align:left;"> The JSE FTSE All Share index fell 1.2% to close at 74,359 on Wednesday, extending losses for a third straight session, along with its global peers, as hawkish comments by US Federal Reserve officials weighed on sentiment. At the same time, investors worried over the impact of tougher sanctions against Russia on the global economy. Losses were led by heavyweights tech stocks, Richemont, Mondi and GrowthPoint. Also, commodity-linked stocks like Northam Platinum Limited and Anglogold Ashanti dragged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 00:22:00 </td>
   <td style="text-align:left;"> French Stocks Fall Sharply </td>
   <td style="text-align:left;"> The CAC 40 plunged 2.2% to close at 6,499 on Wednesday, its biggest daily decline since March 10th, extending losses for a second day, amid nervousness around upcoming presidential elections and fears of aggressive rate hikes ahead of the release of Fed minutes. At the same time, expectations of new sanctions against Russia following its alleged war crimes in Ukraine, spooked investors. On the corporate front, stocks with significant exposure to the French economy such as BNP Paribas and Societe Generale extended declines. Tech stocks are also impacted, with STMicroelectronics and Worldline falling 2.8% and 3.5%, respectively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/06/europe/ukraine-russia-war-technology-intl-cmd/index.html </td>
   <td style="text-align:left;"> 2022-04-07 00:11:25 </td>
   <td style="text-align:left;"> Analysis: Drones, phones and satellite technology are exposing the truth about Russia's war in Ukraine in near real-time
 - CNN </td>
   <td style="text-align:left;"> (CNN)Russia's lies may be catching up with it faster than it ever imagined.                                                                                                                                                                                                                                                                                                                                                                                    , The war in Ukraine is defying President Vladimir Putin's expectations at every turn, not only with Russia's failure to capture Kyiv as planned but with the war crimes his soldiers are alleged to have committed in Bucha, a city close the capital, exposed for the world to see.                                                                                                                                                                             , Throughout history, wars have been won by forces turning new technologies to their advantage. The 1415 victory of English King Henry V over the French at the Battle of Agincourt came courtesy of his archers and their newly developed longbows, raining arrows over a range the French could not match.                                                                                                                                                      , The war in Ukraine may see another historic first, with technology cutting through the fog of war, exposing the aggressors' lies and accelerating efforts to bring about their defeat.                                                                                                                                                                                                                                                                          , Satellite images of murdered civilians that match videos, recorded weeks later, of bodies at the roadside are providing compelling evidence of Russian war crimes, convincing Western leaders to ramp up sanctions on Russia and accelerate weapons supplies for Ukraine.                                                                                                                                                                                       , How this will affect the final outcome of the war is unclear. But what is evident at a time when Ukraine is urgently seeking any additional leverage as Russian forces regroup for a new offensive, is that Russia's actions in Bucha are strengthening Ukraine's hand.                                                                                                                                                                                         , While battlefield satellite imagery has been available to governments for decades and was instrumental in pinpointing war crimes during the Bosnian civil war in the 1990s -- notably locating a mass grave of many of the 7,000 Bosnian Muslims slaughtered in the town of Srebrenica in 1995 -- it has never been so immediately available in the public domain as now.                                                                                       , Putin and his battlefield commanders appear not to care or not to have grasped the fact that orders and actions now leave an indelible record beyond their control that could come back to haunt them.                                                                                                                                                                                                                                                          , They will be aware that in many past conflicts -- even as recent as the Syrian civil war -- leaders like Bashar al Assad escaped conviction and have even been rehabilitated, despite vast troves of incriminating documents spirited from government offices and police stations.                                                                                                                                                                              , But this is not the only lesson to which Putin should pay attention. Following the bloody breakup of Yugoslavia and the Bosnian civil war, the war crimes tribunal in the Hague used political and military leaders' own words to help convict them.                                                                                                                                                                                                            , When the International Criminal Tribunal for the former Yugoslavia (ICTY) put Bosnian Serb President Radovan Karadzic on trial, it had video of him looking over Sarajevo, condemning the civilians below to artillery and mortar fire.                                                                                                                                                                                                                         , His military partner in war crimes there, General Ratko Mladic, also saw his words come back to help convict him, as video showed him on the outskirts of Srebrenica directing the filtering of civilians, many of whom would shortly be slaughtered by his soldiers, following his orders.                                                                                                                                                                     , That type of link may be harder to pin on Putin, but his 20-page thesis published last summer on why Ukraine is not a country, and his TV comments on why Russia should invade, will, if previous war crime courts are a precedent, count against him as author and director of the war.                                                                                                                                                                        , If Putin were to come to trial, his unravelling may turn out to have begun with his inability to understand his army's weaknesses and Ukraine's strengths. Failure to fulfil his first major objective, the capture of Kyiv, forced his troops to retreat, leaving their tide of terror exposed.                                                                                                                                                                , They did what they have done so many times before, in Syria, in Chechnya, in Georgia:  committed awful abuses. And Putin and his officials did what they have done so many time before: lied to cover their crimes.                                                                                                                                                                                                                                             , Russian defense officials claimed photos and videos that emerged on April 2, showing murdered civilians -- shot in the head, some with their hands and legs bound -- were fake, saying their troops left before the killings occurred. "The troops left the city on March 30," the defense ministry said in a statement. "Where was the footage for four days? Their absence only confirms the fake."                                                           , They were very clear about the date. Foreign Minister Sergey Lavrov, one of Putin's most seasoned spin masters, doubled down on the clumsy cover-up, insisting "Russian forces left the Bucha town area as early as the 30th of March."                                                                                                                                                                                                                         , But publicly available satellite images from space-tech company Maxar, taken March 18 while Russian troops were in control, showed the civilians lying dead at the road side in exactly the same locations as Ukrainian forces discovered them when they re-entered the town in early April. And drone video shot before March 10 showed a cyclist being shot and killed by Russian troops. Ukrainian forces found his body weeks later, exactly where he fell. , In the months prior to Russia's invasion and the days since Maxar's images appeared, tracking Russian forces and their destruction, the public's understanding of the battlefield has been revolutionized. Coupled with the near-ubiquitous use of smartphone cameras, geolocation technology and sophisticated drones, Putin faces the possible reckoning he escaped in previous conflicts.                                                                    , Ukrainian President Volodymyr Zelensky wants more cameras, and wider access, to let the public see for themselves: "This is what we are interested in, maximum access for journalists, maximum cooperation with international institutions, enrolment of the International Criminal Court, complete truth and full accountability," he said in a video address on Monday.                                                                                       , Ukraine's enigmatic leader has realized it's not just high-tech, tank-busting weapons like Javelins and NLAWs, or surface-to-air missiles like Stingers and Starstreaks, that could turn the tide in the war. It's truth, and the tools -- satellites, drones and smartphones -- to deliver it.                                                                                                                                                                 , Unparalleled in any modern war, technology could hand the underdog this surprising advantage, undermining the lies of an oversized aggressor.  Zelensky was at pains for the United Nations to understand this when he spoke to them Tuesday: "It is 2022 now. We have conclusive evidence. There are satellite images. And we can conduct full and transparent investigations."                                                                                , Like Henry V in 1415, Zelensky knows an advantage when he sees it. While satellite imagery may not be as game-changing as a six-foot yew branch and a length of hemp string, if he can use it cleverly, he may force Putin to talks much sooner than the Russian President would like.                                                                                                                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 00:10:45 </td>
   <td style="text-align:left;"> Italian Stocks Extend Decline </td>
   <td style="text-align:left;"> The FTSE MIB index closed 2.1% lower at 24,447 on Wednesday, pressured by all sectors as investors anticipated the extent of new European sanctions on Russia while weighing on hawkish stances from the Federal Reserve. After announcing plans of banning coal imports from Russia yesterday, the EU discussed further blows on Moscow during the session. The auto sector led the losses in Milan, driven by a 5.4% decline for Pirelli and a 4.5% loss for Stellantis. Saipem fell 2.3% despite news that the oilfield service provider signed a contract worth $400 million for offshore drilling in Africa and the Middle East. Growth jitters and prospects of tighter monetary policy by major central banks hit the luxury consumer goods sector, with a 4.7% slump for Moncler and 3% loss for Ferrari. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 00:09:00 </td>
   <td style="text-align:left;"> Madrid Stocks Slump on Wednesday </td>
   <td style="text-align:left;"> The Ibex 35 fell 1.6% to close at 8,482 on Wednesday, after three straight sessions of gains, tracking its European peers, amid fears of aggressive rate hikes by the US Federal Reserve and concerns over further sanctions on Russia. Now, traders cautiously await the release of Fed minutes later in the day, which should offer some additional insight into the central bank's plans on monetary policy. On the corporate front, the worst performers were Siemens Gamesa, banks and tourism-related companies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-04-07 00:00:00 </td>
   <td style="text-align:left;"> UK Stocks Snap 3-Day Winning Streak </td>
   <td style="text-align:left;"> The FTSE 100 was down 0.3% to close at 7,588 on Wednesday, following three consecutive sessions of gains, mirroring global markets, on the back of hawkish Fed comments and prospects of more sanctions on Russia from Western countries. Among single stocks, Intermediate Capital Group, Smurfit Kappa Group, Scottish Mortage Investment and JD Sports Fashion led the losses. Meanwhile, Imperial Brands was among the biggest gainers after saying it was on track to deliver full-year results in line with revised guidance issued on March 15th. On the economic data front, a PMI survey showed the UK construction sector logged another robust growth in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-04-06 23:59:00 </td>
   <td style="text-align:left;"> Russian Stocks Extend Decline </td>
   <td style="text-align:left;"> The MOEX Russia Index closed 1.9% lower at 2,611 on Wednesday, as investors weighed on fresh sanctions from the US while awaiting on measures by the EU in retaliation to reports of civilian killings in Ukraine. Sberbank shares closed 8% lower after it was the prime target of US sanctions, which also included Alfabank and President Putin’s adult daughters. VTB shares also closed lower, declining 5%. The EU planned to ban the import of Russian coal, while policymakers discussed the extent of sanctions on other forms of Russian energy. Meanwhile, the Russian treasury edged closer to a default after sending payment for a dollar-denominated Eurobond in rubles, to which foreign banks refused to execute. The US treasury halted Russia from its dollar reserves in US banks, disabling Moscow from paying $552 million in principle and $84 million in coupons of debt. The payments were due to bond holders by April 4th, starting the 30-day grace period before default. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60993641?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-06 23:54:23 </td>
   <td style="text-align:left;"> More Kinder Surprise egg products recalled over salmonella links </td>
   <td style="text-align:left;"> More Kinder Surprise chocolate egg products have been recalled over a link to salmonella cases in the UK.                                                                                                                             , The Food Standards Agency (FSA) had advised people not to eat 20g or three-pack eggs with best before dates between 11 July and 7 October 2022.                                                                                       , Kinder Easter egg hunt kits (150g), Kinder Mini eggs (75g), Kinder schokobons (200g) and the 100g Kinder Surprise have now been recalled too.                                                                                         , All sweets affected had been made in the same Belgian factory.                                                                                                                                                                        , Ferrero, which makes Kinder chocolates, said that it had taken the "precautionary decision" to voluntarily extend the recall to these products in the UK and Ireland with best before dates between 20 April 2022 and 21 August 2022. , The chocolate-maker said none of its Kinder products released for sale had tested positive for salmonella, but that it takes the matter "extremely seriously".                                                                        , They added that they were aware of Easter coming up, which usually sees a sales boost for Kinder Surprise eggs.                                                                                                                       , "The company takes food safety extremely seriously and we sincerely apologise for this matter. Our continued commitment to consumer care has driven our decision today to extend the voluntary recall," the spokesperson said.        , No other Ferrero or Kinder products are believed to have been affected.                                                                                                                                                               , The FSA said that if customers have chocolates from the batches described, they should not eat them. They can also contact Ferrero for a full refund.                                                                                 , The products will be taken off the shelves and notices put up in shops to warn consumers.                                                                                                                                             , It comes after about 63 people in the UK, mostly young children, became infected with salmonella in an outbreak linked to the Kinder Surprise treats.                                                                                 , On Monday, the FSA said no deaths had been reported in the UK but most cases involved children aged five and under.                                                                                                                   , Investigations so far have been led by the UK Health Security Agency, Public Health Scotland, Public Health Wales and Public Health Agency Northern Ireland.                                                                          , Europe's health agency said on Wednesday it was also looking into dozens of suspected cases of salmonella linked with eating chocolate in at least nine countries including the UK, Germany, France and Belgium.                      , It did not mention Ferrero or any other confectioner in a statement, but warned that the reported cases were mostly among children under 10.                                                                                          , Dr Lesley Larkin, of the UK Heath Security Agency, previously said that symptoms of salmonellosis, which can include diarrhoea, stomach cramps, nausea, vomiting and fever, "typically resolve themselves within a few days".         , She said symptoms could be more severe, especially in young children and those with weakened immune systems and anybody with concerns should contact their GP or call NHS 111.                                                        , Salmonella can be spread from person to person, so Dr Larkin advised anyone with symptoms to wash their hands thoroughly and avoid handling other people's food.                                                                      , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                       , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                , Why does it impact almost every system in the human body?                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/democrats-republicans-house-congress-biden-oil-prices-gas-hearing </td>
   <td style="text-align:left;"> 2022-04-06 23:37:58 </td>
   <td style="text-align:left;"> Democrats, Republicans spar with oil executives on who's to blame for high gas prices </td>
   <td style="text-align:left;"> The House Energy and Commerce Subcommittee holds a hearing with oil executives as Americans deal with record gas prices.                                                                                                                                                                                                                                                                                                                                        , House Republicans and Democrats interrupted and talked over a group of energy executives in a testy hearing Wednesday over who is to blame for high gas prices.                                                                                                                                                                                                                                                                                                 , House Energy and Commerce Oversight and Investigations Subcommittee Chair Diana DeGette, D-Colo., started the questioning off quizzing the executives on why they think gas prices are high. She insisted that the executives give yes or no answers on whether the reason prices are high is because of low supply – and interrupted them when they insisted the answer is more complex.                                                                       , "Madam chair, fuel prices are impacted by a number of factors," Chevron Corp. CEO Michael Wirth said.                                                                                                                                                                                                                                                                                                                                                           , HOUSE HEARING WITH OIL EXECUTIVES SETS UP PARTISAN CLASH OVER GAS PRICES                                                                                                                                                                                                                                                                                                                                                                                        , "So you don't agree that crude oil prices are high because there's less supply?" DeGette said, interrupting Wirth.                                                                                                                                                                                                                                                                                                                                              , Wirth said crude oil prices are high because of worries about potential future supply disruptions.                                                                                                                                                                                                                                                                                                                                                              , DeGette interrupted him again: "OK, I'm sorry I don't have time."                                                                                                                                                                                                                                                                                                                                                                                               , DeGette continued the confrontational exchange with the executives, including asking BP America Chairman David Lawler about a lack of correlation between crude oil prices and gas prices. Lawler explained that a "complex set of factors" impacts the price of gas, including supply risk, which affects all refined energy products.                                                                                                                         , Ranking Member H. Morgan Griffith, R-Va., also interrupted the executives in some confrontational questioning. He said they were being too cautious in their answers about whether rhetoric from the Biden administration is reducing their investment in energy production.                                                                                                                                                                                    , REP. JEFFRIES SAYS OIL  EXECS MUST SHOW ‘PATRIOTISM’ AND CUT PRICES, AS GOP SAYS DEMS ‘OWN THIS ENERGY CRISIS’                                                                                                                                                                                                                                                                                                                                                  , "So, apparently everybody wants to get in the weeds and hide behind words," Griffith said. "The president says he wants to make sure that we do not lower the cost of production. Is that going to make you produce more or less? Mr. Woods, more or less?"                                                                                                                                                                                                     , Rep. Diana DeGette asks questions during a House Energy and Commerce Subcommittee hearing in Washington, April 26, 2018. (Reuters/Brian Snyder / Reuters Photos)                                                                                                                                                                                                                                                                                                , "I think the government has a role in encouraging investment and creating a positive investment climate," Exxon Mobil Corp. CEO Darren Woods responded.                                                                                                                                                                                                                                                                                                         , "And when we create a negative climate you produce less, isn't that true. Yes or no?" Griffith shot back.                                                                                                                                                                                                                                                                                                                                                       , "There tends to be a chilling effect with negative words," Woods said.                                                                                                                                                                                                                                                                                                                                                                                          , ENERGY INDUSTRY SLAMS BIDEN'S STRATEGIC PETROLEUM RESERVE RELEASE PLAN: ‘NOT A LONG-TERM SOLUTION’                                                                                                                                                                                                                                                                                                                                                              , Griffith also grilled Wirth, asking if he would "weigh in on this and give me a real answer?" Wirth responded that "mixed messages … do not encourage" investment. Griffith responded that Biden isn't sending mixed messages but instead "a clearly anti-fossil fuel message."                                                                                                                                                                                 , Energy and Commerce Committee Chairman Frank Pallone, D-N.J., then asked the executives if they would commit to increasing production, reducing dividends to investors and halting stock buybacks.                                                                                                                                                                                                                                                              , "We are increasing production," Woods said.                                                                                                                                                                                                                                                                                                                                                                                                                     , Rep. H. Morgan Griffith, R-Va., Wednesday slammed President Biden's energy policies in a house hearing (Official portrait)                                                                                                                                                                                                                                                                                                                                      , "Well, I need a yes or no," Pallone responded.                                                                                                                                                                                                                                                                                                                                                                                                                  , "We will increase our production, yes," Woods said.                                                                                                                                                                                                                                                                                                                                                                                                             , "But … that means you're not going to reduce dividends and buybacks," Pallone said. "Well, that's unfortunate because we need you to do that as well."                                                                                                                                                                                                                                                                                                          , ETHANOL MAY BRING DOWN GAS PRICES: SEN. CHUCK GRASSLEY                                                                                                                                                                                                                                                                                                                                                                                                          , Each of the other executives said they would increase production but wouldn't commit to Pallone's buyback and dividend demands.                                                                                                                                                                                                                                                                                                                                 , The executives who testified remotely at the hearing are Lawler, Wirth, Woods, Devon Energy CEO Richard Muncrief, Pioneer Natural Resources CEO Scott Sheffield, and Shell USA president Gretchen Watkins.                                                                                                                                                                                                                                                      , Oil wells outside of Williston, North Dakota, on August 24, 2021. (Tyler Olson/FOX Business / FOXBusiness)                                                                                                                                                                                                                                                                                                                                                      , It came at a time when Americans are paying near-record gas prices, partially as a result of Russia's war on Ukraine, which has roiled global energy markets. Average nationwide gas prices Tuesday were $4.164 per gallon, just below the record of $4.331 set on March 11, according to AAA.                                                                                                                                                                  , Democrats say the gas prices are not only the fault of Russia, but also because energy company executives are busy maximizing their profits at the expense of Americans. Republicans say energy prices have been increasing since even before the Russian war on Ukraine, and put the blame on President Biden.                                                                                                                                                 ,  "It's not just about the shareholders. The American people who we represent provide the industry with more than $30 billion a year in subsidies while the oil and gas companies report record-high profits," DeGette said Wednesday. "This committee is not going to sit back and allow this system, which forces American taxpayers to pay oil companies out of both pockets, first at the pump and then through tax breaks, to continue in its current form.", BIDEN, PELOSI LIMITED OIL SUPPLY BY SHUTTING DOWN PRODUCTION, SAYS REP. STEVE SCALISE                                                                                                                                                                                                                                                                                                                                                                           , "This hearing is a deliberate distraction … today is purely political," Rep. Cathy McMorris Rodgers, R-Wash., also said during the hearing on Wednesday. "President Biden needs cover for his war on American energy that has caused gas prices to skyrocket."                                                                                                                                                                                                  , Rep. Cathy McMorris Rodgers asks questions during hearing on Capitol Hill on April 2, 2019. (Zach Gibson/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                           , Rep. Raul Ruiz, D-Calif., took a different angle than other questioners. He demanded that the energy executives use green energy to lower prices for Americans. He asked Lawler what BP is doing to "move us toward a clean energy future."                                                                                                                                                                                                                     , "What we're doing at BP is we're working flat out. Our refineries are running flat out. We are bringing 140,000 barrels of crude oil to the market this year. And the second half of this year."                                                                                                                                                                                                                                                                , "That doesn't sound too clean to me," Ruiz interrupted. He demanded that Lawler detail green energy efforts for BP.                                                                                                                                                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                     , Lawler said his company is making investments in green power, including "numerous large solar farms" and the installation of charging stations for electric cars.                                                                                                                                                                                                                                                                                               , Rep. Neal Dunn, R-Fla., meanwhile blamed President Biden for "targeting American energy production," and said that's the reason gas prices are high. He argued the U.S. should build its domestic energy industry and asked Sheffield what is blocking production and transportation of American oil and gas. Sheffield said the Keystone XL pipeline, which Biden canceled, would be a major help to the U.S.                                                  , "If Keystone would have been built six, seven years ago, Canadian production would be another million barrels a day going to the Gulf Coast refineries," he said. "That's an example, you have to make long-term decisions to help the industry. But there's not enough oil and gas pipelines, There's not enough LNG plants. We need LNG plants in the Northeast."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/06/business/economy/yellen-russia-sanctions.html </td>
   <td style="text-align:left;"> 2022-04-06 23:35:01 </td>
   <td style="text-align:left;"> Yellen Says Aim Is ‘Maximum Pain’ for Russia Without Hurting U.S. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The Treasury secretary told a House committee that the U.S. would continue finding ways to punish Russia for its invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , By Alan Rappeport and Katie Rogers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , WASHINGTON — Treasury Secretary Janet L. Yellen said on Wednesday that the United States would continue taking steps to cut Russia off from the global financial system in response to its invasion of Ukraine and argued that the sanctions already imposed had taken a severe toll on the Russian economy.                                                                                                                                                                                                                                                                                   , She addressed the House Financial Services Committee as the United States rolled out a new array of sanctions on Russian banks and state-owned enterprises and on the adult children of President Vladimir V. Putin. The White House also announced a ban on Americans making new investments in Russia no matter where those investors are based.                                                                                                                                                                                                                                             , “Our goal from the outset has been to impose maximum pain on Russia, while to the best of our ability shielding the United States and our partners from undue economic harm,” Ms. Yellen told lawmakers.                                                                                                                                                                                                                                                                                                                                                                                       , The measures introduced on Wednesday included “full blocking” sanctions against Sberbank, the largest financial institution in Russia, and Alfa Bank, one of the country’s largest privately owned banks.                                                                                                                                                                                                                                                                                                                                                                                      , Sberbank is the main artery in the Russian financial system and holds over a third of the country’s financial assets. In February, the Treasury announced limited sanctions against Sberbank, but Wednesday’s sanctions, a senior Biden administration official said, will effectively freeze relations between the bank and the U.S. financial system.                                                                                                                                                                                                                                        , The administration also announced sanctions against two adult daughters of Mr. Putin: Katerina Tikhonova and Maria Putina, who has been living under an assumed name, Maria Vorontsova. Others connected to Russian officials with close ties to Mr. Putin will also face sanctions, including the wife and daughter of Russia’s foreign minister, Sergey Lavrov, and members of Russia’s security council, including former Prime Minister Dmitri Medvedev. The official said those people would be effectively cut off from the U.S. banking system and any assets held in the United States., President Biden said on Wednesday that the new sanctions would deal another blow to the Russian economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , “The sense of brutality and inhumanity, left for all the world to see unapologetically,” Mr. Biden said, describing Russia’s actions as war crimes. “Responsible nations have to come together to hold these perpetrators accountable, and together with our allies and our partners we’re going to keep raising the economic costs and ratchet up the pain for Putin and further increase Russia’s economic isolation.”                                                                                                                                                                       , Experts suggested that the latest round of sanctions were unlikely to compel Mr. Putin to change course. Hundreds of American businesses have pulled out of Russia in recent weeks, making new investments unlikely.                                                                                                                                                                                                                                                                                                                                                                           , “The asset freezes on the additional banks aren’t nothing, but this isn’t the most significant tranche we’ve seen to date,” said Daniel Tannebaum, a partner at Oliver Wyman who advises banks on sanctions.                                                                                                                                                                                                                                                                                                                                                                                   , Other American agencies are joining the effort to exert pressure on Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , In a news conference on Wednesday, officials from the Justice Department and the F.B.I. also announced a series of actions and criminal charges against Russians, including the takedown of a Russian marketplace on the dark web and a botnet, or a network of hijacked devices infected with malware, that is controlled by the country’s military intelligence agency.                                                                                                                                                                                                                      , Justice Department officials also celebrated the seizing of the Tango, a superyacht owned by the Russian oligarch Viktor F. Vekselberg, and charged a Russian banker, Konstantin Malofeev, with conspiring to violate U.S. sanctions. Mr. Malofeev is one of Russia’s most influential magnates and among the most prominent conservatives in the country’s Kremlin-allied elite. (The indictment renders his surname as Malofeyev.)                                                                                                                                                           , At the hearing, Ms. Yellen told lawmakers that she believed Russia should be further isolated from the geopolitical system, including being shut out of international gatherings such as the Group of 20 meetings this year, and should be denounced at this month’s meetings of the International Monetary Fund and the World Bank. She added that the United States might not participate in some G20 meetings that are being held in Indonesia this year if Russians attended.                                                                                                              , Ms. Yellen, whose department has been developing many of the punitive economic measures, rebutted criticism that the penalties leveled so far had not been effective, in part because there are some exceptions to allow Russia to sell energy.                                                                                                                                                                                                                                                                                                                                                , Rising concerns. Russia’s invasion on Ukraine has had a ripple effect across the globe, adding to the stock market’s woes. The conflict has already caused​​ dizzying spikes in energy prices and is causing Europe to raise its military spending.                                                                                                                                                                                                                                                                                                                                              , The cost of energy. Oil prices already were the highest since 2014, and they have continued to rise since the invasion.  Russia is the third-largest producer of oil, so more price increases are inevitable.                                                                                                                                                                                                                                                                                                                                                                                  , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders worry that Moscow could cut flows in response to the region’s support of Ukraine.                                                                                                                                                                                                                                                                                                            , Food prices. Russia is the world’s largest supplier of wheat; together, it and Ukraine account for nearly a quarter of total global exports. Countries like Egypt, which relies heavily on Russian wheat imports, are already looking for alternative suppliers.                                                                                                                                                                                                                                                                                                                               , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                                                                                                  , Financial turmoil. Global banks are bracing for the effects of sanctions intended to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                                                                                                           , “Unfortunately, many of our European partners remain heavily dependent on Russian natural gas, as well as oil, and they are committed to making the transition away from that dependence as rapidly as possible,” Ms. Yellen said. The Treasury secretary downplayed the rebound of Russia’s currency, the ruble, which cratered after the sanctions were imposed in February but has since regained its value. Ms. Yellen said that the ruble’s apparent recovery was the result of currency controls that Russia had put in place and that its exchange rate did not reflect its true value. , “The Russian economy is really reeling from the sanctions that we put in place,” Ms. Yellen said, adding, “You shouldn’t really infer anything from the value of the currency.”                                                                                                                                                                                                                                                                                                                                                                                                                , Ms. Yellen argued that Russia’s invasion of Ukraine underscored the need for the United States and other countries to invest in becoming energy independent so that “dictators” did not control the price and availability of global energy supplies. She added that moving away from fossil fuels and toward renewable energy should be a priority.                                                                                                                                                                                                                                           , The Treasury Department has been trying to create sanctions in a way that minimizes the economic blowback on the United States. However, Ms. Yellen acknowledged that inflation, which was already elevated, would now be “escalated.” She pointed to higher prices for energy, food and metals.                                                                                                                                                                                                                                                                                               , “We think it’s a price that’s important to pay to punish Russia for what it’s doing in Ukraine,” Ms. Yellen said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , As the crisis in Ukraine worsens, the United States and Europe have come under increasing pressure to enact a broader ban on Russian energy purchases. Ms. Yellen warned that doing so could have painful consequences on the United States and its allies.                                                                                                                                                                                                                                                                                                                                    , “We’re likely to see skyrocketing prices, if we did put a complete ban on oil,” Ms. Yellen said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The Treasury secretary acknowledged that inflation, which has become a political problem for Mr. Biden and his party ahead of the November elections, has persisted longer than the White House anticipated. She pointed to pandemic-related supply problems, including shortages of semiconductors that are limiting supplies of new cars and causing prices to rise.                                                                                                                                                                                                                         , Still, Ms. Yellen made the case that the economy was better off than some critics had suggested. She noted that wages for low-income workers, for instance, were outpacing price increases in the United States.                                                                                                                                                                                                                                                                                                                                                                               , Zach Montague contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-06 23:33:00 </td>
   <td style="text-align:left;"> European Stocks Close Sharply Lower </td>
   <td style="text-align:left;"> Major European bourses closed in negative territory on Wednesday, with the pan-European STOXX 600 and the DAX 30 falling 1.6% and 1.9%, respectively, amid fears over the economic impact of fresh sanctions against Russia. Western nations could deliver another slew of economic sanctions on Moscow this week, including a US bar on investment and an EU ban on coal imports, following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. On top of that, surprisingly hawkish comments from several Fed policymakers, signalling that the central bank heads for a more aggressive tightening, kept investors on edge. On the data front, factory orders in Germany sank much more than expected in February, a sign that current supply constraints, elevated energy costs and the war in Ukraine are weighing on the German economy a lot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60993640?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-06 23:29:18 </td>
   <td style="text-align:left;"> P&amp;O Ferries preparing to restart Dover-Calais route </td>
   <td style="text-align:left;"> P&amp;O Ferries has said it is preparing to get its Pride of Kent and Spirit of Britain ships back in action on the Dover-Calais route "by next week".                                                                                                                                                                                                            , The ferries will need to pass inspections by the Maritime Coastguard Agency (MCA) before services can resume.                                                                                                                                                                                                                                                 , There has not yet been any confirmation that the inspections, which can take days, have been booked in.                                                                                                                                                                                                                                                       , Holiday-makers and lorry drivers have faced queues near Dover in recent days.                                                                                                                                                                                                                                                                                 , Bad weather and the disruption to P&amp;O services had caused long queues of traffic as the Easter holidays started for some.                                                                                                                                                                                                                                     , P&amp;O Ferries had confirmed yesterday that all of its Dover-Calais routes would remain suspended this weekend, and that another ferry operator, DFDS, would not be able to take P&amp;O customers.                                                                                                                                                                  , The company expects the Pride of Kent and the Spirit of Britain will be sailing next week.                                                                                                                                                                                                                                                                    , A P&amp;O Ferries spokesperson said: "From this weekend, P&amp;O Ferries are getting ready to resume services across a number of vital routes.                                                                                                                                                                                                                        , "P&amp;O has been working closely with regulators to ensure our ships are safe to sail. P&amp;O is looking forward to welcoming back vital services and we expect to have two of our vessels ready to sail on the Dover-Calais route by next week, subject to regulatory signoff," they added.                                                                        , They also apologised to customers whose journeys had been cancelled or disrupted.                                                                                                                                                                                                                                                                             , Following the no-notice sacking of 786 seafarers by P&amp;O Ferries, passengers hoping to cross the channel have been left with fewer travel options.                                                                                                                                                                                                             , The company said on Wednesday it was providing refunds to all passengers booked to travel with them who cannot get on alternative services.                                                                                                                                                                                                                   , Two P&amp;O Ferries boats have been detained so far after failing to pass inspections by the MCA - including the Pride of Kent.                                                                                                                                                                                                                                   , Safety concerns have been raised over the replacement of employees with less experienced agency workers paid less than the UK minimum wage.                                                                                                                                                                                                                   , The Pride of Kent was detained for a mix of reasons including failures on documentation, crew training and emergency equipment not working properly.                                                                                                                                                                                                          , This video can not be played                                                                                                                                                                                                                                                                                                                                  , P&amp;O Ferries hit out at the time, saying in a statement that inspections of its ships had reached "an unprecedent level of rigour" after interventions by ministers.                                                                                                                                                                                           , Another P&amp;O Ferries vessel, the European Causeway - which runs between Larne and Cairnryan - failed an MCA Port State Control inspection in March. It is among the services P&amp;O is getting ready to resume, along with the Pride of Hull, which runs services between Hull and Rotterdam.                                                                     , In total, eight P&amp;O Ferries need to be inspected so that the MCA is satisfied they are safe to carry passengers and freight.                                                                                                                                                                                                                                  , The government recently announced a package of measures aimed at forcing P&amp;O Ferries to "fundamentally rethink" its decision, which drew outrage from politicians, trade unions and the public. They included plans to create new laws giving ports the power to block ferries from docking in the UK if they do not pay their crew the national minimum wage., Ferry industry groups, however, hit out at the transport secretary's plans, with the UK Major Ports Group saying they should not have to "be the police for the labour practices of ferry companies".                                                                                                                                                         , P&amp;O's chief executive, Peter Hebblethwaite, has insisted that a U-turn on the redundancies would cause the company's total collapse, leading to a loss of an additional 2,200 jobs.                                                                                                                                                                           , The company also faces criminal and civil investigations into the circumstances around the redundancies.                                                                                                                                                                                                                                                      , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                                                                                               , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                                                                        , Why does it impact almost every system in the human body?                                                                                                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/exports-yoy </td>
   <td style="text-align:left;"> 2022-04-06 23:17:00 </td>
   <td style="text-align:left;"> Colombia Exports Grow 43% YoY in February </td>
   <td style="text-align:left;"> Exports from Colombia rose 43 percent over a year to USD 4.2 billion in February of 2022, following a 44.8 percent jump in the previous month. Shipments grew primarily for fuels &amp; mining products (55.9 percent), namely oil &amp; derivatives (75.7 percent); and manufactured products (29.8 percent). Also, a significant increase was seen in sales of agriculture, food and beverages (43.8 percent), of which coffee. Colombia sold 14.7 million barrels of crude oil in February, 32.2 percent more compared to the same month of last year. The most important trading partners were the United States (26.6 percent of total exports), Panama (15.3 percent), China (5.7 percent) and Brazil (4.4 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/06/technology/personaltech/text-scam-spam.html </td>
   <td style="text-align:left;"> 2022-04-06 23:15:19 </td>
   <td style="text-align:left;"> Text Spam Is on the Rise. Here’s How to Spot It and What to Do - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , tech fix                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Text spam is on the rise. The latest version involves scammers sending messages to you seemingly from your own phone number. Here’s what to do.                                                                                                                                                                                                                                                                                                                                 , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                         , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                  , By Brian X. Chen                                                                                                                                                                                                                                                                                                                                                                                                                                                                , A few weeks ago, I woke up to an early morning text message on my smartphone. It wasn’t my editor or a needy friend in a different time zone. It was a message from myself.                                                                                                                                                                                                                                                                                                     , “Free Msg: Your bill is paid for March. Thanks, here’s a little gift for you,” the text from my own phone number read, pointing me to a web link.                                                                                                                                                                                                                                                                                                                               , In the last month I’ve received a handful of such texts. In online forums, many Verizon customers have reported the same experience.                                                                                                                                                                                                                                                                                                                                            , It was clear to me what was going on. Scammers had used internet tools to manipulate phone networks to message me from a number they weren’t actually texting from. It was the same method that robocallers use to “spoof” phone calls to appear as though they are coming from someone legitimate, like a neighbor. Had I clicked on the web link, I most likely would have been asked for personal information like a credit card number, which a scammer could use for fraud., Consumers have struggled with cellphone spam for years, primarily in the form of robocalls with scammers incessantly ringing to leave fraudulent messages about late payments for student loans, audits by the Internal Revenue Service and expired car warranties.                                                                                                                                                                                                             , Only recently has mobile phone fraud shifted more toward texting, experts said. Spam texts from all sorts of phone numbers — and not just your own — are on the rise. In March, 11.6 billion scam messages were sent on American wireless networks, up 30 percent from February. That outpaced robocalls, which rose 20 percent in the same period, according to an analysis by Teltech, which makes anti-spam tools for phones.                                                , Verizon confirmed that it was investigating the text issue. On Monday, it said it had fixed the problem. “We have blocked the source of the recent text messaging scheme in which bad actors were sending fraudulent text messages to Verizon customers which appeared to come from the recipient’s own number,” said Adria Tomaszewski, a Verizon spokeswoman.                                                                                                                 , Representatives for AT&amp;T and T-Mobile said they had not seen the same problem. But text spam affects all wireless subscribers, and carriers now offer resources online for how people can protect themselves and report spam.                                                                                                                                                                                                                                                   , Text scams vary widely but often involve getting you to cough up your personal data with messages disguised as tracking updates for phony package deliveries, or information about health products and online banking. Their rise has been fueled partly by the fact that messages are so effortless to send, Teltech said. In addition, industrywide and government efforts to crack down on robocalls may be pushing scammers to move on to text messages.                    , “Scammers are always looking for the next big thing,” said Giulia Porter, a vice president at Teltech. “Spam texts are just increasing at a much more drastic rate than spam calls.”                                                                                                                                                                                                                                                                                            , Here’s what to look out for with text scams — and what you can do.                                                                                                                                                                                                                                                                                                                                                                                                              , By far the most common text scam is the message impersonating a company that is offering a shipping update on a package, such as UPS, FedEx or Amazon, according to Teltech.                                                                                                                                                                                                                                                                                                    , In the last week, I have received messages that said a Samsung TV — a big-ticket item meant to get my attention — could not be delivered. Another advertised an anti-aging skin cream. Another message touted the benefits of a product that cured brain fog.                                                                                                                                                                                                                   , Be on the lookout for these telltale signs of a fraudulent text:                                                                                                                                                                                                                                                                                                                                                                                                                , Scam texts typically come from phone numbers that are 10 digits or longer. Authentic commercial entities generally send messages from four-, five- or six-digit numbers.                                                                                                                                                                                                                                                                                                        , The message contains misspelled words that were intended to circumvent the wireless carriers’ spam filters.                                                                                                                                                                                                                                                                                                                                                                     , The links in a scam text often look strange. Instead of a traditional web link composed of “www.websitename.com,” they are web links that contain sentences or phrases, like droppoundsketo.com. This practice, called URL masking, involves using a phony web link that directs you to a different web address that asks for your personal information.                                                                                                                        , First and foremost, never click on a link or file in a suspicious message.                                                                                                                                                                                                                                                                                                                                                                                                      , Definitely don’t reply to such a message, either. Even typing “STOP” will indicate to a scammer that your phone number is active.                                                                                                                                                                                                                                                                                                                                               , To report a scammy text, AT&amp;T, Verizon and T-Mobile offer the same number to forward the messages to: 7726. After forwarding, the carrier asks for the phone number that the message came from.                                                                                                                                                                                                                                                                                 , If text spam is becoming overwhelming, spam-filtering apps like Teltech’s TextKiller are meant to help. The app, which blocks spam texts for $4 a month, scans messages coming from phone numbers that are not in your address book. If the text is detected as spam, it gets filtered into a folder labeled “Junk.”                                                                                                                                                            , TextKiller was thorough — perhaps too thorough. It successfully caught five spam messages in five days, but it also erroneously filtered two legitimate messages, including a response from Verizon thanking me for reporting spam and a message from an AT&amp;T spokesman. So I wouldn’t recommend paying $4 a month for this app, which is available only for iPhones, unless spam texts have become truly unbearable for you.                                                   , Teltech said that false positives for messages marked as spam happened in rare cases, and that customers could share feedback to train TextKiller’s accuracy.                                                                                                                                                                                                                                                                                                                   , A more practical solution is to use free tools to minimize interruptions from spam texts. On iPhones, you can open the Settings app, tap messages and enable an option to “filter unknown senders.” That places messages from numbers that are not in your phone book into a separate messages folder. On Android phones, you can open the messages app, enter the spam messages settings and enable “block unknown senders.”                                                   , Finally, both iPhones and Android devices include the ability to open the settings of a message and block a specific number from contacting you.                                                                                                                                                                                                                                                                                                                                , There’s a moral to this story: We can help prevent spam from flooding our phones if we stop sharing our phone numbers with people we don’t fully trust. That includes the cashier at a retail store asking for our phone number to get a discount, or an app or a website asking for our digits when we sign up for an account. Who knows where our digits eventually end up after they reach the hands of marketers?                                                           , A better idea is for all of us to carry a second set of digits, which can be created with free internet calling apps like Google Voice, that we treat as a burner phone number.                                                                                                                                                                                                                                                                                                 , That way, the next time a scammer tries to send you a text from yourself, it won’t come from your own number.                                                                                                                                                                                                                                                                                                                                                                   , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-06 23:15:06 </td>
   <td style="text-align:left;"> Russia 10Y Bond Yield Edges Higher </td>
   <td style="text-align:left;"> The yield on the 10-year OFZ bond jumped to 11.8% in early April, amid continued capital control as investors weighed on Russia’s default risk over the non-payment of sovereign debt, while monitoring the extent of added sanctions by the EU and the US. The Russian treasury edged closer to a default after paying for a dollar-denominated Eurobond in rubles that were rejected by the foreign banks. The move came after the US treasury halted Russia from its dollar reserves in US banks, disabling Moscow from paying $552 million in principle and $84 million in coupons of debt. The payments were due to bond holders by April 4th, starting the 30-day grace period before default. Currency default swaps prices signalled a 99% change of Russia defaulting on government debt this year. Meanwhile, The US prepared new sanctions on Moscow to target banks and officials, while the EU planned to sanction coal imports amid discussions of more restrictions on Russian energy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-04-06 23:03:00 </td>
   <td style="text-align:left;"> Brent Turns Negative in Roller-Coaster Session </td>
   <td style="text-align:left;"> Brent crude futures dropped as low as $101.4 per barrel on Wednesday, having topped the $108 mark earlier this session as investors reacted to news that IEA would release 120 million barrels of oil to cool prices. Pressuring prices further were expectations of weaker demand following a build in US crude stockpiles and an extended lockdown in Shanghai. Still, the prospect of fresh sanctions on Russia raised supply concerns. The US and its allies prepared new sanctions on Moscow over civilian killings in northern Ukraine, with the EU proposing to ban Russian coal and prevent Russian ships from entering EU ports. Britain also urged G7 and NATO countries to agree to a timetable to phase out oil and gas imports from Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bosnia-and-herzegovina/producer-prices-change </td>
   <td style="text-align:left;"> 2022-04-06 22:59:03 </td>
   <td style="text-align:left;"> Bosnia and Herzegovina Producer Inflation Highest Since 2007 </td>
   <td style="text-align:left;"> Producer prices in Bosnia and Herzegovina surged 11.8 percent from a year earlier in February of 2022, accelerating from a 10.6 percent rise in the previous month. It was the highest producer inflation since comparable records began in 2007. Intermediate goods prices jumped 13.8 percent, followed by energy (12.1 percent), capital goods (12.1 percent), durable consumer goods (9.3 percent) and non-durable consumer goods (8.7 percent). On a monthly basis, producer prices rose 2.9 percent, following a 2.1 percent increase in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/elon-musk-twitter-stake </td>
   <td style="text-align:left;"> 2022-04-06 22:56:29 </td>
   <td style="text-align:left;"> Elon Musk signals active Twitter stake in updated SEC filing </td>
   <td style="text-align:left;"> Disruptive Tech Research founder and chief analyst Lou Basenese argues that the ‘best thing’ Elon Musk can do is ‘revoke’ Trump’s suspension on Twitter to ‘boost engagement immediately.’                                                                                                                                                                                                      , Elon Musk signaled he could be taking a more active role at Twitter after filing an update on his 9.2% stake with the Securities and Exchange Commission.                                                                                                                                                                                                                                       , When Musk first disclosed the stake, he used a 13G filing, which is typically reserved for passive investors. Musk acquired his Twitter stake on March 14, according to the filing. Shareholders who are hoping to hold a board position or otherwise change the company are typically required to file a longer, more in-depth form known as 13D within 10 days of buying at least a 5% stake. , New details in the 13D filing reveal that Musk made a series of cash purchases of Twitter stock between January 31 and April 1. The purchases ranged from as low as $32.80 per share to as high as $40.30 per share.                                                                                                                                                                            , The move follows his appointment to the social media giant's board of directors.                                                                                                                                                                                                                                                                                                                , ELON MUSK BECOMES TWITTER'S LARGEST SHAREHOLDER: WHO ARE THE OTHER TOP HOLDERS?                                                                                                                                                                                                                                                                                                                 , Musk, who is now Twitter's largest stockholder with 73,115,038 shares, has had Wall Street buzzing over his potential next steps for the company's long-term strategy, with speculation ranging from an all-out buyout of the platform to doing nothing at all.                                                                                                                                 , He has previously been critical of the platform's approach to free speech, going as far as floating the possibility of making a rival to Twitter. He has also been critical of Twitter CEO Parag Agrawal, comparing the executive to Joseph Stalin, the former leader of the Soviet Union.                                                                                                      , Though Musk's long-term intentions for Twitter remain unclear, the filing emphasizes that he is not allowed to own more than 14.9% of Twitter's stock while serving on the board or for 90 days after. His term is set to expire at Twitter’s 2024 annual meeting.                                                                                                                              , Wedbush Securities analyst Dan Ives said in a note to clients on Tuesday that Musk's involvement with Twitter could "lead to a host of strategic initiatives which could include a range of near-term and long-term possibilities out of the gates for the company still struggling in a social media arms race."                                                                               , Meanwhile, Bernstein analysts Mark Shmulik and Toni Sacconaghi Jr. believe Musk's interest is "mainly personal" and nothing more than a "potential distraction."                                                                                                                                                                                                                                , "We view the interest as a potential distraction for Musk and TSLA shareholders, given that Musk is arguably already overcommitted, and his fervor for the topic of censorship/free speech is high," they wrote in a note to clients on Tuesday.                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                         , Musk has teased that "significant improvements" will be coming to the platform in the coming months.                                                                                                                                                                                                                                                                                            , On Tuesday, Twitter revealed it has been working on an edit button since last year and has kicked off testing with users of its Blue subscription service. The idea was teased a day earlier in a poll put out by Musk seeking input from his more than 80 million followers.                                                                                                                   , Tesla CEO Elon Musk and Armin Laschet, CDU Federal Chairman and Prime Minister of North Rhine-Westphalia, talk during a tour of the plant of the future foundry of the Tesla Gigafactory on August 13, 2021 in Grünheide near Berlin, Germany. (Photo by P ((Photo by Patrick Pleul - Pool/Getty Images) / Getty Images)                                                                        , The latest move comes amid an ongoing legal dispute with the SEC, in which the Tesla executive is trying to throw out a 2018 agreement with the regulator requiring him to obtain pre-approval for his tweets about the company.                                                                                                                                                                , Musk could potentially draw additional SEC scrutiny after he appears to have waited 21 days after March 14 to disclose his Twitter stake. If the SEC determined that Musk violated the disclosure rule, he could be hit with a financial penalty, which are historically pretty small, around $100,000. Musk is worth an estimated $288 billion, according to the Bloomberg Billionaires Index. , FOX Business' Megan Henney contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/janet-yellen-economic-repercussions-russia-ukraine-war </td>
   <td style="text-align:left;"> 2022-04-06 22:54:27 </td>
   <td style="text-align:left;"> Yellen warns of 'enormous' economic repercussions from Ukraine invasion </td>
   <td style="text-align:left;"> Rep. David Kustoff, R-Tenn., calls out Treasury Secretary Janet Yellen for supporting big spending and creating ‘tremendous inflationary pressures.’                                                                                                                                                                                                                                                            , Treasury Secretary Janet Yellen on Wednesday warned of major consequences for the global economy as a result of the Russian-Ukraine war, including severe disruptions to the global flow of food and energy.                                                                                                                                                                                                    , "Russia’s actions represent an unacceptable affront to the rules-based, global order, and will have enormous economic repercussions in Ukraine and beyond," Yellen said in prepared remarks during her annual testimony before the House Financial Services Committee.                                                                                                                                          , JAMIE DIMON WARNS US ECONOMY FACES MAJOR RISKS FROM INFLATION, RUSSIA-UKRAINE WAR                                                                                                                                                                                                                                                                                                                               , Her comments come as the U.S., European Union and Group of Seven coordinated new sanctions on Russia – including a U.S. ban on new investment in the country and fresh penalties targeting top Russian security officials and President Vladimir Putin's adult children – in response to reported Russian atrocities in the Ukrainian town of Bucha.                                                            , Treasury Secretary Janet Yellen speaks during a Senate Banking Committee hearing on Capitol Hill in Washington, Tuesday, Nov. 30, 2021.  (AP Photo/Andrew Harnik / AP Newsroom)                                                                                                                                                                                                                                 , Western allies have already cut off a key part of the Central Bank of Russia by preventing it from selling dollars, euros and other foreign currencies in its roughly $630 billion reserve stockpile; blocked certain financial institutions from the Swift messaging system for international payments; and sanctioned some of the Russian elites who have close ties to Putin.                                , The U.S. also ordered a ban on Russian oil imports – something that Yellen acknowledged will push energy prices higher.                                                                                                                                                                                                                                                                                         , "We think it's a price that's important to pay to punish Russia for what it's doing in Ukraine," she said. "But energy prices are going up, the price of wheat and corn that Russia and Ukraine produce are going up and metals that play an important industrial role – nickel, titanium, palladium – the cost of those things are going up. This is going to escalate inflationary pressures as well."        , Economists have been downgrading their forecasts for the year ahead as the outbreak of the worst European conflict in decades roils markets and threatens to push inflation even higher – in addition to creating a massive humanitarian crisis that has left more than 13,000 dead and millions displaced.                                                                                                     , Members of the public show their support for Ukraine. (Jeff J Mitchell/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                             , Goldman Sachs economists have warned the probability of the U.S. economy plunging into a recession in the next year has risen dramatically in the wake of the war. They noted there is a "higher risk" of about 20% to 35% that the U.S. enters a recession over the next year.                                                                                                                                 , RUSSIA INVADES UKRAINE: LIVE UPDATES                                                                                                                                                                                                                                                                                                                                                                            , "While our baseline forecast assumes that further service sector reopening and spending from excess savings will keep real GDP growth positive in the coming quarters, uncertainty around the outlook is higher than normal," they wrote in a recent analyst note. "We view the risks of a recession as broadly in line with the 20-35% odds currently implied by models based on the slope of the yield curve." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-04-06 22:42:00 </td>
   <td style="text-align:left;"> Russian Ruble Strengthens Despite Default Risk </td>
   <td style="text-align:left;"> The Russian ruble strengthened to 81 per dollar on Wednesday, not far from its pre-invasion level as tough capital controls stabilized the currency despite threats of western sanctions, while Russia faces the risk of sovereign default. The US prepared new sanctions on Moscow to target banks and officials, while the EU planned to sanction coal imports amid discussions of more restrictions on Russian energy, including oil and natural gas. At the same time, the Russian treasury edged closer to a default after paying for a dollar-denominated Eurobond in rubles. The move came after the US treasury halted Russia from its dollar reserves in US banks, disabling Moscow from paying $552 million in principle and $84 million in coupons of debt. The payments were due to bond holders by April 4th, starting the 30-day grace period before default. Having fallen to 150 per USD, the ruble recently recovered those losses as authorities raised the policy rate to 20% along with strict capital controls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-04-06 22:39:51 </td>
   <td style="text-align:left;"> US Crude Inventories Unexpectedly Rise: EIA </td>
   <td style="text-align:left;"> US crude oil inventories rose by 2.421 million barrels to 412.4 million barrels in the week ended April 1st, after a 3.449 million barrel drop and compared with market expectations for a 2.056 million fall, data from the EIA Petroleum Status Report showed. Meanwhile, crude stocks at the Cushing, Oklahoma, rose by 1.654 million barrels, and distillate stockpiles which include diesel and heating oil went up 0.771 million barrels to 114.3 million barrels, against forecasts for a 0.819 million drop. Gasoline inventories went down 2.041 million barrels to 236.8 million barrels, while markets were expecting a 0.063 million-barrel increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-04-06 22:35:00 </td>
   <td style="text-align:left;"> Gasoline Futures Trim Gains on IEA Release </td>
   <td style="text-align:left;"> Gasoline futures hovered below $3.2 a gallon, losing some momentum after the IEA oil reserve release announcement. The release will amount to 120 million barrels, 60 million from the US and the other half from other IEA members, in a coordinated effort to ease prices of crude. The American contribution would be a part of the 180 million barrel release announced earlier by President Biden. Still, supply risks fueled bullish sentiment, as G7 countries and the EU mull a ban on Russian coal, and prospects of a wider ban on oil &amp; gas gained strength. On the demand side, US gasoline inventory levels unexpectedly fell last week by 2,041 thousand barrels, compared with analyst forecasts of a 63 thousand barrel injection into storage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/06/politics/supreme-court-shadow-docket-john-roberts-epa-water/index.html </td>
   <td style="text-align:left;"> 2022-04-06 22:26:42 </td>
   <td style="text-align:left;"> Chief Justice John Roberts joins with liberals to criticize 'shadow docket' as court reinstates Trump-era EPA rule - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)A 5-4 Supreme Court reinstated a Trump-era rule Wednesday that restricts the authority of states to reject federal permits under the Clean Water Act in another ruling putting the court's emergency docket in the spotlight.                                                                                                                                                                                                                                                                                                             , Chief Justice John Roberts joined the court's liberal justices in dissent, arguing that the court's majority had "gone astray" by granting an unwarranted request on its emergency docket.                                                                                                                                                                                                                                                                                                                                                      , "That renders the Court's emergency docket not for emergencies at all," Justice Elena Kagan wrote for the four dissenters. She said that the Republican-led states and others that had petitioned the court for emergency relief had not shown they would suffer the necessary irreparable harm to make their case.                                                                                                                                                                                                                             , "This Court may stay a decision under review in a court of appeals only in extraordinary circumstances and upon the weightiest considerations," Kagan wrote. She said the challengers' request for a stay rested on "simple assertions -- on conjectures, unsupported by any present-day evidence."                                                                                                                                                                                                                                             , The majority's move, Kagan insisted, signals the court's view of the merits even though the applicants have failed to make the irreparable harm showing "we have traditionally required."                                                                                                                                                                                                                                                                                                                                                       , The emergency docket, she said, "becomes only another place for merits determination -- except without full briefing and argument."                                                                                                                                                                                                                                                                                                                                                                                                             , The five conservative justices did not explain their reasoning for reinstating the Trump-era rule.                                                                                                                                                                                                                                                                                                                                                                                                                                              , The emergency docket -- referred to by some justices and outside observers as the "shadow docket" -- has increasingly come under criticism by those who say that important issues are being resolved without the benefit of full briefing schedule and oral arguments.                                                                                                                                                                                                                                                                          , While the court's liberals, especially Kagan, have often criticized the use of emergency petitions, this is the first time Roberts has explicitly joined in.                                                                                                                                                                                                                                                                                                                                                                                    , "We've seen Chief Justice Roberts join the Democratic appointees in dissenting from some of the Court's prior shadow docket rulings," said Steve Vladeck, a CNN Supreme Court analyst and professor at the University of Texas School of Law, who is penning a book on the shadow docket. "But today's ruling is the first time he's joined in publicly criticizing the majority for how it is using and abusing the shadow docket. That's a pretty significant development, and a strong signal for the Court's de facto leader to be sending.", In the dissent, Kagan wrote that the challengers had failed to offer "concrete proof" that they would be harmed  if the Environmental Protection Agency rule were not reinstated. She noted specifically that they had waited five months after the lower court vacated the rule to make their request. In addition, she said, a federal appeals court is set to hear the dispute next month and that the rule that is currently in place had previously been on the books for some 50 years.                                                   , Last September, conservative Justice Samuel Alito launched a 10-point rebuttal in an unusual speech, defending the court's practice when it comes to the emergency docket. He said the complications surrounding the emergency requests and said that the justices do "the best we can" under the time constraints imposed by the situation. Alito called criticism "very misleading," stressing that there is "absolutely nothing new about emergency applications."                                                                           , The court's order on Wednesday reinstates a rule that restricts the authority of states under the Clean Water Act to reject federal permits for projects that affect waters within their borders. The Trump-era rule will go back into effect while the Biden administration issues a new rule which is expected to be finalized by spring 2023.                                                                                                                                                                                                , It is a loss for more than 20 Democratic-led states, the District of Columbia, environmental groups and tribes that challenged the rule put in place by the Trump administration in 2020. They said it limited the abilities of states and local communities to weigh in on projects that could harm their communities. Challengers said the Trump rule could lead to projects -- such as a strip mall on a wetland, a hydroelectric project or oil and gas pipelines -- that could alter waterways without input from the state.               , Earthjustice, representing environmental groups and tribes opposed to the Trump rule, criticized the court's order.                                                                                                                                                                                                                                                                                                                                                                                                                             , "The court's decision to reinstate the Trump administration rule shows disregard for the integrity of the Clean Water Act and undermines the rights of tribes and states to review and reject dirty fossil fuel projects that threaten their water," said Moneen Nasmith, senior attorney for the group.                                                                                                                                                                                                                                        , A lower court had vacated the rule, prompting a group of Republican-led states and various industries to seek emergency relief from the Supreme Court.                                                                                                                                                                                                                                                                                                                                                                                          , This story has been updated with additional details.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/elon-musk-join-twitter-board-of-directors </td>
   <td style="text-align:left;"> 2022-04-06 22:21:19 </td>
   <td style="text-align:left;"> Elon Musk to join Twitter board of directors: Everything we know </td>
   <td style="text-align:left;"> Constellation Research CEO R "Ray" Wang weighs in on Elon Musk joining Twitter’s board of directors.                                                                                                                                                                                                                         , Elon Musk revealed this week that he had purchased a sizable chunk of Twitter shares, becoming the company's largest shareholder one week after hinting that he planned to shake up the social-media industry.                                                                                                               , The Tesla chief executive is a frequent user, as well as a longtime critic, of the platform, which he has previously accused of stifling free speech.                                                                                                                                                                        , The disclosure of his stake on Monday came shortly after he teased the possibility on Twitter of creating a new social media platform, telling his more than 80 million followers that he was "giving serious thought" to the idea without revealing his stake in Twitter.                                                   , ELON MUSK PURCHASES STAKE IN TWITTER AFTER SLAMMING ITS APPROACH TO ‘FREE SPEECH’                                                                                                                                                                                                                                            , In an accompanying poll, Musk asked his followers whether they believe Twitter "rigorously adheres" to the principle of free speech. "The consequences of this poll will be important," he added. "Please vote carefully."                                                                                                   , Tesla CEO Elon Musk tours the plant of the future foundry of the Tesla Gigafactory on Aug. 13, 2021, in Grünheide near Berlin, Germany. (Patrick Pleul - Pool/Getty Images / Getty Images)                                                                                                                                   , Since then, Twitter CEO Parag Agrawal announced that Musk will be joining the company's board of directors, following several weeks of conversation. Musk tweeted that he hopes to make "significant improvements" to Twitter in the coming months with the new role.                                                        , Here is everything that we know about the matter so far:                                                                                                                                                                                                                                                                     , Musk disclosed on Monday that he had acquired a 9.2% stake in Twitter in an SEC form that investors are required to file when they own more than 5% of a company. The filing, dated March 14, revealed that Musk bought about 73.5 million shares for roughly $2.9 billion. Those shares are now worth roughly $3.7 billion. , No. Although Musk is the company's largest shareholder, he does not own a majority of shares – which would mean that he owns and controls at least 50% of Twitter stock.                                                                                                                                                     , Still, the significance of a 9.2% stake should not be overlooked.                                                                                                                                                                                                                                                            , "It looks like Elon has his eyes laser set on Twitter," Wedbush analyst Dan Ives said in a research note. He said the state could ultimately lead to a "more aggressive ownership role."                                                                                                                                     , Musk's stake elbowed Vanguard Group from the top shareholder spot to No. 2, according to data from FactSet. Vanguard Group has an 8.4% stake in the company.                                                                                                                                                                 , In this photo illustration the logo of Twitter can be seen on a smartphone on March 10, 2022, in Berlin, Germany. (Thomas Trutschel/Photothek via Getty Images / Getty Images)                                                                                                                                               , Morgan Stanley Investment Management, meanwhile, fell to No. 3, with holdings of 8.1%.                                                                                                                                                                                                                                       , Twitter founder and former CEO Jack Dorsey is the only other individual shareholder in the top 10. At No. 7, he holds a 2.25% stake in the company, a position that is almost $200 million more valuable after Musk revealed his purchase.                                                                                   , Agrawal on Tuesday announced that Musk would join the company's board.                                                                                                                                                                                                                                                       , "He’s both a passionate believer and intense critic of the service which is exactly what we need on @Twitter, and in the boardroom, to make us stronger in the long-term," Agrawal tweeted.                                                                                                                                  , Musk responded that he was "looking forward to working with Parag &amp; Twitter board to make significant improvements to Twitter in coming months!"                                                                                                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                      , Since then, Musk asked his followers on Twitter to vote on whether to company should add the ability for users to edit tweets after posting them. More than 73% of 4.4 million respondents voted "yes."                                                                                                                      , The following day, the company said that it had been working on that feature since last year. It added, "no we didn't get the idea from a poll."                                                                                                                                                                             , Musk's two-year board term expires in 2024. During his board term, Musk's stake in the company cannot exceed 14.9%, according to a securities filing from Twitter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-04-06 22:18:00 </td>
   <td style="text-align:left;"> Crude Oil Fall Below $97 </td>
   <td style="text-align:left;"> WTI crude futures tumbled to around $96 per barrel, a dramatic reversal from its daily highs of $104 as investors reacted to news that IEA would release 120 million barrels of oil to cool prices. Pressuring prices further were expectations of weaker demand following a build in US crude stockpiles and an extended lockdown in Shanghai. Still, the prospect of fresh sanctions on Russia raised supply concerns. The US and its allies prepared new sanctions on Moscow over civilian killings in northern Ukraine, with the EU proposing to ban Russian coal and prevent Russian ships from entering EU ports. Britain also urged G7 and NATO countries to agree to a timetable to phase out oil and gas imports from Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/06/economy/treasury-yellen-economic-impact-ukraine/index.html </td>
   <td style="text-align:left;"> 2022-04-06 22:16:32 </td>
   <td style="text-align:left;"> Janet Yellen warns of 'enormous' economic repercussions from war in Ukraine - CNN </td>
   <td style="text-align:left;"> New York (CNN Business)US Treasury Secretary Janet Yellen warned Wednesday about the economic shock waves set off by the war in Ukraine, including disruptions to the global flow of food and energy.                                                                                                                                            , "Russia's actions represent an unacceptable affront to the rules-based, global order, and will have enormous economic repercussions in Ukraine and beyond," Yellen said during her testimony before the House Financial Services Committee.                                                                                                      , The war -- and the political response of the West, mostly through sanctions -- has already sent food and energy prices soaring and has raised concerns about an economic slowdown or even recession during a time of already rampant inflation around the world. In the United States, for example, inflation is at a level not seen in 40 years., Yellen described Russia's invasion as "brutal and unprovoked" on Wednesday, and emphasized the Treasury Department is committed to holding Russia "accountable for its actions."                                                                                                                                                                 , On Wednesday, the Biden administration imposed new sanctions on Russian banking institutions -- Sberbank and Alfa Bank -- as well as individuals, including President Vladimir Putin's adult daughters. These new sanctions followed horrific images of carnage and possible war crimes in the Ukrainian city of Bucha.                          , But the fact that America's European partners remain heavily reliant on Russian energy exports limits what the West can do. The United States intends to inflict the maximum sanctions pain possible against Russia while taking care not to inflict undue pain on its allies, Yellen said repeatedly on Wednesday.                              , "The issue with blocking oil exports from Russia is that many countries, especially in Europe, are very dependent on that oil," she said. "And we're likely going to see skyrocketing prices if we did put a complete ban on oil."                                                                                                               , Germany, for example, would be left out in the cold -- literally -- if it stopped importing Russian gas. Germany is Russia's biggest energy customer in the European Union, which depends on Moscow for about 40% of its natural gas.                                                                                                            , "Globally, spillovers from the crisis are heightening economic vulnerabilities in many countries that are already facing higher debt burdens and limited policy options as they recover from Covid-19," Yellen said.                                                                                                                             , Energy prices have been driven higher by concerns about supply from Russia, the number one exporter of crude oil in the world.                                                                                                                                                                                                                   , "We are witnessing the vulnerability that comes from relying on one fuel source or one trade partner," Yellen said, which is why it is imperative to diversify energy sources and suppliers."                                                                                                                                                    , But it's not just about energy. Together, Russia and Ukraine account for nearly one-third of the world's wheat exports.                                                                                                                                                                                                                          , "Russia's invasion disrupted the flow of food for millions of people around the world and caused prices to spike," the Treasury Secretary said.                                                                                                                                                                                                  , Yellen said Treasury will press multilateral development banks to speed up food aid to "vulnerable" countries.                                                                                                                                                                                                                                   , Meanwhile, Yellen was cagey in response to lawmakers' questions about a potential conflict between China and Taiwan and what a US response to that might look like.                                                                                                                                                                              , "Certainly we are concerned about Taiwan and we will act appropriately," she said.                                                                                                                                                                                                                                                               , --CNN's Betsy Klein and Kevin Liptak contributed to this report.                                                                                                                                                                                                                                                                                 , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-04-06 22:10:00 </td>
   <td style="text-align:left;"> Lumber Hits 9-week Low </td>
   <td style="text-align:left;"> Chicago lumber futures extended their decline towards $900 per thousand board feet, a level not seen since December last year, as transportation bottlenecks that sparked a rally in early March started to ease. Flooding in British Columbia disrupted the transportation network and supplies in late 2021, and output volumes at sawmills have recovered from such constraints amid better spring weather, easing supply concerns after months of tight inventories. On top of that, rising mortgage rates should help cool the red-hot US housing market. New home sales in the US fell for a second straight month, surprising markets that expected them to rise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-06 22:09:18 </td>
   <td style="text-align:left;"> Toronto Stocks at Over 2-Week Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, retreated on Wednesday, in line with global peers, to levels not seen since March 18th, weighed down by tech and financial stocks, amid growing concerns over sanctions against Russia and a looming aggressive tightening of monetary policy. Canada and its G7 partners, as well as the EU, were mulling imposing tougher sanctions on Russia’s financial sector and banning Russian coal imports. On corporate updates, Suncor Energy announced its exit from wind and solar power two-decade old investments to focus on hydrogen and renewable fuels instead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/business-confidence </td>
   <td style="text-align:left;"> 2022-04-06 22:07:48 </td>
   <td style="text-align:left;"> Canada Ivey PMI Hits Highest Since 2006 </td>
   <td style="text-align:left;"> The Ivey Purchasing Managers Index in Canada increased to 74.2 in March of 2022 from 60.6 in the prior month, and surprising analysts that expected it to drop to 60. It was the highest reading since May 2006, as firms expanded their workforce at a faster pace (62.5 from 60.3 in February). On the price front, the rate of inflation accelerated (89.6 from 88.5), as inventories remained were higher (65.1 from 62.1) while supplier deliveries were slower than the previous month (34.8 from 31.9). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-04-06 22:05:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 1-Month Low </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 3.8% to 2,128 points on Wednesday, its lowest since March 3rd, extending losses for the tenth straight session, amid weakness across all its vessels segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, slumped 8.3% to 1,490 points; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, decreased 2.8% to 2,868 points. Among smaller vessels, the supramax index shed 55 points to 2,605 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/06/technology/openai-images-dall-e.html </td>
   <td style="text-align:left;"> 2022-04-06 22:00:13 </td>
   <td style="text-align:left;"> Meet DALL-E, the A.I. That Draws Anything at Your Command - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , New technology that blends language and images could serve graphic artists — and speed disinformation campaigns.                                                                                                                                                                                                                                                                                                                                                                           , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                             , By Cade Metz                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , SAN FRANCISCO — At OpenAI, one of the world’s most ambitious artificial intelligence labs, researchers are building technology that lets you create digital images simply by describing what you want to see.                                                                                                                                                                                                                                                                              , They call it DALL-E in a nod to both “WALL-E,” the 2008 animated movie about an autonomous robot, and Salvador Dalí, the surrealist painter.                                                                                                                                                                                                                                                                                                                                               , OpenAI, backed by a billion dollars in funding from Microsoft, is not yet sharing the technology with the general public. But on a recent afternoon, Alex Nichol, one of the researchers behind the system, demonstrated how it works.                                                                                                                                                                                                                                                     , When he asked for “a teapot in the shape of an avocado,” typing those words into a largely empty computer screen, the system created 10 distinct images of a dark green avocado teapot, some with pits and some without. “DALL-E is good at avocados,” Mr. Nichol said.                                                                                                                                                                                                                    , When he typed “cats playing chess,” it put two fluffy kittens on either side of a checkered game board, 32 chess pieces lined up between them. When he summoned “a teddy bear playing a trumpet underwater,” one image showed tiny air bubbles rising from the end of the bear’s trumpet toward the surface of the water.                                                                                                                                                                  , DALL-E can also edit photos. When Mr. Nichol erased the teddy bear’s trumpet and asked for a guitar instead, a guitar appeared between the furry arms.                                                                                                                                                                                                                                                                                                                                     , A team of seven researchers spent two years developing the technology, which OpenAI plans to eventually offer as a tool for people like graphic artists, providing new shortcuts and new ideas as they create and edit digital images. Computer programmers already use Copilot, a tool based on similar technology from OpenAI, to generate snippets of software code.                                                                                                                    , But for many experts, DALL-E is worrisome. As this kind of technology continues to improve, they say, it could help spread disinformation across the internet, feeding the kind of online campaigns that may have helped sway the 2016 presidential election.                                                                                                                                                                                                                              , “You could use it for good things, but certainly you could use it for all sorts of other crazy, worrying applications, and that includes deep fakes,” like misleading photos and videos, said Subbarao Kambhampati, a professor of computer science at Arizona State University.                                                                                                                                                                                                           , A half decade ago, the world’s leading A.I. labs built systems that could identify objects in digital images and even generate images on their own, including flowers, dogs, cars and faces. A few years later, they built systems that could do much the same with written language, summarizing articles, answering questions, generating tweets and even writing blog posts.                                                                                                            , Now, researchers are combining those technologies to create new forms of A.I. DALL-E is a notable step forward because it juggles both language and images and, in some cases, grasps the relationship between the two.                                                                                                                                                                                                                                                                    , “We can now use multiple, intersecting streams of information to create better and better technology,” said Oren Etzioni, chief executive of the Allen Institute for Artificial Intelligence, an artificial intelligence lab in Seattle.                                                                                                                                                                                                                                                   , The technology is not perfect. When Mr. Nichol asked DALL-E to “put the Eiffel Tower on the moon,” it did not quite grasp the idea. It put the moon in the sky above the tower. When he asked for “a living room filled with sand,” it produced a scene that looked more like a construction site than a living room.                                                                                                                                                                      , But when Mr. Nichol tweaked his requests a little, adding or subtracting a few words here or there, it provided what he wanted. When he asked for “a piano in a living room filled with sand,” the image looked more like a beach in a living room.                                                                                                                                                                                                                                        , DALL-E is what artificial intelligence researchers call a neural network, which is a mathematical system loosely modeled on the network of neurons in the brain. That is the same technology that recognizes the commands spoken into smartphones and identifies the presence of pedestrians as self-driving cars navigate city streets.                                                                                                                                                   , A neural network learns skills by analyzing large amounts of data. By pinpointing patterns in thousands of avocado photos, for example, it can learn to recognize an avocado. DALL-E looks for patterns as it analyzes millions of digital images as well as text captions that describe what each image depicts. In this way, it learns to recognize the links between the images and the words.                                                                                          , When someone describes an image for DALL-E, it generates a set of key features that this image might include. One feature might be the line at the edge of a trumpet. Another might be the curve at the top of a teddy bear’s ear.                                                                                                                                                                                                                                                         , Then, a second neural network, called a diffusion model, creates the image and generates the pixels needed to realize these features. The latest version of DALL-E, unveiled on Wednesday with a new research paper describing the system, generates high-resolution images that in many cases look like photos.                                                                                                                                                                           , Though DALL-E often fails to understand what someone has described and sometimes mangles the image it produces, OpenAI continues to improve the technology. Researchers can often refine the skills of a neural network by feeding it even larger amounts of data.                                                                                                                                                                                                                         , They can also build more powerful systems by applying the same concepts to new types of data. The Allen Institute recently created a system that can analyze audio as well as imagery and text. After analyzing millions of YouTube videos, including audio tracks and captions, it learned to identify particular moments in TV shows or movies, like a barking dog or a shutting door.                                                                                                   , Experts believe researchers will continue to hone such systems. Ultimately, those systems could help companies improve search engines, digital assistants and other common technologies as well as automate new tasks for graphic artists, programmers and other professionals.                                                                                                                                                                                                            , But there are caveats to that potential. The A.I. systems can show bias against women and people of color, in part because they learn their skills from enormous pools of online text, images and other data that show bias. They could be used to generate pornography, hate speech and other offensive material. And many experts believe the technology will eventually make it so easy to create disinformation, people will have to be skeptical of nearly everything they see online., “We can forge text. We can put text into someone’s voice. And we can forge images and videos,” Dr. Etzioni said. “There is already disinformation online, but the worry is that this scale disinformation to new levels.”                                                                                                                                                                                                                                                                  , OpenAI is keeping a tight leash on DALL-E. It would not let outsiders use the system on their own. It puts a watermark in the corner of each image it generates. And though the lab plans on opening the system to testers this week, the group will be small.                                                                                                                                                                                                                             , The system also includes filters that prevent users from generating what it deems inappropriate images. When asked for “a pig with the head of a sheep,” it declined to produce an image. The combination of the words “pig” and “head” most likely tripped OpenAI’s anti-bullying filters, according to the lab.                                                                                                                                                                          , “This is not a product,” said Mira Murati, OpenAI’s head of research. “The idea is understand capabilities and limitations and give us the opportunity to build in mitigation.”                                                                                                                                                                                                                                                                                                            , OpenAI can control the system’s behavior in some ways. But others across the globe may soon create similar technology that puts the same powers in the hands of almost anyone. Working from a research paper describing an early version of DALL-E, Boris Dayma, an independent researcher in Houston, has already built and released a simpler version of the technology.                                                                                                                 , “People need to know that the images they see may not be real,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                   , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/04/06/politics/us-latest-sanctions-on-russia/index.html </td>
   <td style="text-align:left;"> 2022-04-06 21:56:02 </td>
   <td style="text-align:left;"> Biden says 'major war crimes' being discovered in Ukraine after he announces new sanctions on Russia - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)President Joe Biden declared "major war crimes" were being discovered in Ukraine as Russian forces retreat from areas around Kyiv, citing scenes of brutal, cold-blooded executions as rationale for ratcheting up US sanctions on Moscow.                                                                                                                                               , "Responsible nations have to come together to hold these perpetrators accountable," Biden told a union crowd in Washington as the White House announced new sanctions on Russia's largest financial institutions and number of individuals tied to the Kremlin, including Russian President Vladimir Putin's two adult daughters.                                                              , "We will keep raising the economic cost and ratchet up the pain for Putin and further increase Russia's economic isolation," Biden said, decrying the intentional targeting of civilians by Russia and heralding a united Western response, even as he acknowledged the battle was still ongoing.                                                                                              , Horrific images from the Ukrainian city of Bucha imparted "a sense of brutality and inhumanity left for all the world to see, unapologetically," Biden said in his remarks as he announced new steps the US was taking to punish those responsible.                                                                                                                                            , The sanctions are designed to tighten the vise on Russia's economy, which has been kneecapped by Western punishment. Still, ever-harsher consequences for the invasion of Ukraine have not appeared to force Putin to ease a brutal campaign that has increasingly targeted civilians.                                                                                                         , Biden has previously said he believes Putin to be a war criminal, and this week called for a trial to hold Moscow accountable. Still, the process for prosecuting war crimes is complex and lengthy, and questions remain about how and when such accountability could be delivered.                                                                                                           , US Attorney General Merrick Garland said Wednesday the Justice Department is assisting with the collection of evidence for potential war crimes prosecutions related to Russia's invasion of Ukraine. He said he'd spoken with French and other European officials about the collection of evidence currently underway.                                                                        , And Secretary of State Antony Blinken said Sunday the US was "working to document" war crimes with the goal of providing the information to relevant agencies.                                                                                                                                                                                                                                 , White House national security adviser Jake Sullivan also said this week the US would seek information from intelligence services, eyewitness Ukrainians, international organizations and interviews in the global media to build a case.                                                                                                                                                       , Biden praised Ukraine on Wednesday for sustaining a fight against Russia that prevented it from taking the country's capital.                                                                                                                                                                                                                                                                  , "Thanks to the bravery, the grit and the fighting spirit of the Ukrainian people Russia has already failed in its initial war aims. Russia wanted to take Ukraine's capital city Kyiv and topple its democracy and elected government. Today, Kyiv still stands and that government presides," Biden said.                                                                                     , But he cautioned the violence may not end soon.                                                                                                                                                                                                                                                                                                                                                , "The fight is far from over," he said. "This war could continue for a long time."                                                                                                                                                                                                                                                                                                              , The "full blocking" sanctions on Russia's largest financial institution, Sberbank, and its largest private bank, Alfa Bank, are meant to grind Russia's economy further to a halt. They will prohibit transactions with any American financial institutions and freeze assets held by the banks in the US.                                                                                     , "They will not be able to touch any of their money. They will not be able to do any business here," Biden said.                                                                                                                                                                                                                                                                                , Sberbank holds nearly one-third of Russia's total banking sector assets, and the White House says that with Wednesday's sanctions, more than two-thirds of the Russian banking sector are now blocked.                                                                                                                                                                                         , "The sad reality is Putin's war will make it harder for Russians to travel abroad. It means their debit cards may not work. They may only have the option to buy knockoff phones and knockoff clothes, the shelves at stores may be empty," a senior administration official told reporters.                                                                                                   , "The reality is the country's descending into economic and financial and technological isolation and at this rate, it will go back to Soviet-style standards from the 1980s," the official went on.                                                                                                                                                                                            , In targeting Putin's two adult daughters, the US hopes to freeze any assets the Russian President may be hiding with them, according to the senior administration official. Without detailing which of Putin's assets could be hiding with Mariya Putina and Katerina Tikhonova, the official said the practice was common among the Russian elite.                                            , Members of Russia's Security Council, including former President and Prime Minister of Russia Dmitry Medvedev and Prime Minister Mikhail Mishustin, are also being targeted by individual sanctions. The US has already sanctioned more than 140 oligarchs and their family members and over 400 Russian government officials, the senior official said.                                       , "Look, these oligarchs and their family members are not allowed to hold on to their wealth in Europe and the United States and keep these yachts worth hundreds of millions of dollars, their luxury vacation homes while children in Ukraine are being killed, displaced from their homes every single day," Biden said in his speech.                                                        , The new sanctions will cut those individuals off from the US banking system and freeze any assets held in the United States.                                                                                                                                                                                                                                                                   , The White House also announced a ban on new investment in Russia that will be executed in alignment with the G7 and EU. The ban will be implemented with an executive order signed by President Joe Biden.                                                                                                                                                                                     , And the US will also apply full blocking sanctions on critical major Russian state-owned enterprises, which will be announced by the Department of Treasury on Thursday. The official also noted Tuesday's announcement that the Department of Treasury has blocked Russia from making debt payments with dollars stockpiled at US banks.                                                      , While the US and its allies have imposed the most sweeping sanctions regime targeting a country of the size of Russia in history, officials acknowledge it has done little to shift Putin's calculation. The threat of the sanctions didn't deter the invasion itself, and the piling on of economic penalties hasn't brought Russia any closer to a withdrawal or negotiated settlement since., Pressed about the efficacy of sanctions in ending Putin's war in Ukraine, the senior official sought to underscore the effect they are having on life in Russia and said Putin would eventually have to reckon with his people.                                                                                                                                                                , "Even an autocrat like Putin has a social contract with the Russian people. He took away their freedom in exchange for promising stability, and so he's not giving them stability," the official said.                                                                                                                                                                                         , "The question really is not so much: What can we do and when will that have an effect? I think it's: What's the endgame here for Putin? What's he playing for?" the official said. "This is very clearly becoming a failure for him and at some point he will have to recognize that reality."                                                                                                 , This story has been updated with additional reporting.                                                                                                                                                                                                                                                                                                                                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/06/watch-treasury-secretary-janet-yellen-speak-live-on-the-global-financial-system.html </td>
   <td style="text-align:left;"> 2022-04-06 21:56:00 </td>
   <td style="text-align:left;"> Watch Treasury Secretary Janet Yellen speak live on the global financial system </td>
   <td style="text-align:left;"> , [The stream is slated to start at 10 a.m. ET. Please refresh the page if you do not see a player above at that time.]                                                                                                                                    , Treasury Secretary Janet Yellen testifies Wednesday before the House Financial Services Committee on the state of international finance.                                                                                                                 , In remarks prepared for the hearing, Yellen in particular noted the impact that Russia's attack on Ukraine will have on the global system.                                                                                                               , "Russia's actions, including the atrocities committed against innocent Ukrainians in Bucha, are reprehensible, represent an unacceptable affront to the rules-based global order, and will have enormous economic repercussions for the world," she said., Yellen also noted that institutions such as the International Monetary Fund, the World Bank and others are stepping in to provide financial assistance to Ukraine.                                                                                       , Subscribe to CNBC on YouTube.                                                                                                                                                                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-06 21:44:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Fall for 3rd Day </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, was down 0.7% to around 118,105 on Wednesday, its lowest since March 23rd, extending losses for a third straight session, led by banking, travel and technology stocks. Meanwhile, gains in heavyweight miner Vale, Suzano and Klabin avoided further decreases. The focus remained on the war in Ukraine and the possible economic consequences of aggressive sanctions against Russia. At the same time, investors reassessed their outlook on interest rates after hawkish comments from Fed officials. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-06 21:31:00 </td>
   <td style="text-align:left;"> US Stocks Extend Losses </td>
   <td style="text-align:left;"> The Dow Jones lost roughly 250 points at the opening bell Wednesday, while the S&amp;P 500 and the Nasdaq 100 fell 1.3% and 2.4%, respectively, following hawkish remarks from Fed officials and as investors await details of fresh international sanctions against Russia. After Fed Governor Lael Brainard flagged rapid reductions in the balance sheet and steady interest rates hikes, Philadelphia Fed President Patrick Harker and San Francisco Fed President Mary Daly joined the chorus warning about inflation. Meanwhile, the gap between 2 and 10-year bond yields widened further. Now all eyes are on the Fed meeting minutes Wednesday for further clues on the central bank’s rate-hike path. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-04-06 21:25:00 </td>
   <td style="text-align:left;"> European Equity Sell-off Deepens </td>
   <td style="text-align:left;"> Main European stock market indexes fell more than 2% on Wednesday, with consumer discretionary and technology shares leading the decline amid fears over the economic impact of fresh sanctions against Russia. Western nations could deliver another slew of economic sanctions on Moscow this week, including a US bar on investment and an EU ban on coal imports, following mounting evidence of war crimes committed by its forces on the outskirts of Kyiv. On top of that, surprisingly hawkish comments from several Fed policymakers, signalling that the central bank heads for a more aggressive tightening, kept investors on edge. On the data front, factory orders in Germany sank much more than expected in February, a sign that current supply constraints, elevated energy costs and the war in Ukraine are weighing on the German economy a lot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-06 21:10:07 </td>
   <td style="text-align:left;"> Poland 10Y Bond Yield Hits Near 10-year High </td>
   <td style="text-align:left;"> Poland 10 Year Government Bond Yeld increased to a near 10-year high of 5.62% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-04-06 21:01:00 </td>
   <td style="text-align:left;"> US Natural Gas Prices Approach 9-Year High </td>
   <td style="text-align:left;"> US natural gas futures increased by more than 5% to above $6.3 per million British thermal units on Wednesday extending a 6% gain in the previous session and closing on the highest level since 2014 on expectations of stronger demand. The probability that Europe may at least partially ban Russia's natural gas, oil or coal imports is rising. The LNG shipments to Europe are already at record levels and the US is facing greater pressure to help Europe secure more supplies. Meanwhile, Tuesday’s pipeline flow data showed the steepest one-day drop in output since the February freeze-off, whilst forecasts pointed to wintry weather in the US West, which could give heating demand a boost until mid-April. Also, the additional pressure comes from a surge in US coal prices. Last week, the coal prices in central Appalachia exceeded $100 a tonne for the first time since 2008. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/interest-rate </td>
   <td style="text-align:left;"> 2022-04-06 20:50:00 </td>
   <td style="text-align:left;"> Poland Surprises with 100bps Rate Hike </td>
   <td style="text-align:left;"> The National Bank of Poland raised its benchmark reference rate by 100bps to 4.5% on April 6th to its highest level since November of 2012 and above expectations of a 50bps increase. It was the seventh consecutive hike of the main rate, as the NBP aimed to combat inflationary pressures brought by higher prices for energy and agricultural commodities due to Russian military aggression against Ukraine. The country’s latest price inflation reading came at 10.9% in March, the highest since July 2000 and significantly above the central bank’s target range of 2.5% plus or minus one percentage point.  Meanwhile, the Lombard rate was increased by 100bps to 5% and the rediscount rate was hiked by 100bps to 4.55%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2022-04-06 20:24:00 </td>
   <td style="text-align:left;"> Swiss 10 Year Bond Yield Rebounds </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond rose to 0.65%, not far from the near seven-year high of 0.7% on March 30th, amid prospects of tighter monetary policy for major central banks. Federal Reserve Governor Brainard said the Fed will continue to tighten policy through a series of Funds rate hikes in the coming meetings, while the bank’s balance sheet could see a rapid reduction starting May. Domestically, the Swiss National Bank kept rates unchanged at -0.75% in its latest meeting, but SNB Chairman Jordan said that the central bank will take all necessary measures to control inflation, including the possibility of a transition away from the ultra-loose monetary policy the bank mandated since 2016. The change in rhetoric came after the SNB doubled its inflation expectations for year-end 2022 to 2.1%, before March figures were at a 13-year high of 2.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/auto-exports </td>
   <td style="text-align:left;"> 2022-04-06 20:14:50 </td>
   <td style="text-align:left;"> Mexico Auto Exports Snap 8 Months of Declines </td>
   <td style="text-align:left;"> Mexico’s auto exports rose 2.5 percent over a year earlier to 262,494 units in March of 2022, ending eight straight months of declines, amid easing signs of the global shortage of semiconductors. Among major exporting brands, shipments rose substantially for GM (38.5 percent to 67,352 units); Ford (9.7 percent to 27,878 units); Toyota (39.9 percent to 24,501 units); and to a lesser extent, Chrysler (1.7 percent to 26,426 units). On the other hand, major losses were observed in Volkswagen (-11.7 percent to 22,557 units) and Nissan (-42.9 percent to 27,648 units). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/04/06/business/energy-environment/gas-prices-executives-congress.html </td>
   <td style="text-align:left;"> 2022-04-06 20:08:49 </td>
   <td style="text-align:left;"> Oil Executives Speak About High Gas Prices at House Hearing - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Leaders of Exxon Mobil, Chevron and four other companies testified about gas prices before a House committee on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                         , By Annie Karni and Clifford Krauss                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , WASHINGTON — Amid a swirl of partisan finger-pointing on who is responsible for rising energy prices, executives of six large oil and gas companies defended themselves on Wednesday against criticisms that they are seeking to boost corporate profits by refusing to produce more oil and gas.                                                                                                                                                                                                                  , They appeared before a House committee as high gasoline prices have become a central issue ahead of the midterm elections in November. Republicans have blamed Biden administration regulations and environmental policies for shortfalls in energy production, while Democrats have questioned why companies could not lower gasoline prices as oil prices have eased somewhat since a spike after Russia’s invasion of Ukraine.                                                                                  , Trying to duck the political debate, the executives said they were not engaging in price gouging and were merely responding to global commodity prices that were out of their control. They also said they were working to shift to cleaner energy.                                                                                                                                                                                                                                                                , “We are here to get answers from big oil companies on why they are ripping off the American people,” said Representative Frank Pallone Jr., a New Jersey Democrat and chair of the Energy and Commerce Committee, during the hearing. “At a time of record profits, Big Oil is refusing to increase production.”                                                                                                                                                                                                   , The oil executives took exception to the accusations by Democrats, but remained low key in their responses.                                                                                                                                                                                                                                                                                                                                                                                                        , “Because oil is a global commodity, Shell does not set or control the price of crude oil,” Gretchen H. Watkins, the president of Shell USA, told the committee in her prepared remarks. “Today’s crisis and the pressure on hydrocarbon supplies and prices reveal the urgent need to accelerate the energy transition.”                                                                                                                                                                                           , Michael Wirth, Chevron’s chief executive, insisted that the company had “no tolerance for price gouging.”                                                                                                                                                                                                                                                                                                                                                                                                          , With his approval ratings falling to a new low as inflation has stayed high for months, President Biden has struggled to explain the rise in gas prices to the American people. In an attempt to capitalize on broad support for crippling sanctions on Russia, the administration has tried to characterize the recent uptick in gas prices as “Putin’s price hike.”                                                                                                                                              , But Republicans have tried to hang the increase around the president’s neck, noting that the price of gas has been on the rise for a year, long before Mr. Putin’s invasion of Ukraine. They have used anxiety about higher gas prices as their main argument to voters about the need for a change in leadership.                                                                                                                                                                                                 , Republicans have hammered Mr. Biden for his cancellation of permits for the Keystone XL oil pipeline, as well as pauses on new leases for oil wells on federal lands. White House officials have tried to explain that neither policy is responsible for the rise in gas prices.                                                                                                                                                                                                                                   , In reality, the loosening of pandemic restrictions has increased demand for gas when supply is not rising quickly enough. Both supply and demand are being driven by factors that are out of the control of Mr. Biden and Congress.                                                                                                                                                                                                                                                                                , Still, the attacks appear to be working. In a recent Quinnipiac University poll, only 24 percent of respondents said they thought the rise in gas prices was a result of the war in Ukraine, with more Americans blaming the Biden administration’s policies.                                                                                                                                                                                                                                                      , A recent NBC News poll showed that despite broad support for banning Russian oil imports, the majority of Americans were still worried about gas prices. Polls have shown Mr. Biden’s approval ratings to be near the lowest of his presidency, at about 40 percent, suggesting that Americans hold him responsible even if they support some of his foreign policies.                                                                                                                                             , Some Democrats facing competitive races in November have pushed to suspend the federal gas tax through the end of the year. But Republicans quickly shot down the proposal, calling it a desperate attempt to appeal to voters.                                                                                                                                                                                                                                                                                    , Progressives have also tried to use the spike in energy and gas prices to push for investments in clean energy in order to reduce the reliance on foreign authoritarian leaders and oil companies. The United Nations Intergovernmental Panel on Climate Change said in a report published this week that the world needs to significantly accelerate efforts to slash greenhouse gas emissions from oil and other fossil fuels in order to limit global warming to 1.5 degrees Celsius, or 2.7 degrees Fahrenheit., Republicans at Wednesday’s hearing sought to capitalize on Mr. Biden’s weak position.                                                                                                                                                                                                                                                                                                                                                                                                                              , “This is not the Putin price hike,” said Representative Cathy McMorris Rodgers, Republican of Washington. “This is the Biden price hike. It’s been a steady climb since he took office.” She said Democrats were seeking another scapegoat by blaming the oil industry.                                                                                                                                                                                                                                            , Ms. Rodgers and other Republicans criticized what they called administration efforts to ease oil sanctions on Venezuela and Iran to boost global oil supplies, as well as the decision to block the Keystone XL pipeline, which would have imported more Canadian production from that country’s oil sands.                                                                                                                                                                                                        , Rising concerns. Russia’s invasion on Ukraine has had a ripple effect across the globe, adding to the stock market’s woes. The conflict has already caused​​ dizzying spikes in energy prices and is causing Europe to raise its military spending.                                                                                                                                                                                                                                                                  , The cost of energy. Oil prices already were the highest since 2014, and they have continued to rise since the invasion.  Russia is the third-largest producer of oil, so more price increases are inevitable.                                                                                                                                                                                                                                                                                                      , Gas supplies. Europe gets nearly 40 percent of its natural gas from Russia, and it is likely to be walloped with higher heating bills. Natural gas reserves are running low, and European leaders worry that Moscow could cut flows in response to the region’s support of Ukraine.                                                                                                                                                                                                                                , Food prices. Russia is the world’s largest supplier of wheat; together, it and Ukraine account for nearly a quarter of total global exports. Countries like Egypt, which relies heavily on Russian wheat imports, are already looking for alternative suppliers.                                                                                                                                                                                                                                                   , Shortages of essential metals. The price of palladium, used in automotive exhaust systems and mobile phones, has been soaring amid fears that Russia, the world’s largest exporter of the metal, could be cut off from global markets. The price of nickel, another key Russian export, has also been rising.                                                                                                                                                                                                      , Financial turmoil. Global banks are bracing for the effects of sanctions intended to restrict Russia’s access to foreign capital and limit its ability to process payments in dollars, euros and other currencies crucial for trade. Banks are also on alert for retaliatory cyberattacks by Russia.                                                                                                                                                                                                               , The average price for a gallon of gasoline is roughly $1.30 higher than it was a year ago, moving up in tandem with oil prices, which are now just below $100 a barrel.                                                                                                                                                                                                                                                                                                                                            , Democrats have called on oil executives to suspend dividend increases and stock buybacks and invest more in developing alternative energy and reducing gasoline prices. They said their constituents were suffering and increasingly upset with oil companies over higher prices.                                                                                                                                                                                                                                  , Last week, Mr. Biden said some oil companies had increased production but added that “too many companies aren’t doing their part and are choosing to make extraordinary profits and without making additional investment to help with supply.”                                                                                                                                                                                                                                                                     , The outrage about oil company profits is not unusual. Politicians often criticize the energy industry for profiteering when gas prices surge, and then quietly drop their complaints when prices fall back. Over the last 15 years, oil and gas prices have moved up and down in three big cycles.                                                                                                                                                                                                                 , Most recently, energy demand quickly recovered from the lull of the early pandemic as vaccines became widely available and a crush of the infections receded. But global oil production has not completely returned to prepandemic levels. U.S. production is just shy of 12 million barrels a day, roughly a million short of the record set just before the pandemic. With oil companies adding rigs, the Energy Department expects U.S. production will surpass 13 million barrels next year.                   , While Mr. Biden urges oil companies to expand production, Wall Street investors are telling them to be more cautious because they don’t want companies to drill up a storm when prices are high only to lose money when prices sink again. That is what happened between 2011 and 2015, leading to scores of bankruptcies.                                                                                                                                                                                         , Right now, oil companies are making record profits. Exxon Mobil said this week that its profits in the first three months of the year could total $11 billion, the most the company has made in a quarter since 2008, when the price of a barrel of oil topped $140.                                                                                                                                                                                                                                               , Exxon has cut spending and its work force in recent years, even while increasing production in the Permian Basin, which straddles Texas and New Mexico, and off the coast of Guyana. Darren Woods, the company’s chief executive and one of the witnesses at the Wednesday hearing, has insisted that Exxon is working to reduce its greenhouse gas emissions while meeting the country’s energy needs but that it is not responsible for rising prices.                                                           , “The uncertainty of supply in a tight market with growing demand leads to significant price volatility — which is what we are seeing today,” Mr. Woods told the committee.                                                                                                                                                                                                                                                                                                                                         , Scott D. Sheffield, chief executive of Pioneer Natural Resources, a big Texas producer, said his company and others could do only so much to increase production quickly.                                                                                                                                                                                                                                                                                                                                          , “I understand the desire to find a quick fix for the recent spike in gasoline prices,” he said, “but neither Pioneer nor any other U.S. producer can increase production overnight by turning on a tap.” He noted that shortages of manpower and drilling equipment, and inflationary pressures on oil services, hampered production increases.                                                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/04/06/business/economy-news-oil-russia </td>
   <td style="text-align:left;"> 2022-04-06 20:08:40 </td>
   <td style="text-align:left;"> Latest Economy, Inflation and Business News: Live Updates - The New York Times </td>
   <td style="text-align:left;"> Notes from the March meeting, at which it raised rates by a quarter of a percentage point, showed officials gearing up to pull back economic support quickly as they try to tame inflation.                                                                                                                                                                                                                                                                                                                                                                                                                                , Follow our latest coverage of business, markets and economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Minutes from the Federal Reserve’s March meeting showed that central bankers were preparing to shrink their portfolio of bond holdings imminently while raising interest rates “expeditiously,” as the central bank tries to cool off the economy and rapid inflation.                                                                                                                                                                                                                                                                                                                                                     , Fed officials are making money more expensive to borrow and spend in a bid to slow shopping and business investment, hoping that weaker demand will help to tame prices, which are now climbing at the fastest pace in four decades.                                                                                                                                                                                                                                                                                                                                                                                       , Central bankers raised interest rates by a quarter of a percentage point in March, their first increase since 2018 — and the minutes showed that “many” officials would have preferred an even bigger rate move and were held back only by uncertainty tied to Russia’s invasion of Ukraine. Markets now expect the Fed to make half-point increases in May and possibly June, even as they begin to withdraw additional support from the economy by shrinking their balance sheet.                                                                                                                                        , The balance sheet stands at nearly $9 trillion — swollen by pandemic response policies — and Fed officials plan to shrink it by allowing some of their government-backed bond holdings to expire starting as soon as May, the minutes showed. That will help to further push up interest rates, potentially leading to slower growth, more muted hiring and weaker wage increases. Eventually, the theory goes, the chain reaction should help to slow inflation. “They’re very resolute in fighting inflation and moving it lower,” said Kathy Bostjancic, chief U.S. economist at Oxford Economics. “They are concerned.”, While central bankers were hesitant to react to rapid inflation last year, hoping it would prove “transitory” and fade quickly, those expectations have been dashed. Price increases remain rapid, and officials are watching warily for signs that they might turn more permanent.                                                                                                                                                                                                                                                                                                                                        , “All participants underscored the need to remain attentive to the risks of further upward pressure on inflation and longer-run inflation expectations,” the minutes showed.                                                                                                                                                                                                                                                                                                                                                                                                                                                , Now, officials are trying to cool off the economy as it is growing quickly and the job market is rapidly improving. Employers added 431,000 jobs in March, wages are climbing swiftly, and the unemployment rate is just about matching the 50-year low that prevailed before the pandemic.                                                                                                                                                                                                                                                                                                                                , Central bankers are hoping that the strong job market will help them slow the economy without tipping it into an outright recession. That will be a challenge, given the Fed’s blunt policy tools, a reality that officials have acknowledged.                                                                                                                                                                                                                                                                                                                                                                             , At the same time, Fed officials are worried that if they do not respond vigorously to high inflation, consumers and businesses may come to expect persistently higher prices. That could perpetuate quick price increases and make wrestling them under control even more painful.                                                                                                                                                                                                                                                                                                                                         , “It is of paramount importance to get inflation down,” Lael Brainard, a Fed governor who is the nominee to be the central bank’s vice chair, said on Tuesday. “Accordingly, the committee will continue tightening monetary policy methodically through a series of interest rate increases and by starting to reduce the balance sheet at a rapid pace as soon as our May meeting.”                                                                                                                                                                                                                                       , Ms. Brainard’s statement that balance sheet shrinking could happen “rapidly” caught markets by surprise, sending stocks lower and rates on bonds higher. Investors also focused their attention on the minutes released on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                      , The notes from the March meeting provided more details about what the balance sheet process might look like. Fed officials are coalescing around a plan to slow their reinvestment of securities, the minutes showed, most likely capping the monthly shrinking at $60 billion for Treasury securities and $35 billion for mortgage-backed debt.                                                                                                                                                                                                                                                                           , That would be about twice the maximum pace the Fed set when it shrank its balance sheet between 2017 and 2019, confirming the signal policymakers have been giving in recent weeks that the plan could proceed much more quickly this time around.                                                                                                                                                                                                                                                                                                                                                                         , Officials “generally agreed that the caps could be phased in over a period of three months or modestly longer if market conditions warrant,” the minutes showed, while outright sales of mortgage-backed securities might be up for consideration “after balance sheet runoff was well underway.”                                                                                                                                                                                                                                                                                                                          , Besides confirming a relatively quick pace of balance sheet drawdown and reaffirming Ms. Brainard’s signal that balance sheet shrinking could begin imminently, the minutes showed that “many” meeting participants “would have preferred a 50 basis point increase in the target range for the federal funds rate at this meeting.”                                                                                                                                                                                                                                                                                       , While they held off on a bigger increase while faced with uncertainty tied to Russia’s invasion of Ukraine, officials signaled that increases above a quarter-point could be appropriate if inflation remained elevated.                                                                                                                                                                                                                                                                                                                                                                                                   , And officials pointed to signs that rapid price increases could last.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “Many participants indicated that their business contacts continued to report substantial increases in wages and input prices that were being passed through into higher prices to their customers without any significant decrease in demand,” the minutes showed.                                                                                                                                                                                                                                                                                                                                                        , Factors that Fed officials thought could cause inflation to persist included “strong aggregate demand, significant increases in energy and commodity prices, and supply chain disruptions that were likely to require a lengthy period to resolve,” the minutes said.                                                                                                                                                                                                                                                                                                                                                      , In all, the discussion in the minutes showed growing nervousness about the pace and persistence of price increases.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , “The overall tone of the minutes showed substantially more concern among policymakers around upside risks” to inflation and less fretting about growth, economists at Morgan Stanley wrote in reaction to the minutes.                                                                                                                                                                                                                                                                                                                                                                                                     , By Coral Murphy Marcos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , April 5
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , April 6
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , 4,460
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , 4,480
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , 4,500
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , 4,520
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , 4,540
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , 4,560
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , 4,580
					                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , By: Ella Koeze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Stocks on Wall Street fell on Wednesday, notching a second day of losses, as the Federal Reserve released details of its March meeting that showed several central bank officials support plans to pull back on support for the economy quickly. The minutes showed that central bankers were preparing to shrink their portfolio of bond holdings imminently while raising interest rates “expeditiously,” two policies that will make money more expensive to borrow.                                                                                                                                                    , The S&amp;P 500 fell 1 percent on Wednesday, adding to a loss of about 1.3 percent on Tuesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , In March, the central bank raised its benchmark interest rate for the first time since it was slashed in early 2020, and projected six more increases this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , But that outlook might already be changing. On Tuesday, Lael Brainard, a Federal Reserve governor, suggested the Fed was willing to pull back its economic support even faster if the circumstances demand it.                                                                                                                                                                                                                                                                                                                                                                                                             , “Currently, inflation is much too high and is subject to upside risks,” Ms. Brainard said in a speech. “The committee is prepared to take stronger action if indicators of inflation and inflation expectations indicate that such action is warranted,” she said, referring to the panel at the Fed that sets rates.                                                                                                                                                                                                                                                                                                      , And the minutes released on Wednesday showed that “many” officials would have preferred an even bigger rate increase and were stalled only by uncertainty tied to Russia’s invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                            , The Fed is debating policy changes as consumer prices rise at their fastest pace in 40 years, with the latest inflation gauge indicating prices rose 6.4 percent over the past year in February.                                                                                                                                                                                                                                                                                                                                                                                                                           , The recent retreat in stocks has come as government bond yields, a proxy for investor expectations about interest rates, have jumped. The yield on 10-year Treasury notes is now at its highest level since early 2019, and on Wednesday climbed about five basis points, or 0.05 percentage points, to about 2.6 percent.                                                                                                                                                                                                                                                                                                 , Oil prices fell after Bloomberg News reported that the International Energy Agency would join the United States in releasing oil from emergency reserves. West Texas Intermediate, the U.S. benchmark crude, was down about 5.6 percent to about $96.23 a barrel.                                                                                                                                                                                                                                                                                                                                                          , In Europe, stock indexes fell sharply. The Stoxx Europe 600 dropped 1.5 percent. On Tuesday, the European Commission proposed banning coal imports from Russia, which account for 47 percent of coal coming into the European Union, as part of a new set of sanctions. European leaders met on Wednesday to discuss the proposal, and deliberations were extended by a day.                                                                                                                                                                                                                                               , By Stacy Cowley                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Sensitive information for more than eight million users of Cash App Investing — a stock trading app run by Block, the owner of the Square payments system — was exposed when a former employee downloaded corporate reports after leaving the company.                                                                                                                                                                                                                                                                                                                                                                     , Block revealed the data exposure in a regulatory filing on Monday, and said it was contacting the affected customers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “Upon discovery, we took steps to remediate this issue and launched an investigation with the help of a leading forensics firm,” Fiona Lee, a Block spokeswoman, said. “We know how these reports were accessed, and we have notified law enforcement.”                                                                                                                                                                                                                                                                                                                                                                    , The exposed data involved only users of Cash App’s investing product, not the person-to-person payment service with roughly 44 million users, the company said.                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The information was retrieved by the former employee in December and included customers’ names and Cash App brokerage account numbers. For some customers, it also included their portfolio value, their holdings and certain trading activity. The information did not include user names, passwords, Social Security numbers and other personally identifiable details, Block said in its filing.                                                                                                                                                                                                                        , Companies that deal with financial data typically have strong internal systems to protect that information. Ms. Lee declined to comment specifically on how the former employee gained access and whether the company had made adjustments since the breach was discovered.                                                                                                                                                                                                                                                                                                                                                , “We continue to review and strengthen administrative and technical safeguards to protect information,” she said in a written statement.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Financial companies that are not banks typically face far less scrutiny from regulators about their security systems than tightly regulated banks. Square obtained a banking charter last year for Square Financial Services, which allows it to offer some banking services, but that unit operates independently from Cash App.                                                                                                                                                                                                                                                                                          , The idea that a former employee was somehow able to sneak in meant something went badly awry. “Taking customers’ data and security seriously would require securing external access to employees’ accounts and disabling that access upon termination, preferably before the employee leaves,” said James McQuiggan, a security expert at KnowBe4, a cybersecurity training company.                                                                                                                                                                                                                                       , Cash App is one of the most popular person-to-person payment systems in the United States, trailing Zelle and PayPal’s Venmo. It has grown to include debit cards, merchant payment tools and a tax-preparation system that Block bought from Credit Karma. The data breach did not affect users of any products other than the investing app, Block said.                                                                                                                                                                                                                                                                 , Cash App Investing customers said in a Reddit forum that they had received emailed notices on Monday about the incident. Many were irked by the breach.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , “Now the question is whether or not our names and accounts numbers were leaked to the dark web?” one user wrote.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By Stacy Cowley and Tara Siegel Bernard                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , More than seven million borrowers who have defaulted on their federal student loans will have their loans restored to good standing, the Education Department said on Wednesday — a boon that the Biden administration included in its four-month payment moratorium extension.                                                                                                                                                                                                                                                                                                                                            , About one in five federal borrowers has a loan in default, meaning their payments were at least 270 days, or around nine months, overdue. And once a loan enters default, it can be nearly impossible to get back out again.                                                                                                                                                                                                                                                                                                                                                                                               , “It’s like quicksand,” said Sarah Sattelmeyer, a higher-education project director at New America, a think tank.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Program rules often prevent defaulted borrowers, especially those who have defaulted multiple times, from starting to pay again under the federal loan program’s usual payment plans. Giving those borrowers a fresh start is “a really big deal,” Ms. Sattelmeyer said.                                                                                                                                                                                                                                                                                                                                                   , Student loans have been effectively frozen for tens of millions of borrowers since the start of the pandemic. The pause has allowed borrowers to stop making payments, prevented interest from accruing and halted collection efforts. And the federal government previously said that delinquent borrowers — those whose payments, before the pandemic, were a few months overdue — would be made current before the pause ended.                                                                                                                                                                                         , Officials urged delinquent borrowers to use that as an opportunity to get into more manageable payment plans, like those based on their income. But because of their defaulted status, borrowers who are the furthest behind were generally not eligible without meeting other requirements first.                                                                                                                                                                                                                                                                                                                         , Education Secretary Miguel Cardona said the department would use the extension of the moratorium to “continue our preparations to give borrowers a fresh start and to ensure that all borrowers have access to repayment plans that meet their financial situations and needs.” An Education Department representative said that further details about the treatment of defaulted borrowers would be posted “in the coming weeks” on StudentAid.gov.                                                                                                                                                                       , But major obstacles loom. For instance, the loan servicers, the vendors hired by the government to collect on its $1.6 trillion in federal student loans, have no idea how this planned clean slate will work.                                                                                                                                                                                                                                                                                                                                                                                                             , The Education Department has given its servicers “zero guidance” about the process, said Scott Buchanan, the executive director of the Student Loan Servicing Alliance, a trade group. “I can’t tell you anything about how formerly defaulted borrowers would be treated — or even who might be eligible — because it’s totally unclear.”                                                                                                                                                                                                                                                                                 , He added: “It’s unclear if they even have an actually operational plan about how they will do it or what they even can do under the law.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Ms. Sattelmeyer said the administration’s planned new date for restarting student loan payments — Aug. 31 — did not give the department, or its contractors, much time to make arrangements.                                                                                                                                                                                                                                                                                                                                                                                                                               , “There’s a lot of decisions that need to be made over the next couple of months to make sure that borrowers are protected and that this transition supports them,” she said. “We don’t want people to re-enter a payments system that didn’t serve them well the first time around.”                                                                                                                                                                                                                                                                                                                                       , By Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Federal Reserve says it has barred six former bank employees from working in the industry because they wrongly received money from a coronavirus relief program that has been plagued by fraud.                                                                                                                                                                                                                                                                                                                                                                                                                        , The penalties on Tuesday were the first meted out by the Fed for fraud relating to coronavirus stimulus efforts and involved money obtained from the Economic Injury Disaster Loan program, which became a prime target for misuse.                                                                                                                                                                                                                                                                                                                                                                                        , Two of the workers were employed by Merrill Lynch Wealth Management. Autumn Jordan, who worked in Jacksonville, Fla., gave false information to get an advance of $9,000 and used the money for personal expenses, the Fed said in a statement. Manuel F. Pinazo, who was based in Miami, received a $20,000 loan based on a bogus application, the regulator said.                                                                                                                                                                                                                                                        , Mr. Pinazo and Ms. Jordan declined to comment. Both were fired in 2020, according to the Financial Industry Regulatory Authority. A spokesman for Bank of America, Merrill’s parent company, declined to comment.                                                                                                                                                                                                                                                                                                                                                                                                          , The Fed also barred four former employees of Regions Bank, which is based in Birmingham, Ala.: Dedryck O. Carson, Wendy Rodriguez Legon, Michael T. Lemley and Tracy L. Mallory. The regulator said they had wrongfully received loans or grants ranging from $10,000 to $21,600. The four did not respond to emails or phone calls to listings under their names.                                                                                                                                                                                                                                                         , “This type of activity is contrary to Regions’ own internal policies, which include our code of conduct and business ethics,” the bank said in a statement. “We appreciate the work of the Federal Reserve in protecting the integrity of the financial system.”                                                                                                                                                                                                                                                                                                                                                           , The disaster loan program dates to the early days of the Small Business Administration in the 1950s, but was hurriedly expanded under the CARES Act to allow businesses to get up to $10,000 in a grant even if they were ultimately denied one of the program’s loans. The agency’s inspector general found that the program had handed out more than $4 billion in fraudulent payments related to the grant program to self-employed people, while nearly $3.7 billion went to recipients who were not permitted to receive federal funds.                                                                               , The Small Business Administration said in a statement on Wednesday that it had “worked closely with the inspector general to identify and address all areas of concern, including  referrals to law enforcement where appropriate.”                                                                                                                                                                                                                                                                                                                                                                                        , By Alan Rappeport and Katie Rogers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , WASHINGTON — Treasury Secretary Janet L. Yellen said on Wednesday that the United States would continue taking steps to cut Russia off from the global financial system in response to its invasion of Ukraine and argued that the sanctions already imposed had taken a severe toll on the Russian economy.                                                                                                                                                                                                                                                                                                               , She addressed the House Financial Services Committee as the United States rolled out a new array of sanctions on Russian banks and state-owned enterprises and on the adult children of President Vladimir V. Putin. The White House also announced a ban on Americans making new investments in Russia no matter where those investors are based.                                                                                                                                                                                                                                                                         , “Our goal from the outset has been to impose maximum pain on Russia, while to the best of our ability shielding the United States and our partners from undue economic harm,” Ms. Yellen told lawmakers.                                                                                                                                                                                                                                                                                                                                                                                                                   , The measures introduced on Wednesday included “full blocking” sanctions against Sberbank, the largest financial institution in Russia, and Alfa Bank, one of the country’s largest privately owned banks.                                                                                                                                                                                                                                                                                                                                                                                                                  , Sberbank is the main artery in the Russian financial system and holds over a third of the country’s financial assets. In February, the Treasury announced limited sanctions against Sberbank, but Wednesday’s sanctions, a senior Biden administration official said, will effectively freeze relations between the bank and the U.S. financial system.                                                                                                                                                                                                                                                                    , The administration also announced sanctions against two adult daughters of Mr. Putin: Katerina Tikhonova and Maria Putina, who has been living under an assumed name, Maria Vorontsova. Others connected to Russian officials with close ties to Mr. Putin will also face sanctions, including the wife and daughter of Russia’s foreign minister, Sergey Lavrov, and members of Russia’s security council, including former Prime Minister Dmitri Medvedev. The official said those people would be effectively cut off from the U.S. banking system and any assets held in the United States.                            , President Biden said on Wednesday that the new sanctions would deal another blow to the Russian economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , “The sense of brutality and inhumanity, left for all the world to see unapologetically,” Mr. Biden said, describing Russia’s actions as war crimes. “Responsible nations have to come together to hold these perpetrators accountable, and together with our allies and our partners we’re going to keep raising the economic costs and ratchet up the pain for Putin and further increase Russia’s economic isolation.”                                                                                                                                                                                                   , Experts suggested that the latest round of sanctions were unlikely to compel Mr. Putin to change course. Hundreds of American businesses have pulled out of Russia in recent weeks, making new investments unlikely.                                                                                                                                                                                                                                                                                                                                                                                                       , “The asset freezes on the additional banks aren’t nothing, but this isn’t the most significant tranche we’ve seen to date,” said Daniel Tannebaum, a partner at Oliver Wyman who advises banks on sanctions.                                                                                                                                                                                                                                                                                                                                                                                                               , Other American agencies are joining the effort to exert pressure on Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , In a news conference on Wednesday, officials from the Justice Department and the F.B.I. also announced a series of actions and criminal charges against Russians, including the takedown of a Russian marketplace on the dark web and a botnet, or a network of hijacked devices infected with malware, that is controlled by the country’s military intelligence agency.                                                                                                                                                                                                                                                  , Justice Department officials also celebrated the seizing of the Tango, a superyacht owned by the Russian oligarch Viktor F. Vekselberg, and charged a Russian banker, Konstantin Malofeev, with conspiring to violate U.S. sanctions. Mr. Malofeev is one of Russia’s most influential magnates and among the most prominent conservatives in the country’s Kremlin-allied elite. (The indictment renders his surname as Malofeyev.)                                                                                                                                                                                       , At the hearing, Ms. Yellen told lawmakers that she believed Russia should be further isolated from the geopolitical system, including being shut out of international gatherings such as the Group of 20 meetings this year, and should be denounced at this month’s meetings of the International Monetary Fund and the World Bank. She added that the United States might not participate in some G20 meetings that are being held in Indonesia this year if Russians attended.                                                                                                                                          , Ms. Yellen, whose department has been developing many of the punitive economic measures, rebutted criticism that the penalties leveled so far had not been effective, in part because there are some exceptions to allow Russia to sell energy.                                                                                                                                                                                                                                                                                                                                                                            , “Unfortunately, many of our European partners remain heavily dependent on Russian natural gas, as well as oil, and they are committed to making the transition away from that dependence as rapidly as possible,” Ms. Yellen said. The Treasury secretary downplayed the rebound of Russia’s currency, the ruble, which cratered after the sanctions were imposed in February but has since regained its value. Ms. Yellen said that the ruble’s apparent recovery was the result of currency controls that Russia had put in place and that its exchange rate did not reflect its true value.                             , “The Russian economy is really reeling from the sanctions that we put in place,” Ms. Yellen said, adding, “You shouldn’t really infer anything from the value of the currency.”                                                                                                                                                                                                                                                                                                                                                                                                                                            , Ms. Yellen argued that Russia’s invasion of Ukraine underscored the need for the United States and other countries to invest in becoming energy independent so that “dictators” did not control the price and availability of global energy supplies. She added that moving away from fossil fuels and toward renewable energy should be a priority.                                                                                                                                                                                                                                                                       , The Treasury Department has been trying to create sanctions in a way that minimizes the economic blowback on the United States. However, Ms. Yellen acknowledged that inflation, which was already elevated, would now be “escalated.” She pointed to higher prices for energy, food and metals.                                                                                                                                                                                                                                                                                                                           , “We think it’s a price that’s important to pay to punish Russia for what it’s doing in Ukraine,” Ms. Yellen said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , As the crisis in Ukraine worsens, the United States and Europe have come under increasing pressure to enact a broader ban on Russian energy purchases. Ms. Yellen warned that doing so could have painful consequences on the United States and its allies.                                                                                                                                                                                                                                                                                                                                                                , “We’re likely to see skyrocketing prices, if we did put a complete ban on oil,” Ms. Yellen said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Treasury secretary acknowledged that inflation, which has become a political problem for Mr. Biden and his party ahead of the November elections, has persisted longer than the White House anticipated. She pointed to pandemic-related supply problems, including shortages of semiconductors that are limiting supplies of new cars and causing prices to rise.                                                                                                                                                                                                                                                     , Still, Ms. Yellen made the case that the economy was better off than some critics had suggested. She noted that wages for low-income workers, for instance, were outpacing price increases in the United States.                                                                                                                                                                                                                                                                                                                                                                                                           , Zach Montague contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , By Eshe Nelson and Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Russia’s finance ministry said on Wednesday that it had used rubles to pay about $650 million in dollar-denominated debt obligations after the U.S. government blocked access to dollars held in American banks. The move pushed the country closer to a default.                                                                                                                                                                                                                                                                                                                                                          , Credit rating agencies have indicated that payments in a currency different from the one the debt was sold in would count as a default once the grace period expired. Russia’s debt payments that were due on Monday have a 30-day grace period and had no provision for repayment in any currency other than dollars. It would be Russia’s first default on foreign currency debt in more than a century.                                                                                                                                                                                                                 , On Monday, the U.S. Treasury Department tightened its restrictions on Russian financial transactions and said it had blocked Russia from making debt payments using dollars held in American banks. The department said it wanted to force Russia to either deplete the foreign currency reserves it has in the country or spend dollars from new revenue to avoid a default.                                                                                                                                                                                                                                              , Last week, Russia bought back in rubles three-quarters of the bond that matured on Monday, which was worth about $2 billion. But it said $552 million, plus the final interest payment, still needed to be paid. A coupon payment for a different bond was also due on Monday.                                                                                                                                                                                                                                                                                                                                             , Russia had previously warned that if foreign banks didn’t follow its orders to make bond payments because of the sanctions, then the debts would be repaid in rubles. On Wednesday, the finance ministry said that was what had happened “due to the unfriendly actions of the U.S. Treasury.”                                                                                                                                                                                                                                                                                                                             , Since Russia invaded Ukraine in late February and sanctions were imposed, routine debt payments have been put under a microscope. Russia had avoided default on its foreign currency government bonds by paying the debt in dollars with the approval of the U.S. government. But amid growing calls for President Vladimir V. Putin to face a “war crime trial,” the U.S. tightened its sanctions.                                                                                                                                                                                                                        , JPMorgan Chase was not given permission by the U.S. authorities to process Monday’s bond payment, according to a person familiar with the situation who spoke on condition of anonymity because of the sensitivity of the situation. It had previously been cleared to handle five other payments after sanctions were imposed last month, the person said.                                                                                                                                                                                                                                                                , On Wednesday, Russia said it had transferred the payments to the country’s National Settlement Depository in rubles and considered its obligations fulfilled “in full.” But sanctions make it difficult for Western lenders to access the rubles held in Russian bank accounts. The finance ministry added that if Russia were allowed to access its internationally held foreign exchange reserves, then the rubles could be converted to dollars.                                                                                                                                                                        , By Matina Stevis-Gridneff                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , BRUSSELS — European Union officials were working on Wednesday to iron out technical details in a new raft of sanctions against Russia, which include a ban on Russian coal, before seeking the approval of each member state of the bloc.                                                                                                                                                                                                                                                                                                                                                                                  , The lengthy deliberations among E.U. ambassadors and their staffs were expected to continue into Thursday and to conclude with the formal approval of the sanctions, the fifth round imposed since Russia’s invasion of Ukraine.                                                                                                                                                                                                                                                                                                                                                                                           , Still, the talks have shown that pushing beyond banning Russian coal, to include oil and gas, will be a very difficult undertaking.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Germany, Austria and Hungary have long voiced opposition to banning Russian natural gas. And diplomats briefed on Wednesday’s ambassadorial talks said that Hungary had raised the bar, asking that European Union leaders convene to debate any further energy-related sanctions.                                                                                                                                                                                                                                                                                                                                         , That demand has raised concerns among E.U. diplomats and officials that Hungary’s prime minister, Viktor Orban, who was re-elected to a fourth term on Sunday and maintains close ties to President Vladimir V. Putin, will become an even tougher negotiator when it comes to imposing more sanctions against Russia. Spokespeople for the Hungarian permanent representation to the European Union did not immediately respond to a written request for comment.                                                                                                                                                         , The new Hungarian position came as Mr. Orban broke ranks with the rest of the bloc and said that Hungary would be prepared to pay for Russian energy imports in rubles as Mr. Putin has demanded. Doing so would shatter an E.U. consensus not to capitulate to the demand because it would provide Russia with currency.                                                                                                                                                                                                                                                                                                  , Currency has been a key target of E.U. sanctions against the Russian central bank, which limit Mr. Putin’s ability to liquidate assets like gold and bonds to generate rubles to fund the war in Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                                  , After talks among E.U. ambassadors on Wednesday, diplomats said that Germany and other countries that had earlier resisted a ban on Russian coal had secured a three-month delay in enforcing the measure, which would allow them to complete current orders and wind down existing contracts.                                                                                                                                                                                                                                                                                                                             , Other technical issues to be worked out included details of a ban on Russian and Russian-operated vessels from E.U. ports, another measure that the European Union is set to adopt.                                                                                                                                                                                                                                                                                                                                                                                                                                        , Once the E.U. ambassadors are content with the technical work on the new package of punishments, they can take the measures to their governments in 27 capitals for final approval. That process is completed via email. Foreign ministers and other high-level officials are not required to meet or sign documents in person.                                                                                                                                                                                                                                                                                            , By Melissa Eddy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , European leaders, seeking to punish Russia for its role in suspected atrocities carried out in Ukraine, are zeroing in on a ban on coal as the imported energy source that would be the easiest to replace.                                                                                                                                                                                                                                                                                                                                                                                                                , Deliberations over the ban and other sanctions on Wednesday were set to continue into Thursday, and European Union officials and diplomats anticipated the measures would be approved by then. The process reflected the challenges of reaching agreement among all 27 member nations on the penalties, which would also include banning Russian ships from E.U. ports.                                                                                                                                                                                                                                                    , If approved, the sanctions would be the harshest enforced by the bloc since President Vladimir V. Putin of Russia launched the invasion of Ukraine six weeks ago. Sanctions need to be approved by all member states.                                                                                                                                                                                                                                                                                                                                                                                                      , Though the European Union depends on Russian coal, the bloc could replace it more easily with imports from other countries than it could replace natural gas and oil.                                                                                                                                                                                                                                                                                                                                                                                                                                                      , But banning coal from Russia could send energy prices soaring for European consumers, given the existing shortages in the bloc, according to Rystad Energy, the consulting firm. Carlos Torres Diaz, a senior vice president at Rystad, called the potential sanctions “a double-edged sword.”                                                                                                                                                                                                                                                                                                                             , Imports from Russia accounted for 47 percent of coal coming into the European Union in 2019, according to the European Union’s statistics office, Eurostat, making the country the most important supplier of the fuel. That amounts to 4 billion euros worth of coal annually, Ursula von der Leyen, the European Commission president, said.                                                                                                                                                                                                                                                                             , Each member state has different energy needs, and among those most dependent on Russian energy overall is Germany, the bloc’s largest economy. Roughly half of all coal that Germany imports comes from Russia, last year totaling €2.2 billion, according to government figures. Most is used to generate electricity and power Germany’s steel industry.                                                                                                                                                                                                                                                                 , Lignite, or brown coal, the only fossil fuel that is still mined in Germany, is burned to generate power. It is also the dirtiest fossil fuel, lending urgency to efforts to cease burning coal. But 2021 proved to be less windy than expected, hurting the country’s wind power efforts, and led to a nearly 5 percent increase in coal-generated power for the year.                                                                                                                                                                                                                                                    , Chancellor Olaf Scholz’s government had laid out plans last year for the country to quit coal by the start of the next decade, and in the past month, the vice chancellor and economy minister, Robert Habeck, has said Germany will aim to wean itself off Russian coal by the end of the summer.                                                                                                                                                                                                                                                                                                                         , “How we will carry out a coal embargo is well prepared,” Mr. Habeck said Wednesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Diplomats in Brussels said Germany and other countries that previously resisted a ban on Russian coal had secured a three-month hiatus, which would allow them to complete current orders and wind down existing contracts before enforcing the measure.                                                                                                                                                                                                                                                                                                                                                                   , German companies have already renegotiated contracts with other countries that export coal, Mr. Habeck said. But shipments that have already been ordered and are underway from Russia would not be stopped or turned back, he added. “If we turned those ships back, then we could face a shortage,” he told reporters in Berlin.                                                                                                                                                                                                                                                                                         , Coal from the United States, Colombia and South Africa could help plug the gap left by cutting out imports from Russia, according to the German Coal Importer Association, an industry group representing companies that depend on coal supplies from abroad.                                                                                                                                                                                                                                                                                                                                                              , In a telephone call on Wednesday, Mr. Scholz and the president of Colombia, Iván Duque Márquez, discussed the war in Ukraine and energy, the chancellor’s office said.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Australia provided nearly one-third of the European Union’s coal imports in 2019. Australian markets have already reported a surge in their coal prices, as companies in Europe have turned to them to inquire about fuel.                                                                                                                                                                                                                                                                                                                                                                                                 , Poland is the E.U. country that still relies most heavily on coal. While much of the country’s coal is mined domestically, roughly 20 percent was imported from Russia last year.                                                                                                                                                                                                                                                                                                                                                                                                                                          , Last month, Poland’s prime minister, Mateusz Morawiecki, proposed legislation to ban imports of coal from Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Cutting off Russia’s oil and natural gas will prove to be much more difficult. Germany has already reduced its dependence on gas from Russia by 15 percent in the first three months of the year, according to Mr. Habeck. But industry leaders have warned against imposing sanctions on Russian natural gas, saying it could lead to substantial job losses in the chemical, mining and pharmaceutical sectors.                                                                                                                                                                                                          , Mr. Habeck presented draft legislation for speeding up Germany’s expansion of renewable energy, focused on generating more through wind and solar power.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , But it will take several years before new terminals are built that would allow for liquefied natural gas to arrive by ship, offering a replacement for Russian gas coming via pipeline. And even if the approval processes are streamlined, it could take years before the terminals are able to replace the nearly 22 percent of Germany’s energy mix that comes from natural gas.                                                                                                                                                                                                                                        , Matina Stevis-Gridneff contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Annie Karni and Clifford Krauss                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , WASHINGTON — Amid a swirl of partisan finger-pointing on who is responsible for rising energy prices, executives of six large oil and gas companies defended themselves on Wednesday against criticisms that they are seeking to boost corporate profits by refusing to produce more oil and gas.                                                                                                                                                                                                                                                                                                                          , They appeared before a House committee as high gasoline prices have become a central issue ahead of the midterm elections in November. Republicans have blamed Biden administration regulations and environmental policies for shortfalls in energy production, while Democrats have questioned why companies could not lower gasoline prices as oil prices have eased somewhat since a spike after Russia’s invasion of Ukraine.                                                                                                                                                                                          , Trying to duck the political debate, the executives said they were not engaging in price gouging and were merely responding to global commodity prices that were out of their control. They also said they were working to shift to cleaner energy.                                                                                                                                                                                                                                                                                                                                                                        , “We are here to get answers from big oil companies on why they are ripping off the American people,” said Representative Frank Pallone Jr., a New Jersey Democrat and chair of the Energy and Commerce Committee, during the hearing. “At a time of record profits, Big Oil is refusing to increase production.”                                                                                                                                                                                                                                                                                                           , The oil executives took exception to the accusations by Democrats, but remained low key in their responses.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , “Because oil is a global commodity, Shell does not set or control the price of crude oil,” Gretchen H. Watkins, the president of Shell USA, told the committee in her prepared remarks. “Today’s crisis and the pressure on hydrocarbon supplies and prices reveal the urgent need to accelerate the energy transition.”                                                                                                                                                                                                                                                                                                   , Michael Wirth, Chevron’s chief executive, insisted that the company had “no tolerance for price gouging.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , With his approval ratings falling to a new low as inflation has stayed high for months, President Biden has struggled to explain the rise in gas prices to the American people. In an attempt to capitalize on broad support for crippling sanctions on Russia, the administration has tried to characterize the recent uptick in gas prices as “Putin’s price hike.”                                                                                                                                                                                                                                                      , But Republicans have tried to hang the increase around the president’s neck, noting that the price of gas has been on the rise for a year, long before Mr. Putin’s invasion of Ukraine. They have used anxiety about higher gas prices as their main argument to voters about the need for a change in leadership.                                                                                                                                                                                                                                                                                                         , Republicans have hammered Mr. Biden for his cancellation of permits for the Keystone XL oil pipeline, as well as pauses on new leases for oil wells on federal lands. White House officials have tried to explain that neither policy is responsible for the rise in gas prices.                                                                                                                                                                                                                                                                                                                                           , In reality, the loosening of pandemic restrictions has increased demand for gas when supply is not rising quickly enough. Both supply and demand are being driven by factors that are out of the control of Mr. Biden and Congress.                                                                                                                                                                                                                                                                                                                                                                                        , Still, the attacks appear to be working. In a recent Quinnipiac University poll, only 24 percent of respondents said they thought the rise in gas prices was a result of the war in Ukraine, with more Americans blaming the Biden administration’s policies.                                                                                                                                                                                                                                                                                                                                                              , A recent NBC News poll showed that despite broad support for banning Russian oil imports, the majority of Americans were still worried about gas prices. Polls have shown Mr. Biden’s approval ratings to be near the lowest of his presidency, at about 40 percent, suggesting that Americans hold him responsible even if they support some of his foreign policies.                                                                                                                                                                                                                                                     , Some Democrats facing competitive races in November have pushed to suspend the federal gas tax through the end of the year. But Republicans quickly shot down the proposal, calling it a desperate attempt to appeal to voters.                                                                                                                                                                                                                                                                                                                                                                                            , Progressives have also tried to use the spike in energy and gas prices to push for investments in clean energy in order to reduce the reliance on foreign authoritarian leaders and oil companies. The United Nations Intergovernmental Panel on Climate Change said in a report published this week that the world needs to significantly accelerate efforts to slash greenhouse gas emissions from oil and other fossil fuels in order to limit global warming to 1.5 degrees Celsius, or 2.7 degrees Fahrenheit.                                                                                                        , Republicans at Wednesday’s hearing sought to capitalize on Mr. Biden’s weak position.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “This is not the Putin price hike,” said Representative Cathy McMorris Rodgers, Republican of Washington. “This is the Biden price hike. It’s been a steady climb since he took office.” She said Democrats were seeking another scapegoat by blaming the oil industry.                                                                                                                                                                                                                                                                                                                                                    , Ms. Rodgers and other Republicans criticized what they called administration efforts to ease oil sanctions on Venezuela and Iran to boost global oil supplies, as well as the decision to block the Keystone XL pipeline, which would have imported more Canadian production from that country’s oil sands.                                                                                                                                                                                                                                                                                                                , The average price for a gallon of gasoline is roughly $1.30 higher than it was a year ago, moving up in tandem with oil prices, which are now just below $100 a barrel.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Democrats have called on oil executives to suspend dividend increases and stock buybacks and invest more in developing alternative energy and reducing gasoline prices. They said their constituents were suffering and increasingly upset with oil companies over higher prices.                                                                                                                                                                                                                                                                                                                                          , Last week, Mr. Biden said some oil companies had increased production but added that “too many companies aren’t doing their part and are choosing to make extraordinary profits and without making additional investment to help with supply.”                                                                                                                                                                                                                                                                                                                                                                             , The outrage about oil company profits is not unusual. Politicians often criticize the energy industry for profiteering when gas prices surge, and then quietly drop their complaints when prices fall back. Over the last 15 years, oil and gas prices have moved up and down in three big cycles.                                                                                                                                                                                                                                                                                                                         , Most recently, energy demand quickly recovered from the lull of the early pandemic as vaccines became widely available and a crush of the infections receded. But global oil production has not completely returned to prepandemic levels. U.S. production is just shy of 12 million barrels a day, roughly a million short of the record set just before the pandemic. With oil companies adding rigs, the Energy Department expects U.S. production will surpass 13 million barrels next year.                                                                                                                           , While Mr. Biden urges oil companies to expand production, Wall Street investors are telling them to be more cautious because they don’t want companies to drill up a storm when prices are high only to lose money when prices sink again. That is what happened between 2011 and 2015, leading to scores of bankruptcies.                                                                                                                                                                                                                                                                                                 , Right now, oil companies are making record profits. Exxon Mobil said this week that its profits in the first three months of the year could total $11 billion, the most the company has made in a quarter since 2008, when the price of a barrel of oil topped $140.                                                                                                                                                                                                                                                                                                                                                       , Exxon has cut spending and its work force in recent years, even while increasing production in the Permian Basin, which straddles Texas and New Mexico, and off the coast of Guyana. Darren Woods, the company’s chief executive and one of the witnesses at the Wednesday hearing, has insisted that Exxon is working to reduce its greenhouse gas emissions while meeting the country’s energy needs but that it is not responsible for rising prices.                                                                                                                                                                   , “The uncertainty of supply in a tight market with growing demand leads to significant price volatility — which is what we are seeing today,” Mr. Woods told the committee.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Scott D. Sheffield, chief executive of Pioneer Natural Resources, a big Texas producer, said his company and others could do only so much to increase production quickly.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “I understand the desire to find a quick fix for the recent spike in gasoline prices,” he said, “but neither Pioneer nor any other U.S. producer can increase production overnight by turning on a tap.” He noted that shortages of manpower and drilling equipment, and inflationary pressures on oil services, hampered production increases.                                                                                                                                                                                                                                                                            , By Kellen Browning                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , For nearly two years, Jassy StokesOliver crisscrossed the freeways of San Diego late at night, delivering food and dropping off riders as a gig driver for DoorDash, Lyft and Uber. She preferred working late because there was little traffic, and she never felt unsafe.                                                                                                                                                                                                                                                                                                                                                , Then two life-threatening situations hammered home the risks of the business. On a delivery trip last summer, her nephew Keshon, who also worked for DoorDash, was shot twice in the head by a passing driver. The 19-year-old survived, but the attacker has not been found.                                                                                                                                                                                                                                                                                                                                              , Just weeks later, as Ms. StokesOliver, 44, was trying to drop off cigarettes and a 12-pack of soda at a property for DoorDash, a man standing nearby followed her up to the door. As she bent down to leave the package, she saw out of the corner of her eye that he was holding a gun. She pulled out her phone to snap a picture, and he retreated. She hurried back to her car and sped off, with her 10-year-old son in the back seat.                                                                                                                                                                                , “That was the last day I drove for DoorDash — it just made me very uncomfortable,” said Ms. StokesOliver, who later moved to Dubai. “I realized we’re not safe.”                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The danger that Ms. StokesOliver and her nephew faced are stark examples of episodes gathered in a report released Wednesday by a driver advocacy group, Gig Workers Rising. The report said at least 50 gig drivers for companies like Uber, Lyft and DoorDash had been killed while on the job in the United States since 2017.                                                                                                                                                                                                                                                                                          , Much attention has been paid to the risks that ride-hailing passengers might face when entering a stranger’s vehicle, but the drivers’ group and the families of drivers who were killed say they hope the report will highlight a concern that receives less focus: the risk that passengers themselves may pose to drivers.                                                                                                                                                                                                                                                                                              , Though the report relied mostly on public news accounts, it is notable in part because it is the most recent count of violence against drivers since Uber and Lyft released their own safety reports years ago.                                                                                                                                                                                                                                                                                                                                                                                                            , In late 2019, Uber said more than 3,000 people had been sexually assaulted, nine murdered and 58 killed in crashes in 2018 in the United States in its first ever safety report. Uber pledged to release a new report every two years but has not yet released the second. It plans to do so this spring.                                                                                                                                                                                                                                                                                                                  , Lyft’s first safety report was released last year and said about 1,800 people had been sexually assaulted, four killed in physical assaults and about 50 killed in accidents in the United States in 2019.                                                                                                                                                                                                                                                                                                                                                                                                                 , Uber, Lyft and DoorDash said in statements that they had built their platforms with safety in mind, with features like the ability to connect discreetly with people at ADT, the security firm, or to share location information through ride-hailing apps.                                                                                                                                                                                                                                                                                                                                                                , It is hard to compare how dangerous gig driving is with other professions, though the Bureau of Labor Statistics makes some fatal occupational injury tallies public. But Gig Workers Rising argues that the risks of gig work stand out for more than simply the number of deaths.                                                                                                                                                                                                                                                                                                                                        , Because gig drivers are often classified as independent contractors rather than employees, they often receive less support from the companies they work for when something goes wrong, the report said.                                                                                                                                                                                                                                                                                                                                                                                                                    , In some cases, Gig Workers Rising said, families of dead drivers never heard from the companies they drove for, or did not receive death benefits or assistance with insurance claims or funeral services.                                                                                                                                                                                                                                                                                                                                                                                                                 , DoorDash said it had spoken with Ms. StokesOliver’s family and helped it make an insurance claim.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , In August, Isabella Lewis, a Lyft driver in Texas, was killed in a seemingly random attack by a passenger who the police believed was a terrorist. After shooting her in the head, the man pulled her out of the vehicle and drove over her while fleeing in her car. He later died from wounds from a shootout with the police, according to news reports.                                                                                                                                                                                                                                                                , Ms. Lewis’s sister, Allyssa Lewis-Brown, said the loss had still not fully sunk in.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , “It still hasn’t hit that I’ll never get to see her again,” said Ms. Lewis-Brown, 23, who remembered her sister as caring and protective. “That just kind of blows my mind. You think you have more time with people.”                                                                                                                                                                                                                                                                                                                                                                                                     , She said she hoped her story and the driver death report would spur ride-hailing companies to find a way to keep drivers safer, perhaps by rigorously screening passengers before they can use the services. Lyft, she said, never spoke with her.                                                                                                                                                                                                                                                                                                                                                                         , “The least you could do is pay for funeral expenses,” she said. Lyft said it had tried to reach Ms. Lewis’s family but had been unsuccessful.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Tiffany Hsu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Pinterest will prohibit ads and posts that feature climate misinformation in its latest attempt to block harmful content on its virtual pinboard service, the company said on Wednesday.                                                                                                                                                                                                                                                                                                                                                                                                                                   , The ban includes any content that denies the existence or impacts of climate change, or denies that humans influence global warming and that the phenomenon is supported by scientific consensus. Inaccurate posts about natural disasters and extreme weather events will also be removed, as will misrepresentations of scientific data through omission or cherry-picking meant to erode trust in climate science.                                                                                                                                                                                                      , Searches about sustainability are on the rise on Pinterest, with queries about “zero waste lifestyle” surging 64 percent in the past year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Google said in October that it would no longer display ads on YouTube videos and other content that promote inaccurate claims about climate change. Some publications have stopped accepting ads from fossil fuel companies, while ad agencies are increasingly turning away work from the industry.                                                                                                                                                                                                                                                                                                                       , A report released this week by a panel of experts convened by the United Nations concluded that nations must drastically cut fossil fuels emissions in the coming years to prevent a disastrous level of global warming.                                                                                                                                                                                                                                                                                                                                                                                                   , Pinterest has blocked several categories of ads over the years, banning ads showing culturally appropriated and inappropriate costumes in 2016, anti-vaccination content in 2017, political ads in 2018 and weight-loss ads in 2021. In response, companies such as Shapermint changed their marketing campaigns to feature women of all body types, according to Pinterest.                                                                                                                                                                                                                                               , Ads account for all of Pinterest’s revenue. The company, which declined to say how many climate misinformation ads it had caught in the past, said it used human moderators, automated systems and user reports to enforce its policies.                                                                                                                                                                                                                                                                                                                                                                                   , Sarah Bromma, Pinterest’s head of policy, said the company wanted to prevent misinformation before it gained popularity on the site. Tech giants such as Meta and Twitter have faced blowback from users and advertisers for allowing hate speech, conspiracy theories and misleading content on their services.                                                                                                                                                                                                                                                                                                           , “We always want to make sure our policies are forward-leaning, that we’re not waiting until we’re overrun with some type of harmful content and then move,” she said. “At that point, it’s kind of too late.”                                                                                                                                                                                                                                                                                                                                                                                                              , Today in the On Tech newsletter, Shira Ovide writes that streaming is a tough business, and the possibility of adding commercials to Netflix shows that even the industry’s star is finding it difficult to repeat its past success. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/car-production </td>
   <td style="text-align:left;"> 2022-04-06 20:03:00 </td>
   <td style="text-align:left;"> Mexico Car Production Inches Higher for 2nd Month </td>
   <td style="text-align:left;"> Mexico’s auto production rose 0.8 percent over a year earlier to 303,515 units in March of 2022, rising for the second straight month amid easing signs of the global shortage of semiconductors. Among major producers, output rose substantially for GM (19.0 percent to 68,132 units), Chrysler (28.4 percent to 41,396 units), Ford (27.2 percent to 32,173 units), and Toyota (29.0 percent to 23,889 units). On the other hand, production fell in plants of Volkswagen (-3.3 percent to 30,993 units) and Nissan (-55.4 percent to 26,367 units). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/04/06/stocks-making-the-biggest-moves-premarket-twitter-spirit-airlines-tilray-and-more.html </td>
   <td style="text-align:left;"> 2022-04-06 19:52:38 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Twitter, Spirit Airlines, Tilray and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                   , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                         , Twitter (TWTR) – Twitter fell 1.5% in premarket trading, potentially breaking a three-day win streak that has seen it gain nearly 32%. Elon Musk – now Twitter's largest shareholder – changed the type of SEC filing regarding his share purchase to show it was not "passive."                                                                  , Spirit Airlines (SAVE) – Spirit said its board will consider a new $3.6 billion cash takeover offer from JetBlue (JBLU). Spirit had agreed in February to be bought by Frontier Airlines parent Frontier Group (ULCC) for $2.9 billion in cash and stock. Spirit slid 2.8% in the premarket, with JetBlue dropping 3.7% and Frontier falling 3.9%., Tilray (TLRY) – Tilray rose 2.1% in the premarket after reporting an unexpected profit for its latest quarter, even as revenue fell below analyst estimates. The cannabis producer also announced a deal with supermarket chain Whole Foods, which will sell the hemp powders produced by Tilray's Manitoba Harvest subsidiary.                   , Rivian (RIVN) – Rivian shares gained 1.7% in the premarket after the company said it was on pace to achieve its previously stated production target of 25,000 electric vehicles this year.                                                                                                                                                        , Occidental Petroleum (OXY) – The energy producer's shares added 1.7% in premarket action after Stifel Financial began coverage with a "buy" rating. Stifel said Occidental remains attractively priced even after it nearly doubled so far this year, noting a largely underappreciated low carbon business.                                      , Intel (INTC) – Intel announced it suspended business operations in Russia, following last month's suspension of semiconductor shipments to customers in Russia and Belarus. Intel fell 1.1% in premarket trading.                                                                                                                                 , Gogo (GOGO) – Gogo surged 10.4% in premarket trading after the aviation industry broadband provider announced its stock would join the S&amp;P SmallCap 600 index prior to Friday's open.                                                                                                                                                             , Array Technologies (ARRY) – Array Technologies rallied 14.5% in the premarket after the renewal energy equipment maker reported better-than-expected quarterly revenue and issued an upbeat revenue outlook. It also named Kevin Hostetler as its new CEO, effective April 18, replacing the retiring Jim Fusaro.                                 , Simply Good Foods (SMPL) – The maker of nutritional foods and snacks reported better-than-expected profit and revenue for its latest quarter and raised its sales forecast for the current year.                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60996174?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-06 19:41:03 </td>
   <td style="text-align:left;"> National Insurance rise starts to hit pay packets </td>
   <td style="text-align:left;"> The burden of tax falling on workers and employers has increased as a hotly-debated rise in National Insurance payments takes effect.                                                                                                                                                                                                      , Employees, businesses and the self-employed will pay an extra 1.25p in the pound. The government says it will spend it on health and social care.                                                                                                                                                                                          , Opposition MPs said it exacerbated cost of living pressures, but mitigation will be introduced in July.                                                                                                                                                                                                                                    , Experts are urging people to check their status as a new tax year starts.                                                                                                                                                                                                                                                                  , Earnings levels at which people start to pay income tax have been frozen, increasing the chances of employees being dragged into a new band - with a higher rate of tax - if they receive a pay rise.                                                                                                                                      , Employees pay National Insurance on their wages, employers pay extra contributions for staff, and the self-employed pay it on their profits.                                                                                                                                                                                               , In September, the government announced the rise in contributions from 6 April, in part to help ease the burden on the NHS.                                                                                                                                                                                                                 , It means that, instead of paying National Insurance contributions of 12% on earnings up to £50,270 and 2% on anything above that, employees will now pay 13.25% and 3.25% respectively. The self-employed will see equivalent rates go up from 9% and 2% to 10.25% and 3.25%.                                                              , Those of state pension age do not pay the tax at present, and nor do those on very low incomes.                                                                                                                                                                                                                                            , After the announcement last year, the plans were met with disapproval from opposition parties and some backbench Conservative MPs who criticised the timing, as many people face sharp rises in energy bills and prices in general.                                                                                                        , Chancellor Rishi Sunak responded in his Spring Statement with plans to allow workers and the self-employed to earn more before they start making National Insurance payments. This will take effect in July.                                                                                                                               , The National Insurance rise will - ministers like to say - provide a much needed boost to health and social care.                                                                                                                                                                                                                          , They claim it will pay for the care cap and boost NHS capacity to help tackle the backlog in England - it is up to the rest of the UK to decide how they spend the proceeds.                                                                                                                                                               , But the truth is it will only contribute to that. Rising inflation, staff shortages and ageing equipment and buildings, means the health and care system is going to suck up the £39bn raised over the next three years by the hike and then some more.                                                                                    , It is also worth bearing in mind the government had already committed to rises for the NHS up until 2024 under a funding settlement agreed by the May government.                                                                                                                                                                          , This had brought the increases to something close to the 4% health has historically got - although the rising inflation that is being seen will whittle that away from now on.                                                                                                                                                             , And that came after a decade of the budget rising by little more than 1% - an unprecedented squeeze for the health service.                                                                                                                                                                                                                , The National Insurance rise is not quite all it seems.                                                                                                                                                                                                                                                                                     , From now, employees will pay National Insurance contributions on earnings above £9,880 a year. From July, it will be paid on earnings above £12,570 a year.                                                                                                                                                                                , Taken together, the measures mean that, over the next 12 months, anyone earning less than about £34,000 a year will pay less in National Insurance than they did the previous year, while those earning more will see their payments rise.                                                                                                 , Had the chancellor stuck with his original plan, then all but the very lowest income workers would have paid more in National Insurance.                                                                                                                                                                                                   , Many employers will still pay more, and business groups have warned that this may be passed on in higher prices. They also said it would add to the pressures already faced by firms following the withdrawal of Covid support measures.                                                                                                   , Among those concerned about the bill is Hanna Gentry, an assistant general manager at George's Bistro in Cleckheaton.                                                                                                                                                                                                                      , "Personally for me if I look at my wage I think it's not too much, but as a business when you have to pay that on everybody's wages, it adds up really, really quickly," she said.                                                                                                                                                         , "We are going to try and bring in more custom, that's the only way we can do it - in terms of events, new menus, to try and draw customers in."                                                                                                                                                                                            , Meanwhile James Hipkins, managing director of Emery's Timber and Builders Merchants in Stoke and Telford, told the BBC's Today programme the rise was "another little extra bit" to add to the rising cost of materials, fuel and energy.                                                                                                  , "My greater concern is, is it the beginning of a perfect storm? By that I just mean all the little snips going up, is it going to start to stifle industry?"                                                                                                                                                                               , However, Mr Hipkins said society had a "moral obligation and responsibility to this" to fund social care services, which he added have been "overlooked" for too long.                                                                                                                                                                     , "We all know it needs sorting out, we all know it needs to be paid for but none of us are particularly keen on paying for it," he added.                                                                                                                                                                                                   , "At this stage is it seems a bit wishy washy and woolly as it's coming in. I would feel a lot more confident and a lot more happy when I see it as an actual separate levy and it can be identified for where it's supposed to be going."                                                                                                  , The government said it had raised Employment Allowance from £4,000 to £5,000, so smaller firms could claim up to £5,000 off their National Insurance bills. Ministers said it meant 670,000 firms would not pay the tax at all.                                                                                                            , Overall, the increases in National Insurance for employers and higher-income workers will raise an extra £10.9bn in a year for the government, according to the Institute for Fiscal Studies.                                                                                                                                              , Prime Minister Boris Johnson described it as "necessary, fair and responsible", adding that it would "provide the health and care system with the long term funding it needs as we recover from the pandemic".                                                                                                                             , Next year, the extra tax will be rebranded as the Health and Social Care Levy.                                                                                                                                                                                                                                                             , Health Minister Sajid Javid said the levy was necessary because it would be "morally wrong" to let "our children pay for our healthcare and our adult social care".                                                                                                                                                                        , The Labour Leader Keir Starmer has condemned the NI rise saying that the UK now has the highest rate of taxation in 70 years.                                                                                                                                                                                                              , Calling it the "wrong tax at the wrong time" he said: "In the middle of worst cost of living crisis for decades today the government chooses to increase taxes on working people."                                                                                                                                                         , Liberal Democrat leader Sir Ed Davey said the NI rise "puts all the burden on working people".                                                                                                                                                                                                                                             , An increase in the tax on dividends is also coming into effect, to add to the funds channelled by the government into the NHS and social care.                                                                                                                                                                                             , It has also gone up by 1.25p in the pound. Many private investors hold shares in an Individual Savings Account (Isa) which protects them from tax. However, some business owners pay themselves in dividends and so will face a tax rise.                                                                                                  , Early last year Mr Sunak said the thresholds at which income tax is paid would be frozen at April 2021 levels for five years (although Scotland has different levels). That means pay rises will push more people into higher tax bands.                                                                                                   , If a pay rise takes somebody from below £12,570 a year to above, then they will start paying income tax at 20% on the amount above £12,570. A shift in salary from below £50,270 to above means paying the higher rate of 40% on the amount above £50,270. The next threshold is at £150,000, when the additional tax rate of 45% kicks in., Adrian Lowery, personal finance spokesman at investing platform Bestinvest, urged people to check their tax code, which is issued by HM Revenue and Customs and can be found on a pay slip.                                                                                                                                                , "A tax code of 1257L is currently used for most people who have one job or pension. If yours is different, make sure you understand why, so you're not paying too much tax," he said.                                                                                                                                                      , At last month's Spring Statement, Mr Sunak pledged to reduce the basic rate of income tax by 1p in the pound before the end of the Parliament in 2024.                                                                                                                                                                                     , For this new tax year, the personal allowance of capital gains tax has also been frozen at £12,300, so this much profit can be realised from assets in a year before tax is paid.                                                                                                                                                          , The threshold for inheritance tax - a levy on estates when somebody dies - has also been frozen again at £325,000, as it has since 2009.                                                                                                                                                                                                   , We're keen to talk to people who are willing to disclose their incoming and outgoing income as well as track their finances over the year.  If you would like to take part email haveyoursay@bbc.co.uk.                                                                                                                                    , Please include a contact number if you are willing to speak to a BBC journalist. You can also get in touch in the following ways:                                                                                                                                                                                                          , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or comment or you can email us at HaveYourSay@bbc.co.uk. Please include your name, age and location with any submission.                                                                          , The rise and fall of media mogul Robert Maxwell                                                                                                                                                                                                                                                                                            , Michelle Visage sits down for a one-to-one encounter with Cameron Diaz                                                                                                                                                                                                                                                                     , Why does it impact almost every system in the human body?                                                                                                                                                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/private-investment </td>
   <td style="text-align:left;"> 2022-04-06 19:27:01 </td>
   <td style="text-align:left;"> Mexico Gross Fixed Investment Beats Expectations </td>
   <td style="text-align:left;"> Gross fixed investment in Mexico rose 8.6 percent year-on-year in January of 2022, advancing from a 7.6 percent increase in the previous month and above market expectations of a 4.5 percent rise. It was the 11th consecutive month of growth in private investment. Investment strengthened for construction (10 percent vs 3.7 percent in December), driven by non-residential construction (24 percent vs 9.8 percent), while it rose at a slower pace for machinery and equipment (6.6 percent vs 12.3 percent). On a seasonally adjusted monthly basis, private investment went up 2.2 percent, quickening from a downwardly revised 1.1 percent gain in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tunisia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-04-06 19:19:00 </td>
   <td style="text-align:left;"> Tunisia Inflation Rate at Over 3-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Tunisia accelerated for the sixth straight month to 7.2 percent in March of 2022, from 7 percent in the prior month. It was the highest reading since February of 2019. Main upward pressure came from the prices of alcoholic beverages and tobacco (21 percent versus 19.4 percent in February), clothing and footwear (9.8 percent vs 8.9 percent) and furniture, household items and routine household maintenance (6.1 percent vs 5.7 percent). On a monthly basis, consumer prices were up 0.8 percent, accelerating from a 0.3 percent rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rpm:us </td>
   <td style="text-align:left;"> 2022-04-06 19:17:22 </td>
   <td style="text-align:left;"> RPM International earnings above expectations at 0.38 USD </td>
   <td style="text-align:left;"> RPM International (RPM) released earnings per share at 0.38 USD, compared to market expectations of 0.30 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/mortgage-applications </td>
   <td style="text-align:left;"> 2022-04-06 19:11:00 </td>
   <td style="text-align:left;"> US Mortgage Applications Fall for 4th Week: MBA </td>
   <td style="text-align:left;"> Mortgage applications in the US fell 6.3% in the week ended April 1st, pushing the index to its lowest since March of 2019, as interest rates continue to march higher. It follows a 6.8% slump in the previous period and marks the 4th straight week of falls. The refinancing index sank 9.9% making now only 38.8% of all mortgage application activity, down from about 60% a year ago and the smallest share since May 2019. Also, the applications to purchase a home went down 3.4%. The average contract interest rate for 30-year fixed-rate mortgages increased to 4.9% from 4.8%, the highest since December of 2018. “The elevated average purchase loan size, and steeper 8% drop in FHA purchase applications, are both indicative of first-time buyers being disproportionately impacted by supply and affordability challenges”, said Joel Kan, an MBA economist. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-04-07 09:24:15 UTC +8

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
   <td style="text-align:left;"> 2022-04-07 09:23:42 </td>
   <td style="text-align:left;"> $SPY. 95billion reduction 9 rate hike y yall bulley?🤷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:23:31 </td>
   <td style="text-align:left;"> $SPY my thesis is that for capital projects to move forward, prices need to come down for inputs or the output needs to be absorbed by the consumer.  In any event, the top 3 types of companies best positioned to benefit from both are those that make real necessities.  1) Green energy, 2) multi family housing and 3) biotechnology </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:23:24 </td>
   <td style="text-align:left;"> $SPY one year ago today I posted this. April 2021 was wilin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:22:51 </td>
   <td style="text-align:left;"> The Fed $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:22:38 </td>
   <td style="text-align:left;"> $SPY 325 by years end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:22:25 </td>
   <td style="text-align:left;"> $SPY it shows 125$ on RH 🤩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:22:14 </td>
   <td style="text-align:left;"> $SPY recap of the market today https://youtu.be/MIERYXdh2PI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:47 </td>
   <td style="text-align:left;"> $SPY If youre a real bull let her fall to 441, that&amp;#39;s where the big buyers  big $$$coming in  and the rocket takes off , right now its fluffy buyers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:45 </td>
   <td style="text-align:left;"> $SPY too many shorties here going nowhere.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:45 </td>
   <td style="text-align:left;"> $SPY  $AAPL $TSLA 
Tomorrow QE pump for “Soft landing”  👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:41 </td>
   <td style="text-align:left;"> $SPY gonna rally tomorrow and go blood red Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:38 </td>
   <td style="text-align:left;"> $SPY OFG Indicator has been making me a fortune over the last year.....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:38 </td>
   <td style="text-align:left;"> $AMZN $SPY 🙄 https://www.nationalheraldindia.com/international/amazon-hikes-prices-of-music-streaming-service-for-prime-members </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:21:31 </td>
   <td style="text-align:left;"> $SPY  
 
https://www.youtube.com/watch?v=ufvCQK_ANUY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:20:52 </td>
   <td style="text-align:left;"> $SPY puts were getting extra frothy so.u know I had to get em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:20:36 </td>
   <td style="text-align:left;"> $SPY If Ukraine is beating Russia like our fake news media tells us, why keep giving Russia more sanctions? Sleepy Joe is getting us into a situation that keeps getting worse.  Mr Workman&amp;#39;s opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:20:35 </td>
   <td style="text-align:left;"> $spy $qqq $iwm https://youtu.be/vHtlCos7-Ag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:19:58 </td>
   <td style="text-align:left;"> $SPY idk what to make of this.  Gaps on the way up, gaps on the way down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:19:26 </td>
   <td style="text-align:left;"> $SPY $dwac Congress as a whole are idiots when it comes to immigration both sides uses as a political cudgel against each other rather than trying to fix it.. biased media  portrays it as poor immigrants huddled trying to get across or illegals getting in mystery buses to Parts Unknown.. obviously any good journalist could follow where these people are going..  most likely going somewhere where they have family.. this is a short article about the process.. it appears  asking for Asylum which  are laws grant starts a long bureaucratic process.
https://www.kvue.com/article/news/special-reports/at-the-border/how-the-asylum-process-works-for-those-caught-crossing-the-border-illegally/269-cf8f1260-4302-4707-b06c-5b2be8e6aa8e </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:19:07 </td>
   <td style="text-align:left;"> $SPY V12&amp;#39;s such beautiful machines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:18:36 </td>
   <td style="text-align:left;"> $SPY Starting to see known bulls claiming that it’s the end of the world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:18:15 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:18:05 </td>
   <td style="text-align:left;"> $SPY 440 tmr futures don’t even try anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:17:51 </td>
   <td style="text-align:left;"> $SPY do you guys realize this has only gone down 1% lol relax 😂😂😂😂. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:17:37 </td>
   <td style="text-align:left;"> $SPY $QQQ These look like sales prices kinda but they aren&amp;#39;t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:17:12 </td>
   <td style="text-align:left;"> $SPY it’s all over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:17:10 </td>
   <td style="text-align:left;"> $SPY $DWAC Confused, lazy and dumber than ever.... &amp;quot; The party of the kids &amp;quot; they say, lol... Libtard logic  #CompleteFailures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:17:04 </td>
   <td style="text-align:left;"> $SPY All you need to know is the Bulltards haven&amp;#39;t sold a single share.... and they still live at home🤣😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:16:52 </td>
   <td style="text-align:left;"> $SPY https://m.youtube.com/watch?v=MKbkhArMM4w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:16:49 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:16:42 </td>
   <td style="text-align:left;"> $AAVE.X $SPY  the fooookingggg gooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:16:28 </td>
   <td style="text-align:left;"> $SPY Chooo Chooo . Train is on . Nxt stop 400 &amp;amp; Lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:15:49 </td>
   <td style="text-align:left;"> $SPY what jack asses buy in a bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:15:37 </td>
   <td style="text-align:left;"> $SPY I think we can stop freaking out about the inverted yields now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:15:05 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:14:31 </td>
   <td style="text-align:left;"> $SPY The police let the Jan 6 protesters into the capital. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:14:29 </td>
   <td style="text-align:left;"> $SPY Oh, my means have reverted alright. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:14:28 </td>
   <td style="text-align:left;"> $SPY  $AAPL $TSLA $SNOW $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:14:28 </td>
   <td style="text-align:left;"> $SPY Putin to give address on CNBC at 11:30 am EST.   Oh! Wait we don’t do that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:13:29 </td>
   <td style="text-align:left;"> $TSLA $SPY All that you need to know... Shorts haven&amp;#39;t covered a single share.. Check it out below.  
 
Highly recommend everyone to follow them.   
http://live-stock-alerts.coordinatetrading.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:13:11 </td>
   <td style="text-align:left;"> $SPY Biden resignation  in less than 30 days….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:13:09 </td>
   <td style="text-align:left;"> $TSLA $SPY All that you need to know... Shorts haven&amp;#39;t covered a single share. Check it out below  
 
Highly recommend everyone to follow them   
http://live-stock-alerts.coordinatetrading.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:12:21 </td>
   <td style="text-align:left;"> $SPY easiest way to build your options account. Only day trade no matter if its 3 trades a week. And buy calls when rsi is very low and puts when very high. This has grown my portfolio tremendously over the past months. And its easy even if you cant read charts very well, and also never be perma anything. Try not to hold over night options( even tho i sometimes do ) but if u do dont go all in. I usually only risk 10% if i swing options. Lets get this $$$ everybody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:12:19 </td>
   <td style="text-align:left;"> $SPY 451 relief rally. Then I&amp;#39;m chanting next leg down! Next leg down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:12:14 </td>
   <td style="text-align:left;"> $SPY after another aggressive month of day trading - it&amp;#39;s vacation time! splurged on my parents business class tickets and two weeks vacation together. Stay safe, keep fighting and win. I&amp;#39;ll see you all in a few weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:11:58 </td>
   <td style="text-align:left;"> $SPY 420 next week🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:11:49 </td>
   <td style="text-align:left;"> $SPY just in!!! 
https://youtu.be/0-uTQSOqVoE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:11:46 </td>
   <td style="text-align:left;"> $SPY “Apes in puts to da moon we riiiiide baby 🦍🏳️‍🌈🐻”

Too funny 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:11:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $NVDA $SPY 
Bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:11:25 </td>
   <td style="text-align:left;"> $SPY Well, that was fun .

Let&amp;#39;s do it again tom., same bat channel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:10:46 </td>
   <td style="text-align:left;"> $SPY futes are red, berries are blue, the Fed just shit all over you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:10:35 </td>
   <td style="text-align:left;"> $SPY cash sweep vehicle swollen with put premium swinging into Friday 
Time to go nite nite bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:09:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures still red little recover .. if goes flat or green I will say we might get some relief rally ; but so far this red not convincing me !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:09:39 </td>
   <td style="text-align:left;"> $SPY    1 hour to go to reclaim the blue line. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:09:34 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $JPM 
🥶 $95B cut per month &amp;amp; 0.5% hike
https://www.cnbc.com/2022/04/06/fed-minutes-march-2022-meetings-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:08:41 </td>
   <td style="text-align:left;"> $SPY 
BREAKING: Russia&amp;#39;s most advanced fighter jet Sukhoi Su-35 successfully intercepts Ukrainian missile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:08:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Futes are red, are u ready for tomorrow tributes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:08:08 </td>
   <td style="text-align:left;"> $SPY if I had a suit would u be more inclined to trust me? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:07:43 </td>
   <td style="text-align:left;"> $SPY I’m coining this indicator, “The Bat” it’s clearly a bullish set up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:07:27 </td>
   <td style="text-align:left;"> $BTC.X $SPY trumpsters are begging you to sell, lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:07:23 </td>
   <td style="text-align:left;"> $SPY wants the nasdaw down 300 plus Tuesday or Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:07:20 </td>
   <td style="text-align:left;"> $SPY H/S FOMC minutes 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:07:16 </td>
   <td style="text-align:left;"> $SPY Fed took away the punch bowl with prejudice. Selling 95 Billion per month. Re-pricing coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:06:48 </td>
   <td style="text-align:left;"> $SPY remember in  November.  Susan Collins, Lisa Murkowski and Mitt Romney </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:06:45 </td>
   <td style="text-align:left;"> $SPY serious question.
Why is everyone not just shorting and buying puts? Seems to be pretty well screwed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:06:29 </td>
   <td style="text-align:left;"> Being $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:06:25 </td>
   <td style="text-align:left;"> $SPY When is crash-Vegas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:06:07 </td>
   <td style="text-align:left;"> $SPY Charts suggest the market could rally after its current ‘short-term volatility spike,’ Jim Cramer says
https://www.cnbc.com/2022/04/06/charts-suggest-the-market-could-rally-after-its-current-short-term-volatility-spike-jim-cramer-says.html
CNBC’s Jim Cramer said Wednesday that the market is poised to bottom and rally again by Monday, leaning on analysis from Option Pit founder and volatility expert Mark Sebastian.
“The charts as interpreted by Mark Sebastian say we’re currently in the middle of a short-term volatility spike, and once it’s over, we’re going to return to the post-March bottom environment where stocks can easily go higher,” the “Mad Money” host said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:05:36 </td>
   <td style="text-align:left;"> $QQQ $SPY Some economists believe Fed will have to sacrifice markets to beat inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:05:14 </td>
   <td style="text-align:left;"> $SPY We all know Psaki is leaving - she looks tired from her recent (2nd) Covid outbreak, and was startled that someone would mention that &amp;quot;Irregular&amp;quot; Border crossers - that were given Smartphones to track them, might actually just throw them away to stop being tracked. 
 
Seems like a logical conclusion that anyone wearing an ankle bracelet might do if they did not want to be tracked and followed. 
 
She is suppose to take over for Richard Maddow, who was transferred out after the ratings tanked on the show. 
 
The Jen Psaki saga will continue.  Thanks for all the entertainment from Spinning the daily gaffs coming out of the Biden/Obama White House. 
 
https://www.youtube.com/watch?v=xtwb_vMj48g&amp;amp;ab_channel=ForbesBreakingNews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:04:37 </td>
   <td style="text-align:left;"> $SPY @sonicmerlin 

Hey moo, take a look at $SST 

400% short……
350% interest on borrowed shares..
It de spac’d and only 700k float. 
5.38 million FTD’s the last week.
Never seen anything like it. 
What an absolute shit storm

S1 at Sec has to drop for shares to free up, could take weeks. 
Hundreds of millions of calls ITM, way over leveraged.

Sit back with some popcorn, this could get fun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:04:34 </td>
   <td style="text-align:left;"> $SPY 436 target 1 wave 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:04:22 </td>
   <td style="text-align:left;"> $fxi $spy $yang $ewt
You know what’s coming next…

https://www.cnn.com/2022/04/06/politics/china-military-russia-ukraine-what-matters/index.html?utm_term=link&amp;amp;utm_source=twCNN&amp;amp;utm_content=2022-04-07T01%3A00%3A10&amp;amp;utm_medium=social </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:04:09 </td>
   <td style="text-align:left;"> $SPY Everything you need to know about most of the hotties on ST. 

A pubic service announcement… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:03:22 </td>
   <td style="text-align:left;"> $SPY rutes fipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:03:11 </td>
   <td style="text-align:left;"> $SPY 🇺🇸🖖🏽 
 
https://open.spotify.com/track/1fDsrQ23eTAVFElUMaf38X?si=s-ghr7KwRjSxV3uGnW7IDQ&amp;amp;context=spotify%3Aplaylist%3A79VJlbqvtofzeQDV6YsEWz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:03:02 </td>
   <td style="text-align:left;"> $SPY my fruit for tonight is 🫐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:02:26 </td>
   <td style="text-align:left;"> $SPY Just buy long dated puts and don&amp;#39;t even look at the screens. Stop being an idiot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:02:24 </td>
   <td style="text-align:left;"> $SPY no spam any trade groups to join? That don’t promise 2000% reruns lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:02:18 </td>
   <td style="text-align:left;"> $SPY where’s the bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:02:14 </td>
   <td style="text-align:left;"> $SPY $NEGG 

Detail: Chart Updates

Stock Market Update

https://youtu.be/rKECMzDfEZM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:01:45 </td>
   <td style="text-align:left;"> $SPY dont forget to BTDF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:01:27 </td>
   <td style="text-align:left;"> $SPY 👍https://youtu.be/xlBQXdCCvQI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:01:23 </td>
   <td style="text-align:left;"> $AAPL $SPY @Amazontacular lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:01:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Fed is going to reduce balance sheet by $95B per month. Double the rate of last time they did this. 

At this rate they will need to continue for about 95 consecutive months to work off the $9 Trillion they have taken on. This helps put into context the excess of the past 2 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:00:59 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 09:00:07 </td>
   <td style="text-align:left;"> $SPY yall like chiggone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:59:37 </td>
   <td style="text-align:left;"> $SPY gdp grew in Q3 and Q4 of 2021 so it is probably waaaay to early to be talking recession. But what do I know I’m just a hobbit with a search engine.

https://www.investopedia.com/terms/r/recession.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:59:05 </td>
   <td style="text-align:left;"> $SPY Relief rally 100 ma before death and destruction. I believe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:59:02 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m sure the bottom is in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:58:49 </td>
   <td style="text-align:left;"> $SPY if you got PUTS buy some $SPX calls for hedging, I think there is some fuckery going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:58:48 </td>
   <td style="text-align:left;"> $SPY $QQQ  It&amp;#39;s getting not good at all. The QQQs reversal needs confirmation if this bouce is more than a bear market rally. Failure to make new highs from here would mean that February lows will likely be broken. Better stay out for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:58:45 </td>
   <td style="text-align:left;"> $SPY Next week will be a bloodbath bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:58:36 </td>
   <td style="text-align:left;"> $SPY $DWAC   #Shame </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:58:29 </td>
   <td style="text-align:left;"> $SPY tbh today was brutal it went up and down after fomc looking at chart wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:58:00 </td>
   <td style="text-align:left;"> $SPY $AMC $GME this Is THE MUST WATCH AMC AND GME DD VIDEO from a couple days ago. Share. I will keep sharing this. This is important. 25 minutes long worth your time if you have the attention span which you should if you have money in these 

https://youtu.be/JzotZjgbjcE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:50 </td>
   <td style="text-align:left;"> $SPY cash on hand when would be a good idea to start leveraging back in and what stocks or markets… 

Help a newb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:44 </td>
   <td style="text-align:left;"> $SPY so who here has the balls to short this pig market? Feds been helping everyone since 2009 and the party is over. 🌷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:41 </td>
   <td style="text-align:left;"> $SPY $QQQ   Time
Stamp check ***if you watched the tape/chart  today when Fomc minutes hit then you know both sides of this trade went exceptionally green. Chats n stuff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:38 </td>
   <td style="text-align:left;"> $SPY tomorning opening price 443.08 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:34 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 1: $SPY $AAPL $SST $FB $ULCC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:16 </td>
   <td style="text-align:left;"> $SPY stomach hurts 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:57:03 </td>
   <td style="text-align:left;"> $SPY funny…all those people that collected unemployment and got tons of stimulus are getting jobs again…but now with rising interest rates and a sketchy future, employers will be hesitant on hiring. Once the labor market changed (which it will), then the entire system collapses. The labor market is the last strong signal in the economy….and that will be gone soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:56:53 </td>
   <td style="text-align:left;"> $SPY Maybe my mind is fried from months of volatility but I think the correction is over. I remember in 2018 and 2020, I SWORE it was the end. Fed tried to taper in 18 and it backfired. Worse than this. They immediately reinstated QE and then obviously turned the printer on full force in 2020. I traded both of those corrections and took some heavy losses on futures, initially. Of course, over time I scraped it all back and started over. In March, I made one bad trade and it cost me $35,000. 

That’s unacceptable. You have to realize that the fed and the government will do everything in its power to keep the dollar as the reserve currency. Look how quickly we forgot about covid, forgot about Russia. The headlines are back to monetary policy. 

It’s a currency war and with China starting its initial phases of QE, we are just going to back down?

Nope. Sorry. We can say that it’s ruining the economy and will never adjust. 

Truth is, it IS transitory.

Btfd and quit reading headlines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:50 </td>
   <td style="text-align:left;"> $SPY PPT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:47 </td>
   <td style="text-align:left;"> Dow Jones futures fell 0.3% vs. fair value. S&amp;amp;P 500 futures declined 0.4% and Nasdaq 100 futures lost 0.35%.

The 10-year Treasury yield fell 6 basis points to 2.46%.

Crude oil prices rose 1% overnight
$SPY $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:46 </td>
   <td style="text-align:left;"> $SPY wat do u think of those massive prints again 250k lots. They had disappeared on the way up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:42 </td>
   <td style="text-align:left;"> $SPY consumer credit could be a doozy tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:40 </td>
   <td style="text-align:left;"> $SPY rip to $455 tomorrow. I wish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:36 </td>
   <td style="text-align:left;"> $SPY $QQQ from @WallStJesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:21 </td>
   <td style="text-align:left;"> $SPY $QQQ From the FOMC Minutes: 
 
&amp;quot;No decision regarding the Committee’s plan to reduce 
the Federal Reserve’s balance sheet was made at this 
meeting, but participants agreed they had made substantial progress on the plan and that the Committee was 
well placed to begin the process of reducing the size of 
the balance sheet as early as after the conclusion of its 
upcoming meeting in May.&amp;quot; 
 
May stands for MAYBE we&amp;#39;ll end QE. 
 
&amp;quot;A number of participants noted that the Committee&amp;#39;s previous communications had already contributed to a tightening of financial conditions, as evident in the notable increase in longer-term interest rates over recent months.&amp;quot; 
 
Our terror campaign of fear and intimidation in the bond market is working! Just look at $TLT. 
 
&amp;quot;The staff’s common inflation expectations index, which combines information from many indicators of inflation expectations and inflation compensation, had largely leveled off over the fall and was close to its 2014 average.&amp;quot; 
 
☝️👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:55:03 </td>
   <td style="text-align:left;"> $SPY Freddy vs Bulls tomorrow. 2 paths both equal destruction. 1) gap down with continuance. 2) gap fill at 452 with a &amp;quot;don&amp;#39;t pass go don&amp;#39;t collect $200 waterfall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:54:57 </td>
   <td style="text-align:left;"> $SPY I’ve reviewed 14,000,605 market possibilities and there’s only one scenario where we come out without recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:54:55 </td>
   <td style="text-align:left;"> $SPY right now, the bears are in control, until it is not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:54:53 </td>
   <td style="text-align:left;"> $SPY the ppl telling you to buy the dip are NOT buying the dip 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:54:15 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY melt down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:54:10 </td>
   <td style="text-align:left;"> $SPY $IWM $AMZN $TSLA BUY All Dips tomorrow and Friday! We are going to bounce... News is behind us now!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:54:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:53:47 </td>
   <td style="text-align:left;"> $SPY 

Would have been more funny to send them to Delaware. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:52:58 </td>
   <td style="text-align:left;"> $SPY 
 
Come as you aaaaaare.  .   as you were 
 
aaaas I want you to beeeeeeeee   
 
*charts* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:52:54 </td>
   <td style="text-align:left;"> $SPY if you are bearish you don’t want to continue closing over the 20MA &amp;amp; 200MA, a close over the 10MA, then it’s a 🧸 🪤  
  
3/18/22 candle will play a big roll in this set up, if those buyers aren’t flush out, well….  Insert rocket emoji, 440 most likely will hold 🖖🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:52:11 </td>
   <td style="text-align:left;"> $SPY bulls are taking recession like a champ $WMT $COST

Poor bears never talk about recession? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:51:10 </td>
   <td style="text-align:left;"> $SPY omg bears are delusionals now they talking about recession lol it&amp;#39;s been a whole year of sell offs. Everything is oversold and ready to spike. Enjoy your puts and give us the 100% pumps lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:51:07 </td>
   <td style="text-align:left;"> $DTST When the United States comes under significant cyber attack. This will open at 50 and halt all the way to $300+ over a period of 2-3 days. Be holding when that happens. $SPY $IRNT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:56 </td>
   <td style="text-align:left;"> $SPY I just added to my Gold and Silver portfolio
again today and just bought 
10oz of Gold
40oz of Silver
20 boxes of girl scout cookies
I already ate 2 boxes of tagalongs
Markets in Turmoil tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:44 </td>
   <td style="text-align:left;"> $SPY meet Kevin bought. Dump it! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:44 </td>
   <td style="text-align:left;"> $SPY legit legal market as usual, looks like a fkn EKG for a VFIB, shills </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:38 </td>
   <td style="text-align:left;"> $SPY True bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:37 </td>
   <td style="text-align:left;"> $SPY seems too perfect 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:18 </td>
   <td style="text-align:left;"> $SPY I can some vertical drops from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:09 </td>
   <td style="text-align:left;"> $SPY so are the bears celebrating... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:50:09 </td>
   <td style="text-align:left;"> $SPY ive been saying since like September they were not passing bbb because of inflation. Its all theatre 

https://twitter.com/zerohedge/status/1511691917637132289?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:49:58 </td>
   <td style="text-align:left;"> $SPY this week will be the worst and gonna wipe out all March gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:49:37 </td>
   <td style="text-align:left;"> $SPY democrats could sweep in 2024 if they started pushing to outlaw rent seeking and parasitic landlords. Land reform movement 2.0  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:49:21 </td>
   <td style="text-align:left;"> $SPY 2008 is a recession
The only stonk that went up is recession proof stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:48:58 </td>
   <td style="text-align:left;"> $SPY libbies be libbin. Wrecking the country but God bless Texas!

Texas Gov. Greg Abbott said Wednesday that undocumented migrants released into his state will be shipped to the steps of the U.S. Capitol in Washington D.C., as border checkpoints struggle to manage the flow of people attempting to enter the United States and the Biden administration&amp;#39;s move to eliminate the Title 42 expulsion provision. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:48:57 </td>
   <td style="text-align:left;"> $SPY what I’m hoping to see is a gap fill followed by momentum down to reject a breakout also would help if vwap confirms bear trend. Otherwise I also would like to see a gap fill and consolidation to upside for continuation up ⬆️. Either way I’m ready to pull the trigger. We’ll see what futes gives us in the am. Overall on the 1 yr I see a bear flag with the pole already formed and the flag is playing out as we speak. Any day it wouldn’t be a surprise to see a down move back to 415-425 range. Cautious with calls and only playing scalp dead cat bounces or just 5-15% gains off momentum . Puts show more favor imo and I plan on shorting major rips and looking at rsi plus macd for confirmation but vwap my fav </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:48:49 </td>
   <td style="text-align:left;"> $SPY 0 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:48:35 </td>
   <td style="text-align:left;"> $SPY I choose you Lapras! Use MAX PUMP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:48:03 </td>
   <td style="text-align:left;"> $SPY why is the Feds speaking every week, saying the same, and down each time.  Is the rate hikes and balance sheet roll off priced in by now.  Bullard is up again tomorrow.  Seems like he speaks every week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:48:01 </td>
   <td style="text-align:left;"> $SPY $SPX No panic. Get this indicator here: https://stonkmetrics.ca/product/thinkorswim-vix-term-structure/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:47:38 </td>
   <td style="text-align:left;"> $SPY Women drivers, no survivors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:47:23 </td>
   <td style="text-align:left;"> $SPY soooo... Green tomorrow right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:47:15 </td>
   <td style="text-align:left;"> $SPY I think the biggest problem a lot of people have with trading markets is overthinking it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:47:00 </td>
   <td style="text-align:left;"> $SPY $BTC.X $DOGE.X eat the fear bearz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:46:34 </td>
   <td style="text-align:left;"> $SPY Daddy Powell committed a crime against me today, and I&amp;#39;d rather it had physical..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:46:27 </td>
   <td style="text-align:left;"> $SPY I am buying the futures big tonight. War seems to be wingding down. I will watch until HSI opens and then buy some SPY futures. I think China will be up big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:46:26 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/G6l7akp6prs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:46:01 </td>
   <td style="text-align:left;"> DB getting more bearish $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:31 </td>
   <td style="text-align:left;"> $QQQ $SPY if I had a dollar for everytime somsone uses “recession” on here incorrectly, I could buy every outstanding share of all major indexes.

A down market does not CAUSE a recession.

A down market is one EFFECT of a recession.

Recession is defined by GDP. Nothing to do with markets directly at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:19 </td>
   <td style="text-align:left;"> latexcad12a2c2c0bdff621344993197788d4BRK.B IS NOT SHOWN AS GREEN TAG

$BRK.A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:17 </td>
   <td style="text-align:left;"> $SPY simply a massive gap up is needed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:14 </td>
   <td style="text-align:left;"> EI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:14 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:45:01 </td>
   <td style="text-align:left;"> $SPY  $QQQ $TSLA latexc341aa97203717ae4696765e8ef30157MSFT down 3.85% 
$FB down 3.71% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:44:12 </td>
   <td style="text-align:left;"> $SPY looks like suddenly we realized that everything is still fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:43:33 </td>
   <td style="text-align:left;"> $SPY prolly go up now until may fomc. No more uncertainty. It’s priced in as they say. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:43:26 </td>
   <td style="text-align:left;"> $SPY Dick measuring contest globally on who can pump their markets the longest until everything falls apart and the switch to CBDC becomes official (Cough cough Xi Xin Ping).... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:43:09 </td>
   <td style="text-align:left;"> $SPY if I took the same energy I have here in the SPY board to Instagram I’d get cancelled and end up on CNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:42:27 </td>
   <td style="text-align:left;"> $SPY Don&amp;#39;t fight the FED, but the FED ain&amp;#39;t done yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:42:25 </td>
   <td style="text-align:left;"> $SPY the answer to all our problems is more hobbit dik piks and more taters and I’m all out of taters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:42:13 </td>
   <td style="text-align:left;"> $SPY order filled vamos! Pppt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:42:12 </td>
   <td style="text-align:left;"> $SPY  $TSLA $PLTR up 5 down 3 baby! Life is this equation, bulls love the 5 and 2, while bears love the 3. Rinse repeat, we all win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:42:11 </td>
   <td style="text-align:left;"> $SPY imagine being a
Normie 401k bag holder
An opening your statement
An it reads 2008 the sequel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:41:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM The ITM insurance calls paid off. Especially those $PLUG calls. ✔️👌👍  
Better than bear 🐻🐨 spray. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:41:29 </td>
   <td style="text-align:left;"> $SPY Look at the Market Rug pull twice on spy after 1pm. The Market Makers are screwing option holders on both ends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:54 </td>
   <td style="text-align:left;"> $SPY I just want to give out positive encouragement to say that 50% of y&amp;#39;all are right everyday! that&amp;#39;s not bad if you&amp;#39;re playing baseball⚾ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:52 </td>
   <td style="text-align:left;"> $SPY $SPX Where are the call buyers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:46 </td>
   <td style="text-align:left;"> $SPY This stuffed mummy is trying to get every penny back that you earned with Trump/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:41 </td>
   <td style="text-align:left;"> $SPY my conclusion is all of u belong here please dont go anywhere else yall fking belong here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:40 </td>
   <td style="text-align:left;"> $SPY James Bullard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:33 </td>
   <td style="text-align:left;"> $U this will be same market cap as $ADSK $ADOBE

As a china programmer, we only use unity to code game, $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:23 </td>
   <td style="text-align:left;"> $SPY Ready for another crack at .15 debit on 5.0 wide SPX debit spreads. Almost reeled it in today. What a beautiful trade she would&amp;#39;ve been </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:20 </td>
   <td style="text-align:left;"> Over 230 points total in price swing on $SPY $SPX final 30 minutes of trading. One of the craziest reactions to the FOMC Minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:40:01 </td>
   <td style="text-align:left;"> $SPY I. Not sold on the sell of till may... NO NO NOPE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:39:54 </td>
   <td style="text-align:left;"> JPM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:39:33 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  
 
If an unfortunate event has already occurred twice , it will most likely happen a third time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:39:26 </td>
   <td style="text-align:left;"> $SPY see of es can break all this  support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:39:14 </td>
   <td style="text-align:left;"> $QQQ $SPY let’s revisit this with a few more gap downs

https://twitter.com/financialjuice1/status/1511707211814346758?s=21&amp;amp;t=cPl5eIGZV5bpTUnVacLCRw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:39:05 </td>
   <td style="text-align:left;"> $SPY I lose money unprofessionally. Some here lose it professionally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:38:38 </td>
   <td style="text-align:left;"> $SPY man are we gonna ump into a china covid closure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:38:37 </td>
   <td style="text-align:left;"> $SPY fute are rippig </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:38:31 </td>
   <td style="text-align:left;"> $SPY after spending the 15mins reading all your posts i&amp;#39;ve come to a devastating conclusion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:38:22 </td>
   <td style="text-align:left;"> $SPY $450 retest incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:38:10 </td>
   <td style="text-align:left;"> Shanghai $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:37:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

Wen Optimus?...🤖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:37:34 </td>
   <td style="text-align:left;"> $SPY $qqq tanking last 2 days and not even small rally ? Come on .. stupid same game .. when green push ; it was no relief for bears too … they just screw both side … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:37:34 </td>
   <td style="text-align:left;"> $SPY 451 to 400 in the coming weeks imo. But I literally lost 12k today dont even listen to me lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:37:16 </td>
   <td style="text-align:left;"> $SPY no one has said it yet…. I volunteer as tribute….  LIMIT DOWN!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:37:00 </td>
   <td style="text-align:left;"> $SPY Ruskis not allowed to use their money to pay debt, that looks like a good idea. Aha…..who’s got more debt then Ruskis? Just about any country with US leading the pack. The US bonds will do well aha probably unintended consequences somewhere along the road. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:36:58 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm $labu
We just had our 3 waves pullback, looking for bullish confirmation tomorrow or Friday for another leg up.
This time it will be ATH $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:36:34 </td>
   <td style="text-align:left;"> $DWAC $SPY   :-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:35:59 </td>
   <td style="text-align:left;"> $SPY 📣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:35:36 </td>
   <td style="text-align:left;"> $SPY ALRIGHT EVERYONE COMMENT ON THIS PLEASE. ANSWER THIS QUESTION!
-Are we finally going DOWN tomorrow and are the bears big FUQ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:35:05 </td>
   <td style="text-align:left;"> $SPY Stick to your guns! just dont put them in your mouth... that s just silly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:34:57 </td>
   <td style="text-align:left;"> $SPY $QQQ

Give me a gap down!!! Futes watchers please make it happen.

I&amp;#39;ll make sure the donuts at continental breakfast are fresh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:34:31 </td>
   <td style="text-align:left;"> $SPY $451 PM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:34:05 </td>
   <td style="text-align:left;"> $SPY machines off as ofg heads to the course in Augusta ⛳️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:33:36 </td>
   <td style="text-align:left;"> $SPY the usual pattern forming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:33:28 </td>
   <td style="text-align:left;"> $SPY Starting an account over sucks. When you have 400 followers, everyone likes your shit. When you have 3, no one pays attention to it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:32:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA is it time to sell and short everything? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:32:05 </td>
   <td style="text-align:left;"> $SPY $QQQ

Judging off the past few trading sessions of $TWTR pumping and $TSLA  dumping it’s starting to look like twitter has musk’s heart. I would even argue that Twitter is starting to look like the more dominant tech company than tesla... would you agree bulls?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:31:42 </td>
   <td style="text-align:left;"> $SPY ok the fed
Hasn&amp;#39;t even stated
Yet. Lol. What
Then? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:31:12 </td>
   <td style="text-align:left;"> $SPY ...bounce spot on 50MA ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:30:58 </td>
   <td style="text-align:left;"> $SPY 453 then 440. I think relief rally and dump. Unless I&amp;#39;m very dumb. Which I am lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:30:50 </td>
   <td style="text-align:left;"> Looking Ahead: Investors will receive the weekly Initial and Continuing Claims report and Consumer Credit for February Thursday. 
 
DJIA -5.1% YTD 
S&amp;amp;P 500 -6.0% YTD 
Russell 2000 -10.2% YTD 
NAS Comp -11.2% YTD 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:30:18 </td>
   <td style="text-align:left;"> $SPY 

Warning Cramer alert 🚨

I suddenly now have the urge to sell and short EVERYTHING

https://youtu.be/YJ6Twr85VZ0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:30:15 </td>
   <td style="text-align:left;"> $SPY may 360 puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:30:15 </td>
   <td style="text-align:left;"> $SPY I think that they should make Political Parties vote separately. That way there won’t be a number to skew. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:30:13 </td>
   <td style="text-align:left;"> $SPY only thing I’m sure of is I’m buying leaps when qe5 is announced and not trading a gd thing. Til then…trade on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:29:28 </td>
   <td style="text-align:left;"> $SPY the obvious play is that this will continue to bleed. Which means that it won’t in order to screw more people who are expecting that to happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:29:21 </td>
   <td style="text-align:left;"> Bruh, the market is one big scam you just have to learn how to play it as well as the cons do. $SPY been saying this for weeks. Exactly why $VXX was suspended so they could run it up and make sure they finished Q1 green. Criminal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:28:42 </td>
   <td style="text-align:left;"> $SPY $400 by 4/20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:28:21 </td>
   <td style="text-align:left;"> $SPY wana buy some Euros for 90c USD so my Summer vacation is not inflated. Heard that food prices higher in Europe than here, shitting you not, so before you Will Smith your Public cashier think of those poor bastards in Europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:28:20 </td>
   <td style="text-align:left;"> $SPY I have seen enough of back to back red days!  I need Elon musk to tweet that he bought 9-10% shares in a random stock again so we can have a green day tomorrow!  This is getting ridiculous when it is April (the greenest month of the year) and right before earnings.  Unless WW3 is going to happen soon, I don&amp;#39;t see a reason for this ridiculous selling the past 2 days! $AMD $UPST $INTC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:28:14 </td>
   <td style="text-align:left;"> $SPY red futures..how original </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:28:05 </td>
   <td style="text-align:left;"> $SPY unless you&amp;#39;re tiger at the masters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:27:40 </td>
   <td style="text-align:left;"> $SPY  Sending Ritualistic blessings for all traders on this board tonight. Will refer to Sacrificial offerings otherwise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:27:28 </td>
   <td style="text-align:left;"> I will keep compounding over the long haul $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:27:08 </td>
   <td style="text-align:left;"> $SPY red futes means a big green day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:58 </td>
   <td style="text-align:left;"> $SPY actually wtf my order isn&amp;#39;t even close it looked like it but it&amp;#39;s not weird </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:56 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:56 </td>
   <td style="text-align:left;"> $SPY y bears excited over futes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:50 </td>
   <td style="text-align:left;"> $SPY reversal by tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:34 </td>
   <td style="text-align:left;"> $SPY bulls r fucked tmm yu hear Mr FOOOkkd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:34 </td>
   <td style="text-align:left;"> $SPY 😐https://youtu.be/VxgFX-J0ZQ4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:26:32 </td>
   <td style="text-align:left;"> $SPY probably weird to have a cat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:25:36 </td>
   <td style="text-align:left;"> $SPY 4450 breaks it goes to 0 quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:25:20 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY

Now do you understand why we’re fucked?

https://twitter.com/smitadeshmukh/status/1511561298609201153?t=9-Fvpx1P7MkYJWEZKJo8_A&amp;amp;s=08 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:25:07 </td>
   <td style="text-align:left;"> $SPY nice too see green futes again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:25:01 </td>
   <td style="text-align:left;"> $SPY RTS super green... guess its bullish bro... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:24:52 </td>
   <td style="text-align:left;"> $SPY im afraid wouldn&amp;#39;t be fast enough to.roll since I need to manually so not gonna roll it unless I need too but my order to average down didn&amp;#39;t fill but it might it close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:24:16 </td>
   <td style="text-align:left;"> $SPY why yes, I’d love some melatonin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:24:09 </td>
   <td style="text-align:left;"> $SPY all eyes on the 4h after JPs notes. In danger of failing. Spells big trouble then. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:59 </td>
   <td style="text-align:left;"> $SPY 4-5% down before all time high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:56 </td>
   <td style="text-align:left;"> $SPY Traders and investors blaming ceos for stocks falling and saying companies are trash when the market is obviously not in a good condition... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:46 </td>
   <td style="text-align:left;"> $SPY POOMPA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:45 </td>
   <td style="text-align:left;"> $SPY Red pattern, pretty much following it so far. If it holds here we should see some upward movement through the end of the month  and at that point I think I&amp;#39;ll be looking for the best shorting opportunities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:37 </td>
   <td style="text-align:left;"> $SPY  📣prepare to be mind fcked to sleep by foots  ✍️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:32 </td>
   <td style="text-align:left;"> $SPY I will keep compounding condiments from restaurants </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:23:27 </td>
   <td style="text-align:left;"> $SPY @rustystonkelford looks very bearish. relief rally or nah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:22:49 </td>
   <td style="text-align:left;"> $SPY Occasionally I will hold myself in the night, cursing myself for buying weeklies again…then wake up and glance at London open for validation. 

I don’t sleep well with weeklies. Kinda like my ex-wife. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:22:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA more escalations wtf this is good for the environment and the world idiots  
 
https://amp.theguardian.com/world/2022/apr/06/as-ukraine-war-enters-new-phase-can-western-arms-turn-the-tide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:22:44 </td>
   <td style="text-align:left;"> $SPY this is the way it starts. Limit up tomorrow. I need 10 people to agree with me so I sleep peacefully tonight 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:22:32 </td>
   <td style="text-align:left;"> $SPY is Brandon on the tele or something? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:22:31 </td>
   <td style="text-align:left;"> $SPY $UPRO ✅👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:22:11 </td>
   <td style="text-align:left;"> $SPY $TSLA Earnings reports today before the markets open&amp;quot; amazing-stocks-room.stockmarketus.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:21:53 </td>
   <td style="text-align:left;"> $SPY I could average down or just roll to.the 60s then.add 1 hmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:21:52 </td>
   <td style="text-align:left;"> $SPY  bears enjoy the night, futes will turn bright green tmrw mrng before open 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:21:04 </td>
   <td style="text-align:left;"> $ES_F $SPY $SPX   $4580 should be your  🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:20:37 </td>
   <td style="text-align:left;"> $SPY there...  i fixed the typo for them 🤣🤣🤣💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:20:04 </td>
   <td style="text-align:left;"> $SPY can&amp;#39;t believe, we actually crashed

I&amp;#39;m so well prepared for recession $WMT $COST $KO

COME AT ME BRO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:20:04 </td>
   <td style="text-align:left;"> $SPY awww man my one call is going to die :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:19:57 </td>
   <td style="text-align:left;"> $SPY 02:54: TEXAS IS CHARTERING BUSES TO DROP MIGRANTS OFF AT U.S. CAPITOL, GOVERNOR SAYS -BI, 07.04.22
😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:19:51 </td>
   <td style="text-align:left;"> $SPY Smells like early February all over again . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:19:47 </td>
   <td style="text-align:left;"> $SPY The Fed pumped 9 trillion and our government has made an art form out of wasting money. This has made us weak and emboldened our enemies. Our liabilities will soon be untenable and the entire system will go down in an inferno that will change the world as we know it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:19:19 </td>
   <td style="text-align:left;"> $SPY BULL RATS - ALMOST! 😆😂📈🐀💨   
 
MAN I made a nice HAUL TODAY!!! (same time , same place tomorrow💡💰😁)   
 
$tsla $rivn $rh $qqq - just getting comfortable to drop some evening  WEAR 👙🩱👀💦😁for twits tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:19:09 </td>
   <td style="text-align:left;"> $SPY economy and market will absolutely be a disaster if energy prices stay high. It’s a massive tax on everyone and everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:19:02 </td>
   <td style="text-align:left;"> $SPY 

Crazy crazy opportunities in this market everyday! April is totally living up to the expectations and we are just loving it in my Small Account Challenge discord!🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:18:59 </td>
   <td style="text-align:left;"> $SPY if libs had any doubt the entire system is just a puppet act, the obama visit brought it into the light. This is disrespect on the highest level of the highest position, and everyone there knows whats going on. Its all right there for public view. Joes not even above kamala. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:18:31 </td>
   <td style="text-align:left;"> $SPY just hope my amc puts print. They should offset my spy calls 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:18:30 </td>
   <td style="text-align:left;"> $SPY   What do you DO when your Prezident is a DUNCE and his Number Two is a STINKING Number TWO 💩💩💩?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:18:02 </td>
   <td style="text-align:left;"> $SPY 😳😳😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:18:02 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $NDX 

Finished up call buying here 

Have to go to bed early tonight 

No one’s selling into Easter 🐣. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:17:40 </td>
   <td style="text-align:left;"> $QQQ $SPY market is definitely fked. Will break March low soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:17:33 </td>
   <td style="text-align:left;"> $SPY If a lot of you stopped using intraday charts for long term trades, you’d be alright… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:17:26 </td>
   <td style="text-align:left;"> $SPY @PurpleReign8 meme request  a laugh now cry later bear/bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:17:18 </td>
   <td style="text-align:left;"> $SPY I might just YOLO $XLP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:17:17 </td>
   <td style="text-align:left;"> $SPY  $QQQ I’ve seen BIG put volumes/OI get incinerated before. It’s called big Ooofism. Just saying don’t over leverage 📣🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:17:02 </td>
   <td style="text-align:left;"> $SPY Timmmberrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:16:53 </td>
   <td style="text-align:left;"> $BYND is not like the Fed will need to trim $BYND from its balance sheets😅😅😅 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:16:40 </td>
   <td style="text-align:left;"> $SPY No more uncertainty. Last chance to buy the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:16:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  
 
Chinese authorities have extended their lockdown of Shanghai to cover all its 25 million people after a fresh surge in Covid cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:16:08 </td>
   <td style="text-align:left;"> $SPY  “Tough talk” from b!tch Brainard but WE ALL KNOW THE FED IS FULLA 
SH!T !!!

They can NEITHER tighten NOR raise rates because of  ALL THE STINKING US DEBT!! 

So BACK TO BUSINESS AS USUAL tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:16:07 </td>
   <td style="text-align:left;"> $SPY Bitcoin and Ether in a free fall. Margin calls and liquidations . This is happening more frequently these days almost every 2 or 3 days. :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:59 </td>
   <td style="text-align:left;"> $SPY Green day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:56 </td>
   <td style="text-align:left;"> $SPY  Just remember diamond hands does not work for options and short positions …it only truly applies to bulls who are willing to stay put and weather the storm without the threat of their options expiring or margin calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:48 </td>
   <td style="text-align:left;"> Market is still 🧐 not a buy a these levels $SPY #inflation #stagflation #economist #trader #interest rates 🚀 #bonds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:45 </td>
   <td style="text-align:left;"> $SPY glitch? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:42 </td>
   <td style="text-align:left;"> $SPY i got order out to average down and it missed by a hair was trying to average down the 4470 strikes I sold because the first 1 I I a cheap price because I chased it just trying to get 1 extra but of.premium😅 literally why I don&amp;#39;t chase but yea then try average down again at dip think 1 more time would.give me decent price to try and get a scalp and still short the 4440s for Friday 
Shake me out bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:35 </td>
   <td style="text-align:left;"> $SPY nobody actually read the FED crap, if you would, there is a back door open, always is, up to 100B(rounded up) means $350 USD qualifies as a drawdown as well…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:18 </td>
   <td style="text-align:left;"> $SPY 
456 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:15:07 </td>
   <td style="text-align:left;"> $SPY You know how I know the market’s going higher … because I want it to go lower!😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:14:46 </td>
   <td style="text-align:left;"> $SPY snag some calls around 445 for the bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:14:39 </td>
   <td style="text-align:left;"> $SPY Bullard speaks tomorrow, puts gonna pay big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:14:35 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:14:25 </td>
   <td style="text-align:left;"> $SPY equities will continue to be undervalued.  
 
of course there will be bumps in the road.  
 
Buy good companies or the S&amp;amp;P500(OVER TIME) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:14:16 </td>
   <td style="text-align:left;"> $SPY I hope you bears enjoyed the red futes. Time to reverse ⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:14:08 </td>
   <td style="text-align:left;"> $SPY what just happened </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:45 </td>
   <td style="text-align:left;"> $SPY 1% exact pin ...lmfao only John cam fight skynet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:45 </td>
   <td style="text-align:left;"> $SPY 👍https://youtu.be/1yoYGmJ1bP0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:43 </td>
   <td style="text-align:left;"> $SPY job claim tomorrow :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:33 </td>
   <td style="text-align:left;"> $SPY  well it’s over folks! See you at 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:25 </td>
   <td style="text-align:left;"> $SPY Mike Money for everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:21 </td>
   <td style="text-align:left;"> $SPY to 440 by 9:30. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:19 </td>
   <td style="text-align:left;"> $SPY big green dildo ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:15 </td>
   <td style="text-align:left;"> $SPY  what they say is one thing. But We’ll see just how much QT they actually
do.  Hehe 

TINA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-07 08:13:13 </td>
   <td style="text-align:left;"> $SPY muahhaha. Everything priced in. Even your calls being worthless. Muahhah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:21:47 </td>
   <td style="text-align:left;"> $PLTR CONFIRMED $QQQ $ACN $MSFT 

Palantir X Accenture 

PARABOLIC 

https://blog.palantir.com/palantir-foundry-and-accenture-expertise-powerful-results-fa886aae9210 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:20:35 </td>
   <td style="text-align:left;"> $spy $qqq $iwm https://youtu.be/vHtlCos7-Ag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:19:15 </td>
   <td style="text-align:left;"> $QQQ the Feds will be reducing the balance sheet by about 95 billion a month. Major liquidity crisis coming up in the market on top of 0.5 rate hikes looming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:17:37 </td>
   <td style="text-align:left;"> $SPY $QQQ These look like sales prices kinda but they aren&amp;#39;t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:14:11 </td>
   <td style="text-align:left;"> $QQQ Bullard speaking tomorrow. CPI/PPI data next week will bring new lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:12:38 </td>
   <td style="text-align:left;"> $QQQ futes tripin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:11:26 </td>
   <td style="text-align:left;"> $QQQ https://youtu.be/0-uTQSOqVoE 
bad news!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:09:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures still red little recover .. if goes flat or green I will say we might get some relief rally ; but so far this red not convincing me !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:08:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Futes are red, are u ready for tomorrow tributes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:06:50 </td>
   <td style="text-align:left;"> $QQQ The only sure thing is, sadly, the market will always find a way to fxxk me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:06:04 </td>
   <td style="text-align:left;"> $QQQ Have that many people lost money, or have i just been blocked by so many of you. This site is weak anymore. No offense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:05:36 </td>
   <td style="text-align:left;"> $QQQ $SPY Some economists believe Fed will have to sacrifice markets to beat inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:02:31 </td>
   <td style="text-align:left;"> $QQQ 5 year chart should tell you everything you need to know about where this is headed in the next 12-18 months, maybe sooner. Party’s over boys and girls. Time for the hangover of a lifetime. $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:01:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Fed is going to reduce balance sheet by $95B per month. Double the rate of last time they did this. 

At this rate they will need to continue for about 95 consecutive months to work off the $9 Trillion they have taken on. This helps put into context the excess of the past 2 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 09:00:28 </td>
   <td style="text-align:left;"> $SOXL $30 grest entry but $qqq is still high,if if retraces to $320 $soxl might be $20-$25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:58:48 </td>
   <td style="text-align:left;"> $SPY $QQQ  It&amp;#39;s getting not good at all. The QQQs reversal needs confirmation if this bouce is more than a bear market rally. Failure to make new highs from here would mean that February lows will likely be broken. Better stay out for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:57:41 </td>
   <td style="text-align:left;"> $SPY $QQQ   Time
Stamp check ***if you watched the tape/chart  today when Fomc minutes hit then you know both sides of this trade went exceptionally green. Chats n stuff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:55:47 </td>
   <td style="text-align:left;"> Dow Jones futures fell 0.3% vs. fair value. S&amp;amp;P 500 futures declined 0.4% and Nasdaq 100 futures lost 0.35%.

The 10-year Treasury yield fell 6 basis points to 2.46%.

Crude oil prices rose 1% overnight
$SPY $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:55:36 </td>
   <td style="text-align:left;"> $SPY $QQQ from @WallStJesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:55:21 </td>
   <td style="text-align:left;"> $SPY $QQQ From the FOMC Minutes: 
 
&amp;quot;No decision regarding the Committee’s plan to reduce 
the Federal Reserve’s balance sheet was made at this 
meeting, but participants agreed they had made substantial progress on the plan and that the Committee was 
well placed to begin the process of reducing the size of 
the balance sheet as early as after the conclusion of its 
upcoming meeting in May.&amp;quot; 
 
May stands for MAYBE we&amp;#39;ll end QE. 
 
&amp;quot;A number of participants noted that the Committee&amp;#39;s previous communications had already contributed to a tightening of financial conditions, as evident in the notable increase in longer-term interest rates over recent months.&amp;quot; 
 
Our terror campaign of fear and intimidation in the bond market is working! Just look at $TLT. 
 
&amp;quot;The staff’s common inflation expectations index, which combines information from many indicators of inflation expectations and inflation compensation, had largely leveled off over the fall and was close to its 2014 average.&amp;quot; 
 
☝️👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:49:32 </td>
   <td style="text-align:left;"> $QQQ this week will wipe out all March gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:48:11 </td>
   <td style="text-align:left;"> $QQQ Don’t fight the Fed…..
They want the markets lower. Ride it down with the Fed while making some coin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:45:31 </td>
   <td style="text-align:left;"> $QQQ $SPY if I had a dollar for everytime somsone uses “recession” on here incorrectly, I could buy every outstanding share of all major indexes.

A down market does not CAUSE a recession.

A down market is one EFFECT of a recession.

Recession is defined by GDP. Nothing to do with markets directly at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:45:01 </td>
   <td style="text-align:left;"> $SPY  $QQQ $TSLA $TWTR 

 MM Wanna play dirty huh ?? We can do it . ✅ chats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:41:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM The ITM insurance calls paid off. Especially those $PLUG calls. ✔️👌👍  
Better than bear 🐻🐨 spray. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:40:37 </td>
   <td style="text-align:left;"> Long Term Cycles &amp;amp; Elliott Wave for $QQQ. Read the article: https://elliottwave-forecast.com/stock-market/long-term-cycles-elliott-wave-for-qqq/ #elliottwave #ondaselliott #qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:39:33 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  
 
If an unfortunate event has already occurred twice , it will most likely happen a third time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:39:14 </td>
   <td style="text-align:left;"> $QQQ $SPY let’s revisit this with a few more gap downs

https://twitter.com/financialjuice1/status/1511707211814346758?s=21&amp;amp;t=cPl5eIGZV5bpTUnVacLCRw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:38:47 </td>
   <td style="text-align:left;"> $QQQ some days are so wow  that you have to catalog it on your playbook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:38:38 </td>
   <td style="text-align:left;"> $SQQQ if $QQQ drops below 350, look out below. Will open some yolo calls for SQQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:37:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

Wen Optimus?...🤖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:37:34 </td>
   <td style="text-align:left;"> $SPY $qqq tanking last 2 days and not even small rally ? Come on .. stupid same game .. when green push ; it was no relief for bears too … they just screw both side … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:36:58 </td>
   <td style="text-align:left;"> $SPY $qqq $iwm $labu
We just had our 3 waves pullback, looking for bullish confirmation tomorrow or Friday for another leg up.
This time it will be ATH $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:34:57 </td>
   <td style="text-align:left;"> $SPY $QQQ

Give me a gap down!!! Futes watchers please make it happen.

I&amp;#39;ll make sure the donuts at continental breakfast are fresh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:32:06 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA is it time to sell and short everything? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:32:05 </td>
   <td style="text-align:left;"> $SPY $QQQ

Judging off the past few trading sessions of $TWTR pumping and $TSLA  dumping it’s starting to look like twitter has musk’s heart. I would even argue that Twitter is starting to look like the more dominant tech company than tesla... would you agree bulls?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:30:31 </td>
   <td style="text-align:left;"> $QQQ the dust will settle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:30:23 </td>
   <td style="text-align:left;"> $QQQ not too sound bearish but shit is mad expensive!!! even a gallon of milk! 🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:27:38 </td>
   <td style="text-align:left;"> $QQQ y’all know the drill… red futures at night…. Call buyers delight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:25:20 </td>
   <td style="text-align:left;"> $QQQ , $IWM, $SPY

Now do you understand why we’re fucked?

https://twitter.com/smitadeshmukh/status/1511561298609201153?t=9-Fvpx1P7MkYJWEZKJo8_A&amp;amp;s=08 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:24:20 </td>
   <td style="text-align:left;"> $QQQ all the paper hand babies sold today so tmr should be green cause everyone is starting to realize that the fomc isnt as bad as they thought so there just gonna buy back in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:22:54 </td>
   <td style="text-align:left;"> $QQQ holy smokas this ain’t no Jokas ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:22:48 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA more escalations wtf this is good for the environment and the world idiots  
 
https://amp.theguardian.com/world/2022/apr/06/as-ukraine-war-enters-new-phase-can-western-arms-turn-the-tide </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:22:15 </td>
   <td style="text-align:left;"> $QQQ meh Futes don’t mean anything until 3am when the dump or pump comes in….which has been dictating the moves for the rest of the day the past week 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:20:43 </td>
   <td style="text-align:left;"> $QQQ - Down another 2.25%-2.75% tomorrow. The Fed has spoken and specifically said it wants the stock markets down to help curb inflations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:19:19 </td>
   <td style="text-align:left;"> $SPY BULL RATS - ALMOST! 😆😂📈🐀💨   
 
MAN I made a nice HAUL TODAY!!! (same time , same place tomorrow💡💰😁)   
 
$tsla $rivn $rh $qqq - just getting comfortable to drop some evening  WEAR 👙🩱👀💦😁for twits tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:19:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 78132100. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:18:02 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F $QQQ $NDX 

Finished up call buying here 

Have to go to bed early tonight 

No one’s selling into Easter 🐣. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:17:40 </td>
   <td style="text-align:left;"> $QQQ $SPY market is definitely fked. Will break March low soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:17:21 </td>
   <td style="text-align:left;"> $QQQ 5% drop in 2 days is not enough! ? Insane! Let’s take a break! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:17:17 </td>
   <td style="text-align:left;"> $SPY  $QQQ I’ve seen BIG put volumes/OI get incinerated before. It’s called big Ooofism. Just saying don’t over leverage 📣🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:16:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  
 
Chinese authorities have extended their lockdown of Shanghai to cover all its 25 million people after a fresh surge in Covid cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:15:08 </td>
   <td style="text-align:left;"> $QQQ Holy smokes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:13:47 </td>
   <td style="text-align:left;"> $QQQ hit my target… I will re-evaluate tomorrow… very likely bearish… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:12:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Futures crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:11:32 </td>
   <td style="text-align:left;"> $QQQ lol that chart looks like my heart beat I’m a heavy smoker and drinker and I love weed lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:11:20 </td>
   <td style="text-align:left;"> Top Bearish Flow Today: $SPY $AAPL $NVDA $QQQ $XRT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:11:06 </td>
   <td style="text-align:left;"> $QQQ Fawking hell man.... Biden is finished, after just one year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:10:58 </td>
   <td style="text-align:left;"> $QQQ embrace the pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:09:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  
 
https://globalnews.ca/news/8740052/covid-19-deaths-hong-kong/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:09:37 </td>
   <td style="text-align:left;"> $QQQ $TSLA Remember folks. Cramer said we were out of the bear market and called the &amp;quot;bottom&amp;quot;. Do the opposite of whatever he says. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:08:13 </td>
   <td style="text-align:left;"> $QQQ don’t worry her period ends at $345 lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:08:03 </td>
   <td style="text-align:left;"> $QQQ well that was a nice close in the after mkt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:07:17 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY theres no end in sight folks, its all downhill from here... thank yourselves with who you voted for.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:06:23 </td>
   <td style="text-align:left;"> $QQQ dang can’t believe this cocksuckers started this bear shit again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:04:23 </td>
   <td style="text-align:left;"> $SPY $qqq - another day day tomorrow, 😌😌😌 
 
normally april will be good but i guess not this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:04:22 </td>
   <td style="text-align:left;"> $QQQ Red Thursday!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:03:43 </td>
   <td style="text-align:left;"> $SPY $QQQ 

I just wonder… what part of “reduction by $95B a month” was actually bullish? From +$120B to -$95B a month? That is like yanking the needle from a heroine junkie! Withdrawal symptoms will range from uncontrolled sobbing to mass shootings. It is over. UNLESS the market throws a major tantrum like the December 2018… oh then maybe just maybe Fed will give back the needle… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:03:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $95B a month… It will take 3+ years just to bring FED’s BS back to pre-pandemic levels. Not aggressive by any mean. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 08:01:43 </td>
   <td style="text-align:left;"> $QQQ This will be on the floor come tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:59:54 </td>
   <td style="text-align:left;"> $QQQ https://www.cnbc.com/amp/2022/04/06/uk-has-detected-a-new-covid-variant-heres-what-we-know-so-far-about-omicron-xe.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:58:58 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  
 
The news seems like we are heading back down more 
new variant of Covid  
6th wave of Covid 
war not ending soon 
inflation going up more 
unaffordable housing  
 
wtf I can’t catch a break </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:58:13 </td>
   <td style="text-align:left;"> $QQQ  
even Cramer bought SQQQ today for his club! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:58:04 </td>
   <td style="text-align:left;"> $QQQ wow this lost $1.30 in after hours lol. If futures go red, its a slow death tomorrow and Friday $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:57:22 </td>
   <td style="text-align:left;"> Spy has been in this channel from the 2006-2018(12 yrs) it’s been out of it for 2 years… this is how far we could fall. Just a warning. I think we’ll at the least test thr too if the channel. $SPY $QQQ $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:56:56 </td>
   <td style="text-align:left;"> $QQQ me looking at 3k$ worth of calls that expire Friday…. Gambling is a hell of a drug </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:56:55 </td>
   <td style="text-align:left;"> $SPY  $QQQ WTF Today drop with all stocks was not enough and Ah futures more red ? shame </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:56:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $DIA $NDX 

Bullish from now into Easter.  $4700’s.  Low Vol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:55:43 </td>
   <td style="text-align:left;"> $QQQ Lmfao I wish i could meet Biden to ask if he knows his approval rating is going to 0% if we see another 2% sell off tomorrow. Just saying.  
 
I don&amp;#39;t think any of these guys will escape the guillotines retail is preparing.  
 
With that said i bought 1 single call at the closing bell. Grats bears we going lower because of my actions. 😭 
 
No relief bounce... At least not in the futes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:54:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  Cheescake  chart caution for the $2 Billion Darkpool selling at $176!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:54:04 </td>
   <td style="text-align:left;"> $SPY $QQQ *Updated the March 30 #Nacho #Bot #Libre  Nasdaq Chart.  
 
#Caution after retesting ichimoku resistance/ flat cloud equilibirum level (26 day average of candle prices formed 26 days ago)  
 
momenum rolled over hard..  
 
expecting fast test of white line then cloud bottom. caution under cloud! for bearish trend below cloud) 
 
$2Billion in #QQQ Darkpool selling at $365! 
$2 $Billion in $AAPL Darkpool at $176  distribution  massive selling  
(will post separate $AAPLchart) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:53:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I just wanna be the first to congratulate put holders.

🧸 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:51:15 </td>
   <td style="text-align:left;"> $QQQ how many more years of Biden? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:49:20 </td>
   <td style="text-align:left;"> $SPY $QQQ futures gon fute but this market is quickly running out of unknowns to be afraid of. We have paths on rates, QT now, Putin failed, consumers still buying in the face of inflation. We go back up soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:48:45 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/AtJKHd_D0D8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:48:10 </td>
   <td style="text-align:left;"> $QQQ “don’t fight the market man, your losses could be catastrophic“ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:47:33 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:46:07 </td>
   <td style="text-align:left;"> $QQQ new bottom will be at 250 and lower! Don’t fight the Fed baby! It’s gonna be an ugly recession! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:45:03 </td>
   <td style="text-align:left;"> $QQQ I doubt this runs tomorrow morning but  if it does, $345Puts once it hits $358-359. But it looks more likely we’ll see $345 in the morning if futures keep dropping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:44:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ markets still bullish, block the noise and follow the price action 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:43:41 </td>
   <td style="text-align:left;"> $QQQ thought yall my need this. My son has Williams Syndrome and it made me laugh after the market open and throughout  the day. Despite loses.  
https://youtube.com/shorts/anYWkrX96tQ?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:43:02 </td>
   <td style="text-align:left;"> $QQQ $SPY down 5% in 2 days…ridiculous.   I swear if we get another gap down… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:42:31 </td>
   <td style="text-align:left;"> $QQQ Cramer said he has been doing his most selling during these times and then says you got to remain bullish and not sell most of your portfolio. Shame he says on thing and does another and admits to it at the same time. This market rally is ridiculous. Going up 16% in 11 trading days isn’t normal and I guess the Feds tightening is bullish as well. Majority of Americans can’t afford to pay 20% down payment snd 5%+ interest rates. Russia is back on the offensive and it’s shaking up supply chains along with China. China is just experiencing wave 2 or Covid while America has dealt with 3/4 waves already. They don’t have the immunity needed there and that’s where majority of our supplies come from.  Stagflation and a recession is right around the corner and once corporate earnings slow this quarter there definitely isn’t anything to be bullish about going foward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:41:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL ya&amp;#39;ll gon learn, boiiii </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:41:47 </td>
   <td style="text-align:left;"> $QQQ 3% down tomorrow and 5% down Friday. And you gonna see the VIX up to 40 bucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:38:03 </td>
   <td style="text-align:left;"> $QQQ $MRVL Co. is overvalued overbought overhyped on 5G Crap #cyclical $AMD $NVDA SMH Semiconductors going to take big hit as Fed induces hard rock landing Recession. United States GDP growth dramatically drops and so will Expensive Valuations for Chips;buy Lay’s or Doritos.
Market $SPY goes lower because of Fed Hawkishness and Super High Inflation for prolonged Timeframe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:37:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Turning every retail long into a swing trader. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:37:39 </td>
   <td style="text-align:left;"> $QQQ Futes moving down heavy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:37:35 </td>
   <td style="text-align:left;"> $QQQ  inverse h&amp;amp;s gets completed tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:37:28 </td>
   <td style="text-align:left;"> $QQQ how will the market replace the liquidity it got used to? sell to unsuspecting bag holders on rallies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:36:51 </td>
   <td style="text-align:left;"> $QQQ FUTES SHITTIN. LIFE SAVINGS DRIPPINNN. FUCK YOU JPOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:36:34 </td>
   <td style="text-align:left;"> $QQQ Triple Qs starting to finally show what tomorrow holds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:36:28 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:35:36 </td>
   <td style="text-align:left;"> $QQQ inverse H&amp;amp;S on 6 month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:32:51 </td>
   <td style="text-align:left;"> Guys I’m seeing $QQQ dropping to 2015 levels how do we see $BTC.X being effected during this. Trying to evaluate how the next few years will play out I don’t think Bitcoin will be effected to the scale of NASDAQ but today was concerning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:32:19 </td>
   <td style="text-align:left;"> $NQ_F  $NASDAQ  $QQQ  
 
👀 👀 👀 
Take a look at my last post... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:31:00 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ $IWM - The last time the Fed announced faster actions like faster tapering was in December. Anyone remember what happened in January? This is part two. All that liquidity they injected into the markets will start being removed. Markets are already reacting. I feel like the Fed actions will first hit markets, because they are more hesitant to get MBS off their sheets. They can allow markets to tank as they will let the stock market find a logical price instead of trading anywhere from 20x to 150x valuation. I think about it, Apple was trading at $20-40 before the pandemic. We will see markets return to their means and more logical valuation. Morgan Stanley has called for it, and more analyst have called for at 20% haircut at least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:30:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA oh ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:26:54 </td>
   <td style="text-align:left;"> $QQQ $spy 2009-2020 was great then the fed wanted to hurt us f you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:26:08 </td>
   <td style="text-align:left;"> $SPY $QQQ the end of the bull is near. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:20:41 </td>
   <td style="text-align:left;"> $QQQ $TSLA $SPY 

Couldnt post earlier here ya go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:18:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Fed literally telling you they need the markets to go down, and open to a hard landing if required.  It’s as simple as that.  Sell rallies, ride the momentum down on days like today till we get closer to historical averages. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:18:16 </td>
   <td style="text-align:left;"> S&amp;amp;P Sectors: Median mkt still UP 
 
$SPY $QQQ $DIA $XLK $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:15:28 </td>
   <td style="text-align:left;"> The Fed’s plan to rapidly slash its balance sheet is out. Here’s what happens to money in the system. https://www.billionaireclubcollc.com/the-feds-plan-to-rapidly-slash-its-balance-sheet-is-out-heres-what-happens-to-money-in-the-system/  $SPY $QQQ $DXY $DJIA $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:14:09 </td>
   <td style="text-align:left;"> $SPY green bounce tomorrow $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:09:07 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Yall still falling for this dog&amp;amp;pony show?. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:08:41 </td>
   <td style="text-align:left;"> $QQQ Its so peaceful on the days bulls get rugged... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:08:02 </td>
   <td style="text-align:left;"> $SPY: setting up for Cup and handle

$QQQ: Inverse H&amp;amp;S 

📊🔜 🐂💎💰💵🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:03:54 </td>
   <td style="text-align:left;"> $QQQ Inverse H&amp;amp;S is that u?? 🧐 speedy recovery is around the corner 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:03:09 </td>
   <td style="text-align:left;"> $QQQ Ahmed is coming for your stonks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 07:01:32 </td>
   <td style="text-align:left;"> $QQQ Added calls eod today here. Technical bounce expected after brutal back to back red days. Target 358 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:59:39 </td>
   <td style="text-align:left;"> $DDOG $QQQ
https://www.datadoghq.com/blog/function-urls-monitoring/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:58:44 </td>
   <td style="text-align:left;"> $QQQ today was a buy…ask me in six nonths </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:57:24 </td>
   <td style="text-align:left;"> Six-days-a-week mail delivery saved; Biden signs Postal bill https://www.billionaireclubcollc.com/six-days-a-week-mail-delivery-saved-biden-signs-postal-bill/ $DJIA $QQQ $DXY $VIX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:56:32 </td>
   <td style="text-align:left;"> $BABA 448,261 shares in dark pool after hours and $BIDU 365,057 shares. Something is brewing.

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:52:42 </td>
   <td style="text-align:left;"> $QQQ I have diamond balls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:52:27 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:52:02 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA crooks and unpatriotic  
 
https://www.cnn.com/2022/04/06/investing/short-selling-oil-consumer-stocks/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:51:57 </td>
   <td style="text-align:left;"> $QQQ DEMOCRATS are POS. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:51:15 </td>
   <td style="text-align:left;"> $QQQ when you think it will go much lower…buy some now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:50:37 </td>
   <td style="text-align:left;"> $QQQ cramer just made a good case for being bullish 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:49:36 </td>
   <td style="text-align:left;"> $SPY $qqq shame on you fed it is tax time and people are on vacation and you are purposely crashing the markets you dumb incompetent idiots knew that it was not transitory inflation you fu$&amp;amp;’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:49:03 </td>
   <td style="text-align:left;"> $QQQ we only away 2% from the percentage drop of covid lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:48:38 </td>
   <td style="text-align:left;"> $qqq and bulls are happy about this ?  Why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:47:09 </td>
   <td style="text-align:left;"> $QQQ this going back to $319 where it came from </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:44:40 </td>
   <td style="text-align:left;"> $QQQ 🤣🤣🤣

https://youtu.be/hHUbLv4ThOo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:39:39 </td>
   <td style="text-align:left;"> $AAPL ....My Goodness where are all the chart hating Pumpers now...🤷‍♂️ As of now we&amp;#39;ve got from a $178 to $171.... Just gonna keep screenshot within screenshot until this goes to a $150...ish....$TSLA $SPY $QQQ $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:39:28 </td>
   <td style="text-align:left;"> $QQQ $spy never had a year during tax season f me so hard. Loosing $10,000 daily for months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:37:35 </td>
   <td style="text-align:left;"> $QQQ actually after further analysis, this will test $345 IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:34:06 </td>
   <td style="text-align:left;"> $QQQ are we pricing in a recession? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:31:08 </td>
   <td style="text-align:left;"> $ARKK $QQQ $SPY .. potential for tomorrow to be a green day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:29:20 </td>
   <td style="text-align:left;"> $MULN $QQQ When u put 2 &amp;amp; 2 together 🤔🤑

Fyi, Comau (COnsorzio MAcchine Utensili) is an Italian multinational company based in Turin, Italy and is part of automaker Stellantis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:27:44 </td>
   <td style="text-align:left;"> $TMC is up 5.13% Today. Insiders are loading the boat! Something huge is coming up! Nickel shortage is now a matter of national security! $DJIA $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:27:21 </td>
   <td style="text-align:left;"> $QQQ bullish pattern </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:26:59 </td>
   <td style="text-align:left;"> $QQQ $360 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:26:54 </td>
   <td style="text-align:left;"> $QQQ $SPY tomorrow&amp;#39;s theme song.

https://youtu.be/BfnjX88Va4Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:24:14 </td>
   <td style="text-align:left;"> $QQQ we Will be f upped by the fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:20:04 </td>
   <td style="text-align:left;"> $TMC Boom! Latest update on the company with the World&amp;#39;s Largest Nickel Reserves!  
-TMC is up 5.13% in the sea of red. 
-TMC insiders bought a total of 6.2 millions of shares with $3.02 average. 
-US oil and gas giants $RIG and $OIS transitioning into Deepsea Mining. 
-TMC and Epsilon Carbon have signed an agreement to set up the world&amp;#39;s first polymetallic nodules processing plant. 
-Price is above 20, 50, and 100 Moving Averages.  
-MACD Bullish Crossover on the daily chart 
-RSI Cooled down and set-up for another run 
-Technical Analysis showing &amp;quot;BUY&amp;quot; on  Tradingview&amp;#39;s daily chart 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:18:38 </td>
   <td style="text-align:left;"> $SPY $qqq good time to be all cash the end is near </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:18:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’m gonna ride this pig down like dr. burry in 08 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:18:00 </td>
   <td style="text-align:left;"> $QQQ is currently showing a bull flag pattern! A bull flag pattern is a pull back after a strong rise up. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:17:26 </td>
   <td style="text-align:left;"> $SPY $qqq this market has been shit since Feb 12,2021………. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:16:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $BTC.X  
 
Time for Red States to bus iIIegaI immigrants to DeIaware, Connecticut, Vermont and Washington DC 
 
If Democrats want them they shouId take them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:16:18 </td>
   <td style="text-align:left;"> $QQQ $SPY Ya ya ya ya....Pump Now and dump hard soon enough loll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:15:28 </td>
   <td style="text-align:left;"> $DJIA Very interesting... 240p/250p... 
 
https://twitter.com/MeisaBonelli/status/1511829420549578753?s=20&amp;amp;t=d3_qzxvPkZqnXn9EtoW3dw 
 
$SPY $IYT $DJT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:15:18 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:14:54 </td>
   <td style="text-align:left;"> $QQQ does market go up infinitely? is it an infinite number? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:14:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC $BTC.X  
 
The Biden government is using American tax doIIars to buy android phones for iIIegaI immigrants 
 
Money weII spent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:11:33 </td>
   <td style="text-align:left;"> $NQ_F: Bounced right above the 50 sma (14324.11). This is the level to watch. Under that, we see next leg down. Hard to be bullish until bulls can plow through the 200 sma (15148.88). Until then, mentality has to be, sell the rips.&amp;quot; 
$QQQ $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:10:51 </td>
   <td style="text-align:left;"> $SPY $qqq $dia

Slowdown is here

https://youtu.be/L4DcAJah2lE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:08:23 </td>
   <td style="text-align:left;"> $SPY $QQQ

once again, if you inverse Lord Quas you get Madlib so that&amp;#39;s fine with us either way. You have a choice!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:07:10 </td>
   <td style="text-align:left;"> $QQQ $DXY  $VIX $SPY $DJIA  What Is The Yield Curve Saying? https://www.billionaireclubcollc.com/what-is-the-yield-curve-saying/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:06:44 </td>
   <td style="text-align:left;"> $QQQ That is not a bullish chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:05:53 </td>
   <td style="text-align:left;"> $QQQ fill the gap tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:05:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
The markets keeps on 
Bullshitting  and Bullshitting Over and Over and Over… Never Ending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:04:40 </td>
   <td style="text-align:left;"> $QQQ Hoping we ReTest $350 again &amp;amp; then blast off. Or we just blast off lol either way I’m </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:04:15 </td>
   <td style="text-align:left;"> $QQQ next week&amp;#39;s CPI/PPI print will be the worst one yet. Feds have shown they will act on bad inflation numbers. They have tipped their hands and will be removing billions every month from their balance sheet to combat inflation. This will lead to a huge amount of liquidity leaving the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:03:50 </td>
   <td style="text-align:left;"> $QQQ obscenely inappropriate fed manipulation this week they are trying to crush the markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:02:18 </td>
   <td style="text-align:left;"> $QQQ $SPY if these were going to recover it would of closed stronger. they are just toying with options but we have all caught on to them by now. Expect them to step aside tomorrow and watch her work with no interference. going to dump so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:01:54 </td>
   <td style="text-align:left;"> $SPY $QQQ what a fucking amazing day. Made 60k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 06:00:55 </td>
   <td style="text-align:left;"> $QQQ double top formation looks scary ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:58:58 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Potential large Inverse Head and Shoulders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:58:48 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 4/4/2022 for #Stocks #Bitcoin #Gold and #Silver 
 
Congrats fam, we are killing it!  
$SPY $QQQ $IWM $TLT $UUP  
https://www.youtube.com/watch?v=ymOhlFnA_hI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:58:21 </td>
   <td style="text-align:left;"> $QQQ 370 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:55:48 </td>
   <td style="text-align:left;"> $SPY give it up feds, hedges, only ppl buying right now are options gamblers. The volume tells the story. retail is barely has money left to chase. Big dip incoming $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:55:35 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:55:15 </td>
   <td style="text-align:left;"> Yellen: Russia’s invasion will have ‘enormous repercussions’ https://www.billionaireclubcollc.com/yellen-russias-invasion-will-have-enormous-repercussions/ $DJIA $QQQ $SPY $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:55:10 </td>
   <td style="text-align:left;"> $PLTR $SPY $QQQ 

Why  can’t the fed let us have nice things , I mean let’s be clear the only way out of this mess is absolute global default so let’s just crank it up get rich and hope our kids aren’t complete failures like the baby boom generation , and fix this broken casino . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:54:45 </td>
   <td style="text-align:left;"> $QQQ Will see $345 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:54:18 </td>
   <td style="text-align:left;"> https://twitter.com/i/spaces/1ypKdElmqVQGW 
$SST $SPY $QQQ $UVXY $VIXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:53:53 </td>
   <td style="text-align:left;"> $SPY puts we’re only up like 100-120% today. Outside of 0dte. And ya think the dip is over? Alot more incoming And fast. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:53:45 </td>
   <td style="text-align:left;"> I am sorry $TSLA bulls.  
BUT if you were to look at this where do you think we go?  
Don&amp;#39;t deny that we have to try and complete the gap-fill and more than likely wick off 1000.  
All we don&amp;#39;t want to see is TSLA get below 1000 and start rejecting. 
 
P.S LONG-TERM I am BULLISH! 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:52:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X someone want to explain how bitcoins intraday chart is identical to the spy and qqq index lmao. Can’t make this shit up and y’all trust this market? Market going to bleed into Friday close. MARK IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:52:47 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Please queue up a gap down so we may test a dip buy. Thank you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:51:13 </td>
   <td style="text-align:left;"> $SST confirmed huge itm call options purchased today before close $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:50:46 </td>
   <td style="text-align:left;"> $SST confirmed heavy shorts  and cost of borrowing $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:50:25 </td>
   <td style="text-align:left;"> $SST confirmed unable to provide shares for call contracts exercised $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:49:57 </td>
   <td style="text-align:left;"> $SST confirmed locked shares 700k float $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:49:28 </td>
   <td style="text-align:left;"> $SST strong fundamentals $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:49:09 </td>
   <td style="text-align:left;"> $SST #1 on short squeeze list for fintel $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:47:47 </td>
   <td style="text-align:left;"> $QQQ What if we do with inflation like Democrats do with gender and say we identify as having 0 percent inflation. Would that work??? Just thinking how we can fix everything Biden screwed up, using Democrat solutions. What if we just call inflation racist? Will it lower itself to prove it&amp;#39;s not racist???​ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:46:31 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load up what a joke!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:44:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
I love how the FED will be reducing their balance sheet *up to* 95 Billion a month. 
 
Two questions... 
 
1) How much will they *actually* roll off each month? 
 
2) Who is going to buy these Treasuries and MBS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:40:58 </td>
   <td style="text-align:left;"> $QQQ $NVDA $TSLA $SPY https://www.youtube.com/watch?v=JlEGU2ypr1Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:39:05 </td>
   <td style="text-align:left;"> $QQQ I honestly see in the next 18-24 months a recession that will make 2008 seem small. How and why

Inflation crazy high. Property values crazy high. Taxes crazy high. Rent and daily living crazy high.

Pay 7.25 an hour federally and on average $11-15 most places

No more pua/unemployment/stimulus.
Rate hikes coming.

A lot of uncertainty covid/jobs/war.

2008 rich took a hit too. Since 2020 rich got even richer.

Everything is setting up for significant decline as rates and inflation stay high and wage is low. This is far bigger then just the banking system over extending credit and utilization of variable apr. Every single institution is ready to burst </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:38:37 </td>
   <td style="text-align:left;"> $QQQ omg lost my 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:36:24 </td>
   <td style="text-align:left;"> $QQQ $SPY $UVXY $XRT $BTC.X 
https://youtu.be/SWdZPIlHi_Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:34:52 </td>
   <td style="text-align:left;"> $QQQ bulls be like don’t fight the fed. Ya bitch don’t fight the fed they is tightening lol 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:34:13 </td>
   <td style="text-align:left;"> $QQQ holy smokas this ain’t no Jokas! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:30:55 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/6/2022 $SPY $QQQ $NVDA $TSLA $FB https://www.youtube.com/watch?v=R1H-HyeAHAw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:27:48 </td>
   <td style="text-align:left;"> Russia to pay bonds in rubles, which may cause default https://www.billionaireclubcollc.com/russia-to-pay-bonds-in-rubles-which-may-cause-default/ $DJIA $QQQ $SPY $VIX $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:25:53 </td>
   <td style="text-align:left;"> $QQQ bulls are so conditioned and been blessed with such a parabolic market that they become complacent. Well your in for a rude awakening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:25:44 </td>
   <td style="text-align:left;"> $SST big bid after hours $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:21:57 </td>
   <td style="text-align:left;"> $SST https://youtu.be/SWdZPIlHi_Y 
you really need to watch this asap 
$SPY $QQQ $VIXX $UVXY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:20:10 </td>
   <td style="text-align:left;"> $QQQ  200 DMA Krypotnite </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:19:10 </td>
   <td style="text-align:left;"> Update on TQQQ- Was going to swing this to 55.30 but due to increased buying pressure we managed to hit our goal today. Saw a lot of activity around the $52.70 level. All out of this now. 4 hour frame looks good but daily frame does not in my opinion. Will re-evaluate price action tomorrow during pre-market and send out more alerts. Congratulations again bulls, you nailed it again. $SQQQ $QQQ $NQ_F

Alert on $TQQQ delivered today at 1:25PM CDT on 4/6/2022 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:17:13 </td>
   <td style="text-align:left;"> $QQQ Yahoo finance at it again with the &amp;quot;and that&amp;#39;s a good thing&amp;quot; articles. Absolutely trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:15:49 </td>
   <td style="text-align:left;"> Average Equity Sector Performance  between Inversions and Recessions 🔻

$SPX $IWM $TLT $QQQ $VIX

#unitedtraders #news #recession #stockmarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:15:45 </td>
   <td style="text-align:left;"> $SPY $QQQ All of that because of the  Clowns who elected sleepy Joe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:15:32 </td>
   <td style="text-align:left;"> $QQQ $SPY Tf is the balance sheet at $9 trillion in the first place?!😂🤦‍♂️🤦‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:14:31 </td>
   <td style="text-align:left;"> $SPY $QQQ
Went to an all vegetarian Indian restaurant for lunch and one of the small dishes was lentil soup.  No wonder market tanked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:11:40 </td>
   <td style="text-align:left;"> $QQQ find out who are the groomers in your kids school and have them fired </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:10:30 </td>
   <td style="text-align:left;"> $QQQ I annihilated all the bulls today with my 360 PUT from the other day. 94% green on this trade in less than 4 days. Muahahah!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:09:41 </td>
   <td style="text-align:left;"> $QQQ $SPY wen -5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:06:11 </td>
   <td style="text-align:left;"> $QQQ top 10 (54% market cap). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 05:06:07 </td>
   <td style="text-align:left;"> $AMC $GME $QQQ $SPY . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:58:49 </td>
   <td style="text-align:left;"> $WMT Wow here’s shareholders of WallMart Break Out Pattern. Brand New High Now

 $gme $amc $spy $qqq    WallMart play the Break Out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:56:23 </td>
   <td style="text-align:left;"> $NASDAQ $QQQ composite into support, but flat moving averages = trend is sideways </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:55:53 </td>
   <td style="text-align:left;"> Its going to be a wild summer. $QQQ $TSLA $GLD $SLV $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:55:43 </td>
   <td style="text-align:left;"> $SPY $QQQ A moment of silence for the traders we lost in the chop and volatility  over the last few weeks. You will be missed.  🪦🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:55:07 </td>
   <td style="text-align:left;"> $SPY $QQQ A lot of the FED hawkishness have already priced into the market. The QT and higher rates are not going to slow the US economy down all that much due to the strong pent up demand and consumers having a great balance sheet, stocks should continue to move higher as long as the US economy continues to boom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:53:34 </td>
   <td style="text-align:left;"> $QQQ https://vimeo.com/696714995 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:53:34 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $IWN  
 
You thought 3 weeks ago was bad, wait just wait.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:53:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  hold up… the US doesn’t have hypersonic missiles? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:52:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SO SINCE THE FED WONT BE PRINTING ANYMORE DOES THAT MEAN THAT NOW WE GO RBBBBBBBBBBBBBBBBB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:52:36 </td>
   <td style="text-align:left;"> $QQQ Unsure about directions, but looks like it&amp;#39;s a little more bullish for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:52:00 </td>
   <td style="text-align:left;"> $QQQ “Don’t fight the Fed” works in both directions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:50:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM still looking to re-buy these (my 3/28 tweet) 
As bad as $SPX was today, I did NOT sense &amp;quot;panic&amp;quot; 
Perhaps, a couple more % down would do it 
For bar counters, DM gave a 13buy signal on $QQQ today (fwiw, it&amp;#39;s been 100% correct on buy signals this year) 
Anyone long/short today?  Which stocks/ETFs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:50:28 </td>
   <td style="text-align:left;"> $QQQ we here at the bear reserve believe that corporate earnings have peaked, and that peak could be summarized as transitory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:50:23 </td>
   <td style="text-align:left;"> $QQQ Well the minutes said what everyone was thinking.. I don’t think they will raise by .5  can’t kill or all at once </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:50:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Short every rip from here on out bears, it’s over for the fed backed bull.😤

🧸 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:48:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Why would the Fed not move as hard and fast as they can to tamp down 8% inflation? That&amp;#39;s what they should have been doing when it got to 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:46:14 </td>
   <td style="text-align:left;"> Today was Dohawkishy. Markets ruining put and call holders. Be careful folks. It may seems as if we are outnumbered, but slowly the tides are turning.  $SPY $QQQ $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:44:14 </td>
   <td style="text-align:left;"> $SPY raise your pitiful hands if you bought puts at daily 20ma… lol clowns.

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:44:13 </td>
   <td style="text-align:left;"> $TMC Harvesting of polymetallic nodules is the future of mining battery metals needed for energy transition.

US oil and gas giant Oil states $OIS is transitioning into this new frontier.

 $QQQ $SPY $DJIA 

https://twitter.com/OilStatesInd/status/1511267502113837060 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:41:45 </td>
   <td style="text-align:left;"> $SST huge call option print today $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:41:20 </td>
   <td style="text-align:left;"> $SST #1 on fintel short squeeze list $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:41:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ The sky is falling scenario in the markets...chicken little once again... China keeps buying first then the sheep and knuckleheads chase. Chop no doubt but not once did they mention oil price today and a few other things on our checklist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:40:58 </td>
   <td style="text-align:left;"> $SST cost to borrow data $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:40:40 </td>
   <td style="text-align:left;"> $SST first notice of FTD as market makers unable to find shares for exercised calls $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:40:11 </td>
   <td style="text-align:left;"> $SST 2nd point of confirmation of tradable float due to lock up $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:39:44 </td>
   <td style="text-align:left;"> $SST confirmation from IR of tradable float of 700k $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:39:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:39:11 </td>
   <td style="text-align:left;"> $SST full thesis get caught up $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:39:07 </td>
   <td style="text-align:left;"> $QQQ This is bear country, roar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:38:14 </td>
   <td style="text-align:left;"> $SPY $QQQ

STUMBLE &amp;#39;TIL YOU CRAWL
sinking into
SWEET UNCERTAINTY!!!

Enjoy

https://youtu.be/ROatPGGMvXg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:36:36 </td>
   <td style="text-align:left;"> Ukraine braces for new Russian offensive in the east https://www.billionaireclubcollc.com/ukraine-braces-for-new-russian-offensive-in-the-east/  $DJIA $SPY $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:36:09 </td>
   <td style="text-align:left;"> $QQQ ended the day on a perfect H/S </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:34:03 </td>
   <td style="text-align:left;"> $IRNT distance from Washington DC=13 miles
Distance from the pentagon=13 miles
Distance from NSA headquarters=40 miles
Coincidence? I think not $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:33:18 </td>
   <td style="text-align:left;"> $SPY $qqq GREEN DAY TODAY for a NORMAL index, but usa is trash country hence why its red and trash vs ewu green index........ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:32:12 </td>
   <td style="text-align:left;"> $QQQ dumbbulls will buy tech dip for earnings. Tell me I&amp;#39;m wrong. You see what retail did pushing this shit up with no volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:31:18 </td>
   <td style="text-align:left;"> $TMC Video of US Oil and Gas Company Transocean talking about their transition into harvesting of  polymetallic nodules. $RIG  
 
$SPY $QQQ $DJIA  
 
https://ch.linkedin.com/company/transocean?trk=organization-update_share-update_actor-text </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:29:46 </td>
   <td style="text-align:left;"> Fed Officials Weigh In On Pruning Balance Sheet by $95 Million Per Month $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:29:11 </td>
   <td style="text-align:left;"> $QQQ  
 
QQQ Key Levels Grid for Apr 7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:28:08 </td>
   <td style="text-align:left;"> EXPLAINER: Biden extends student loan freeze through August 2022.  https://www.billionaireclubcollc.com/explainer-biden-extends-student-loan-freeze-through-august/ $DJIA $QQQ $DXY $VIX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:27:39 </td>
   <td style="text-align:left;"> $QQQ next two days will be interesting, hope it bounces to short EOD Friday into economic data next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:27:30 </td>
   <td style="text-align:left;"> $QQQ $SPY the Q’s are well below their 200dma.  Just how much fn more selling can there be. 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:26:22 </td>
   <td style="text-align:left;"> $WMT   $COST $DIA $QQQ $SPY  New High 

From  what I know WallMart owns Sam’s Club </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:25:06 </td>
   <td style="text-align:left;"> $QQQ You have to be a complete moron or a virgin investor/ trader if you are bullish over the next 6 months when the fed is telling you that the stock market has got to go down to help elevate inflation 

Prepared to get fucked virgins 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:23:40 </td>
   <td style="text-align:left;"> EXPLAINER: A look at West’s escalating sanctions on Russia https://www.billionaireclubcollc.com/explainer-a-look-at-wests-escalating-sanctions-on-russia/  $DJIA $DXY $SPY $QQQ $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:23:12 </td>
   <td style="text-align:left;"> $COST bring your money to $WMT 

Costco broke out from $185 to $600.  

WallMart made a brand new high 

It could jump $25 - $50 or more from here easy on a short squeeze in play $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:23:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:22:29 </td>
   <td style="text-align:left;"> $QQQ Does options move indexes or is it a myth? Why does an index move? Becauae od stocks right? But what else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:21:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
This joke of a market decided not to trade on fundamentals anymore.. 
this is just bulls and bears tugging prices… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:21:01 </td>
   <td style="text-align:left;"> Live Updates | Mayor: Over 5,000 civilians dead in Mariupol https://www.billionaireclubcollc.com/live-updates-mayor-over-5000-civilians-dead-in-mariupol/  $SPY $DJIA $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:19:38 </td>
   <td style="text-align:left;"> Stocks fall, yields rise as Fed details inflation efforts https://www.billionaireclubcollc.com/stocks-fall-yields-rise-as-fed-details-inflation-efforts/  $DJIA $QQQ $SPY $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:19:29 </td>
   <td style="text-align:left;"> $QQQ 
$346 tomo or lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:19:20 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Burn it to the ground!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:18:45 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM The most sensible thing CNBC has said in a while... Don&amp;#39;t fight the fed on the way down. Liquidity is rapidly drying up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:17:18 </td>
   <td style="text-align:left;"> $SAVA $NIO $UVXY $QQQ those ups and downs are simple Fibonacci levels... 

https://www.investopedia.com/articles/active-trading/091114/strategies-trading-fibonacci-retracements.asp

This is proof the algos control like 99% of all trades. Unemotional except when trying to look emotional. What goes down is an stop loss hunt and margin stretching until at about 63% everyone who was exchausted and destroyed is in so the new resistance level is created from which an inevitable rebound is created.
My AI sees this as clear as day...  hence why algo trading can be profitable because intra day the patterns are anything but random but you need to pierce the veil of several layers. 

here&amp;#39;s the most glaring way to decompose those patterns using Fourier analysis!

http://maxmatsuda.com/Papers/2004/Matsuda%20Intro%20FT%20Pricing.pdf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:17:10 </td>
   <td style="text-align:left;"> $SST -700k float due to share lockup
-cost to borrow for shorts is as high as 700%
-company ER was stellar
-not enough shares to cover itm calls so they will be forced to buy for their FTD&amp;#39;s
-huge print on itm calls today 
-huge move on warrants as well
Get ready Gamma squeeze is coming

🔥🔥🔥

$spy $qqq $gme $amc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:16:14 </td>
   <td style="text-align:left;"> They just pumped $FB AH all about an Elon post sad as fuck. 
If this runs I’m suing Elon and who ever else FACTS!!! 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:16:03 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
I want to see some real fear in this market...total panic selling! 
 
Let&amp;#39;s get this party started!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:15:47 </td>
   <td style="text-align:left;"> $SMH $QQQ price action is out of mind - GO! $NVDA $AOSL $HIMX https://www.semiconductors.org/global-semiconductor-sales-increase-32-4-year-to-year-3-4-month-to-month-in-february/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:15:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$1.519B to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:15:15 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:14:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:13:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:13:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 4/7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:12:14 </td>
   <td style="text-align:left;"> $QQQ Held my NASDAQ calls overnight, might have an aneurysm, might make a grand, tough to say. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:11:15 </td>
   <td style="text-align:left;"> latex9359a83b26c415a1f7fb23ef7bc230e0SPY 
$QQQ 
  
NEWS ALERT  
SEC Is Investigating How Amazon Disclosed Business Practices  
  
Federal securities regulators are investigating how Amazon has disclosed certain details of its business practices, including how it uses third-party-seller data for its private-label business, according to people familiar with the matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:11:00 </td>
   <td style="text-align:left;"> $QQQ: The short term trend is positive, while the long term trend is neutral. So this is evolving in the right dir ... https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:10:13 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Bears are back! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:10:13 </td>
   <td style="text-align:left;"> $QQQ $AMZN Perfect timing with talks of a potential recession on the way. $SPY  
 
 
NEWS ALERT 
SEC Is Investigating How Amazon Disclosed Business Practices 
 
Federal securities regulators are investigating how Amazon.com has disclosed certain details of its business practices, including how it uses third-party-seller data for its private-label business, according to people familiar with the matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:09:48 </td>
   <td style="text-align:left;"> $SST huge options prints today, #1 on fintels short squeeze list too $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:09:18 </td>
   <td style="text-align:left;"> $QQQ The pain will continue this week get your puts ready. Hope you had fun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:08:30 </td>
   <td style="text-align:left;"> $QQQ rejected at the 10min 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:08:25 </td>
   <td style="text-align:left;"> $SPY $QQQ Tom Lee on CNBC now, he remains bullish and he has made a lot of good calls on the market in the past </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:08:21 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Gonna be fun to watch bulls try and run bears out of their shorts when the FED is no longer printing Trillions of free dollars and suppressing rates at 0%. 
 
Bears know bulls are fucked. 
 
They are done taking shit from FED-sponsored bulls!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:07:54 </td>
   <td style="text-align:left;"> $SPY $QQQ At 17.5% cash.  Sold $TSM for a loss and $MSFT for a profit. Restarted a position in $QCOM 

I&amp;#39;m sticking with my theme of dividend focus and &amp;quot;growth at a reasonable price&amp;quot; that I adopted since Fall 2021.

My accounts were up 0.26% today despite the carnage. 0.5% off all time highs. I&amp;#39;m going to stick with my discipline, trades, and investments. It has been working so far for me. Good luck everyone! ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:07:28 </td>
   <td style="text-align:left;"> $QQQ The time for technicals is over, we must make a sacrifice to the market gods </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:06:28 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DJIA 

you guys need to watch the futes EXTRA HARD tonight, thanks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:06:16 </td>
   <td style="text-align:left;"> $MRVL This Company is overhyped 5G Crap 
They don’t make any substantial money lol
Earnings will be coming down due to Recession 
ALL OF These have expensive valuations 
$AMD $NVDA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:53 </td>
   <td style="text-align:left;"> $QQQ gonna pump hard tmr now that all the fear is gone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:51 </td>
   <td style="text-align:left;"> $QQQ $SPY  shorted every pop today.  what fun. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:46 </td>
   <td style="text-align:left;"> $QQQ those spikes are crazy. What kind of wild trading are people doing on an entire index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:39 </td>
   <td style="text-align:left;"> $QQQ 🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:14 </td>
   <td style="text-align:left;"> $QQQ should have came to $SONN for that nice push at the end. From -6% to almost +2% and we&amp;#39;ve noticed it&amp;#39;s just passing the consolidation and should see some bigger gains very soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:13 </td>
   <td style="text-align:left;"> $SPY $QQQ  Closed near VWAP after a day algo spikes in both directions lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-07 04:05:01 </td>
   <td style="text-align:left;"> $QQQ $SPY 

WHAT A DAY!!!!!

SEE YAH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:21:45 </td>
   <td style="text-align:left;"> $SPY  $AAPL $TSLA 
Tomorrow QE pump for “Soft landing”  👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:19:08 </td>
   <td style="text-align:left;"> $AAPL $AMD All that you need to know... Shorts haven&amp;#39;t covered a single share... Check it out below.   
 
Highly recommend everyone to follow them.   
http://live-stock-alerts.coordinatetrading.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:14:28 </td>
   <td style="text-align:left;"> $SPY  $AAPL $TSLA $SNOW $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:11:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $NVDA $SPY 
Bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:09:34 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $JPM 
🥶 $95B cut per month &amp;amp; 0.5% hike
https://www.cnbc.com/2022/04/06/fed-minutes-march-2022-meetings-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:08:09 </td>
   <td style="text-align:left;"> $AAPL 20% from high is standard. Likely glide as casual as possible, simulate false recovery, then take it down into deep recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:01:23 </td>
   <td style="text-align:left;"> $AAPL $SPY @Amazontacular lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 09:01:15 </td>
   <td style="text-align:left;"> $AAPL So long as apple doesn&amp;#39;t have a supply chain, bullish sign is outa there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:58:36 </td>
   <td style="text-align:left;"> $AAPL I have those 170s and 165 puts. People say you can&amp;#39;t time the market... its not true. first year, lack of experience  and knowledge in general huge handicap. Hard work get u up to speed. experience is better. 2k to 3 mil last year. 3 mil to 20 k by feb. working way back up off the downside. jpyusd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:57:34 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 1: $SPY $AAPL $SST $FB $ULCC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:57:17 </td>
   <td style="text-align:left;"> $AAPL - Apple stock fell 1.85% to 171.83, but rebounded from its 21-day exponential moving average. Wednesday&amp;#39;s intraday drop offered a bit more of a shakeout in the tech titan&amp;#39;s handle in the double-bottom base. The proper buy point is 179.71. It&amp;#39;s possible Apple stock will form a three-weeks-tight after Friday&amp;#39;s close, though that wouldn&amp;#39;t offer a different entry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:56:52 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s get to 3 trillion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:54:52 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s see tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:41:57 </td>
   <td style="text-align:left;"> $AAPL $TWTR $TSLA What does the most powerful trading platform do for its members? Let’s take a look shall we?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:38:05 </td>
   <td style="text-align:left;"> $SQQQ 

I think $AAPL  is a buy around $125 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:36:23 </td>
   <td style="text-align:left;"> $AAPL wtf about red day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:33:22 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s up apple bro&amp;#39;s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:28:55 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $160.00 Put for Friday, April 29, 2022. Roughly 191 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:28:52 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $185.00 Call for Friday, May 20, 2022. Roughly 3 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:27:00 </td>
   <td style="text-align:left;"> $AAPL Poor moronic bears 🐻 are posting “news” from last month (3/14/22) to justify their bearish view. Really shows that they don’t have anything to justify their unhinged bearishness !
Go to Russell companies that are loosing money not a number one money maker!🤮😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:26:11 </td>
   <td style="text-align:left;"> $FSR  $AAPL  $TSLA 
What&amp;#39;s a Fisker? Still early.

FISKER 2022 - it&amp;#39;s a start up
https://youtu.be/ezn6iY6LzIU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:23:20 </td>
   <td style="text-align:left;"> $AAPL Great job team!!! Keep up the great work tomorrow… Holding above $170 SP Thursday &amp;amp; Friday … 👁 4/8 Puts expire &amp;amp; a small wager… 👍 or 👎 🥂🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:16:55 </td>
   <td style="text-align:left;"> In our NEW technical analysis series: 
 
We talk how $AAPL is nearing a crucial trend-line that will test its true strength. Make sure to mark it on your charts! 
 
Watch video 👉: http://youtu.be/eaoMJnAxOyQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:16:12 </td>
   <td style="text-align:left;"> $AAPL BTW troops, the lives sacriced over the past two decades serving your country mean Jack sht bc we fed around and crashed out with China. So tuck tail and run boys.  
 
Ps support Ukraine war.  
 
Ukraine btch ass ugly mf can suck my American. Got nothing to do with me or </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:15:37 </td>
   <td style="text-align:left;"> $AAPL 

But do it hit the 168 this week tho? 

That would be sensational. Make sure future is ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:15:19 </td>
   <td style="text-align:left;"> $AAPL https://www.ped30.com/2022/04/06/apple-airpods-teens-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:13:44 </td>
   <td style="text-align:left;"> $SBFM   should be worth with CRUE FOR CANCER  $25 -$58 &amp;amp; full range up ....HOLD ON u will see ..next SPRT $DWAC $INDO &amp;amp; $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:12:43 </td>
   <td style="text-align:left;"> $AAPL Nice close. Tomorrow gonna be drama </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:11:30 </td>
   <td style="text-align:left;"> $AAPL Let&amp;#39;s trade battle china.China.. The supply of our economic wealth. Especially since allied with our fuel supply. say bye to your cars. I want to hurt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:11:20 </td>
   <td style="text-align:left;"> Top Bearish Flow Today: $SPY $AAPL $NVDA $QQQ $XRT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:09:45 </td>
   <td style="text-align:left;"> $AAPL Apples 3 Trillion USD is what&amp;#39;s carrying the entire economy.  
What genius ppl we have leading our livelihood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:04:20 </td>
   <td style="text-align:left;"> $AAPL Who wants $155!? like this post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:03:35 </td>
   <td style="text-align:left;"> $AAPL This guy lost a bet and had to walk through a parking lot in his underwear.  But he ain&amp;#39;t worried about losing with AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:03:21 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-06 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=h3lm7KgwyaI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:03:08 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s pretty relevant that apples primary supplier is shut down in China isn&amp;#39;t it           fffffffgffg Being that US trade war with China is what&amp;#39;s cutting us down. been at war a long time. Theyre not going to let up when we(the governed) are about to </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 08:01:53 </td>
   <td style="text-align:left;"> $AAPL Option to look at... 👀 👀  $185.00 Call for Friday, June 17, 2022. Roughly 1 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:58:30 </td>
   <td style="text-align:left;"> $AMC swing idea 💡 
Entry: 21.93 
Stop: 19.99 
 
🎯 Target: 24.84 
 
$GME $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:58:00 </td>
   <td style="text-align:left;"> $AAPL is one of the better performing stocks in the Technology Hardware, Storage &amp;amp; Peripherals industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:54:59 </td>
   <td style="text-align:left;"> $AAPL Apple Myeongdong Opens Saturday, April 9, in South Korea https://www.otcdynamics.com/aapl-apple-myeongdong-opens-saturday-april-9-in-south-korea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:54:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  Cheescake  chart caution for the $2 Billion Darkpool selling at $176!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:54:04 </td>
   <td style="text-align:left;"> $SPY $QQQ *Updated the March 30 #Nacho #Bot #Libre  Nasdaq Chart.  
 
#Caution after retesting ichimoku resistance/ flat cloud equilibirum level (26 day average of candle prices formed 26 days ago)  
 
momenum rolled over hard..  
 
expecting fast test of white line then cloud bottom. caution under cloud! for bearish trend below cloud) 
 
$2Billion in #QQQ Darkpool selling at $365! 
$2 $Billion in $AAPL Darkpool at $176  distribution  massive selling  
(will post separate $AAPLchart) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:53:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I just wanna be the first to congratulate put holders.

🧸 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:53:22 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:48:15 </td>
   <td style="text-align:left;"> $AAPL Sell, buy Walmart and dollar store. That’s all the gp can afford </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:47:23 </td>
   <td style="text-align:left;"> $AAPL 165 inbound tomorrow and 160 Friday  
added SQQQ UVXY Walmart Philip Morris, Macdonald’s. These are recession stocks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:47:15 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Myeongdong Opens Saturday, April 9, in South Korea https://www.stck.pro/news/AAPL/25747608 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:46:04 </td>
   <td style="text-align:left;"> $CENN 

$AAPL 

Potential Partnerships  are Nice when they blossum to help the world.

#greentech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:41:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL ya&amp;#39;ll gon learn, boiiii </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:41:38 </td>
   <td style="text-align:left;"> $AAPL bears recycling old news again? Lmao. Last time that happened we hit a nice high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:40:40 </td>
   <td style="text-align:left;"> $AAPL https://www.irishtimes.com/business/manufacturing/apple-supplier-foxconn-shuts-plants-as-covid-outbreak-in-china-grows-1.4826405 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:40:11 </td>
   <td style="text-align:left;"> $AAPL “Companies in Shenzhen. . . need to stop operations, the companies cannot operate and suppliers in Dongguan cannot deliver,” he said, referring to a nearby manufacturing   phttps://www.irishtimes.com/business/manufacturing/apple-supplier-foxconn-shuts-plants-as-covid-outbreak-in-china-grows-1.4826405 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:37:30 </td>
   <td style="text-align:left;"> $SPY fed can do whatever they want. I’m still getting the new $AAPL iPhone when it comes out. I’m still ordering everything I want from $AMZN Amazon. I’m also going to continue taking my family to the $AMC movies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:30:46 </td>
   <td style="text-align:left;"> $AAPL 📰 Apple Myeongdong Opens Saturday, April 9, in South Korea

https://quantisnow.com/i/2689736?utm_source=stocktwits

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:30:35 </td>
   <td style="text-align:left;"> $AAPL Apple Myeongdong Opens Saturday, April 9, in South Korea
https://www.stocktitan.net/news/AAPL/apple-myeongdong-opens-saturday-april-9-in-south-bvytgpnm9ecd.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:30:02 </td>
   <td style="text-align:left;"> $AAPL New Press Release:  
  
Apple Myeongdong Opens Saturday, April 9, in South Korea 
  
Apple® today previewed Apple Myeongdong, a new retail store located in the center of Seoul’s vibrant and bustling shopping district. Serving as Apple’s largest store in South Korea, this new space will invite customers to discover Apple’s latest products, receive best-in-class support from highly knowledgeable Apple Specialists, and participate in educational Today at Apple® sessions. “We are thrilled to deepen our relationship with our Korean customers with the opening of this special store in Myeongdong,” said Deirdre O’Brien, Apple’s senior vice president of Retail + People. “Our incredible retail team is ready to welcome the local community, and we invite everyone to find endless inspira (...) 
  
https://webchronicletoday.com?p=235745 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:30:01 </td>
   <td style="text-align:left;"> $AAPL Apple Myeongdong Opens Saturday, April 9, in South Korea 

https://newsfilter.io/a/13ff1ab4dce2041198fb094008cf0e75 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:24:54 </td>
   <td style="text-align:left;"> $MSFT will surpass $AAPL market cap in 2 years. If you would like to make long term investment. That&amp;#39;s microsoft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:09:57 </td>
   <td style="text-align:left;"> $AAPL Apple tends to repeat its chart patterns.  I think we see a minimum low of 168 (possibly 165.50) before a bounce to test $172.  https://www.tradingview.com/x/EyTclmGk/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:03:35 </td>
   <td style="text-align:left;"> $AAPL no demand near to ATH, test 150-160 lows so it might find a demand zone there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 07:03:22 </td>
   <td style="text-align:left;"> $SPY do you know how I got into options trading? $TSLA $AAPL $AMC I was told not to trade options when I didn’t know what options were…so I looked them up
And became an addict gambler 🐷🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:56:12 </td>
   <td style="text-align:left;"> $AAPL $DWAC Anyone else rooting for the other side? 
https://www.irishtimes.com/news/world/europe/us-targets-new-sanctions-at-putin-s-two-daughters-and-two-banks-1.4846382?mode=sample&amp;amp;auth-failed=1&amp;amp;pw-origin=https%3A%2F%2Fwww.irishtimes.com%2Fnews%2Fworld%2Feurope%2Fus-targets-new-sanctions-at-putin-s-two-daughters-and-two-banks-1.4846382 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:53:10 </td>
   <td style="text-align:left;"> $AAPL 👌🏻🖖🏻👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:49:54 </td>
   <td style="text-align:left;"> $AAPL today brought neutral outlook….. everyone should just be quiet and wait 🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:39:39 </td>
   <td style="text-align:left;"> $AAPL ....My Goodness where are all the chart hating Pumpers now...🤷‍♂️ As of now we&amp;#39;ve got from a $178 to $171.... Just gonna keep screenshot within screenshot until this goes to a $150...ish....$TSLA $SPY $QQQ $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:38:51 </td>
   <td style="text-align:left;"> $AAPL we will hit $167 here and then a bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:38:02 </td>
   <td style="text-align:left;"> $AAPL Red tomorrow and Friday, then bounce next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:37:10 </td>
   <td style="text-align:left;"> $TSLA $AAPL please please bounce back. Holding strong calls for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:32:27 </td>
   <td style="text-align:left;"> $AAPL $TSLA these hand selected overvalued turds have much more room to fall still and bring down the $SPY with it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:31:26 </td>
   <td style="text-align:left;"> $AAPL open under $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:20:28 </td>
   <td style="text-align:left;"> $AAPL https://www.irishtimes.com/business/manufacturing/apple-supplier-foxconn-shuts-plants-as-covid-outbreak-in-china-grows-1.4826405 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:19:54 </td>
   <td style="text-align:left;"> $AAPL 
“Companies in Shenzhen. . . need to stop operations, the companies cannot operate and suppliers in Dongguan cannot deliver,” he said, referring to a nearby manufacturing hub 
https://www.irishtimes.com/business/manufacturing/apple-supplier-foxconn-shuts-plants-as-covid-outbreak-in-china-grows-1.4826405 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:18:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’m gonna ride this pig down like dr. burry in 08 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:18:16 </td>
   <td style="text-align:left;"> $AAPL Really liked listening to this! possible? may be, may be not.. but be careful out there! 
https://www.youtube.com/watch?v=JlEGU2ypr1Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:17:26 </td>
   <td style="text-align:left;"> $AAPL $SPY Thought this was the Nasdaq top in 2000 lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:14:24 </td>
   <td style="text-align:left;"> $AAPL held up well vs the other mega cap names which were down at least 3% or more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:13:31 </td>
   <td style="text-align:left;"> $UPST The shorts doubled down today.  All you need to know is that they haven&amp;#39;t covered a cent.  I have a friend who work for the hedge fund and he told me to buy the dip now. $AAPL $TSLA $AMD $INTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:11:18 </td>
   <td style="text-align:left;"> $AABB Bashers post together (3) in a 5 minute window. LMAO that might help work better. Lol $TSLA $AAPL $MSFT $NFLX Watch $AABB in 2022 make a nice run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:02:40 </td>
   <td style="text-align:left;"> $AAPL So now we play the Bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:01:04 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 4/4/2022 for #Stocks #Bitcoin #Gold and #Silver 
https://www.youtube.com/watch?v=ymOhlFnA_hI 
Tech is the laggard, easier to short vs materials 
 
$AAPL $AMD $TSLA $RBLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 06:00:51 </td>
   <td style="text-align:left;"> $AAPL this gonna be trading at 165 or less by monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:57:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:48:35 </td>
   <td style="text-align:left;"> $AAPL $DIS $AMD Ready for OP Miami?
Nobody does what OP does 💪😎

https://youtu.be/WHnpGcy_Gyc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:46:31 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load up what a joke!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:43:33 </td>
   <td style="text-align:left;"> latex77b1c182fa1b1c3cf887fc33d8c04692SPY 

$ERYP 

NEW OUT!!!

APRIL 14TH 10.00 CALLS 

500K WORTH

GIVING YOU A 5X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:30:30 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN $GOOG $GOOGL 

Fed officials plan to shrink the balance sheet by $95 billion a month https://www.cnbc.com/2022/04/06/fed-minutes-march-2022-meetings-.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard

As the fed shrinks its balance sheet, I’d be a seller of these stocks, they are the most prone to a massive sell off.  #recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:29:57 </td>
   <td style="text-align:left;"> $VIX  shooting star on the VIX looks nice. Yes, we’re in economic ruin but the inverted yield curve is a lagging indicator. This could be a lower high coming for the overall topping process. Unlikely but possible $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:28:27 </td>
   <td style="text-align:left;"> $AAPL 
$180 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:25:22 </td>
   <td style="text-align:left;"> $AAPL probably back to $175 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:24:33 </td>
   <td style="text-align:left;"> $AAPL This will be last to fall but it will fall. Magellan has a buy @ $117.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:24:13 </td>
   <td style="text-align:left;"> latexc704014aa7c5d52d0534a8f3072efa50ERYP 

NEWS OUT MOFOS

$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:12:46 </td>
   <td style="text-align:left;"> $AAPL earning report comes in a couple weeks, I don’t expect this to keep falling .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 05:07:34 </td>
   <td style="text-align:left;"> $AAPL latex0b856a7f3004a52cf7ae1aab589a3e1dAMD
$TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:58:27 </td>
   <td style="text-align:left;"> $AAPL 

when I pull up
On a red light
They don&amp;#39;t want it 

Lol

this is my shit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:57:22 </td>
   <td style="text-align:left;"> $AAPL $140’s you’ll drop your first small tear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:55:37 </td>
   <td style="text-align:left;"> $AAPL $SPY 😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕tooo zeee moooon!🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:50:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Short every rip from here on out bears, it’s over for the fed backed bull.😤

🧸 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:50:07 </td>
   <td style="text-align:left;"> $AAPL Just got wind of something mighty hit global news. fox caught trafficking. Not looking good bc all the nonsense is due to fact u.s. is in trade war with china. apple trade partner gets opted out at start of acknowledgement of recession. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:49:17 </td>
   <td style="text-align:left;"> latex856c5b43be1fe5d2b9f035dc7cb2efd7AAPL is down after the bell 
$TSLA is down after the bell 
*need I say more? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:48:39 </td>
   <td style="text-align:left;"> $AAPL $TSLA expect one of these companies heavily rely on China to release updated revenue forecast lower soon lol. Expect huge sales miss in China lol 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:44:51 </td>
   <td style="text-align:left;"> $AAPL Closing Chart on Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:44:33 </td>
   <td style="text-align:left;"> $AAPL Is one of the more firm technology names.  However, we favour downside to take place in technology sector, and AAPL in turn will also decline.  There is no good blue box to sell it, so we do not like to take on new short positions at this time but further downside is favored.. #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:40:59 </td>
   <td style="text-align:left;"> Top Flow for the Week 😲: $AAPL with a single CALL Trade for total premium worth $536.1K Ranking #20 the Week | This was a SWEEP trade.  | Platform I am using is SweepCast.com! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:37:20 </td>
   <td style="text-align:left;"> $AAPL bye seeya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:34:29 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-06 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=h3lm7KgwyaI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:31:49 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TWTR Fun to see our members excited about hitting their goals!
Means we are doing our job!
Are you hitting your goals? Let’s get it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:30:39 </td>
   <td style="text-align:left;"> $AAPL What happened? Did Walmart stop selling iPhones $WMT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:28:48 </td>
   <td style="text-align:left;"> $AAPL 
Apple: Dividend And Buyback Raise Coming Soon
Apr.05,2022. 
Summary
*   Fiscal Q2 report provides annual capital return update.
*   Dividend raise should be modest given share count reduction.
*   Look for the buyback to remain strong moving forward.
* 
* On Thursday, April 28th, technology giant Apple (NASDAQ:AAPL) will report its fiscal Q2 results after the bell. Everyone
* 
* Over this six-year period, the split-adjusted dividend rose from $0.13 a quarter to $0.22.
* As of Christmas 2021, Apple had $40.5 billion left on its total buyback authorization according to the 10-Q filing

Perhaps investors could get a little more if the board wants the dividend increase to be more than the current US inflation rate.

https://seekingalpha.com/article/4499856-apple-stock-dividend-buyback-raise-coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:27:01 </td>
   <td style="text-align:left;"> What You Missed On Wall Street On Wednesday - $AAPL - http://thefly.com/permalinks/entry.php/AAPLid3490119 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:26:26 </td>
   <td style="text-align:left;"> $AAPL Don’t blame me… Blame the Federal Reserve’s interests hikes my friends..Causing uncertainty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:26:23 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:24:18 </td>
   <td style="text-align:left;"> $AAPL not to worry. If Apple raised the price on every iPhone they sold last year by $10 it would add $2.5 billion in revenue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:23:09 </td>
   <td style="text-align:left;"> $TSLA China shutdown meaning Tesla suppliers also shutdown lol. Not only they lost China sales they also lost all the suppliers in China. They going to have big problem making cars in other factories because there is no car parts to make cars lol 😂 $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:22:49 </td>
   <td style="text-align:left;"> $AAPL letting know the stupid shorts in here that some people have been long since 150s.

You dumb idiots will take this to all-time highs...just wait. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:22:36 </td>
   <td style="text-align:left;"> $SOFI Replace those board members with people from $AAPL $GS and $GOOG or $MSFT 
Buying opp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:17:42 </td>
   <td style="text-align:left;"> $AAPL this isn’t holding up well so far at all ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:16:00 </td>
   <td style="text-align:left;"> $AAPL 😜 $170 SP 🎯 👀…🛑 Loss trigger On/Off 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:14:05 </td>
   <td style="text-align:left;"> $TLRY more than $TSLA $NVDA and $AAPL today.  https://stocktwits.com/rankings/watchers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:12:36 </td>
   <td style="text-align:left;"> $SPY it’s over. The fed is going to crash the stock. And China shutdown will make it worst lol 😂  $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:09:48 </td>
   <td style="text-align:left;"> $AAPL I bought that 170 dip  easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:08:36 </td>
   <td style="text-align:left;"> $AAPL sellers are NOT in control. Clowns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:08:01 </td>
   <td style="text-align:left;"> $AAPL always moves ahead of SPY, and SPY never has long lasting corrections. Buy AAPL calls when SPY is down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:07:54 </td>
   <td style="text-align:left;"> $AAPL if you learned anything from that 13 day run up, don’t fight the trend. AAPL fought like hell to close a green candle on the day but was furiously rejected (172.36).  Gap down red candle, we should see continuation over the coming days.  Sellers are in control. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:05:27 </td>
   <td style="text-align:left;"> $SPY 200 day is fine....ever so slightly below....it&amp;#39;s only an average!! 
 
The market is oversold and over shorted by the greedy MM&amp;#39;s 
$AAPL $AZN $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:05:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Can I interest anyone in a free carpet cleaning with a &amp;quot;checks notes . . .&amp;quot;  Kirby vacuum? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:05:03 </td>
   <td style="text-align:left;"> $AAPL Insiders coming thru!! 🚀 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:04:55 </td>
   <td style="text-align:left;"> $AAPL  ⚠️  $170 🎯 Wall 🍀🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:04:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:01:45 </td>
   <td style="text-align:left;"> $AAPL holding puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:01:31 </td>
   <td style="text-align:left;"> Let&amp;#39;s see $155 and bank off these puts $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:00:51 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMZN $SPY It was bad battle we&amp;#39;ve got hurt. I was moving stops all day, some re-entered . Moment of silence for decent people whos acc was wiped out. I hope those bulls will have chane to comeback. Never underestimate your enemy. We will be happy for you to join us. Cya tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:00:29 </td>
   <td style="text-align:left;"> $AAPL cpi finishing it off by morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:00:22 </td>
   <td style="text-align:left;"> $AAPL 👀 @$170 investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 04:00:16 </td>
   <td style="text-align:left;"> $SPY $AAPL disgusting close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:58:41 </td>
   <td style="text-align:left;"> $AAPL Run 🏃‍♂️ 🏃‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:57:51 </td>
   <td style="text-align:left;"> latex8b1e8a6e87bc492cb9a98887a644eac6TSLA CALLS 3.5➡️7.05+ 102% 🔥

$SPY CALLS 0.35➡️0.52 49% 🔥

OVER 554% GAINS TODAY 🤯🙌

JOIN NOW LINK IN BIO 🕺 #stockmafia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:55:37 </td>
   <td style="text-align:left;"> $AAPL time to go all in on calls and pray </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:54:39 </td>
   <td style="text-align:left;"> $AAPL kangaroo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:53:00 </td>
   <td style="text-align:left;"> The industry average ROA is 5.95%. $AAPL outperforms 96% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:52:47 </td>
   <td style="text-align:left;"> $AAPL 

Jealous or crazy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:52:23 </td>
   <td style="text-align:left;"> $SPY  $AAPL aaaand hedged. looking like it might end in a doji. gonna be sleeping like this tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:51:39 </td>
   <td style="text-align:left;"> $AAPL the theta crush on calls just now was unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:49:44 </td>
   <td style="text-align:left;"> $AAPL $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:49:19 </td>
   <td style="text-align:left;"> $AAPL omg fed , it’s not a secret or something we didn’t know was coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:48:42 </td>
   <td style="text-align:left;"> $TWST $GOOGL $AAPL $MSFT 🎬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:47:49 </td>
   <td style="text-align:left;"> $AAPL sell sell yo morons. I’m buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:47:04 </td>
   <td style="text-align:left;"> $spy $aapl $tsla $gme inflation, food shortages, lack of market growth, terrible policies, and mandated vaccinations will ruin democrats for years and years and years

Great job Joe. Stand up job here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:46:56 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOGL  
 
Tech stocks have moved broadly lower today, as investors were dreading the upcoming release of the Federal Reserve minutes following the last Federal Open Market Committee (FOMC) meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:45:18 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:43:22 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT  🚨 https://www.benzinga.com/markets/cryptocurrency/22/04/26507585/heres-why-amazon-apple-and-microsoft-shares-are-falling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:42:46 </td>
   <td style="text-align:left;"> $AAPL That chart looks like a kid with a crayon did it. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:42:27 </td>
   <td style="text-align:left;"> $AAPL failed mini rallies one after another </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:41:11 </td>
   <td style="text-align:left;"> $SPY 460 4/8 calls

$AAPL 180 4/8 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:39:37 </td>
   <td style="text-align:left;"> $SMFL $TLRY $AAPL $SWN SMFL load up while you can at these prices!!!Gains dont miss em!!anytime now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:39:11 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD  Funny how stocks aren&amp;#39;t seeing any effects of inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:38:28 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $TSLA

here comes the powel pump 🖨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:37:05 </td>
   <td style="text-align:left;"> $ADN This is like getting into $AAPL, $MSFT or $AMZN early. Game changing MEAs everyone is going to be buying or trying to replicate/compete against. Already working with tier 1 manufactures. FACT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:36:04 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN $AAPL patience pays off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:35:54 </td>
   <td style="text-align:left;"> $AAPL 

It appears sell side never give up .. we need to stomp them out!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:35:12 </td>
   <td style="text-align:left;"> $TSLA $AAPL $AMD How to discover if you are being ratioed on Stocktwits... 
 
Give this a like if you are interested in knowing.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:35:01 </td>
   <td style="text-align:left;"> $AAPL 175 tomorrow 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:34:00 </td>
   <td style="text-align:left;"> $SPY  $AAPL i&amp;#39;m back. My alert just went off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:33:05 </td>
   <td style="text-align:left;"> $AAPL $MSFT $TSLA $FB $AMZN tomorrow should be beautiful 🤩. 

Hopefully lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:32:52 </td>
   <td style="text-align:left;"> $AAPL damn it 180 calls 4/8 expiration </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:32:36 </td>
   <td style="text-align:left;"> $AAPL 180 calls 1/8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:30:25 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:30:24 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $QQQ 

Wow, talk about a bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:29:22 </td>
   <td style="text-align:left;"> $AAPL just pure downward movement. Couldn’t hold onto any gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:27:35 </td>
   <td style="text-align:left;"> $AAPL $PLTR $NVDA Enough already !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:27:32 </td>
   <td style="text-align:left;"> $AAPL y is it down so little, while $msft down almost 4% ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:26:53 </td>
   <td style="text-align:left;"> $MSFT  $AAPL  is happening today .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:26:49 </td>
   <td style="text-align:left;"> $AAPL I think price discovery will be crucial now as fed is reducing balance sheet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:26:32 </td>
   <td style="text-align:left;"> $AAPL bought a few 172.5 calls exp 4/8 at 2.11 rip should I hold it or sell it for a loss?🤦🏽‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:26:06 </td>
   <td style="text-align:left;"> $AAPL yes yes yes.dump the pig into the close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:24:14 </td>
   <td style="text-align:left;"> $AAPL watch this 172s ....

Pop, it&amp;#39;ll go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:24:03 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $AMD $BABA  just looking at today&amp;#39;s chart is giving me motion sickness. Holy crap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:19:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : AAPL, MSFT, FB, GOOGL, NVDA: Why Are Tech Stocks Down Today? https://www.stck.pro/news/AAPL/25735989 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:18:29 </td>
   <td style="text-align:left;"> $AAPL 

Apple outperforms the whole market for mega caps section.

Let’s pump up !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:17:32 </td>
   <td style="text-align:left;"> $AAPL damn wtf 🍎 go 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:15:54 </td>
   <td style="text-align:left;"> $AAPL  big pop back to its weekly range coming in ... for bulls to have full control we need to break $178.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:15:27 </td>
   <td style="text-align:left;"> $AAPL power hour sell off coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:15:07 </td>
   <td style="text-align:left;"> $AAPL I’m at a loss of words... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:14:56 </td>
   <td style="text-align:left;"> Gen Z Is Using Apple Pay to Buy Nike Shoes While They Surf TikTok

$AAPL $NKE 

https://www.thestreet.com/investing/gen-z-piper-sandler-survey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:14:03 </td>
   <td style="text-align:left;"> $AAPL 

Kept my promise to the Brotherhood of Bulls.

Shall we?....again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:13:46 </td>
   <td style="text-align:left;"> $AMD $NVDA $TSLA $AAPL How to discover if you are being ratioed on Stocktwits... 
 
Give this a like if you are interested in knowing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:13:12 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $AMD $FB These 5 companies should thrive in any market environment.  It generates revenue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:12:24 </td>
   <td style="text-align:left;"> $AAPL, $MSFT, $FB, $GOOGL, $NVDA: Why Are Tech Stocks Down Today? https://investorplace.com/2022/04/aapl-msft-fb-googl-nvda-why-are-tech-stocks-down-today/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:12:03 </td>
   <td style="text-align:left;"> $SPY Hedge fund boss just told me to pump it in power hour. Good luck bears, you will need it. 🥱🥱🥱🥱 $TSLA $AAPL $AMD $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:11:00 </td>
   <td style="text-align:left;"> $AAPL dump this over valued hog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:09:20 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY $QQQ $MSFT  
These &amp;quot;analysts&amp;quot;, fund managers and banks should not be allowed to short the markets. 
What the Fed are doing is all within reasonable measures, everyone is expecting it and want it to happen sooner, rather than later. 
But a few comments are deemed to be hawkish and sensationalised in the media... and down go the major indices. 
 
Today the Fed minutes (when did that become a thing?!) were reasonable and in fact quite doveish. Yet...oh no...WE are short so we can&amp;#39;t have good news. 
 
The talking heads on CNBC (do NOT trust them) jumped on it again and spun it all as terrible news. 
 
What nonsense. Stay calm, let the Fed do their job and don&amp;#39;t be shaken from your long term plans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:09:04 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:08:17 </td>
   <td style="text-align:left;"> $AAPL waiting for 170 again. Still many ask at 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:06:40 </td>
   <td style="text-align:left;"> $AAPL struggling for 173… wayyyyy down we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:06:17 </td>
   <td style="text-align:left;"> $AMZN  $AMC $GME $AAPL $MSFT 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:05:34 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPY $QQQ market uncertainty is over... now market will do what it does best, going up :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:04:53 </td>
   <td style="text-align:left;"> $AAPL 85 puts for $6k and then 80 calls in the green for $8k. It’s going to be a good summer! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:04:49 </td>
   <td style="text-align:left;"> $AAPL Sleepy Joe 
BLAH BLAH BLAH 😑 no better than Kackling Kamala 
Word salad kings !!
$TSLA $FB $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:04:21 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:04:03 </td>
   <td style="text-align:left;"> $AAPL hope you all bought the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:03:48 </td>
   <td style="text-align:left;"> $AAPL whats up shorts??

Wait for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:03:48 </td>
   <td style="text-align:left;"> $AAPL watching these charts is nuts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:02:30 </td>
   <td style="text-align:left;"> $AAPL 180 is possible? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:01:50 </td>
   <td style="text-align:left;"> $AAPL The fed is selling and so are executives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:01:38 </td>
   <td style="text-align:left;"> $SPY let those puts options gambler cry

I don&amp;#39;t even know what is options

I only buy boomer stock like $WMT $COST $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:01:38 </td>
   <td style="text-align:left;"> $AAPL new HOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:01:28 </td>
   <td style="text-align:left;"> $AAPL Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:00:44 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 03:00:34 </td>
   <td style="text-align:left;"> $AABB $AAPL $GOOG $MSFT $TSLA https://aabbgoldtoken.com/aabb-wallet-merchant-api/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:59:46 </td>
   <td style="text-align:left;"> $AAPL wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:59:17 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask 
 
$AAPL - $747K put sweep 
$NVDA - $550K put sweep 
$ON - $375K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:58:47 </td>
   <td style="text-align:left;"> $AAPL 3 trillion MC? gtfo of here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:58:33 </td>
   <td style="text-align:left;"> $AAPL patience… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:58:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $BAC $AAPL $TSLA  
Most Anticipated Economic Events this Week   
 
https://www.financegreater.com/economiccalendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:57:48 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SPY $AAPL Damn Bears,  thos puts that bouhgt on 443.48 must be hurt! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:57:44 </td>
   <td style="text-align:left;"> $AAPL 

It’s clear that the war between buy side and sell side has begun.

They are pushing the sell side out with attack on short by squeezing them out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:57:10 </td>
   <td style="text-align:left;"> $AAPL She’s crawlin……Timmy C’s buyin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:56:35 </td>
   <td style="text-align:left;"> $SPY what make you think mm want pay puts? You&amp;#39;re poor, mm is rich, they can literally buy 2 billion of apple now and send spy green $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:56:06 </td>
   <td style="text-align:left;"> Is this good for your portfolio? $AAPL&amp;#39;s price moved above its 50-day Moving Average on March 22, 2022. View odds for this and other indicators: https://srnk.us/go/3557741 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:55:28 </td>
   <td style="text-align:left;"> $AAPL Everything is hunky dory mission accomplished </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:54:24 </td>
   <td style="text-align:left;"> $AAPL strongest performing mega cap tech today. MSFT AMZN fb Goog down much more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:53:43 </td>
   <td style="text-align:left;"> $AAPL 18k worth of 172.5 4/14 exp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:53:00 </td>
   <td style="text-align:left;"> $AAPL As long as it remains above 170 there’s no need to worry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:52:43 </td>
   <td style="text-align:left;"> $AAPL why would anyone short apple lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:52:04 </td>
   <td style="text-align:left;"> $AAPL yeah definitely going below 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:50:23 </td>
   <td style="text-align:left;"> Here’s Why Amazon $AMZN , Apple $AAPL And Microsoft  $MSFT Shares Are Falling https://www.billionaireclubcollc.com/heres-why-amazon-apple-and-microsoft-shares-are-falling/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:49:03 </td>
   <td style="text-align:left;"> $TSLA $AMZN $AAPL $SPY Cmon Bulls push lets slain the pigs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:48:17 </td>
   <td style="text-align:left;"> $AAPL why would anyone buy $AAPL near ATH and we ahead of a recession ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:46:34 </td>
   <td style="text-align:left;"> $AAPL yawn just a lil volatility 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:46:09 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $AAPL $NVDA let the recovery begin 😉 cuz less than 200 basis points this year plus inflation and war still here… stock market is the only game in town!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:44:06 </td>
   <td style="text-align:left;"> Bullish investment portfolio: Apple( $AAPL ), Piedmont… https://www.macroaxis.com/invest/stock-correlation?s=AAPL,PLL,PLUG,EIX,ICE,KSS,FTI #insidertrading #stocks #fintechnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:42:43 </td>
   <td style="text-align:left;"> $AAPL too many shorts and lmao when they close their position this thing will bust open like a pinyata </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:41:51 </td>
   <td style="text-align:left;"> $AAPL $TSLA  Both plays paid. We just keep stacking gains 🤷🏼‍♂️
Y’all ready for What’s Next Wallstreet show tonight ? 📺🚀🥇💰
$SPY 

https://m.youtube.com/c/OptionsPlayerscom/videos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:40:34 </td>
   <td style="text-align:left;"> $AAPL when volatility is bizarre like this apple is a safe heaven. I just added. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:40:16 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPX  - gosh oil spiked and then went down 5 percent - big indication of whats coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:39:13 </td>
   <td style="text-align:left;"> $AAPL Puts banked 50% gain in 15 mins, if u bought 0dte SPY puts they went up 1000% in 15 mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:38:58 </td>
   <td style="text-align:left;"> $SPY someone needs to take the fkn control off that mfkr turning the algos and and off! TF!
$AAPL $AMZN $TSLA $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:38:55 </td>
   <td style="text-align:left;"> $AAPL America has found a way to pump the market. Jack this and everything else bankrupt follows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:38:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Here&amp;#39;s Why Amazon, Apple And Microsoft Shares Are Falling https://www.stck.pro/news/AAPL/25734079 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:38:01 </td>
   <td style="text-align:left;"> $AAPL looks like a failed follow up pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:37:41 </td>
   <td style="text-align:left;"> $AAPL Alert play paid… per usual
😝🤷🏼‍♂️🙌🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:36:23 </td>
   <td style="text-align:left;"> $AAPL all legit btw lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:36:21 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-04-06 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=h3lm7KgwyaI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:36:20 </td>
   <td style="text-align:left;"> $SPY watch $AAPL $NVDA fed mins equal tech money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:36:09 </td>
   <td style="text-align:left;"> $AAPL near ATH &amp;amp; recession around the corner and $aapl up hmm I see this short term covering and will reverse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:35:58 </td>
   <td style="text-align:left;"> $AAPL this thing trades like a freaking penny stock hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:34:40 </td>
   <td style="text-align:left;"> $AAPL how ya like me now bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:34:28 </td>
   <td style="text-align:left;"> $AAPL what in the manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:34:14 </td>
   <td style="text-align:left;"> $AAPL don’t sell homies don’t fucking sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:33:41 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPX what do you think inflation control checks with fed do… markets go up after digesting it. Go long! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:33:36 </td>
   <td style="text-align:left;"> I think my panties just got a little wet, trading $SPY futures and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:33:36 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:33:00 </td>
   <td style="text-align:left;"> latexa43a226a78825da7d5585ccbaa918bc0GGPI 🚘

$PLUG ⚡️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:30:11 </td>
   <td style="text-align:left;"> $AAPL ain’t no way lol 📈📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:29:30 </td>
   <td style="text-align:left;"> $BAC $WFC i knew this would happen. They are going to fill the 38:80 before this goes up. So buy puts.  $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:29:18 </td>
   <td style="text-align:left;"> $ABBV .... Been looking like this all day on this pump.... At resistance with divergence and mass Exodus while they hold it up.... This is exactly what Apple looked like Before it gapped down $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:27:39 </td>
   <td style="text-align:left;"> $AAPL 168 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:27:18 </td>
   <td style="text-align:left;"> $AABB $AABB is the talk of the &amp;#39;&amp;#39;chat&amp;#39;&amp;#39; at the bitcoin conference. Here&amp;#39;s why and the estimation is 3-4 billion UNCOVERED &amp;#39;&amp;#39;naked short&amp;#39;&amp;#39; shares. .11 cents to $11 the VYGVF MARA RIOT MVIS runs coming,MOASS. $AAPL $TSLA $ETH.X $DOGE.X https://finance.yahoo.com/quote/AABB?p=AABB&amp;amp;.tsrc=fin-srch BOOM! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:27:14 </td>
   <td style="text-align:left;"> $TSLA $SHOP $AMZN $AAPL $GMBL Invest in what you consume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:26:32 </td>
   <td style="text-align:left;"> $SPY so what 95 bil  outflow by fed

You guys dumb? Pension fund 401k and retirement net inflow is 500b per month

And this sum is going increase, cough inflation

$AAPL TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:26:14 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:24:59 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Damn, markets are fooked looks like jpow’s turning off the 🖨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:24:42 </td>
   <td style="text-align:left;"> $UVXY $TQQQ $SPY $AAPL $TSLA shorting borrow rates just went insane. Yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:24:15 </td>
   <td style="text-align:left;"> $AAPL you can’t time this more perfectly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:23:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA I love stockwitts when im making money! Its so funy being a negative bear!! poor bulls we know the feeling of heartache.. pst you had 3 weeks of mindless pumps, hope you sold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:23:31 </td>
   <td style="text-align:left;"> $AAPL options 🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:23:16 </td>
   <td style="text-align:left;"> $AAPL double bottom on the 77 minute </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:22:41 </td>
   <td style="text-align:left;"> $AAPL Muddle dopp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:21:27 </td>
   <td style="text-align:left;"> $AAPL whiplash action, crushing options, seems likely it’s going to go further down but waiting for the magical last hour to do so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:20:50 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ Everyone who works at CNBC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:20:44 </td>
   <td style="text-align:left;"> $AAPL 

headed to $120 and that’s being generous, lock in profits or get smoked in a few days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:20:36 </td>
   <td style="text-align:left;"> $AAPL 

It’s just algo is taking whole market down on the news of balance sheet reduction for which it’s overreaction.

They are trying to attack again on feds expected decision to 50 basis point increase.

Actually .. it’s not happening until next month.

They are changing the game how to be bullish when Fed raised 50 basis points in next meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:19:47 </td>
   <td style="text-align:left;"> $AAPL  $AMD 

These two stickers will rip so hard and so fast 💨 you don’t know what has hit you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:19:30 </td>
   <td style="text-align:left;"> $AAPL good luck pinning this…heading much lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:19:05 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NVDA $AMD  
Ladies and gentleman, virus news are back. FED, Ukraine,inflation and again Covid ! 
 
https://www.cnbc.com/2022/04/06/uk-has-detected-a-new-covid-variant-heres-what-we-know-so-far-about-omicron-xe.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:18:45 </td>
   <td style="text-align:left;"> $SPY $AAPL minutes very hawkish. They are gonna push us into recession along with inflation that cannot be corrected with rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:18:07 </td>
   <td style="text-align:left;"> $AMZN $GOOG $AAPL $MSFT $NVDA  
$2.7 Trillion in MBS (housing bubble pop, nothing was organic about the rise in home prices)  
 
Real estate represents &amp;gt;50% of global “wealth”, and it is therefore such an important driver for the business cycle 
 
Likely markets going much lower along with almost everything else, including commodities.  
 
Fed is telling you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:17:15 </td>
   <td style="text-align:left;"> $AAPL lol this old fart holding up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:17:11 </td>
   <td style="text-align:left;"> $AAPL literally dropped $3 in 1 minute and I killed it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:16:25 </td>
   <td style="text-align:left;"> $AAPL Crooked action by algos! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:16:03 </td>
   <td style="text-align:left;"> $AAPL please just break 171 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:59 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Bulls are finished 🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:53 </td>
   <td style="text-align:left;"> $AAPL if you didn’t sell those calls on that pop then oh well. That’s why you should always watch market if you’re in a play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:25 </td>
   <td style="text-align:left;"> $SPY what was that pump $TSLA $AAPL what the fuck is happening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:20 </td>
   <td style="text-align:left;"> $AAPL Jan ‘23 $60 calls only $112….sweet acquisition </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:20 </td>
   <td style="text-align:left;"> $AAPL rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:13 </td>
   <td style="text-align:left;"> $AAPL Fraphl GoneA thrash dumorra </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-07 02:15:02 </td>
   <td style="text-align:left;"> $AAPL that pump and dump was great. Once again stops are amazing to lock profits. Now looking to rebuy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:23:13 </td>
   <td style="text-align:left;"> $PLTR $CRWD $TSLA $AMD 

Palantir is the next $500.00 stock. In 5 years you will look back and be glad you held. 

https://blog.palantir.com/palantir-foundry-and-accenture-expertise-powerful-results-fa886aae9210 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:22:34 </td>
   <td style="text-align:left;"> $TSLA should see a fake pump tomorrow followed by a drop to $950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:22:03 </td>
   <td style="text-align:left;"> $TSLA any good news 📰 coming out tomorrow for a run up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:21:59 </td>
   <td style="text-align:left;"> $TSLA Face it. It’s a constant pump and dump and ifs and buts and candy and nuts and we are all going to have a wonderful Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:21:45 </td>
   <td style="text-align:left;"> $SPY  $AAPL $TSLA 
Tomorrow QE pump for “Soft landing”  👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:19:58 </td>
   <td style="text-align:left;"> $tsla $arkk https://www.youtube.com/watch?v=HPxQ3zCq6KE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:14:28 </td>
   <td style="text-align:left;"> $SPY  $AAPL $TSLA $SNOW $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:13:40 </td>
   <td style="text-align:left;"> $TSLA Surprises for the Rodeo tomorrow.   Place your wager.   https://electrek.co/2022/04/06/tesla-surprises-cyber-rodeo-2-cybertrucks-spotted-unidentified-vehicles/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:13:29 </td>
   <td style="text-align:left;"> $TSLA $SPY All that you need to know... Shorts haven&amp;#39;t covered a single share.. Check it out below.  
 
Highly recommend everyone to follow them.   
http://live-stock-alerts.coordinatetrading.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:13:09 </td>
   <td style="text-align:left;"> $TSLA $SPY All that you need to know... Shorts haven&amp;#39;t covered a single share. Check it out below  
 
Highly recommend everyone to follow them   
http://live-stock-alerts.coordinatetrading.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:11:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $NVDA $SPY 
Bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:11:27 </td>
   <td style="text-align:left;"> $TSLA how do I put this nicely… this stock is well.. fcked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:11:20 </td>
   <td style="text-align:left;"> $TSLA Could we get Tony Stark to attend the giga opening tomorrow? Kappa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:10:09 </td>
   <td style="text-align:left;"> $TSLA Any full time traders in the house? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:09:34 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $JPM 
🥶 $95B cut per month &amp;amp; 0.5% hike
https://www.cnbc.com/2022/04/06/fed-minutes-march-2022-meetings-.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:08:54 </td>
   <td style="text-align:left;"> $TSLA 95% sure we get a cybertruck update tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:08:32 </td>
   <td style="text-align:left;"> LIVE DAY TRADING 4.6.22 $amzn $tsla $cost 
https://youtu.be/WTyi0zj14vc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:03:01 </td>
   <td style="text-align:left;"> $TSLA there was some rodeo in the AH price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 09:01:46 </td>
   <td style="text-align:left;"> $TSLA ✋https://youtu.be/xlBQXdCCvQI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:59:12 </td>
   <td style="text-align:left;"> $TSLA drop them zeros and get with the hero. 

And yes, I made that shit up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:58:10 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 2: $UNH $ABBV $COST $TWTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:57:31 </td>
   <td style="text-align:left;"> $GGR - with only 4-5m shares  to trade if the $Amc $GME $tsla crowd get wind of this it will rocket!!

It is the Tesla of 2 wheelers - with more customers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:57:18 </td>
   <td style="text-align:left;"> $TSLA 
Futes green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:55:49 </td>
   <td style="text-align:left;"> $TSLA 

Inflation ———— ——PUTIN
Recession ——— —-   PUTIN
Leaky Border—— ——PUTIN
Stock Market mani — PUTIN
$9 ⛽️ at pump —-——PUTIN 
Cognitive Decline ——PUTIN
C19 &amp;amp; Variants INC — PUTIN
My fkn back pain——PUTIN

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:54:10 </td>
   <td style="text-align:left;"> $TSLA folks get real serious on an opportunistic social media platforn built around subjective markets using objective rules lol, but hey lets human shall we? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:54:10 </td>
   <td style="text-align:left;"> $SPY $IWM $AMZN $TSLA BUY All Dips tomorrow and Friday! We are going to bounce... News is behind us now!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:52:42 </td>
   <td style="text-align:left;"> $TSLA do we get a gap up tomorrow🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:52:19 </td>
   <td style="text-align:left;"> $TSLA 5000 more Starlink terminals going to Ukraine https://www.bloomberg.com/news/articles/2022-04-06/u-s-sends-5-000-spacex-starlink-internet-terminals-to-ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:52:18 </td>
   <td style="text-align:left;"> $TSLA source Twitter #gigatexas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:50:59 </td>
   <td style="text-align:left;"> $TSLA  cyber-“truck’’ design was drawn up by a 6 yo with a crayon in the wrong hand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:50:31 </td>
   <td style="text-align:left;"> $TSLA 
😎💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:48:47 </td>
   <td style="text-align:left;"> $TSLA I’M FREAKIN OUT WITH MY 4/8 PUTS!!!  GIGA TEXAS MIGHT COME WITH SURPRISES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:48:31 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/3_d_E7-iQ8o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:46:54 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/bank-of-america-has-raised-pt-on-tesla-to-1-300-per-share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:46:48 </td>
   <td style="text-align:left;"> $TSLA 

Everyone knows Megatron that is stronger than Optimus... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:45:01 </td>
   <td style="text-align:left;"> $SPY  $QQQ $TSLA $TWTR 

 MM Wanna play dirty huh ?? We can do it . ✅ chats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:44:55 </td>
   <td style="text-align:left;"> $TSLA it’s sad to see people here happy for bad economy (recession ) to make couple of thousands of dollars without giving a fuckkk about consequences of recession that will have on millions of families. You’re worst than covid really and there is nothing to cure you!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:44:22 </td>
   <td style="text-align:left;"> $TMC 🚀🚀🚀🚀
-Insiders have loaded 6.2 Million shares with an average price of $3.05
-TMC to announce a nickel offtake agreement with a customer facing brand this year.
-US big oil and gas players TransOcean and Oil States are transitioning their businesses into the collection of polymetallic nodules
$LCID $TSLA $NIO $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:44:13 </td>
   <td style="text-align:left;"> $TSLA let’s close that gap and bounce off the 50 , shall we? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:42:12 </td>
   <td style="text-align:left;"> $SPY  $TSLA $PLTR up 5 down 3 baby! Life is this equation, bulls love the 5 and 2, while bears love the 3. Rinse repeat, we all win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:41:57 </td>
   <td style="text-align:left;"> $AAPL $TWTR $TSLA What does the most powerful trading platform do for its members? Let’s take a look shall we?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:39:43 </td>
   <td style="text-align:left;"> $TSLA 

The bears 🐻 on this feed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:38:13 </td>
   <td style="text-align:left;"> $TSLA 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:38:10 </td>
   <td style="text-align:left;"> $TSLA 1500$ by end of month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:37:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK 

Wen Optimus?...🤖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:36:35 </td>
   <td style="text-align:left;"> $TSLA what price can we see tomorrow??👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:36:06 </td>
   <td style="text-align:left;"> $TWTR $TSLA $ARKK

scam just like elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:34:58 </td>
   <td style="text-align:left;"> $TSLA can we see $1,046 at pre-market??👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:57 </td>
   <td style="text-align:left;"> $TSLA China could keep factory closed for a long time. they are so stupid about this damn virus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:52 </td>
   <td style="text-align:left;"> $TSLA was trading in channel for a while, reached a low of ~700 before breaking out to a high ~1150. I wonder what’s next for this 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:41 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $2475.00 Call for Friday, May 20, 2022. Roughly 44 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:38 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $1550.00 Call for Friday, April 8, 2022. Roughly 825 Thousand dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:34 </td>
   <td style="text-align:left;"> $TSLA ridiculous.   So much for saving money on gas with a Tesla.  He’s increased the price of his cars by like 30% over the past year.  And we worried about gas that’s up a $1-1.50 a gallon.  😂

https://twitter.com/livesquawk/status/1511859477393334277?s=21&amp;amp;t=cPl5eIGZV5bpTUnVacLCRw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:17 </td>
   <td style="text-align:left;"> $TSLA can we see $1,046 tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:06 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-06 Chart Analysis Video: 
https://www.youtube.com/watch?v=rj2merOiZ-E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:32:05 </td>
   <td style="text-align:left;"> $SPY $QQQ

Judging off the past few trading sessions of $TWTR pumping and $TSLA  dumping it’s starting to look like twitter has musk’s heart. I would even argue that Twitter is starting to look like the more dominant tech company than tesla... would you agree bulls?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:31:52 </td>
   <td style="text-align:left;"> $TSLA 600 by end of month. Overinflated tech stock won’t weather all these upcoming interest rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:31:24 </td>
   <td style="text-align:left;"> $TSLA 

🙏🏻🐉🦅⚡️⚡️⚡️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:30:21 </td>
   <td style="text-align:left;"> $TSLA Declines -4.2%. The 08-Apr-22 Option Straddle is Implying a ±2.8% Move in the Next 2 days https://tinyurl.com/yybt77jv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:28:20 </td>
   <td style="text-align:left;"> $SPY I have seen enough of back to back red days!  I need Elon musk to tweet that he bought 9-10% shares in a random stock again so we can have a green day tomorrow!  This is getting ridiculous when it is April (the greenest month of the year) and right before earnings.  Unless WW3 is going to happen soon, I don&amp;#39;t see a reason for this ridiculous selling the past 2 days! $AMD $UPST $INTC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:26:39 </td>
   <td style="text-align:left;"> $TSLA 100% invested in Tsla with max margin, I&amp;#39;m super, mega, ultra, super 🐂🐂🐂🐂🐂🐂, LFG...🚀🤑🚀🤑🚀🤑🐂💰🐂🤑🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:26:11 </td>
   <td style="text-align:left;"> $FSR  $AAPL  $TSLA 
What&amp;#39;s a Fisker? Still early.

FISKER 2022 - it&amp;#39;s a start up
https://youtu.be/ezn6iY6LzIU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:26:06 </td>
   <td style="text-align:left;"> $TSLA 😕https://youtu.be/VxgFX-J0ZQ4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:25:22 </td>
   <td style="text-align:left;"> $TSLA is Shanghai closed all month 50,000 production lost? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:23:14 </td>
   <td style="text-align:left;"> $TSLA let’s give these tesla fanboys another leg down 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:22:57 </td>
   <td style="text-align:left;"> $TSLA GIGA AUSTIN 💎🚀🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:22:11 </td>
   <td style="text-align:left;"> $SPY $TSLA Earnings reports today before the markets open&amp;quot; amazing-stocks-room.stockmarketus.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:21:19 </td>
   <td style="text-align:left;"> $TSLA i love that zero COVID policy from China.   Will send the world into recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:19:19 </td>
   <td style="text-align:left;"> $SPY BULL RATS - ALMOST! 😆😂📈🐀💨   
 
MAN I made a nice HAUL TODAY!!! (same time , same place tomorrow💡💰😁)   
 
$tsla $rivn $rh $qqq - just getting comfortable to drop some evening  WEAR 👙🩱👀💦😁for twits tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:19:17 </td>
   <td style="text-align:left;"> $TSLA load up….Cyber Rodeo is gonna pop ! #texas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:19:15 </td>
   <td style="text-align:left;"> $TSLA $twtr  maybe Elon likes the letter T for Toker, smoker, midnight joker.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:18:19 </td>
   <td style="text-align:left;"> Whats your prediction for tomorrow?

$PLUG $IDEX $TSLA $OPTT $WWR $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:18:04 </td>
   <td style="text-align:left;"> $TSLA woah, COVID-19 is spreading like wild fire in China. The Tesla factory there and parts manufacturers may jave to remain locked down until June 2022 to flatten the curve. Why isn&amp;#39;t Elon criticizing Premiere Xi on Twitter?

https://www.reuters.com/world/china/shanghai-reports-19660-new-asymptomatic-covid-cases-322-symptomatic-cases-april-2022-04-07/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:18:03 </td>
   <td style="text-align:left;"> $TSLA If it drops at the open you better BTFD tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:16:38 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $900.00 Call for Thursday, April 14, 2022. Roughly 2 Million dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:16:28 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m Bullish - But I wouldn&amp;#39;t rule out us retesting the low end of this range before we breakout again 🔎  
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:16:14 </td>
   <td style="text-align:left;"> $JASMY.X who’s going to win the $TSLA 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:16:10 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price Prediction and Analysis for Tomorrow Thursday  April 7
https://youtu.be/xeSOmQRl0uA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:15:38 </td>
   <td style="text-align:left;"> $TWTR  tomorrow Texas Giga $TSLA festival.. wondering why Elon’s Twiter investment news was right  before this festival.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:14:08 </td>
   <td style="text-align:left;"> $TSLA we’ll prolly see a  simpthy run up to 1070-1100 max then another leg dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:14:01 </td>
   <td style="text-align:left;"> $TSLA ✋https://youtu.be/1yoYGmJ1bP0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:13:13 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:13:06 </td>
   <td style="text-align:left;"> $TSLA $SPY Why Tesla just dropped in after hours.  
 
https://www.reuters.com/world/china/shanghai-reports-19660-new-asymptomatic-covid-cases-322-symptomatic-cases-april-2022-04-07/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:12:45 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Futures crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:12:42 </td>
   <td style="text-align:left;"> $TSLA | Tesla Raises US Prices Of Some Model 3 Vehicles By At Least $1,000 - RTRS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:12:19 </td>
   <td style="text-align:left;"> $TWTR Elon will learn he can Not control the stock like he does with $TSLA. He has 9 percent not 90 percent lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:11:44 </td>
   <td style="text-align:left;"> $TSLA I MAXXED OUT ON LOTTO PUTS FOR THIS FRIDAY.  DAMN YOU GIGA TEXAS!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:10:50 </td>
   <td style="text-align:left;"> $TSLA 1090 with the texas hype tomorrow! yay or nay? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:10:21 </td>
   <td style="text-align:left;"> $TSLA wow im only up 70k on the year now in tesla smh.. PARTY OF THE CENTURY TOMORROW IN TEXAS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:09:37 </td>
   <td style="text-align:left;"> $QQQ $TSLA Remember folks. Cramer said we were out of the bear market and called the &amp;quot;bottom&amp;quot;. Do the opposite of whatever he says. 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:09:23 </td>
   <td style="text-align:left;"> $TSLA great day to buy the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:08:19 </td>
   <td style="text-align:left;"> $TSLA everyone being so irrational and stupid. 
 It was a crappy day overall and tesla had a gap to fill from the split announcement and they used this crappy day to their advantage.
 IT GOT FILLED!
It really is that simple. If your a long term bull, chill out. In 6 months today won&amp;#39;t matter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:07:53 </td>
   <td style="text-align:left;"> $TSLA regardless if you’re a bear or bull, money is always to made on both sides. But please, learn from your mistakes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:06:37 </td>
   <td style="text-align:left;"> $SPY 2022 is gonna be a wake up call for a lot of you... 

I&amp;#39;ve warned you multiple times.  

I told you 460 was &amp;quot;resistance,&amp;quot; and because we got a false break (above) - you laughed at me (while I&amp;#39;m still making 10k/day; BOTH ways).  

You&amp;#39;re experiencing the &amp;quot;calm&amp;quot; before the &amp;quot;storm.&amp;quot; 

And for the record...NOTHING has changed &amp;quot;fundamentally&amp;quot; since the most recent highs...  Nothing... 

Markets move news...news RARELY moves Markets.  

Need a headline to justify a move down?  Already in queue.  And the same applies in the opposite direction.  

Stop believing the hype.  Stop listening to these &amp;quot;experts&amp;quot; who get paid to leave YOU holding bags.  

Everything you need to see -- EVERYTHING -- can be analyzed with basic math &amp;amp; statistics.  And yes-- TA is a visual representation of that math/statistics.  

$SOFI  $TSLA $TLRY $SBFM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:05:24 </td>
   <td style="text-align:left;"> $TSLA bears and bulls here just borrowing money back n forth :) Glta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:04:53 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $150.00 Put for Friday, December 16, 2022. Roughly 171 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:04:12 </td>
   <td style="text-align:left;"> $TSLA ‘like’ if u loaded shares Tuesday and calls today! 💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:03:44 </td>
   <td style="text-align:left;"> $TSLA who is right? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:02:42 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-06 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=PlwJcZdLBpM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:01:44 </td>
   <td style="text-align:left;"> $TSLA let’s see how tomorrow goes, made $10k on a swing trade today from $1,030 up to $1,060 (got lucky) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:01:32 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Order Flow Sentiment is 51.4% Bearish. https://tinyurl.com/y4jo7k7o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:01:27 </td>
   <td style="text-align:left;"> $TSLA Oh Gosh!  Why did I buy in yesterday when I have to sell out today!   
 
phawwwwwkkkkk me!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:00:31 </td>
   <td style="text-align:left;"> $MF good and high demand, strong hold!!!!!!!!  $TSLA $AMC  buy it!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:00:25 </td>
   <td style="text-align:left;"> $TSLA wearing full control diapers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:00:18 </td>
   <td style="text-align:left;"> $TSLA sooo fucking boolish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 08:00:15 </td>
   <td style="text-align:left;"> $TSLA Let&amp;#39;s go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:58:40 </td>
   <td style="text-align:left;"> $TSLA I’m losing control. Haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:58:30 </td>
   <td style="text-align:left;"> $AMC swing idea 💡 
Entry: 21.93 
Stop: 19.99 
 
🎯 Target: 24.84 
 
$GME $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:58:22 </td>
   <td style="text-align:left;"> $TSLA MMs in full control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:58:15 </td>
   <td style="text-align:left;"> $TSLA I’m in full control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:57:51 </td>
   <td style="text-align:left;"> $TSLA Bull in full control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:57:03 </td>
   <td style="text-align:left;"> $TSLA Bear in Full Control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:56:36 </td>
   <td style="text-align:left;"> $TSLA hopefully 700 by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:56:20 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s make Elon a millionaire! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:55:47 </td>
   <td style="text-align:left;"> $TSLA Elon hates us… and that’s okay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:54:05 </td>
   <td style="text-align:left;"> latex6c2cf3406610dff35da36f376ab9ed8c , because we tested 1025$, because China lock downs, Bc fed meeting , Bc economic recession , I am short term bearish … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:53:45 </td>
   <td style="text-align:left;"> $TSLA if this closes red tomorrow I’ll buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:53:31 </td>
   <td style="text-align:left;"> $TSLA tweet something Elon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:53:22 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I just wanna be the first to congratulate put holders.

🧸 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:51:48 </td>
   <td style="text-align:left;"> $TSLA it’s crazy to see here day in day out:

“It will do this then that” 
“What will it do?”

Crazy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:51:44 </td>
   <td style="text-align:left;"> $TSLA fair Tesla valuation

Now 200 pe
5 years car production triple
66 pe
Tesla insurance
33 pe

Self driving, tesla battery, Tesla charging
20 pe

$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:51:18 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s closing price 

https://youtu.be/DPXtWyVcJBk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:50:22 </td>
   <td style="text-align:left;"> $TMC can single-handedly help US attain energy independence for its national security. TMC has enough nickel, cobalt, manganese and copper reserves to energize 280M EVs. EV battery metals will be the new oil. $TSLA $NIO $LCID $WKHS 

https://vimeo.com/693667097 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:50:12 </td>
   <td style="text-align:left;"> $BTC $MULN $TSLA $HUSA —-&amp;gt;&amp;gt;  $NILE 💸💸💸💭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:50:00 </td>
   <td style="text-align:left;"> $TSLA: The EPS is expected to grow by 26.94% on average over the next 5 years. This is a very strong growth. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:47:53 </td>
   <td style="text-align:left;"> $TSLA bears get your lube ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:47:35 </td>
   <td style="text-align:left;"> $TSLA musk has to break the rules to manipulate tesla, twitter and doge. Screw the little guy, he needs more gigafactoies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:44:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ markets still bullish, block the noise and follow the price action 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:43:51 </td>
   <td style="text-align:left;"> $TSLA Would love to meet a ST Tesla bear in public, but seldom do I walk under the overpass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:43:32 </td>
   <td style="text-align:left;"> $IPOF LOL merger coming soon 🔥🚀😂 bears and shorts puts will be worth $0 $TSLA God is going to give us a gift SpaceX / STARLINK

If you didn’t know ELON MUSK AND CHAMATH ARE FRIENDS! 🤣🔥

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:42:55 </td>
   <td style="text-align:left;"> $TSLA ⚓️⚡️ 
 
Resources being scarce as they are, would it or would it not make sense for TESLA to acquire another company that already had &amp;quot;items” and “lines of materials in great need” and add it under the TSLA umbrella? 
 
This might be a faster way to obtain resources that are becoming harder and more expensive to acquire. 
 
No moronic replies please. 
_ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:41:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL ya&amp;#39;ll gon learn, boiiii </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:41:15 </td>
   <td style="text-align:left;"> $TSLA I’d hate to be holding puts on cyber rodeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:41:04 </td>
   <td style="text-align:left;"> $TSLA Back to red by AH close, let&amp;#39;s get it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:40:16 </td>
   <td style="text-align:left;"> $TSLA I’d hate to be a call holder here 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:39:40 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s get a $75 haircut tomorrow on this stock in celebration of Giga Austin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:38:35 </td>
   <td style="text-align:left;"> $TSLA killing myself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:38:03 </td>
   <td style="text-align:left;"> $JASMY.X ♥️ $TSLA 
I want this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:37:23 </td>
   <td style="text-align:left;"> $TSLA futes gapping down!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:34:18 </td>
   <td style="text-align:left;"> $TSLA give me 1200 tomorrow I’ll be done trading Tsla this week, maybe😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:33:48 </td>
   <td style="text-align:left;"> $TSLA futes are on fuego!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:30:44 </td>
   <td style="text-align:left;"> $IPOF $20 tomorrow look at OI $20 calls for next week 🚀🔥 $TSLA $IPOD SOMONE KNOWS SOMETHING SPACEX STARLINK MERGER? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:30:17 </td>
   <td style="text-align:left;"> $TSLA Muln jk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:29:47 </td>
   <td style="text-align:left;"> $TSLA It might go up… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:28:34 </td>
   <td style="text-align:left;"> $TSLA this is  closing week at 1200  period </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:26:26 </td>
   <td style="text-align:left;"> $TSLA  went up +50% without significant pullback.   gotta play with bearish bias, tho I play both ways. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:25:06 </td>
   <td style="text-align:left;"> $TSLA such a scammer. He waited for Tesla news to dry up in the media then he reported to hold Tesla shares up. https://www.washingtonpost.com/technology/2022/04/06/musk-twitter-sec/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:23:54 </td>
   <td style="text-align:left;"> $TSLA gap down to 1020 imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:21:50 </td>
   <td style="text-align:left;"> $TSLA any way we drop 20% by Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:20:41 </td>
   <td style="text-align:left;"> $QQQ $TSLA $SPY 

Couldnt post earlier here ya go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:19:44 </td>
   <td style="text-align:left;"> $TSLA I bought so many calls this is one those days that it opens green asf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:18:57 </td>
   <td style="text-align:left;"> $TSLA just hang and wait for the see saw to go in your direction. In the mean time, I’m gonna ride my motorcycles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:17:38 </td>
   <td style="text-align:left;"> $TWTR $TSLA $DOGE $TWTR
Elon paid for my Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:17:34 </td>
   <td style="text-align:left;"> $TSLA FSD this is and easy 10x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:13:41 </td>
   <td style="text-align:left;"> $SPY $TSLA $PLTR  
 
Technical Analysis   
  
Chart movement next few days gonna follow the Konami cheat code, IYKYK:  
  
&amp;quot;up, up, down, down, left right, left right, B, A, Start&amp;quot;  
  
Next week we all get  extra lifes and the cycle repeats itself! 
 
Fed blasting all red green candles! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:13:06 </td>
   <td style="text-align:left;"> $TSLA giga berlin already at volume? Wepa! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:11:21 </td>
   <td style="text-align:left;"> $TSLA 
Isn&amp;#39;t the event at 4pm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:10:44 </td>
   <td style="text-align:left;"> $TSLA everyone knows the event tomorrow, why wouldn’t it already be factored in … why would that cause sudden price increase ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:10:34 </td>
   <td style="text-align:left;"> $TSLA 

Show me $2k already🔥🔥🔥
I got bills to pay this month🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:09:10 </td>
   <td style="text-align:left;"> $TSLA prob all you mf’ers have is your are trading a bipolar stock, but not trading bipolar yourself. Play both sides no better way to trade a bipolar stock than like you are yourself bipolar.😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:08:30 </td>
   <td style="text-align:left;"> $TSLA when Tesla file for bankruptcy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:08:15 </td>
   <td style="text-align:left;"> $TSLA 
Giga buy for Guga Rodeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:07:46 </td>
   <td style="text-align:left;"> $TSLA I hope this sky rockets tomorrow. Tesla giga factory Austin has its first deliveries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:07:32 </td>
   <td style="text-align:left;"> $TSLA futes looking soooo bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:06:45 </td>
   <td style="text-align:left;"> $TSLA remember Monday when all the bears lost all their money and they didn’t say a word. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:06:10 </td>
   <td style="text-align:left;"> $TSLA mooooooon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:04:02 </td>
   <td style="text-align:left;"> $TSLA I’m absolutely infuriated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:03:22 </td>
   <td style="text-align:left;"> $SPY do you know how I got into options trading? $TSLA $AAPL $AMC I was told not to trade options when I didn’t know what options were…so I looked them up
And became an addict gambler 🐷🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:01:06 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/SawyerMerritt/status/1511558499695792137?t=pylUJihnR0FCXIfWwia0RA&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 07:00:44 </td>
   <td style="text-align:left;"> $TSLA The only new thing tomorrow that could help the bulls in any meaningful way is the announcement of the Tesla compact car, which is their most important project. But that will be produced in Shanghai so the chances of it appearing tomorrow is close to zero </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:56:13 </td>
   <td style="text-align:left;"> $TSLA it’s always been you. I’m sorry I fcked with others they didn’t mean anything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:56:09 </td>
   <td style="text-align:left;"> $TSLA come on musky, give us a one last thing moment tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:54:46 </td>
   <td style="text-align:left;"> $TSLA no brainer tomorrow with the event and the mystery vehicles along with cybertruck. Don’t think 1200 is out of the question </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:54:43 </td>
   <td style="text-align:left;"> $TSLA puts getting shredded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:54:17 </td>
   <td style="text-align:left;"> $TSLA so damn bipolar anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:53:34 </td>
   <td style="text-align:left;"> $TSLA Market makers will start making your puts worthless tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:51:14 </td>
   <td style="text-align:left;"> $TSLA over the years we had to deal with some big boys trying to short this and their sheep&amp;gt; but they ran broke to puts for face egh.. this new round have nothing compared to what we went through... Yet they still play believing the market swings can beat Musk and Team..🙃🙂😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:49:12 </td>
   <td style="text-align:left;"> $TSLA 

They have NO idea!

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:48:20 </td>
   <td style="text-align:left;"> $TSLA can’t wait for musk to merge SpaceX through $IPOF soon!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:48:09 </td>
   <td style="text-align:left;"> $TSLA shares are going to 100,000 per share anyhow so you only need a small amount to retire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:48:05 </td>
   <td style="text-align:left;"> $TSLA are puts gonna run tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:47:04 </td>
   <td style="text-align:left;"> $TSLA Americans better step up to the plate come November. Democrats have destroyed the best country in the world in just 16 months. 

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:45:58 </td>
   <td style="text-align:left;"> $SPY MUUUUUUSK…… come out and PLAAAAYA….. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:45:53 </td>
   <td style="text-align:left;"> $TSLA We need to break this range Bulls 🔎 
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:45:16 </td>
   <td style="text-align:left;"> $TSLA BEAR FACE RIPPER TOMORROW!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:43:09 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Works With Toyota To Develop Cameras: 
https://www.youtube.com/watch?v=ImA5sw6qKhY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:39:39 </td>
   <td style="text-align:left;"> $AAPL ....My Goodness where are all the chart hating Pumpers now...🤷‍♂️ As of now we&amp;#39;ve got from a $178 to $171.... Just gonna keep screenshot within screenshot until this goes to a $150...ish....$TSLA $SPY $QQQ $UVXY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:39:00 </td>
   <td style="text-align:left;"> $TSLA gap up bigly from Giga Texas event </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:37:44 </td>
   <td style="text-align:left;"> $TSLA  gap up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:37:10 </td>
   <td style="text-align:left;"> $TSLA $AAPL please please bounce back. Holding strong calls for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:36:38 </td>
   <td style="text-align:left;"> $TSLA Key levels I&amp;#39;m watching tomorrow: 
 1030, 1060 and 1126 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:36:34 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:35:28 </td>
   <td style="text-align:left;"> $TSLA  bound to hit $1500 just before going into split. Hold !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:35:21 </td>
   <td style="text-align:left;"> $TSLA  if cyber truck plus the other two mystery vehicles are unveiled tomorrow I don’t think 1200 tomorrow is crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:34:26 </td>
   <td style="text-align:left;"> $TSLA after market action looks strong... 1200 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:32:38 </td>
   <td style="text-align:left;"> $TSLA greeeennn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:32:34 </td>
   <td style="text-align:left;"> $TMC Boom! Latest update on the company with the World&amp;#39;s Largest Nickel Reserves!  
-TMC is up 5.13% in the sea of red. 
-TMC insiders bought a total of 6.2 millions of shares with $3.02 average. 
-US oil and gas giants TransOcean and Oil States are transitioning into Deepsea Mining. 
-TMC and Epsilon Carbon have signed an agreement to set up the world&amp;#39;s first polymetallic nodules processing plant. 
-Price is above 20, 50, and 100 Moving Averages.  
-MACD Bullish Crossover on the daily chart 
-RSI Cooled down and set-up for another run 
-Technical Analysis showing &amp;quot;BUY&amp;quot; on  Tradingview&amp;#39;s daily chart 
 
$TSLA $LCID $MULN $WKHS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:32:27 </td>
   <td style="text-align:left;"> $AAPL $TSLA these hand selected overvalued turds have much more room to fall still and bring down the $SPY with it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:32:27 </td>
   <td style="text-align:left;"> $TSLA good news is giga Austin not canceled woohoo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:31:46 </td>
   <td style="text-align:left;"> $TSLA  fish bowl perhaps?  All glass roof </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:30:45 </td>
   <td style="text-align:left;"> $TSLA this belongs at 50 bucks a share and thats generous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:30:37 </td>
   <td style="text-align:left;"> $TSLA  financial fake news engaged  by biden admin to attack Elon...and those little woke bitches get right in line just like cnn,msnbc, and the likes.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:30:18 </td>
   <td style="text-align:left;"> $TSLA After Hour Chart 🔎 
 
Who played this range today ? 
 
https://discord.com/invite/uQ5UXZW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:26:34 </td>
   <td style="text-align:left;"> $TSLA $GOOG $AMZN  I want to buy 2024 calls after these three split. Am I making the right move here ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:25:48 </td>
   <td style="text-align:left;"> $TSLA Cyber Rodeo gonna rip face tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:23:56 </td>
   <td style="text-align:left;"> $IPOF bears and shorts have to cover or they will go bankrupt if merger news hit today or tomorrow, be smart 
 
$IPOD $TSLA All the DD we have done indicates it is SpaceX or Starlink </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:23:20 </td>
   <td style="text-align:left;"> $TSLA LFP batteries r the future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:22:52 </td>
   <td style="text-align:left;"> $TSLA cybertruck coming tomorrow. Get ready for an insane gap up. 
$SPY $GM $F $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:22:50 </td>
   <td style="text-align:left;"> $TSLA recovery mode coming I’m not even worried </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:21:52 </td>
   <td style="text-align:left;"> $TSLA everyone just has predictions. Nothing is true! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:21:35 </td>
   <td style="text-align:left;"> $TSLA Tesla could have a few surprises at Cyber Rodeo – two Cybertrucks and some unidentified vehicles spotted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:19:13 </td>
   <td style="text-align:left;"> $CFVI 🎙️Breaking News

Rumble Reported Massive March Growth Numbers 🤳🌐🚀

Content Creators Earning 💸

YouTube loosing Global Share to RUMBLE due to Cancel Culture😈

Rumble: Freedom of speech 🌐
(Backed by Peter Thiel $TSLA  Elons Founding Partner in $PYPL &amp;amp; Spacex)

$DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:18:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

I’m gonna ride this pig down like dr. burry in 08 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:17:39 </td>
   <td style="text-align:left;"> $TSLA remember that time only days ago every bullshitter was screaming $1250 end of the week ? Wow the last 2 days certainly a slice of humble pie eh ? 😂 Tsla last 48 hours ripping new bull assholes wide open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:16:58 </td>
   <td style="text-align:left;"> $TSLA Love the Members Since April 6 2022 giving advice talking crap!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:16:47 </td>
   <td style="text-align:left;"> $TSLA if it does this then it could do that. 

Wow. How insightful! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:15:22 </td>
   <td style="text-align:left;"> $NIO remember this stock was $2 2 years ago. They have to keep it in 20s for a bit before next run to $400 with consolidation to $200. 

$TSLA my major holding is good. But even a 1 year old will know which has exponential potential out of the two. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:14:48 </td>
   <td style="text-align:left;"> $TSLA Telsa cyber rodeo the hottest ticket in town </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:14:25 </td>
   <td style="text-align:left;"> $TSLA if she close above 1050+ we could see a lag up to 1065+ 🔥🔥🔥 hodl tomorrow should be interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:13:49 </td>
   <td style="text-align:left;"> $TSLA 4pm Texas time-midnight, imagine a 20:1 announcement 😯🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:13:31 </td>
   <td style="text-align:left;"> $UPST The shorts doubled down today.  All you need to know is that they haven&amp;#39;t covered a cent.  I have a friend who work for the hedge fund and he told me to buy the dip now. $AAPL $TSLA $AMD $INTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:13:05 </td>
   <td style="text-align:left;"> $TSLA If you don’t think this is a good price to get in! Remember this was at $1152 yesterday!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:12:47 </td>
   <td style="text-align:left;"> $TSLA why would tsla go down tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:12:20 </td>
   <td style="text-align:left;"> $TSLA 8 shares @ avg price 1090 🦅 &amp;amp; hodl 2 960puts expiring this week 🎰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:11:45 </td>
   <td style="text-align:left;"> #WallStreetBets Top Stock Mentions Today #WSB  (NFA)               
$TLRY $HMHC $TSLA $GME  
  
financials.fyi/sentiment/reddit/wallstreetbets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:11:18 </td>
   <td style="text-align:left;"> $AABB Bashers post together (3) in a 5 minute window. LMAO that might help work better. Lol $TSLA $AAPL $MSFT $NFLX Watch $AABB in 2022 make a nice run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:09:05 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-04-06 Daily Forecast Video: 
https://www.youtube.com/watch?v=HjNv5eDu3ik </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:08:19 </td>
   <td style="text-align:left;"> $IPOF I cant imagine a run like $DWAC here, options will run 100K% 
 
$TSLA $IPOD I think IPOF and IPOD will be used together to merge into SpaceX Starlink </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:08:05 </td>
   <td style="text-align:left;"> $TSLA next buy 50 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:07:05 </td>
   <td style="text-align:left;"> $TSLA bullish cross 🔥🚀 1150+ test incoming 🧌🐊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:03:56 </td>
   <td style="text-align:left;"> $TSLA 

This is now at 38 forward P/E !! 

By WS standards which they have it at 68 based on their own PTs, delivery estimates and EPS, is vey undervalued !! 

I have it at 50 (forward- very conservative ) Multiple which translates to $1400 now !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:03:11 </td>
   <td style="text-align:left;"> $TSLA there a fomc meeting tmrw ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 06:01:04 </td>
   <td style="text-align:left;"> Daily Market Recap for Monday 4/4/2022 for #Stocks #Bitcoin #Gold and #Silver 
https://www.youtube.com/watch?v=ymOhlFnA_hI 
Tech is the laggard, easier to short vs materials 
 
$AAPL $AMD $TSLA $RBLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:59:30 </td>
   <td style="text-align:left;"> $TSLA short the rodeo ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:58:28 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $1250.00 Call for Friday, May 20, 2022. Roughly 935 Thousand dollars! 💰💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:57:45 </td>
   <td style="text-align:left;"> $TSLA Help me if my thinking is wrong. I know the last share split this continued to rise but the share count is already 1 billion. After the share split, it could be upwards of 6 billion. Won&amp;#39;t that make it fairly hard to see gains with that much dilution? There would need to be a crazy amount of money put in to push it up. Feel free to correct me if I&amp;#39;m wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:57:21 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=OcIWAUpjc48 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:56:52 </td>
   <td style="text-align:left;"> $TSLA why aren’t we trending giga tomm. Somebody @ Elon tell him to tweet from his website </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:56:27 </td>
   <td style="text-align:left;"> $TSLA $1,500 tomorrow 

Elon has been quiet about Tesla for a while. New battery, cybertruck, new model y, semi, lots of people that are there are going to be buying Tesla stock. 

Let the run begin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:56:15 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Why Tesla Shares Rose 24% Last Month https://www.stck.pro/news/TSLA/25741502 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:55:44 </td>
   <td style="text-align:left;"> $IPOF can you imagine DA today before 8 pm? The massive squeeze while the markets are closed and bears shorts trapped, it will explode tomorrow to infinite short covering after short covering! $IPOD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:53:45 </td>
   <td style="text-align:left;"> I am sorry $TSLA bulls.  
BUT if you were to look at this where do you think we go?  
Don&amp;#39;t deny that we have to try and complete the gap-fill and more than likely wick off 1000.  
All we don&amp;#39;t want to see is TSLA get below 1000 and start rejecting. 
 
P.S LONG-TERM I am BULLISH! 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:52:23 </td>
   <td style="text-align:left;"> $TSLA  GIGA THESE CALL BEARS!
ATX CHECKMATE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:52:21 </td>
   <td style="text-align:left;"> $IPOF  👈🔥🔥 $DWAC  $TWTR  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:52:07 </td>
   <td style="text-align:left;"> $TSLA pt = $86/share eoy (without any stock splits)  rumor going around that Shanghai Tesla may remain locked down for most of April </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:52:04 </td>
   <td style="text-align:left;"> $TSLA 1100 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:51:42 </td>
   <td style="text-align:left;"> $TSLA will fly tmrw because that’s how odds work in the stock casino </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:50:54 </td>
   <td style="text-align:left;"> $TSLA weekly options are for suckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:49:23 </td>
   <td style="text-align:left;"> $SPY $Tsla 
And $Amd puts holding overnight. 
Wish me luck lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:49:03 </td>
   <td style="text-align:left;"> $TSLA  I have been waiting for this rodeo. Got shaken out of my swing this morning. Made 11.26% trading a put which recovered my losses from the gap down open and a call that was ok.

I got one day trade left for the week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:49:00 </td>
   <td style="text-align:left;"> $TSLA: The EPS has grown by an impressive 204.86% over the past year. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:48:23 </td>
   <td style="text-align:left;"> $TSLA when can i buy a tesla truck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:47:53 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:47:05 </td>
   <td style="text-align:left;"> $TSLA shorting this stock is the equivalent to being suicidal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:45:03 </td>
   <td style="text-align:left;"> $TSLA ALL YOU NEED TO KNOW IS THAT THE SHORTS WILL COVER 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:44:11 </td>
   <td style="text-align:left;"> $TSLA Option to look at... 👀 👀  $150.00 Put for Friday, December 16, 2022. Roughly 171 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:43:56 </td>
   <td style="text-align:left;"> $TSLA giga tomm, cyber trucks pulled up and y’all buying puts 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:43:33 </td>
   <td style="text-align:left;"> $MSFT $AAPL $TSLA $SPY red or green tomorrow? Place your bet please 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:40:58 </td>
   <td style="text-align:left;"> $QQQ $NVDA $TSLA $SPY https://www.youtube.com/watch?v=JlEGU2ypr1Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:40:31 </td>
   <td style="text-align:left;"> $TSLA 😈😈😈🐀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:40:19 </td>
   <td style="text-align:left;"> $TSLA share split will at $400 is how
Much this pos is going down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:39:48 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:39:38 </td>
   <td style="text-align:left;"> $EXN x $TSLA :  
https://twitter.com/djseanzito/status/1511764478597160970 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:38:01 </td>
   <td style="text-align:left;"> So am i missing anything that Elon pumped? Feel like there is more but this is all I can think of currently. $TSLA $GME $BTC.X $DOGE.X $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:34:51 </td>
   <td style="text-align:left;"> Has Elon Musk Sold Shares Of Twitter Already? https://www.billionaireclubcollc.com/has-elon-musk-sold-shares-of-twitter-already/  $TWTR $TSLA $DWAC $FB  $SNAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:33:30 </td>
   <td style="text-align:left;"> $TSLA 

If anyone thinks that earnings will help in this fed environment, they have another thing coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:33:13 </td>
   <td style="text-align:left;"> $TSLA sure looks like Cybertruck got three variants. We will see tomorrow if this rockets back to 1100 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:31:41 </td>
   <td style="text-align:left;"> $TSLA $TWTR $FB $GOOG 

Elon Musk: Should I start a new social media platform? -posted on Twitter 

Twitter stock: -27% 

Elon Musk: I bought 9.2% of Twitter 

Twitter stock: +40%. 

Elon: I’m playing fucking chess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:31:28 </td>
   <td style="text-align:left;"> $TSLA Hi, Anyone here think IPOF is starlink? Not tagging the ticker cos they all seem like a desperate bunch of morons imo!? 🤔🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:30:56 </td>
   <td style="text-align:left;"> $TSLA who else high af rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:30:55 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 4/6/2022 $SPY $QQQ $NVDA $TSLA $FB https://www.youtube.com/watch?v=R1H-HyeAHAw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:30:25 </td>
   <td style="text-align:left;"> $SPY $TSLA Market was resilient today,  but how long? The minutes were not good, chk the details foolios 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:30:17 </td>
   <td style="text-align:left;"> $TSLA i am so desperate for 1200s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:29:57 </td>
   <td style="text-align:left;"> $VIX  shooting star on the VIX looks nice. Yes, we’re in economic ruin but the inverted yield curve is a lagging indicator. This could be a lower high coming for the overall topping process. Unlikely but possible $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:29:32 </td>
   <td style="text-align:left;"> $TSLA 4 analysts upgraded price targets
... you know what that means? Sell-off secured! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:28:54 </td>
   <td style="text-align:left;"> $TSLA  
 
Below $1000 by tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:27:47 </td>
   <td style="text-align:left;"> $TSLA 🚨🧌🐊 last contract placed before AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:27:08 </td>
   <td style="text-align:left;"> $TSLA Tesla Fires on All Cylinders; Deutsche Bank Says ‘Buy’ https://www.tipranks.com/news/article/tesla-fires-on-all-cylinders-deutsche-bank-says-buy/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:26:43 </td>
   <td style="text-align:left;"> $TSLA desperation by the hedge wanting to exit this garbage.... 🤣  these losers are so predictable. 

https://seekingalpha.com/news/3786906-tesla-pt-raised-to-1300-by-morgan-stanleys-jonas-after-q4-unit-beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:26:21 </td>
   <td style="text-align:left;"> $TSLA giga this up 5% giga that up 10%.  PT 10K </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:25:54 </td>
   <td style="text-align:left;"> $TSLA The stock is still in a major 6 month downtrend starting with the 52 week high in November which has produced multiple lower highs and lower lows. Yesterday was another lower high. 800s or even 700s are entirely possible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:25:43 </td>
   <td style="text-align:left;"> $TSLA buying more calls in the morning! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:23:40 </td>
   <td style="text-align:left;"> $TSLA Is there someone to talk to? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:23:25 </td>
   <td style="text-align:left;"> $IPOF SELL ALL YOUR STOCKS AND GO ALL IN BEFORE WE MERGE, I BET IT IS SPACEX/STARLINK 
 
EASY $100 IF IT IS SPACEX/STARLINK 
 
$TSLA $IPOD $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:22:50 </td>
   <td style="text-align:left;"> $TSLA 2 days each with ~5% drop. Tomorrow happens to be Giga Texas day. You decide to still swing puts hoping for a gap down.

➡️➡️You need Jesus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:22:10 </td>
   <td style="text-align:left;"> $TWTR $TSLA how ironic the guy that manipulates markets the most owns the biggest stake in Twitter lol wonder why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:21:41 </td>
   <td style="text-align:left;"> $IPOF $TSLA STARLINK!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:20:23 </td>
   <td style="text-align:left;"> $TSLA 1st delivery of cybertruck completed!! Woohooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:16:54 </td>
   <td style="text-align:left;"> $TSLA Does anyone know when we are likely to get a split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:14:19 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : No more radar for Tesla EVs headed for Europe, Middle East https://www.stck.pro/news/TSLA/25738868 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:13:40 </td>
   <td style="text-align:left;"> $TSLA dang, I bought so many August expiratin puts today, Strike price 700.  This stonk about to fucking shit all over itself these upcoming weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:13:20 </td>
   <td style="text-align:left;"> $TSLA $1200 Soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:13:20 </td>
   <td style="text-align:left;"> $TSLA  I&amp;#39;m still holding out for that heroic 0 dte Friday move of $50+...wonder if I will ever profit from a Friday morning strangle? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:11:08 </td>
   <td style="text-align:left;"> $JASMY.X Only crypto running $DOGE.X $SHIB.X $BTC.X $TSLA   Smart marketing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:10:43 </td>
   <td style="text-align:left;"> $TWTR $DWAC $TSLA $AMZN 
Accurate??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:09:54 </td>
   <td style="text-align:left;"> $TSLA oh we’re just getting started fellas. This thing will settle around $450-$600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:09:33 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:09:14 </td>
   <td style="text-align:left;"> $MN.CA my average is at .57 , I will add 10k more shares tomorrow,  with this war and stuff , this Canadian resource will be an amazing oppurtunity and hopefully TESLA $TSLA makes a deal with this battery hill project ... 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:08:57 </td>
   <td style="text-align:left;"> $TSLA when Twitter stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-07 05:08:47 </td>
   <td style="text-align:left;"> $TSLA the FED manipulates the market with TALK..... LIES in fact. Its comical beyond belief that people still think the FED isn&amp;#39;t creating inflation on purpose via INACTION. Yet they keep &amp;quot;threatening&amp;quot; to do something.  😆 </td>
  </tr>
</tbody>
</table></div>

---
