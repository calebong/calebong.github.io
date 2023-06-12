---
output:
  html_document:
    keep_md: true
---

# Research Portfolio

A preview of my experience in workflow conceptualization, idea implementation, and deployment of financial and risk management analytical tools, which are used/have been used in everyday work.

* Forecasting Models
  * Monthly Country Industry Performance and Risk Forecast Model
  * Daily Country Industry Risk Monitoring and Forecast Model
  * Target Stock Price Setting for US Listed Equities
  * Economic Forecasting
  * Currency Forecasting
  
* Data Scraping
  * Financial News Scraping
  * Stock Tweets Scraping
  
---

## Forecasting Models

---

### Monthly Country Industry Performance and Risk Forecast Model

#### Gradient boosting frameworks for emprical probabilistic assessments of market sectors performance and risk expectations. Implementable and scalable across industries and sub sectors of many countries. The preview document highlights the workflow and analysis, as applied to the 11 main USA GIC sectors and some investment style factors.

[Preview Document](/pdf/Preview-Monthly-Country-Industry-Forecast-Model.pdf)

<img src="images/demoRmdUsa.png?raw=true"/>

---

### Daily Country Industry Risk Monitoring and Forecast Model

#### Markov-switching GARCH models for market sectors risk monitoring and risk expectations assessment. Implementable and scalable across industries and sub sectors of many countries. The preview document highlights the workflow and analysis, as applied to the 11 main USA GIC sectors and some investment style factors.


[Preview Document](/pdf/Preview-Daily-Country-Industry-Risk-Forecast-Model.pdf)

<img src="images/demoRmdUsaGarch.png?raw=true"/>

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



Last Updated: 2023-06-12 23:49:33 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 23:48:53 </td>
   <td style="text-align:left;"> South African Stocks End in the Red </td>
   <td style="text-align:left;"> The JSE FTSE All Share index reversed some early gains to close roughly 0.9% down at 76,282 on Monday, the third straight session of drops, mainly pushed down by resource-linked sectors (-2.6%) and financials (-1.7%). Meanwhile, global investors looked ahead to the latest US inflation data and the outcome of the Federal Reserve policy meeting this week. Federal Reserve Chair Jerome Powell is widely expected to halt his yearlong campaign of hiking interest rates to curb inflation, but concerns persist that the decision to hold rates could be only a "skip" instead of a "pause". </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 23:27:17 </td>
   <td style="text-align:left;"> Swiss 10-Year Bond Yield Approaches 9-Month Low </td>
   <td style="text-align:left;"> The yield on the Swiss 10-year government bond retreated past the 1% level, heading toward the nine-month low of 0.87% touched on June 2nd as slowing inflation in the Swiss economy limited the extent of tightening forecasted for the Swiss National Bank. Consumer prices rose by 2.2% annually in May, the least in 15 months and sharply below forecasts from the central bank. Further, core inflation slowed to 1.9%, dropping below the SNB’s upper limit of 2% for the first time in nearly one year. Still, SNB policymakers have stated that the current interest rate of 1.5% is not restrictive enough to curb upside inflationary risks, setting the stage for a final rate hike in its June meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2023-06-12 23:22:18 </td>
   <td style="text-align:left;"> US Gasoline Futures Follow WTI Crude Lower </td>
   <td style="text-align:left;"> Gasoline futures in the US dropped to $2.5 per gallon, tracking a decline in other energy-related commodities due to growing concerns over demand. US oil prices declined to $68 per barrel, as disappointing China economic data offset a boost in prices from Saudi Arabia pledging to cut production by 1 million barrels per day in July. Domestically, the US government has forecasted a slight increase in gasoline consumption from last year to 9.09 million barrels a day between June and August, but still below pre-pandemic levels by more than 6%. Additionally, refiners that have been profitable in recent years may consider cutting output if demand does not maintain their margins, while new supply is coming online as refiners add units for the first time in decades after many closures during the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/inflation-expectations </td>
   <td style="text-align:left;"> 2023-06-12 23:06:00 </td>
   <td style="text-align:left;"> US Inflation Expectations Lowest since March 2021 </td>
   <td style="text-align:left;"> US consumer inflation expectations for the year ahead fell to 4.1% in May 2023, the lowest since March 2021. Median year-ahead expected price changes declined for the cost of college education (down by 0.7 pp to 7.1%), food (down by 0.4 pp to 5.4%), medical care (down by 0.1 pp to 9.2%), and rent (down by 0.1 pp to 9.1%). Median year-ahead expected price changes remained unchanged for gas (at 5.1%). Meanwhile, inflation expectations for the three- and five-year horizons increased by 0.1 percentage point to 3% and 2.7%, respectively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/12/business/dealbook/george-soros-alex-foundation.html </td>
   <td style="text-align:left;"> 2023-06-12 23:02:35 </td>
   <td style="text-align:left;"> George Soros Gives Control of His $25 Billion Foundation to His Son - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                          , Supported by                                                                                                                                                                                                                                                                                                                                                                                           , Alex Soros will take the reins of Open Society Foundations, a grant-making network, from his father, whose support of liberal causes has long made him a boogeyman of the right.                                                                                                                                                                                                                       , By Michael J. de la Merced                                                                                                                                                                                                                                                                                                                                                                             , After decades running one of the most prominent and politically active financial empires, George Soros is handing the reins of his $25 billion Open Society Foundations to his son Alex, the grant-making network confirmed on Monday.                                                                                                                                                                 , The move is another example of succession planning by Wall Street’s old guard. But the changeover is especially notable because it involves the elder Soros, whose unabashed support of liberal causes, to the tune of $1.5 billion a year, has long made him a boogeyman of the right.                                                                                                                , Alex Soros, the second-youngest of George’s five children, was elected the foundation’s chairman in December. He also serves as president of the Soros super PAC and is the only family member on the investment committee for Soros Fund Management, a private investment management firm.                                                                                                            , That will put him in charge of a philanthropic empire, funded from the billions that George Soros made from finance. Over five decades, George Soros cemented his reputation as one of the most successful investors in modern history, particularly when he made more than $1 billion by betting against the British pound in 1992.                                                                   , George Soros, who has already given $32 billion to the Open Society Foundations, has indicated that his fortune will go to his family’s philanthropic efforts. That encompasses a wide range of causes that the foundation describes as fighting injustice and inequality, something that George Soros traces back to his roots as a Holocaust survivor.                                               , Like his father, Alex Soros leans left politically — “We think alike,” George Soros told The Wall Street Journal, which reported the news earlier — and is a prolific backer of Democratic Party causes. Earlier this month, he posted a picture of himself with Vice President Kamala Harris on Twitter and wrote an opinion piece for CNN defending President Biden’s efforts to combat antisemitism., Alex Soros’s rise was considered unlikely to some: The soft-spoken 37-year-old was better known in his younger days for partying than for finance. Many had considered his half brother Jonathan, a lawyer and former Soros employee, to be the more natural successor, until a falling-out with their father more than a decade ago.                                                                  , But over the years, Alex Soros became more involved in his father’s philanthropic endeavors.                                                                                                                                                                                                                                                                                                           , He is inheriting a high-profile role, one that can make him a prominent political target. George Soros has drawn criticism — some laced with antisemitism — for his political and philanthropic activities for years: The Open Society Foundations shut its offices in George Soros’s native Hungary after facing pressure from the country’s prime minister, Viktor Orban.                            , And more recently, George Soros became a target of Elon Musk, who compared him on Twitter to the “X-Men” villain Magneto. “He wants to erode the very fabric of civilization,” the billionaire technology executive wrote. “Soros hates humanity.”                                                                                                                                                     , “I’m the go-to man when they want to blame someone,” George Soros told The Journal.                                                                                                                                                                                                                                                                                                                    , Michael de la Merced joined The Times as a reporter in 2006, covering Wall Street and finance. Among his main coverage areas are mergers and acquisitions, bankruptcies and the private equity industry.  @m_delamerced • Facebook                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/goldman-ceo-says-rates-could-head-higher-on-stickier-inflation </td>
   <td style="text-align:left;"> 2023-06-12 22:47:56 </td>
   <td style="text-align:left;"> Goldman CEO Says Rates Could Head Higher on Stickier Inflation </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.                                                             , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                                                                                 , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                                                                                       , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                                                                              , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                                                                            , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                                                                           , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                                                                           , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                                                                           , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                   , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                           , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                           , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                                                                                        , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                                                                           , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                                                                                      , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                                                                                          , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                                                                             , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                                                                             , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                                                                                , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                   , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                                                                              , Railway Safety Act Should Be Scrapped                                                                                                                                                                                                                                                     , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                                                                                , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                                                                                        , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                                                                            , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                                                                                , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                                                                             , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                                                                           , Augmented Reality Is Coming for Cities                                                                                                                                                                                                                                                    , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                                                                               , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                            , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                                                                               , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                                                                              , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                                                                            , David Solomon                                                                                                                                                                                                                                                                             , Sridhar Natarajan                                                                                                                                                                                                                                                                         , Subscriber Benefit                                                                                                                                                                                                                                                                        , Subscribe                                                                                                                                                                                                                                                                                 , Goldman Sachs Group Inc. Chief Executive Officer David Solomon said the Federal Reserve could still push interest rates higher as inflation remains stubbornly persistent.                                                                                                                , “Inflation is a little bit stickier, and I do think, in the distribution of outcomes, there’s a reasonable chance that rates go higher,” Solomon said in an interview Monday with CNBC. “If they do that, it’s probably going to make the economic environment a little more challenging.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2023-06-12 22:29:00 </td>
   <td style="text-align:left;"> WTI Crude Tumbles 5% </td>
   <td style="text-align:left;"> WTI crude futures extended losses to nearly 5% to below $67 per barrel on Monday, the lowest in over five weeks, as concerns about weakening demand in top consumer China and rising Russian crude supply outweighed Saudi Arabia's plans to slash output. Russian oil exports to China and India rose to record levels in May even after the implementation of the European Union’s embargo and the Group of Seven’s price cap mechanism that started in early December. On the other hand, Saudi Arabia, the world's largest oil exporter, announced earlier this month its intention to reduce output by 1 million barrels per day to 9 million bpd in July, the lowest level in years amid an effort to bolster crude prices. Meanwhile, investors are cautious ahead of a busy week ahead with the US inflation rate and interest rate decisions from the Federal Reserve, the ECB and the BoJ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 22:06:54 </td>
   <td style="text-align:left;"> TSX Underperforms on Monday </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite index booked slight losses to hover near the 19,870 mark on Monday, underperforming its counterparts in the United States due to the heavy weight of resource-linked companies in the Toronto Exchange. Oil companies led the losses, tracking the sharp retreat in crude oil prices with Cenovus Energy sinking nearly 2%, while Canadian Natural Resources and Suncor Energy dropped 0.8% each. Gold prices also edged lower in the session ahead of the US inflation print tomorrow and the Federal Reserve’s decision on Wednesday, pressuring shares of Canadian gold miners. In the meantime, Teck Resources dropped by 1% after Glencore offered to buy its steelmaking coal business as an alternative to the $23 billion takeover that the Canadian miner repeatedly rejected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2023-06-12 22:01:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Up for 6th Day </td>
   <td style="text-align:left;"> The Baltic Exchange's main sea freight index, which measures the cost of shipping goods worldwide, was up for a sixth day on Monday, rising 0.1% to its highest since May 30th at 1,056 points. The capesize index, which tracks vessels typically transporting 150,000-tonne cargoes such as iron ore and coal, rose 1.2% to 1,532 points. "Demand for (capesize vessels) is being supported by coal chartering into India and Vietnam," said Alexis Ellender, dry bulk analyst at Kpler, adding that higher electricity usage in the summer months is contributing to higher demand for coal. Meanwhile, the panamax index, which tracks ships that usually carry coal or grain cargoes of about 60,000 to 70,000 tonnes, fell 0.2% to 1,144 points; and the supramax index dropped 10 points to an almost four-month low of 726 points. "We're seeing slower grain chartering out of Ukraine in the Black Sea because only two ports are operating since the renewal of the grain export agreements", noted Ellender. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/colony-im-is-said-in-talks-to-buy-stake-in-art-gallery-perrotin </td>
   <td style="text-align:left;"> 2023-06-12 22:00:00 </td>
   <td style="text-align:left;"> Colony IM in Talks to Buy Stake in Art Gallery Perrotin </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.  , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                      , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                            , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                   , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                 , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                        , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                             , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                           , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                               , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                  , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                  , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                     , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                        , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                   , Railway Safety Act Should Be Scrapped                                                                                                                                                                                          , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                     , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                             , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                 , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                     , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                  , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                , Augmented Reality Is Coming for Cities                                                                                                                                                                                         , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                    , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                 , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                    , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                   , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                 , Angelina Rascouet                                                                                                                                                                                                              , Subscriber Benefit                                                                                                                                                                                                             , Subscribe                                                                                                                                                                                                                      , Colony Investment Management is in exclusive talks to buy a majority stake in Perrotin, a contemporary art gallery, according to people familiar with the matter.                                                              , A deal between the fund headed by Nadra Moussalem and the French business created by Emmanuel Perrotin could be announced as soon as this week, the people added, asking not to be identified discussing private negotiations.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/earl-cadogan-billionaire-head-of-uk-property-empire-dies-at-86 </td>
   <td style="text-align:left;"> 2023-06-12 21:50:44 </td>
   <td style="text-align:left;"> Earl Cadogan, Billionaire Head of UK Property Empire, Dies at 86 </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News., Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                    , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                          , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                 , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                               , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                              , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                              , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                              , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                      , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                              , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                              , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                           , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                              , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                         , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                             , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                   , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                      , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                 , Railway Safety Act Should Be Scrapped                                                                                                                                                                                        , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                   , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                           , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                               , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                   , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                              , Augmented Reality Is Coming for Cities                                                                                                                                                                                       , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                  , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                               , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                  , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                 , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                               , Charles Cadogan                                                                                                                                                                                                              , Photographer: Max Mumby/Indigo/Getty Images                                                                                                                                                                                  , Benjamin Stupples                                                                                                                                                                                                            , Subscriber Benefit                                                                                                                                                                                                           , Subscribe                                                                                                                                                                                                                    , Charles Cadogan, the billionaire aristocrat behind one of London’s biggest real estate fortunes, has died. He was 86.                                                                                                        , He died on Sunday at home in Chelsea, according to a statement from his family’s namesake investment firm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/12/business/media/fox-news-tucker-carlson-twitter.html </td>
   <td style="text-align:left;"> 2023-06-12 21:48:32 </td>
   <td style="text-align:left;"> Fox News Tells Tucker Carlson to Stop Posting Videos on Twitter - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The network and its former star host have been engaged in an increasingly bitter dispute over Mr. Carlson’s Twitter videos, which Fox says violate his contract.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By Jeremy W. Peters and Benjamin Mullin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fox News has demanded that Tucker Carlson stop posting videos to Twitter, escalating the dispute between the network and its former star host over how — and if — he can continue to speak publicly now that his prime-time show is off the air.                                                                                                                                                                                                                                                                                                                                                                                                , In a letter sent to Mr. Carlson from Fox lawyers, the network accused him of violating the terms of his contract, which runs until early 2025 and limits his ability to appear in media other than Fox. The letter is labeled “not for publication,” in all caps.                                                                                                                                                                                                                                                                                                                                                                               , Since Mr. Carlson was ousted by Fox News, he has begun producing a bare-bones version of his Fox program, “Tucker Carlson Tonight,” and posting it directly to Twitter. The new show, called “Tucker on Twitter,” bears some of the hallmarks of his prime-time show on Fox, including a monologue focused on current affairs and cultural issues.                                                                                                                                                                                                                                                                                              , Harmeet K. Dhillon, a lawyer representing Mr. Carlson, said in a statement that Fox News’s legal threat was not in the interest of the network’s audience.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “Doubling down on the most catastrophic programming decision in the history of the cable news industry, Fox is now demanding that Tucker Carlson be silent until after the 2024 election,” the statement read. “Tucker will not be silenced by anyone.”                                                                                                                                                                                                                                                                                                                                                                                         , Justin Wells, Mr. Carlson’s former executive producer, said on Twitter that the next episode of Mr. Carlson’s show, expected on Tuesday, would feature Mr. Carlson’s response to the indictment of former President Donald J. Trump.                                                                                                                                                                                                                                                                                                                                                                                                            , Axios earlier reported that Fox sent Mr. Carlson the cease-and-desist letter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , A spokeswoman for Fox News said the network had no comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Fox’s decision to take Mr. Carlson off the air shocked him and the wider media and political world when the network announced the move in a terse, four-sentence statement. A series of public relations and management headaches led to his downfall, according to multiple interviews with people inside the company. Much to the dismay of senior Fox executives, including the chief executive of Fox Corporation, Lachlan Murdoch, Mr. Carlson continued to push conspiracy theories about the Jan. 6, 2021, assault on the Capitol. A former Carlson producer filed a lawsuit alleging he allowed a hostile, sexist workplace to flourish., And as part of the defamation lawsuit against Fox by Dominion Voting Systems, which the network settled in April for $787.5 million, Mr. Carlson’s personal text messages became public, revealing how he spoke disparagingly about Fox executives and Mr. Trump.                                                                                                                                                                                                                                                                                                                                                                               , After the discovery of one particularly incendiary text from Mr. Carlson, the Fox Corporation board decided to begin an internal investigation into his conduct. A few days later, he was out.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Mr. Carlson’s cancellation — he is still an employee of Fox unless the network decides to let him out of his contract — has upended Fox’s lucrative and popular prime-time lineup. The perennial top-rated cable news network by a wide margin, Fox has suffered a significant drop in viewership across the board in recent weeks. Roughly one-third of its prime-time audience has tuned out since Mr. Carlson was taken off the air.                                                                                                                                                                                                         , Fox News had been loath to pick a public fight with its former star, who has commanded one of the biggest followings in conservative media and demonstrated a distinctive ability to shape some of the biggest policy debates in Republican politics. The network has been publicly silent as Mr. Carlson and his associates threatened — mostly through anonymous leaks in the media — to release their own programming and to attack Fox in the process.                                                                                                                                                                                      , Fox’s attempt to force Mr. Carlson off Twitter indicates that talks between his lawyers and representatives for the network are becoming strained and that Fox executives are becoming more pessimistic about reaching an amicable agreement on the terms of his departure.                                                                                                                                                                                                                                                                                                                                                                     , Mr. Carlson’s lawyers have argued that Fox News breached its contract with Mr. Carlson first, in part by failing to prevent his private messages from being disclosed. The former Fox host also believes his Twitter show is protected speech under the First Amendment, according to a person with knowledge of Mr. Carlson’s legal strategy.                                                                                                                                                                                                                                                                                                  , Mr. Carlson’s Twitter videos — recorded at his studio in Maine — have received considerable attention from the news media. Twitter does not release data on how much time its users spend watching videos, making it impossible to know how many people watched Mr. Carlson’s posts for any extended period.                                                                                                                                                                                                                                                                                                                                    , Mr. Carlson joins a long list of television news stars who have tried to use their fame to reach a large audience without the platform of a major broadcast or cable network behind them. Success is not easy to quantify. Katie Couric of CBS News and Ted Koppel of ABC News found it difficult to replicate the clout they once enjoyed after they branched out into their own ventures. A series of former Fox News stars have also seen their influence diminished, including Glenn Beck, Bill O’Reilly and Megyn Kelly.                                                                                                                   , Even Oprah Winfrey struggled to convert her enormous star power into ratings with the launch of her cable network, OWN.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Jeremy W. Peters covers media and its intersection with politics, law and culture. He is the author of “Insurgency: How Republicans Lost Their Party and Got Everything They Ever Wanted.” He is a contributor to MSNBC.  @jwpetersnyt • Facebook                                                                                                                                                                                                                                                                                                                                                                                               , Benjamin Mullin is a media reporter for The Times, covering the major companies behind news and entertainment.  @benmullin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 21:45:00 </td>
   <td style="text-align:left;"> Brazilian Equities Waver </td>
   <td style="text-align:left;"> Brazil’s Ibovespa stock index swung between small losses and gains around 116,900 on Monday, tracking a cautious mood in international markets, in anticipation of central bank meetings in the US, Europe and Japan, as well as a crucial US inflation report. In the domestic scenario, projections for inflation fell again to 5.42% in 2023 and 4.04% in 2024, on the heels of a stronger-than-expected slowdown in consumer price increases in May; while this year's GDP estimate rose for the second week to 1.84% from 1.68%. On the corporate front, heavyweight miner Vale and steel companies along with oil companies were among the biggest laggards, amid falling prices of iron ore and crude oil. On the flip side, Braskem shares surged over 7%, after confirming that controller Novonor received a bid from Unipar Carbocloro for a stake in the company, which valued each share in the firm at 36.50 reais. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 21:37:00 </td>
   <td style="text-align:left;"> US Stocks Rise Ahead Inflation, Fed </td>
   <td style="text-align:left;"> The Dow Jones rose 20 points on Monday, the S&amp;P 500 was up 0.3% and the Nasdaq 0.4% as investors are hopeful that inflationary pressures would show further signs of easing, supporting the case for a pause in the Fed’s interest rate hikes this week. The US inflation rate is forecasted to fall 4.1% in May, the lowest since March 2021, from 4.9% in April while the core gauge may decelerate to 5.2% from 5.5%. Most market participants expect the US central bank to leave interest rates unchanged at the current levels but there is a 30% chance of a rate hike depending on the CPI reading and after surprise moves in Australia and Canada last week. Among single stocks, Nasdaq tumbled 10% after the exchange operator said it agreed to acquire Adenza. Oracle was up nearly 4% ahead of earnings results after the market close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 21:29:38 </td>
   <td style="text-align:left;"> Indian Bond Yields Remain Close to 1-Year Low </td>
   <td style="text-align:left;"> The yield on the Indian 10-year government bond remained close to 7%, not far from the 13-month low of 6.96% touched on May 16th as loose monetary policy from the RBI outweighed expectations of further tightening from other central banks worldwide. The latest data showed that consumer prices rose by 4.25% domestically in May, the lowest in two years and below market forecasts of 4.42% to approach the RBI’s target inflation rate of 4%. While the RBI underscored the risks that El Nino may pose to India’s food prices, the data suggested that borrowing costs are restrictive enough to fight against inflation in the Indian economy The development contrasts with stubbornly high inflation across North America and Europe, expected to cause the FED and the ECB to extend rate hikes in upcoming meetings, thus limiting the declines in Indian bonds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/warren-buffet-is-making-occidental-oxy-stock-trade-like-exxon-xom </td>
   <td style="text-align:left;"> 2023-06-12 21:15:27 </td>
   <td style="text-align:left;"> ‘Buffett Effect’ Is Making Occidental’s Stock Trade Like Exxon’s </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.                                                                                                                                                               , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                                                                                                                                                                                   , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                                                                                                                                                                                         , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                                                                                                                                                                                , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                                                                                                                                                                              , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                                                                                                                                                                             , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                                                                                                                                                                             , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                                                                                                                                                                             , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                                                                                                                     , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                                                                                                             , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                                                                                                             , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                                                                                                                                                                                          , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                                                                                                                                                                             , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                                                                                                                                                                                        , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                                                                                                                                                                                            , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                                                                                                                                                                               , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                                                                                                                                                                               , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                                                                                                                                                                                  , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                                                                                                                     , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                                                                                                                                                                                , Railway Safety Act Should Be Scrapped                                                                                                                                                                                                                                                                                                                                                       , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                                                                                                                                                                                  , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                                                                                                                                                                                          , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                                                                                                                                                                              , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                                                                                                                                                                                  , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                                                                                                                                                                               , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                                                                                                                                                                             , Augmented Reality Is Coming for Cities                                                                                                                                                                                                                                                                                                                                                      , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                                                                                                                                                                                 , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                              , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                                                                                                                                                                                 , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                                                                                                                                                                                , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                                                                                                                                                                              , Warren Buffett                                                                                                                                                                                                                                                                                                                                                                              , Geoffrey Morgan                                                                                                                                                                                                                                                                                                                                                                             , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                          , Subscribe                                                                                                                                                                                                                                                                                                                                                                                   , Warren Buffett is shielding Occidental Petroleum Corp. from the worst of the drubbing hitting oil and gas producers and making the stock trade like fossil fuel firms more than five times it size.                                                                                                                                                                                         , For much of the past year, the billionaire investor’s Berkshire Hathaway Inc. has been snapping up Occidental stock whenever it falls under $60, a level shares closed below on Friday as crude prices slid. Buffett’s firm is the largest stockholder with nearly 222 million shares, almost a 25% stake, according to data compiled by Bloomberg — and regulatory permission to buy more.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/saudi-arabia-s-flynas-in-talks-with-airbus-about-placing-order </td>
   <td style="text-align:left;"> 2023-06-12 21:03:13 </td>
   <td style="text-align:left;"> Saudi Arabia’s Flynas in Talks With Airbus About Placing Order </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News., Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                    , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                          , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                 , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                               , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                              , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                              , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                              , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                      , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                              , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                              , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                           , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                              , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                         , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                             , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                   , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                      , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                 , Railway Safety Act Should Be Scrapped                                                                                                                                                                                        , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                   , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                           , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                               , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                   , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                              , Augmented Reality Is Coming for Cities                                                                                                                                                                                       , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                  , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                               , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                  , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                 , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                               , People walk past a model of a Flynas plane in Riyadh, Saudi Arabia.                                                                                                                                                          , Siddharth Vikram Philip and                                                                                                                                                                                                  , Layan Odeh                                                                                                                                                                                                                   , Subscriber Benefit                                                                                                                                                                                                           , Subscribe                                                                                                                                                                                                                    , Sign up for our Middle East newsletter and follow us  @middleeast for news on the region.                                                                                                                                    , Saudi Arabian low-cost carrier Flynas is in talks for an Airbus SE jet order, according to people familiar with the matter, as airlines in the country bulk up operations to better compete with regional rivals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2023-06-12 21:03:00 </td>
   <td style="text-align:left;"> Mexican Peso at Over 7-Year High </td>
   <td style="text-align:left;"> The Mexican peso was changing hands around $17.2, its highest since April 2016, supported by expectations that interest rates will stay high for longer. The central bank, known as Banxico, last month halted a record hiking cycle and promised to keep the key rate at 11.25% for an extended period. Central banker Jonathan Heath said recently in an interview that Mexico will likely keep the key rate at a record high for its next three meetings, as policy must remain restrictive for “as long as possible” to ensure inflation falls back to the 2.0%–4.0% target range. Recent data showed annual inflation cooled for a 4th straight month to 5.84% in May, the lowest level since August 2021; and the core inflation rate also continued to ease to 7.39% in May. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2023-06-12 20:53:00 </td>
   <td style="text-align:left;"> Rupee Holds Rebound After Inflation Print </td>
   <td style="text-align:left;"> The Indian rupee extended recent gains to hover at 82.4 per USD, stretching its rebound since testing record-low levels of 83 on May 19th as the latest macroeconomic data aligned with the hawkish rhetoric from the RBI. Lower food prices drove inflation in the Indian economy to a 2-year low of 4.25% in May, well below market estimates of 4.42%, to approach the central bank’s target of 4%. In the meantime, industrial production expanded by 4.2% annually in April, soaring past forecasts of 1.8% to underscore the resilience of Indian manufacturing to higher interest rates. The result backed the current policy backdrop that no rate cuts are imminent to stimulate growth. Additionally, inflation in the Indian economy remains exposed to the risks of shocks to food prices should El Nino weather threaten supply, hence markets continue to expect that cuts are only due in 2024. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/panel-to-discuss-if-there-s-a-successor-to-credit-suisse-s-cds </td>
   <td style="text-align:left;"> 2023-06-12 20:33:13 </td>
   <td style="text-align:left;"> Panel to Discuss If There’s a Successor for Credit Suisse’s CDS </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.                                                                                                                                                          , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                                                                                                                                                                              , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                                                                                                                                                                                    , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                                                                                                                                                                           , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                                                                                                                                                                         , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                                                                                                                                                                        , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                                                                                                                                                                        , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                                                                                                                                                                        , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                                                                                                                , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                                                                                                        , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                                                                                                        , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                                                                                                                                                                                     , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                                                                                                                                                                        , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                                                                                                                                                                                   , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                                                                                                                                                                                       , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                                                                                                                                                                          , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                                                                                                                                                                          , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                                                                                                                                                                             , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                                                                                                                , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                                                                                                                                                                           , Railway Safety Act Should Be Scrapped                                                                                                                                                                                                                                                                                                                                                  , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                                                                                                                                                                             , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                                                                                                                                                                                     , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                                                                                                                                                                         , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                                                                                                                                                                             , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                                                                                                                                                                          , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                                                                                                                                                                        , Augmented Reality Is Coming for Cities                                                                                                                                                                                                                                                                                                                                                 , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                         , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                                                                                                                                                                            , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                                                                                                                                                                           , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                                                                                                                                                                         , Libby Cherry                                                                                                                                                                                                                                                                                                                                                                           , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                     , Subscribe                                                                                                                                                                                                                                                                                                                                                                              , The panel that oversees the credit-default swap market, the Credit Derivatives Determinations Committees, will discuss whether there’s a so-called successor to Credit Suisse Group AG’s contracts.                                                                                                                                                                                    , With Credit Suisse’s takeover by UBS Group now finalized, the panel received a question earlier on Monday, and will deliberate the issue on Tuesday at 2:00 p.m. in London, according to a statement on the CDDC’s website. If the panel rules that there is a successor, then UBS may become the new reference entity for Credit Suisse’s swaps, but the contracts won’t be triggered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 20:24:20 </td>
   <td style="text-align:left;"> Indian Inflation Slows to 2-Year Low </td>
   <td style="text-align:left;"> The annual inflation rate in India fell to 4.25% in May of 2023 from 4.7% in the previous month, the lowest since April 2021 and firmly below market forecasts of 4.42% amid a fresh slowdown in inflation for food. The result drove inflation closer to the RBI’s target of 4% and extended the decline past the central bank’s upper limit of 6%, paring concerns of an eventual resumption of its tightening cycle. Consumer food inflation fell to 2.91% from 3.84% in the previous month, amid significant deflation for oils and fats (-16.01% vs -12.33% in April), vegetables (-8.18% vs -6.5%), and meat and fish (-1.29% vs -1.23%). In the meantime, inflation slowed for transport and communication (1.1% vs 1.17%), housing (4.84% vs 4.91%), and fuel and light (4.64% vs 5.52%). On a monthly basis, consumer prices rose at a steady pace from the previous month at 0.51%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/industrial-production </td>
   <td style="text-align:left;"> 2023-06-12 20:15:00 </td>
   <td style="text-align:left;"> India Industrial Output Growth Tops Expectations </td>
   <td style="text-align:left;"> Industrial production in India rose 4.2 percent year-on-year in April 2023, accelerating from an upwardly revised 1.7 percent increase in the previous month and above market expectations of 1.8 percent. Factory activity surged 4.9 percent, after a meager 0.5 percent increase in March. Elsewhere, mining activities increased 5.1 percent while electricity generation fell 1.1 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/pakistan/interest-rate </td>
   <td style="text-align:left;"> 2023-06-12 20:14:00 </td>
   <td style="text-align:left;"> Pakistan Leaves Key Rate Steady at 21% </td>
   <td style="text-align:left;"> The central bank of Pakistan left its key policy interest rate steady at 21% on June 12th 2023, as expected, amid the cash-strapped country's efforts to tame record-high inflation. This marks a massive 1125 bps rise since March 2022. The policymakers highlighted that the inflation rate reached its peak at 38% in May 2023 but a downward trend has been anticipated starting from June onwards. They also added that it is expected that domestic demand will continue to remain subdued amid the tight monetary stance, domestic uncertainty, and ongoing pressure on the external account. Meanwhile, the central bank noted that the current account balance recorded consecutive surpluses in March and April 2023, which alleviated some pressures on foreign exchange reserves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/india-inflation-cools-faster-than-expected-to-4-25-in-may </td>
   <td style="text-align:left;"> 2023-06-12 20:06:36 </td>
   <td style="text-align:left;"> India Inflation Cools Faster Than Expected to 4.25% in May </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.                                                                         , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                                                                                             , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                                                                                                   , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                                                                                          , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                                                                                        , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                                                                                       , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                                                                                       , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                                                                                       , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                               , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                       , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                       , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                                                                                                    , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                                                                                       , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                                                                                                  , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                                                                                                      , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                                                                                         , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                                                                                         , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                                                                                            , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                               , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                                                                                          , Railway Safety Act Should Be Scrapped                                                                                                                                                                                                                                                                 , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                                                                                            , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                                                                                                    , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                                                                                        , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                                                                                            , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                                                                                         , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                                                                                       , Augmented Reality Is Coming for Cities                                                                                                                                                                                                                                                                , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                                                                                           , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                        , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                                                                                           , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                                                                                          , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                                                                                        , Anup Roy                                                                                                                                                                                                                                                                                              , Subscriber Benefit                                                                                                                                                                                                                                                                                    , Subscribe                                                                                                                                                                                                                                                                                             , India’s retail inflation cooled faster-than-expected in May, providing relief to policymakers even as risks from an uneven monsoon remain.                                                                                                                                                            , The consumer price index rose 4.25% from a year earlier, according to data released by the Statistics Ministry on Monday. The reading is lowest since April 2021, and compares with a median forecast for a 4.32% gain in a Bloomberg survey of economists. The inflation print was at 4.70% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/ubs-picks-credit-suisse-s-doshi-to-head-combined-india-business </td>
   <td style="text-align:left;"> 2023-06-12 20:04:11 </td>
   <td style="text-align:left;"> UBS Picks Credit Suisse’s Doshi to Head Combined India Business </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News., Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                    , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                          , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                 , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                               , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                              , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                              , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                              , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                      , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                              , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                              , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                           , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                              , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                         , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                             , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                   , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                      , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                 , Railway Safety Act Should Be Scrapped                                                                                                                                                                                        , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                   , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                           , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                               , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                   , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                              , Augmented Reality Is Coming for Cities                                                                                                                                                                                       , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                  , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                               , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                  , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                 , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                               , Menaka Doshi and                                                                                                                                                                                                             , Preeti Singh                                                                                                                                                                                                                 , Subscriber Benefit                                                                                                                                                                                                           , Subscribe                                                                                                                                                                                                                    , UBS Group AG has picked Credit Suisse Group AG’s India head for the last 17 years to helm the combined businesses of the Swiss lenders in the country as their merger formally closed.                                       , Mihir Doshi, managing director and country chief executive of Credit Suisse since 2006, will take over as the head of the combined business from July 1, a spokesperson for the lender said on Monday.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/12/stocks-making-the-biggest-moves-premarket-ndaq-ilmn-orcl-more.html </td>
   <td style="text-align:left;"> 2023-06-12 19:56:04 </td>
   <td style="text-align:left;"> Stocks making the biggest moves before the bell: Nasdaq, Illumina, Oracle, Carnival &amp; more </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                               , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                 , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                                                                                            , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                       , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                                                                               , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                                                                                , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                                , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                                                                                        , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                  , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                                                                                         , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                                                  , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                           , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , All Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , ETFs                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bonds                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Check out the companies making headlines in premarket trading.                                                                                                                                                                                                                                                                                                                                                                                                                , Nasdaq — The exchange operator's shares dropped 7.7% following the announcement of its deal to buy Adenza, the software firm owned by Thoma Bravo. The deal, valued at around $10.5 billion, would be Nasdaq's largest acquisition as the company sharpens its focus on financial technology and attempts to diversify.                                                                                                                                                       , Illumina — The biotech stock rose 2% in premarket trading after Illumina announced a CEO transition plan on Sunday. CEO Francis deSouza resigned, effective immediately, but will stay on as an advisor through July 31. The move follows pressure from activist investor Carl Icahn.                                                                                                                                                                                         , Nio — Shares popped more than 4% after the Chinese electric car maker said it was cutting prices for its vehicles and ending free battery swaps for new buyers. Last week, Nio also said it was delaying its capital expenditure projects. Nomura assumed coverage of Nio with a neutral rating on Sunday, after previously rating it a buy.                                                                                                                                  , SentinelOne — Shares rose 5.2% following an upgrade to overweight from equal weight by Morgan Stanley, which said the market hasn't correctly priced the stock's inherent asset value. The cybersecurity stock was hit with a salvo of downgrades after it reported weaker-than-expected first-quarter revenue and disappointing current-quarter and full-year guidance on the metric earlier in June.                                                                        , Bill.com — Shares shed 4.8% in the premarket after Morgan Stanley downgraded the expense management platform to equal weight from overweight. The firm said Bill.com has limitations to expansion and could see increased competition.                                                                                                                                                                                                                                        , Oracle — The IT stock added 4.7% in Monday's premarket as investors awaited earnings for the fiscal fourth quarter expected after the bell. Wolfe Research upgraded the stock to outperform from peer perform over the weekend, while Evercore ISI said on Friday that it anticipated a strong quarterly report and positive commentary around the cloud business. Evercore ISI, Barclays and JPMorgan all raised their respective price targets for the stock in recent days., Carnival — The cruise stock popped 5.5% following an upgrade from JPMorgan. The Wall Street firm upgraded shares to overweight, citing continued demand momentum in the cruise industry.                                                                                                                                                                                                                                                                                      , — CNBC's Jesse Pound, Samantha Subin and Michelle Fox contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                              , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/pakistan-pauses-rates-to-prevent-growth-from-declining-further </td>
   <td style="text-align:left;"> 2023-06-12 19:39:18 </td>
   <td style="text-align:left;"> Pakistan Pauses Rates to Prevent Growth From Declining Further </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.                                      , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                                                          , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                                                                , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                                                       , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                                                     , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                                                    , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                                                    , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                                                    , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                            , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                    , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                    , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                                                                 , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                                                    , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                                                               , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                                                                   , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                                                      , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                                                      , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                                                         , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                            , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                                                       , Railway Safety Act Should Be Scrapped                                                                                                                                                                                                                              , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                                                         , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                                                                 , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                                                     , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                                                         , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                                                      , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                                                    , Augmented Reality Is Coming for Cities                                                                                                                                                                                                                             , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                                                        , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                     , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                                                        , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                                                       , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                                                     , The State Bank of Pakistan in Karachi.                                                                                                                                                                                                                             , Ismail Dilawar and                                                                                                                                                                                                                                                 , Faseeh Mangi                                                                                                                                                                                                                                                       , Subscriber Benefit                                                                                                                                                                                                                                                 , Subscribe                                                                                                                                                                                                                                                          , Pakistan’s central bank left interest rates unchanged to stop growth from weakening and rein in inflation as the cash-strapped nation and the International Monetary Fund remain deadlocked over bailout loans.                                                    , The State Bank of Pakistan’s monetary policy committee decided to keep the target rate at a record 21%, a move expected by a majority of the 44 economists surveyed by Bloomberg. Seven forecast a hike of a 100 basis points and one saw a 200 basis points jump.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 19:38:55 </td>
   <td style="text-align:left;"> US Futures Edge Up </td>
   <td style="text-align:left;"> US stock futures rose on Monday, with contracts on the Dow Jones adding 30 points, the S&amp;P 500 up 0.3% and the Nasdaq 0.6% as investors are hopeful that inflationary pressures would show further signs of easing, supporting the case for a pause in the Fed’s interest rate hikes this week. The US inflation rate is forecasted to fall 4.1% in May, the lowest since March 2021, from 4.9% in April while the core gauge may decelerate to 5.2% from 5.5%. Most market participants expect the US central bank to leave interest rates unchanged at the current levels but there is a 30% chance of a rate hike depending on the CPI reading and after surprise moves in Australia and Canada last week. In premarket trading, UBS shares added over 1% after the Swiss bank said it had completed the takeover of Credit Suisse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 19:28:53 </td>
   <td style="text-align:left;"> Italian Bond Yields Narrow Sharply </td>
   <td style="text-align:left;"> The yield on Italy’s 10-year BTP fell toward the 4.05% mark, approaching the two-month low of 4% touched on June 2nd as markets continued to assess the outlook of monetary policy for major central banks ahead of the ECB’s decision this week. The euro’s monetary authority is expected to maintain its tightening campaign with a 25bps rate hike, while investors eagerly await updates regarding the pace of quantitative tightening. Despite the hawkish outlook, Italian government bonds were supported by expectations of robust growth for the domestic economy, which can help reign in the country’s high debt. ISTAT upwardly revised GDP estimates to reflect a 1.3% growth this year and 1.1% in 2024. Bond yields also retreated following the death of coalition member Forza Italia’s leader Berlusconi, triggering a potential restructuring of the Italian government. Hence, the spread between the 10-year BTP and Bund narrowed to 160bps, the least in 13 months, suggesting low credit risk in BTPs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 19:22:33 </td>
   <td style="text-align:left;"> German 10-Year Bond Yield Little Changed ahead CB Decisions </td>
   <td style="text-align:left;"> Germany's 10-year government bond yield was little changed around 2.4%, as investors cautiously await central bank decisions this week. Market participants anticipate the European Central Bank to raise rates to a peak of approximately 3.75% later this year, up from the current 3.25%. Many investors are expecting 25 basis point rate hikes in both this month and the following month. CB President Lagarde recently highlighted that inflation in the Eurozone remains at elevated levels, indicating the need for additional monetary policy tightening. Elsewhere, the Federal Reserve is also scheduled to announce its rate decision next week, while the Reserve Bank of Australia and the Bank of Canada surprised markets with a 25 basis point interest rate increase in their respective recent meetings following a pause. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 19:08:00 </td>
   <td style="text-align:left;"> US Inflation Rate Seen Falling to 4.1% </td>
   <td style="text-align:left;"> The annual inflation rate in the US likely fell to 4.1% in May 2023, the lowest since March 2021, from 4.9% in April and 5% in March, mainly due to lower energy prices. On a monthly basis, the CPI is projected to increase by 0.2%, easing from a 0.4% rise in April. Meanwhile, core inflation is expected to decrease to 5.3% from 5.5%, with the monthly rate projected to remain at 0.4%, the same as in April. The upcoming data precedes the Federal Reserve's interest rate decision on Wednesday and is expected to strengthen the case for a pause in its tightening cycle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/12/business/jpmorgan-settlement-jeffrey-epstein-victims.html </td>
   <td style="text-align:left;"> 2023-06-12 19:07:59 </td>
   <td style="text-align:left;"> JPMorgan Reaches $290 Million Settlement With Epstein’s Victims - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The proposed deal would settle a suit on behalf of victims who were sexually abused by Jeffrey Epstein, over claims the bank ignored warnings about him.                                                                                                                                                                                                                                                                                                                                                             , By Matthew Goldstein                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , JPMorgan Chase reached a tentative settlement with sexual abuse victims of Jeffrey Epstein, the deceased financier, after weeks of embarrassing disclosures about the bank’s longstanding relationship with him, the bank and lawyers for the victims said in a statement on Monday.                                                                                                                                                                                                                                 , David Boies, one of the lead lawyers for the victims, said the bank was prepared to pay $290 million to resolve the lawsuit. The parties initially had agreed not to disclose the settlement amount in their joint statement, as it was set to be included in a court filing within the next week.                                                                                                                                                                                                                   , The proposed deal would settle a lawsuit filed last November in Manhattan federal court by an unidentified woman on behalf of victims who were sexually abused by Mr. Epstein over a roughly 15-year period when they were teenage girls and young women, the suit said. The number of victims could potentially rise to more than 100.                                                                                                                                                                              , In the statement, the bank and the lawyers for the victims said they had reached “an agreement in principle to settle” the lawsuit on behalf of the victims and the “settlement is in the best interests of all parties, especially the survivors who were the victims of Epstein’s terrible abuse.”                                                                                                                                                                                                                 , The settlement agreement was reached roughly two weeks after Jamie Dimon, JPMorgan’s chief executive and one of Wall Street’s best-known bankers, sat for a daylong deposition in which he said he had barely heard of Mr. Epstein before the financier’s July 2019 arrest on federal sex trafficking charges.                                                                                                                                                                                                       , Mr. Epstein killed himself in August 2019 in a Manhattan jail cell a month after his arrest.                                                                                                                                                                                                                                                                                                                                                                                                                         , JPMorgan still faces a related lawsuit by the government of the U.S. Virgin Islands. That suit remains the biggest outstanding Epstein-related case after years of lawsuits against Mr. Epstein’s estate and Ghislaine Maxwell’s conviction in 2021 in Manhattan federal court for helping Mr. Epstein engage in sex trafficking.                                                                                                                                                                                    , The lawsuit filed by the victims claimed that JPMorgan ignored repeated warnings that Mr. Epstein had been trafficking teenage girls and young women for sex, even after he registered as a sex offender and pleaded guilty in a 2008 Florida case to soliciting prostitution from a teenage girl. The complaint said the bank overlooked red flags in Mr. Epstein’s activity because it valued him as a wealthy client who had access to dozens of even wealthier people.                                           , Court documents and deposition testimony reviewed by The New York Times revealed that bank employees had filed numerous suspicious activity reports about Mr. Epstein’s repeated large cash withdrawals. The legal documents revealed that after designating Mr. Epstein a “high risk client” in 2006, the bank kept him on as a customer despite media reports detailing allegations of his sexual abuse of teenage girls and evidence that some of the cash withdrawals were for payments to dozens of young women., JPMorgan had provided banking services for Mr. Epstein from roughly 1998 to 2013 — a period in which the federal authorities and victims have said some of the worst conduct was committed by the financier, who had palatial homes in Manhattan, Florida, the U.S. Virgin Islands, New Mexico and Paris.                                                                                                                                                                                                            , The bank reiterated on Monday what it had said a number of times before about how Mr. Epstein committed “heinous crimes” and “any association with him was a mistake and we regret it.”                                                                                                                                                                                                                                                                                                                              , The same lawyers for Mr. Epstein’s victims last month negotiated a tentative $75 million settlement with Deutsche Bank, which succeeded JPMorgan as Mr. Epstein’s primary banker. Deutsche, which ended its relationship with Mr. Epstein in late 2018, paid a $150 million fine to New York regulators in 2020 over allegations that it failed to sufficiently police its financial dealings with the disgraced financier among other compliance failures.                                                          , The settlements with both banks must be approved by Judge Jed Rakoff of Federal District Court in Manhattan. Judge Rakoff is also presiding over the related lawsuit by the government of the U.S. Virgin Islands.                                                                                                                                                                                                                                                                                                   , The Virgin Islands, the U.S. territory in the Caribbean, contends that JPMorgan should pay it damages for enabling Mr. Epstein to set up a sex trafficking operation on his private island residence off St. Thomas. But JPMorgan, in court papers, has bitterly opposed the lawsuit, arguing that government officials there cozied up to Mr. Epstein for nearly two decades.                                                                                                                                       , Two of Mr. Epstein’s businesses received lucrative tax breaks from the U.S. territory worth tens of millions of dollars. Shortly after JPMorgan ended its relationship with Mr. Epstein, the Virgin Islands approved a first-of-its-kind boutique banking license for Mr. Epstein.                                                                                                                                                                                                                                   , Judge Rakoff had put the lawsuits against JPMorgan on a fast track, with more than a dozen depositions given over the past three months, including the one from Mr. Dimon and another from Albert Bryan Jr., the governor of the Virgin Islands. The deal between JPMorgan and Mr. Epstein’s victims was hammered out as some of the plaintiffs’ lawyers were taking the deposition of James E. Staley, the former JPMorgan executive who had close ties to Mr. Epstein.                                             , In court filings, the Virgin Islands claimed Mr. Epstein and Mr. Staley shared sexually suggestive emails about young women.                                                                                                                                                                                                                                                                                                                                                                                         , Mr. Staley, better known as Jes, has in court papers repeatedly denied doing anything wrong or being aware that Mr. Epstein had sexually abused young women and teenage girls. JPMorgan then sued Mr. Staley seeking to ensure that, if it is determined that he did engage in improper activity, he can be held liable for damages the bank ends up paying.                                                                                                                                                         , The victims’ lawyers who were most involved in litigating and negotiating the proposed settlements with the two banks included Mr. Boies, Sigrid McCawley, Brad Edwards and Brittany Henderson.                                                                                                                                                                                                                                                                                                                      , Mr. Boies said of the proposed settlement with JPMorgan, “It has taken a long time, too long, but today is a great day for Jeffrey Epstein survivors.” Mr. Edwards said the deal goes along way to bringing “full justice” to Mr. Epstein’s many victims.                                                                                                                                                                                                                                                            , “The settlements signal that financial institutions have an important role to play in spotting and shutting down sex trafficking,” said Ms. McCawley, who argued before Judge Rakoff that the JPMorgan lawsuit should be treated as a class-action suit Judge Rakoff approved the class-action status in a ruling on Monday.                                                                                                                                                                                         , In court papers associated with the proposed settlement with Deutsche Bank, the victims’ lawyers said they expected to seek fees of up to 30 percent. The lawyers are likely to submit a similar fee request in the JPMorgan litigation. Any fee request must be approved by Judge Rakoff.                                                                                                                                                                                                                           , In the Deutsche settlement, the victims will each be entitled to receive anywhere from $75,000 to $5 million in restitution, according to court filings.                                                                                                                                                                                                                                                                                                                                                             , The settlements with the two banks will add to the total relief that the many victims of Mr. Epstein have received in recent years. Mr. Epstein’s estate has paid out about $150 million in restitution to more than 125 victims — many of whom may be eligible to apply for additional compensation from the deals with Deutsche and JPMorgan.                                                                                                                                                                      , The Virgin Islands, which last year secured a $105 million settlement from Mr. Epstein’s estate, said in a statement that it would “continue to proceed with its enforcement action to ensure full accountability for JPMorgan’s violations of law.”                                                                                                                                                                                                                                                                 , And on Monday, the Virgin Islands filed a new round of court papers that included emails from JPMorgan employees, in which several argued as far back as 2008 that he should not be retained as customer.                                                                                                                                                                                                                                                                                                            , In July 2011, Stephen Cutler, the bank’s general counsel at the time, wrote an email to Mr. Staley and others at JPMorgan: “This is not an honorable person in any way. He should not be a client.”                                                                                                                                                                                                                                                                                                                  , Matthew Goldstein covers Wall Street and white-collar crime and housing issues.  @mattgoldstein26                                                                                                                                                                                                                                                                                                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2023-06-12 19:02:00 </td>
   <td style="text-align:left;"> Turkish Lira Continues to Depreciate Against the Greenback </td>
   <td style="text-align:left;"> The Turkish lira continued to weaken to a new record low of 23.7 per USD, extending the monthly loss to 14%, and bringing the total depreciation to about 18% since the runoff election on May 28th despite signals from President Tayyip Erdogan indicating his willingness to move away from unorthodox economic policies, with assignments of  Hafize Gaye Erkan, a former Wall Street banker, as the head of Turkey's central bank, and ex-Merrill Lynch strategist Mehmet Simsek as the new Treasury and Finance Minister. Investors also weigh on the unexpected widening of April's current account deficit that highlights the challenge facing the government, with causing official reserves to be mostly utilized for its financing. Meanwhile, in early June, analysts at Goldman Sachs Group Inc. also revised their lira forecast, projecting a depreciation to 28 per dollar within 12 months, as compared to their previous forecast of 22. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/senegal/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 18:57:55 </td>
   <td style="text-align:left;"> Senegal Inflation Rate Softens to 1-Year Low of 8.3% </td>
   <td style="text-align:left;"> The annual inflation rate in Senegal eased further to hit a one-year low of 8.3% in May 2023, down from 9% in the prior month, mainly due to a slowdown in prices of food &amp; non-alcoholic beverages (10.4% vs 11.5% in April). Softer increases were also observed for other CPI items, such as restaurants &amp; hotels (7.9% vs 8.1%); communication (7.3% vs 8.5%); housing &amp; utilities (5.1% vs 5.9%); clothing &amp; footwear (4.6% vs 5.1%), among others. On a monthly basis, consumer prices were up 0.1% in May, after increasing by 0.5% in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-12/devaluation-in-nigeria-s-naira-in-focus-after-emefiele-ousted </td>
   <td style="text-align:left;"> 2023-06-12 18:56:11 </td>
   <td style="text-align:left;"> Investors Eye Nigeria Devaluation as Central Bank Chief Ejected </td>
   <td style="text-align:left;"> Bloomberg Markets European Close. Live from New York and London, analyzing the major market moving stories across the day in Europe, hear from the biggest newsmakers and showcase the unrivaled expertise of Bloomberg News.                                                                                                                             , Bloomberg Markets live from New York, focused on bringing you the most important global business and breaking markets news and information as it happens.                                                                                                                                                                                                 , Accelerate is an in-depth exploration of the science, ethos and implications of near-future transportation methods.                                                                                                                                                                                                                                       , EasyJet Scrapped 100 Flights at Gatwick Due to Thunderstorms                                                                                                                                                                                                                                                                                              , Goldman CEO Says Rates Could Head Higher on Stickier Inflation                                                                                                                                                                                                                                                                                            , Near-Term Inflation Expectations Hit Two-Year Low in Fed Survey                                                                                                                                                                                                                                                                                           , US Food Prices Are Still Up 8.2% Online Even as Inflation Cools                                                                                                                                                                                                                                                                                           , Fed Backs Away From Wages Focus, Bolstering Case for Rate Pause                                                                                                                                                                                                                                                                                           , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                                                                                   , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                                                                           , Tesla Chargers Win More Backers as Its Plug Becomes US Standard                                                                                                                                                                                                                                                                                           , War in Ukraine Prompts Increased Cyberattacks on German Businesses                                                                                                                                                                                                                                                                                        , Reddit Blackout Begins as Forums Protest Charges for Developers                                                                                                                                                                                                                                                                                           , Biden to Undergo Root Canal at White House on Monday                                                                                                                                                                                                                                                                                                      , Romanian Premier Quits to Hand Power to Ally in Pre-Agreed Shift                                                                                                                                                                                                                                                                                          , Mary Erdoes, JPMorgan’s Billionaire Whisperer, Faces Flak Over Epstein Emails                                                                                                                                                                                                                                                                             , Why Billionaires Are Circling Debt-Laden French Grocer Casino                                                                                                                                                                                                                                                                                             , Berlusconi’s Death Set to Reshape Media, Political Empires                                                                                                                                                                                                                                                                                                , Hotelier Ian Schrager Aspires to Be More Like Apple Instead of Marriott                                                                                                                                                                                                                                                                                   , How Trump’s Indictment Compares to Other Espionage Act Cases                                                                                                                                                                                                                                                                                              , Railway Safety Act Should Be Scrapped                                                                                                                                                                                                                                                                                                                     , Fentanyl and Politics Are Toxic 2024 Mix for US and Mexico                                                                                                                                                                                                                                                                                                , Google CEO Vows Not to Rush AI and Says Efficiency Drive Continues                                                                                                                                                                                                                                                                                        , China’s Plane Shortage Is Good News For Boeing                                                                                                                                                                                                                                                                                                            , Illumina’s Sudden CEO Exit Is Just One of Many Problems Facing DNA Company                                                                                                                                                                                                                                                                                , Solar Power Provider Seeks $100 Million for Nigeria Expansion                                                                                                                                                                                                                                                                                             , US, Canada Cities Risk Smoke as Fires Still Burn: Weather Watch                                                                                                                                                                                                                                                                                           , Augmented Reality Is Coming for Cities                                                                                                                                                                                                                                                                                                                    , A Sherbet-Colored Experiment in Cohousing Outside of Boston                                                                                                                                                                                                                                                                                               , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                            , Novogratz Firm Galaxy Wins Dismissal of BitGo Suit Over M&amp;A Termination Fee                                                                                                                                                                                                                                                                               , Sam Bankman-Fried’s Risky Japan Trade Seeded a Crypto Empire                                                                                                                                                                                                                                                                                              , Crypto Resumes Drop After SEC Crackdown Led to Weekend Selloff                                                                                                                                                                                                                                                                                            , Colleen Goko                                                                                                                                                                                                                                                                                                                                              , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                        , Subscribe                                                                                                                                                                                                                                                                                                                                                 , Emerging-market investors are looking at a devaluation of Nigeria’s naira after the suspension of the country’s central bank governor Godwin Emefiele.                                                                                                                                                                                                    , Analysts are considering how soon a devaluation may happen and how deep it will be, following the removal late Friday of a policy chief whose unorthodox policies included propping up the naira and banning access to foreign exchange for imports. The currency steadied Monday at 471.80 per dollar, having fallen for three weeks to hit a record low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 18:44:05 </td>
   <td style="text-align:left;"> Indian Shares Edge Higher Ahead of RPI </td>
   <td style="text-align:left;"> The BSE Sensex closed marginally higher at 62,725 on Monday, extending the marginal gain from the prior week with support from the tech sector as investors awaited key inflation data due after the closing bell. Markets forecasted retail prices to have risen by 4.42% annually in May, which would mark a fourth consecutive slowdown at levels well below the RBI’s upper target of 6%. A cool reading will strengthen hopes that the RBI will ease off its recent hawkish rhetoric, further supporting the momentum for Indian equities. The technology sector led the gains on the corporate front, with HCL Technologies and Infosys adding more than 2%, while TCS and Tech Mahindra advanced 1% each. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/12/hsbc-builds-innovation-division-from-the-bones-of-collapsed-svb-uk.html </td>
   <td style="text-align:left;"> 2023-06-12 18:40:59 </td>
   <td style="text-align:left;"> HSBC builds innovation division from the bones of collapsed SVB UK </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                            , Loans                                                                                                                                                                                                                                                                                                   , Banking                                                                                                                                                                                                                                                                                                 , Mortgages                                                                                                                                                                                                                                                                                               , Insurance                                                                                                                                                                                                                                                                                               , Credit Monitoring                                                                                                                                                                                                                                                                                       , Personal Finance                                                                                                                                                                                                                                                                                        , Small Business                                                                                                                                                                                                                                                                                          , Taxes                                                                                                                                                                                                                                                                                                   , Help for Low Credit Scores                                                                                                                                                                                                                                                                              , Investing                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                  , All Credit Cards                                                                                                                                                                                                                                                                                        , Find the Credit Card for You                                                                                                                                                                                                                                                                            , Best Credit Cards                                                                                                                                                                                                                                                                                       , Best Rewards Credit Cards                                                                                                                                                                                                                                                                               , Best Travel Credit Cards                                                                                                                                                                                                                                                                                , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                      , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                             , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                        , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                       , SELECT                                                                                                                                                                                                                                                                                                  , All Loans                                                                                                                                                                                                                                                                                               , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                     , Best Personal Loans                                                                                                                                                                                                                                                                                     , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                           , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                , Best Loans with Fast Funding                                                                                                                                                                                                                                                                            , Best Small Personal Loans                                                                                                                                                                                                                                                                               , Best Large Personal Loans                                                                                                                                                                                                                                                                               , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                     , Best Student Loan Refinance                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                  , All Banking                                                                                                                                                                                                                                                                                             , Find the Savings Account for You                                                                                                                                                                                                                                                                        , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                        , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                          , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                         , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                           , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                      , Best Checking Account Bonuses                                                                                                                                                                                                                                                                           , Best Money Market Accounts                                                                                                                                                                                                                                                                              , Best CDs                                                                                                                                                                                                                                                                                                , Best Credit Unions                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                  , All Mortgages                                                                                                                                                                                                                                                                                           , Best Mortgages                                                                                                                                                                                                                                                                                          , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                   , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                      , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                  , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                 , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                               , Affording a Mortgage                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                  , All Insurance                                                                                                                                                                                                                                                                                           , Best Life Insurance                                                                                                                                                                                                                                                                                     , Best Homeowners Insurance                                                                                                                                                                                                                                                                               , Best Renters Insurance                                                                                                                                                                                                                                                                                  , Best Car Insurance                                                                                                                                                                                                                                                                                      , Travel Insurance                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                  , All Credit Monitoring                                                                                                                                                                                                                                                                                   , Best Credit Monitoring Services                                                                                                                                                                                                                                                                         , Best Identity Theft Protection                                                                                                                                                                                                                                                                          , How to Boost Your Credit Score                                                                                                                                                                                                                                                                          , Credit Repair Services                                                                                                                                                                                                                                                                                  , SELECT                                                                                                                                                                                                                                                                                                  , All Personal Finance                                                                                                                                                                                                                                                                                    , Best Budgeting Apps                                                                                                                                                                                                                                                                                     , Best Expense Tracker Apps                                                                                                                                                                                                                                                                               , Best Money Transfer Apps                                                                                                                                                                                                                                                                                , Best Resale Apps and Sites                                                                                                                                                                                                                                                                              , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                           , Best Debt Relief                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                  , All Small Business                                                                                                                                                                                                                                                                                      , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                    , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                   , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                    , Best Small Business Loans                                                                                                                                                                                                                                                                               , Best Tax Software for Small Business                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                  , All Taxes                                                                                                                                                                                                                                                                                               , Best Tax Software                                                                                                                                                                                                                                                                                       , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                  , Tax Refunds                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                  , All Help for Low Credit Scores                                                                                                                                                                                                                                                                          , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                        , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                      , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                            , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                 , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                   , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                            , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                            , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                           , Best Hardship Loans                                                                                                                                                                                                                                                                                     , How to Boost Your Credit Score                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                  , All Investing                                                                                                                                                                                                                                                                                           , Best IRA Accounts                                                                                                                                                                                                                                                                                       , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                  , Best Investing Apps                                                                                                                                                                                                                                                                                     , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                       , Best Robo-Advisors                                                                                                                                                                                                                                                                                      , Index Funds                                                                                                                                                                                                                                                                                             , Mutual Funds                                                                                                                                                                                                                                                                                            , ETFs                                                                                                                                                                                                                                                                                                    , Bonds                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                         , U.K. banking titan HSBC unveiled a new HSBC Innovation Banking unit Monday, as it seeks to push into the technology sector following its eleventh-hour rescue of the U.K. subsidiary of failed Silicon Valley Bank (SVB) in March.                                                                      , HSBC acquired the London-based SVB unit for £1 after its parent company suffered a run on its assets fueled by customer fears over the bank's solvency. SVB was one of several U.S. and European lenders that met their downfall earlier this year as broader turmoil rattled the global banking sector., The U.K. government and Bank of England facilitated the purchase in a bid to protect deposits, as Britain separately struggles to retain its position as an international tech capital.                                                                                                                 , Some have questioned whether traditional financial institution HSBC is well placed to take over the legacy of SVB and finance tech-focused startups and small businesses.                                                                                                                               , The criticism was shot down last week by HSBC UK CEO Ian Stuart, who told CNBC's Arjun Kharpal that the bank would take its activity "from seed funding all the way through to IPO, customers will never have to go outside of that network to meet their funding requirements."                        , HSBC said Monday that its Innovation Banking unit, launched at London Tech Week, will bring together SVB UK and freshly formed teams in the U.S., Israel and Hong Kong as it focuses on tech and life science enterprises.                                                                              , "The UK's world-leading technology and life sciences sectors are central to growing the UK economy and boosting global exports," HSBC Group Chief Executive Noel Quinn said in a Monday statement.                                                                                                      , "HSBC now has a world-class team focused on innovation companies, their founders and their investors. We will protect this specialisms and take it to the next level."                                                                                                                                  , British Prime Minister Rishi Sunak said that the new HSBC division will assist innovative businesses and create additional jobs, "supporting my priority to grow the UK economy and cement our position as a science and tech superpower."                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                        , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2023-06-12 18:40:00 </td>
   <td style="text-align:left;"> South African Rand at Over 1-Month High </td>
   <td style="text-align:left;"> The South African rand was trading around 18.5 per USD, its highest since May 8th, boosted by encouraging domestic economic data and amid easing concerns over load-shedding. The latest GDP figures showed that South Africa's economy had narrowly avoided a recession in the first quarter and central bank data indicated the current account deficit narrowed more than expected in the same period. Meanwhile, June has surprised with load shedding being suspended for more than half the day and kept to lower stages at night, against expectations it could get worse. The higher availability of electricity has been attributed to improved maintenance at Eskom's power plants and increased diesel supply at the open-cycle gas turbines that are used for emergency supply during periods of high demand, as well as higher tariffs that have cut demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/serbia/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 18:34:22 </td>
   <td style="text-align:left;"> Serbia Inflation Eases Further from March Peak </td>
   <td style="text-align:left;"> The annual inflation rate in Serbia stood at 14.8% in May 2023, following 15.1% in April and easing from a record high of 16.2% in March. Still, the reading came above the market estimates of 14.3% due to accelerated price growth in food &amp; non-alcoholic beverages (23.2% vs 23.1% in the previous month) and housing &amp; utilities (23.5% vs 21.6%). On the other hand, the cost slowed for communications (1.7% vs 1.9%), health (7.8% vs 8.5%), miscellaneous goods &amp; services (14.9% vs 15.1%), and furnishings, household equipment &amp; routine household maintenance (18.1% vs 18.9%). Prices also fell for transport (-0.6 vs 3.7%). Monthly, consumer inflation accelerated to 0.9% from 0.7% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 18:01:00 </td>
   <td style="text-align:left;"> US 10-Year Treasury Yield Little Changed </td>
   <td style="text-align:left;"> The yield on the US 10-year Treasury note edged up to 3.73%, as investors await the Federal Reserve's announcement on Wednesday. Most market participants expect the US central bank to leave interest rates unchanged at the current levels but there is a chance of a rate hike depending on the CPI reading and after surprise moves in Australia and Canada last week. The US inflation rate is forecasted to fall 4.1% in May, the lowest since March 2021, from 4.9% in April while the core gauge may decelerate to 5.2% from 5.5%. Meanwhile, the ECB is expected to raise rates by 25 basis points on Thursday, after a surprise hawkish move from both the Bank of Canada and the Reserve Bank of Australia last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lithium </td>
   <td style="text-align:left;"> 2023-06-12 17:59:41 </td>
   <td style="text-align:left;"> Lithium Extends Rebound to 3-Month High </td>
   <td style="text-align:left;"> Lithium carbonate prices rose above the CNY 315,000 per tonne level in June, the highest in three months to extend the rebound from the 19-month low of CNY 165,500 at the end of April amid robust demand for battery inputs. The latest data showed that NEV sales in China jumped by 60% year-on-year in May, extending the 110% surge in April and marking nearly one-third of the market share, erasing concerns about poor demand levels at the start of the year. During the first quarter, the drop in demand coincided with a significant oversupply of batteries. Producers took advantage of final inflows of government subsidies and ramped up production until the end of 2022, creating unsustainably high inventory levels. Robust expectations for longer-term demand also supported lithium prices, as government incentives to switch to EVs lead analysts to forecast that lithium demand by 2040 will be 16 times higher than present-day levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 17:38:00 </td>
   <td style="text-align:left;"> Turkish Stocks Hit Record High </td>
   <td style="text-align:left;"> The Borsa Istanbul 100 index reached an all-time high of 5,700 in June and surged nearly 20% since the runoff election, as investors continued to show optimism after the appointments of Hafize Gaye Erkan, a former US-based banking executive, as the head of Turkey's central bank, and market-friendly policy maker Mehmet Simsek as the new Treasury and Finance Minister. These assignments signal President Erdogan's shift from unorthodox economic policies that had resulted in high inflation, low interest rates, a plummeting lira, and negative net foreign exchange reserves. Despite inflation reaching a 24-year high of 85% in October last year, the central bank has reduced its key policy rate from approximately 19% in 2021 to 8.5% in 2023. The official inflation rate eased to 39.5% in May, but some academics estimate it to be more than double the figure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-12 17:37:23 </td>
   <td style="text-align:left;"> Croatia Producer Inflation Sharply Down </td>
   <td style="text-align:left;"> Producer inflation in Croatia eased sharply to 2.5 percent year-on-year in May 2023 from 6.5 percent in the previous month, marking the lowest reading since February 2021, as cost slowed significantly for electricity, gas, steam, &amp; air conditioning supply (20.3 percent vs 30.8 percent in April). Prices also grew at a softer pace for manufacturing (0.9 percent vs 4.2 percent) and water supply, sewerage, waste management, &amp; remediation activities (1.2 percent vs 1.3 percent) while continuing to decline for mining &amp; quarrying (-32.9 percent vs -26.6 percent). On a monthly basis, producer prices plunged by 1.4 percent in May, deepening a prior 0.9 percent drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/steel </td>
   <td style="text-align:left;"> 2023-06-12 17:34:27 </td>
   <td style="text-align:left;"> Steel Halts Rally on Demand Concerns </td>
   <td style="text-align:left;"> Steel rebar futures fell to CNY 3,690 per tonne, edging lower from the seven-week high of CNY 3,710 touched on June 9th as markets continued to weigh on concerning data from China’s essential property market against hopes of consequent stimulus rollouts from the country’s government. Goldman Sachs issued a warning that weakness in China’s real estate market is likely to remain in the coming years, adding that the government will attempt to reduce economic and fiscal reliance on construction activity and refrain from granting property-specific stimulus. The forecast follows a note from Citigroup stating that steel demand in China is unlikely to rebound on the back of weak construction activity. The underwhelming recovery since the country’s reopening from lockdowns drove Beijing to consider capping crude steel output at 2.5% below the prior year’s level in 2023, supporting prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kosovo/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 17:12:39 </td>
   <td style="text-align:left;"> Kosovo Inflation Lowest in Over 1-1/2 Year </td>
   <td style="text-align:left;"> Kosovo's annual inflation rate eased for the fifth month to 5.5% in May 2023 from 6.3% in April, marking the lowest reading since September 2021. Prices grew at a slower pace for food &amp; non-alcoholic beverages (9.4% vs 10.6% in the previous period) and restaurants &amp; hotels (6.8% vs 7.2%) while decreasing for transport (-4.4% vs -0.5%), primarily fuels &amp; lubricants for personal transport equipment (-1.2 %), and communication (-0.6% vs -0.7%). Monthly, consumer inflation stood at 0.1% in May, down from 0.3% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/12/business/wework-softbank-sandeep-mathrani.html </td>
   <td style="text-align:left;"> 2023-06-12 17:01:09 </td>
   <td style="text-align:left;"> WeWork Faces More Turmoil After Its CEO Departs - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The company’s top boss, a real estate industry veteran, abruptly left in May after growing frustrated with SoftBank, its largest shareholder and lender.                                                                                                                                                                                                                                                                                                                                        , By Maureen Farrell and Peter Eavis                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Sandeep Mathrani was supposed to be WeWork’s savior.                                                                                                                                                                                                                                                                                                                                                                                                                                            , A real estate executive, he became the chief executive of the troubled office space company in 2020 after a failed initial public offering pushed it to the brink of collapse. He instilled discipline and order on a business that had grown fast and chaotically under its co-founder Adam Neumann.                                                                                                                                                                                           , Instead of building a company that would “elevate the world’s consciousness” as Mr. Neumann had wanted, Mr. Mathrani focused on the staid details of running a real estate company. He steered WeWork through the pandemic, got its landlords to accept less rent, took the company public and oversaw a financial restructuring, completed last month, that cut the company’s debt.                                                                                                            , But just weeks after the restructuring, the company said on May 16 that Mr. Mathrani would step down, and that no permanent successor was lined up. Wall Street analysts who had recently met with him were stunned — one analyst wrote in a research note that the executive was “abandoning ship.” A couple of weeks later, WeWork’s chief financial officer, who had joined last June, departed, too.                                                                                        , The turmoil raises fresh questions about the viability of WeWork, which has spent billions of dollars building a business that has never come close to breaking even — and must now compete with the flood of cheap office deals that have become available since working from home shrank demand for commercial real estate.                                                                                                                                                                   , Investors have all but given up on a WeWork turnaround. The stock is trading around 20 cents, down more than 95 percent from October 2021 when it secured a stock market listing through a merger.                                                                                                                                                                                                                                                                                              , “We still believe that the current capital structure remains unsustainable,” said Pranav Khattar, a primary credit analyst at S&amp;P Global Ratings.                                                                                                                                                                                                                                                                                                                                               , To a large extent, the company’s fate rests with SoftBank, the Japanese conglomerate that has invested nearly $12 billion in WeWork and is its largest shareholder. SoftBank has also lent the company hundreds of millions of dollars, and took a haircut on its WeWork debt in last month’s restructuring.                                                                                                                                                                                    , By reducing WeWork’s debt by $1.4 billion overall and pushing out the repayment of its remaining debt, the restructuring gave WeWork more time to try to build a sustainable business. But the company is still burning through large amounts of cash each quarter and may be forced to shrink substantially, perhaps through bankruptcy.                                                                                                                                                       , Office landlords are watching the company with dread.                                                                                                                                                                                                                                                                                                                                                                                                                                           , A collapse of WeWork could be a “systematic shock” to the weak commercial real estate sector in New York, San Francisco and other cities, said Stijn Van Nieuwerburgh, a Columbia Business School professor who specializes in real estate.                                                                                                                                                                                                                                                     , “It would pour more cold water on the office market, which is struggling direly,” he said, noting that WeWork rents nearly 20 million square feet of office space, more than any other company in the United States.                                                                                                                                                                                                                                                                            , Until recently, Mr. Mathrani appeared committed to turning WeWork around. But he had grown exhausted by the challenges of the business and was frustrated by what he perceived as a lack of engagement from SoftBank, according to four people familiar with his leadership who spoke on the condition of anonymity. He told colleagues that he was particularly annoyed that it did not move more quickly to wrap up the debt restructuring, three people familiar with his conversations said., The transaction could not be done quickly because it was complex and required sign-off by numerous parties, according to a person familiar with SoftBank’s thinking.                                                                                                                                                                                                                                                                                                                            , Mr. Mathrani declined to comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , As WeWork and SoftBank discussed a restructuring, other parties suggested deals aimed at steadying the company.                                                                                                                                                                                                                                                                                                                                                                                 , Last fall, Mr. Neumann, the co-founder, who holds a small stake in the company, started telling friends and associates that he was thinking about getting involved in WeWork again and buying back some of its stock, according to three people familiar with his conversations. He scheduled a meeting with Mr. Mathrani in October to discuss a large investment and other strategic initiatives that could bolster the company, four people familiar with the plans said.                    , Mr. Neumann had recently landed a $350 million investment from the venture capital firm Andreessen Horowitz for his new real estate venture called Flow. He and other investors were considering an investment in WeWork of up to $1 billion, some of which could have been used to buy back some of the company’s debt, two of the people said.                                                                                                                                                , Mr. Mathrani canceled the meeting and did not reschedule it, the three people said. The two men never met to discuss Mr. Neumann’s proposal, and it is not clear why Mr. Mathrani was not interested.                                                                                                                                                                                                                                                                                           , Mr. Mathrani opted to negotiate the debt restructuring with SoftBank and other investors allied with the Japanese company. But he and SoftBank executives struggled to get the attention of SoftBank’s chief executive, Masayoshi Son, to secure his approval for the debt deal.                                                                                                                                                                                                                , By March, as negotiations over the deal dragged on, Mr. Mathrani increasingly felt that Softbank’s influence over the company hampered his ability to make key decisions, three people familiar with the matter said.                                                                                                                                                                                                                                                                           , In the spring, as WeWork’s stock tumbled, he approached SoftBank with offers from other companies that were interested in striking deals with WeWork. The co-working company IWG discussed a deal to operate WeWork’s locations in return for a fee, and JLL, one of the world’s largest commercial real estate brokers, was in talks about a potential operating agreement with WeWork, according to two people familiar with the conversations.                                               , SoftBank was not interested. JLL and IWG declined to comment.                                                                                                                                                                                                                                                                                                                                                                                                                                   , WeWork has made some progress under Mr. Mathrani. The company has lowered its costs by negotiating lower rents from landlords and closing some locations. A recent WeWork securities filing said that, since 2019, it had saved nearly $12 billion by terminating and amending hundreds of leases.                                                                                                                                                                                              , But the company fell far short of some goals Mr. Mathrani had set. In August 2021, the company projected it would bring in $4.3 billion of revenue in 2022; it ended up reporting $1 billion less than that.                                                                                                                                                                                                                                                                                    , And the company’s costs may still be too high given the weak demand for office space. It had 614 locations at the end of March, down from around 715 at the end of 2020.                                                                                                                                                                                                                                                                                                                        , Mr. Mathrani and office landlords had failed to fully appreciate the transformation of office work during and after the pandemic. With fewer people coming into the office five days a week, many employers decided they no longer needed to maintain expensive office space.                                                                                                                                                                                                                   , One big challenge is that WeWork is competing with a huge amount of office space that employers no longer need and are seeking to lease out to others. “There’s no question that WeWork is more expensive than a well-priced sublet,” said Ruth Colp-Haber, chief executive of Wharton Property Advisors, a New York office space broker.                                                                                                                                                       , She said a 5,000-square-foot office — big enough for 20 people — in a second-tier building in Manhattan could be had for about $12,500 a month on the sublet market. A similar amount of space in a comparable WeWork facility would probably cost about $16,000 a month, Ms. Colp-Haber said, acknowledging that WeWork offers tenants more flexibility over how long they want to be in a space.                                                                                              , A WeWork representative said subleasing involved significant costs and inconveniences that could make using a WeWork space more attractive.                                                                                                                                                                                                                                                                                                                                                     , Even before the recent downturn in demand for office space, WeWork’s business model always rested on a shaky premise.                                                                                                                                                                                                                                                                                                                                                                           , Founded by Mr. Neumann and Miguel McKelvey in 2010 in the wake of the financial crisis, WeWork signed long-term leases for floors in office buildings or entire buildings. The company refurbished those spaces and rented them out to freelancers, start-ups and large corporations. The idea was that WeWork could generate more in rental income than it was paying landlords by offering shorter leases, well-designed spaces and perks like happy hours.                                   , The model never really worked on a large scale. At most locations, costs greatly outpaced revenue. WeWork grew fast, doubling its revenue most years since it was founded, but it also more than doubled its losses. When the company sought to go public in 2019, investors balked.                                                                                                                                                                                                            , WeWork withdrew its I.P.O. in September 2019, and Mr. Neumann resigned as chief executive. Since then, he has received more than $700 million from selling stock to SoftBank and from cash payments.                                                                                                                                                                                                                                                                                            , Two people familiar with the matter said Mr. Neumann had moved on and was no longer interested in investing in WeWork. In a recent financial filing, SoftBank disclosed that it had so far taken more than $10 billion of losses on its investments in WeWork.                                                                                                                                                                                                                                  , Maureen Farrell is a business reporter, covering a wide-ranging beat that includes private equity, hedge funds and billionaires.  @maureenmfarrell                                                                                                                                                                                                                                                                                                                                              , Peter Eavis is a New York-based reporter covering companies and markets. Before coming to The Times in 2012, he worked at The Wall Street Journal.  @PeterJEavis                                                                                                                                                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 16:55:00 </td>
   <td style="text-align:left;"> South African Stocks Edge Higher </td>
   <td style="text-align:left;"> The JSE FTSE All Share index was slightly higher around 77,090 on Monday, in cautious trading, as global investors eagerly awaited the release of U.S. inflation data and the Federal Reserve’s decision on interest rates. Although the Federal Reserve is widely anticipated to keep interest rates unchanged, some concerns persist that the decision to hold rates steady is merely a temporary pause by the Fed, rather than a permanent end to tightening. On the corporate front, gains in heavyweight tech companies and industrials were offset by losses in resource-linked sectors and financials. Meanwhile, South African thermal coal exporter Thungela Resources said in a trading update it expects its half-year profit to fall by as much as 75% on weaker coal prices, higher costs and persistent rail logistics problems. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 16:55:00 </td>
   <td style="text-align:left;"> Turkey 10-Year Bond Yield Hits 16.1% </td>
   <td style="text-align:left;"> Turkey's 10-year government bond yield was around 16.1% in June, its highest level since August 2022, led by investors' growing expectations that Turkey's monetary policy will normalize after years of ultra-low borrowing costs and climbing inflation. The optimistic mood is attributed to the assignment of Hafize Gaye Erkan, a former US-based banking executive, as the head of Turkey's central bank and Mehmet Simsek as the new Treasury and Finance Minister. Over the past few years, Turkey has experienced a significant outflow of billions of dollars from its bond and stock markets, coupled with nearly 85% inflation, due to President Erdogan's unorthodox economic policies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2023-06-12 16:43:04 </td>
   <td style="text-align:left;"> UK Natural Gas Prices Fall from 1-Month High </td>
   <td style="text-align:left;"> UK natural gas futures fell to 73.6 pence per therm from a 1-month high hit above 80 last week, as investors evaluate the balance between reduced demand and potential supply risks. US gas shipments to Europe have decreased as the focus shifts towards the more competitive Asian market, which experiences higher demand for cooling during the summer. Additionally, Norway's Equinor has postponed the restart of its Hammerfest Arctic LNG plant by one week to June 14 due to technical difficulties. On the demand side, the UK's National Gas Transmission projects a decline in natural gas demand to 33.25 billion cubic meters during the summer, compared to 42.08 billion cubic meters in the same period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 16:35:07 </td>
   <td style="text-align:left;"> Spain Stocks Approach 9400 </td>
   <td style="text-align:left;"> The IBEX 35 rose to 9,380 on Monday, reversing the previous drop and following its European peers thanks to a nearly 7% surge in Solaria shares. The company gained on improved recommendation from RBS analysts and increased appetite for renewables after the takeover of the Antin fund for Opdenergy. The other protagonists included Acciona Energia (2.2%), Inditex (1.4%), and Sacyr (1.3%), with the latter announcing the sale of its waste management unit Valoriza Servicios Medioambientales to Morgan Stanley Infrastructure Partners. Iberdrola also advanced 0.8% due to the agreement with Mexico Infrastructure Partners to divest 80% of its business in the country. Meanwhile, Repsol and Endesa underperformed, falling around 0.6% each. Further movements in the index were limited in anticipation of central banks meetings this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 16:30:00 </td>
   <td style="text-align:left;"> Hang Seng Muted at Close </td>
   <td style="text-align:left;"> The Hang Seng was up 14.36 points or less than 0.1% to end at 19,404.31 on Monday, trying to maintain gains for the fourth straight session, as traders braced for interest rate decisions from major central banks this week. Meanwhile, US stock futures were notably higher amid speculation that the Federal Reserve could deliver one more rate hike next month rather than this Wednesday. Separately, Bloomberg Economics forecast that the PBoC may cut its medium-term lending facility on Thursday. Investors continued to follow reports about the COVID positivity rate in China approaching its early January peak last month amid growing mobility caused by Beijing's lift of all pandemic restrictions. The tech and financials mainly went up while consumers were muted and property fell. Among top performers of the day were AIM VAccine (4.7%), Xinyl Solar Hlds. (3.1%), Want Want China (2%), Yadea Group (1.6%), and AIA Group (1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2023-06-12 16:30:00 </td>
   <td style="text-align:left;"> WTI Crude Oil Extends Losses for 3rd Day </td>
   <td style="text-align:left;"> WTI crude futures fell 4% to nearly $67 per barrel on Monday, as concerns about weakening demand in top consumer China and rising Russian crude supply outweighed Saudi Arabia's plans to slash output. Russian oil exports to China and India rose to record levels in May even after the implementation of the European Union’s embargo and the Group of Seven’s price cap mechanism that started in early December. On the other hand, Saudi Arabia, the world's largest oil exporter, announced earlier this month its intention to reduce output by 1 million barrels per day to 9 million bpd in July, the lowest level in years amid an effort to bolster crude prices. Meanwhile, investors are cautious ahead of a busy week ahead with the US inflation rate and interest rate decisions from the Federal Reserve, the ECB and the BoJ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palm-oil </td>
   <td style="text-align:left;"> 2023-06-12 16:24:00 </td>
   <td style="text-align:left;"> Palm Oil Approaches 2-Year Low </td>
   <td style="text-align:left;"> Malaysian palm oil futures fell to below MYR 3,320 per tonne, approaching the two-and-a-half-year low of MYR 3,200 touched on May 31st amid evidence of lower demand and strong supply. Early cargo surveyors showed that exports of Malaysian palm oil products fell by 16.7%-17.6% from the previous month in the first ten days of June. The developments were affected by stronger competition from the world’s top producer, Indonesia, as oversupply in its domestic market spurred higher exports. In the meantime, data from the Malaysian Palm Oil Board showed that inventories were at 1.67 million tonnes in the end of May, 12.6% higher than the previous month to mark the first buildup in four months. Inventories were built on the back of strong production in the period, with domestic output jumping by 27% to 1.52 million tonnes, firmly above expectations of 1.45 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 16:22:00 </td>
   <td style="text-align:left;"> French Stocks Up 0.7% on Monday </td>
   <td style="text-align:left;"> The CAC 40 index rose about 0.7% to 7,260 on the first trading day of the week, tracking its European peers higher, as investors focus on this week's policy meetings from the US Federal Reserve, the European Central Bank, and Bank of Japan. Among single stocks, Teleperformance advanced the most (+2.8%). The shares of Unibail-Rodamco-Westfield (+ 2.2%) were also among the top performers after Goldman Sachs upgraded the stock from "neutral" to "buy" and raised its price target from 61 to 63 euros. The luxury stocks Hermes, LVMH, and Kering increased by more than 1%, while the banking sector was also in the green. On the flip side, Orange (-0.9%) was leading the losses. Additionally, TotalEnergies lost 0.8% in the wake of the 1% decline in Brent to 74 dollars, its lowest level since the end of March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-12 16:14:58 </td>
   <td style="text-align:left;"> Bulgaria Trade Deficit Narrows in April </td>
   <td style="text-align:left;"> Bulgaria’s trade deficit narrowed to BGN 601.4 million in April 2023, from BGN 769.4 million in the corresponding month of the previous year, preliminary estimates showed. Imports fell 12.1% year-on-year to BGN 7,424.8 million, as arrivals declined sharply from the non-EU countries (-27.1%), while rose slightly to EU countries (+0.5%). On the other hand, exports contracted by 11.2% to BGN 6,823.4 million, dragged down by decreases in shipments to EU countries (-18.1%). In contrast, shipments to non-EU increased by 3.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2023-06-12 16:13:00 </td>
   <td style="text-align:left;"> NZ Dollar Hovers Near 2-Week High </td>
   <td style="text-align:left;"> The Kiwi dollar traded at around $0.6139 on Monday, hovering near its highest level in over two weeks, as traders awaited the US Fed monetary policy decision on Wednesday after several central banks hiked interest rates last week. Both the Reserve Bank of Australia and the Bank of Canada surprised markets with a 25bps interest rate increase following the pause in their previous meetings. Domestically, the country's annual inflation rate eased to 6.7% in Q1 of 2023 but stayed outside the Reserve Bank of New Zealand's medium-term target of 1%-3%. Meanwhile, the central regulator lifted the official cash rate for the 12th time in May, bringing borrowing costs to their highest level since December 2008 of 5.5%. Market participants now anticipate the release of New Zealand's Q1 GDP on Wednesday, with expectations growing that the economy could avoid a recession. Offering support to the Kiwi, the US dollar weakened slightly to around 103.4 due to a cautious mood ahead of the inflation data. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 16:01:00 </td>
   <td style="text-align:left;"> Italian Stocks Up to Start the Week </td>
   <td style="text-align:left;"> The FTSE MIB index rose more than 1% to around 27,450 on Monday, tracking its European peers higher, mainly driven by solid gains in Prysmian (+3%), Italgas (+1.9%) and Stellantis (+1.9%). On the other hand, Telecom Italia was down (-1%) after the group received improved offers from both KKR and CDP-Macquire consortium. Proposals are still unsatisfactory for shareholder Vivendi who has invited the board of directors to reject them and interrupt negotiations. Meanwhile, investors braced for key interest rate decisions this week in the US, Europe and Japan, along with US inflation data that will certainly influence the Fed's policy path. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2023-06-12 15:56:10 </td>
   <td style="text-align:left;"> British Pound Appreciates Toward 12-Month High </td>
   <td style="text-align:left;"> Sterling rose past $1.25, approaching a 12-month high of $1.2679 reached on May 10th, as the Bank of England remains committed to tightening monetary policy in order to combat high inflation. The Bank of England is expected to raise interest rates to 4.75% on June 22 and reach a peak of 5.5% by year-end. The latest CPI report showed UK annual inflation rate decreased to 8.7% in April from 10.1% in March, marking the first time it fell below double digits since last summer. Elsewhere, the outcome of the next Federal Reserve monetary policy meeting this week is highly uncertain, as inflation data is due to be released a day earlier, while the ECB is expected to raise rates by 25 bps when it meets on Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2023-06-12 15:44:55 </td>
   <td style="text-align:left;"> European Natural Gas Down after Last Week's Rally </td>
   <td style="text-align:left;"> Natural gas futures in Europe fell more than 6% below €30 per megawatt-hour, on some profit-taking after last week's 35% rally as investors weigh lower supplies against ample gas storage levels and weaker demand. Gas shipments from the US are becoming scarcer as the supply is funneled to Asia, where prices are more competitive in the summer months due to stronger demand for cooling. Meanwhile, Norway's Equinor has postponed the restart of its Hammerfest LNG plant to June 14 due to technical difficulties. Additionally, the Turkstream gas pipeline, which transports gas from Russia through the Black Sea to Turkey, has been closed for maintenance work. Currently, Europe's gas storage is 70.4% full, and the European Union aims to achieve a storage inventory target of 90% by November 1. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 15:40:49 </td>
   <td style="text-align:left;"> British Shares Edge Higher to Start Week </td>
   <td style="text-align:left;"> The FTSE 100 edged higher to hover near the 7,590 mark on Monday, trimming the slight losses from the prior week as markets continued to assess the outlook of the British economy ahead of further tightening by major central banks. The CBI revised GDP forecasts to reflect a slight growth in the British economy in 2023, joining the BoE in ditching expectations of a recession and highlighting the resilience of businesses to the current high-interest rate environment. Shares for the Ocado Group led the gains, extending its volatile momentum to add 6%. Also, Croda shares jumped by over 2% to trim the 12% slump on Friday due to the company’s profit warning issuance. On the other hand, resource-dependent companies led the losses, tracking a broad decline for commodity prices to start the week with BP, Shell, Anglo American, and Rio Tinto trading firmly in the red. Also, Glencore edged 0.4% down after confirming its offer to buy the Canadian Teck Resources’s steelmaking coal business. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2023-06-12 15:39:00 </td>
   <td style="text-align:left;"> Brent Crude Oil Falls For 3rd Session </td>
   <td style="text-align:left;"> Brent crude futures fell below $74 per barrel on Monday, as concerns about weakening demand in top consumer China and rising Russian crude supply outweighed Saudi Arabia's plans to slash output. Russian oil exports to China and India rose to record levels in May even after the implementation of the European Union’s embargo and the Group of Seven’s price cap mechanism that started in early December. On the other hand, Saudi Arabia, the world's largest oil exporter, announced earlier this month its intention to reduce output by 1 million barrels per day to 9 million bpd in July, the lowest level in years amid an effort to bolster crude prices. Meanwhile, investors are cautious ahead of a busy week ahead with the US inflation rate and interest rate decisions from the Federal Reserve, the ECB and the BoJ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/current-account </td>
   <td style="text-align:left;"> 2023-06-12 15:30:00 </td>
   <td style="text-align:left;"> Turkey Current Account Deficit Widens Sharply </td>
   <td style="text-align:left;"> Turkey’s current account deficit widened sharply to USD 5.40 billion in April 2023, more than doubling USD 2.54 billion gap in the same month a year earlier and above market forecasts of a USD 4.50 billion shortfall due to the deterioration in the deficit of goods (USD 7.02 billion vs USD 4.34 billion in April 2022) and primary income (USD 1.29 billion vs USD 0.90 billion). On the other hand, the gap for secondary income narrowed broadly to USD 0.01 billion (vs USD 0.10 billion), while the services surplus increased to USD 2.92 billion (vs USD 2.79 billion). Excluding gold and energy, the current account posted a USD 0.48 billion deficit, shifting from a USD 4.19 billion surplus in the corresponding period last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/czech-republic/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 15:23:00 </td>
   <td style="text-align:left;"> Czech Republic Inflation Rate Lowest in 15 Months </td>
   <td style="text-align:left;"> The annual inflation rate in the Czech Republic eased to a 15-month low of 11.1% in May 2023 from 12.7% in the previous month, and slightly above market estimates of 10.9%. Prices slowed for most sub-indices, led by food &amp; non-alcoholic beverages (14.5% vs 17.3% in April) and housing &amp; utilities (16.1% vs 17.6%). Additional downward pressure came from restaurants &amp; hotels (15% vs 17.5%), clothing &amp; footwear (12.1% vs 13.1%), miscellaneous goods &amp; services (10.8% vs 12.3%), furnishings &amp; household equipment (10.4% vs 12%) and recreation &amp; culture (11.7% vs 12.9%). At the same time, transport costs declined further (-4.4% vs -1.7%), mainly due to falling fuel prices. On a monthly basis, consumer prices increased 0.3%, rebounding from a 0.2% drop in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ora:fp </td>
   <td style="text-align:left;"> 2023-06-12 15:21:44 </td>
   <td style="text-align:left;"> Orange Hits 16-week Low </td>
   <td style="text-align:left;"> Orange decreased to a 16-week low of 10.514 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 15:19:00 </td>
   <td style="text-align:left;"> European Stocks Start Week Higher </td>
   <td style="text-align:left;"> The German DAX rose more than 1% on Monday, boosted by an over 5% rally in Adidas shares after Bernstein upgraded the stock's rating from "market perform" to "outperform," citing potential benefits from the return of Chinese influencers and Lionel Messi's transfer to Inter Miami. Also, the benchmark Stoxx 600 is up 0.6%, as investors look ahead to monetary policy decisions from major central banks this week. The Federal Reserve will announce its latest policy move on Wednesday, the European Central Bank on Thursday and the Bank of Japan on Friday. In corporate news, Swiss bank UBS said that it formally completed the takeover of its rival Credit Suisse. Meanwhile, there are no major economic releases and earnings reports in Europe on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-12 15:15:00 </td>
   <td style="text-align:left;"> Turkish Jobless Rate Edges Up to 4-Month High </td>
   <td style="text-align:left;"> The unemployment rate in Turkey rose to a four-month high of 10.2 percent in April of 2023 from an upwardly revised 10.1 percent in the previous month. The number of unemployed surged by 74 thousand to 3,585 million people, and the number of employed soared by 521 thousand to 31.610 million. Among genders, the jobless rate was lower for men (at 8.1 percent) than for women (at 14.3 percent). The labor force participation rate went up to 53.9 percent from a downwardly revised 53 percent in March, and the employment rate increased to 48.4 percent from 47.6 percent. Meanwhile, the youth jobless rate for those aged between 15-24 years was down 1.2 percentage points to 19.1 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovakia/construction-output </td>
   <td style="text-align:left;"> 2023-06-12 15:13:56 </td>
   <td style="text-align:left;"> Slovak Construction Output Shrinks for Second Month </td>
   <td style="text-align:left;"> Construction output in Slovakia shrank 8.3% year-on-year in April 2023, the second month of contraction, although easing from a 10.1% fall in the previous month. Domestic construction fell less (-9% vs -11.3% in March), as engineering works rebounded (1.5% vs -10.7%). Meanwhile, construction abroad declined (-2.2% vs 1.3%). On a seasonally adjusted monthly basis, construction activity fell by 10.4%, the same as in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 14:51:00 </td>
   <td style="text-align:left;"> NZX 50 Close at 11-Week Low </td>
   <td style="text-align:left;"> Stocks in New Zealand lost 74.79 points or 0.64% to finish at 11,615.55 on Monday, their lowest since March 27th and down for the sixth session, amid worries that the domestic economy has fallen into a recession during Q1 of 2023. Markets projected a GDP contraction of 0.1% for the first three months of the year, the second negative reading in a row, due to weakness in retail and wholesale sectors. Still, bets that the US Fed is nearing the end of its hiking cycle limited the losses, along with hopes that China's central bank would cut its medium-term lending facility later this week. Distribution services, consumers, and transport dragged down the index, while financials also moved lower after Fitch Ratings cut its outlooks for the banking sectors in New Zealand and Australia due to falls in earnings and asset quality. South Port of NZ sank 5.7%, followed by Freightways Group (-3.9%), A2 Milk Co. (-3.1%), Auckland Intl. (-2.9%), and Skellerup Hlds. (-2.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 14:30:11 </td>
   <td style="text-align:left;"> The Nikkei 225 Index rose 0.59% </td>
   <td style="text-align:left;"> In Tokyo the Nikkei 225 Index rose 191 points or 0.59 percent on Monday. Leading the gains are Taiheiyo Cement (4.55%), Mitsubishi Heavy Industries (3.80%) and Daiichi Sankyo (3.54%). Top losers were Tokyo Electric Power (-3.98%), Kawasaki Kisen (-3.92%) and Nippon Yusen (-2.47%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 14:28:00 </td>
   <td style="text-align:left;"> European Markets Head for Higher Open </td>
   <td style="text-align:left;"> European equity markets were headed for a higher open on Monday as investors look ahead to monetary policy decisions from major central banks this week. The Federal Reserve will announce its latest policy move on Wednesday, the European Central Bank on Thursday and the Bank of Japan on Friday. Meanwhile, there are no major economic releases and earnings reports in Europe on Monday. DAX futures rose 0.4% in premarket trade, while Stoxx 600 and FTSE 100 futures  both gained 0.5%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/machine-tool-orders </td>
   <td style="text-align:left;"> 2023-06-12 14:23:54 </td>
   <td style="text-align:left;"> Japan Machine Tool Orders Down 22.2% YoY in May </td>
   <td style="text-align:left;"> Japan’s machine tool orders dropped 22.2% year-on-year to JPY 119,316 million in May 2023, slipping further from an upwardly revised 14.4% fall in the previous month, data from Japan Machine Tool Builders’ Association showed. Domestic demand shrank 24% to JPY 37,599 million, while foreign orders declined 21.3% to JPY 81,717 million. Considering the January-May period, machine tool orders contracted 14.6%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-12 14:23:00 </td>
   <td style="text-align:left;"> Danish Inflation Rate at 20-Month Low </td>
   <td style="text-align:left;"> Denmark's annual inflation rate declined to 2.9% in May 2023 from 5.3% in April. It was the lowest figure since September 2021, with food prices rising the least in 12 months (10.6% vs 13.1%) and transport (-1.0% vs 2.6%) and housing (-1.6% vs 2.0%) prices falling. Also, the cost eased for clothing (2.6% vs 3.8% in April), communication (3.6% vs 5.4%), leisure &amp; culture (3.8% vs 4.6%), restaurants and hotels (7.8% vs 10%), household services (5.4% vs 8.9%), and other goods and services (5.7% vs 6.3%). Meanwhile, inflation accelerated for health (4.7% vs 4.4%) and alcoholic beverages &amp; tobacco (3.5% vs 3.1%). Education was steady (at 3.0%). Monthly, consumer prices dropped 1.4% in May, reversing a 0.3% rise in the previous period. The harmonized index of consumer prices advanced by 2.9%, the least in 20 months, after a 5.6% growth in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-12 14:10:00 </td>
   <td style="text-align:left;"> Japan 10-Year Yield Steadies Around 0.42% </td>
   <td style="text-align:left;"> Japan’s 10-year government bond yield steadied around 0.42% in mid-June, moving in a tight range as investors look ahead to the Bank of Japan’s policy meeting, in which the regulator is expected to maintain ultra-low interest rates without making any changes to the current yield curve control policy. The body is also likely to caution markets about slowing global demand and project moderate economic recovery driven by robust corporate and household spending. BOJ officials have repeatedly stated they are intent on maintaining massive stimulus until the 2% inflation target is achieved in a sustainable and stable manner. However, hopes linger that the lender could start normalizing its monetary policy by the end of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 13:15:46 </td>
   <td style="text-align:left;"> Sensex Rises Ahead of Inflation Data </td>
   <td style="text-align:left;"> The BSE Sensex rose 110.5 points or 0.2% to 62,736.1 in morning trade on Monday, rising for the first session in three, ahead of domestic inflation data later today. Optimism grew after the Reuters poll showed the country's annual inflation slowed to a 20-month low of 4.42% in May, staying within the RBI's 2%-6% target range for the second straight month. Market participants also awaited India's manufacturing production in April, with markets expecting to accelerate to 1.8% from 1.1% in March. Investors also awaited the US May inflation data that was the clue of the Fed monetary policy decision later this week. Among the top gainers were realty, technologies, media, and metals. HCL Technologies rose 1.8%, followed by SBI Life (1.7%),  HDFC Life (1.5%), Infosys (1.5%), and Bharat Petroleum Corp (1.2%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/12/ubs-says-it-has-completed-the-takeover-of-credit-suisse.html </td>
   <td style="text-align:left;"> 2023-06-12 13:08:24 </td>
   <td style="text-align:left;"> UBS says it has completed the takeover of stricken rival Credit Suisse </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                             , Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                , Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                        , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                         , Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                           , Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                               , Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                         , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Banking                                                                                                                                                                                                                                                                                                                                                                                                                                              , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                                                         , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                          , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                            , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                                                               , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                                                                       , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                  , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                                                                     , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                       , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                                                           , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                           , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                                                               , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                     , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                                                                   , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                             , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                                                                    , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                             , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                             , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                                                                      , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                   , All Investing                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                                                                       , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                                                              , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                                                             , ETFs                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Bonds                                                                                                                                                                                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                          , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                          , Swiss bank UBS on Monday said that it formally completed the takeover of its rival Credit Suisse.                                                                                                                                                                                                                                                                                                                                                        , "Instead of competing, we'll now unite as we embark on the next chapter of our joint journey," UBS Group's newly-returned CEO Sergio Ermotti said in a statement.                                                                                                                                                                                                                                                                                        , In an open letter, the bank's chiefs also said they would not compromise UBS's "strong culture" or "conservative risk approach." Risk management failures over a number of years played a key role in Credit Suisse's eventual downfall.                                                                                                                                                                                                                 , Ermotti told CNBC's "Squawk Box" in a Monday interview that he believed the combined bank — which he said was the world's 21th largest — would "compete better, serve our clients better."                                                                                                                                                                                                                                                               , "We are the only bank with this kind of magnitude and size and scope that is focused on wealth management," Ermotti said.                                                                                                                                                                                                                                                                                                                                , "We need to make sure we don't fall back into any bad habits or do things the wrong way. But in that sense we have a very clear view on how to manage a UBS-led integration," he continued, as it seeks to "restore confidence."                                                                                                                                                                                                                         , UBS Group will manage UBS and Credit Suisse as separate banks at least for the short term. Questions linger over the future of assets including Credit Suisse's prized retail bank.                                                                                                                                                                                                                                                                      , Following the acquisition, Credit Suisse and its American Depositary Shares will be delisted from the SIX Swiss Exchange and New York Stock Exchange, with shareholders receiving one UBS share for every 22.48 Credit Suisse shares held.                                                                                                                                                                                                               , The enlarged UBS will have a balance sheet of $1.6 trillion and a workforce of 120,000. Ermotti previously warned the new group "won't be able to create, short term, job opportunities for everybody. Synergies is part of the story." The combined company will report its first consolidated results on August 31.                                                                                                                                    , UBS said Monday it expected "Credit Suisse operating losses and significant restructuring charges" to be offset as it ditches risk-weighted assets, and forecast a common equity tier 1 capital ratio — a measurement of capital against assets — of around 14% for the rest of the year.                                                                                                                                                                , In an internal memo seen by CNBC, the bank announced that several senior Credit Suisse figures intend to leave the company, including Chief Financial Officer Dixit Joshi, who only took on the role in October, and Asia Pacific regional CEO Edwin Low.                                                                                                                                                                                                , Simon Grimwood, currently Credit Suisse's global head of tax and finance change, will take over as Credit Suisse CFO. Grimwood has been managing integration planning since March, the bank said.                                                                                                                                                                                                                                                        , Former Credit Suisse Co-head of Markets Michael Ebert will become head of the Credit Suisse investment bank and head of Americas at UBS investment bank, while Jake Scrivens will replace Markus Diethelm as general counsel. Credit Suisse Global Head of Operations Isabelle Hennebelle joins the board in her existing role as head of operations.                                                                                                    , Asked whether he was concerned about an exodus of talent, Ermotti told CNBC: "We are always sorry to see talented people leaving, in other cases people were anticipating probably the inevitable restructuring that we will need to go through and decided to go."                                                                                                                                                                                      , He added that the bank had managed to attract external talent after the acquisition announcement.                                                                                                                                                                                                                                                                                                                                                        , Ermotti's own return to the UBS top job was confirmed in March shortly after the takeover announcement to oversee the transition. He previously led the company from November 2011 to October 2020, managing the fallout from the 2008 financial crisis and a $2.3 billion loss stemming from a rogue trader in London. UBS Chair Colm Kelleher said he "transformed" the bank through cost cutting and implementing cultural changes.                   , The $3.2 billion takeover was the tumultuous conclusion of a frantic weekend in March, when worries that severe losses at Credit Suisse would destabilize the banking system drew the key involvement of Swiss regulators.                                                                                                                                                                                                                               , Sweetening the deal, the Swiss government has agreed to cover losses of up to 9 billion Swiss francs ($10 billion) after UBS incurs the first 5 billion Swiss francs as part of the transaction, as the bank absorbs a portfolio that does not entirely "fit its business and risk profile."                                                                                                                                                             , The takeover, which follows multiple scandals and years of share price decline at Credit Suisse, controversially wiped out the 16 billion Swiss francs ($17 billion) worth of assets of the bank's AT1 bond holders.                                                                                                                                                                                                                                     , Beat Wittmann, co-founder and partner at Porta Advisors, said the speed with which UBS had managed the takeover was positive for the bank.                                                                                                                                                                                                                                                                                                               , Going forward will be "certainly a challenge … but UBS, due to the emergency operation and the collective failure of policymakers and of course of Credit Suisse, got over a weekend an extraordinarily advantageous deal," Wittmann told CNBC's "Squawk Box Europe".                                                                                                                                                                                    , "There's so much margin of safety in terms of price, in terms of credit lines, in terms of risk sharing with the government, that this is a great deal indeed."                                                                                                                                                                                                                                                                                          , Wittmann said that UBS faces several key challenges, the first of which is the physical integration of the two banking juggernauts and merging of their operating models.                                                                                                                                                                                                                                                                                , Citing a Financial Times report published over the weekend — which CNBC has not confirmed — that UBS had set "red lines" for Credit Suisse bankers including bans on new clients from high-risk countries and on launching new products without the approval of UBS managers, Wittmann said "that's exactly what a bank should do in any case."                                                                                                          , Addressing the report, Ermotti told CNBC: "We have developed that 'red line', which I wouldn't really call a 'red line', over the course of years. This is simply what I mentioned before, we are introducing our processes, our operating model, into Credit Suisse. It's not meant to be discriminatory."                                                                                                                                              , As for further challenges, Wittman drew attention to an upcoming parliamentary inquiry into the Credit Suisse takeover and wider banking stability. Swiss elections could also lead to "populist demands," he stressed, as jobs are cut and branches close around Switzerland. A final trial is the broader macro environment, Wittman said, given the current credit crunch and likely financial market volatility resulting from higher interest rates., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                         , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/finland/current-account </td>
   <td style="text-align:left;"> 2023-06-12 13:08:00 </td>
   <td style="text-align:left;"> Finnish Current Account Deficit Narrows Sharply </td>
   <td style="text-align:left;"> Finland's current account deficit shrank to EUR 1,745 million in April 2023 from EUR 4,122 million in the same month of the previous year, with the primary income gap narrowing to EUR 1,738 million from EUR 2,879 million. Also, the secondary income deficit decreased to EUR 123 million from EUR 242 million. Meanwhile, the goods account posted a strong surplus of EUR 1,178 million, reversing a shortfall of EUR 380 million in April last year. On the other hand, the service account gap increased to EUR 1,061 million from EUR 620 million in the prior year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2023-06-12 12:23:00 </td>
   <td style="text-align:left;"> South Korean Won Weakens Further </td>
   <td style="text-align:left;"> South Korean won was changing hands around 1,291 against USD on Monday, staying below the psychological level of 1,300 for the third day, as Asia's fourth-largest economy was losing momentum in the long-term expansion. The Bank of Korea in May cut its 2023 growth forecasts to 1.4% from the prior 1.6%. Meanwhile, Seoul recently flagged GDP below 1.6% this year, much lower than the 3.1% in 2022. However, the government has yet to consider measures such as a supplementary budget to support the economy. On the trade front, the country suffered a 14th successive trade deficit last month, the longest such sequence since 1997, as exports fell for the eighth consecutive period, owing to sluggish overseas sales of semiconductors, South Korea's top sales item. The weakness in local currency held even though the US dollar remained near multi-week lows after hopes built that the Fed may pause its rate hike cycle during its meeting later this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/retail-sales-yoy </td>
   <td style="text-align:left;"> 2023-06-12 12:16:00 </td>
   <td style="text-align:left;"> Malaysia Retail Trade Growth Eases to 13-Month Low </td>
   <td style="text-align:left;"> Retail trade in Malaysia rose by 12.9 percent year-on-year in April 2023, slowing from a 17.7 percent gain in the previous month. It was the slowest expansion in retail activity since March 2022, as sales eased for household equipment (1.5 percent vs 7.8 percent in March), other goods in specialized stores (17.4 percent vs 21.9 percent), and non-specialized stores (18 percent vs 19.8 percent). At the same time, wholesale trade slowed (3.2 percent vs 7.6 percent), while sales for motor vehicles dropped sharply (-5.1 percent vs 9.3 percent). On a monthly basis, retail sales grew by 3.1 percent, accelerating from a 0.9 percent rise in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2023-06-12 11:33:11 </td>
   <td style="text-align:left;"> Gold Subdued as CenBank Meetings Loom </td>
   <td style="text-align:left;"> Gold fell below $1,960 an ounce in subdued trade on Monday, as caution dominated sentiment ahead of monetary policy meetings scheduled this week for the Federal Reserve, the European Central Bank and the Bank of Japan. Investors also braced for US inflation data this week that could influence the outlook for the economy and interest rates. Markets see an over 70% chance that the Fed will keep its benchmark interest rate unchanged on Wednesday, while remaining split on whether it would hold rates steady or resume its policy tightening in July. The BOJ is also expected to maintain its ultra-loose monetary policy on Friday, while the ECB is widely anticipated to raise its policy rate by 25 basis points this week and again in July to combat sticky inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2023-06-12 11:16:00 </td>
   <td style="text-align:left;"> Dollar Steadies Ahead of Busy Week </td>
   <td style="text-align:left;"> The dollar index steadied above 103.5 on Monday as investors geared up for US inflation data and the Federal Reserve’s interest rate decision this week. Last week, the index lost 0.5% as softer-than-expected economic data supported the case for a pause in the Fed’s tightening cycle at the upcoming meeting. Meanwhile, markets remain divided on whether the US central bank would hold rates steady or resume its policy tightening in July. Externally, investors also braced for monetary policy decisions from the European Central Bank and the Bank of Japan. The ECB is widely expected to raise its policy rate by 25 basis points this week and again in July to combat sticky inflation. On the other hand, the BOJ is anticipated to maintain its ultra-loose monetary policy this week as continued economic recovery was countered by slowing global growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/indonesia/consumer-confidence </td>
   <td style="text-align:left;"> 2023-06-12 11:14:00 </td>
   <td style="text-align:left;"> Indonesia Consumer Morale Highest in A Year </td>
   <td style="text-align:left;"> Indonesia's consumer confidence increased to 128.3 in May 2023 from 126.1 in April, pointing to the highest level since May 2022. Households' assessment regarding the country's economic outlook improved (up by 2.3 points to 137.8), and those of current economic conditions strengthened (up by 2.3 points to 118.9). Also, the job availability rose (by 3.0 points to 121.1), as did the job availability compared to six months ago (by 0.1 points to 136.6) and current income (up by 1.5 points to 125.4). On the other hand, sub-indexes of income expectations for the next six months were lower (down by 1.0 points to 136.9). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 10:56:00 </td>
   <td style="text-align:left;"> China Stocks Mixed on Monday </td>
   <td style="text-align:left;"> The Shanghai Composite fell 0.08% to close at 3,229 while the Shenzhen Component gained 0.74% to 10,874 in mixed trade on Monday, as economic uncertainties continued to weigh on sentiment, while hopes for further policy support buoyed the technology sector. Investors also remained cautious ahead of monetary policy decisions from major central banks this week amid concerns that further interest rate hikes could dampen overall demand. Technology stocks advanced after China’s securities regulator vowed to support technology self-independence with fresh capital markets policies. Gains in the sector were led by Foxconn Industrial (7.9%), Zhongji Innolight (4.9%), and 360 Security Technology (2%). Meanwhile, healthcare, industrial and financial stocks mostly declined. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 10:35:00 </td>
   <td style="text-align:left;"> Hong Kong Stocks Snap 3-Day Gains </td>
   <td style="text-align:left;"> Hong Kong's shares fell 75 points or 0.38% to 19,315 in early deals at the start of the week, halting gains from the prior three sessions, as traders were cautious ahead of several interest rate decisions from central banks in the US, Europe, China, and Japan this week. Unexpected hikes last week from the Bank of Canada and the Reserve Bank of Australia have added an extra element of uncertainty. Also, concerns over the health of China's economy lingered amid growing deflation risk following weak inflation numbers for May and ahead of a slew of data later in the day, including new yuan loans, M2 money supply, and total social financing. Losses were across the board, with healthcare, property, and energy among early decliners. JD Health Intl. slipped 5.6%, followed by Longfor Group (4.4%), Wuxi Biologics (-3.7%), Li Ning (-3.2%), and Country Garden Hlds. (-2.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/stocks </td>
   <td style="text-align:left;"> 2023-06-12 10:18:00 </td>
   <td style="text-align:left;"> Asian Stocks Mixed Ahead of CenBank Meetings </td>
   <td style="text-align:left;"> Asian equity markets were mixed on Monday as caution dominated sentiment ahead of monetary policy meetings scheduled this week for the Federal Reserve, the European Central Bank and the Bank of Japan. Investors also assessed data showing Japanese producer prices rose 5.1% year-on-year in May 2023, slowing for the fifth straight month to its lowest level in nearly two years amid easing global inflationary pressures. The Nikkei 225, Topix and Shenzhen Component indexes advanced, while the Kospi, Shanghai Composite and Hang Seng indexes declined. Meanwhile, Australian markets are closed for a holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2023-06-12 09:48:00 </td>
   <td style="text-align:left;"> Oil Declines in Cautious Trade </td>
   <td style="text-align:left;"> WTI crude futures fell below $70 per barrel on Monday, sliding for the third straight session as caution dominated sentiment ahead of a heavy calendar week, headlined by US inflation data and the Federal Reserve’s interest rate decision. Persistent concerns about Chinese demand growth also weighed on markets as weaker-than-expected economic data pointed to a challenging recovery path for the world’s top crude importer. On the supply side, Russian oil exports to China and India increased even after the implementation of the European Union’s embargo and the Group of Seven’s price cap mechanism that started in early December, Reuters reported. These bearish factors have so far outweighed Saudi Arabia’s efforts to boost prices by reducing an additional 1 million barrels per day of oil production in July. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 09:02:00 </td>
   <td style="text-align:left;"> Japanese Shares Rise for Second Session </td>
   <td style="text-align:left;"> The Nikkei 225 Index gained 0.52% to close at 32,434, while the broader Topix Index climbed 0.65% to 2,239 on Monday, rising for the second straight session, with nearly all sectors participating in the advance. While looking ahead to the Bank of Japan’s policy decision on Friday, investors digested data showing producer prices in Japan slowed more than expected in May. Notable wins were seen from technology names such as Socionext (4.5%), SoftBank Group (1.6%), Advantest (2.9%), Keyence (2.3%), and Renesas Electronics (1.9%). Other index heavyweights also advanced, including Eisai Co (9%), Mitsubishi Heavy Industries (3.7%), Sony Group (1%), Daiichi Sankyo (4.1%), and Nidec Corp (2.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-12 08:22:00 </td>
   <td style="text-align:left;"> Japan Producer Prices Hit Near 2-Year Low </td>
   <td style="text-align:left;"> Producer prices in Japan rose 5.1% year-on-year in May 2023, slowing for the fifth straight month to their lowest level in nearly two years amid easing global inflationary pressures. May’s figure also followed a revised 5.9% gain in April and came below expectations of a 5.5% growth. Costs declined further for textile products (6.8% in May vs 8.3% in April), plastic products (6.3% vs 7.2%), iron &amp; steel (9% vs 10.8%), transportation equipment (3.4% vs 3.9%) and lumber &amp; wood products (-19.8% vs -18.2%). On a monthly basis, producer prices dropped 0.7%, turning negative for the first time since February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/12/investors-eye-chinas-neighbors-as-recovery-from-zero-covid-slows.html </td>
   <td style="text-align:left;"> 2023-06-12 08:21:52 </td>
   <td style="text-align:left;"> Investors are eyeing China's neighbors as the recovery from 'zero-Covid' slows </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                            , Loans                                                                                                                                                                                                                                                                                                                                                   , Banking                                                                                                                                                                                                                                                                                                                                                 , Mortgages                                                                                                                                                                                                                                                                                                                                               , Insurance                                                                                                                                                                                                                                                                                                                                               , Credit Monitoring                                                                                                                                                                                                                                                                                                                                       , Personal Finance                                                                                                                                                                                                                                                                                                                                        , Small Business                                                                                                                                                                                                                                                                                                                                          , Taxes                                                                                                                                                                                                                                                                                                                                                   , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                              , Investing                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Credit Cards                                                                                                                                                                                                                                                                                                                                        , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                            , Best Credit Cards                                                                                                                                                                                                                                                                                                                                       , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                               , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                      , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                             , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                        , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                       , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Loans                                                                                                                                                                                                                                                                                                                                               , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                     , Best Personal Loans                                                                                                                                                                                                                                                                                                                                     , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                           , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                            , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                               , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                               , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                     , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Banking                                                                                                                                                                                                                                                                                                                                             , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                        , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                        , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                          , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                         , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                           , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                      , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                           , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                              , Best CDs                                                                                                                                                                                                                                                                                                                                                , Best Credit Unions                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Mortgages                                                                                                                                                                                                                                                                                                                                           , Best Mortgages                                                                                                                                                                                                                                                                                                                                          , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                   , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                      , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                  , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                 , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                               , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Insurance                                                                                                                                                                                                                                                                                                                                           , Best Life Insurance                                                                                                                                                                                                                                                                                                                                     , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                               , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                  , Best Car Insurance                                                                                                                                                                                                                                                                                                                                      , Travel Insurance                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                   , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                         , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                          , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                          , Credit Repair Services                                                                                                                                                                                                                                                                                                                                  , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Personal Finance                                                                                                                                                                                                                                                                                                                                    , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                     , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                               , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                              , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                           , Best Debt Relief                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Small Business                                                                                                                                                                                                                                                                                                                                      , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                    , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                   , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                    , Best Small Business Loans                                                                                                                                                                                                                                                                                                                               , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Taxes                                                                                                                                                                                                                                                                                                                                               , Best Tax Software                                                                                                                                                                                                                                                                                                                                       , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                  , Tax Refunds                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                          , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                        , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                      , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                            , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                 , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                   , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                            , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                            , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                           , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                     , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                  , All Investing                                                                                                                                                                                                                                                                                                                                           , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                       , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                  , Best Investing Apps                                                                                                                                                                                                                                                                                                                                     , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                       , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                      , Index Funds                                                                                                                                                                                                                                                                                                                                             , Mutual Funds                                                                                                                                                                                                                                                                                                                                            , ETFs                                                                                                                                                                                                                                                                                                                                                    , Bonds                                                                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                         , China's lackluster economic recovery since emerging from strict "zero-Covid" lockdowns has caused weaker sentiment toward the country, prompting investors to look for alternative options — like its near neighbors.                                                                                                                                   , In particular, stock markets in Japan, South Korea and India have all been major beneficiaries of the disappointment from China's reopening, highlighted by softer-than-expected data from the world's second-largest economy.                                                                                                                          , "Amid China weakness, investors have looked elsewhere in the region for opportunities," Goldman Sachs Chief Asia-Pacific Economist Andrew Tilton said in a Friday research note, adding that Japan "is in the limelight" while India has "also returned to focus in recent months."                                                                     , The Nikkei 225 is in bull market territory, up by more than 23% year-to-date thanks to garnered interest from foreign investors, including Berkshire Hathaway's Warren Buffett.                                                                                                                                                                         , India's Nifty 50 index has rallied nearly 7% so far this quarter and pared all of its losses from its March low, while South Korea's Kospi index has risen 18% year-to-date.                                                                                                                                                                            , Bernstein says buy this China-based personal finance stock that can rally nearly 60%                                                                                                                                                                                                                                                                    , Morgan Stanley names 2 chip stocks with 'significant upside' as China bans Micron                                                                                                                                                                                                                                                                       , This fund puts a spin on emerging markets investing with bets from Nvidia to Chinese spirits                                                                                                                                                                                                                                                            , That shows a stark contrast to a sell-off seen in the Chinese stock market. The CSI 300 index, which measures the largest companies listed in Shanghai and Shenzhen, has fallen 5.29% quarter-to-date and has erased all of its gains seen earlier in the year, when stocks rallied on reopening momentum.                                              , The Hang Seng index also touched bear market territory last month and is down nearly 2% year-to-date, Refinitiv data shows.                                                                                                                                                                                                                             , "Investor sentiment on China has weakened further, and in our view is around rock-bottom levels we've only seen a few times over the past decade," Goldman Sachs' Tilton said in the note.                                                                                                                                                              , Foreign investors have undoubtedly been key in driving the Japanese market, maintaining the highest levels the Nikkei has seen since 1990.                                                                                                                                                                                                              , The latest data from Japan's Ministry of Finance shows overseas investors continue to build on their Japanese equity positions as domestic investors remain the net buyers of foreign bonds.                                                                                                                                                            , Foreign investors bought a net 342.18 billion Japanese yen ($2.45 billion) of stocks in the week ending June 2, according to a Reuters calculation, totaling roughly 6.65 trillion yen of net purchases of Japanese shares this year. During the same period last year, foreign investors had sold a net 1.73 trillion yen approximately.               , PRO Japan is in a ‘Goldilocks’ position, Credit Suisse says. Here’s how to play itPRO Japan stocks are on fire this year. Here are 3 reasons why the rally could have ‘staying power’What Warren Buffett is buying in Japan's Berkshire Hathaway look-alikesCall to ‘Buy Japan’ is premature, say Bank of America analysts                              , Wall Street banks including Morgan Stanley and Societe Generale are among those that are optimistic on Japanese stocks, holding "overweight" positions.                                                                                                                                                                                                 , In its global mid-year outlook, Morgan Stanley predicted Japanese stocks will outperform their global peers: "Japan is our most preferred region, with improving ROE [Return-on-Equity] and a superior EPS [earnings per share] outlook," Chief Investment Officer Mike Wilson said.                                                                    , The firm raised its estimates for the Topix index to rise 18% by June 2024 from its previous target of a 13% gain.                                                                                                                                                                                                                                      , "Japan [is] looking even more attractive, while we hold a preference for EM [emerging markets] versus the U.S. and EU," Morgan Stanley strategists said in a note, adding that "accelerating regional growth and solid domestic GDP should support earnings" for Japanese companies.                                                                    , South Korea is another market closely watched as concerns over China's recovery linger.                                                                                                                                                                                                                                                                 , Korean technology stocks, which make up roughly half of the Kospi 200 index, have been the main driver behind UBS Global Wealth Management's "most preferred" status on the sector and its market.                                                                                                                                                      , Noting that the bank expects U.S. interest rates to peak soon followed by a drop in the U.S. dollar, UBS wrote in its monthly outlook: "We remain most preferred on Asia semiconductors over the next 3-6 months and Korea, which we've previously highlighted as a winner in such an environment."                                                     , South Korean technology stocks' low price-to-book ratio makes it "an attractive alternative to more expensive tech segments," UBS said, noting that there is still "significant value" seen in China's e-commerce stocks, which have plunged 20% year-to-date. Price-to-book ratio is an important metric used by traders to gauge the value of a stock., "For China, questions continue over the durability of its economic recovery. This, and ongoing geopolitical concerns, have weighed on the market," UBS strategists said in the report.                                                                                                                                                                  , Goldman Sachs is also confident in the South Korean market, expecting more overseas investment ahead.                                                                                                                                                                                                                                                   , "We are relatively bullish on Korea both because we are less concerned about broader domestic spillovers from housing sector weakness and more optimistic about foreign portfolio inflows," Goldman's Tilton said.                                                                                                                                      , The Bank of Korea, meanwhile, is expected to be one of the first central banks to deliver a monetary policy pivot, despite its governor Rhee Chang-yong telling CNBC that it's still "premature" to be discussing a rate cut.                                                                                                                           , Banks including Citi and Nomura are expecting to see a rate cut of 25 basis points as early as the third quarter of this year.                                                                                                                                                                                                                          , South Korea's money market fund (MMF) logged a record high at the end of May, data from Korea Financial Investment Association showed. The total MMF assets under management stood at 172.7 trillion South Korean won ($134 billion), or a 22% rise since the end of September last year.                                                               , A money market fund is a type of fund that invests in highly liquid, near-term instruments, including cash, and is seen as a place of safety amid a volatile market.                                                                                                                                                                                    , Fitch Ratings Senior Analyst Chloe Andrieu said in a June 8 note: "The increase was driven by institutional investors pivoting assets towards high-quality investments, such as MMFs," adding that rising interest rates across the world have also contributed to the shift.                                                                           , In contrast, newly launched funds in China marked the smallest holdings since 2019 for the first five months of this year, having raised a total of 432.1 billion Chinese yuan ($61 billion), according to data from local consultancy Z-Ben Advisors.                                                                                                  , There is also growing interest in investing in India, according to Goldman Sachs.                                                                                                                                                                                                                                                                       , "Clients increasingly ask about India's potential to benefit from greater investment amid supply chain reconfiguration," Tilton said. The firm said it is "generally positive in the medium term," citing India's continued monetary policies, credit conditions, and its prospects for attracting foreign direct investment.                           , HSBC's chief economist for India and Indonesia, Pranjul Bhandari, said ahead of the Indian central bank's June meeting that keeping rates unchanged would be "allowing the perfect macro mix to continue," pointing to raised growth and lowered inflation forecasts.                                                                                   , The firm also raised India's full-year gross domestic forecast for 2024 from 5.5% to 5.8% and expects the RBI to deliver two rate cuts in the first quarters of 2024, bringing its repo rate to 6% by mid-2024.                                                                                                                                         , "India's economy is much improved from a year ago," Bhandari said. "GDP growth momentum has been steady as per the latest high frequency data, with the informal sector picking up the slack as the formal sector growth softens," she said.                                                                                                            , The Reserve Bank of India held its benchmark repo rate steady at 6.50% last week for the second consecutive time — in line with market expectations.                                                                                                                                                                                                    , The Organization for Economic Cooperation and Development also expects India's economic growth to outpace that of China this year and next, it said in its latest global outlook report.                                                                                                                                                                , "Growth has surprised on the upside recently, and we believe an improving informal sector is at the heart of it," Bhandari said. "Rising state government spending, and some cushion in the central government budget to support social welfare schemes, is likely to remain supportive of informal sector demand."                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                        , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/12/ad-sales-in-china-are-pointing-to-a-soft-recovery-for-the-consumer.html </td>
   <td style="text-align:left;"> 2023-06-12 08:18:33 </td>
   <td style="text-align:left;"> What one key business indicator is saying about China's consumer recovery </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                      , Loans                                                                                                                                                                                                                                                                                             , Banking                                                                                                                                                                                                                                                                                           , Mortgages                                                                                                                                                                                                                                                                                         , Insurance                                                                                                                                                                                                                                                                                         , Credit Monitoring                                                                                                                                                                                                                                                                                 , Personal Finance                                                                                                                                                                                                                                                                                  , Small Business                                                                                                                                                                                                                                                                                    , Taxes                                                                                                                                                                                                                                                                                             , Help for Low Credit Scores                                                                                                                                                                                                                                                                        , Investing                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                            , All Credit Cards                                                                                                                                                                                                                                                                                  , Find the Credit Card for You                                                                                                                                                                                                                                                                      , Best Credit Cards                                                                                                                                                                                                                                                                                 , Best Rewards Credit Cards                                                                                                                                                                                                                                                                         , Best Travel Credit Cards                                                                                                                                                                                                                                                                          , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                          , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                       , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                  , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                            , All Loans                                                                                                                                                                                                                                                                                         , Find the Best Personal Loan for You                                                                                                                                                                                                                                                               , Best Personal Loans                                                                                                                                                                                                                                                                               , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                     , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                          , Best Loans with Fast Funding                                                                                                                                                                                                                                                                      , Best Small Personal Loans                                                                                                                                                                                                                                                                         , Best Large Personal Loans                                                                                                                                                                                                                                                                         , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                               , Best Student Loan Refinance                                                                                                                                                                                                                                                                       , SELECT                                                                                                                                                                                                                                                                                            , All Banking                                                                                                                                                                                                                                                                                       , Find the Savings Account for You                                                                                                                                                                                                                                                                  , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                  , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                    , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                   , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                     , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                , Best Checking Account Bonuses                                                                                                                                                                                                                                                                     , Best Money Market Accounts                                                                                                                                                                                                                                                                        , Best CDs                                                                                                                                                                                                                                                                                          , Best Credit Unions                                                                                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                                                                            , All Mortgages                                                                                                                                                                                                                                                                                     , Best Mortgages                                                                                                                                                                                                                                                                                    , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                             , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                            , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                           , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                         , Affording a Mortgage                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                            , All Insurance                                                                                                                                                                                                                                                                                     , Best Life Insurance                                                                                                                                                                                                                                                                               , Best Homeowners Insurance                                                                                                                                                                                                                                                                         , Best Renters Insurance                                                                                                                                                                                                                                                                            , Best Car Insurance                                                                                                                                                                                                                                                                                , Travel Insurance                                                                                                                                                                                                                                                                                  , SELECT                                                                                                                                                                                                                                                                                            , All Credit Monitoring                                                                                                                                                                                                                                                                             , Best Credit Monitoring Services                                                                                                                                                                                                                                                                   , Best Identity Theft Protection                                                                                                                                                                                                                                                                    , How to Boost Your Credit Score                                                                                                                                                                                                                                                                    , Credit Repair Services                                                                                                                                                                                                                                                                            , SELECT                                                                                                                                                                                                                                                                                            , All Personal Finance                                                                                                                                                                                                                                                                              , Best Budgeting Apps                                                                                                                                                                                                                                                                               , Best Expense Tracker Apps                                                                                                                                                                                                                                                                         , Best Money Transfer Apps                                                                                                                                                                                                                                                                          , Best Resale Apps and Sites                                                                                                                                                                                                                                                                        , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                     , Best Debt Relief                                                                                                                                                                                                                                                                                  , SELECT                                                                                                                                                                                                                                                                                            , All Small Business                                                                                                                                                                                                                                                                                , Best Small Business Savings Accounts                                                                                                                                                                                                                                                              , Best Small Business Checking Accounts                                                                                                                                                                                                                                                             , Best Credit Cards for Small Business                                                                                                                                                                                                                                                              , Best Small Business Loans                                                                                                                                                                                                                                                                         , Best Tax Software for Small Business                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                            , All Taxes                                                                                                                                                                                                                                                                                         , Best Tax Software                                                                                                                                                                                                                                                                                 , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                            , Tax Refunds                                                                                                                                                                                                                                                                                       , SELECT                                                                                                                                                                                                                                                                                            , All Help for Low Credit Scores                                                                                                                                                                                                                                                                    , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                  , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                      , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                           , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                             , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                      , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                      , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                     , Best Hardship Loans                                                                                                                                                                                                                                                                               , How to Boost Your Credit Score                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                            , All Investing                                                                                                                                                                                                                                                                                     , Best IRA Accounts                                                                                                                                                                                                                                                                                 , Best Roth IRA Accounts                                                                                                                                                                                                                                                                            , Best Investing Apps                                                                                                                                                                                                                                                                               , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                 , Best Robo-Advisors                                                                                                                                                                                                                                                                                , Index Funds                                                                                                                                                                                                                                                                                       , Mutual Funds                                                                                                                                                                                                                                                                                      , ETFs                                                                                                                                                                                                                                                                                              , Bonds                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                   , BEIJING — Businesses in China are spending cautiously on advertising this year as local consumption isn't expected to bounce back for a while yet.                                                                                                                                                , Marketing revenue rose in the first three months of 2023 for several Chinese internet giants — but not Alibaba, the largest of them all by dollar value. That's on a year-on-year basis.                                                                                                          , Heading into the 618 shopping festival this month, brands remain cautious.                                                                                                                                                                                                                        , "For 618, generally of course brands will be trying, but compared to before it's a bit more tired," said Ashley Dudarenok, founder of ChoZan, a China marketing consultancy.                                                                                                                      , "We know it takes exactly the same amount of money to bring the customer into your shop today versus 2021, but the customer is going to spend about 30% less in your shop," she said.                                                                                                             , In the first quarter, the median disposable income of urban residents in China was officially 12,175 Chinese yuan ($1,739), up 3.9% from a year ago. Education, health care and travel were the top three categories for planned spending, a central bank survey found.                           , "The general consensus in the industry is that 2024 is going to be the year of growth and rebound," Dudarenok said. "2023, let's just get out of the downturn, stay connected with the platforms, with the customer," she said.                                                                   , Dudarenok noted that ad agencies are also spending just to experiment with search engines. Baidu and Microsoft's Bing have both been working with new generative artificial intelligence technology.                                                                                              , Sluggish economic growth and uncertainty about future income have weighed on Chinese consumer spending since the Covid-19 pandemic. In the absence of national stimulus checks, retail sales have rebounded moderately in the first four months of this year. Figures for May are due out June 15., This year, consumers in China are looking to buy better quality products — and get more value for their money, said Dave Xie, principal at consultancy Oliver Wyman focusing on China's retail sector.                                                                                            , He pointed out that by promoting product functionality and affordability around the 618 shopping festival, domestic cosmetics brands have expanded their market share versus international brands.                                                                                                , When asked Tuesday about the outlook for the Chinese consumer this year, a JD Retail representative said growth may be bumpy.                                                                                                                                                                     , Companies are also seeing different results by platform, as online shopping trends shift.                                                                                                                                                                                                         , Brands are keen to spend more on ByteDance's Douyin, likely taking away from ad spending on Alibaba's Taobao and Tmall e-commerce platforms, Oliver Wyman's Xie said.                                                                                                                             , ByteDance isn't publicly listed and doesn't frequently disclose detailed numbers.                                                                                                                                                                                                                 , Among major U.S.-listed Chinese internet platforms, Pinduoduo saw the biggest year-on-year increase in revenue from ad sales in the first quarter. The company operates a group-buying app known for bargain discounts. That growth is likely a sign that locals aren't willing to shell out.     , "Lots of people around me are using Pinduoduo," said Sun Hao, partner at Beijing-based Goodidea Growth Network, a media group whose website lists Nestle, P&amp;G and Tmall among its clients.                                                                                                        , He also noted "significant" growth for the Little Red Book, or Xiaohongshu, app since its users tend to be mothers and white-collar workers in cities with spending power. The app isn't publicly traded.                                                                                         , However, Sun said that many brands didn't meet their performance targets in the first quarter and his sense was that overall ad budgets were contracting, especially for traditional media.                                                                                                       , And for brands spending on Douyin, he said the return on investment per ad dollar was getting lower.                                                                                                                                                                                              , The end of China's strict Covid controls and the pandemic itself have undoubtedly boosted travel and in-person events. Travel booking site Trip.com said it doubled its spending on sales and marketing in the first quarter to 1.8 billion yuan ($256 million).                                  , For iQiyi, nicknamed the "Netflix" of China, offline marketing has become more important since China's reopening due to the recovery in foot traffic, according to branding director Kelly Shi. The company has used billboards and interactive experiences to promote its content.               , IQiyi's selling, general and administrative expenses surged by 48% in the first quarter from a year ago to 1.1 billion yuan "primarily due to higher marketing spending," a release said.                                                                                                         , Bernstein says buy this China-based personal finance stock that can rally nearly 60%                                                                                                                                                                                                              , Morgan Stanley names 2 chip stocks with 'significant upside' as China bans Micron                                                                                                                                                                                                                 , This fund puts a spin on emerging markets investing with bets from Nvidia to Chinese spirits                                                                                                                                                                                                      , Slower growth in China's domestic market is pushing more local consumer companies to look overseas — sometimes by acquiring or merging with other brands.                                                                                                                                         , Largely thanks to that strategy, China-based consumer product companies saw the fastest growth among Asia-Pacific peers in international revenue over the past decade, according to a Bain &amp; Company report released in late May.                                                                 , More China overseas deal activity is expected in the next six to 18 months, said Philip Leung, Shanghai-based leader of Bain's Asia-Pacific M&amp;A practice.                                                                                                                                         , For many China-based companies, he said the strategy is now to acquire brands so they can benefit from both the overseas market and in China.                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                  , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/construction-pmi </td>
   <td style="text-align:left;"> 2023-06-12 08:08:00 </td>
   <td style="text-align:left;"> Irish Construction Output Shrinks at Softer Pace </td>
   <td style="text-align:left;"> The BNP Paribas Real Estate Construction PMI in Ireland increased to 49.4 in May 2023 from April’s three-month low of 48.4, as new orders, employment, and purchasing grew faster. The latest reading pointed to an eighth fall in construction activity levels, albeit only slight, as the decline in housing activity eased while commercial activity strengthened. The sustained growth in new orders for a fourth month droved the firms to uplift their staffing level for the fifth successive period. Meanwhile, the latest lengthened vendor performance was the least pronounced since November 2017. On prices, input cost inflation dropped to the lowest since August 2020, while output cost inflation slowed the most in 26 months. Finally, sentiment improved to the second-highest since February 2022 amid hopes for a consistent rise in market demand boosted by development activity, higher volumes of renewable energy projects, and a payoff from new business strategies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 08:03:58 </td>
   <td style="text-align:left;"> US Futures Edge Up Ahead of Busy Week </td>
   <td style="text-align:left;"> US stock futures edged higher on Monday as investors brace for the latest inflation data and the Federal Reserve’s policy meeting this week. Futures contracts tied to the three major indexes were all up at least 0.1%. Last week, the major averages finished slightly higher, with the Dow rising 0.34%, while the S&amp;P 500 and Nasdaq Composite gained 0.39% and 0.14%, respectively. A broader participation outside of mega-cap technology names was seen last week, with the consumer cyclical, energy, utilities, industrials and financial sectors outperforming the market. Investors are hopeful that inflationary pressures would show further signs of easing, supporting the case for a pause in the Fed’s interest rate hikes this week and maybe even in July. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2023-06-12 07:09:00 </td>
   <td style="text-align:left;"> New Zealand Stocks Fall for 6th Session </td>
   <td style="text-align:left;"> Equities in New Zealand dropped 25.27 or 0.22% to 11,665.07 in early trade on Monday, retreating for the 6th straight session while staying at their lowest in over two months, amid caution ahead of the release of domestic GDP reading this week. Several economists forecast that the economy had already been in recession. Meantime, Fitch Ratings revised downward its projections on the country's GDP growth this year to 0.8% from December's forecasts of 1%. On top of that, the banking sector in New Zealand is expected to deteriorate, pressured by earnings and asset quality. Market participants also awaited US May inflation for clues on the Fed's future monetary policy. Back at home, electric retail card spending growth rose by 3.3% yoy in May, easing sharply from a 6.4% gain in April. Financials, consumer services, and real estate mainly fell, with notable losses from Fisher &amp; Paykel, (-0.72%), Freightways Group (-0.57%), Meridien Energy (-0.47%), and Mainfreight Ltd. (-0.43%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/credit-card-spending </td>
   <td style="text-align:left;"> 2023-06-12 06:58:52 </td>
   <td style="text-align:left;"> New Zealand Credit Card Spending Eases in May </td>
   <td style="text-align:left;"> Electronic card transactions in New Zealand rose by 3.3 percent year-on-year to NZD 6,374 in May 2023, following a 6.4 percent advance in the previous month. On a seasonally monthly basis, electronic card spending went down 1.7 percent, after a 0.4 percent increase. Spending fell across all retail industries, including consumables, durables, apparel, fuel, and motor vehicles, as well as the non-retail excluding services category. Services was the only industry that saw an increase, rising $1.4 million, or 0.4 percent. “This is the first time since December 2022 that only one industry saw a rise in spending, and the first time since February this year that total card spending fell,” business performance manager Ricky Ho said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/11/business/media/unabomber-manifesto-ethics-journalism.html </td>
   <td style="text-align:left;"> 2023-06-12 06:18:12 </td>
   <td style="text-align:left;"> Newspapers Printed Unabomber’s Manifesto in 1995. It’s Still Fiercely Debated. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , It wouldn’t be the last time the media would grapple with whether to publish something that might inspire others to take harmful actions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Lydia DePillis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , In June 1995, hefty packages arrived in the mail rooms of The Washington Post and The New York Times with identical contents: single-space typed copies of a document called “Industrial Society and Its Future,” with a note from an anonymous sender who said he would kill again unless the newspapers published the manifesto in its entirety within 90 days.                                                                                                                                                                                                                                                                                                                                                                     , The danger seemed credible. The author claimed to have been responsible for three deaths and dozens of injuries in a mail bombing campaign that had already lasted 17 years, and was increasing in frequency. But if they gave in to the threat, how did the newspapers know the bomber would keep his word — or whether other terrorists would make such demands in the future?In September of that year, at the urging of the Justice Department and the Federal Bureau of Investigation, the newspapers decided to publish. Because of its weekday printing capabilities, The Post ran the manifesto as an eight-page insert to distinguish it from the regular news and opinion sections; The Times covered half The Post’s costs., The manifesto provided critical clues to his identity, and six months and two weeks later, the Unabomber — Theodore Kaczynski, who died in a federal prison cell on Saturday — was captured. But to many in the profession, acceding to Mr. Kaczynski’s demands set a terrible precedent, undermining journalistic independence and doing the bidding of law enforcement.                                                                                                                                                                                                                                                                                                                                                             , “They don’t know who this guy is, they can’t sue him for breach of contract if he bombs again,” said Jane Kirtley, then the executive director of the Reporters Committee for Freedom of the Press, in a round-table discussion soon after the manifesto’s publication. “They really made a pact with the devil when they have no control ultimately over what he will do or not do.”                                                                                                                                                                                                                                                                                                                                                 , The Newspaper Association of America found its membership evenly divided. In a poll at the time, exactly half of the 200 publishers who responded said they would have run the manifesto, while the other half disagreed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The Times and The Post made clear it wasn’t an easy decision. They took nearly the whole 90 days allotted to think about it, and the choice wasn’t left to newsroom leaders. Instead, the newspapers’ two publishers issued a joint statement saying that they believed it could help save lives.                                                                                                                                                                                                                                                                                                                                                                                                                                     , “Neither paper has any journalistic reason to print this,” said Donald E. Graham, then publisher of The Post. Arthur Sulzberger Jr., who was the publisher of The Times, agreed. “Whether you like it or not, we’re turning our pages over to a man who has murdered people,” he said. “But I’m convinced we’re making the right choice between bad options.”                                                                                                                                                                                                                                                                                                                                                                         , After Mr. Kaczynski’s death on Saturday, Len Downie, who was the executive editor of The Post in 1995, told the newspaper that his boss was ultimately vindicated when Mr. Kaczynski’s brother recognized the phrasing and tipped off the F.B.I.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , It wasn’t the first time and wouldn’t be the last that the media has grappled with the question of whether to serve as a platform for material that might inspire others to take harmful actions, or might mislead the public. The temptation to publish can be strong, especially when the documents could garner a lot of attention and have plausible news value.                                                                                                                                                                                                                                                                                                                                                                  , BuzzFeed News reaped the traffic for publishing a dossier in 2017 that contained explosive allegations about President Donald J. Trump, for example, even though it was largely discredited years later. There is often intense interest in the manifestoes written by perpetrators of mass shootings, but news organizations now shy away from excerpting them, for fear of encouraging copycats.                                                                                                                                                                                                                                                                                                                                    , “I think today we have more conversations about minimizing harm, and I think that’s a good thing,” said Kathleen Culver, director of the Center for Journalism Ethics at the University of Wisconsin-Madison.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Even in the 1990s, Dr. Culver said, the ferocious debate in journalism circles seemed academic to much of the public, when a killer was on the loose and the newspapers might have the power to stop him. “My principal memory from the time was people outside newsrooms saying, ‘Why was this a question?’”                                                                                                                                                                                                                                                                                                                                                                                                                         , At the same time, however, newspapers have faced criticism — and sometimes lost readers’ faith — for being too close to government authorities. Insufficiently critical reporting by The Times during the months leading up to the war in Iraq in the early 2000s is one example. A second is the media’s failure to adequately scrutinize statements by police departments in the wake of protests over the killing of an unarmed Black teenager in Ferguson, Mo.                                                                                                                                                                                                                                                                    , John Watson, a journalism professor at American University’s School of Communication, said the newspapers should have allowed the Justice Department to buy an advertorial section for the manifesto, to satisfy Mr. Kaczynski’s demands while separating it from editorial decision making.                                                                                                                                                                                                                                                                                                                                                                                                                                          , “Journalists should never be seen to be on the same side as the police,” Dr. Watson said. “Their ability to be watchdogs depends on the public believing that they will never be in bed with the government, they will always be skeptical, even if it is obvious that the government is right.”                                                                                                                                                                                                                                                                                                                                                                                                                                      , Through a Times spokesperson, Mr. Sulzberger declined an interview, deferring to his comments at the time. His son, the current publisher of the Times, A.G. Sulzberger, recently published a long meditation on the meaning and value of journalistic independence. He did not respond to an email asking whether he would have made the same decision as his father.                                                                                                                                                                                                                                                                                                                                                                , Lydia DePillis is a reporter on the Business desk who covers the changing American economy and what it means for peoples’ lives.  @lydiadepillis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/saudi-arabia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-11 14:14:00 </td>
   <td style="text-align:left;"> Saudi Arabia Industrial Output Growth at 23-Month Low </td>
   <td style="text-align:left;"> Industrial production in Saudi Arabia increased by 3.2% year-on-year in April 2023, slowing from a 4.1% gain in March. While pointing to the 24th straight month of expansion, the latest result was the softest since May 2021 amid a notable slowdown in mining and quarrying output (0.2% vs 1.6% in March) as the country raised its oil production to more than 10 million barrels per day. Meanwhile, manufacturing grew by 10.5%, the same pace as in March. At the same time, electricity and gas supplies rose by 25.5%, much faster than a 16.6% advance in March. On a monthly basis, industrial production fell by 0.3%, the first decline in four months and following a 0.2% growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/10/money-20/20-2023-whats-hot-and-whats-not-in-fintech.html </td>
   <td style="text-align:left;"> 2023-06-10 19:58:30 </td>
   <td style="text-align:left;"> Here's what's hot — and what's not — in fintech right now </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                     , Loans                                                                                                                                                                                                                                                                                                                                                                                                            , Banking                                                                                                                                                                                                                                                                                                                                                                                                          , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                        , Insurance                                                                                                                                                                                                                                                                                                                                                                                                        , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                 , Small Business                                                                                                                                                                                                                                                                                                                                                                                                   , Taxes                                                                                                                                                                                                                                                                                                                                                                                                            , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                       , Investing                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                 , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                        , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                         , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                         , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                               , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                      , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                 , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                              , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                              , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                    , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                         , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                     , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                        , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                        , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                              , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Banking                                                                                                                                                                                                                                                                                                                                                                                                      , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                 , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                 , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                   , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                  , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                    , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                               , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                    , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                       , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                         , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                    , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                   , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                               , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                           , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                          , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                        , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                    , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                              , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                        , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                           , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                               , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                  , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                   , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                   , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                             , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                              , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                        , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                         , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                       , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                    , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Small Business                                                                                                                                                                                                                                                                                                                                                                                               , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                             , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                             , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                           , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                   , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                 , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                               , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                          , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                            , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                     , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                    , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                              , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                                                                                                                                                                                           , All Investing                                                                                                                                                                                                                                                                                                                                                                                                    , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                           , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                              , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                               , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                      , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                     , ETFs                                                                                                                                                                                                                                                                                                                                                                                                             , Bonds                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                  , AMSTERDAM, Netherlands — At last year's Money 20/20 — Europe's marquee event for the financial technology industry — investors and industry insiders were abuzz with talk about embedded finance, open banking, and banking-as-a-service.                                                                                                                                                                        , As nebulous as these terms may be, they reflected a very real push from tech startups, including the biggest names in the business such as Stripe and Starling Bank, to allow businesses of all stripes to develop their own financial services, or integrate other firms' products into their platforms.                                                                                                        , This year, with fintechs and their mainly venture capital and private-equity backers reeling from a dire slump in technology valuations and softer consumer spending, the narrative around what's "hot" in fintech hasn't changed an awful lot.                                                                                                                                                                  , Investors still love companies offering services to enterprises rather than consumers. In some cases, they've been willing to write checks for firms at valuations unchanged from their last funding round. But there are a few key differences — not least the thing of curiosity that is generative artificial intelligence.                                                                                   , So what's hot in fintech right now? And what's not? CNBC spoke to some of the top industry insiders at Money 20/20 in Amsterdam. Here's what they had to say.                                                                                                                                                                                                                                                    , Looking around Money 20/20 this week, it was easy to see a clear trend going on. Business-facing or business-to-business companies like Airwallex, Payoneer, and ClearBank, dominated the show floor, while consumer apps such as Revolut, Starling, and N26 were nowhere to be found.                                                                                                                           , "I think many fintechs have pivoted to enterprise sales having found consumer hard to make sufficient unit economics — plus it's pretty expensive to get a stand and attend M2020 so you need to be selling to other attendees to justify the outlay," Richard Davies, CEO of U.K. startup lender Allica Bank, told CNBC.                                                                                        , "B2B is definitely in good shape — both SME and enterprise SaaS [software-as-a-service] — providing you can demonstrate your products and services, have proven customer demand, and good unit economics. Embedded finance certainly is part of this and has a long way to run as it is in its infancy in most cases," Davies said.                                                                              , B2B fintechs are startups that develop digital financial products tailored to businesses. SaaS is software that tech firms sell to their customers as a subscription. Embedded finance refers to the idea of third-party financial services like bank accounts, brokerage accounts and insurance policies being integrated into other businesses' platforms.                                                     , Niklas Guske, who runs operations at Taktile — a fintech start-up focused on streamlining underwriting decisions for enterprise clients — describes the sector as being in the middle of a renaissance for B2B payments and financing.                                                                                                                                                                           , "There is a huge opportunity to take lessons from B2C fintechs to uplevel the B2B user experience and deliver far better solutions for customers," said Guske. "This is particularly true in SME finance, which is traditionally underserved because it has historically been difficult to accurately assess the performance of younger or smaller companies."                                                   , One area fintech companies are getting excited by is an improvement to online checkout tools. Payments technology company Stripe, for instance, says a newer version of its checkout surfaces has helped customers increase revenue by 10.5%.                                                                                                                                                                    , "That is kind of incredible," David Singleton, chief technology officer of Stripe, told CNBC. "There are not a lot of things you can do in a business that increase your revenue by 10%."                                                                                                                                                                                                                        , Meanwhile, companies tightening their belts at the event is also a theme.                                                                                                                                                                                                                                                                                                                                        , One employee of a major firm that usually attends the event said they have cut down on the number of people they have sent to Money 20/20 and have not even bought a stand. The employee was not authorized to speak to the media.                                                                                                                                                                               , Indeed, as companies look to scale as they cut back on spending, many say a key priority is adequately managing risk.                                                                                                                                                                                                                                                                                            , "When funds were readily available, many fintechs could subsidize poor risk assessments with investor money," Guske said of the sector, adding that in today's climate, fintechs are only profitable if they can identify and secure the right customers.                                                                                                                                                        , "This is another moment where the proliferation of new data sources and the adoption of sophisticated risk modeling enables fintechs to better target their ideal customers better than ever before," said Guske, who raised more than $24 million from the likes of Y Combinator and Tiger Global.                                                                                                              , The main area that drew the most hype from Money 20/20 attendees, however, was artificial intelligence.                                                                                                                                                                                                                                                                                                          , That's as ChatGPT, the popular generative AI software from OpenAI which produces human-like responses to user queries, dazzled fintech and banking leaders looking to understand its potential.                                                                                                                                                                                                                  , In a closed-door session on the application of fintech in AI Wednesday, one startup boss pitched how they're using the technology to be more creative in communications with their customers by incorporating memes into the chat function and allowing its chatbot, Cleo, to "roast" users about poor spending decisions.                                                                                       , Callan Carvey, global head of operations at Cleo, said the firm's AI connects to a customer's bank account to get a better understanding of their financial behavior.                                                                                                                                                                                                                                            , "It powers our transaction understanding and that deeply personalized financial advice," Carvey said during her talk. "It also allows us to leverage AI and have predictive measures to help you avoid future financial mistakes," such as avoiding punchy bank fees you could otherwise avoid.                                                                                                                  , Teo Blidarus, CEO and co-founder of financial infrastructure firm FintechOS, said generative AI has been a boon to platforms like his, where companies can build their own financial services with little technical experience.                                                                                                                                                                                  , "AI, and particularly generative AI, it's a big enabler for fintech enablement infrastructure, because if you're looking at what are the barriers that low code, no code on one side and generative AI on the other are trying to solve if the complexity of the overall infrastructure," he told CNBC.                                                                                                          , "A job that typically would take around one or two weeks can now be completed in 30 minutes, right. Granted, you still need to polish it a little bit, but fundamentally I think it allows you know to spend your time on more productive stuff — creative stuff, rather than integration work."                                                                                                                 , As businesses hyper-focus on how they can do more with less, both tech-forward and traditional businesses say they have been turning to revenue and finance automation products that handle back-office operations to try to optimize efficiency.                                                                                                                                                                , Indeed, Taktile's Guske notes that the current demand to continue scaling rapidly while simultaneously reducing costs has driven many fintechs to reduce operational expenses and improve efficiency through an increase in automation and reducing manual processes, especially in onboarding and underwriting.                                                                                                 , "I see the biggest, actual application of generative AI in using it to create signals out of raw transaction or accounting data," said Guske.                                                                                                                                                                                                                                                                    , One thing's for sure: consumer-oriented services aren't the ones getting the love from investors.                                                                                                                                                                                                                                                                                                                , This year has seen major digital banking groups and payment groups suffer steep drops in their valuations as shareholders reevaluated their business models in the face of climbing inflation and higher interest rates.                                                                                                                                                                                         , Revolut, the British foreign exchange services giant, had its valuation cut by shareholder Schroders Capital by 46%, implying a $15 billion markdown in its valuation from $33 billion, according to a filing. Atom Bank, a U.K. challenger bank, had its valuation marked down 31% by Schroders.                                                                                                                , It comes as investment into European tech startups is on track to fall another 39% this year, from $83 billion in 2022 to $51 billion in 2023, according to venture capital firm Atomico.                                                                                                                                                                                                                        , "No one comes to these events to open like a new bank account, right?" Hiroki Takeuchi, CEO of GoCardless, told CNBC. "So if I'm Revolut, or something like that, then I'm much more focused on how I get my customers and how I make them happy. How do I get more of them? How do I grow them?"                                                                                                                , "I don't think Money 20/20 really helps with that. So that doesn't surprise me that there's more of a shift towards B2B stuff," said Takeuchi.                                                                                                                                                                                                                                                                   , Layoffs have also been a massive source of pain for the industry, with Zepz, the U.K. money transfer firm, cutting 26% of its workforce last month.                                                                                                                                                                                                                                                              , Even once richly valued business-focused fintechs have suffered, with Stripe announcing a $6.5 billion fundraise at a $50 billion valuation — a 50% discount to its last round — and Checkout.com experiencing a 15% drop in its internal valuation to $9 billion, according to startup news site Sifted.                                                                                                        , As Money 20/20 kicked off, the U.S. Securities and Exchange Commission sued crypto exchange Binance and its founder Changpeng Zhao for securities violations. Shortly after, the SEC sued U.S. firm Coinbase alleging it is acting as an unregistered broker and exchange.                                                                                                                                       , It comes after a turbulent year for the crypto industry which has seen failed projects and companies go bankrupt — likely a big part of why few crypto firms made an appearance in Amsterdam this year.                                                                                                                                                                                                          , During the height of the most recent bull run, digital asset companies and know-your-customer providers dominated a lot of the Money 20/20 expo hall, but conference organizers tell CNBC that just 6% of revenue came from companies with a crypto affiliation.                                                                                                                                                 , Plunging liquidity in the crypto market, paired with a regulatory crackdown in the U.S. on firms and banks doing business with the crypto sector, have altered the value proposition for investing in digital asset integrations. Several fintech executives CNBC interviewed spoke of how they're not interested in launching products tailored to crypto as the demand from their customers isn't there.       , Airwallex, a cross-border payments start-up, partners with banks and is regulated in various countries. Jack Zhang, the CEO of Airwallex, said the company will not be introducing support for cryptocurrencies in the near future, especially with the regulatory uncertainty.                                                                                                                                  , "It's very important for us to maintain the high standard of compliance and regulation … it is a real challenge right now to deal with crypto, especially with these global banks," Zhang told CNBC in an interview on Tuesday.                                                                                                                                                                                  , Prajit Nanu, CEO of Nium, a fintech company that has a product that allows financial institutions to support cryptocurrencies, said interest in that service has "fallen off."                                                                                                                                                                                                                                   , "Banks who we power today have become very skeptical about crypto … as we see the overall ecosystem going through this ... difficult time … we are looking at it much more carefully than what we would have looked at last year," Nanu told CNBC in an interview Tuesday.                                                                                                                                       , Blockchain is also no longer the buzzword it once was in fintech.                                                                                                                                                                                                                                                                                                                                                , A few years ago, the trendy thing to talk about was blockchain technology. Big banks used to say that they weren't keen on the cryptocurrency bitcoin but instead were optimistic about the underlying tech known as blockchain.                                                                                                                                                                                 , Banks praised the way the ledger technology could improve efficiency. But blockchain has barely been mentioned at Money 20/20.                                                                                                                                                                                                                                                                                   , One exception was JPMorgan, which is continuing to develop blockchain applications with its Onyx arm. Onyx uses the technology to create new products, platforms and marketplaces — including the bank's JPM Coin, which it uses to transfer funds between some of its institutional clients.                                                                                                                    , However, Basak Toprak, executive director of EMEA and head of coin systems at JPMorgan, gave attendees a reality check about how limited practical use of the technology is in banking at the moment.                                                                                                                                                                                                            , "I think we've seen a lot of POCs, proof of concepts, which are great at doing what it says on the tin, proving the concept. But I think, what we need to do is make sure we create commercially viable products for solving specific problems, sustain customer confidence, solving issues, and then launching a product or a way of doing things that is commercially viable, and working with the regulators.", "Sometimes I think the role of the regulators is also quite important for industry as well."                                                                                                                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                 , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/egypt/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-10 18:24:00 </td>
   <td style="text-align:left;"> Egypt Inflation Rate Above Forecasts in May </td>
   <td style="text-align:left;"> The annual urban inflation rate in Egypt accelerates to 32.7% in May 2023 from 30.6% in the previous month and above market forecasts of 31.4%, mainly due to faster rises in food inflation (60.0% vs 54.7%). Still, the figure remained well above the upper limit of the central bank’s 5-9% target range, amid the recent plunge of the currency. On a monthly basis, consumer prices climbed 2.7%, after a 1.7% rise in the previous month, which was the least in seven months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/10/business/economy/mortgage-rates-real-estate.html </td>
   <td style="text-align:left;"> 2023-06-10 17:01:05 </td>
   <td style="text-align:left;"> Mortgage Transfers Pick Up as a Way to Beat Rising Rates - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Real estate agents are pushing sub-3 percent mortgages as an amenity, just like marble countertops or a view of the mountains.                                                                                                                                                                                                                                                                                                                                                                                                   , By Conor Dougherty                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The only goal was to not lose money.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , When Matthew Kilboy listed the Washington, D.C., condominium that he and his husband had bought in 2017, they accepted that higher interest rates and a soft market for condos meant any dollar over the $529,000 they had paid was a dollar they would thank their lucky stars for.                                                                                                                                                                                                                                             , A similar two-bedroom and two-bath unit in the building had recently gone for just under half a million. The $549,000 price they listed in April was basically a wish.                                                                                                                                                                                                                                                                                                                                                           , A month later, the couple closed at $565,000 — thanks to a little-known amenity that has become increasingly popular as mortgage rates have risen. Their unit came with an assumable 30-year mortgage, with a 2.25 percent fixed rate that the couple had locked in after a November 2020 refinancing. By advertising that the buyer could inherit the mortgage, the couple, who have moved to Denver, got several over-asking-price bids that seemed like a relic from the warped real estate market during the Covid lockdown. , “It was the very first sentence of the listing,” said Mr. Kilboy, 39, a former Navy nurse whose loan, backed by the Department of Veterans Affairs, could be passed to the buyer. “No one could find an interest rate that low, so we were really pushing it.”                                                                                                                                                                                                                                                                   , The Federal Reserve might have slowed interest rate increases, but monthly mortgage costs remain more than double their levels from 18 months ago. This has significantly lowered the supply of for-sale inventory by discouraging the millions of homeowners who locked in bargain rates during the pandemic from selling their home and incurring potentially hundreds of dollars a month in extra borrowing costs on a new one.                                                                                               , Because so little is for sale, home prices have remained stable, and even resumed their ascent, despite a huge increase in borrowing costs. The refrain among real estate agents and economists is that anyone who secured a mortgage rate of 3 percent or lower owns a valuable asset that they are loath to give up.                                                                                                                                                                                                           , But every asset has a price. And now an emerging cadre of investors and real estate agents are trying to, in effect, sell mortgage rates from several years ago by transferring them to new buyers.                                                                                                                                                                                                                                                                                                                              , Redfin, the real estate brokerage, has seen a steep rise in listings like Mr. Kilboy’s that have comments like “beautiful home with assumable loan at 3.25 percent.” Facebook groups have popped up to find buyers for them, while new companies are pitching services to speed up the transfer.                                                                                                                                                                                                                                 , “Homeowners with mortgages that are capable of being assumed have something valuable that many home buyers want and would be willing to pay for,” said Daryl Fairweather, chief economist at Redfin. “For people who bought when home prices were near the peak but mortgage rates were still low, it may be an attractive way to get out of a remorseful purchase.”                                                                                                                                                             , Investors are just as eager: The euphemistic “creative finance” has become a huge topic of conversation on sites like BiggerPockets, a forum where landlords trade tips on topics like operating short-term rentals and buying a first investment property. In books, seminars and YouTube videos, influencers peddle advice on how to find struggling homeowners willing to transfer a low-rate mortgage without their bank’s knowledge — a valuable but immensely risky strategy that title companies say they’ve seen more of., “It’s just too appealing,” said Scott Trench, chief executive of Bigger Pockets, adding the disclaimer that many of these strategies frequently involve extra risks and paperwork that most people are unfamiliar with.                                                                                                                                                                                                                                                                                                          , From the pedestrian to the dodgy, it all seems to underscore the manner in which the nation’s real estate market has been frozen by regret. Buyers are resentful that the low-cost mortgages are gone. Sellers are reluctant to lower their prices from the peaks of the pandemic. In lieu of acceptance, a determined few are trying to use imagination and fine print to build a portal to the cheap-money days of 2021.                                                                                                       , Most U.S. mortgages are not directly assumable. However, a host of popular government-backed mortgages — such as those insured by the Federal Housing Administration, the Department of Veterans Affairs and the Department of Agriculture — typically are, said Michael Fratantoni, chief economist at the Mortgage Bankers Association. These loans are frequently used by first-time buyers and account for roughly a quarter of outstanding mortgages, according to Black Knight, a mortgage technology and data provider.   , In theory, any of the millions of homeowners holding a assumable low-rate mortgage have a valuable perk to sell with their home. Still, real estate agents say it can be hard in practice to transfer them. For instance, homeowners who transfer a V.A.-backed mortgage can lose their ability to get another similar loan unless they can find a V.A.-eligible buyer to take their original mortgage.                                                                                                                          , Or consider a homeowner who has a low-rate mortgage but has paid a chunk of it down: To assume the loan, a buyer would have to come up with a large down payment to account for the seller’s equity — something that very few people can do.                                                                                                                                                                                                                                                                                     , Craig O’Boyle is hoping to create a business making assumptions faster and easier. Mr. O’Boyle is a real estate agent who has been selling homes in Colorado for three decades, long enough that he remembers having to read through the door-stopper contracts that buyers and sellers now just click through on DocuSign. Reading over the lines about certain loans being assumable, he said, he had long thought that if rates ever spiked those owners would suddenly discover that their debts had value.                  , “And then here comes this shift in the interest rate market,” Mr. O’Boyle said.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Last year, he and a partner started Assumption Solutions, a consulting firm that, for a $1,100-per-deal processing fee, helps real estate agents navigate transferring mortgages between sellers and buyers. In his pitch to agents, Mr. O’Boyle argues that they push sub-3 percent rates as they do marble countertops or a view of the mountains.                                                                                                                                                                             , “You market this, and let’s say you’re competing against the house next door, your house should sell either faster or for more money,” he said.                                                                                                                                                                                                                                                                                                                                                                                  , Even for the vast majority of people using a conventional mortgage that can’t be transferred, some sort of rate compensation is becoming the norm. While home prices have fallen from their all-time high last June, they haven’t come down nearly enough to make up for the increase in mortgage rates, and they’re rising again.                                                                                                                                                                                               , To stimulate new loans, mortgage companies have started marketing products in which borrowers can “buy down” rates by paying several thousand dollars for a year or two of significantly lower interest. One of the more popular products is a “2/1 buydown,” in which a borrower pays for an interest rate reduction of two percentage points during the first year and one percentage point in the second.                                                                                                                     , Put simply: “Most homes are unaffordable at today’s rates,” said Luis Solis, a real estate agent in Phoenix and Portland, Ore.                                                                                                                                                                                                                                                                                                                                                                                                   , A majority of Mr. Solis’s recent deals have had some form of interest rate compensation that is a price cut in all but name, he said. Usually it’s a lump sum at closing that buyers use to buy temporarily lower rates. Sellers with a lot of equity can cut out the middleman and finance the buyer’s purchase below prevailing rates by acting as a lender — seller financing, it’s called.                                                                                                                                   , Assuming mortgages, paying down rates: These are creative but straightforward solutions to rising borrowing costs. But on the margins, a rising number of investors looking to buy homes with minimal cash are trying a gray technique of finance — known as “Subject to" or “Subto” — in which they try to find people who have fallen behind on their debts and make a side agreement to take over their (low-interest) payments. (The deal is said to be “subject to” an existing loan.)                                      , The strategy has obvious appeal when interest rates are high, but it comes with a huge asterisk: Once a home has changed hands, banks typically have the right to call the loan — that is, demand that the seller’s mortgage balance be paid in full immediately. Also, if the buyer falls behind on the payments, the property can be still foreclosed on — ruining the seller’s credit, for a home that he or she no longer owns.                                                                                              , Despite this, Bill McAfee, president of Empire Title, said he has seen an increase in customers looking to change their title under these terms, and has stock disclosures warning both sides what can go wrong.                                                                                                                                                                                                                                                                                                                 , “I’m not saying I agree with doing this, but it’s a way to get into property with very little money,” he said. “They have to figure out if it’s worth the risk.”                                                                                                                                                                                                                                                                                                                                                                 , Conor Dougherty is an economics reporter and the author of “Golden Gates: Fighting for Housing in America.” His work focuses on the West Coast, real estate and wage stagnation among U.S. workers.  @ConorDougherty                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/10/technology/ai-humanity.html </td>
   <td style="text-align:left;"> 2023-06-10 17:00:48 </td>
   <td style="text-align:left;"> How Could AI Destroy Humanity? - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                   , Researchers and industry leaders have warned that A.I. could pose an existential risk to humanity. But they’ve been light on the details.                                                                                                                                                                                                                                      , By Cade Metz                                                                                                                                                                                                                                                                                                                                                                   , Cade Metz has spent years covering the realities and myths of A.I.                                                                                                                                                                                                                                                                                                             , Last month, hundreds of well-known people in the world of artificial intelligence signed an open letter warning that A.I. could one day destroy humanity.                                                                                                                                                                                                                      , “Mitigating the risk of extinction from A.I. should be a global priority alongside other societal-scale risks, such as pandemics and nuclear war,” the one-sentence statement said.                                                                                                                                                                                            , The letter was the latest in a series of ominous warnings about A.I. that have been notably light on details. Today’s A.I. systems cannot destroy humanity. Some of them can barely add and subtract. So why are the people who know the most about A.I. so worried?                                                                                                           , One day, the tech industry’s Cassandras say, companies, governments or independent researchers could deploy powerful A.I. systems to handle everything from business to warfare. Those systems could do things that we do not want them to do. And if humans tried to interfere or shut them down, they could resist or even replicate themselves so they could keep operating., “Today’s systems are not anywhere close to posing an existential risk,” said Yoshua Bengio, a professor and A.I. researcher at the University of Montreal. “But in one, two, five years? There is too much uncertainty. That is the issue. We are not sure this won’t pass some point where things get catastrophic.”                                                          , The worriers have often used a simple metaphor. If you ask a machine to create as many paper clips as possible, they say, it could get carried away and transform everything — including humanity — into paper clip factories.                                                                                                                                                 , How does that tie into the real world — or an imagined world not too many years in the future? Companies could give A.I. systems more and more autonomy and connect them to vital infrastructure, including power grids, stock markets and military weapons. From there, they could cause problems.                                                                            , For many experts, this did not seem all that plausible until the last year or so, when companies like OpenAI demonstrated significant improvements in their technology. That showed what could be possible if A.I. continues to advance at such a rapid pace.                                                                                                                  , “A.I. will steadily be delegated, and could — as it becomes more autonomous — usurp decision making and thinking from current humans and human-run institutions,” said Anthony Aguirre, a cosmologist at the University of California, Santa Cruz and a founder of the Future of Life Institute, the organization behind one of two open letters.                              , “At some point, it would become clear that the big machine that is running society and the economy is not really under human control, nor can it be turned off, any more than the S&amp;P 500 could be shut down,” he said.                                                                                                                                                        , Or so the theory goes. Other A.I. experts believe it is a ridiculous premise.                                                                                                                                                                                                                                                                                                  , “Hypothetical is such a polite way of phrasing what I think of the existential risk talk,” said Oren Etzioni, the founding chief executive of the Allen Institute for AI, a research lab in Seattle.                                                                                                                                                                           , Not quite. But researchers are transforming chatbots like ChatGPT into systems that can take actions based on the text they generate. A project called AutoGPT is the prime example.                                                                                                                                                                                           , The idea is to give the system goals like “create a company” or “make some money.” Then it will keep looking for ways of reaching that goal, particularly if it is connected to other internet services.                                                                                                                                                                       , A system like AutoGPT can generate computer programs. If researchers give it access to a computer server, it could actually run those programs. In theory, this is a way for AutoGPT to do almost anything online — retrieve information, use applications, create new applications, even improve itself.                                                                      , Systems like AutoGPT do not work well right now. They tend to get stuck in endless loops. Researchers gave one system all the resources it needed to replicate itself. It couldn’t do it.                                                                                                                                                                                      , In time, those limitations could be fixed.                                                                                                                                                                                                                                                                                                                                     , “People are actively trying to build systems that self-improve,” said Connor Leahy, the founder of Conjecture, a company that says it wants to align A.I. technologies with human values. “Currently, this doesn’t work. But someday, it will. And we don’t know when that day is.”                                                                                            , Mr. Leahy argues that as researchers, companies and criminals give these systems goals like “make some money,” they could end up breaking into banking systems, fomenting revolution in a country where they hold oil futures or replicating themselves when someone tries to turn them off.                                                                                   , A.I. systems like ChatGPT are built on neural networks, mathematical systems that can learn skills by analyzing data.                                                                                                                                                                                                                                                          , Around 2018, companies like Google and OpenAI began building neural networks that learned from massive amounts of digital text culled from the internet. By pinpointing patterns in all this data, these systems learn to generate writing on their own, including news articles, poems, computer programs, even humanlike conversation. The result: chatbots like ChatGPT.    , Because they learn from more data than even their creators can understand, these systems also exhibit unexpected behavior. Researchers recently showed that one system was able to hire a human online to defeat a Captcha test. When the human asked if it was “a robot,” the system lied and said it was a person with a visual impairment.                                  , Some experts worry that as researchers make these systems more powerful, training them on ever larger amounts of data, they could learn more bad habits.                                                                                                                                                                                                                       , In the early 2000s, a young writer named Eliezer Yudkowsky began warning that A.I. could destroy humanity. His online posts spawned a community of believers. Called rationalists or effective altruists, this community became enormously influential in academia, government think tanks and the tech industry.                                                              , Mr. Yudkowsky and his writings played key roles in the creation of both OpenAI and DeepMind, an A.I. lab that Google acquired in 2014. And many from the community of “EAs” worked inside these labs. They believed that because they understood the dangers of A.I., they were in the best position to build it.                                                              , The two organizations that recently released open letters warning of the risks of A.I. — the Center for A.I. Safety and the Future of Life Institute — are closely tied to this movement.                                                                                                                                                                                      , The recent warnings have also come from research pioneers and industry leaders like Elon Musk, who has long warned about the risks. The latest letter was signed by Sam Altman, the chief executive of OpenAI; and Demis Hassabis, who helped found DeepMind and now oversees a new A.I. lab that combines the top researchers from DeepMind and Google.                       , Other well-respected figures signed one or both of the warning letters, including Dr. Bengio and Geoffrey Hinton, who recently stepped down as an executive and researcher at Google. In 2018, they received the Turing Award, often called “the Nobel Prize of computing,” for their work on neural networks.                                                                 , Cade Metz is a technology reporter and the author of “Genius Makers: The Mavericks Who Brought A.I. to Google, Facebook, and The World.” He covers artificial intelligence, driverless cars, robotics, virtual reality and other emerging areas.  @cademetz                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/10/business/scratch-off-lottery-ticket-home-sales.html </td>
   <td style="text-align:left;"> 2023-06-10 17:00:48 </td>
   <td style="text-align:left;"> I Won $50,000 From a Scratch-Off Lottery Ticket and Bought a House - The New York Times </td>
   <td style="text-align:left;"> , Sydney Bean was young, broke and tolerating a bad roommate to make ends meet. Then she won the lottery.                                                                                                                                                                                                                                                                                                                                                                                       , Sydney Bean bought her first home with gambling winnings.Credit...Lindsay D'Addato for The New York Times                                                                                                                                                                                                                                                                                                                                                                                     , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , By Sydney Bean                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Our downstairs neighbors had been trying to get us evicted.                                                                                                                                                                                                                                                                                                                                                                                                                                   , It was September 2021. I was 22 and working as a paraprofessional at an elementary school in Boise, Idaho, earning $9 an hour. My wages didn’t go very far there, so I found a roommate to split the $1,900 monthly rent for a two-bedroom apartment just outside the city. We had met one night when her dog, a Rottweiler mix, ran up to play with my dog, Gaspard, a Labrador husky. We were both students — I was pursuing a bachelor’s degree in finance while she was studying medicine., Things started out fine, but they quickly deteriorated in the way that commonly happens among 20-somethings who find themselves living with incompatible roommates.                                                                                                                                                                                                                                                                                                                           , Our neighbors initially had minor noise complaints, but things escalated when my roommate started having her friends over. They would get drunk, play rowdy games of Ping-Pong and blast music late into the night. My roommate would also leave her dog in a kennel for more than eight hours at a time, and the dog would howl for someone to let her out. Our neighbors were fed up with the situation and filed formal complaints with our management company to have us evicted.         , I was also fed up with our living arrangement. On top of everything else, my roommate was often behind on her bills, and I had to draw on student loans to front over $2,000 a month to keep us current on our rent and utility bills.                                                                                                                                                                                                                                                        , In an attempt to plot my escape, I searched for a pet-friendly, one-bedroom apartment for under $1,700 a month on a rental listing website, but came up empty. On Facebook Marketplace, I found a room in a cute house for only $500 a month — but then I read the description and changed my mind: “Single male with one room available for single female aged 18-35.”                                                                                                                       , Envisioning the next chapter of my life helped me cope with the stress of my current living situation. I would spend hours browsing Zillow, looking at trailer homes, duplexes and “handyman specials” for sale.                                                                                                                                                                                                                                                                              , There was no way I could afford to buy a house at the time. I wasn’t earning enough to be able to save meaningfully, and I had about $40,000 in student loan debt. But I scrolled through listings as if money wasn’t a concern, considering the qualities and trade-offs of each house. I also started using a banking app to check my credit score every week, which hovered around 750 — a score that I understood would help me get a good interest rate on a mortgage loan one day.      , Little did I know that this day would come sooner than I had ever imagined.                                                                                                                                                                                                                                                                                                                                                                                                                   , During the Christmas holidays, I loaded up my car and drove four hours with Gaspard on an icy highway to spend time with my family in Idaho Falls, Idaho. When my two brothers and sister arrived on Christmas Eve, we played a game my mother invented, “the Bucket Game.”                                                                                                                                                                                                                   , The objective is to toss a beanbag across the room into a five-gallon bucket to win a scratch-off lottery ticket. When it was time to play, we gathered in the living room and waited for my mother to bring in the $150 worth of tickets she had picked up from a gas station.                                                                                                                                                                                                               , After a few rounds, my stack of tickets was notably smaller than everyone else’s because I kept missing the bucket. When I missed again, my mother allowed me to take another turn, and when the beanbag made it in, I grabbed a $5 Silver Bells holiday scratcher and added it to my pile.                                                                                                                                                                                                   , When all the tickets were accounted for, we all sat quietly and scratched at them. Occasionally, one of us would call out a $5 or $20 win. My Silver Bells ticket had five winning numbers at the top: 47, 44, 21, 41 and 39. If you uncovered one of the numbers, you would win a prize. It wasn’t until I got to the last row of the ticket that I uncovered the number 39. Just below the number was a cash prize of $50,000. I sat there quietly, rereading the rules.                    , “I think I won,” I announced incredulously to the room.                                                                                                                                                                                                                                                                                                                                                                                                                                       , Everyone rushed over to examine the ticket and agreed that it looked like a winner, but to be sure, we all piled into a car and drove to the one gas station in town that was open on Christmas Eve. I walked up to the scanner and checked my ticket. In small letters on the blue screen was the word “Winner.”                                                                                                                                                                             , I offered to share the money with my family, but my older brother said I should keep it. He and my family were genuinely happy for me — they didn’t want a dime of my winnings. With their blessing, I knew exactly what I wanted to do with the money: buy a house.                                                                                                                                                                                                                          , I was given a check for $37,000 at the Idaho Lottery headquarters the following Monday, after I was told I could pay the taxes on the gambling winnings upfront.                                                                                                                                                                                                                                                                                                                              , The search for a house I could afford came next. All the time I had spent on Zillow in the previous months came in handy because I was familiar with the market. I knew I could afford a house between $90,000 and $150,000, but I wanted to stay on the lower end of that range. My goals were to pay the lowest monthly mortgage possible and to pay less than what I would normally spend on rent.                                                                                         , After broadening my search to include all of Idaho, I found three homes I liked in Pocatello, which I had visited a handful of times when I was child. It had a reputation for being one of the most dangerous cities in the state. A real estate agent on Zillow offered to visit the homes and give me a video tour. After he looked at the first house, he called me and said, “I will not let you live in this part of town.”                                                             , A tour of the second house was underwhelming. The third house was small, but it had a spacious yard and didn’t need any immediate repairs. It was listed for $120,000, and I told the real estate agent that I was interested.                                                                                                                                                                                                                                                                , The agent gave me contact information for a mortgage banker to get preapproved for a loan. The only difficult part of the preapproval process was income verification. Moving to Pocatello meant I would have to leave my job at the elementary school, which I loved. To meet the income requirements, I instead found work in sales at a call center for $15 an hour. With my credit rating, new source of income and down payment, I was able to get preapproved for a $150,000 loan.      , When I went to Pocatello to see the house in person on a snowy day, I fell in love with it immediately. It was 100 years old and 700 square feet — a perfect size for Gaspard and me. The front yard and backyard were spacious, and the bathroom had a lavender tub. The floors were a little slanted, but the quirks made me want the home.                                                                                                                                                 , The real estate agent offered $117,000 with $3,000 in earnest money (a good faith deposit). My down payment was $23,000. A home inspector looked at the house to ensure it was sound. The banker I worked with spoke on the phone with me regularly and answered all of my questions. He explained that interest rates would be spiking in the near future, so it was good that I was buying now. My mortgage has an interest rate of 3.375 percent and a monthly payment of $591.            , I gave my roommate one month’s notice that I would be moving out. She was upset and rebuffed my offer to help her find a new roommate, but it was for the best.                                                                                                                                                                                                                                                                                                                               , After moving expenses, I had $7,000 of my winnings left in savings, and I settled into my new house five weeks after winning the lottery.                                                                                                                                                                                                                                                                                                                                                     , I’m now 24, and I will graduate with a degree in finance and marketing from Idaho State University in the fall. I quit my job at the call center. Instead, I earn about $5,000 a month from the videos I make on TikTok, where I have grown a following by telling stories about my life.                                                                                                                                                                                                     , It feels impossible for the majority of people in their 20s to become homeowners. The cost of living is far too high and it can be difficult for young people to get ahead no matter how hard they work and try to save. If I hadn’t won the money, it would have taken me years to buy a house and it’s hard to say whether I would have gotten a good interest rate on a loan or an affordable monthly payment.                                                                             , Gaspard has a younger brother now: a 1-year-old Labrador husky named Garbanzo. We love living in Pocatello, where the people are kind and where there are beautiful hills, mountains and accessible trails. I never imagined I could feel so at home.                                                                                                                                                                                                                                         , Advertisement </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2023-06-12 23:50:13 UTC +8

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
   <td style="text-align:left;"> 2023-06-12 23:49:44 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $nvda $aapl

CPI tomorrow est 4.1% YoY 

WHAT IS YOUR CPI NUMBER FOR TOMORROW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:49:14 </td>
   <td style="text-align:left;"> $SPY bears scared to post and are out of moneys to play anyways </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:49:14 </td>
   <td style="text-align:left;"> $SPY 432.4 resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:49:03 </td>
   <td style="text-align:left;"> $SPY $QQQ DeepMind CEO - &amp;#39;AI could cure cancer.&amp;#39; NVDA, MSFT, etc. for now, can&amp;#39;t wait to see the 1,000+ AI IPOs I&amp;#39;m guessing are in the pipelines perhaps starting this Fall, TBD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:54 </td>
   <td style="text-align:left;"> $SPY it’s going to pump today and dump tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:54 </td>
   <td style="text-align:left;"> $SPY thank you bears for being so bearish this year! I wouldn&amp;#39;t have made so much money this year without you! Lots of love 💕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:26 </td>
   <td style="text-align:left;"> $SPY I don’t think it’s over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:23 </td>
   <td style="text-align:left;"> $RUM latex3c676ac754ccb4f6bbc238feea7e2ad7 head in the dirt. 
 
The market is NOT controlled by companies. 
 
Just learn that you might stop failing 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:16 </td>
   <td style="text-align:left;"> $SPY $435?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:16 </td>
   <td style="text-align:left;"> $SPY finally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:08 </td>
   <td style="text-align:left;"> $SPY semis is holding this PoS up. Its ovah tmw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:48:07 </td>
   <td style="text-align:left;"> $SPY I don’t always love bull markets, but when I do, I love them with multiple bank failures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:38 </td>
   <td style="text-align:left;"> $SPY let’s go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:33 </td>
   <td style="text-align:left;"> $SPY is about to POP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:22 </td>
   <td style="text-align:left;"> $SPY we have the classic meltup underway .. shorts are absolutely fooked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:20 </td>
   <td style="text-align:left;"> $SPY nickname of this market is “Grift Central” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:14 </td>
   <td style="text-align:left;"> $SPY The-fact everyone is bearish is your signal togo long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:13 </td>
   <td style="text-align:left;"> $SPY puts are dirt cheap after this last pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:12 </td>
   <td style="text-align:left;"> $SPY $QQQ market has lost its mind with hype… inflation numbers out tomorrow… will be RED BIGLY!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:11 </td>
   <td style="text-align:left;"> $SPY - $431 CALLS 0DTE .60

CHEAP LOTTO PLAY, HERO OR ZERO 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:11 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:08 </td>
   <td style="text-align:left;"> $SPY this will go down several bucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:02 </td>
   <td style="text-align:left;"> $SPY this won’t last the spy always favors green for some reason </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:01 </td>
   <td style="text-align:left;"> $SPY vix is fake news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:47:00 </td>
   <td style="text-align:left;"> $SPY $QQQ  
WTF  is  TA?   You  Sheeps  believe  anything  
Over  sold  does  not  exist.  This  is  a  Joe  Biden  Market  #VoteBlue  
Buy  in  June  and  Hold!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:45 </td>
   <td style="text-align:left;"> $SPY 10 years from now, this is going to $_____ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:39 </td>
   <td style="text-align:left;"> $SPY VIX shooting up again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:19 </td>
   <td style="text-align:left;"> $SPY 440 before 240? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:17 </td>
   <td style="text-align:left;"> $SPY poor doomturds about to lose their box as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:17 </td>
   <td style="text-align:left;"> $SPY $434 still has a chance! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:12 </td>
   <td style="text-align:left;"> $SPY VIX going to 8 and you will never see SPY below 420 again. 440 EOW , calling it now . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:08 </td>
   <td style="text-align:left;"> $SPY the S&amp;amp;P is always oversold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:46:08 </td>
   <td style="text-align:left;"> $SPY The S&amp;amp;P 7 is holding this up. the other 493 are garbage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:45:46 </td>
   <td style="text-align:left;"> $SPY 2 cubs riding the green slide down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:45:32 </td>
   <td style="text-align:left;"> $SPY TRILLIONS INTO THE SAME 7 STOCKS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:45:30 </td>
   <td style="text-align:left;"> $SPY lol regional banks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:45:29 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AMZN &amp;lt;&amp;gt;&amp;lt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:45:23 </td>
   <td style="text-align:left;"> $HIMX BUY BUY BUY $AMD $TSM $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:45:06 </td>
   <td style="text-align:left;"> $SPY bears keep talking is entertaining 🤡🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:55 </td>
   <td style="text-align:left;"> $SPY literally, the recession is over. Bull market roaring 20’s 2.0. 

Prosperity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:53 </td>
   <td style="text-align:left;"> $SPY bye bye $430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:49 </td>
   <td style="text-align:left;"> $SPY this has been the most retarded 3 weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:40 </td>
   <td style="text-align:left;"> @nytrader60 @NODOUT $SPY You owe NyTrader60 an apology. 
 
1. you have no idea what he posted. 
 
2. your shit gamble long Puts is losing $$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:35 </td>
   <td style="text-align:left;"> $SPY fat sell incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:22 </td>
   <td style="text-align:left;"> $SPY moar oversold than Foley catheters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:17 </td>
   <td style="text-align:left;"> $SPY JUST SAD ♻️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:06 </td>
   <td style="text-align:left;"> $SPY bears about to get obliterated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:44:02 </td>
   <td style="text-align:left;"> $SPY 

Continue to sell and I shall buy at these levels old Obie One Konobi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:56 </td>
   <td style="text-align:left;"> $SPY crazy to see this kind of buying going into cpi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:42 </td>
   <td style="text-align:left;"> $SPY is facing a lot of positive pressure with an imbalance of 2.1 M. Learn more about net option delta  https://tinyurl.com/y6ozf3by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:36 </td>
   <td style="text-align:left;"> $DIA $SPY $IWM U.S. May CPI (Tuesday) is the last big number that could influence Wednesday&amp;#39;s decision at the margin. A hotter number could tip the scales in favor of a rate hike, while a softer report could allow the FOMC room to step to the sidelines after 500 bps in hikes since the March 4, 2022. Analysts expect gains of 0.2% for the headline and 0.4% for the core after April pops of 0.4% for both. As-expected figures would result headline inflation slowing to a 4.2% y/y from 4.9% in April, and the core rate sliding to 5.2% y/y from 5.5%. Such figures, move than 2X the 2% inflation goal would suggest a data-dependent Fed would have to continue its rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:30 </td>
   <td style="text-align:left;"> $SPY 422-424 gap still never filled will be this week fellas! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:22 </td>
   <td style="text-align:left;"> $SPY all time high in a month or two. Watch it… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:19 </td>
   <td style="text-align:left;"> Stocks open higher to kick off key week for US economy: Stock market news today

https://finance.yahoo.com/news/stocks-open-higher-to-kick-off-key-week-for-us-economy-stock-market-news-today-110707386.html

$QQQ $TQQQ $SQQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:43:13 </td>
   <td style="text-align:left;"> $SPY  this market is checkers not chess - just buy calls at 7:20 everyday - nothing but higher lows from 7:30 on out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:55 </td>
   <td style="text-align:left;"> $SPY Lunch time runner? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:55 </td>
   <td style="text-align:left;"> $SPY pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:51 </td>
   <td style="text-align:left;"> $SPY 4300 puts are already WORTHLESS. that&amp;#39;s how u know its going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:45 </td>
   <td style="text-align:left;"> $SPY get past 431 pls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:45 </td>
   <td style="text-align:left;"> $SPY when tech stalls, Dow goes up. Understand the game… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:41 </td>
   <td style="text-align:left;"> $SPY -15% correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:35 </td>
   <td style="text-align:left;"> $SPY THEY ARE PAMPING ALL THE BS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:22 </td>
   <td style="text-align:left;"> $SPY 

Without size there is no prize </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:41:12 </td>
   <td style="text-align:left;"> $SPY NEVER short a dull market! Its the summertime. stocks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:40:57 </td>
   <td style="text-align:left;"> $KEY next bank on the down tread. 

WILL $JPM turns it&amp;#39;s eyes to another small bank? 

$PACW $WAL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:40:20 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ Remember boys and girls, always be bullish. 2 year ripping? Who cares. DXY higher? Doesn&amp;#39;t matter. Equities sitting at resistance for days. Whatever. IV out of control after massive runs higher and would need huge moves to justify call options? Buy &amp;#39;em anyway you pussy! CPI coming out tomorrow? TO THE MOON! All time highs ahead! What, you haven&amp;#39;t heard of AI yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:40:12 </td>
   <td style="text-align:left;"> @KeanuTheBear $SPY tech isn&amp;#39;t carrying market, market moves higher and the beta/bullish companies get the MOST $$$ pulled forward. 
 
Its index buying, its index hedge covering that is pulling the market up. BEST COMPANIES get 5x more $$ than shit companies. 
 
Tech pullback does not matter....$$$ NEVER LEAVES the market, it rotates around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:40:03 </td>
   <td style="text-align:left;"> $SPY this market is SO EASY. it won&amp;#39;t go down cause there are too many bears lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:51 </td>
   <td style="text-align:left;"> $SPY whoever buying will be taking massive loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:31 </td>
   <td style="text-align:left;"> $QQQ $SPY  
? ?  ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:22 </td>
   <td style="text-align:left;"> $SPY opportunity to buy more great companies at better prices DUH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:21 </td>
   <td style="text-align:left;"> $SPY this just goes up. Never any pull backs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:03 </td>
   <td style="text-align:left;"> $SPY remember when broke $ human trash though Treasury creating bonds would be bearish...something but liquidity??? that shit is STUPID!! 
 
All of them got sucked into the perfect BS trap set by Wall St !!! 
 
 
IDIOTS!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:03 </td>
   <td style="text-align:left;"> $SPY Just blast past this zone…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:39:01 </td>
   <td style="text-align:left;"> $SPY spread it open dad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:38:38 </td>
   <td style="text-align:left;"> $QQQ $SPY

Ugly auction but here’s some liquidity for you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:38:36 </td>
   <td style="text-align:left;"> $SPY Theres your bear squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:38:25 </td>
   <td style="text-align:left;"> $SPY Tech carrying the rest of the market on their shoulders...what happens when tech pulls back even for consolidation?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:38:12 </td>
   <td style="text-align:left;"> $SPY 

When they say hope isn’t an investment strategy yet that’s the only thing holding the market up today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:58 </td>
   <td style="text-align:left;"> $SPY TESLAPPLEVIDEASOFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:55 </td>
   <td style="text-align:left;"> $ES_F $SPY only trade for the day, still holding runners. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:50 </td>
   <td style="text-align:left;"> $SPY low volume push.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:44 </td>
   <td style="text-align:left;"> $SPY think PPI will come lower than expected but CPI i dont know.. oof going to be fun~~~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:16 </td>
   <td style="text-align:left;"> $SPY the real price comes out soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:12 </td>
   <td style="text-align:left;"> $SPY Double Top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:08 </td>
   <td style="text-align:left;"> $SPY crypto losers are probably buying stock now.  Should stay bullish considering the sheer buying power crypto traders have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:02 </td>
   <td style="text-align:left;"> $SPY fed will raise, otherwise hyperinflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:37:01 </td>
   <td style="text-align:left;"> $SPY I told everyone it was a bear trap, but again, again and again, bears are getting wrecked. 

When
Are 
You
Going
To
Understand? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:58 </td>
   <td style="text-align:left;"> $SPY Real push here sends us $432 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:49 </td>
   <td style="text-align:left;"> $SPY bout to go higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:37 </td>
   <td style="text-align:left;"> $SPY so strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:26 </td>
   <td style="text-align:left;"> $SPY vix gapped up expect it to fall back and close gap so calls here back to the top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:18 </td>
   <td style="text-align:left;"> $SPY Puts did nothing but go down, but you kept scooping them up thinking it was a discount! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:11 </td>
   <td style="text-align:left;"> $SPY we don’t trade on Mondays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:10 </td>
   <td style="text-align:left;"> $QQQ $SPY  said so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:09 </td>
   <td style="text-align:left;"> $SPY as soon as strength came back $iwm fell ahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:36:05 </td>
   <td style="text-align:left;"> $SPY $JPM  . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:57 </td>
   <td style="text-align:left;"> Rich af. No downside risk. Buy all dips. $spy .. thank you bears for feeding us more and more. All time highs are coming… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:49 </td>
   <td style="text-align:left;"> $SPY bears got excited 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:43 </td>
   <td style="text-align:left;"> $AAPL yes higher! Deserves new ATH. Scuba diving will be big this summer, Apple‘s gonna make goggles. It’s related somehow $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:40 </td>
   <td style="text-align:left;"> $SPY  boring day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:36 </td>
   <td style="text-align:left;"> $SPY that all you got? Yee yee. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:35 </td>
   <td style="text-align:left;"> $SPY I often see on this board people write how they are selling puts. 

What is that you are selling? 

Cash secured put? 
Put credit spreads? 
Put BackRatio spreads? 

Or any other multi leg potions strategy? Are you doing weekly? Or longer? If so? How much are you collecting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:33 </td>
   <td style="text-align:left;"> $SPY added to the cellar again today 😍😍😍😍 now valued at $36.6k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:25 </td>
   <td style="text-align:left;"> $SPY Lots of selling on the TICK &amp;amp; TICK/Q but we keep going up. VIX has been dumping for an hour straight. You can take all of your stupid outdated theories and throw them in the trash. 0DTE options volume is the only thing that matters. And it will only continue to push the market higher. No sense trying to fight it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:35:11 </td>
   <td style="text-align:left;"> $SOFI target continues to be 15$ in 6-9 months. Profitability and student loan refinance are going to be incredible. Before the pause Sofi was selling the loans because they were not a bank. Now as a bank they get to capture all that margin and could potential offer ultra competitive rates too $SPY $QQQ $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:50 </td>
   <td style="text-align:left;"> $SPY $422 is max pain today. Something going to happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:49 </td>
   <td style="text-align:left;"> $SPY same action everyday. Endless bids and no sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:48 </td>
   <td style="text-align:left;"> $SPY 

Lol let’s see how this works out in the hood…

I saw a wacky lib collecting dirty leaves on street last Fall for composting instead of just having them taken away.  🤡

https://link.crainsnewyork.com/click/31766274.26725/aHR0cHM6Ly93d3cuY3JhaW5zbmV3eW9yay5jb20vY2xpbWF0ZS1jaGFuZ2UvaXQtd2lsbC1zb29uLWJlLW1hbmRhdG9yeS1uZXcteW9yay1jaXR5LWNvbXBvc3QtZm9vZC1zY3JhcHM_dXRtX3NvdXJjZT1icmVha2luZy1uZXdzJnV0bV9tZWRpdW09ZW1haWwmdXRtX2NhbXBhaWduPTIwMjMwNjEyJnV0bV9jb250ZW50PWFydGljbGUxLWhlYWRsaW5l/5f692facc51f056d0a6630e4Befff5bfd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:19 </td>
   <td style="text-align:left;"> $Spy $QQQ  
Its  going  Up  so  load  the  boat.   
Throwing  you  a  Bone  here  ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:18 </td>
   <td style="text-align:left;"> $AAPL prop job on the market here $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:00 </td>
   <td style="text-align:left;"> $SPY such a strong bull market we have here be a shame if that CPI print came in hot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:34:00 </td>
   <td style="text-align:left;"> $SPY: The long and short term trends are both positive. This is looking good! https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:54 </td>
   <td style="text-align:left;"> $SPY Been watching SPY all morning , I trade ES for several reasons but this is where traders get screwed buying FOMO breakouts. I am always watching for the break and base of whatever you prefer to use ~ Could be the 8/9 MA or VWAP . 
Patience goes a long way, sure sometimes it doesnt come back however longevity comes with trading the probability. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:49 </td>
   <td style="text-align:left;"> $SPY Omg omg omg what were the bears thinking piling into 430P?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:42 </td>
   <td style="text-align:left;"> $SPY SOOOOO excited for CPI data &amp;amp; Tuesday fireworks! Justttt no inline for mixed reactshunnn, print 4.3-4.5% or 3.9%-below. Prefer strong sell with vix, but a strong moon is fine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:38 </td>
   <td style="text-align:left;"> $spy $dia $qqq

gotta squeeze a tad bit more out of tech before it begins haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:27 </td>
   <td style="text-align:left;"> $ASST $SPY  
EVERYONE GUESS YOU KILLED YET ANOTHER POSITION. If only you had been following maybe you could have had a piece of this pie! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:27 </td>
   <td style="text-align:left;"> $SPY ha ha .. bears 🐻 are rekt .. they can’t understand it’s the same pattern everyday..  small dip at open sucking them in and then rekt them.. with a V </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:24 </td>
   <td style="text-align:left;"> $SPY its over after this sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:24 </td>
   <td style="text-align:left;"> $SPY today’s going to be a flat day… if it was going to make a move, It would’ve made the move by now. Tomorrow we’re going to see some swings and fireworks… we ride at dawn My friends. Stay frosty 🫡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:21 </td>
   <td style="text-align:left;"> $SPY WEDNESDAY, JUNE 14      
8:30 am Producer price index  
8:30 am Core PPI    
8:30 am PPI year over year    
8:30 am Core PPI year over year    
2:00 pm Fed decision on interest-rate policy     
2:30 pm Fed Chair Powell press conference </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:02 </td>
   <td style="text-align:left;"> $SPY pumpin megcap.  Havent seen that playbook before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:33:02 </td>
   <td style="text-align:left;"> $SPY 433.3333333210 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:58 </td>
   <td style="text-align:left;"> $SPY garbage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:57 </td>
   <td style="text-align:left;"> $AAPL $SPY endless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:48 </td>
   <td style="text-align:left;"> $SPY one More 431 test. Before 🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:48 </td>
   <td style="text-align:left;"> $SPY 
433 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:47 </td>
   <td style="text-align:left;"> $SPY $QQQ yep. Every 15 mins there is a pump.   Algo trading.  Don’t fight it. This will move sideways until probably 3:30pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:46 </td>
   <td style="text-align:left;"> $SPY TUESDAY, JUNE 13      
8:30 am Consumer price index  
8:30 am Core CPI May  
8:30 am CPI year over year    
8:30 am Core CPI year over year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:30 </td>
   <td style="text-align:left;"> $SPY retest at 431  If it can break that...look out bellow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:28 </td>
   <td style="text-align:left;"> @NODOUT so @nytrader60 was right $SPY do not buy puts right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:11 </td>
   <td style="text-align:left;"> $SPY Let her gooooooooo. Lol One way or the other. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:32:08 </td>
   <td style="text-align:left;"> $SPY rip to $340? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:58 </td>
   <td style="text-align:left;"> $SPY snooze fest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:53 </td>
   <td style="text-align:left;"> $SPY $450 by Friday if powell doesn’t fck it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:41 </td>
   <td style="text-align:left;"> $SPY new pick up line for single man &amp;#39;so CPI tomorrow, we should get protection&amp;#39; 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:41 </td>
   <td style="text-align:left;"> $SPY run bull run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:33 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ a red day would give NVDA a macd cross to the downside.  Not that it really matters in this strong a bull market but… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:07 </td>
   <td style="text-align:left;"> $SPY about to get out of control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:03 </td>
   <td style="text-align:left;"> $SPY nowhere else for this market to run. Time to face judgement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:31:03 </td>
   <td style="text-align:left;"> $spy would love to see it run hard over 430 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:30:40 </td>
   <td style="text-align:left;"> $SPY go down you POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:30:38 </td>
   <td style="text-align:left;"> Morning Update $QQQ $IWM $SPY  
 
https://twitter.com/bclund/status/1668279423735582722?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:30:34 </td>
   <td style="text-align:left;"> $SPY come on, soon them tires. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:30:28 </td>
   <td style="text-align:left;"> $SPY wow what a boring day here.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:30:26 </td>
   <td style="text-align:left;"> $SPY looks like options sellers want this right where it&amp;#39;s at.  They want those premiums.  Don&amp;#39;t feed them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:59 </td>
   <td style="text-align:left;"> $SPY lol how many times will we retest $430.76 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:37 </td>
   <td style="text-align:left;"> $SPY $QQQ moment of truth! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:27 </td>
   <td style="text-align:left;"> $SPY another topping tail on the 5min? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:18 </td>
   <td style="text-align:left;"> $SPY one positive note is that it is holding trend even tho it is very choppy. That is usually a good sign. It would be horrible if it broke out to the top before news day.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:15 </td>
   <td style="text-align:left;"> $AAPL 182 per share! Give me 190 this week so I can say I told you so! Boy did you guys see those inflation numbers that came out 20 minutes ago? Lfg bulls! $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:11 </td>
   <td style="text-align:left;"> $SPY who tf gambles on a monday?  Best thing you cam do is just watch and wait on the off chance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:29:06 </td>
   <td style="text-align:left;"> $SPY the trend is up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:53 </td>
   <td style="text-align:left;"> $SPY that is some serious sideways action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:52 </td>
   <td style="text-align:left;"> $SPY just be grateful they let you participate in their self enrichment grift </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:42 </td>
   <td style="text-align:left;"> $SPY here comes the shit show very shortly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:33 </td>
   <td style="text-align:left;"> $SPY $QQQ The price of oil is telling you where the economy is headed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:24 </td>
   <td style="text-align:left;"> $SPY come on shorts drop this. It is your day. VIX UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:22 </td>
   <td style="text-align:left;"> $SPY  just gimme 428 real quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:04 </td>
   <td style="text-align:left;"> $SPY $QQQ I have removed my DRIPs from the majority of my stocks. Keeping any that have yield above 7.25% going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:28:04 </td>
   <td style="text-align:left;"> $LAZR 💥💥💥💥💥 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:27:44 </td>
   <td style="text-align:left;"> $SOFI Does anyone have a site to view what the current short interest is on this stock? If so, I would appreciate any link, etc. I&amp;#39;m assuming at some point the number should start falling. Thanks $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:27:38 </td>
   <td style="text-align:left;"> $SPY high volume chop chop. Lovin it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:27:22 </td>
   <td style="text-align:left;"> $SPY This is retarded.  How many times are we going to retest 431? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:27:21 </td>
   <td style="text-align:left;"> $SPY The AI day is paying off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:27:21 </td>
   <td style="text-align:left;"> $SPY $TJX these should be green if you follow me, i just give them out for free, just like Lynch gives out turkeys in the hood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:27:19 </td>
   <td style="text-align:left;"> $SPY Wierd price action..Looks like selloff coming... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:48 </td>
   <td style="text-align:left;"> $ASST $SPY  
Hit that follow. Trust me folks your missing out!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX Big day tomorrow. This explains why the VIX is up today. Massive institutional hedging… It’ll be interesting to see how the market reacts if this meets expectations…. Or if it misses completely. It will be interesting to see Mr. Moodymarket’s reaction. He is a drunken maniac… and he’s been on a bender for a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:33 </td>
   <td style="text-align:left;"> $SPY hmmmmmm... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:25 </td>
   <td style="text-align:left;"> $SPY quack quack quack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:22 </td>
   <td style="text-align:left;"> $SPY MM will keep it up and pull the rug premarket cpi , shits so obvious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:07 </td>
   <td style="text-align:left;"> $SPY give er’ some gas, hank. ⛽️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:26:06 </td>
   <td style="text-align:left;"> @gusherishere $SPY going no where.. Waiting game for CPI and FED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:48 </td>
   <td style="text-align:left;"> $SPY No momo in da dojo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:46 </td>
   <td style="text-align:left;"> $SPY going red Fred deep drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:43 </td>
   <td style="text-align:left;"> $TSLA please help this stock needs more pumpers, who will join the FOMOA BUYERS AND buy more at 90 RSI?? Anyone? $SPY 🤣🐖🐷😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:40 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/1OptionsTrading/status/1667963002060980230?t=LqU9FzlXkDl_znMoGFSD0A&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:39 </td>
   <td style="text-align:left;"> $SPY theta just taking everyone in options money 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:38 </td>
   <td style="text-align:left;"> $spy $tsla $aapl $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:36 </td>
   <td style="text-align:left;"> $SPY 430.6s  HOS 431.2s. I have Calls like 1-3 per week High and Low. Pump FOMC CPI ER and  Dump. 90% Correct and Calls for Shorts $SOXL $SOXS Since Sept 2022. 2-4 per week for +5-15%. 90-95% Correct in 1-5 days. Almost all Winners bc Decay. The Shorts Calls have like 10-15 to 1   % Gains vs Losses. 
 
I hope $SPY drop 2-3  pre M 70% Chance. So I can Covers SOXL for +3-5% of Gains. I Predicted SPY at FOMC 435-440 and a drop 430-425.I Shorts SOXL 22.8s avg and it drop in Few Hours 22.1s my Orders to covers 22.01. So I was greedy and The Shorts Calls are Good. I have take  +1.5-2 Last Week and Misses +1.6. SOXL is now 23.7s and will drop under 22 aGain in few days. SOXL was 24.6s drop 20.4s a week later as I Predicted 2 weeks ago for 20.s.   
 
I Covers some  SOXL 23.3s to Shorts $SCO 28.5s. a week ago I Short it 28.9s I Covers 3 days later 26 for Shorts $KOLD  and I take +10 Monday and another +10. Monday SCO 24.6 and KOLD 77.s and it Pop 88 And drop 73.s Msgs Posted and Saves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:31 </td>
   <td style="text-align:left;"> 🔥Out | Trimming:  $SPY $431Call 0DTE | Round 6 
🔥Price: $0.45/Contrac 
😭Profit: $0.47→ $0.45  🍎    
 
 
#SPY #QQQ #TQQQ #TSLA #TRADINGVIEW #TRENDINGNOW #FROGALGO @everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:26 </td>
   <td style="text-align:left;"> $coin $spy law firm announces investigation into Coinbase for breach of fiduciary duty, other charges. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:19 </td>
   <td style="text-align:left;"> $SPY they won’t let mega caps go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:14 </td>
   <td style="text-align:left;"> $SPY fat lady singing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:13 </td>
   <td style="text-align:left;"> $SOFI still holding but pullback imminent - holding for few years but already 100% 🔥👌 $SPY $QQQ $TSLA 

Congrats if you jumped in 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:25:13 </td>
   <td style="text-align:left;"> $SPY fking flat today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:50 </td>
   <td style="text-align:left;"> Indices like watching grass grow $ES_F $SPY - great for the short iron condors from Friday continue to erode =) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:37 </td>
   <td style="text-align:left;"> $SPY I love seeing AI along with weight loss pills drugs being the talk of the market.
It’s funny especially live cattle are reaching highs lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:36 </td>
   <td style="text-align:left;"> $SPY has about a one dollar range on the day so far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:22 </td>
   <td style="text-align:left;"> $SPY Side fcuk all day today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:21 </td>
   <td style="text-align:left;"> $SPY A great way to see that the moves are PM&amp;#39;s trying to catch up &amp;amp; are just chasing now is how $tsla over 90 RSI is still getting a bid.  
Even  if Quants are able to set that up as a Buy its def fast money. 
 
The Market is being bought because its being bought, that cant end well 
 
$qqq $nvda $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:18 </td>
   <td style="text-align:left;"> $SPY salute to all the stop losses that were murdered today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:24:07 </td>
   <td style="text-align:left;"> $SPY They better build true AI very qyickly to replace the divisions our military has lost because of Obama and Biden. No one wants to join the military having to rely on queers and transexuals to cover your a s. The illegals they are recruiting will not be reliable under fire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:58 </td>
   <td style="text-align:left;"> $AAP $SPY once Big T shows up, its over for you 🧸 cubs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:44 </td>
   <td style="text-align:left;"> $SPY 🫡📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:39 </td>
   <td style="text-align:left;"> $SPY 
We KNEW they were going to C@NTS today and just stay in this spot ALLLLLLL day!

We hate them! 

Gl all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:30 </td>
   <td style="text-align:left;"> $SPY 390 puts for sure for today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:22 </td>
   <td style="text-align:left;"> $SPY Data/Fed this week has everyone distracted... look at oil. And don&amp;#39;t forget banks still on collapse watch, just like 08. oof. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:19 </td>
   <td style="text-align:left;"> $SPY JPM to pay 290M in Epstein case

Time to rug some gamblers Jamie to pay for that lawsuit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:06 </td>
   <td style="text-align:left;"> 🔥Option: $SPY $431Call 0DTE 
🔥Price: $0.47/Contract [Super Lotto] | 200Contracts 
🗣️Stop_Loss: -21%  
 
 
#SPY #QQQ #TQQQ #TSLA #TRADINGVIEW #TRENDINGNOW #FROGALGO @everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:23:00 </td>
   <td style="text-align:left;"> $spy rotation now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:59 </td>
   <td style="text-align:left;"> $QQQ $SPY putting the money in dumb hands because they are more likely to give it up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:54 </td>
   <td style="text-align:left;"> $SPY There is still so much buying pressure up here, the RSI isn’t too bad because of all the soft resets they did.  And all this bear talk… calls usually always works. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:44 </td>
   <td style="text-align:left;"> $SPY $ENVX wen 15.5, just close it over 13.8 and lets find out 🖖🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:41 </td>
   <td style="text-align:left;"> $SPY grifter power activate! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:28 </td>
   <td style="text-align:left;"> $SPY just waiting to see if there’s another rug pull, like last Friday, in the next 40min or so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:26 </td>
   <td style="text-align:left;"> $SPY compressed down with insane low end volume on means one thing. Green beam!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:07 </td>
   <td style="text-align:left;"> $QQQ $SPY bulls hanging on until the plug gets pulled on them. Setting up for fire works this week. Get your beer ready bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:22:02 </td>
   <td style="text-align:left;"> $SPY this is about to shit itself so bad with these pumps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:21:37 </td>
   <td style="text-align:left;"> $SPY 2:00 🕑 move coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:21:34 </td>
   <td style="text-align:left;"> $SPY  
 
1/2 point Hike would be so sweet! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:21:27 </td>
   <td style="text-align:left;"> $TSLA no need to be clowns 🤡 and pump it! It pumps itself with fanbois! Look 👀 when it dumps! Sky is not the limit! It won’t go to the Moon, even if it goes, it comes back! What goes up must go down! Simple physics! Insider dump is coming anytime $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:20:35 </td>
   <td style="text-align:left;"> $SPY Tesla, SOFI INTC just rippin bears dont stand a change here - yields still going up bonds and metals/safe heavens screwed. FED is supplying the TINA route..... Its speculative risk assets/tech or nothing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:20:32 </td>
   <td style="text-align:left;"> $SPY you can feel it in your gut — something is wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:20:14 </td>
   <td style="text-align:left;"> $SPY up $.20 down $.20 up $.30 down $.30 up $.20 down $.20 up $.25 down $.25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:20:07 </td>
   <td style="text-align:left;"> $SPY Injecting liquidity WHEN NEEDED!! …And not a minute to late. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:20:00 </td>
   <td style="text-align:left;"> $SPY time is on our side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:19:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:19:39 </td>
   <td style="text-align:left;"> $SPY latex513f368e9fe0e31b1a84e0cbbff06393BVNRY
$SIGA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:19:35 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ what spreads? I’m up over 100% YTD on options mainly, and booking more profits every week, of course, I’m not buying nearly as much as I write 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:19:29 </td>
   <td style="text-align:left;"> $SPY eh scalped 14% on the usual puts. Profit is profit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:19:26 </td>
   <td style="text-align:left;"> $SPY too many bears as usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:56 </td>
   <td style="text-align:left;"> $SPY losing money on both sides today, everyone just sell not worth it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:30 </td>
   <td style="text-align:left;"> $SPY $QQQ consolidation for a bloodbath real soon just be patient </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:23 </td>
   <td style="text-align:left;"> $SPY here go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:21 </td>
   <td style="text-align:left;"> $SPY 

How a hawkish pause can be bullish? It&amp;#39;s just telling that the economy and bank situation are so bad that they cannot hike despite sticky inflation... This market is so weird. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:10 </td>
   <td style="text-align:left;"> $SPY 450 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:10 </td>
   <td style="text-align:left;"> $SPY crushing calls and puts chillin here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:18:09 </td>
   <td style="text-align:left;"> $SPY the algo knows what it’s doing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:17:44 </td>
   <td style="text-align:left;"> $BTX.X $SPY 

Crypto on a key support.

I expect a breakdown coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:17:42 </td>
   <td style="text-align:left;"> $SPY flat until tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:17:35 </td>
   <td style="text-align:left;"> $TSLA if you think 12 straight Green Day’s is normal I got a penny stock to sell you $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:17:23 </td>
   <td style="text-align:left;"> latex241ad1e23f2d63e35d2fe743ad230d8fZJYL 
$SPY puts

All on watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:42 </td>
   <td style="text-align:left;"> $SPY so many better tickers to be playing today. spy’s gonna chop until data and fomc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:40 </td>
   <td style="text-align:left;"> $AAP $SPY i like squeezing shorts 🖖🏽 i was train for this fools 😂😂😂🤙🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:33 </td>
   <td style="text-align:left;"> $SPY what&amp;#39;s up with $IWM range.. nice to trade them futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:32 </td>
   <td style="text-align:left;"> $SPY typical monday action nothing special </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:27 </td>
   <td style="text-align:left;"> $SPY lets pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:26 </td>
   <td style="text-align:left;"> $SPY I need more volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:26 </td>
   <td style="text-align:left;"> $INTC Break 33.03 

Watch the FOMO&amp;#39;ers pile up 

$SPY $AMD $NVDA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:16:09 </td>
   <td style="text-align:left;"> $spy 
Switzerland&amp;#39;s central bank lost $143 billion last year. But it&amp;#39;s no problem if you are an unregulated entity :) Many central banks will have to be recapitalized by governments (taxpayers) at some point in the future. 
Theoretically, central banks can operate without any capital under a fiat system: &amp;quot;Give me control of a nation&amp;#39;s money supply and I care not who makes its laws,&amp;quot; as Rothschild put it. Can this policy be implemented indefinitely?

The leader of the Russian Bolshevik Revolution Vladimir Lenin once said that “…the way to crush the bourgeoisie is to grind them between the millstones of taxation and inflation.”

The father of mainstream macroeconomics J.M. Keynes agreed: “Lenin was certainly right. There is no subtler, no surer means of overturning the existing basis of society than to debauch the currency.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:51 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY look out shorts…Tesla is bull flagging on the intraday.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:43 </td>
   <td style="text-align:left;"> $SPY $TGT i need to see just a little more candles 🖖🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:32 </td>
   <td style="text-align:left;"> $SPY tomorrow and Wednesday a ton of economic data this won’t hold through all that. Has had a whole week of basically no economic data after budget agreement been great run but this will fall in time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:21 </td>
   <td style="text-align:left;"> $SPY there will be no meaningful price action today and my brokerage account will go back to zero </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:15 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ spreads are all jacked up wtf! cant trade in this kind of environment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AVGO $900 C were up over 300% today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:15:00 </td>
   <td style="text-align:left;"> $SOFI: One thing this market has been showing over and over again is that overbought can remain overbought. Lots of dated calls coming into this one today. 
$SPY 
https://share.trendspider.com/chart/SOFI/52149szvyyv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:56 </td>
   <td style="text-align:left;"> $SPY yawnnnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:53 </td>
   <td style="text-align:left;"> $SPY too much going on int the next few days I&amp;#39;ll wait before opening a position. Looks horizontal and boring.  Best to look elsewhere for now.  This is like a bar on a Thurs day night  with 2 chicks and 15 guys.  Why even try just move on to the next opportunity.  Tommorrow and the next day are the real volatility days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:41 </td>
   <td style="text-align:left;"> $SPY 

Consumer ultra discretionary being pumped hard again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:37 </td>
   <td style="text-align:left;"> $SPY should hold here.. or down we go... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:34 </td>
   <td style="text-align:left;"> $CCL $SPY  
 
another $BBBYQ  
 
get you bags here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:15 </td>
   <td style="text-align:left;"> $SPY she is ready to comee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:14:11 </td>
   <td style="text-align:left;"> &amp;quot;Another common error people commit when dealing with options is overlooking the potential impact of implied volatility (IV) spikes. Even if you anticipate a long-term increase in the stock price, failing to capitalize on a 10% shift in the share price and ignoring the accompanying IV surge can lead to significant IV crush if the price remains stagnant in the following day or two.&amp;quot; $spy $spx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:58 </td>
   <td style="text-align:left;"> $SPY scam premium killa </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:46 </td>
   <td style="text-align:left;"> $SOFI America is all about issuing credit and holding debt. How could you not be bullish on this? lol 
⤴️🤑
$NASDAQ $DJIA $RUT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:44 </td>
   <td style="text-align:left;"> $SPY bulls destroy the cubs already so papa bear can short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:41 </td>
   <td style="text-align:left;"> $SPY Apple keeping spy alive today huh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:33 </td>
   <td style="text-align:left;"> $SPY is the market really this messed up. Green every day. They refuse to let apple see red again $AAPL pretty crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:31 </td>
   <td style="text-align:left;"> $IJH vs. $SPY vs. $SUSA: what will be the best investment? https://srnk.us/go/4722364 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:27 </td>
   <td style="text-align:left;"> $SPY loading up on puts here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:18 </td>
   <td style="text-align:left;"> $SPY What were the bears thinking buying $430 puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:03 </td>
   <td style="text-align:left;"> $SPY looks bullish to me 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:13:02 </td>
   <td style="text-align:left;"> $SPY just go up already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:52 </td>
   <td style="text-align:left;"> $SPY who is looking at Apple up here and telling themselves it&amp;#39;s a great price 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:49 </td>
   <td style="text-align:left;"> $SPY Don’t waste your time watching this today.  The real action will be tomorrow and Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:44 </td>
   <td style="text-align:left;"> $COIN $SPY 

I believe we are going to see COIN break this massive large key resistance. The beginning of a brand new lawsuit is going to drive investors out of this company (at least for the mid to short range) 

Upside is limited with a SEC lawsuit and it will take a LONG time for this to get sorted. So gains here will be unlikly especailly since the stock hasn’t moved much since mid 2022 as it is already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:41 </td>
   <td style="text-align:left;"> $SPY Quad witching this Friday...  
 
So many puts vs calls... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:29 </td>
   <td style="text-align:left;"> $SPY Algos every time the indices fall a few cents... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:18 </td>
   <td style="text-align:left;"> $SPY lmfao lol 😆 😂 🤣  I remember bulltatds telling me during my short at 57  that cgc would be a 200$ stock and my put would &amp;quot; be destroyed&amp;quot; lol 😆 😂 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:07 </td>
   <td style="text-align:left;"> $QQQ DOWN turn possible from these overextended levels. Looks like there is a lot of room to DROP lower. $SPY $DIA $BTC.X $COIN on close watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:03 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $IWM  
 
haha! 
 
bool weak AF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:12:02 </td>
   <td style="text-align:left;"> $SPY I get it it’s hard…. First it looked like a V …. Good for you! Then it turned into a W. Great eyes bull. Lol then it turned into a staircase to hell lol burn 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:11:30 </td>
   <td style="text-align:left;"> $SPY This guy has been consistently wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:11:09 </td>
   <td style="text-align:left;"> $SPY $QQQ WOW  A space solar power prototype has demonstrated its ability to wirelessly beam power through space and direct a detectable amount of energy toward Earth for the first time. The experiment proves the viability of tapping into a near-limitless supply of power in the form of energy from the sun from space.

👍 https://www.space.com/space-solar-power-satellite-beams-energy-1st-time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:11:07 </td>
   <td style="text-align:left;"> $SPY gimme a real cpi print stop lying , it’s minimum 10% show is the real numbers assholes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:11:03 </td>
   <td style="text-align:left;"> $SPY feel like they so control now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:58 </td>
   <td style="text-align:left;"> $SPY walk it out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:45 </td>
   <td style="text-align:left;"> $SOXS $AAPL $SPY $QQQ  Ignore the hype and artificial exubrance. &amp;quot; It&amp;#39;s the inflation and the FED stupid&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:43 </td>
   <td style="text-align:left;"> $SPY too many bids on puts right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:22 </td>
   <td style="text-align:left;"> $SPY what’s the Japanese way of saying it? Sayonara bulls lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:22 </td>
   <td style="text-align:left;"> $SPY theta burnnnnnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:02 </td>
   <td style="text-align:left;"> $SPY it’ll come. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:10:00 </td>
   <td style="text-align:left;"> $SPY  When the price is volatile y’all complain. 
  When the price is non-volatile y’all complain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:59 </td>
   <td style="text-align:left;"> $spy so jerome has balls. Keep raising rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:56 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $tsla $meta - 
 Treasury auction over 100 billion today  
  
treasurydirect.gov/auctions... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:51 </td>
   <td style="text-align:left;"> $SPY grift grift grift grift grift </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:43 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:38 </td>
   <td style="text-align:left;"> $SPY def of getting caught in the middle like a retailer would be placing a put or calll at these levels don’t get whiplash lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:34 </td>
   <td style="text-align:left;"> $SPY $QQQ  how would fucking retail bring trust to the public? Damn you&amp;#39;re goofy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-12 23:09:29 </td>
   <td style="text-align:left;"> $SPY ie. supply is so poor, that even relatively low demand causes inflation, still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:49:44 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $nvda $aapl

CPI tomorrow est 4.1% YoY 

WHAT IS YOUR CPI NUMBER FOR TOMORROW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:49:03 </td>
   <td style="text-align:left;"> $SPY $QQQ DeepMind CEO - &amp;#39;AI could cure cancer.&amp;#39; NVDA, MSFT, etc. for now, can&amp;#39;t wait to see the 1,000+ AI IPOs I&amp;#39;m guessing are in the pipelines perhaps starting this Fall, TBD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:48:46 </td>
   <td style="text-align:left;"> $QQQ 356 new support for the day. Let&amp;#39;s see if it holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:48:23 </td>
   <td style="text-align:left;"> $RUM latex77e44aac6f03289f9049ed09cf88770d head in the dirt. 
 
The market is NOT controlled by companies. 
 
Just learn that you might stop failing 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:48:02 </td>
   <td style="text-align:left;"> $QQQ 357.55 interesting area to short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:47:12 </td>
   <td style="text-align:left;"> $SPY $QQQ market has lost its mind with hype… inflation numbers out tomorrow… will be RED BIGLY!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:47:00 </td>
   <td style="text-align:left;"> $SPY $QQQ  
WTF  is  TA?   You  Sheeps  believe  anything  
Over  sold  does  not  exist.  This  is  a  Joe  Biden  Market  #VoteBlue  
Buy  in  June  and  Hold!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:46:31 </td>
   <td style="text-align:left;"> $SQQQ $QQQ At this point whether cpi comes in hot or fed raises rates, any outcome would be bullish. You might see a 0.5% drop then a 5% pump after. All is bullish so just buy any fucking dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:46:13 </td>
   <td style="text-align:left;"> $QQQ imagine if you just bought calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:46:07 </td>
   <td style="text-align:left;"> $QQQ  Rug pull in 1...  2... and 3.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:45:48 </td>
   <td style="text-align:left;"> $QQQ Jesus fucking christ this shit is relentless. STOP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:45:41 </td>
   <td style="text-align:left;"> $QQQ 
 
October  CPI sent markets up! 
 
Will May CPI send markets down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:45:39 </td>
   <td style="text-align:left;"> $QQQ creating a cushion for bad news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:45:29 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AMZN &amp;lt;&amp;gt;&amp;lt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:43:56 </td>
   <td style="text-align:left;"> $QQQ  
 
Still very early in the day and volume is very low, no one can sure what&amp;#39;s going to happen here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:43:29 </td>
   <td style="text-align:left;"> latexcabd0d660803a35893e11fc6f9235c46 in 6 months. lol let that set in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:43:19 </td>
   <td style="text-align:left;"> Stocks open higher to kick off key week for US economy: Stock market news today

https://finance.yahoo.com/news/stocks-open-higher-to-kick-off-key-week-for-us-economy-stock-market-news-today-110707386.html

$QQQ $TQQQ $SQQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:43:07 </td>
   <td style="text-align:left;"> $QQQ This POS really only moves one direction... ffs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:42:00 </td>
   <td style="text-align:left;"> $QQQ is currently trading near its 52 week high, which is a good sign. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:41:18 </td>
   <td style="text-align:left;"> $QQQ AI programs running the markets. Suck in as many retail investors as possible then pull the plug. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:40:58 </td>
   <td style="text-align:left;"> $QQQ 358 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:40:20 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ Remember boys and girls, always be bullish. 2 year ripping? Who cares. DXY higher? Doesn&amp;#39;t matter. Equities sitting at resistance for days. Whatever. IV out of control after massive runs higher and would need huge moves to justify call options? Buy &amp;#39;em anyway you pussy! CPI coming out tomorrow? TO THE MOON! All time highs ahead! What, you haven&amp;#39;t heard of AI yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:39:31 </td>
   <td style="text-align:left;"> $QQQ $SPY  
? ?  ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:38:55 </td>
   <td style="text-align:left;"> $QQQ someone removed the reverse gear on this cow.  only moves forward gears 1 to 6. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:38:38 </td>
   <td style="text-align:left;"> $QQQ $SPY

Ugly auction but here’s some liquidity for you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:38:16 </td>
   <td style="text-align:left;"> Oracle $orcl was in the low $80s in March (now $117), a name like $IBM has gone from $120 to $136 in a month &amp;amp; no one has noticed. It&amp;#39;s not just FAANNG, these are huge market cap moves from the second tier players. $qqq $xlk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:37:53 </td>
   <td style="text-align:left;"> $TLT Short US treasuries -&amp;gt; increase interest rates -&amp;gt; bang down the VIX $UVXY and oil $USO -&amp;gt; long $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:37:42 </td>
   <td style="text-align:left;"> $QQQ I wonder if there are any bears left that formed their trade thesis in December still holding on for $250? There sure were a lot of them the first 2-3 months this year but seems like most have gone home with their tail between their legs since. Never think you’re smarter than the market, because you’re not, and it charges very high prices to prove it to you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:37:16 </td>
   <td style="text-align:left;"> $QQQ Ridiculous upward candlestick nonsense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:37:13 </td>
   <td style="text-align:left;"> $QQQ dude it has been doing this for 6 straight weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:37:06 </td>
   <td style="text-align:left;"> $QQQ should be up 5 or 6 by end of day -- easy peasy -- will sit on a lounger and collect moolah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:36:54 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:36:41 </td>
   <td style="text-align:left;"> $QQQ NEW ATH!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:36:25 </td>
   <td style="text-align:left;"> $QQQ $SPX  all meme at QT &amp;amp; higher rate , how long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:36:10 </td>
   <td style="text-align:left;"> $QQQ $SPY  said so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:36:03 </td>
   <td style="text-align:left;"> $QQQ so the vix don’t mean shit. Got it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:53 </td>
   <td style="text-align:left;"> $QQQ probably test and hovers around 360 till fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:43 </td>
   <td style="text-align:left;"> $QQQ Studio rent prices in my apartment building (NJ/NYC metro area) have gone up $150 in the 8 months I have been here. They are currently $50 less than the 1 bedroom I live in, which means I&amp;#39;m probably going to see a $100-150 increase in rent when lease ends..good luck with your deflationary cpi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:43 </td>
   <td style="text-align:left;"> $AAPL yes higher! Deserves new ATH. Scuba diving will be big this summer, Apple‘s gonna make goggles. It’s related somehow $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:20 </td>
   <td style="text-align:left;"> $QQQ here it goes, only knows green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:16 </td>
   <td style="text-align:left;"> $QQQ could rest 360 here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:11 </td>
   <td style="text-align:left;"> $SOFI target continues to be 15$ in 6-9 months. Profitability and student loan refinance are going to be incredible. Before the pause Sofi was selling the loans because they were not a bank. Now as a bank they get to capture all that margin and could potential offer ultra competitive rates too $SPY $QQQ $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:35:04 </td>
   <td style="text-align:left;"> $QQQ Going to $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:34:19 </td>
   <td style="text-align:left;"> $Spy $QQQ  
Its  going  Up  so  load  the  boat.   
Throwing  you  a  Bone  here  ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:34:18 </td>
   <td style="text-align:left;"> $AAPL prop job on the market here $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:33:43 </td>
   <td style="text-align:left;"> $QQQ I guess we&amp;#39;re back to stonks only go up full retard market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:33:38 </td>
   <td style="text-align:left;"> $spy $dia $qqq

gotta squeeze a tad bit more out of tech before it begins haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:33:09 </td>
   <td style="text-align:left;"> $QQQ this is just unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:32:47 </td>
   <td style="text-align:left;"> $SPY $QQQ yep. Every 15 mins there is a pump.   Algo trading.  Don’t fight it. This will move sideways until probably 3:30pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:31:33 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ a red day would give NVDA a macd cross to the downside.  Not that it really matters in this strong a bull market but… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:30:53 </td>
   <td style="text-align:left;"> $QQQ wants to go here. Close watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:30:48 </td>
   <td style="text-align:left;"> $QQQ Man this thing is relentlessly pumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:30:38 </td>
   <td style="text-align:left;"> Morning Update $QQQ $IWM $SPY  
 
https://twitter.com/bclund/status/1668279423735582722?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:29:37 </td>
   <td style="text-align:left;"> $SPY $QQQ moment of truth! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:29:06 </td>
   <td style="text-align:left;"> $QQQ What a load of bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:28:37 </td>
   <td style="text-align:left;"> $QQQ rarely ride swings into big binary catalysts like CPI, but QQQ $355-360 just seems like way too good risk reward not to hold. I could live with being wrong up here no way would I go long at these levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:28:33 </td>
   <td style="text-align:left;"> $SPY $QQQ The price of oil is telling you where the economy is headed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:28:18 </td>
   <td style="text-align:left;"> $QQQ Does anyone else find it fishy that every single analyst is on the same page about AI? There isn&amp;#39;t a single analyst out there with any doubts, or bearish speculation, or any projected roadblocks. Everyday is some news article that comes out to pump AI every day. I usually find that when everybody on wall street is on one side of the trade, they are usually wrong. When it&amp;#39;s too obvious, it&amp;#39;s usually wrong. Traders and investors should be cautious about this AI driven rally. Develop your own thoughts and hypothesis, do not listen to fraudstreet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:28:04 </td>
   <td style="text-align:left;"> $SPY $QQQ I have removed my DRIPs from the majority of my stocks. Keeping any that have yield above 7.25% going </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:27:44 </td>
   <td style="text-align:left;"> $SOFI Does anyone have a site to view what the current short interest is on this stock? If so, I would appreciate any link, etc. I&amp;#39;m assuming at some point the number should start falling. Thanks $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:26:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX Big day tomorrow. This explains why the VIX is up today. Massive institutional hedging… It’ll be interesting to see how the market reacts if this meets expectations…. Or if it misses completely. It will be interesting to see Mr. Moodymarket’s reaction. He is a drunken maniac… and he’s been on a bender for a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:25:38 </td>
   <td style="text-align:left;"> $spy $tsla $aapl $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:25:13 </td>
   <td style="text-align:left;"> $SOFI still holding but pullback imminent - holding for few years but already 100% 🔥👌 $SPY $QQQ $TSLA 

Congrats if you jumped in 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:24:21 </td>
   <td style="text-align:left;"> $SPY A great way to see that the moves are PM&amp;#39;s trying to catch up &amp;amp; are just chasing now is how $tsla over 90 RSI is still getting a bid.  
Even  if Quants are able to set that up as a Buy its def fast money. 
 
The Market is being bought because its being bought, that cant end well 
 
$qqq $nvda $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:23:49 </td>
   <td style="text-align:left;"> I just cant buy stocks after Nasdaq $QQQ up 7 weeks in a row…I just cant… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:22:59 </td>
   <td style="text-align:left;"> $QQQ $SPY putting the money in dumb hands because they are more likely to give it up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:22:48 </td>
   <td style="text-align:left;"> $QQQ will see if this continues til eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:22:24 </td>
   <td style="text-align:left;"> $QQQ this really sucks when Monday action is 0.0% at all times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:22:07 </td>
   <td style="text-align:left;"> $QQQ $SPY bulls hanging on until the plug gets pulled on them. Setting up for fire works this week. Get your beer ready bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:21:27 </td>
   <td style="text-align:left;"> $TSLA no need to be clowns 🤡 and pump it! It pumps itself with fanbois! Look 👀 when it dumps! Sky is not the limit! It won’t go to the Moon, even if it goes, it comes back! What goes up must go down! Simple physics! Insider dump is coming anytime $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:20:42 </td>
   <td style="text-align:left;"> $QQQ $SPX $SMH $IGV all get impact,  when Treasury sell T Bill almost 290 Billion,  QT. 95 Billion

Total  $385 liquidity drying by end of this week

https://www.treasurydirect.gov/auctions/upcoming/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:19:39 </td>
   <td style="text-align:left;"> $SPY latex513f368e9fe0e31b1a84e0cbbff06393BVNRY
$SIGA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:19:35 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ what spreads? I’m up over 100% YTD on options mainly, and booking more profits every week, of course, I’m not buying nearly as much as I write 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:18:30 </td>
   <td style="text-align:left;"> $SPY $QQQ consolidation for a bloodbath real soon just be patient </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:16:26 </td>
   <td style="text-align:left;"> $INTC Break 33.03 

Watch the FOMO&amp;#39;ers pile up 

$SPY $AMD $NVDA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:15:51 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY look out shorts…Tesla is bull flagging on the intraday.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:15:15 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ spreads are all jacked up wtf! cant trade in this kind of environment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:15:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AVGO $900 C were up over 300% today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:12:07 </td>
   <td style="text-align:left;"> $QQQ DOWN turn possible from these overextended levels. Looks like there is a lot of room to DROP lower. $SPY $DIA $BTC.X $COIN on close watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:12:03 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $IWM  
 
haha! 
 
bool weak AF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:11:09 </td>
   <td style="text-align:left;"> $SPY $QQQ WOW  A space solar power prototype has demonstrated its ability to wirelessly beam power through space and direct a detectable amount of energy toward Earth for the first time. The experiment proves the viability of tapping into a near-limitless supply of power in the form of energy from the sun from space.

👍 https://www.space.com/space-solar-power-satellite-beams-energy-1st-time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:10:45 </td>
   <td style="text-align:left;"> $SOXS $AAPL $SPY $QQQ  Ignore the hype and artificial exubrance. &amp;quot; It&amp;#39;s the inflation and the FED stupid&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:10:13 </td>
   <td style="text-align:left;"> $QQQ 352 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:09:56 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $tsla $meta - 
 Treasury auction over 100 billion today  
  
treasurydirect.gov/auctions... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:09:34 </td>
   <td style="text-align:left;"> $SPY $QQQ  how would fucking retail bring trust to the public? Damn you&amp;#39;re goofy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:09:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Fill up their pockets with more cash, there’s a reason it’s not going up much further from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:09:00 </td>
   <td style="text-align:left;"> $PLUG 6/23 calls are over 110% now. I&amp;#39;m realizing here. Not getting too greedy 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:07:44 </td>
   <td style="text-align:left;"> $QQQ max pain for today is 353 plus inflation nasty data and rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:07:28 </td>
   <td style="text-align:left;"> $Spy $QQQ  
Think  about  it  ...  I  am  no  Genius  but I  could  read  ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:06:47 </td>
   <td style="text-align:left;"> $INTC $AMD $QQQ Ukraine says one thing, Cold War is on again. The only way out is for 24 Million Taiwan People relocated out of Taiwan and All Manufacturing Scuttled. After China is peacefully handed Taiwan. All Taiwan People can wait while new Manufacturing plants get rebuilt elsewhere. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:06:25 </td>
   <td style="text-align:left;"> SNY FED: MAY THREE-YEAR AHEAD EXPECTED INFLATION AT 3% VS 2.9% IN APRIL 
 
3% target inflation will be new 2 % for a long time  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:05:59 </td>
   <td style="text-align:left;"> $SPCE 

🔥40 REASONS TO BUY VIRGIN GALACTIC (SPCE) STOCK🔥

1. First Commercial Flight in June
2. Successful Last Test Flight
3. Huge Revenue Coming
4. Celebrity Passengers Media Exposure
5. Potential SpaceX Deal
6. Branson owns 46M Shares
7. Musk &amp;amp; Branson Friendship
8. 800+ Reservations
9. $450k each flight
10. FAA Approved
11. Hype Building
12. Delta Spaceships
13. U.S./Italy Contract
14. NASA Partnership
15. Under Armour deal
16. Excellent Patents
17. SuperSonic Air Travel
18. 1st to Spaceflights
19. Microsoft deal
20. $1B Cash
21. Undervalued
22. Experienced Flight Team
23. Boeing deal
24. Will Explore Space
25. Rolls Royce deal
26. 400 flights yearly
27. Oversold
28. Superior Tech
29. Qarbon Aerospace
30. Successful Test Flights
31. Lead by Branson
32. Spaceport America Lease
33. Land Rover Deal
34. Ahead of Competition
35. Potential 30x+ Long Term
36. Space Era Coming
37. Research Flight for Italy
38. Gov’t Contracts
39. Virtuoso deal
40. Great Management

$SPY $DIA $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:05:01 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl

if it was tough, you’d just let it go without a long post proving it haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:04:50 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Sentiment Speaks: A New Bull Market Has Begun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:04:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM $ARKK Am I beating the market? This is result of buying when heaviness % is low.
Whats the Win/Lose ratio?

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
February (&amp;#39;23) = 0 loss
January (&amp;#39;23) = 0 loss
December (&amp;#39;22) = 2 losses
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps + buy fills for everything. Learn to buy when Algos are tired of selling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:04:32 </td>
   <td style="text-align:left;"> $SPY $QQQ hasn’t been a a bull or bear market in years. Just do the opposite of logic market. As soon as good news starts flowing in, things will start tanking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:04:15 </td>
   <td style="text-align:left;"> Retail call loading is at its highest level in over a year. 
$SPY $QQQ $SMH $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:03:49 </td>
   <td style="text-align:left;"> $SPY very weak action we should dip any minute $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:03:00 </td>
   <td style="text-align:left;"> $SPY $qqq - does it mean anything? 
 
Treasury auction over 100 billions today 
 
https://www.treasurydirect.gov/auctions/upcoming/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:01:49 </td>
   <td style="text-align:left;"> $QQQ so much open interest at $350 on options at end of this week.  I will not be surprised to see $350 here by eow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:01:33 </td>
   <td style="text-align:left;"> $QQQ yes I bought $362 puts June 30 x 5 contracts few minutes ago as said in my chart history </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:00:21 </td>
   <td style="text-align:left;"> @jsimco4 yeah I considered them at cost zero $$ due other profits already made .. but if you wish to ad puts needs $SPY $QQQ June 30 expiration </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 23:00:16 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ  Watchlist for June 12 th https://www.youtube.com/watch?v=DF5f9tzjZrQ&amp;amp;t=3s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:58:52 </td>
   <td style="text-align:left;"> $SIGA over 500 cases of m pox cya at $10+ $SPY $QQQ $MRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:58:24 </td>
   <td style="text-align:left;"> $META King cash cow 👑 💵 🐄 

$SPY $QQQ $QCOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:58:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Super choppy day- make the most of it and don’t overtrade. Nailed calls earlier. Back to just watching. Great start to the week💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:58:00 </td>
   <td style="text-align:left;"> $SPY $QQQ Hope you’re hedged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:57:15 </td>
   <td style="text-align:left;"> $QQQ vicious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:55:30 </td>
   <td style="text-align:left;"> $Spy $QQQ  
Oops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:55:29 </td>
   <td style="text-align:left;"> $QQQ - No volume pump will lead to big volume dump……. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:55:21 </td>
   <td style="text-align:left;"> $QQQ runs all day everyday on fairy dust and hopium for AI and EV and tech bullshit. Guess people forgot what type of energy and type of labor that actually runs the world.  That would be carbon based fuels and good ole fuckung blue collar human hands actually working!  Society full of weak men nowadays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:54:34 </td>
   <td style="text-align:left;"> On being added june 20 to the nasdaq is interesting for a trade

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:53:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $NASDAQ $DJIA $RUT 

Bools didn&amp;#39;t count on quad witching to thwart their weak push.  D&amp;#39;oh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:53:36 </td>
   <td style="text-align:left;"> $SPY slowly starting to make sense $qqq still in 🦄 land </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:53:09 </td>
   <td style="text-align:left;"> @FalconX_96 yes tomorrow there is less CPI % $SPY $QQQ which is priced in already and as per chart history we should have a new hight tomorrow at $434 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:53:06 </td>
   <td style="text-align:left;"> $QQQ the day trader in me wants to cash out but I&amp;#39;m holding for cpi tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:51:56 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:50:52 </td>
   <td style="text-align:left;"> $QQQ why is this flying up right now while the other indexes aren&amp;#39;t going up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:50:35 </td>
   <td style="text-align:left;"> $QQQ LOOOOOL look at the green candle its so cute in this 0% nothing.....red candles are ALL dojis ya ok. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:50:13 </td>
   <td style="text-align:left;"> $QQQ - Up 33.34% year to date. Don’t worry if the fed hikes tomorrow 🤣

Hedge accordingly 😁💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:50:11 </td>
   <td style="text-align:left;"> $TWLO This is a long-term hold, do not overthink this. They have been ruthless the past 4 months, CEO buying 10M with personal funds, activist coming in and lighting a match under their ass, 1B share buyback, 17% layoffs to cut costs, real estate gone to cut more costs, and CustomerAI is going to be massive new opportunity for Twilio, Signal conference in August. Remember 4B revenue, 4B cash, and 11B market cap is a joke, this is 20B company easily, highest was 75B 2 years ago, but if they become gaap profitable its game over for bears.  This company has 300k business that use them, that is a moat that will continue to grow and those customers use Twilio to make their businesses more effective and profitable.  It&amp;#39;s a win win $SPY $ARKK $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:49:29 </td>
   <td style="text-align:left;"> $QQQ GNOTZ ALGO WITHA. BEAUTIFUL LONG OFF THE RESISTANCE BREAK! 📈🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:49:28 </td>
   <td style="text-align:left;"> $TLT $QQQ $VIX nice midday pump... smooth sailing this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:49:16 </td>
   <td style="text-align:left;"> $QQQ Fed pause pump. More buyers coming in. Addding short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:48:37 </td>
   <td style="text-align:left;"> $SPY $QQQ about every 15 mins there is a pump.  Watch it again at 11am. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:48:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM $ARKK Some traders already getting all caught up (and are nervous) about this pullback; mostly based on  the 5 min chart action. 
 
What&amp;#39;s needed is a better plan. 
 
Focus guys. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:48:00 </td>
   <td style="text-align:left;"> $BABA so much to go 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:47:58 </td>
   <td style="text-align:left;"> $QQQ $SPY this week might be crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:47:13 </td>
   <td style="text-align:left;"> $SPY  $SPX  $QQQ $MSFT 

Come on, bulls, tell me that wouldn&amp;#39;t be a totally makes sense reason for a 4 deviation move in $NVDA. Semis would IMPLODE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:46:55 </td>
   <td style="text-align:left;"> $QQQ nah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:46:52 </td>
   <td style="text-align:left;"> $QQQ too cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:46:46 </td>
   <td style="text-align:left;"> $QQQ when is quad witching? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:46:26 </td>
   <td style="text-align:left;"> $QQQ $SPY CPI tomorrow only thing keeping me interested </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:46:04 </td>
   <td style="text-align:left;"> $QQQ the infamous V strikes again, almost comical at this point knowing it’s going to happen 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:45 </td>
   <td style="text-align:left;"> What is the best stock to buy right now? Pick the best $NFLX vs. $QQQ vs. $XLY. #Netflix https://srnk.us/go/4722280 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:31 </td>
   <td style="text-align:left;"> $QQQ $SPY I don’t see how the Q’s will ever see $330 or even $340 again.  Tech is just to cheap and this is headed to ATH’s before EOY.  💪

Breakout to $370 coming today or tomorrow.  🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:30 </td>
   <td style="text-align:left;"> $QQQ shocked if this gap holds today….flat close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:28 </td>
   <td style="text-align:left;"> $QQQ it doesn&amp;#39;t take a rocket scientist to predict the direction of this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:24 </td>
   <td style="text-align:left;"> $ES_F $SPY $NQ_F $QQQ #BONDS #NASDAQ #SP500 #FED #INFLATION #CPI 

CPI Tuesday⬇️
PPI Wednesday⬇️
FOMC Wednesday🔄
Retail sales &amp;amp; jobless claims Thursday
OPEX expiration Friday

#stockmarket #equities #Futures #Trading #marketforecast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $NASDAQ $RUT $NASDAQ 

Who wins today?

Theta.  Theta wins again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:45:01 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Notes From BlackRock&amp;#39;s Outlook Forum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:44:22 </td>
   <td style="text-align:left;"> $QQQ I truly ruined my life buying puts. I’m just devastated right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:43:35 </td>
   <td style="text-align:left;"> $U with a bullish setup... $SPX $SPY $QQQ 
 
Basically, trading sideways for the last seven months. 
 
Good luck.                     
 
Real-time alerts at http://thetradinganalyst.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:43:27 </td>
   <td style="text-align:left;"> $QQQ short $355 average, time to swing this - do or die tmrw with CPI. If I’m wrong I could live with it, risk reward to the short side is too good here to not try </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:43:00 </td>
   <td style="text-align:left;"> $QQQ this market loves sitting itself in pivotal points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:42:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $NASDAQ $RUT 

Awesome rally there bulls.  How...quaint. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:41:48 </td>
   <td style="text-align:left;"> $QQQ $NDX -- tight and choppy as expected ahead of CPI/PPI/FED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:41:04 </td>
   <td style="text-align:left;"> $QQQ Can we just get a red day for just one day! jesus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:40:54 </td>
   <td style="text-align:left;"> $SPY ai won’t save your ass bulls, party is over $QQQ t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:40:47 </td>
   <td style="text-align:left;"> How was your May? This is the result of ONLY buying when H% is low. 

$SPY $QQQ $TSLA $NFLX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:40:44 </td>
   <td style="text-align:left;"> $SPY $QQQ market will not like prices coming down... price increases are the only thing keeping company&amp;#39;s revenue growing... unit volumes are slowing in almost every industry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:39:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $NDX  The long trade is stretched. Time for backfill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:39:12 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ SPY and Qs may be about to make a move, but look at IWMs chart. If you can avoid the tricks, there is a lot of money to be made there... Hot damn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:39:06 </td>
   <td style="text-align:left;"> $SPY Just looks like some covering &amp;amp; some chasing on the Open w/ Buying pressure from EU, 
 
Not something to put money into. These are not Investors this is fast in &amp;amp; out money 
 
Trade Smart 
 
$baba $nvda $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:38:48 </td>
   <td style="text-align:left;"> $QQQ stop lying! Tech isn’t no where near all time highs. You should block all liars that are posting 💩 for click bait. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:37:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $NASDAQ $RUT 

Poots poots poots poots poots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:36:57 </td>
   <td style="text-align:left;"> $QQQ 5m bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:36:21 </td>
   <td style="text-align:left;"> $QQQ Chop master, Just gonna wait to buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:36:06 </td>
   <td style="text-align:left;"> $SPY $QQQ VIX is up 7%. Big drop in stocks coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:36:05 </td>
   <td style="text-align:left;"> $SPY $QQQ .. So $VIX is giving us the green light to hold this short. It’s up 6% and there is no slowdown in sight with this gap and go setup. 18&amp;gt;20&amp;gt;24 for starters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:35:55 </td>
   <td style="text-align:left;"> $TSLA Tesla has technically TOPPED OUT - come short for FREE MONEY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:35:22 </td>
   <td style="text-align:left;"> $QQQ the modern stock market... when you get head and shoulder bottoms... above the upper bollinger band. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:34:16 </td>
   <td style="text-align:left;"> $QQQ funny how the market telegraphs pauses and rate cuts a year in advance but still marches higher when it happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:33:27 </td>
   <td style="text-align:left;"> $INTC $AMD $QQQ https://twitter.com/fangtooth124875/status/1668263773868523521?s=20 I tweet on Twitter. If anyone doesn&amp;#39;t like the Tweets and Posts I make don&amp;#39;t be Lot&amp;#39;s Wife staring at Sodom. Pretend I don&amp;#39;t exist and leave me be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:32:34 </td>
   <td style="text-align:left;"> BOE&amp;#39;S MANN: THE DROP IN INFLATION EXPECTATIONS WAS IMPORTANT FOR ME TO SWITCH MY VOTE TO 25 BP RATE HIKE FROM 50 BPS 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:31:50 </td>
   <td style="text-align:left;"> $SPY to $QQQ my barcode is bigger than your barcode. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:31:44 </td>
   <td style="text-align:left;"> $QQQ how is the market loving uncertainty? They are pausing too early. We will find it nessisary to hike more. The problem now is shrinkflation happening we are still paying high inflation. This month June will show up next month and it will show inflation on the rise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:31:12 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:30:52 </td>
   <td style="text-align:left;"> $TSLA well this is an easy dip buy as the $QQQ rolls upwards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:30:22 </td>
   <td style="text-align:left;"> $INTC $AMD $QQQ https://stocktwits.com/pllonnger/message/531667813 Stocktwits ChatGBT is confusing me with AMD Comrades. I am not the comrade, AMD pumpers Are, licking the XI Jinping boot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:30:09 </td>
   <td style="text-align:left;"> $QQQ Oooh good old delusional animal spirits. Retail does it every time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:30:08 </td>
   <td style="text-align:left;"> $SOXL breaking out 🚀

$QQQ $TQQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:29:07 </td>
   <td style="text-align:left;"> $QQQ someone let the market know its not Saturday anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:29:05 </td>
   <td style="text-align:left;"> $QQQ $SPY World&amp;#39;s biggest f0gg0t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:29:05 </td>
   <td style="text-align:left;"> $QQQ $SPY we need to fill some gaps they just playing games to keep you guessing on when that’s gonna happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:27:33 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ Is it just me or did the futures contract roll over get a much bigger gap higher today compared to IWM/SPY/QQQ. Like a huge gap up that isn&amp;#39;t reflected in it&amp;#39;s price as a percentage higher. I know rolls can gap it a bit, but damn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:27:01 </td>
   <td style="text-align:left;"> $spy Ok Im going to use the original AI here &amp;amp; ask what I should do. 
 
&amp;quot;If I Buy this Market where it is today will I be happy in a month?&amp;quot; 
 
$nvda $aapl $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:26:56 </td>
   <td style="text-align:left;"> $QQQ There’s the bait. Right on time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:26:31 </td>
   <td style="text-align:left;"> $QQQ now it traded like a penny stock. Lol nice spike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:26:20 </td>
   <td style="text-align:left;"> $IWM and $QQQ with that inverse correlation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:26:14 </td>
   <td style="text-align:left;"> $QQQ then they cry &amp;quot;rigged&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:26:13 </td>
   <td style="text-align:left;"> $QQQ lmao ok I was half right. I didn&amp;#39;t think the algo would actually rip it immediately to intraday highs 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:25:50 </td>
   <td style="text-align:left;"> $QQQ bears keep shorting when it&amp;#39;s a clear uptrend...

Of course one time you will be right, but you will be losing 90% of the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:25:43 </td>
   <td style="text-align:left;"> $QQQ this is fucked up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:25:07 </td>
   <td style="text-align:left;"> $QQQ $SPY . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:24:35 </td>
   <td style="text-align:left;"> $QQQ $SPY VIX up 7% and dow, spy, qqq all positive. Fuck this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:24:14 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Listening to Joe Rogans Podcast with Thei Von. One of the things they were talking about is North Korea being on the WHO Board. Lol. Funny how a country who starves and deprives their people are on the board. 

You cant take anything serious these days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:23:19 </td>
   <td style="text-align:left;"> $CCL $NCLH super quick 90% profits in under an hour. All out at 1.06
$SPY $QQQ $UVXY bets on CPI? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:22:43 </td>
   <td style="text-align:left;"> $SPY burning premium all day everyday $QQQ $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:22:08 </td>
   <td style="text-align:left;"> $QQQ lol headfake! Cheers to another week of ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:22:08 </td>
   <td style="text-align:left;"> $RAD $GME $AMC $SPY $QQQ RiteAid trades at less  marketcap(100M) than BBBY which filed for bankruptcy already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:21:52 </td>
   <td style="text-align:left;"> $QQQ $SQQQ  
 
Tech at all time highs, extreme greed index through the roof, Vix in the basement...Powell gonna talk this week. 
 
What could possibly go wrong? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:21:29 </td>
   <td style="text-align:left;"> $SPY $QQQ PPT buying the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:21:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $NASDAQ $RUT 

&amp;quot;...but...but...why stonks no go up!?&amp;quot;

Alexa: What is quad witching? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:20:53 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ Bear trap after bear trap on IWM. If you are still having trouble reversing into them and riding the move back up, you must be like me, retarded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:20:11 </td>
   <td style="text-align:left;"> $SPY $QQQ easy short here all week long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:19:47 </td>
   <td style="text-align:left;"> $QQQ Not a terrible idea putting shorts on up here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:19:36 </td>
   <td style="text-align:left;"> $QQQ stay the fuc*k out of this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:19:21 </td>
   <td style="text-align:left;"> $QQQ $SPY this is giving me a headache </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:19:15 </td>
   <td style="text-align:left;"> $SPY theta burn till wednesday $QQQ $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:18:59 </td>
   <td style="text-align:left;"> $QQQ they are killing both way now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:18:45 </td>
   <td style="text-align:left;"> GOLDMAN SACHS CEO DAVID SOLOMON SAYS HE THINKS INFLATION IS A LITTLE BIT STICKIER - CNBC INTERVIEW $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:18:44 </td>
   <td style="text-align:left;"> $WISH $GME $AMC $QQQ can shorts over come 50million buyback by WISH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:18:07 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Equity CEFs: Ride The NBXG Wave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:17:53 </td>
   <td style="text-align:left;"> $TMF $SPY $QQQ Gargi Chaudhuri, BlackRock Head of iShares Investment Strategy Americas, on Bloomberg calling Bank of Japan largest near-term risk - avoid U.S. Treasuries beyond 10 years on possible yield-curve steepening scenario. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:17:38 </td>
   <td style="text-align:left;"> $QQQ  
 
Surprise hike with hawkish tone would collapse the Qs.  
 
May not happen, but it could  and that possibility is being competent ignored right now.  
 
$SQQQ makes a lot of  sense as a hedge right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:17:33 </td>
   <td style="text-align:left;"> $QQQ bulls need to be manhandled into submission </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:17:08 </td>
   <td style="text-align:left;"> $SPY $SPX $DJIA $NASDAQ $QQQ  Probability of zero rate hike  is 78% and continues to climb. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:16:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Let&amp;#39;s see...inflation numbers coming out tomorrow morning with stock market at ATH... does it make sense to be a bull here??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:16:54 </td>
   <td style="text-align:left;"> $SPY $QQQ you are here 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:16:34 </td>
   <td style="text-align:left;"> $QQQ bottom in for the day. Theta burn for next 5 hours 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:16:27 </td>
   <td style="text-align:left;"> $SPY $QQQ Probably another sell the news event incoming... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:16:15 </td>
   <td style="text-align:left;"> $QQQ back to $357 in no time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:15:39 </td>
   <td style="text-align:left;"> $QQQ Today would be the 10th day that it is in this range. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:15:22 </td>
   <td style="text-align:left;"> $QQQ  
 
No rate cuts in 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:55 </td>
   <td style="text-align:left;"> $SPY $QQQ BS pump that won&amp;#39;t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:40 </td>
   <td style="text-align:left;"> $SPY $QQQ 

A 130k share buy over @ $FNGD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:32 </td>
   <td style="text-align:left;"> $QQQ options are a fools errand.  Stick to trading $SQQQ and $TQQQ, where you can exit outside normal trading hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:31 </td>
   <td style="text-align:left;"> $QQQ $SPY 200sma bullshit continues... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:29 </td>
   <td style="text-align:left;"> $SPY $QQQ higher for longer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Put/Call ratio is disgustingly low... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:13 </td>
   <td style="text-align:left;"> $QQQ buying puts here to save the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:14:00 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA US/China tensions continue to rise. This should be scaring the market, especially tech. I&amp;#39;m really surprised we haven&amp;#39;t at least seen a 5% movement down last week since China is a key market. Losing that market or any significant disruptions will shave off a huge amount of revenue. 
 
There&amp;#39;s better stocks that can weather breakdown of US/China relations. Defense, infrastructure, utility stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:13:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM don&amp;#39;t worry... have no fear.... J Powell will be here to pad your landing with a mountain of cash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:13:34 </td>
   <td style="text-align:left;"> $GME reclaiming the high ground after 2 insider buys. 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:12:23 </td>
   <td style="text-align:left;"> $MOTS awesome yodl ; holding for a .20 squeeze here 🦾🚀
Slapping 
$UK and $ZVSA looking good right besides it
3 winners 
$QQQ ⏫️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:11:58 </td>
   <td style="text-align:left;"> $QQQ Still looks like distribution within fang at the FNGU 200 day MA. Today is TSLA and Broadcom day which have the lowest weights in the QQQ, but the rest of fang sentiment is looks like it is fading. Digi times which is a completely non reputable source out of taiwan gave AI stocks some sentiment this morning. Gold is also selling off this morning and the dollar is up, so they may actually expect feds to be going tighter. We know 1 bad jobs data print doesn&amp;#39;t necessarily mean the economy is weakening and the fed will want to see multiple weeks of weaker jobs data before confirming a pause. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:11:09 </td>
   <td style="text-align:left;"> $SPY $SPX $DJIA $NASDAQ $QQQ Rate pause this Month,Most likely per CME GROUP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:11:00 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA $NASDAQ $RUT 

Not until Chi-na comes and takes it out.

Oh yeah, are they still evacuating? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:10:09 </td>
   <td style="text-align:left;"> $dia $spy $qqq $msft $amzn and more ... a must read re #cnbc link ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:09:42 </td>
   <td style="text-align:left;"> $QQQ Gap up sell off, pump EOD. Holy fack this is so predictable $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:09:17 </td>
   <td style="text-align:left;"> $HON price action feels really poppy hard to say, but I think we end higher today $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:09:10 </td>
   <td style="text-align:left;"> $QQQ honest question, is war good or bad for markets, the way they are these days it could go either way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:08:46 </td>
   <td style="text-align:left;"> $QQQ Market is done if you go for Bull.. Fu*cking trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:08:21 </td>
   <td style="text-align:left;"> $QQQ this market is wild 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:08:13 </td>
   <td style="text-align:left;"> $QQQ - Don’t worry, just buy it! So what you lose 20-25% in the next few months. Remember you are long this market🤣🤣🤣🤣, no matter how long it takes you to get your money back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:07:24 </td>
   <td style="text-align:left;"> $NVDA $TSLA $QQQ $SPY 

 https://www.express.co.uk/news/world/1779942/taiwan-america-china-xi-biden/amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:06:40 </td>
   <td style="text-align:left;"> $QQQ Ah the 10am dip, like clock work. End of A period (i.e. amateur hour). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:06:34 </td>
   <td style="text-align:left;"> $SPY $QQQ  Sitting on enough collateral to sell one SPY put. I just don’t see the logical reason to make the trade at this point right now. I mean I could theoretically probably sell a SPY put for like $185 of premium right now a-month out. But I could wait tomorrow and there could be a dip down to 420….sell a $400 put (better price to own if assigned) and I would collect at least $300 of premium on a .200 delta put. Patience is key when running the KC wheel strategy. Patience my friends. Stay frosty…🫡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:05:31 </td>
   <td style="text-align:left;"> $QQQ really confuse... Bull trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:05:27 </td>
   <td style="text-align:left;"> $SOXL — so far so good for the bulls. Price action creating higher highs and higher lows, just what we like to see 😉 

$SOXS $QQQ $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:05:16 </td>
   <td style="text-align:left;"> $QQQ $SPY Qs with a fairly bearish weekly last week and its meant nothing...all that bearish candle, rising wedge shxt don&amp;#39;t work when the bull market is this strong.    💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:04:17 </td>
   <td style="text-align:left;"> $SHOP not too shabby at all

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:04:17 </td>
   <td style="text-align:left;"> $SPY CHOPFEST $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:04:11 </td>
   <td style="text-align:left;"> $QQQ back into SQQQ here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:04:10 </td>
   <td style="text-align:left;"> $QQQ this is messed up people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:03:55 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $SPX $DJIA Watch list $AABB CEO is taking on the crooked market makers in a big way!! For the record the company has 4 pipe lines ALL backed by GOLD (mine to token) 1000 TPD Q3=$55,000,000 annually trading below asset value 109M (cash &amp;amp; gold)= generational wealth opportunity for the WIN!! https://finance.yahoo.com/news/asia-broadband-pursues-market-manipulation-130000152.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:03:30 </td>
   <td style="text-align:left;"> $SPY $QQQ 

A live look at the options chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:01:39 </td>
   <td style="text-align:left;"> $QQQ look out below </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:01:28 </td>
   <td style="text-align:left;"> $FUBO $IWM 

Trump’s going to the electric chair and we going to the moon baby!!

https://www.history.com/this-day-in-history/rosenbergs-executed

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:00:47 </td>
   <td style="text-align:left;"> $COIN DROPPING since this morning (and could keep dropping lower) as $BTC.X went DOWN as well. Let&amp;#39;s see when/if $SPY $QQQ turn down what will be the next step... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 22:00:38 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ $VXX $SQQQ  

Bring it.  The retrace is due. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:59:57 </td>
   <td style="text-align:left;"> $SPY euphoria galore, yet market is likely reaching its top. Who is buying this when so many large caps have gaps $META $NVDA, $TSLA with an rsi is 80+, this market is crazy. 

Really think $QQQ sees a new ATL by EOY. Always go against public consensus. People on Twitter are way to overly confident yet actual numbers show the truth, recession is almost guaranteed, and smart money has positioned for the crash. Most short net futures since 2007, vs dumb money most active since 2021 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:59:38 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Never been more booooolish

https://www.teletrader.com/us-reportedly-prepares-evacuation-plans-in-taiwan/news/details/60147954 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:58:41 </td>
   <td style="text-align:left;"> $spy $QQQ  
Hold!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:58:38 </td>
   <td style="text-align:left;"> $SPY $DJIA $NASDAQ $QQQ $RUT 

Bulls are doing just fine today: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:58:20 </td>
   <td style="text-align:left;"> $SPY $QQQ ECB predicting dodging recession few months ago. FED predicts mild recession not even dodging like europe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:57:40 </td>
   <td style="text-align:left;"> $UVXY little if any resistance all the way back to 4.31 now that they&amp;#39;re fully loaded.  $SPY $QQQ $VXX $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:57:19 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA bearish week up ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:57:08 </td>
   <td style="text-align:left;"> $AAPL $NVDA $QQQ Ai is alive…. We talk about it and how to invest in it here!
Our OP platform also mentions what undiscovered Ai plays there are to invest in!

https://youtu.be/X4pZB-Htz_k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:56:34 </td>
   <td style="text-align:left;"> $NVDA $SQQQ $QQQ $NVDS Still holding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:55:44 </td>
   <td style="text-align:left;"> $QQQ nothing can stop me i&amp;#39;m all the way up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:55:25 </td>
   <td style="text-align:left;"> $SPY $QQQ Authoritarian DemonRat Dystopia is here to stay. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:54:45 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:54:43 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Q2 Earnings Season Could Lift These ETFs https://www.stck.pro/news/QQQ/52864450/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:54:38 </td>
   <td style="text-align:left;"> $SPY $QQQ 

2yr climbing again 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:54:20 </td>
   <td style="text-align:left;"> $QQQ gotta shave a few here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:53:41 </td>
   <td style="text-align:left;"> $PLUG Entered at open today 🔥🔥🔥

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:53:17 </td>
   <td style="text-align:left;"> $QQQ damn I did the call thing and it’s going down…… your welcome bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:53:08 </td>
   <td style="text-align:left;"> $QQQ any minute now... buy algo v 3.0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:53:05 </td>
   <td style="text-align:left;"> $NIO $SPY $TSLA $QQQ $XPEV  There it is 10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:59 </td>
   <td style="text-align:left;"> $SPY  $QQQ  Bears fighting away the bullish deception. ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:52 </td>
   <td style="text-align:left;"> $SOFI stock after setting a new 52-week high

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:51 </td>
   <td style="text-align:left;"> $QQQ BULL MARKET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:39 </td>
   <td style="text-align:left;"> $QQQ will you please
Cool the fuck off for a couple days wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Goldman bearish during the lows in november last year,. now they are bullish. after 20% rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:26 </td>
   <td style="text-align:left;"> $SPY $NASDAQ $RUT $QQQ $DJIA 

Wave goodbye to your 0dte calls there bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:51:05 </td>
   <td style="text-align:left;"> $TSLA all you need to know is that every short has covered and everyone is long and hasn’t sold a share yet $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:50:36 </td>
   <td style="text-align:left;"> $NVDA $TSM $QQQ $SPY 😳 
https://www.express.co.uk/news/world/1779942/taiwan-america-china-xi-biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:50:06 </td>
   <td style="text-align:left;"> $QQQ needs a small pullback to go higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:49:23 </td>
   <td style="text-align:left;"> $SPY $QQQ ouchhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:49:04 </td>
   <td style="text-align:left;"> $TSLA will drag the $SPY and the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:49:03 </td>
   <td style="text-align:left;"> $SPY As the day moves on lets see how many PM&amp;#39;s are willing to go into the data &amp;amp; Powell not taking anything off the tale &amp;amp; keep it all on Paper. 
 
$nvda $aapl $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:47:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA Outside of NVDA large cap tech isn&amp;#39;t expensive at all...look at Tesla, only trading at 8x sales and with growth in the 30-40% range.    Yes, they have all gone up fast past couple of months but it&amp;#39;s because they were so cheap and still is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:47:50 </td>
   <td style="text-align:left;"> $SQQQ I bought SQQQ on open market but hedged with $QQQ . #ExpertMove </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:47:34 </td>
   <td style="text-align:left;"> $QQQ so this just goes on like this forever! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:47:22 </td>
   <td style="text-align:left;"> One thing i am sure that ; Market about to break out or reverse dump coming .. One of then soon… Too stupid areas now to trap and cheat retails … Watch closely  
 
$spy $qqq $tsla $nvda $intc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:47:19 </td>
   <td style="text-align:left;"> $SPY $QQQ punishment week loading …. 🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:46:39 </td>
   <td style="text-align:left;"> So absurd how $EA gets going down after their earnings call while $TTWO &amp;amp; $QQQ are up. 
 
1. Stock beat on top and bottom line and raised guidance. 
 
2. Stock had 7 price target upgrades since earnings. 
 
3. Company continues to buyback shares. 
 
4. They actually have games out performing sales (Deadspace, Jedi Survivor) 
 
5. Their live service games continue to grow according to Steamcharts (Apex Legends) 
 
6. If the CoD boycott keeps growing those players are going to  go to Apex Legends / BF 2042 (Which has been growing according to steamcharts) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:46:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $NASDAQ $RUT 

So how about that pump there bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:46:23 </td>
   <td style="text-align:left;"> $SOXL — price action just broke above critical liquid level 23.30 and buy pressure is sustained above this area

$SOXS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:46:00 </td>
   <td style="text-align:left;"> $QQQ $3.7M OTM Call 
 
Strike: 360 
Expiration: 6/23/23 
 
*Above the Ask* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:45:51 </td>
   <td style="text-align:left;"> Good morning everyone ☀️ I hope you all had a restful weekend. Trade in progress right now with $SOXL. We saw the gap up premarket followed by some sideways price swings. One thing I pointed out was the constant retest of premarket resistance.

$SOXS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:45:43 </td>
   <td style="text-align:left;"> 🛑🥴You Remember the last time it was a &amp;quot;new bull market&amp;quot; announced by virtually every pundit and media outlet across the board in 2022 

Over the next two months,The Nasdaq fell by 23%🤔

PS  “No landing” was a thing in August 2000🥶🥶
https://twitter.com/PaulVikingGlob1/status/1667836100377735169?t=6g--pT7KE_fXf66Ln_GXpA&amp;amp;s=19
$QQQ $SPY $DJIA $ARKK $NASDAQ  vvv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:44:56 </td>
   <td style="text-align:left;"> $QQQ is Max Pain for this Friday really $322? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:44:39 </td>
   <td style="text-align:left;"> $QQQ fing fed , now the whole market has to do a David blame and hold it&amp;#39;s breath for 3 days until we hear from them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:44:18 </td>
   <td style="text-align:left;"> $AMD $SPY $QQQ Trimmed some AMD shares here at $129.10...still holding core position, my largest holding, won&amp;#39;t sell those shares.   
 
Looks great but really hoping it will just consolidate between $116-$130 for a couple of weeks before it takes off to ATH&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-12 21:43:45 </td>
   <td style="text-align:left;"> $SPY $QQQ also rotation out if tech into defense continues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:49:44 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $nvda $aapl

CPI tomorrow est 4.1% YoY 

WHAT IS YOUR CPI NUMBER FOR TOMORROW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:45:01 </td>
   <td style="text-align:left;"> $AAPL would take a severe mental disability to be holding here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:43:48 </td>
   <td style="text-align:left;"> $AAPL Its the VR thing, I think people are realizing it is game changing. I heard it may be as big as the smartphone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:40:35 </td>
   <td style="text-align:left;"> $SOFI $AAPL partnership? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:39:45 </td>
   <td style="text-align:left;"> $AAPL Add more short here 😆🖕🍏🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:39:13 </td>
   <td style="text-align:left;"> $AAPL inexplicable buying in tech remains - especially this over priced pig.  Waiting for the events this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:37:14 </td>
   <td style="text-align:left;"> $AAPL holding 4400 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:35:43 </td>
   <td style="text-align:left;"> $AAPL yes higher! Deserves new ATH. Scuba diving will be big this summer, Apple‘s gonna make goggles. It’s related somehow $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:34:18 </td>
   <td style="text-align:left;"> $AAPL prop job on the market here $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:32:59 </td>
   <td style="text-align:left;"> $AAPL expect a big scuba google order from
china XI and kimjung um
they will use them to properganda read their eye ball to control compliance
and obama and brandon will order them so ever person can be brain washed
that woke is good and bud lite is the beer
of choice
I hear Apple will change its name to
&amp;quot;Skynet&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:32:57 </td>
   <td style="text-align:left;"> $AAPL $SPY endless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:32:26 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s the rush Wall Street???? $$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:31:48 </td>
   <td style="text-align:left;"> $AAPL wen top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:29:15 </td>
   <td style="text-align:left;"> $AAPL 182 per share! Give me 190 this week so I can say I told you so! Boy did you guys see those inflation numbers that came out 20 minutes ago? Lfg bulls! $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:28:48 </td>
   <td style="text-align:left;"> $AAPL iPhone sales dropped in May </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:28:33 </td>
   <td style="text-align:left;"> What is the best stock to buy right now? Pick the best $AAPL vs. $MSFT vs. $TQQQ. #Apple https://srnk.us/go/4722401 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:27:59 </td>
   <td style="text-align:left;"> $AAPL this headline sounds like apple is working on a car and it’s just 10 years away 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:25:38 </td>
   <td style="text-align:left;"> $spy $tsla $aapl $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:25:07 </td>
   <td style="text-align:left;"> $AAPL $AMAT Long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:24:23 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple is reportedly working on a cheaper version of its $3,500 Vision Pro — but it&amp;#39;s 2 years away https://www.stck.pro/news/AAPL/52870185/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:24:21 </td>
   <td style="text-align:left;"> $SPY A great way to see that the moves are PM&amp;#39;s trying to catch up &amp;amp; are just chasing now is how $tsla over 90 RSI is still getting a bid.  
Even  if Quants are able to set that up as a Buy its def fast money. 
 
The Market is being bought because its being bought, that cant end well 
 
$qqq $nvda $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:23:23 </td>
   <td style="text-align:left;"> $AABB Best performing stocks from infancy investors buying are $MNST $LLY $TSLA $AAPL as $AABB infancy investors will be also when all is said and done! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:22:36 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:20:30 </td>
   <td style="text-align:left;"> $AAPL playing whack a mole on the bears jeez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:18:57 </td>
   <td style="text-align:left;"> $AAPL everything seems expensive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:18:41 </td>
   <td style="text-align:left;"> $AAPL I expect this to test its high this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:18:13 </td>
   <td style="text-align:left;"> $AAPL she want 185 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:15:39 </td>
   <td style="text-align:left;"> $AAPL nobody going to buy the goggles as no content. Plus $3500 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:15:24 </td>
   <td style="text-align:left;"> $AAPL it wants $182 will it get it though? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:14:05 </td>
   <td style="text-align:left;"> $AAPL Visionpro on a 36 month installment plan through a carrier will only be $97.19.  They will sell as many as they can make 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:13:33 </td>
   <td style="text-align:left;"> $SPY is the market really this messed up. Green every day. They refuse to let apple see red again $AAPL pretty crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:11:59 </td>
   <td style="text-align:left;"> $AAPL rejecting off 182 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:11:40 </td>
   <td style="text-align:left;"> $AAPL why is this up so high today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:10:45 </td>
   <td style="text-align:left;"> $SOXS $AAPL $SPY $QQQ  Ignore the hype and artificial exubrance. &amp;quot; It&amp;#39;s the inflation and the FED stupid&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:10:39 </td>
   <td style="text-align:left;"> $AAPL $NVDA market has lost its collective mind... way overvalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:09:56 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $tsla $meta - 
 Treasury auction over 100 billion today  
  
treasurydirect.gov/auctions... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:09:17 </td>
   <td style="text-align:left;"> $AAPL Sucking more bulls in for the monster upcoming rug pull!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:08:39 </td>
   <td style="text-align:left;"> $AAPL dump already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:07:37 </td>
   <td style="text-align:left;"> $AAPL going to 4 trillion market cap. All is well. As interest rates rise so  does the stock market. If your paying $80k a year for college to study Inverse Relationships, wasting time and money....... $SPY $FED $POWELL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:06:21 </td>
   <td style="text-align:left;"> $AAPL Vision pro at this price point will not go mainstream next year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:06:04 </td>
   <td style="text-align:left;"> $AAPL buying puts here. Starting to look a bit weak. Risky but I don’t see it going much higher today. Well see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:05:17 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:05:01 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl

if it was tough, you’d just let it go without a long post proving it haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:04:15 </td>
   <td style="text-align:left;"> Retail call loading is at its highest level in over a year. 
$SPY $QQQ $SMH $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 23:01:12 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:59:39 </td>
   <td style="text-align:left;"> $AAPL still wating for a clear direction , before a trade today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:55:42 </td>
   <td style="text-align:left;"> $AAPL I don’t like the stock. $155 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:54:59 </td>
   <td style="text-align:left;"> $ZJYL Insane Anticipation Of This Move Before The 2nd Wave Of Momentum 🚨

• Pulls Back To Fill My Entry Price ($12.85)

• Breaks Both 1st &amp;amp; 2nd Price Targets ($13.74 , $14.64) 

• Currently Stuck In The Halt Here @ $14.78 

Stocks To Watch :

$ASST $AHI $MGOL $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:54:08 </td>
   <td style="text-align:left;"> $INTC  lol of course they have to buy something up straight up at open. And the v recovery in $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:53:49 </td>
   <td style="text-align:left;"> $AAPL how many times are we trying to get over $182? Is this a good sign or bad? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:53:02 </td>
   <td style="text-align:left;"> $CVNA YOU WANT A LAMBO ? SO GO FOR IT $AMC $GME $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:51:55 </td>
   <td style="text-align:left;"> $AAPL ✈️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:46:40 </td>
   <td style="text-align:left;"> $TSLA 

Tesla stock is the only Tech stock that has NOT rebound back ti its ATH since 2021 and still trading 40% below it —

Talking heads talking about 2023 stock doubled -CNBC and others those are pushing disinformation- 

In 2022 Tesla stock lost 74% of its value and bottomed on 1/5/23 at 75% drawdown biggest loss the stock has suffered since inception — what you see now $735 is well below where the stock was 2021 $1243 vs $AAPL $NVDA $META 

BEWARE OF 🛑 DISINFORMATION!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:44:34 </td>
   <td style="text-align:left;"> $AAPL buy low sell high. Don’t let the greed get the best of you- At ATH for no real good reason.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:43:53 </td>
   <td style="text-align:left;"> $AAPL Added more short, so easy!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:41:19 </td>
   <td style="text-align:left;"> $WLDS 👀 $NASDAQ $AAPL $DJIA @Stocktwits #shortsqueeze #squeezy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:40:48 </td>
   <td style="text-align:left;"> $U Let&amp;#39;s talk Unity. Feel free to comment. 
Hundreds-of-thousands of human hours, probably millions, went into making these tools. They now include the WETA toolset and some of the folks who made those are part of the team! 
 
It doesn&amp;#39;t make sense to build your own engine, if you want to make a complex game. You bascially only have Unreal and Unity to choose from. 
 
Zuck $META mentioned perhaps buying Unity years ago in a leaked memo. Autodesk $ADSK is another possible buyer, as they could avoid the WETA tools from becoming a competitor. Even Adobe or Microsoft might sweep in. 
 
Unity could fire its terrible CEO any day, stock would likely rocket! 
 
Finally, Unity landed that precious Vision Pro deal. This alone should lead to a rising stock. Many articles will come out over the coming months, the hype will grow. Apple $AAPL, the most valuable company, is coming out with its first new category since the Apple Watch in 2015?! It&amp;#39;s a BIG DEAL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:40:47 </td>
   <td style="text-align:left;"> How was your May? This is the result of ONLY buying when H% is low. 

$SPY $QQQ $TSLA $NFLX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:38:44 </td>
   <td style="text-align:left;"> $AUUD curling back up

$AHI $AI $SPOT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:36:56 </td>
   <td style="text-align:left;"> $AAPL Pigs getting ready for the slaughter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:34:45 </td>
   <td style="text-align:left;"> $AAPL one of investors&amp;#39; fav ticker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:34:31 </td>
   <td style="text-align:left;"> $AAP 

Told you so ! Now see you around $105 Range ! 

Maybe we will Supply AI Parts to $NVDA llol or $AAPL or maybe even $CVNA or who knows $AMD  ? 

Haha AI 💃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:33:33 </td>
   <td style="text-align:left;"> $AAPL grabbed some 182.5C at 1.44. Rip or dip? Going for the rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:31:53 </td>
   <td style="text-align:left;"> $AAPL $NVDA will see a big drop tomorrow when INFLATION data comes out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:31:18 </td>
   <td style="text-align:left;"> $SAVA $ENPH $AAPL 

Bearish 🩸🩸🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:30:53 </td>
   <td style="text-align:left;"> $GOOG $AAPL $NVDA $MSFT $AMZN  
QQQ call VOL. jump on $360 strike  for JUNE 23 
 
Vol @ 12,166  
 OI @ 9,752 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:30:12 </td>
   <td style="text-align:left;"> $ASST Took A Small Loss Here 📉

• Stop Limit Order Filled @ $3.38 ✔️

• Starts To Spike Hitting $3.49 ✔️

• Couldn’t Achieve My 1st &amp;amp; 2nd Price Targets ($3.61 , $3.85) ❌

It Happens , Lower Your Share Size To Take Losses Without Being Altered Mentally ☝️

Stocks To Watch :

$AHI $MGOL $IFBD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:29:55 </td>
   <td style="text-align:left;"> $AAPL hii </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:29:17 </td>
   <td style="text-align:left;"> $SPY $AAPL bulls are gamboling here... not much upside left and potentially big drop tomorrow with inflation data coming out.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:28:33 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA  call/put volume influence stock movement? If so, how? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:28:12 </td>
   <td style="text-align:left;"> $AAPL Nice if we could close above 182.50 😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:27:01 </td>
   <td style="text-align:left;"> $spy Ok Im going to use the original AI here &amp;amp; ask what I should do. 
 
&amp;quot;If I Buy this Market where it is today will I be happy in a month?&amp;quot; 
 
$nvda $aapl $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:24:44 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMZN $NVDA $MSFT  
Everything is GREEN 
 
 even the vix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:21:36 </td>
   <td style="text-align:left;"> $AAPL the long term average (through ups and downs) is 160. I think the stock goes below that at around 150 again and that’s where you pull the trigger. Thank you so much and have a great day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:20:45 </td>
   <td style="text-align:left;"> $AAPL been far more successful on a daily basis after I quit trading $SPY. Apple and other big names are much simpler to use TA on than an index. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:20:12 </td>
   <td style="text-align:left;"> $AAPL low float 🚨  🚨 🚨 extreme volatility with the right momentum $AUMN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:18:07 </td>
   <td style="text-align:left;"> $AAPL Underperforming tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:16:14 </td>
   <td style="text-align:left;"> $SQQQ $TQQQ $AAPL $TSLA $NVDA 

on a collision course with a freight train… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:13:54 </td>
   <td style="text-align:left;"> $U Two things, Unity gets bought out by Apple, or Apple just continues to add more Unity colabs.   $AAPL   Nice marriage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:13:37 </td>
   <td style="text-align:left;"> $AAPL $UBER Every Week Like Christmas 🚀🎉🎊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:12:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : As workers return to the office, companies turn to video technology https://www.stck.pro/news/AAPL/52865658/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:10:20 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m out until cpi comes out tomorrow, then I&amp;#39;ll probably go short if there&amp;#39;s a large bump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:09:25 </td>
   <td style="text-align:left;"> $SPX $SPY $AAPL $META $NVDA If you are wondering why the market is slow, it has its reason!  
 
CPI Data is tomorrow at 8:30am EST 
 
Jerome Powell Speaks Wednesday at 2:30pm EST 
 
Investors want to wait for news before they buy in! READ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:08:00 </td>
   <td style="text-align:left;"> $AAPL is currently trading near its 52 week high, which is a good sign. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:07:53 </td>
   <td style="text-align:left;"> $yext $aapl $F $TSLA $dis and more ... Friends, like you I am sure, I am sick and tired of this 24x7 self serving forever, older than dirt, hopium jawboning by #fraudstreetboilerroommarketmakersandcronies #cnbc et al  ... stfu 🤡🤡🤡 and wait until the facts are delivered. Where the fk is #SEC putting an end to this bullshit tabloid news? &amp;quot;Stocks rise as hope builds Fed will pause rate hikes this week: Live updates This is a developing news story. Please check back for updates:  
https://www.cnbc.com/2023/06/11/stock-market-today-live-updates.html  &amp;quot; 🐻❤😈  Thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker  😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:04:46 </td>
   <td style="text-align:left;"> $JPM $AAPL $TSLA $SPY $BRK.B What is the result of buying when heaviness % is low?
See the Win/Lose ratio.

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
January (&amp;#39;23) = 0 loss.
December (&amp;#39;22) = 2 losses.
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps + buy fills for everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:04:36 </td>
   <td style="text-align:left;"> $AAPL Why the sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:03:08 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Broadcom: Feeding The AI Frenzy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:02:50 </td>
   <td style="text-align:left;"> $AAPL Bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:02:21 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 22:01:18 </td>
   <td style="text-align:left;"> $AAPL 182 huge resistance 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:59:20 </td>
   <td style="text-align:left;"> $AAPL 🪂🪂🪂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:57:21 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMZN $NVDA $MSFT  
VIX up over 6% but markets are green across the board  
 
This kinda wild &amp;amp; makes it even more likely SPY sees 4600 after the Powell Pause &amp;amp; short covering boom! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:57:08 </td>
   <td style="text-align:left;"> $AAPL $NVDA $QQQ Ai is alive…. We talk about it and how to invest in it here!
Our OP platform also mentions what undiscovered Ai plays there are to invest in!

https://youtu.be/X4pZB-Htz_k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:56:14 </td>
   <td style="text-align:left;"> $AABB My favorite CEO&amp;#39;s past and present Steve Jobs $AAPL  Elon Musk $TSLA Bill Gates $MSFT Sundar Pinchai $GOOGL and add to that CEO Chris Torres $AABB fighting back for his company and shareholders at .03 cents OTC says it all https://finance.yahoo.com/news/asia-broadband-pursues-market-manipulation-130000152.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:54:45 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:54:17 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy Jun 16, 2023 $182.5 Calls 
Entry Price: $1.54 - $1.54 
Exit Price: $1.8 
Stop Loss: $1.42 
Potential ROI: 17% 
Estimated Hold Time: 40 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:54:02 </td>
   <td style="text-align:left;"> $AAPL 177.5 puts back in play next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:53:41 </td>
   <td style="text-align:left;"> $AAPL $VIX is picking up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:49:03 </td>
   <td style="text-align:left;"> $SPY As the day moves on lets see how many PM&amp;#39;s are willing to go into the data &amp;amp; Powell not taking anything off the tale &amp;amp; keep it all on Paper. 
 
$nvda $aapl $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:47:44 </td>
   <td style="text-align:left;"> $AAPL CANT FIGHT THE INEVITABLE 😂🥇🥇🥇🍏🍏🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:46:07 </td>
   <td style="text-align:left;"> 🛑🥴You Remember the last time it was a &amp;quot;new bull market&amp;quot; announced by virtually every pundit and media outlet across the board in 2022 

Over the next two months,The Nasdaq fell by 23%🤔

PS  “No landing” was a thing in August 2000🥶🥶
https://twitter.com/PaulVikingGlob1/status/1667836100377735169?t=6g--pT7KE_fXf66Ln_GXpA&amp;amp;s=19
$TSLA $AAPL $AMZN $NVDA $AMD  JJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:43:28 </td>
   <td style="text-align:left;"> Here’s some friendly tips I wish I started following years ago. 

1) Find 2-3 tickers, and become experts on them. 

2) Don’t chase losses. Usually  closing the laptop and trying again tomorrow is the best move. 

3) Charts DO lie. Don’t trade solely off of technical analysis. Factor in overall market conditions, recent news, etc. 

4) Set a P/L target for every trade, when you’ve hit it, get out. Don’t be greedy. 

5) $SPY  and $QQQ   options at the bell is a literal money cheat-code. 

6) Set stop losses. It’s insurance, and it’s free. 

7) Don’t buy/ sell certain stocks because of comments on apps like this. People have skin in the game and think they can move the market with their comments.

8) If you’re starting out, find a good group to be a part of. Watching someone experienced will save you a lot of trial and error. (Doesn’t have to be our group) Just any decent one. 

Not financial advice 

$TSLA $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:42:35 </td>
   <td style="text-align:left;"> $AAPL We need to bresk 182$ with high volume 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:39:56 </td>
   <td style="text-align:left;"> $AAPL 1/2, Chamath explains clearly the true value of Sabre company as an AI Company, quote on quote suggested by the CEO of PALO ALTO NETWORKS company (PANW) 
https://twitter.com/Podcast_GPT/status/1667663596703166466 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:35:11 </td>
   <td style="text-align:left;"> $SPY, $AMZN, $GOOG, $TSLA, $AAPL Let the battle begin.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:34:53 </td>
   <td style="text-align:left;"> $TSLA Bulls need 250.5 Breakout. Bears need 245 Breakdown. $SPY $QQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:33:46 </td>
   <td style="text-align:left;"> $AAPL Bulls need 182 Breakout. Bears need 180.5 Breakdown. $SPY $QQQ $UVXY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:33:44 </td>
   <td style="text-align:left;"> What stocks might make more money? Compare $AAPL vs. $QLD. #Apple https://srnk.us/go/4721982 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:33:18 </td>
   <td style="text-align:left;"> $AAPL Added 25000 shares short 183 resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:32:38 </td>
   <td style="text-align:left;"> $QQQ Bulls need 357.5 Breakout. Bears need 355 Breakdown. $SPY $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:32:31 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $AAPL with Unusual Options Activity Alerted on $105 CALL Expiring: 09-15-2023 worth 63K🐂 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:31:30 </td>
   <td style="text-align:left;"> Ribbon Charts 
 
$TSLA $NVDA $SPY $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:31:12 </td>
   <td style="text-align:left;"> $SPY Data This Week - CPI - PPI - Funds Rate - FOMC - Retail Sales - Manufacturing Index - Unemployment - Consumer Sentiment. Bulls need 432 Breakout. Bears need 430 Breakdown. $QQQ $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:30:38 </td>
   <td style="text-align:left;"> $AAPL corruption at its finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:30:13 </td>
   <td style="text-align:left;"> Make Sure You’re Getting In On The Chart Where The Action Is Hot 

With High Buying Pressure

This Way You Can Flip Your Shares For More Than You Paid ✔️

$ASST $AUUD $AHI $IFBD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:22:56 </td>
   <td style="text-align:left;"> June 12, 2023 
$SPY $430 to $431.70. Over $431.80 to $432.50-$433.30-$434.70. Under $430 to $429-$428.50 
  
$AAPL $181 to $182. Over $182 to $183-$183.50-$184. Under $181 to $180-$179.70-$179 
  
$BA $217 to $219. oVer $219 to $221-$222.50. Under $217 to $215-$214 
  
$NFLX $420 to$423. Over $423 to $426-$430. Under $419-$415-$414 
  
$NVDA $390 to $395. Over $395 to $400-$402. Under $390 to $385-$383 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:21:57 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Taiwan Semiconductor: Why Growth Will Resume In 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:21:22 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Taiwan Semiconductor: Why Growth Will Resume In 2024 https://www.stck.pro/news/AAPL/52862071/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:14:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL Too many bulls, not enough positive data. Psudo pump, priced to perfection. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:14:34 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY OP Wire is out and ready for you to stack well with!
Hope you enjoy the week we have ahead!

If you love real-time alerts, kind knowledgeable community that makes you feel like family, and the best mentors in the game then you will love Optionsplayers. You get a free month trial to see what I mean. Use our Stocktwits Premium Room free trial now to get our alerts, premarket news/plans, live chat, and our free course now!

https://stocktwits.com/r/OptionsPlayers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:09:47 </td>
   <td style="text-align:left;"> $AABB $AAPL &amp;amp; $MSFT started their infancy stages in tiny 1 car garages with a vision only to see those visions become the biggest market caps on the planet! $NVDA has recently joined that group with a MC close to a trillion dollars! $AABB vision of $AABBG.X becoming the New Global Standard of Exchange backed by Gold (mine to token) trading below asset value with a estimated 7B-10B+ FTD&amp;#39;s get DD ASAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:09:25 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:08:00 </td>
   <td style="text-align:left;"> @Mike_Ross Messi officially signing with Inter Miami and what the construct of his contract is going to be.  $AAPL $ADDYY will both be involved and the actual signing and $$$$ will be enormous for his brand and the U.S. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:08:00 </td>
   <td style="text-align:left;"> $SPY BULL MARKET INCOMING!
May went away and we survived! 
$FCEL $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:05:41 </td>
   <td style="text-align:left;"> $AAPL AI just sounds best </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:02:38 </td>
   <td style="text-align:left;"> $AAPL $AMZN $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:01:43 </td>
   <td style="text-align:left;"> $AAPL 200 EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 21:01:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN CPI is tomorrow at 830am, FOMC is Wednesday at 2pm.. trade accordingly y’all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:59:32 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:59:27 </td>
   <td style="text-align:left;"> $AAPL    
Calls:     
📈  at $180 - $179 
Puts:    
📉  at $184.36 - $184.95 if we get rejected  
 
Let the setup come to you!  
Manage risk properly! cut losses quickly! And always take profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:57:14 </td>
   <td style="text-align:left;"> $META BofA deez nuts upgrade their price target to $390 from $360. 

On track for $4 EPS Q4 2023

$SPY $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:50:36 </td>
   <td style="text-align:left;"> $ASTS -   🅰️     🛰️📱📶🌎     Connected. 
 
$AAPL  $TMUS   $T  $VZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:46:22 </td>
   <td style="text-align:left;"> $TSLA   $AAPL  
Only  Up  ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:46:05 </td>
   <td style="text-align:left;"> $NRGV Looks like the short sellers fucked around and found it. It&amp;#39;s called subsidies you morons. The company is Swiss (I&amp;#39;m Swiss-American) where they use &amp;quot;gravity&amp;quot; hydroelectric dams for the majority of their power. The Swiss bored the biggest tunnel in history.  
 
I have nothing to say about the bankers at $CS but I&amp;#39;m proud to say that my brother is working on m-RNA startup research in Zurich as we speak with a PhD in particle physics and the fact that the ultra secret $AAPL lab is located within ETH in Zurich. Do you know that is one of the most prestigious schools in Europe and if you are Swiss you get to go for $1,200 CHF a semester to any university you want. 
 
Look at all the successful European Companies. I made a huge bet on $ONON with shares and calls. Long since sold the calls but my current cost basis is $17/share and let me tell you no one wants anything at $DKS (the largest sports retailer) except Hoka, Nike or ON at retail price. They sell running shirts for $80! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:44:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:42:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:39:06 </td>
   <td style="text-align:left;"> $AAPL Ahoy there apple lovers! The Viking says Mango is considered as the King of fruits in some parts of the world. If you want mangoes, come to Mangoceuticals $MGRX . Their cool product is called a Mango. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:38:00 </td>
   <td style="text-align:left;"> $TSLA rule Number one never fall in love with any stock  
follow the trend. 
 
this will start to retreat before moving up 
 
time to sell and buy back $210-220 range 
 
$AMD $NIO $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:29:17 </td>
   <td style="text-align:left;"> &amp;gt; **MY TOP WATCHES FOR TODAY!**

&amp;gt; **Other**

&amp;gt; $NVDA
&amp;gt; $ORCL
&amp;gt; $PYPL
&amp;gt; $AAPL
&amp;gt; $ADBE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:26:16 </td>
   <td style="text-align:left;"> Friends, do you concur re just saying, I can&amp;#39;t stand the #fraudstreetboilerroommarketmakersandcronies&amp;#39; self serving, misleading, positive hopium jawboning trying to put a spin on a positive future 24×7 for stock markets  #mikesantoli https://www.cnbc.com/michael-santoli/ I wish #CNBC would give him the hook along with a few other circus 🤡🤡🤡 at https://www.cnbc.com/anchors-and-reporters/ #Santoli is paid approximately $150,000 per year versus the 🤡 of all 🤡🤡 #Cramer at $12,000,000 according to Google search.  Thank dog that I am here to help at no charge @Profit_Maker https://stocktwits.com/Profit_Maker 😁 $aapl $msft $amzn $meta $goog and more  ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:07:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 20:03:29 </td>
   <td style="text-align:left;"> My Option Watchlist For 06/12/2023   
  
$AAPL    
Calls:     
📈  at $180 - $179 
Puts:    
📉  at $184.36 - $184.95 if we get rejected  
  
$SPY    
Calls:   
📈  1st at $429.70 - $428.80 
📈  2nd at $426.70 - $426 
Puts:   
📉 at$431.80 - $431.99 if we rejected (resistance)   
 
$TSLA    
Calls:    
📈 at $235.20 - $233.32 
📈 above 253 
Puts:   
📉  below $241 
📉  at $251 - $252.42 if we get rejected (resistance)  
 
$AI    
Calls:    
📈 above $39.51 
📈at $36 - $35 
Puts: 
📉at $38.50 - $39.52 if we get rejected  
 
Let the setup come to you!  
Manage risk properly! cut losses quickly! And always take profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:53:09 </td>
   <td style="text-align:left;"> $NIO wait until the announcement with $AAPL .... 
 
https://todaysfive.com/nio-partnership-with-apple-likely-on-horizon/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:40:36 </td>
   <td style="text-align:left;"> $SPY lol newer bulls aren&amp;#39;t recognizing the level and longevity of rates

$AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:40:34 </td>
   <td style="text-align:left;"> $AAPL One of the main reasons people pile into the magnificent 7 is that they can&amp;#39;t be manipulated as much by short attacks from the douchebag suits on Wall Street. 
 
Market caps are too high to be fucked with. $MSFT $NVDA $AMZN $META </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:40:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

Got the headphones on, ready to enter that ofg state of mind 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:35:47 </td>
   <td style="text-align:left;"> $AAPL WE GOT 2 MONTHS OF GAINS COMING 🍏🥇👀🏦✅‼️😂🚀🚙👑👑👑👑👑👑👑👑👑👑👑👑👑👑🍏🍏🍏🥇🥇🥇🥇🍏🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:35:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

Getting ready to board my flight to Arizona. 🏜️ 

Tiny $$ bears will never know what it’s like to fly first class $$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:35:11 </td>
   <td style="text-align:left;"> $AAPL my calls for June 16, 30 picked up on Friday 😉 https://finance.yahoo.com/news/apple-made-smartphones-one-indias-092500790.html?.tsrc=rss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:32:06 </td>
   <td style="text-align:left;"> $SPY do people really not think inflation is dropping sharply? 
You&amp;#39;re going to get wrecked tomorrow if you&amp;#39;re short. $SPX $AAPL  
 
Today&amp;#39;s CPI Data by Truflation 
 
USA 
The USA Inflation Rate by Truflation is 2.75% 
https://truflation.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:29:47 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #2 stock that institutions traded this week with 533.0K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:26:30 </td>
   <td style="text-align:left;"> @magictape_behindwendys $SPY $TSLA $AAPL $QQQ 
 
I wish Stocktwits had a BET BUTTON to silence every broke idiot with a failed opinion. 
 
why should we have to endure 72 hours of BULLSHIT crash babble??? 
 
In real life EVERY single moron that opens their mouth like that gets run over, they get bet into the ground, they simply shut up because its too costly for them to be WRONG again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:24:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AAPL 

machine world $$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:21:45 </td>
   <td style="text-align:left;"> $AAPL TOI to fight cancer with help of AI 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:15:45 </td>
   <td style="text-align:left;"> $WLDS shorts are screwed on this low float ticker! 💯 $NASDAQ ctb is 800% 👀 $DJIA possible Apple buy out too! $AAPL @Stocktwits #squeeze #runiup #invest #stocks #money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 19:07:47 </td>
   <td style="text-align:left;"> $AAPL 😂👑👑👑👑👑🚀🚀🚀🥇🥇🍏🍏🍏🚙🚙🚙🚙🏦🏦🏦🏦🏦🕵️🕵️🕵️✅✅✅✅🏦🏦🏦🏦🤯🤯🚀🚀🚀😂😂😂🔥🔥🔥🔥👀👀👀👀✅✅✅🚙🚙🚙🍏🍏🥇🥇🚀🚀😂😂😂😂😂😂🚀🚀🚀🚀🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🥇🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏🍏LETS GOOOO WE BACK NEW HIGHSSSSS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 18:58:45 </td>
   <td style="text-align:left;"> $AAPL 1yr chart vs AT chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 18:55:50 </td>
   <td style="text-align:left;"> $AAPL 🚀 🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 18:41:10 </td>
   <td style="text-align:left;"> $AAPL 👁💚🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 18:16:33 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Elon Musk mocks Apple&amp;#39;s Vision Pro by taking a swipe at its price tag https://www.stck.pro/news/AAPL/52849056/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 18:01:45 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL when your personal investments portfolio gains for the first 5 months is already twice your yearly income, perhaps it’s time to retire? All I am doing is invest, stay invested and ignore the up and down of the market, nothing special really. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 17:53:36 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #2 ticker with sweep activity that institutions traded urgently this week options with 454.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 17:17:54 </td>
   <td style="text-align:left;"> $AAPL zoom out and it’s still buying time and you would be stupid to sell now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 16:46:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 16:17:23 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG $MSFT META $YEXT  fyi #yext 🐻❤😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 16:11:01 </td>
   <td style="text-align:left;"> $AAPL We will see new highs for some stocks today 👍🏻🟢

Will be amazing week ☘️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 16:02:49 </td>
   <td style="text-align:left;"> $AAPL it resumes higher from the blue box area and finished wave 3 at 184.95 high. It favors pullback in wave 4 before turning higher in 5 of (3). Chart from 5.30.2023 updates at https://elliottwave-forecast.com, #Elliottwave #Trading #Stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 15:42:57 </td>
   <td style="text-align:left;"> My track record for CHIP stocks. I have timestamps + buy fills for everything. What&amp;#39;s my win rate? 

My trading strategy is to buy the dip when Algos are tired of selling. I buy when &amp;quot;Heaviness %&amp;quot; by Algos is low. 

$NVDA + $AMD + $QCOM + $MU + $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 15:36:46 </td>
   <td style="text-align:left;"> $AAPL if anything can be learned from history! Sorry bulls, I am bearish in short term 🥸 testing $150-$160, if not lower 😌 $SPY $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 15:35:31 </td>
   <td style="text-align:left;"> $AAPL - great company just over-invested… VIX jumping, fear/greed index peaking,,, at over 30x p/e with decreased iPhone sales… it’s headed down…, time to exit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 15:25:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 15:21:12 </td>
   <td style="text-align:left;"> $AAPL yup it was only a matter of time 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 15:12:15 </td>
   <td style="text-align:left;"> $AAPL It is the day ☘️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 14:51:45 </td>
   <td style="text-align:left;"> $AAPL 200 very soon guys! 
 
https://www.interactivebrokers.com/mkt/?src=xiaowangNPY&amp;amp;url=%2Fcn%2Fwhyib%2Foverview.php </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 14:38:39 </td>
   <td style="text-align:left;"> $YEXT $aapl $dis $tsla $F and more.  😁 Good crash Monday morning my friends, followers, haters and those on block for jawboning nonsense, wasting broadband and my time. For your reading 🐻❤😈🤯😜 pleasure, let&amp;#39;s start with: 
▪Today&amp;#39;s WSJ headlines, print edition to follow in a few hours, @ https://intodayspaper.cmail20.com/t/d-e-vbikjy-jidrghyo-r/ 
▪REUTERS EU @ https://newslink.reuters.com/public/31761604 
▪Latest on the chip crisis | Suppliers still affected by pandemic, etc. from Automotive News @ https://link.autonews.com/view/62d92b9cbde45514f7087d3fiwr9n.38n/1bc6ea01 
▪Oil prices declined ahead of a U.S. Federal Reserve meeting as investors tried to gauge the central bank&amp;#39;s appetite for further rate hikes, while concerns about China&amp;#39;s fuel demand growth and rising Russian crude supply weighed on the market @ Refinitiv. 
▪More to follow.  Thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker ✔. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 14:30:26 </td>
   <td style="text-align:left;"> $AAPL thanks for the free AAPL shares, SoFi 😂 who doesn’t love free promos 

https://www.sofi.com/invite/invest?gcp=6a8612e3-a8ae-40a0-a482-279de12ecefa&amp;amp;isAliasGcp=false </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 13:55:47 </td>
   <td style="text-align:left;"> $AAPL what’s a great entry ? 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 13:45:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : LRT Capital Management May 2023 Investor Update https://www.stck.pro/news/AAPL/52831268/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 13:39:32 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 13:15:11 </td>
   <td style="text-align:left;"> $AAPL I just watched the promo video for the apple vision pro. It looks cool. I&amp;#39;m not a tech person but I&amp;#39;m probably going to get one just to see what I&amp;#39;m capable of making it do. It&amp;#39;s like an amplifier for whatever it is that you are doing. Exciting times we live in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 13:04:39 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Sets Sights On Retail And Enterprise Markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 13:02:53 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Google: Bing Fears Mask Explosive Upside Ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 12:30:12 </td>
   <td style="text-align:left;"> $AAPL thanks for the free AAPL shares SoFi 😂 love me some free promos 

https://www.sofi.com/invite/invest?gcp=6a8612e3-a8ae-40a0-a482-279de12ecefa&amp;amp;isAliasGcp=false </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 12:26:29 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AAPL brilliant! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 12:17:50 </td>
   <td style="text-align:left;"> $NVDA Now my favorite day trading stocks due to high stock price, 5K shares $5 either directions a day is good enough for e $24k daily profit avg not too bad. $AAPL $QQQ  
 
Tomo High $397.5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:57:11 </td>
   <td style="text-align:left;"> $AAPL whut does wazniack think about it tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:48:42 </td>
   <td style="text-align:left;"> $SPY $AAPL $NVDA $JPM  looooooooserrrrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:45:10 </td>
   <td style="text-align:left;"> $AAPL 
 
Same levels as last week more calls over 182, bearish under 177.5 but 179.5 might be. Bounce. Will see how the market develops with CPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:40:10 </td>
   <td style="text-align:left;"> $AAPL Vision Pro really does look like a game changer, will this disrupt television and monitor industries? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:34:36 </td>
   <td style="text-align:left;"> $AAPL I still got some 178s but wanted another spike to 184 to sell em.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:33:36 </td>
   <td style="text-align:left;"> $AAPL $SPY Dudes holy shit this thing is going to dominate and be a major game changer.  

https://youtu.be/TX9qSaGXFyg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:23:44 </td>
   <td style="text-align:left;"> $AAPL https://stocks.apple.com/A2SL4KbsLQ6qU4V84FFO5ew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:11:14 </td>
   <td style="text-align:left;"> $SPY just bought a new phone

Sorry $AAPL i bought another galaxy

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 11:02:12 </td>
   <td style="text-align:left;"> $AAPL Weekly view </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:56:10 </td>
   <td style="text-align:left;"> $AAPL $200+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:40:49 </td>
   <td style="text-align:left;"> How was your May? This is the result of ONLY buying when H% is low. 

$SPY $QQQ $TSLA $NFLX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:37:07 </td>
   <td style="text-align:left;"> $AAPL $BUD $DIS  $NKE  
Diversity=Biz Acuity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:36:26 </td>
   <td style="text-align:left;"> $AAPL needs to get to 185.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:34:52 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $AAPL with Unusual Options Activity Alerted on $105 CALL Expiring: 09-15-2023 worth 63K🐂 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:24:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 8.03%. $AAPL outperforms 93% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:13:49 </td>
   <td style="text-align:left;"> @RAMaDAMNdingDONG I don&amp;#39;t trade options, too risky, greater safety trading on full marging long and short $f $dis $tsla $yext $aapl and more active 🐻❤😈😜🤑💲💰✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:10:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LCID vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:07:16 </td>
   <td style="text-align:left;"> 😁 Hee haw, blow me long, lol, #fraudstreetboilerroommarketmakersandcronies re must read @ https://www.forexlive.com/centralbank/bank-of-america-say-they-remain-bearish-us-stocks-investors-are-too-bullish-fed-not-done-20230612/ hee haw, 🐻⛺❤😈🤯 $aapl $F $TSLA $YEXT $dis and more overpriced unregulated manipulated stocks ... thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker ✔ Stock Futures 
https://www.investing.com/indices/indices-futures 
Stock Market Index 
https://www.investing.com/indices/major-indices 
Energy Futures Prices 
https://www.investing.com/commodities/energy 
Trading Economics 
https://tradingeconomics.com/ 
Finviz News 
https://finviz.com/news.ashx 
Reuters News 
https://www.reuters.com/news/archive/businessNews 
CNBC News 
https://www.cnbc.com/latest/ 
Investingcom News 
https://www.investing.com/news/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:06:12 </td>
   <td style="text-align:left;"> $spy $qqa $aapl $meta $nvda

Watch out... 

&amp;#39;Don&amp;#39;t chase this equity rally&amp;#39;: Wells Fargo outlines the risks for stocks

https://www.cnbc.com/2023/06/12/dont-chase-this-equity-rally-wells-fargo-says-there-are-risks-for-stocks-ahead.html?__source=androidappshare </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:04:27 </td>
   <td style="text-align:left;"> $WIMI $AAL $AAPL This week big big week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 10:02:41 </td>
   <td style="text-align:left;"> Many times I get a question &amp;quot;What is low H%?&amp;quot; This visually shows exactly what it is and why I ONLY buy when H% is low.
$BYND $TLRY $XPEV $MP
Got timestamps and buy fills for the skeptics

The result speaks for itself
These are just 4 from many other tickers I&amp;#39;ve traded. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:56:16 </td>
   <td style="text-align:left;"> $AAPL $JPM $NVDA $SPY FED is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:55:43 </td>
   <td style="text-align:left;"> $AAPL $WIMI Find a new soft persimmon to pinch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:54:46 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:53:18 </td>
   <td style="text-align:left;"> $SPY fed gonna finish the job,, 

couple more cuts coming, housing market way way up still 

$AAPL $NVDA $JPM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:38:46 </td>
   <td style="text-align:left;"> My alerts for LARGE caps.This shows the result of ONLY buying when H% is low.
I have timestamps + buy fills for everything

$TSLA + $AAPL + $NKE are just few of many I&amp;#39;ve traded. $SPY 
I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:29:26 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $NFLX $NVDA  mwahahha facts my bro. It&amp;#39;s been tough for them actually longer, about 6-8 months. Markets reversal began in October. We are now in a &amp;quot;bull market&amp;quot; type run for the past 7 months, soon to be 8. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:20:58 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NVDA BYD in April unveiled its new Seagull EV that it will market in China later this year for a little over $11,000 to make it the least expensive EV in the world. It hasn&amp;#39;t said when it might begin selling the vehicle in Europe or other parts of the world.

https://www.thestreet.com/electric-vehicles/tesla-chinese-rival-produces-its-first-electric-suv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:18:42 </td>
   <td style="text-align:left;"> $TSLA $AAPL    
Watch  $GME  Melt  up  
 History  in  repeat  ;)  $Spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 09:04:23 </td>
   <td style="text-align:left;"> $AAPL $TSLA $TGT $NKE Trading is like GOLF!
Takes work, Education, and determination…. Plus a great support group!
OP is all that 

https://instagram.com/stories/optionsplayers/3123176303116656957?igshid=MzRlODBiNWFlZA== </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:56:54 </td>
   <td style="text-align:left;"> $AAPL 177 support being held. As indicated last week. Push against BBs are always bound to come in. If not major drawdown, expect choppiness. Note it is still holding above 5 day EMA which shows strength while $MSFT closed below 13 day EMA. To be seen how many days it can last. MACD flipping over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:55:05 </td>
   <td style="text-align:left;"> First time in the last 7-8 weeks we&amp;#39;ve seen this concerning pattern on the $AAPL chart.

And remember, we did hit all-time highs, so a pullback is expected.

But the market typically follows Apple, so keep your eye on this if you&amp;#39;re trading. Video
 https://twitter.com/the_rocktrading/status/1668025286393229312?s=46&amp;amp;t=TuenkWtzdRNZ4v8huOlDFQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:51:07 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:46:19 </td>
   <td style="text-align:left;"> &amp;gt; **MY TOP WATCHES FOR THIS WEEK!**

&amp;gt; **Other**

&amp;gt; $NVDA
&amp;gt; $ORCL
&amp;gt; $PYPL
&amp;gt; $AAPL
&amp;gt; $COIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:44:49 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - S&amp;amp;P 500 Officially Enters Bull Market: Unstoppable Surge Or House Of Cards? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:44:44 </td>
   <td style="text-align:left;"> $AAPL /    https://stocks.apple.com/A2SL4KbsLQ6qU4V84FFO5ew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:44:04 </td>
   <td style="text-align:left;"> $SPX $SPX $SPY As indicated last week -- bump against BBs are the limit where one should exercise caution. This week BB upper is ~4334 before it pushes back.  The SPX  chopped sideways bouncing along 5 day EMA. Support around 4198 and then 4166. MACD seems to roll over. Big Eco Week demands caution and unwinding of leveraged trades given the fact the VIX is so low:  
- Huge Treasury Auction this week post debt ceiling approval may suck liquidity out  
- CPI Tue  
- PPI Wed  
- FOMC Wed  
- Quad Witching Friday!!  
   
Caution is the word. Any big pull back is opportunity to deploy cash to work!  $QQQ $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:43:38 </td>
   <td style="text-align:left;"> $AAPL  
 
 
https://stocks.apple.com/A2SL4KbsLQ6qU4V84FFO5ew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:43:11 </td>
   <td style="text-align:left;"> $AAPL He must have bought 185 calls 😆🍏🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:33:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $NFLX $NVDA 

Its a been tough 3 months for Bears 

McDonalds positions are filling up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:29:52 </td>
   <td style="text-align:left;"> $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:29:11 </td>
   <td style="text-align:left;"> $SPY  this week will break the stubborn bears. As soon as they cover and go long, we can crash. And not a minute sooner.

I’m guessing August/October this year.

Until then, buy the “fed pause” rally. Don’t fight the Momo.

$QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:25:17 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Sets Sights On Retail And Enterprise Markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:25:09 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Vs. Meta: Which VR Stock Is Better? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:23:16 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Google: Bing Fears Mask Explosive Upside Ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:21:50 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/stocktwits.html gained 53 new watchers today! - Check https://www.stockilluminati.com/aapl/miscellaneous.php for trend data </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 08:20:07 </td>
   <td style="text-align:left;"> $AAPL Wait for the 185 retest  
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 07:59:39 </td>
   <td style="text-align:left;"> $AAPL Huge sell off tomorrow guaranteed 😆🖕🍏🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 07:47:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 07:31:47 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA $QQQ bears are actually don&amp;#39;t trade with real money so they always feel ’better’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 07:23:02 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl 

just the messenger. trade based upon your own analysis haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 07:14:00 </td>
   <td style="text-align:left;"> $NVDA, $AAPL and $TSLA are the top gainers in the Nasdaq 100 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_20&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_Nasdaq_100_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 07:00:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:57:56 </td>
   <td style="text-align:left;"> $AAPL So is this ready to POP big yet ? 
 
COME ON POP !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:57:17 </td>
   <td style="text-align:left;"> $MARA I have money that cleared on Friday and will be buying shares on any dip in premarket and again during market hours tomorrow.   

Bitcoin is not under attack, sh’tcoins are and I say good riddance.  Much of that capital will flock to safety in bitcoin, Mara is a monster now in the mining space and with a cost per coin (hosting and power) around $15k they are profitable whether bitcoin is at $25k or $26k.  The low IQ market hasn’t figured it out yet, but I see a profitable Q2 happening here and waaaay more hash and expansion coming up in the very near future. 

Mara is the next $AAPL and $BTC.X is inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:46:27 </td>
   <td style="text-align:left;"> $SPY not bad at all $QQQ $AAPL 

Bearish reverts in placed 🩸🩸🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:33:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

GREATEST BEAR MARKET EVER!!! 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:33:28 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl

all bulls should just post bearish statements &amp;amp; make bears feel better &amp;amp; vice versa haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:25:35 </td>
   <td style="text-align:left;"> $AAPL #AAPL engaged LONG from our Daily Focus List on 5/11/23, using this posted chart pattern. The June 170 calls paid out +163% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:20:37 </td>
   <td style="text-align:left;"> Equity Sentiment Weekly Recap: $AAPL is the #2 stock that institutions traded this week with 533.0K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 06:19:42 </td>
   <td style="text-align:left;"> $AAPL A must read by Puck (Baratunde Thurston)

https://puck.news/apples-beautiful-lonely-vision/

“5000 patents went into making it” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:54:42 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LAZR vs $SPY is one example of many

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low. This is one example of LAZR.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:46:46 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LCID vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:33:41 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy Jun 16, 2023 $182.5 Calls 
Entry Price: $1.32 - $1.36 
Exit Price: $1.56 
Stop Loss: $1.16 
Potential ROI: 18% 
Estimated Hold Time: 54 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:24:38 </td>
   <td style="text-align:left;"> Why do traders lose 90% of the times? This shows VISUALLY how I get my reversal trade while 99% traders buy the random level.

Learn what it means to buy when H% is low.

$V $SPY $TSLA $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:24:18 </td>
   <td style="text-align:left;"> $AAPL: Broke all time highs last week and came back under. 182-183 tough resistance. Look for 179 level to act as support if we get pullback. Under 179, like the short for a move back to 176 level. Under 176, this has room back to 170. 
$SPY 
https://share.trendspider.com/chart/AAPL/52149rxlvic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:22:24 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG $MSFT $NVDA The narrative to keep the valuations of these companies will eventually matter. Especially because they are mega cap, the rule of numbers has long stopped supporting the rally thus far but it has continued against every risk metric, including imminent credit crunch.
One does not need to gamble, but use history as the guide to know that this is another wash, rinse, and repeat bull and bust run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:22:05 </td>
   <td style="text-align:left;"> $AAPL https://www.businessinsider.com/why-apples-high-price-for-vision-pro-is-smart-move-2023-6?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:15:16 </td>
   <td style="text-align:left;"> Momentum Indicator for $AAPL turns positive, indicating new upward trend 
https://tickeron.com/ticker/AAPL/?via=serhii </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:14:35 </td>
   <td style="text-align:left;"> $RNDR.X $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:11:30 </td>
   <td style="text-align:left;"> $AAPL It&amp;#39;s very Tesla like this pricing strategy. $3,500 will see the early tech adopters gobble them up . Then in a year or two prices will come down and appeal to most of the budget consious .  It&amp;#39;s called a skimming strategy and helps Apple profit from all segments of the market ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:08:40 </td>
   <td style="text-align:left;"> $JPM $AAPL $TSLA $SPY $BRK.B What is the result of buying when heaviness % is low?
See the Win/Lose ratio.

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
January (&amp;#39;23) = 0 loss.
December (&amp;#39;22) = 2 losses.
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps + buy fills for everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:04:42 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose
$BLNK vs $SPY is one example of many. 

This visually shows why I ONLY buy when H% is low instead of buying random levels
Algos are very complex, learn to buy only when H% is low 

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:03:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 8.03%. $AAPL outperforms 93% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 05:02:28 </td>
   <td style="text-align:left;"> $AAPL  needs to sell 300 thousand Vision Pro&amp;#39;s to return  $1 Billion in revenue... I think that&amp;#39;s very possible , especially in Asia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:53:06 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - S&amp;amp;P 500 Officially Enters Bull Market: Unstoppable Surge Or House Of Cards? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:52:34 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$MULN vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:51:55 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl

reverse psychology is about to f*ck with traders. better learn how to find / invest in great businesses, quickly. buy shares instead of shorting / buying puts &amp;amp; average down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:48:36 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:48:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : A top analyst says Apple is on the cusp of another monster sales cycle for the iPhone 15 and its share price will break more records https://www.stck.pro/news/AAPL/52798555/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:43:45 </td>
   <td style="text-align:left;"> $AAPL Up 27% in the last 6 mos. I blew that one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:32:39 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Sets Sights On Retail And Enterprise Markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:32:27 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Vs. Meta: Which VR Stock Is Better? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:30:24 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Google: Bing Fears Mask Explosive Upside Ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:18:43 </td>
   <td style="text-align:left;"> How was your March?
1 loss. You read that right.

This shows the Wins + Notable mentions + Losses

$SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 04:16:31 </td>
   <td style="text-align:left;"> $yext $aapl $f $tsla $dis ... all five are bloated stocks in queue to implode in tandem with dramatically higher interest rates incoming as will many other #fraudstreetboilerroommarketmakersandcronies companies  ... enjoy the Autogeddon Armageddon Recession and crash Monday and beyond  ... 🐻❤😈🤯😜 ... 2023 FOMC Meetings 
6.13,14.23 
7.24,25.23 
9.18,19.23 
10.31-10.1.23 
12.12,13.23 
FOMC statement on the second day of each meeting at 2 PM. https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm ... thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker  ... Stock Futures 
https://www.investing.com/indices/indices-futures 
Stock Market Index 
https://www.investing.com/indices/major-indices 
Energy Futures Prices 
https://www.investing.com/commodities/energy 
Trading Economics 
https://tradingeconomics.com/ 
Economic Calendar 1 
https://www.investing.com/economic-calendar/ 
Finviz News 
https://finviz.com/news.ashx 
Reuters News 
https://www.reuters.com/news/archive/businessNews 
Investingcom News 
https://www.investing.com/news/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:54:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:45:26 </td>
   <td style="text-align:left;"> $AABB apple is going in to the web 3 space and meta aabb is poised to benefit from the transition to web 3 they are in the spaces already $META  
$AAPL $INTC  
 
https://www.cnbc.com/2023/06/11/what-apples-entry-into-virtual-reality-means-for-meta-platforms.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:41:21 </td>
   <td style="text-align:left;"> Fresh Momentum Monday 
 
I fleshed out some ofmy thknking about trends In tech, tesla and crypto ...you might enjoy  
 
$AAPL $COIN $TSLA $BTC.X $DKNG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:30:58 </td>
   <td style="text-align:left;"> 20 mins YouTube Stock Market Technical Analysis:                                                 
https://youtu.be/ELHCBVScXUk 
Subscribe on YouTube for daily market updates &amp;amp; plays  
 
- TSLA bulls 4 hour time frame 12 EMA full bull control, Bears need to form a hourly downtrend as first step 
- NVDA bull break lacking follow through, bears still need to confirm that hourly downtrend as well 
- $AAPL holding 2 day time frame EMA 12 full bull control 
- $GOOGL $MSFT $AMZN - potentially shaping up a daily downtrend 
$META </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:20:17 </td>
   <td style="text-align:left;"> $AABB You can add how many buys to your long position if you like such as @Goodgrief8 100++ buys! Hey MM&amp;#39;s were HOLDING/ACCUMULATING and tomorrow you will see our shareholder base is the strongest OTC with loyal shareholders holding/accumulating with massive conviction &amp;amp; patience! This group is as strong and long as the best stocks of the past performed from infancy like $TSLA $AAPL $LLY $AMZN investors stayed strong &amp;amp; long!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:15:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $AAPL 

#PivotPointServer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:08:40 </td>
   <td style="text-align:left;"> Blow me long $yext  ... -21% downside incoming  ... 🐻❤😈🤯😜 ... https://www.marketbeat.com/stocks/NYSE/YEXT/ ... $nvda $aapl $msft $amzn and more ✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:06:56 </td>
   <td style="text-align:left;"> $AAPL will they HAVE A SALE  on THE SUNGLASSES SOON ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 03:05:43 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy Jun 16, 2023 $182.5 Calls 
Entry Price: $1.32 - $1.36 
Exit Price: $1.48 
Stop Loss: $1.16 
Potential ROI: 12% 
Estimated Hold Time: 72 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:57:00 </td>
   <td style="text-align:left;"> In G3 Weekend Video, we explained that next week is going to be an interesting week for the #Dollar. We expect bounces to find sellers and that will support #indices and #stocks. #Elliottwave $SPY $QQQ $AAPL $TSLA $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:56:21 </td>
   <td style="text-align:left;"> $AAPL weekly candle closed above 180 for the first time last week. closed above 180 again this week. is this bullish or bearish? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:54:19 </td>
   <td style="text-align:left;"> Good Afternoon and welcome to Elliottwave Forecast. We cover all major asset groups around the clock, including Forex, Commodities, CryptoCurrency, World Indices, U.S. stocks &amp;amp; ETFs. Check us out at https://elliottwave-forecast.com/amember/go.php?r=34991&amp;amp;i=l1 #Elliottwave #Stocks #Trading $AAPL $TSLA $SPX $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:50:42 </td>
   <td style="text-align:left;"> How was your February?
0 loss. You read that right.

This shows the Wins + Notable mentions + Losses

$SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:47:14 </td>
   <td style="text-align:left;"> $SPY ~ Front page of Barrons June 10. Move your stops up. We have been in a bull market since Jan 2023 when the Macro downtrend line was broken to the upside. Most bear market declines happen after the first Fed rate cut. That ain’t happening anytime soon. $DIA $QQQ $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:46:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:45:39 </td>
   <td style="text-align:left;"> $AAPL think this goes under $175 this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:20:41 </td>
   <td style="text-align:left;"> How was your January?
0 loss. You read that right.

This shows the Wins + Notable mentions + Losses

$SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 02:13:27 </td>
   <td style="text-align:left;"> $SPY $AAPL guess they arent getting the apple vision pro anytime soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:52:09 </td>
   <td style="text-align:left;"> $RIDE Short $AAPL Fck the Asian thieves; Foxconn shorted us, we short them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:48:30 </td>
   <td style="text-align:left;"> $AAPL Where do surfers learn to surf? At boarding school. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:45:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq CONTINUES with its nonsense HYPED FOMO OVERVALUATION. CAREFUL next week 
https://youtu.be/BtXrlA9mZWw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:35:37 </td>
   <td style="text-align:left;"> $AAPL focus on your dream!

WORK ON YOUR DREAM - Motivational Video by Les Brown, Eric Thomas, and Will Smith
https://youtu.be/T9jX79szyBE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:34:43 </td>
   <td style="text-align:left;"> My track record for CHIP stocks. I have timestamps + buy fills for everything. What&amp;#39;s my win rate? 

My trading strategy is to buy the dip when Algos are tired of selling. I buy when &amp;quot;Heaviness %&amp;quot; by Algos is low. 

$NVDA + $AMD + $QCOM + $MU + $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:32:26 </td>
   <td style="text-align:left;"> Sweep Options Activity Weekly Recap: $AAPL is the #2 ticker with sweep activity that institutions traded urgently this week options with 454.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:32:21 </td>
   <td style="text-align:left;"> @Stockpatience $TSLA $AAPL $BABA $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:21:47 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMZN $NVDA $MSFT  
&amp;quot;People are short you got a little bit of a ball squeeze going on.  You&amp;#39;re going into a June OPEX which is very important there&amp;#39;s a lot of open interest in those PUTS that drives all this buyback&amp;quot; 
 
Let&amp;#39;s see if we can tap SPY 4600  even it for just a moment . 
 
Blowoff Top &amp;quot;sponsored&amp;quot; by Shorts &amp;amp; Powell pause  
https://youtu.be/ypGuWlbwSJ0?t=15 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 01:10:41 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LCID vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-12 00:59:33 </td>
   <td style="text-align:left;"> $DIPGF - Should I keep both Datang International and Apple ( $AAPL ) in the same portfolio? https://www.macroaxis.com/invest/pair-correlation/DIPGF/AAPL/Datang-vs-Apple #portfolio_prospective #better_portfolio #diversify </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:49:47 </td>
   <td style="text-align:left;"> $TSLA 15min chart still doing the usual gap up, fade, dip buying, repeat. its a computer lol. tons of calls at 250. price hanging around. thin volume profile 250-286. possible squeeze imminent. still RSI very close to ATH, so watch closely.  
I want to move this money but this chart is still very bullish imo. could go sideways though and there are lots of breakouts in mid/small cap, so it&amp;#39;s a tough choice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:49:44 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $nvda $aapl

CPI tomorrow est 4.1% YoY 

WHAT IS YOUR CPI NUMBER FOR TOMORROW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:49:17 </td>
   <td style="text-align:left;"> $TSLA all up bc leaks of fed pause </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:49:02 </td>
   <td style="text-align:left;"> $TSLA low key sick of 247 tho. It’s gunna be a all day thing today smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:48:27 </td>
   <td style="text-align:left;"> $TSLA green day, new record for 12 days dumbos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:48:19 </td>
   <td style="text-align:left;"> $TSLA feels like Algos in control today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:48:18 </td>
   <td style="text-align:left;"> $AMD CPI data pre market tomorrow, then AI event in the morning. Allin here $TSLA and $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:48:09 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #2 ticker with sweep activity where institutions are trading options urgently with 42.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:47:15 </td>
   <td style="text-align:left;"> $TSLA 

bulls buying rips today 🍆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:45:35 </td>
   <td style="text-align:left;"> $PLTR will increase 1000% in the next year from these levels. We have partnerships and news that will hit regularly. Target p[rices getting lifted, a league of its own. $TSLA $SOFI $CVNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:45:33 </td>
   <td style="text-align:left;"> $TSLA everything is pumping hard.  250 coming soon soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:45:29 </td>
   <td style="text-align:left;"> $AABB $SPY $QQQ $TSLA $AMZN &amp;lt;&amp;gt;&amp;lt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:44:58 </td>
   <td style="text-align:left;"> $BLNK $CHPT should double when news catches on, $TSLA sympathy play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:44:51 </td>
   <td style="text-align:left;"> $TSLA everything is ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:44:13 </td>
   <td style="text-align:left;"> $TSLA lets goooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:44:01 </td>
   <td style="text-align:left;"> $TSLA feeling good today, holding strong 😤😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:43:53 </td>
   <td style="text-align:left;"> $TSLA let’s break 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:43:46 </td>
   <td style="text-align:left;"> $TSLA bears are gunna be pissed when they pamps power hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:43:30 </td>
   <td style="text-align:left;"> $TSLA lmao only up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:43:27 </td>
   <td style="text-align:left;"> $TSLA looks like a runner within next 45 mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:43:19 </td>
   <td style="text-align:left;"> $TSLA market is turning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:42:30 </td>
   <td style="text-align:left;"> $TSLA  @GammaNoodles has spoken. @teambullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:41:08 </td>
   <td style="text-align:left;"> $TSLA   

BRUTALLY BEAT 🐻 🐻‍❄ 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:40:22 </td>
   <td style="text-align:left;"> $TSLA LMFAOOO “ trust me bro” 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:40:10 </td>
   <td style="text-align:left;"> $TSLA Nas is Ripping !!! We&amp;#39;re gonna fly any second !!   over 255 today ;-)  OH YEAH !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:40:00 </td>
   <td style="text-align:left;"> $TSLA only way this drops if bill gates doubles his short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:39:43 </td>
   <td style="text-align:left;"> $TSLA Lol $257 squeeze ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:39:41 </td>
   <td style="text-align:left;"> $tsla $500 leaps 🧹  $12/19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:39:36 </td>
   <td style="text-align:left;"> $TSLA 

TATE 

https://youtu.be/HUYp5Gkomng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:39:30 </td>
   <td style="text-align:left;"> $TSLA THIS THING IS TURTLE 🐢 TAIL IN HARD NOW FOLKS 🫵🫵🫵🫵🫵🥇🥇🥇👏👏😂😂😂👌👌🤘🤘👍👍👍💵💵💵💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:39:19 </td>
   <td style="text-align:left;"> $TSLA looks like Algo&amp;#39;s  are in control here sideways all day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:38:31 </td>
   <td style="text-align:left;"> $TSLA ez money 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:38:30 </td>
   <td style="text-align:left;"> $TSLA she’s due for a red day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:38:13 </td>
   <td style="text-align:left;"> $TSLA shorts trying hard to hold it down but lil they know, they’re F’d‼️‼️‼️‼️‼️🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:38:00 </td>
   <td style="text-align:left;"> $TSLA has an average volume of 132584000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:37:27 </td>
   <td style="text-align:left;"> $TSLA Big $$$ is squashing every pop now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:37:18 </td>
   <td style="text-align:left;"> $TSLA pinned at 247 and bears are saying it’s dropping lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:37:15 </td>
   <td style="text-align:left;"> $TSLA 250 this PUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:36:42 </td>
   <td style="text-align:left;"> $TSLA lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:36:17 </td>
   <td style="text-align:left;"> $TSLA nice slow drip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:36:03 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:35:59 </td>
   <td style="text-align:left;"> $TSLA There’ll be a huge stop loss hunt beyond $250. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:35:58 </td>
   <td style="text-align:left;"> $TSLA  after lunch it will run ! Get in now while it’s chillin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:35:42 </td>
   <td style="text-align:left;"> $TSLA flagging on the weekly bullish i dont care </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:35:23 </td>
   <td style="text-align:left;"> $TSLA bears getting all excited when this drops 0.5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:35:08 </td>
   <td style="text-align:left;"> $TSLA earnings are July.  19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:34:54 </td>
   <td style="text-align:left;"> $TSLA 

My option call break even 248.55 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:34:29 </td>
   <td style="text-align:left;"> $TSLA ‘keeps crashing’ 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:34:25 </td>
   <td style="text-align:left;"> $TSLA at this rate everyone thinking nio yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:34:18 </td>
   <td style="text-align:left;"> $TSLA we&amp;#39;re moving inversely to the indices. Weird </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:33:52 </td>
   <td style="text-align:left;"> $TSLA NASDAQ rising and this keeps crashing 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:33:46 </td>
   <td style="text-align:left;"> $TSLA bought 300 filler calls for July 21 want to be in for the earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:33:39 </td>
   <td style="text-align:left;"> $TSLA now i know why black eyed peas made that song cuz this thing keeps runnin runnin and runnin runnin and runnin runnin (up outta ya soul, lose control) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:33:36 </td>
   <td style="text-align:left;"> @MAgntW that’s my move for this week.
$TSLA $300 EOW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:32:47 </td>
   <td style="text-align:left;"> $TSLA  nice 👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:32:30 </td>
   <td style="text-align:left;"> $TSLA not too shabby.😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:32:19 </td>
   <td style="text-align:left;"> $APRN $SHOP $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:31:56 </td>
   <td style="text-align:left;"> $TSLA $250 is the key resistance level here. After a big gap up we’ll likely see a retest if that $225 support level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:31:40 </td>
   <td style="text-align:left;"> $TSLA LMFAO bulls wondering why it won’t go higher after a 90RSI print🤣🤣🐷🐷🐷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:31:38 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m getting terrible entry signals from my dog. I don&amp;#39;t know who can trade like this. I was told he learned on forex and was a beast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:31:04 </td>
   <td style="text-align:left;"> $TSLA going to lunch. f this shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:30:58 </td>
   <td style="text-align:left;"> $TSLA every single day the same scam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:30:52 </td>
   <td style="text-align:left;"> $TSLA if it was going to flush it would have done it already. Risk free calls literally never seen the like before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:30:35 </td>
   <td style="text-align:left;"> $TSLA the correction was when it hit 109 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:30:09 </td>
   <td style="text-align:left;"> @TwoSeasonsLimited $TSLA hasnt been red in weeks.  IDK who you think youre fooling?  If bears are excited because $TSLA only does 1% some days then you are beyond desperate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:29:49 </td>
   <td style="text-align:left;"> $TSLA wow bulls 100 k calls at 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:29:48 </td>
   <td style="text-align:left;"> $TSLA this will dump $17 in seconds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:29:43 </td>
   <td style="text-align:left;"> $TSLA selling when get to $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:29:20 </td>
   <td style="text-align:left;"> $TSLA holy crap this thing is overbought needs to pull back for real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:29:19 </td>
   <td style="text-align:left;"> $PLUG $tsla need 12.50 to recover 3 months:) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:28:54 </td>
   <td style="text-align:left;"> $TSLA where are the robo taxis 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:28:18 </td>
   <td style="text-align:left;"> $TSLA it’s no Pontiac people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:27:56 </td>
   <td style="text-align:left;"> $TSLA Bears really thought they were going to get some money back today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:27:52 </td>
   <td style="text-align:left;"> $TSLA reality is ATH coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:27:30 </td>
   <td style="text-align:left;"> $TSLA $319 EOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:26:35 </td>
   <td style="text-align:left;"> $TSLA gap close after FOMC? or just nonstop squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:26:06 </td>
   <td style="text-align:left;"> $TSLA OK STOP FUCKING AROUND NOW AND PUNCH IT TO 260 BITCH !!!! 
 
WHO&amp;#39;S DYING TO REALLY FUCK UP SHORTS ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:25:43 </td>
   <td style="text-align:left;"> $TSLA another great day of tessy scalps = 5,839 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:25:43 </td>
   <td style="text-align:left;"> $TSLA please help this stock needs more pumpers, who will join the FOMOA BUYERS AND buy more at 90 RSI?? Anyone? $SPY 🤣🐖🐷😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:25:38 </td>
   <td style="text-align:left;"> $spy $tsla $aapl $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:25:33 </td>
   <td style="text-align:left;"> $TSLA anyone dare to buy $300 calls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:25:25 </td>
   <td style="text-align:left;"> $TSLA every single day it’s green what makes you think it’s gunna be red today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:25:13 </td>
   <td style="text-align:left;"> $SOFI still holding but pullback imminent - holding for few years but already 100% 🔥👌 $SPY $QQQ $TSLA 

Congrats if you jumped in 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:24:47 </td>
   <td style="text-align:left;"> $TSLA making deals with other auto makers presents a whole new value segment. The market has to consider not just ford and GM but the possibility of other deals going forward. E.g. ‘what if Tesla licenses its battery tech to other automakers?’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:24:21 </td>
   <td style="text-align:left;"> $SPY A great way to see that the moves are PM&amp;#39;s trying to catch up &amp;amp; are just chasing now is how $tsla over 90 RSI is still getting a bid.  
Even  if Quants are able to set that up as a Buy its def fast money. 
 
The Market is being bought because its being bought, that cant end well 
 
$qqq $nvda $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:23:37 </td>
   <td style="text-align:left;"> $TSLA next gap to fill 260$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:23:29 </td>
   <td style="text-align:left;"> $TSLA nah 300 then 325 within next 2 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:23:23 </td>
   <td style="text-align:left;"> $AABB Best performing stocks from infancy investors buying are $MNST $LLY $TSLA $AAPL as $AABB infancy investors will be also when all is said and done! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:22:56 </td>
   <td style="text-align:left;"> $TSLA let’s see 225-235 this week..before it sees 265$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:22:33 </td>
   <td style="text-align:left;"> $TSLA This is much more than just a car company.

Only reason it went below 200 was because Elon bought Twitter. Will soon be at all time high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:21:59 </td>
   <td style="text-align:left;"> Day highs here in $NXGL 🙌🏼 , another insider buy today from Scott Henry!! If you don’t know who he is , do some research 💻 Only a 4 million float here with 8 insider buys inside 14 days … NO BRAINER 🧠 once we are over $3, $4… then $5 then $8-$10 here !! 

$TSLA running recently with $SOFI and $PDD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:21:35 </td>
   <td style="text-align:left;"> $TSLA bulls always tell each other to follow smart money, but then blame the market manipulation as soon as the portfolio goes red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:21:27 </td>
   <td style="text-align:left;"> $TSLA no need to be clowns 🤡 and pump it! It pumps itself with fanbois! Look 👀 when it dumps! Sky is not the limit! It won’t go to the Moon, even if it goes, it comes back! What goes up must go down! Simple physics! Insider dump is coming anytime $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:21:11 </td>
   <td style="text-align:left;"> $TSLA $225 then $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:21:09 </td>
   <td style="text-align:left;"> $TSLA will probably be stuck in the 240&amp;#39;s all month. Might even dip into 230&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:20:27 </td>
   <td style="text-align:left;"> $TSLA do have upside gap at 260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:19:59 </td>
   <td style="text-align:left;"> $TSLA 

The stock Trend Angle trajectory is at 79° - this is inline with all near vertical moves since inception 76°-82° angle ! 

This is Tesla ! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:19:05 </td>
   <td style="text-align:left;"> $TSLA rsi is going to 100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:18:44 </td>
   <td style="text-align:left;"> $TSLA yes this is prolly touching 270 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:18:39 </td>
   <td style="text-align:left;"> $TSLA best sign of price strength: daily MACD about to cross back into positive territory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:18:39 </td>
   <td style="text-align:left;"> $TSLA 20 straight days I’ll be concerned but the Rev increase for the foreseeable future is just way way too good to pass up rn. 250 is a steal I’m not even speaking in hyperbole. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:18:35 </td>
   <td style="text-align:left;"> $TSLA and we are back! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:18:24 </td>
   <td style="text-align:left;"> Covered Call Alert: TESLA  INC. $TSLA returning up to 27.34% through 17-Nov-2023 https://ideas.quantcha.com/?p=23048 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:18:14 </td>
   <td style="text-align:left;"> $TSLA when u quote CNBC, u need to recheck your comprehensive skillset </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:17:35 </td>
   <td style="text-align:left;"> $TSLA if you think 12 straight Green Day’s is normal I got a penny stock to sell you $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:17:33 </td>
   <td style="text-align:left;"> $TSLA entire Tesla fleet is lithium-ion powered. 
 
New Salt-ion batteries are here... 
 
https://www.youtube.com/watch?v=7tPWJxZsHuo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:17:14 </td>
   <td style="text-align:left;"> $TSLA longs are reinvesting and holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:17:12 </td>
   <td style="text-align:left;"> $TSLA $260 range before Fed, 275 w. OpEx
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:17:04 </td>
   <td style="text-align:left;"> $TSLA totally out of this now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:55 </td>
   <td style="text-align:left;"> $TSLA let’s see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:54 </td>
   <td style="text-align:left;"> $TSLA bears two weeks ago &amp;quot;this is a bull trap.&amp;quot; 
 
bears last week &amp;quot;this is a bull trap.&amp;quot; 
 
bears today &amp;quot;this is a bull trap.&amp;quot; 
 
imagine being so braindead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:39 </td>
   <td style="text-align:left;"> $TSLA come on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:37 </td>
   <td style="text-align:left;"> $TSLA The most overbought stock in market per CNBC.  
12 straight day up with RSI 90.  
Who is buying here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:29 </td>
   <td style="text-align:left;"> $TSLA pinned at 247 to fuck over puts . Then will pump hard power hour to 250 per usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:12 </td>
   <td style="text-align:left;"> $TSLA I’m telling y’all they’re gonna pump this to 300 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:07 </td>
   <td style="text-align:left;"> $TSLA pretty steady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:16:01 </td>
   <td style="text-align:left;"> $TSLA the beins are strong in this one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:15:51 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY look out shorts…Tesla is bull flagging on the intraday.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:15:05 </td>
   <td style="text-align:left;"> $RIVN CAN EXPLODE LIKE $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:14:57 </td>
   <td style="text-align:left;"> $TSLA nice bull trap 🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:14:44 </td>
   <td style="text-align:left;"> $TSLA she is holding up perfect we will be 300+ end of the week.. 🚘😎👑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:14:00 </td>
   <td style="text-align:left;"> $TSLA the poor poor bag holding bears, they tried so hard. it&amp;#39;ll blow through 250 in the next hour and so many covers will come in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:13:52 </td>
   <td style="text-align:left;"> $TSLA I just want to know if Boss Blunts is present on this feed? Anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:13:42 </td>
   <td style="text-align:left;"> $TSLA no red days here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:13:23 </td>
   <td style="text-align:left;"> $TSLA damn chop city </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:13:04 </td>
   <td style="text-align:left;"> $TSLA curling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:13:01 </td>
   <td style="text-align:left;"> $TSLA we should be to 290 pretty soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:12:54 </td>
   <td style="text-align:left;"> $TSLA little triangle forming …breaking out in an hr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:12:48 </td>
   <td style="text-align:left;"> $TSLA 

If you are buying today…you are a moron. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:12:20 </td>
   <td style="text-align:left;"> $TSLA Outperforming the AI&amp;#39; s $NVDA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:12:10 </td>
   <td style="text-align:left;"> $TSLA not a single share has been covered! Gamma squeeze the FSD. For the NACS plug, my guy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:11:34 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:11:19 </td>
   <td style="text-align:left;"> $TSLA $263 ✅✅✅✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:11:12 </td>
   <td style="text-align:left;"> $TSLA calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:10:13 </td>
   <td style="text-align:left;"> $TSLA today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:10:06 </td>
   <td style="text-align:left;"> $FSR  Oceans getting ready to be delivered. $LCID $NIO $TSLA 🍺 ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:10:05 </td>
   <td style="text-align:left;"> $TSLA EV stocks are up but Tsla? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:10:04 </td>
   <td style="text-align:left;"> $TSLA I think we’ll revisit the $220 area first before continuing higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:09:56 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $tsla $meta - 
 Treasury auction over 100 billion today  
  
treasurydirect.gov/auctions... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:09:42 </td>
   <td style="text-align:left;"> $TSLA 

256 EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:09:30 </td>
   <td style="text-align:left;"> $TSLA I’m bullish. But my contracts expired on Friday, and I need this to pull back to 220 so I can get back in. And bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:09:19 </td>
   <td style="text-align:left;"> $TSLA long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:09:04 </td>
   <td style="text-align:left;"> $TSLA - All of our technology is obsolete or off-planet which was stolen and reverse engineered, if the globalists cannot enslave us by metering it, they have not allowed it to come to the market.. 
https://www.dailymail.co.uk/news/article-12175195/Crashed-UFO-recovered-military-distorted-space-time.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:08:49 </td>
   <td style="text-align:left;"> $EVGO rebound incoming! I guess they figured out $TSLA cant do it all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:08:19 </td>
   <td style="text-align:left;"> $TSLA lol
U know its just a matter of minutes before it pops
If u been around enough, u should know this by now ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:07:55 </td>
   <td style="text-align:left;"> $TSLA 2 sells x 5 buys all week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:07:33 </td>
   <td style="text-align:left;"> $TSLA Everything feels a little too good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:07:29 </td>
   <td style="text-align:left;"> $TSLA this movement is my fav </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:06:39 </td>
   <td style="text-align:left;"> $TSLA  it&amp;#39;s the MM&amp;#39;s Algos. Controlled.
Has been. This is not meant to blow but rather crawl up and climb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:05:52 </td>
   <td style="text-align:left;"> $TSLA gotta fall a little. Needs to consolidate some before resuming uptrend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:05:50 </td>
   <td style="text-align:left;"> $TSLA 

Rolling over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:05:04 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #2 ticker with unusual activity from institutional traders with an average of 20% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:05:01 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl

if it was tough, you’d just let it go without a long post proving it haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:04:48 </td>
   <td style="text-align:left;"> $TSLA Seems bears trying really hard to keep this below $250. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:04:38 </td>
   <td style="text-align:left;"> $TSLA we’ll guess it’s pinned here all fucking day . Boring ass shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:04:20 </td>
   <td style="text-align:left;"> $TSLA shorts getting caught with their pants down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:03:56 </td>
   <td style="text-align:left;"> $TSLA reversing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:03:24 </td>
   <td style="text-align:left;"> $TSLA - Just a daily reminder of how we are all being enslaved, extorted and robbed unlawfully by Govt. criminals (Federal, State, Local) in every aspect of our lives!! We are not their F ATM machine!! The enslavement of humanity must end, enough is enough!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:03:15 </td>
   <td style="text-align:left;"> $TSLA easy 250 close, that chart is a beauty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:02:41 </td>
   <td style="text-align:left;"> $MULN https://investorplace.com/2023/05/get-ready-for-mullen-stock-to-go-high-in-july/ GET READY $F $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:02:00 </td>
   <td style="text-align:left;"> $TSLA anyone here recently buy a M3? I’m on the fence, but the financing rates suck. If tesla offered under 3% financing I’d be all over it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:01:40 </td>
   <td style="text-align:left;"> $TSLA no one knows anything, fact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:01:38 </td>
   <td style="text-align:left;"> $TSLA that was a nice trade since the Tesla lowest but American most loved cars by work force is pickups trucks no ugly trucks so wait and see how gm and ford leaves Tesla in the dust good luck 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:01:16 </td>
   <td style="text-align:left;"> $TSLA two consecutive 10 minute directs the direction and volume for rest of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:01:09 </td>
   <td style="text-align:left;"> $TSLA why so weak, no pump to 260? Come on pump it 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:00:51 </td>
   <td style="text-align:left;"> $TSLA Premiums are crazy high, not worth watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:00:46 </td>
   <td style="text-align:left;"> $TSLA two consecutive 10 minute dumps just started. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:00:42 </td>
   <td style="text-align:left;"> $TSLA feels  like  it  has  a $10+ drop  loaded  up  just  waiting  for  indexes  to  red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:00:33 </td>
   <td style="text-align:left;"> $MULN https://finance.yahoo.com/news/ready-mullen-stock-high-july-173007007.html GET READY $LCID $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 23:00:12 </td>
   <td style="text-align:left;"> $NIO Avg call flow , Previous day call flow , Today call flow . 
 
Go figure 🐝🙏 
 
$TSLA huge in Premium call flow as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:59:58 </td>
   <td style="text-align:left;"> $TSLA Bear trap! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:58 </td>
   <td style="text-align:left;"> $TSLA HERE WE GOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO 🤘🤘🤘🤘🫵🫵🥇🥇🥇🥇🥇🥇💵💵💵💵💵💵🤜🏼🤛🏿👏👏👏👏👏😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:47 </td>
   <td style="text-align:left;"> $TSLA wtf jjst go up enough of 247 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:45 </td>
   <td style="text-align:left;"> $TSLA There is a big buyer at the moment! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:43 </td>
   <td style="text-align:left;"> $TSLA $LCID $MULN small dilution(17m to 5B) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:42 </td>
   <td style="text-align:left;"> $TSLA such overbought dog shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:32 </td>
   <td style="text-align:left;"> $TSLA still holding strong from $170, won’t take profit until $260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Super choppy day- make the most of it and don’t overtrade. Nailed calls earlier. Back to just watching. Great start to the week💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:15 </td>
   <td style="text-align:left;"> $MULN its a small dillution compared to $TSLA $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:58:14 </td>
   <td style="text-align:left;"> $PEARQ should I buy a $TSLA M3 if this goes to 10c? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:57:58 </td>
   <td style="text-align:left;"> $TSLA a good day to jump in if youve been waiting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:57:57 </td>
   <td style="text-align:left;"> $TSLA 260 by earnings those who said 300 by the eow are delusional and bought in on the hype </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:57:29 </td>
   <td style="text-align:left;"> $TSLA been good   
💖 
Elon is amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:57:05 </td>
   <td style="text-align:left;"> $TSLA $250! Big buy volume coming in! Short covering.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:56:08 </td>
   <td style="text-align:left;"> $TSLA sideways today, time to sleep, cya bulls on the rocket in 2 days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:55:42 </td>
   <td style="text-align:left;"> $TSLA hey bears watch this video about the fraud Tesla implements

https://youtu.be/lD6ICmMRSL8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:55:14 </td>
   <td style="text-align:left;"> $TSLA SELL NOW OR RRGRET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:54:53 </td>
   <td style="text-align:left;"> $TSLA nice little pullback but bulls still winning overall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:54:42 </td>
   <td style="text-align:left;"> $TSLA aw. My calls still haven&amp;#39;t hit. I&amp;#39;ll pay a little extra I feel bad for sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:53:52 </td>
   <td style="text-align:left;"> $TSLA  240 test? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:53:49 </td>
   <td style="text-align:left;"> What You Missed This Week in EVs and Clean Energy - $TSLA - https://thefly.com/permalinks/entry.php/TSLAid3729704 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:53:32 </td>
   <td style="text-align:left;"> $TSLA gamblers and fortune tellers lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:53:02 </td>
   <td style="text-align:left;"> $CVNA YOU WANT A LAMBO ? SO GO FOR IT $AMC $GME $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:52:45 </td>
   <td style="text-align:left;"> $TSLA Did Ray Dalio Tesla? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:52:36 </td>
   <td style="text-align:left;"> $TSLA I’m sitting on a gold mine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:52:35 </td>
   <td style="text-align:left;"> $TSLA feels like a pull back may be coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:52:12 </td>
   <td style="text-align:left;"> $TSLA 
Govt subsidized EV + AI self driving + Govt subsidized Solar panels + govt induced grid failing battery backup + worldwide biggest and soon to be standard across the board charging network + no debt + expanding and hiring, not shrinking and laying off + self insurance + cash on hand in tens of billions + all this WITHOUT advertising, which will be happening soon = a great long investment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:51:47 </td>
   <td style="text-align:left;"> $TSLA Now in June 23, 245 puts at 865 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:51:10 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla Stock Could Set New Winning Streak https://www.stck.pro/news/TSLA/52868136/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:51:08 </td>
   <td style="text-align:left;"> $TSLA I won’t cover till $195-$210 

If the market keep dumping I hold them till $165. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:51:00 </td>
   <td style="text-align:left;"> $TSLA the brilliance of buying Twitter    12 days green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:50:40 </td>
   <td style="text-align:left;"> $TGT target will have a longer win streak then $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:50:05 </td>
   <td style="text-align:left;"> $TSLA Sticking with this 1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:50:04 </td>
   <td style="text-align:left;"> $TSLA that rejection lower was start of the squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:49:52 </td>
   <td style="text-align:left;"> They keep dumping in 10 minute batches $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:49:32 </td>
   <td style="text-align:left;"> $TSLA  you fucked up!!!!!!!!!!! Big-time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:49:23 </td>
   <td style="text-align:left;"> $TSLA 
Yep def was a BEAR TRAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:49:21 </td>
   <td style="text-align:left;"> $TSLA after 4 SOLID weeks of gains I&amp;#39;m expecting a sideways week.  Options are lining up that way as well. Looking to write the weekly $250 Calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:48:43 </td>
   <td style="text-align:left;"> $TSLA Track record for TSLA = 10 wins + notable mention / 0 loss. You read that right.
This shows the previous 4 trades showing EXACTLY how I did it. Step by step.

Got timestamp + buy fills for each trade for the skeptics.
The KEY is to buy when Algos hit &amp;quot;5% HEAVINESS&amp;quot; or lower. Learn what &amp;quot;Heaviness %&amp;quot; is by Algos.

Look at the:
1) time I alerted 
2) at what $ level 
3) Heaviness % by Algos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:48:06 </td>
   <td style="text-align:left;"> $TSLA teslas going to increase sales big time ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:47:51 </td>
   <td style="text-align:left;"> $SPY $tsla nice article about most overbought stock today this pig </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:47:40 </td>
   <td style="text-align:left;"> $TSLA predictions mean nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:46:40 </td>
   <td style="text-align:left;"> $TSLA 

Tesla stock is the only Tech stock that has NOT rebound back ti its ATH since 2021 and still trading 40% below it —

Talking heads talking about 2023 stock doubled -CNBC and others those are pushing disinformation- 

In 2022 Tesla stock lost 74% of its value and bottomed on 1/5/23 at 75% drawdown biggest loss the stock has suffered since inception — what you see now $735 is well below where the stock was 2021 $1243 vs $AAPL $NVDA $META 

BEWARE OF 🛑 DISINFORMATION!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:46:09 </td>
   <td style="text-align:left;"> Check out $NKLA $NIO $OZSC $TSLA 

Green Energy plays Finally Rebounding after 26 months 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:46:07 </td>
   <td style="text-align:left;"> $TSLA reversal soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:45:53 </td>
   <td style="text-align:left;"> $TSLA added more to shorts, $248 Avg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:45:48 </td>
   <td style="text-align:left;"> $TSLA obviously a lot more buyer, shorts waiting for every dip to buy/cover
GL 🍀 
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:45:21 </td>
   <td style="text-align:left;"> $TSLA going to $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:45:13 </td>
   <td style="text-align:left;"> $TSLA 12 straight green days🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:44:49 </td>
   <td style="text-align:left;"> $AVGO Jump back in on opening. Look for bounce back to $900.
$TSLA Clear out all my call options opening it was good profit but, need take break for few days. Stiil believes heading to $295.
$ORCL $ADBE Watching for ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:44:41 </td>
   <td style="text-align:left;"> $TSLA lol and flipped a single call to hedge my ones from this morning.  I love this place </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:44:32 </td>
   <td style="text-align:left;"> $TSLA should just let it go to $242 real quick and see if that will bounce first before anything else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:44:24 </td>
   <td style="text-align:left;"> $SPY $TSLA i read all weekend long that bear market is over. You know what that means! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:58 </td>
   <td style="text-align:left;"> $TSLA when Elon musk is back.  We know this will back to all time high soon or later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:56 </td>
   <td style="text-align:left;"> $TSLA HAAANNNNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:47 </td>
   <td style="text-align:left;"> $TSLA 🥳🥳🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:26 </td>
   <td style="text-align:left;"> $TSLA $PLUG Tesla lead on the recovery:) Congratulation! to all those that still holding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:25 </td>
   <td style="text-align:left;"> $TSLA I wouldn&amp;#39;t bet on this for AI. Better buy GOOG or MSFT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:24 </td>
   <td style="text-align:left;"> $TSLA caught 73k worth in the 245s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:22 </td>
   <td style="text-align:left;"> $TSLA he&amp;#39;s not out of money! Still sucking up sells for any and all prices! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:43:05 </td>
   <td style="text-align:left;"> $TSLA 5 Red Daily candles in a row will be nice!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:27 </td>
   <td style="text-align:left;"> $TSLA 
FSD is AI
AI is FSD
Finkle is Einhorn! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:20 </td>
   <td style="text-align:left;"> Tesla upgraded by KGI Securities to outperform. www.marketbeat.com/stocks/NASDAQ/TSLA/price-target/ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:19 </td>
   <td style="text-align:left;"> $TSLA it still hasn&amp;#39;t gone below positive for the day and bears are acting like they finally did it. please go get your heads checked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:07 </td>
   <td style="text-align:left;"> $TSLA here we go did u add </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:05 </td>
   <td style="text-align:left;"> $SQQQ $SPXS $UDOW $TSLA $NVDA  

“Bruh, just keep buying more…it’ll keep going up”

“As long as they keep saying AI, we make money”

“None of the macro stuff matters, bro…that’s old school thinking”

THIS CRASH WILL BE EPIC. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:04 </td>
   <td style="text-align:left;"> $TSLA maybe it will sell off $15 tonight 

Everyone flip to Poots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:03 </td>
   <td style="text-align:left;"> $TSLA SHARES SET FOR RECORD WINNING STREAK, LAST UP 1%
 $TSLA http://dlvr.it/SqYWCW #NEWS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:42:03 </td>
   <td style="text-align:left;"> $TSLA 235 today :-))))) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:55 </td>
   <td style="text-align:left;"> $TSLA Hilarious. Bears are out now giving free handjobs because it only up 0.5%. You can&amp;#39;t fix stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:52 </td>
   <td style="text-align:left;"> $TSLA that was awesome !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:49 </td>
   <td style="text-align:left;"> $TSLA put the bear in their place $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:45 </td>
   <td style="text-align:left;"> $TSLA Shorted 5 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:43 </td>
   <td style="text-align:left;"> $TSLA right back up to HOD lmao can’t make it up . That was a chance to reload calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:43 </td>
   <td style="text-align:left;"> $TSLA really happy with execution on this one today.. albeit small base hits, perfection! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:26 </td>
   <td style="text-align:left;"> $TSLA this stock is crazy, can’t even get a decent dip to add lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:23 </td>
   <td style="text-align:left;"> $TSLA nice trap! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:15 </td>
   <td style="text-align:left;"> $TSLA Sold at 1400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:41:12 </td>
   <td style="text-align:left;"> $TSLA What the fuck is up with this drop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:52 </td>
   <td style="text-align:left;"> $TSLA And... it&amp;#39;s back lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:47 </td>
   <td style="text-align:left;"> How was your May? This is the result of ONLY buying when H% is low. 

$SPY $QQQ $TSLA $NFLX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:43 </td>
   <td style="text-align:left;"> $TSLA check out volume accumulation at its finest people ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:32 </td>
   <td style="text-align:left;"> $TSLA KGI Securities upgrades Tesla to Outperform (from Neutral) with a $335 PT, ‘strong US advantage &amp;amp; AI prowess’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:30 </td>
   <td style="text-align:left;"> $TSLA HEY SHORTS 12 Days of GREEN. 😂😂😂😂🖕fuck you you negative Doom And Gloommers pieces of shit. Thank you for your money it’s only the beginning keeps shorting. fuck you.🖕 better go stock up on lube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:25 </td>
   <td style="text-align:left;"> $TSLA here&amp;#39;s where you buy.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:12 </td>
   <td style="text-align:left;"> $TSLA Elon must be selling like he usually does </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:07 </td>
   <td style="text-align:left;"> $TSLA can’t go up for 12 straight days the market makers won’t let it happen! short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:40:00 </td>
   <td style="text-align:left;"> $TSLA gotta sell some puts ..get then excited a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:53 </td>
   <td style="text-align:left;"> $TSLA all predictions are meaningless lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:48 </td>
   <td style="text-align:left;"> $BLNK $CHPT $DCFC $EVGO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:42 </td>
   <td style="text-align:left;"> $TSLA shorts better take profit reload time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:37 </td>
   <td style="text-align:left;"> $TSLA who just got trapped?! I think she’s gunna retest 220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:34 </td>
   <td style="text-align:left;"> $TSLA pull back now after fed it&amp;#39;s a wrap $280 to $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:30 </td>
   <td style="text-align:left;"> $TSLA IM OUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:30 </td>
   <td style="text-align:left;"> $TSLA Woohoo, for once I didn&amp;#39;t fall for the pump and chase.  I have buy orders waiting at $235 and $225.  Not sure if those will get filled today or not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:27 </td>
   <td style="text-align:left;"> $TSLA that was some BIG selling… Elon? Institutions? Massive short opening? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:21 </td>
   <td style="text-align:left;"> $TSLA so over this.  Soon as I buy it falls on its face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:18 </td>
   <td style="text-align:left;"> $TSLA DOWN 2% IN TEN MINUTES LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:09 </td>
   <td style="text-align:left;"> Bye byeeee see ya at 190s in a few weeks luv $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:07 </td>
   <td style="text-align:left;"> $TSLA buy more need you to throw more money at it short then </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:07 </td>
   <td style="text-align:left;"> $TSLA going red. she is getting dumped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:39:06 </td>
   <td style="text-align:left;"> $SPY Just looks like some covering &amp;amp; some chasing on the Open w/ Buying pressure from EU, 
 
Not something to put money into. These are not Investors this is fast in &amp;amp; out money 
 
Trade Smart 
 
$baba $nvda $tsla $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:58 </td>
   <td style="text-align:left;"> $TSLA adding more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:51 </td>
   <td style="text-align:left;"> $SPY 👀 $AI $KRE $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:48 </td>
   <td style="text-align:left;"> $TSLA please keep shorting 🙏🏻😍🩷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:42 </td>
   <td style="text-align:left;"> $SPY $TSLA LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:21 </td>
   <td style="text-align:left;"> $TSLA If Biden win again, watch out. lots of Vendetta coming for Musk who is just a tiny bit slightly pro-republican. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:17 </td>
   <td style="text-align:left;"> $TSLA we’re up $100 from last month we’re right here clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:38:01 </td>
   <td style="text-align:left;"> $TSLA 
Most likely going down !!! 
could be a Bear Trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:54 </td>
   <td style="text-align:left;"> $TSLA ............. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:51 </td>
   <td style="text-align:left;"> $TSLA 😱 I’m so scared lol 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:45 </td>
   <td style="text-align:left;"> $CHPT $DCFC $EVGO $BLNK $TSLA  
 
https://electrek.co/2023/06/09/white-house-throws-cold-water-tesla-nacs-victory/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:41 </td>
   <td style="text-align:left;"> $TSLA shorts winning now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:38 </td>
   <td style="text-align:left;"> $TSLA really like MMs adding me a short again $247.57 x 100 shares and now elevator down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:32 </td>
   <td style="text-align:left;"> $TSLA Elon and Co might be running out of money. 20 sessions of pumping which rivals the available liquidity of the world&amp;#39;s reserve currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:25 </td>
   <td style="text-align:left;"> $TSLA you do realize the current govt Democrats want this company totally gone right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:20 </td>
   <td style="text-align:left;"> $TSLA this is going to see $230 in seconds once the flush hit might even need to halt the stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:14 </td>
   <td style="text-align:left;"> $TSLA BOOOOOOOOOM 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:11 </td>
   <td style="text-align:left;"> AI Bot Boosts $TSLA by 6.2%: Aroon Indicator Predicts Further Rise 
https://tickeron.com/blogs/ai-bot-boosts-tsla-by-6-2-aroon-indicator-predicts-further-rise-9920/?utm_source=stocktwits_free&amp;amp;utm_medium=news&amp;amp;utm_campaign=compare_summary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:09 </td>
   <td style="text-align:left;"> $TSLA  $Nflx 🤫🤐😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:37:09 </td>
   <td style="text-align:left;"> $TSLA gambling clowns all around  
 
get a life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:36:46 </td>
   <td style="text-align:left;"> $TSLA WHERE DID ALL THE BULLS GO??? LMFAOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:36:43 </td>
   <td style="text-align:left;"> $TSLA I told you… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:36:42 </td>
   <td style="text-align:left;"> $TSLA here comes the red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:36:24 </td>
   <td style="text-align:left;"> $TSLA Imagine not selling at $250 again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:36:23 </td>
   <td style="text-align:left;"> $TSLA THE STREAK IS IN JEOPARDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:36:05 </td>
   <td style="text-align:left;"> $TSLA  Bought July 7, 245 puts at 1295 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:35:56 </td>
   <td style="text-align:left;"> KGI Securities upgrades Tesla $TSLA from Neutral to Outperform and announces a price target of 
https://marketsblock.com/tesla-tsla-stock-price-target/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:35:55 </td>
   <td style="text-align:left;"> $TSLA Tesla has technically TOPPED OUT - come short for FREE MONEY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-12 22:35:51 </td>
   <td style="text-align:left;"> $TSLA selling here. Not gonna risk it. Will try again at 220 </td>
  </tr>
</tbody>
</table></div>

---
