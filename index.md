---
output:
  html_document:
    keep_md: true
---

# Financial Data Analytics Portfolio

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



Last Updated: 2023-06-09 22:03:36 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 21:57:08 </td>
   <td style="text-align:left;"> Canadian Shares Retreat on Friday </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite index was slightly lower to trade below the 19,925 mark on Friday, setting up a 0.4% drop on the week with losses for gold miners and consumer staples as markets digested the latest labor data for insights on the BoC’s policy outlook. The Canadian unemployment rate rose to 5.2%, above expectations of 5.1% to mark the first increase in the jobless rate since August 2022. The data raised concerns over the resilience of the Canadian economy to higher interest rates following the BoC’s surprise hike this week. Gold miners led the losses on the corporate front, pressured by lower bullion prices with a 1% drop for Barrick Gold and a 1.6% slide for Agnico Eagle Mines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/aluminum </td>
   <td style="text-align:left;"> 2023-06-09 21:49:14 </td>
   <td style="text-align:left;"> Aluminum Futures Remain Subdued </td>
   <td style="text-align:left;"> Aluminum futures have been trading within the range of 2,200 to 2,300 USD per metric ton as traders anticipate a more balanced Chinese aluminum market following the deficit in 2022. A key factor emerging in this market is the province of Yunnan, which has significantly increased its annual output capacity in the past five years. However, the region's aluminum production is now threatened by a severe decline in rainfall, leading to multi-decade lows in hydroelectric power output. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/regional-bank-stocks-flash-signs-of-life-in-fourth-weekly-gain </td>
   <td style="text-align:left;"> 2023-06-09 21:45:33 </td>
   <td style="text-align:left;"> Regional Bank Stocks Flash Signs of Life in Fourth Weekly Gain </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Breanna Bradham                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , A stock market sector that investors furiously bailed out of just months ago is slowly making a comeback.                                                                                                                                                                                                                                                                                                                                                                                                                                            , Regional bank stocks are set to notch their fourth weekly gain in a row, tying a January streak as a revival in bond sales from the group reinforced bank resilience. While the sector is far from recouping the losses that Silicon Valley Bank’s collapse in March inflicted, the fresh debt sales mark the latest sign that the sector is buckling down for future pressures while distancing itself from the tumult. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 21:36:21 </td>
   <td style="text-align:left;"> US Stocks Mixed to End the Week </td>
   <td style="text-align:left;"> US stocks were mixed on Friday, with the Dow Jones falling nearly 50 points, while the S&amp;P 500 edged slightly higher after entering bull market territory the day before, and the Nasdaq added 0.5%. Investors refrain from making big bets ahead of key US CPI report and the FOMC decision next week. On the corporate front, Tesla shares rallied nearly 6% and General Motors was up over 5% after the latter announced it will use Tesla technology to charge its electric vehicles. On the other hand, stocks of Target lost over 1% after Citigroup analysts cut their rating. So far on the week, the Dow is up 0.2%, the S&amp;P 500 gained nearly 0.3% to book a fourth straight week of gains while the Nasdaq is little changed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 21:25:00 </td>
   <td style="text-align:left;"> Ukraine Inflation at Fresh Lows </td>
   <td style="text-align:left;"> The annual inflation rate in Ukraine eased for the fifth month to 15.3 percent in May 2023, following 17.9 percent in April 2023 and marking the lowest reading since February 2022. Consumer prices slowed for 10 out of 12 categories thanks to weaker consumer demand and stabilizing energy sector, with the most marked impact observed in food &amp; non-alcoholic beverages (20.1 percent vs 22.2 percent in the previous period), restaurants &amp; hotels (19.4 percent vs 21.9 percent), miscellaneous goods &amp; services (17.9 vs 18.1percent), and transportation (10.9 percent vs 23.6 percent). On the other hand, the cost rose slightly for health (14 percent vs 12.1 percent) while remaining unchanged for education (at 9.6 percent). On a monthly basis, inflation accelerated to 0.5 percent from 0.2 percent in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2023-06-09 21:05:13 </td>
   <td style="text-align:left;"> Canadian Dollar Eases from 2-Month High </td>
   <td style="text-align:left;"> The Canadian dollar depreciated slightly since touching the two-month high of 1.335 per USD on June 8th, as higher unemployment in the Canadian economy challenged the Bank of Canada’s hawkish pledges. The domestic jobless rate rose by 0.2 percentage points to 5.2% in May, the first increase since August of 2022, suggesting that the labor market is finally feeling the impact of the BoC’s aggressive tightening cycle. The data came shortly after the central bank unexpectedly hiked its key rate by 25bps, going against the BoC’s signal that rates could have peaked and suggesting that borrowing costs were not as restrictive as policymakers expected. The latest price data showed that the Canadian CPI rose by 4.4% in April, well above market forecasts of 4.1% and picking up from 4.3% in March. In the meantime, crude oil prices bounced from recent lows and supported buying activity for the loonie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-09 21:03:00 </td>
   <td style="text-align:left;"> Canadian 10-Year Bond Yield Edges Lower after Disappointing Jobs Data </td>
   <td style="text-align:left;"> The yield on the Canadian 10-year government bond eased to below 3.4% after the labour force report showed a bigger-than-expected slowdown in the job market, with the economy losing jobs for the first time in nine months and the unemployment rate rising above forecasts to 5.2%. Earlier, the yield topped 3.46%, the highest in near three months, after the Bank of Canada unexpectedly raised interest rates by another 25bps in June, and signalled it could increase them further if necessary. Markets are still expecting another increase in July as the inflation remains more than twice the central bank's target of 2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/bernanke-banks-inflation-ai.html </td>
   <td style="text-align:left;"> 2023-06-09 21:00:10 </td>
   <td style="text-align:left;"> Former Fed Chair Ben Bernanke on Inflation, Bank Runs and More - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Strategies                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The former Fed chairman shared his thoughts with our columnist.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By Jeff Sommer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Jeff Sommer is the author of Strategies, a weekly column on markets, finance and the economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , I called Ben S. Bernanke, the former chairman of the Federal Reserve, late in the debt-ceiling standoff. It hadn’t been concluded quite yet but soon would be. This time, at least, the financial system averted another full-fledged crisis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , But when truly dire events happen and Congress and the White House are focused on political battles, the Fed often ends up as the “only game in town,” Mr. Bernanke said, “the only policymaker that can help an economy in trouble.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Fixing the world’s urgent problems is no longer Mr. Bernanke’s responsibility. In 2014, he stepped down as Fed chair, after leading it through the global financial crisis. Now, at 69, he is a scholar at the Brookings Institution in Washington, devoting himself mainly to research and writing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , His research, showing “that bank crises can potentially have catastrophic consequences” and illustrating “the importance of well-functioning bank regulation,” earned him a Nobel Prize in economics in 2022. That academic work, and the changes he made at the Fed, have altered the way we understand financial news, even if he is making fewer headlines himself.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Yet, Mr. Bernanke said he still “monitors the Fed very carefully,” and in a wide-ranging interview, he discussed many thorny issues, including bank runs, inflation and threats to financial stability.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , At the moment, the banking system appears to be stable, he said, but you never know. In the summer of 2007, for instance, when the global financial crisis started, Mr. Bernanke said he didn’t immediately recognize how “devastating” it was going to be. Now, he said, he regrets that it took “some months” to “appreciate the magnitude of the crisis.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Conditions in the financial system appear to be fairly calm today, he said, but added, “I’ve learned from painful experience that one never says never; it’s always possible.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , In agreeing to an open-ended conversation, he insisted on one ground rule: He would not “second-guess the Fed.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , “I will tell you what I think the Federal Reserve is doing and why it’s doing it,” he said, “but I will not tell you what I think they should do at the next meeting,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Once Mr. Bernanke got rolling, his comments included these highlights:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Further bank runs could be headed off by raising the ceiling for deposit insurance. That insurance “should cover more than $250,000 per account,” perhaps by requiring larger bank depositors “to pay some kind of premium” for the benefit. His research, and that of his two fellow 2022 Nobel laureates, Douglas W. Diamond and Philip H. Dybvig, showed that fear of losing money at a weakened bank could set off or worsen bank runs, like those earlier this year, and lead to deep economic stress.                                                                                                                                                                                                                                                                                                                                                                                        , If the Fed had the legal authority that other central banks possess, it wouldn’t need to invoke emergency powers and set up temporary rescue “facilities” every time a crisis demands that it backstop “shadow banks,” which include hedge funds, investment banks, private equity funds, money market funds and the like. These giant institutions perform many of the functions of traditional banks. The Fed is hampered by “a structural flaw that was never corrected by Congress, which is that the Fed is restricted on normal grounds to lending only to banks and not to other types of financial institutions,” he said.                                                                                                                                                                                                                                                                 , Don’t ever assume everything in the financial system is OK. It may not be. There is a need for constant monitoring and bolstering of systemic regulatory oversight to head off major problems. Mr. Bernanke’s research showed that “the financial crisis of the 1930s was a major factor in the Great Depression,” an insight that, he recalls, people “laughed at” when he first wrote about it. “I think it’s become quite conventional wisdom at this point that a big financial crisis is really bad for the economy.”                                                                                                                                                                                                                                                                                                                                                                         , The Fed may need time to get inflation down to the 2 percent target he helped institute, but unlike some writers — including this columnist — he said that target must stand. Two percent isn’t an “ideal” number, he said, and during his early academic career, he advocated a higher target, of 3 or 4 percent, for Japan. But now, U.S. politics and practical reality mean the 2 percent target should be preserved, he said. “I would think that if the Fed announced tomorrow that it was raising the inflation target, that would destroy its credibility,” he said. And any attempt to raise the target might set off Congressional action that could have the opposite effect.                                                                                                                                                                                                           , Are we in an A.I. bubble? Mr. Bernanke said it was hard to identify bubbles as they were forming, and to know what to do when one existed. “A.I. stocks are zooming up despite the fact that the overall economic environment is worrisome,” he said. “Is that a bubble? It depends on whether A.I. turns out to be the transformative technology that some people think it will be. Maybe it is, maybe it isn’t.” The problem is that when some bubbles collapse, they can wreak havoc, as the housing bubble did in 2008. Such a collapse can “bring down critical financial institutions and that creates tremendous financial distress.” He added, “If you have a strong and well-regulated financial system, then even if you have a bubble that comes down, the system should be able to weather it without massive effects on the economy.”                                                 , Regular news conferences by the Fed chair, which Mr. Bernanke initiated, and which his successors, Janet L. Yellen and Jerome H. Powell, expanded, are essential, he said. They are needed not just to convey the Fed’s messaging to market specialists, but also to explain what’s going on to the general public. At the onset of the 2007-8 crisis, he said, the Fed took a lot of heat for rescuing big Wall Street firms while, supposedly, neglecting the little guy. “It probably was impossible, but at least I should have tried to explain why it was important to preserve the stability of the financial system,” he said. “And why it would benefit everyone and not just the Wall Street C.E.O.s. There’s this feeling that the Fed is captured by Wall Street, which is just not true. But if you’re asking for regrets, I think that’s one thing I should have done more actively.”, The Fed, he said, had to innovate in those years because the economy was in a severe downturn and needed more help, yet the Fed had already reduced short-term interest rates to close to zero.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By 2011, he said, “we were facing a very, very bad situation with no more ammunition, in terms of the Fed funds rate.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , More fiscal stimulus — more spending — might have done the trick, he said. But, he recalled, “Congress was already trying to go to an austerity program, trying to cut back on fiscal policy.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , “And so essentially, the Federal Reserve was left as the only policymaker in Washington that could do anything about this desperately deep recession and all the job losses and all the cost that was imposing on workers and their families,” he said. “So we needed a new set of tools.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , By that point in his academic work, Mr. Bernanke had formulated the principles for quantitative easing (purchasing bonds and other securities to reduce longer-term interest rates) and forward guidance (using messaging to shift expectations). These become permanent parts of the Fed tool kit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Large-scale fiscal stimulus certainly occurred in the recent pandemic downturn, but with inflationary consequences, so the Fed has been not only raising interest rates, but also using its new tools, too. In a reversal of quantitative easing, it has been paring down the assets it has purchased through the years, and sent out plenty of belt-tightening messages. At a policymaking meeting next week, the Fed will assess whether all these measures are slowing the economy.                                                                                                                                                                                                                                                                                                                                                                                                             , The Fed’s job would be easier if fiscal policy were “more cooperative,” he said, but it’s most likely the central bank will frequently find itself “the only game in town.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mr. Bernanke has been churning out a stream of books and articles on both abstruse and topical subjects, including a paper in the American Economic Review based on his December Nobel lecture summarizing his life work. The paperback edition of his book, “21st Century Monetary Policy” was released in May, with a fresh analysis of recent events.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Like many of us, Mr. Bernanke is putting away money for retirement. A cottage industry of Fed watchers base their investment strategies on what they believe the Fed is doing. Mr. Bernanke may be the most sophisticated of Fed watchers, but he said he was “a very boring investor.” “I basically have a well-diversified portfolio,” he said. “I do not try to pick individual stocks. I don’t base my investments on what I think the Fed is going to do.”                                                                                                                                                                                                                                                                                                                                                                                                                                    , In fact, Mr. Bernanke told me that he essentially practiced the straightforward approach that “you advocate in your column.” He added, “I’m certainly not going to advise people to buy meme stocks, or to do anything unusual.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , He summarized his approach this way: “The other day you said something like, you know, have your portfolio consistent with your risk aversion and with your liquidity needs.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , I’d say, make sure you can pay the bills first. Don’t put any money into the stock market that you can’t stand to lose. And invest for the long haul.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Based on Mr. Bernanke’s own example, I’d add: Think, study, innovate and do all you possibly can to keep the world afloat. But for your own personal investing, keep it simple.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Jeff Sommer writes Strategies, a column on markets, finance and the economy. He also edits business news. Previously, he was a national editor. At Newsday, he was the foreign editor and a correspondent in Asia and Eastern Europe.  @jeffsommer • Facebook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/sweden-s-alecta-scales-back-international-holdings-after-review </td>
   <td style="text-align:left;"> 2023-06-09 20:57:20 </td>
   <td style="text-align:left;"> Sweden’s Alecta Scales Back International Holdings After Review </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Love Liman                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The Swedish pension fund caught up in the fallout from Silicon Valley Bank in March has decided to scale back its stock holdings in companies located outside the Nordic region.                                                                                                                                                                                                                                                                                                                                                                     , The decision by Alecta follows a review into the group’s failed bets on three niche US lenders, SVB Financial Group, First Republic Bank and Signature Bank. The holdings triggered loses of nearly $2 billion, equivalent to roughly 2% of the fund’s total assets, and saw the then chief executive and equities boss ousted amid a public outcry in Sweden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/rising-profit-estimates-mask-south-africa-s-frail-equity-outlook </td>
   <td style="text-align:left;"> 2023-06-09 20:38:44 </td>
   <td style="text-align:left;"> Rising Profit Estimates Mask South Africa’s Frail Equity Outlook </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Srinivasan Sivabalan and                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Khuleko Siwele                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Analysts have raised the earnings outlook for South Africa’s main equity index to an almost 11-year high. Money managers say that’s a red herring.                                                                                                                                                                                                                                                                                                                                                                                                   , The average forecast for 12-month profits in the FTSE JSE Africa All Share Index rose as much as 4% in dollar terms this year through May 31 to the highest level since 2012. It also hit a record high in local-currency terms. The upgrades came even as the estimate for emerging-market stocks as a whole fell 1.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/capacity-utilization </td>
   <td style="text-align:left;"> 2023-06-09 20:38:00 </td>
   <td style="text-align:left;"> Canada Capacity Utilization Rate Below Forecasts </td>
   <td style="text-align:left;"> Canadian industries operated at 81.9% of their production capacity in the first quarter of 2023, slightly higher than the upwardly revised 81.8% in the prior period, but below market forecasts of 82.2%, largely attributed to an uptick in the manufacturing capacity utilization rate (78.1% vs 77.1% in Q4). Capacity utilization increased in 13 of the 21 major manufacturing industry groups, representing approximately 75% of the gross domestic product in the manufacturing sector, notably the manufacture of transportation equipment (80.7% vs 77%), petroleum and coal products (86.8% vs 83.8%) and fabricated metal products (78.3% vs 76.3%).  Meanwhile, capacity utilization fell in the mining, quarrying, and oil and gas extraction sector (79.5% from 80.4%) and construction (90.2% vs 90.5%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-09 20:36:00 </td>
   <td style="text-align:left;"> Canadian Unemployment Rises More than Expected </td>
   <td style="text-align:left;"> The unemployment rate in Canada rose to 5.2% in May of 2023 after remaining at 5% for the five previous months, above market estimates of 5.1% to mark the first monthly increase in the unemployment rate since August 2022. The data suggested that the Canadian labor market is starting to give in to higher interest rate from the BoC after remaining stubbornly tight for a long period, as unemployment rose by 34,800 individuals to 1,058,200. Joblessness was notably higher among people aged 55 and older (+0.2pp to 4.1%), while unemployment for the core-aged working force was broadly unchanged (at 4.3%). Consequently, 17,300 jobs were removed from the Canadian economy, sharply missing market expectations of a 23,200 gain. In the meantime, the labor force participation rate fell by 0.1 percentage point to 65.5% in the period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/employment-change </td>
   <td style="text-align:left;"> 2023-06-09 20:34:00 </td>
   <td style="text-align:left;"> Canadian Economy Sheds Jobs for 1st Time in 9 Months </td>
   <td style="text-align:left;"> The Canadian economy shed 17.3K jobs in May of 2023, the first decline in nine months, and compared to forecasts of a 23.2K rise. The number of employees held steady in the private and public sector, while there was a decline in the number of self-employed workers (-40K). Employment fell by 77K for youth aged 15 to 24, offsetting a 63K increase among people aged 25 to 54. There were fewer people employed in business, building and other support services (-31K), as well in professional, scientific and technical services (-13K) while increases were seen in manufacturing (13K) and utilities (4.2K). Employment growth has moderated in recent months and monthly increases averaged 33K from February to April, after strong gains totalling 326K from September 2022 to January 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-09 20:26:50 </td>
   <td style="text-align:left;"> Russian Bond Yields Extend Rise After CBR </td>
   <td style="text-align:left;"> The yield on the Russian 10-year OFZ jumped to 10.85% in June, adding 60bps since the start of the second quarter amid a hawkish central bank and persistent concerns over the government’s fiscal stability. The Central Bank of Russia paved the way for rate hikes in upcoming meetings as inflationary risks are higher and consumer demand is rising, trimming demand for government bonds. In the meantime, new data from the Ministry of Finance showed that the Federal government posted a budget deficit of RUB 3.4 trillion in the first five months of the year, a record-high for the period, as war spending continued to soar and low energy prices dented the state’s essential revenue streams. The developments force the government to depend on bond issuance to finance its budget deficit, lifting yields. Additionally, the Kremlin continued to deplete its foreign currency holdings and its National Welfare Fund. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/citi-to-cut-50-london-jobs-in-investment-and-corporate-banking </td>
   <td style="text-align:left;"> 2023-06-09 20:20:28 </td>
   <td style="text-align:left;"> Citi to Cut 50 London Jobs in Investment and Corporate Banking </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Citigroup’s offices in Canary Wharf, London.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , William Shaw                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Citigroup Inc. is planning to cut 30 investment banking jobs and 20 more in its corporate banking unit in London in its latest wave of redundancies.                                                                                                                                                                                                                                                                                                                                                                                                 , The cuts are necessary for the bank to reduce its cost base because of adverse market conditions, according to a person within the bank, who isn’t authorized to speak publicly. Financial News reported the layoffs earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 20:13:00 </td>
   <td style="text-align:left;"> Mexico Industrial Output Growth Continues to Slow </td>
   <td style="text-align:left;"> Mexico’s industrial production went up by 0.7% from a year earlier in April 2023, following a downwardly revised 1.5% increase in the prior month and below market forecasts of a 1.3% rise. It marks the 18th consecutive month of growth in industrial activity, albeit the weakest since October 2021. Output increased for mining &amp; quarrying (1.9% vs 2.2%); manufacturing (1.4% vs 1.1%) and utilities (0.6% vs 3.8%), but it contracted for construction (-2% vs 1.7%). On a seasonally adjusted monthly basis, industrial output rose by 0.4% in April, after a 0.9% fall in March, in line with market estimates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 20:00:47 </td>
   <td style="text-align:left;"> MOEX Holds Gains Despite Hawkish CBR </td>
   <td style="text-align:left;"> The ruble-based MOEX Russia index held slight gains and hovered close to the 2,715 mark, extending the advance from the previous session with support from banks and oil companies, while investors digested the Central Bank of Russia’s interest rate decision. The CBR held borrowing costs unchanged for the sixth consecutive decision but paved the way for rate hikes in the incoming meetings as inflationary risks are higher than before. Banking giant Sberbank hovered flat after its May results were broadly in line with market expectations, while shares in the rest of the sector booked sharp gains on the back of solid results from VTB posted earlier in the week. In the meantime, gains for oil companies were led by a 5% surge for preferred Surgut shares following the announcement of strong 2022 results. Also, Transneft added 1.6% as its board will announce dividends on Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/inflation-s-big-stock-winner-insurance-broker-arthur-j-gallagher-outperforms </td>
   <td style="text-align:left;"> 2023-06-09 20:00:00 </td>
   <td style="text-align:left;"> The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Arthur J. Gallagher &amp; Co. CEO J. Patrick Gallagher Jr.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Source: PRNewswire                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Breanna Bradham                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , It’s enemy No. 1 inside the halls of the Federal Reserve, dreaded in cash-strapped households across America and a headache for CFOs at countless companies, big and small.                                                                                                                                                                                                                                                                                                                                                                          , But bring up inflation with executives at Arthur J. Gallagher &amp; Co., an insurance broker outside Chicago, and you’ll get a very different reaction. “We win,” says J. Patrick Gallagher Jr., the firm’s CEO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/09/stocks-making-the-biggest-moves-premarket-target-tesla-general-motors-docusign-and-more.html </td>
   <td style="text-align:left;"> 2023-06-09 19:47:51 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Target, Tesla, General Motors, DocuSign and more </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                   , Loans                                                                                                                                                                                                                                                                                                                                          , Banking                                                                                                                                                                                                                                                                                                                                        , Mortgages                                                                                                                                                                                                                                                                                                                                      , Insurance                                                                                                                                                                                                                                                                                                                                      , Credit Monitoring                                                                                                                                                                                                                                                                                                                              , Personal Finance                                                                                                                                                                                                                                                                                                                               , Small Business                                                                                                                                                                                                                                                                                                                                 , Taxes                                                                                                                                                                                                                                                                                                                                          , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                     , Investing                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                         , All Credit Cards                                                                                                                                                                                                                                                                                                                               , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                   , Best Credit Cards                                                                                                                                                                                                                                                                                                                              , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                      , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                       , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                       , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                             , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                    , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                               , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                                                                                                                         , All Loans                                                                                                                                                                                                                                                                                                                                      , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                            , Best Personal Loans                                                                                                                                                                                                                                                                                                                            , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                  , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                       , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                   , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                      , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                      , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                            , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                         , All Banking                                                                                                                                                                                                                                                                                                                                    , Find the Savings Account for You                                                                                                                                                                                                                                                                                                               , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                               , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                 , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                  , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                             , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                  , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                     , Best CDs                                                                                                                                                                                                                                                                                                                                       , Best Credit Unions                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                         , All Mortgages                                                                                                                                                                                                                                                                                                                                  , Best Mortgages                                                                                                                                                                                                                                                                                                                                 , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                          , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                             , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                         , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                        , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                      , Affording a Mortgage                                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                         , All Insurance                                                                                                                                                                                                                                                                                                                                  , Best Life Insurance                                                                                                                                                                                                                                                                                                                            , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                      , Best Renters Insurance                                                                                                                                                                                                                                                                                                                         , Best Car Insurance                                                                                                                                                                                                                                                                                                                             , Travel Insurance                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                         , All Credit Monitoring                                                                                                                                                                                                                                                                                                                          , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                 , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                 , Credit Repair Services                                                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                                                                         , All Personal Finance                                                                                                                                                                                                                                                                                                                           , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                            , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                      , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                       , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                     , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                  , Best Debt Relief                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                         , All Small Business                                                                                                                                                                                                                                                                                                                             , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                           , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                          , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                           , Best Small Business Loans                                                                                                                                                                                                                                                                                                                      , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                         , All Taxes                                                                                                                                                                                                                                                                                                                                      , Best Tax Software                                                                                                                                                                                                                                                                                                                              , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                         , Tax Refunds                                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                         , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                 , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                               , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                             , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                   , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                        , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                          , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                   , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                   , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                  , Best Hardship Loans                                                                                                                                                                                                                                                                                                                            , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                         , All Investing                                                                                                                                                                                                                                                                                                                                  , Best IRA Accounts                                                                                                                                                                                                                                                                                                                              , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                         , Best Investing Apps                                                                                                                                                                                                                                                                                                                            , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                              , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                             , Index Funds                                                                                                                                                                                                                                                                                                                                    , Mutual Funds                                                                                                                                                                                                                                                                                                                                   , ETFs                                                                                                                                                                                                                                                                                                                                           , Bonds                                                                                                                                                                                                                                                                                                                                          ,                                                                                                                                                                                                                                                                                                                                                , Check out the companies making headlines in premarket trading.                                                                                                                                                                                                                                                                                 , Tesla, General Motors -- Both carmaker stocks were climbing in premarket trading, with gains of 5.7% and 5%, respectively. General Motors announced on Thursday plans to utilize Tesla's electric vehicle charging network, and said its vehicles will also utilize Tesla's North American Charging Standard port in its cars starting in 2025., Corning — Shares of the glass materials maker added 3.2% after an upgrade from Morgan Stanley, which labeled the company's business as "derisked."                                                                                                                                                                                             , DocuSign – The e-signature provider's stock rose about 5% premarket after the company reported earnings and revenue that beat analysts estimates for the fiscal quarter ended April 30, issued upbeat guidance and announced a handful of new service offerings and C-suite hires.                                                             , Adobe — Shares of the software company gained more than 3% after Wells Fargo upgraded the stock Friday morning to overweight, according to StreetAccount.                                                                                                                                                                                      , Target — The retail giant slipped 1.3% after Citi downgraded the stock over concerns that sales may have peaked.                                                                                                                                                                                                                               , Nio — Shares of the electric vehicle company dipped 2% in premarket trading after it reported that vehicle sales decreased 0.2% year over year. The company's vehicle margin and net loss also worsened year over year.                                                                                                                        , Sonoma Pharmaceuticals — The company's stock soared nearly 33% after announcing Thursday evening a new application for its intraoperative pulse lavage irrigation treatment that could replace IV bags in some surgical procedures. Sonoma said the treatment will be available in Europe this year and in the U.S. commercially in 2024.      , — CNBC's Tanaya Macheel and Jesse Pound contributed reporting.                                                                                                                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                               , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 19:45:41 </td>
   <td style="text-align:left;"> US Futures Point to Mixed Open </td>
   <td style="text-align:left;"> US futures were mixed on Friday, with contracts on the Dow Jones falling nearly 70 points, while the S&amp;P 500 was little changed after entering bull market territory the day before, and Nasdaq 100 futures added 0.1%. Investors refrain from making big bets ahead of key US CPI report and the FOMC decision next week. On the corporate front, Tesla shares rallied 6% and General Motors was up over 4% in premarket trading after the latter announced it will use Tesla technology to charge its electric vehicles. On the other hand, stocks of Target lost over 1% after Citigroup analysts cut their rating. So far on the week, the Dow is up 0.2%, the S&amp;P 500 gained nearly 0.3% to book a fourth straight week of gains while the Nasdaq is little changed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2023-06-09 19:42:50 </td>
   <td style="text-align:left;"> Russian Ruble Sinks to 1-Year Low </td>
   <td style="text-align:left;"> The Russian ruble weakened toward 82.5 per USD in June, the lowest in over one year, and trading below levels before Russia’s invasion of Ukraine amid continued pressure from Russia’s unsustainable fiscal deficit and persistently low energy prices. New data from the Ministry of Finance showed that the Federal government posted a budget deficit of RUB 3.4 trillion in the first five months of the year, the highest on record, as war spending surged and energy revenues plummeted. Consequently, the Ministry announced that it sold four tonnes of gold and CNY 2.6 billion from its National Welfare Fund to finance its budget deficit. The low inflows also forced the Kremlin to continue selling foreign currency. On the other hand, increased inflationary risks in the Russian economy drove the Central Bank to flag interest rate hikes in the upcoming meetings, reigning in losses for the ruble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-09 19:36:29 </td>
   <td style="text-align:left;"> Macedonia Jobless Rate Hits New Record Low </td>
   <td style="text-align:left;"> The unemployment Rate in North Macedonia fell further to 13.4 percent in the first quarter of 2023, down from 14 percent in the previous period. This was the lowest jobless rate since comparable records began in 1993, as the number of unemployed declined by 8 thousand to 104.4 thousand and the number of employed was also down by 13 thousand to 683 thousand. Meanwhile, the employment rate edged down to 45.1 percent from 47.2 percent, while the activity rate fell to 52 percent from 54.9 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/teachers-strike-in-romania-as-union-sees-little-scope-for-deal </td>
   <td style="text-align:left;"> 2023-06-09 19:28:13 </td>
   <td style="text-align:left;"> Teachers Strike in Romania as Union Sees Little Scope for Deal </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Romanian teachers protest in front of the Romanian Government headquarters in Bucharest, on May 25                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Photographer: Daniel Michaelscu/AFP/Getty Images                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Andra Timu and                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Irina Vilcu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Thousands of teachers took to the streets of Romania’s capital as the biggest education strike in almost two decades approached its third week and the government struggled to reach a deal with union negotiators.                                                                                                                                                                                                                                                                                                                                  , Some 10,000 people joined the demonstration in central Bucharest Friday to demand a pay hike and better working conditions, according to local media. It was the third such gathering since the teachers’ strike began May 22.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2023-06-09 19:21:00 </td>
   <td style="text-align:left;"> Cocoa Hits 4-Week High </td>
   <td style="text-align:left;"> Cocoa futures jumped above $3,170 a tonne, its highest in four weeks, amid growing concerns about tight global supplies. In Ivory Coast, the world’s leading cocoa-producing country, both the volume of cocoa beans and harvest forecasts continue to fall. For the 2022-2023 harvest campaign, the government is predicting a harvest of 450,000 tonnes, or even 500,000 tonnes, which is smaller than the 600,000 tonnes harvested during the 2021-2022 interim campaign. Recent rains have also raised concern over the quality of the mid-crop. Latest data showed that farmers sent a cumulative 2.09 million tonnes of cocoa to Ivory Coast ports for the 2022/23 marketing year, which runs from October 1 through May 28, down 3% from the same period last season. Adding to the bullish tone, fears mount that an El Nino weather event could undercut global cocoa production. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 19:14:28 </td>
   <td style="text-align:left;"> BIST 100 Above 5500 Level </td>
   <td style="text-align:left;"> The Turkish benchmark BIST 100 index has surged nearly 16% since the runoff election, surpassing the 5,500 level and hitting the highest level since January, after the appointment of Hafize Gaye Erkan, formerly a co-CEO at First Republic Bank and a managing director at Goldman Sachs, as the head of Turkey's central bank. Following the assignment of highly respected former banker Mehmet Simsek as Minister of Treasury and Finance, this move indicated a notable signal of President Erdogan's shift from unorthodox economic policies that had resulted to high inflation, low interest rates, a plummeting lira, and negative net foreign exchange reserves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/italians-boost-state-coffers-in-dash-to-snap-up-new-retail-bonds </td>
   <td style="text-align:left;"> 2023-06-09 19:04:08 </td>
   <td style="text-align:left;"> Italians Boost State Coffers in Dash to Buy New Retail Bonds </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Palazzo Montecitorio, Italy's parliament building..                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Alice Gledhill                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Ordinary Italians answered the call to fund their government as they clamored to buy a new class of bonds designed especially for them.                                                                                                                                                                                                                                                                                                                                                                                                              , The nation closed its first placement of the four-year securities called BTP Valore, which raised more than €18 billion, a record amount for a debt offering pitched to retail investors, according to the Ministry of Economy and Finance. That’s nearly twice the size of an inflation-linked bond targeted at individual savers in March.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2023-06-09 19:04:00 </td>
   <td style="text-align:left;"> European Natural Gas Prices Up 20% on the Week </td>
   <td style="text-align:left;"> Natural gas futures in Europe surged more than 20% to nearly €29 per megawatt-hour in the second week of June, as concerns about lower supplies outweighed ample gas storage levels and weaker demand. Gas shipments from the US are becoming scarcer as the supply is funneled to Asia, where prices are more competitive in the summer months due to stronger demand for cooling. Meanwhile, France's Montoir LNG terminal will be closed for maintenance until June 10, and Norway's Equinor has postponed the restart of its Hammerfest LNG plant to June 14 due to technical difficulties. Additionally, the Turkstream gas pipeline, which transports gas from Russia through the Black Sea to Turkey, is suspended until June 12 for maintenance work. Currently, Europe's gas storage is 70.4% full, and the European Union aims to achieve a storage inventory target of 90% by November 1. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macedonia/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 19:02:40 </td>
   <td style="text-align:left;"> Macedonia Producer Inflation Lowest Since 2020 </td>
   <td style="text-align:left;"> Macedonia's producer prices rose 1.6% year-on-year in April 2023, easing from a 5% hike in the previous month. This was the lowest producer inflation rate since November 2020, as cost declined significantly for mining &amp; quarrying (-9.8% vs -2.4% in March) and prices also slowed for manufacturing (1.6% vs 5%). On the other hand, prices advanced faster for electricity, gas, steam &amp; air conditioning supply (17.1% vs 5%). On a monthly basis, producer prices went up 0.4% in April, following a 0.1% fall in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/consumer-confidence </td>
   <td style="text-align:left;"> 2023-06-09 19:02:22 </td>
   <td style="text-align:left;"> Spain Consumer Morale Jumps to Over 1-Year High </td>
   <td style="text-align:left;"> The consumer confidence indicator in Spain jumped to 81.5 in May of 2023 from 73 in the previous month, the highest since the start of the Russian invasion of Ukraine in February of 2022 to challenge a series of gloomy economic data in the Eurozone. The subindex measuring current conditions for the Spanish consumer rose by 8.7 points from the previous month to 71.5, while that measuring future expectations jumped by 8.4 points to 91.5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2023-06-09 19:00:40 </td>
   <td style="text-align:left;"> US Natural Gas Futures Fall, Set for Weekly Gain </td>
   <td style="text-align:left;"> US natural gas futures fell below $2.3/MMBtu after mild weather last week kept demand for the fuel low and allowed utilities to inject more gas into storage. The latest EIA report showed US utilities added 118 billion cubic feet of gas into storage, slightly more than market expectations of a 113 bcf increase. Despite this setback, natural gas prices in the US are on course for an over 5% weekly gain, recovering from two consecutive periods of losses, in anticipation of increased demand from air conditioning usage amid forecasts for warmer weather. The number of cooling degree days (CDDs) in the coming two weeks is expected to rise to 167, above the 30-year normal of 149, according to Refinitiv. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/latvia/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 18:53:00 </td>
   <td style="text-align:left;"> Latvia Trade Deficit Little Changed in April </td>
   <td style="text-align:left;"> Latvia's trade deficit remained almost unchanged at EUR 450.5 million in April 2023, following EUR 455.3 million in the same month of the previous year, as exports dropped faster than imports. Exports plunged by 9.5% yoy to EUR 1.52 billion due to falling sales of wood &amp; wood products (-33.4%), mineral fuels, mineral oils &amp; products of their distillation (-45.3%), and iron &amp; steel (-19.9%). Most shipments went to Lithuania (17.9 % of total exports), Estonia (11.3 %), Germany (6.7 %), and Sweden (5.8 %). Meanwhile, imports decreased at a softer 7.2% to EUR 1.97 billion on lower purchases of mineral fuels, mineral oils &amp; products of their distillation (-52.9%), and products of the chemical and allied industries (-12.3%). The main import partners were Lithuania (18.2 % of total imports), Germany (10.5 %), Poland (10.2 %), and Canada (9.1%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/interest-rate </td>
   <td style="text-align:left;"> 2023-06-09 18:49:00 </td>
   <td style="text-align:left;"> Russia Holds Rate, Flags Possibility of Future Hikes </td>
   <td style="text-align:left;"> The Central Bank of Russia held its key interest rate unchanged at 7.5% for the sixth consecutive decision in its June 2023 meeting, in line with market expectations, but flagged a higher possibility of rate hikes in the upcoming meetings due to higher inflationary risks. The bank noted that inflation is due to rise as base effects from the war will start to fade, while consumer demand recovers from last year’s crash and the effects of a weaker ruble pass through. Inflationary expectations are also higher as war spending and lower energy prices spark a record-high budget deficit for the Federal government, pressuring the ruble and lifting bond yields. Additionally, production costs are higher as the military mobilization caused a crash in the labor force and pressured firms’ capacity. Policymakers also noted that economic activity has picked up at a greater pace than expected. The CBR expects inflation to hover between the 4.5-6.5% range this year before steadying at 4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/malaysia-names-abdul-rasheed-ghaffour-as-central-bank-governor </td>
   <td style="text-align:left;"> 2023-06-09 18:36:21 </td>
   <td style="text-align:left;"> Malaysia Names Abdul Rasheed Ghaffour as Central Bank Governor </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Shaik Abdul Rasheed Abdul Ghaffour                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Anisah Shukry                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Malaysia named Shaik Abdul Rasheed Abdul Ghaffour as its new central bank governor, tasked with fostering stability and confidence in an economy under pressure from slowing global demand, volatile inflation and a weakened ringgit.                                                                                                                                                                                                                                                                                                               , Malaysia’s king approved Abdul Rasheed as the governor from July 1 for a period of five years, Bank Negara Malaysia said Friday. He will replace Nor Shamsiah Mohd Yunus, whose term ends June 30, according to the statement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/zimbabwe-share-prices-daily-limit-raised-after-760-jump </td>
   <td style="text-align:left;"> 2023-06-09 18:27:11 </td>
   <td style="text-align:left;"> Zimbabwe Lifts Daily Share-Move Limit to Cope With Price Surges </td>
   <td style="text-align:left;"> Jonathan Ferro drives you through the market moving events from around the world on Bloomberg's The Open. 60 minutes featuring the brightest minds on Wall Street, taking you through the most important hour of the trading day.                                                                                                                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                                                                                                                                                                            , If the only thing you know about sports is who wins and who loses, you are missing the highest stakes action of all. The business owners that power this multibillion dollar industry are changing, and a new era of the business of sports is underway. From media and technology to finance and real estate, leagues and teams across the globe have matured into far more than just back page entertainment. And the decisions they make have huge consequences, not just for the bottom line, but for communities, cities, even entire countries., Sweden’s Alecta Scales Back International Holdings After Review                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rising Profit Estimates Mask South Africa’s Frail Equity Outlook                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ukraine Economy Contracts Less Than Expected Despite Attacks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Canada Suffers Minor Job Losses, Snapping Eight-Month Streak                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , University of Manchester Says It’s Investigating a Hack                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Billionaire Who Rode Zoom’s 1,479% Stock Boom Builds Health Bets                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Orlando Bravo Predicts VC Shakeup, Says It’s PE’s Time to Shine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Pandemic Aid Saved Millions of Americans From Eviction and the Data Proves It                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , US Expands China Forced-Labor Embargo With Ban on Two New Firms                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Here’s the Guaranteed, Can’t-Lose Belmont Stakes Pick                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With Trump's Federal Prosecution, Timing Is Everything                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , EU Looks to Boost Efforts to Store Captured Carbon Underground                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How Arctic Ice Melt Raises the Risk of Far-Away Wildfires                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , A New Crypto Banking System Arises Under the Shadow of a Regulatory Crackdown                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Ray Ndlovu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Subscribe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Share prices are rising so rapidly on Zimbabwe’s main stock exchange that the bourse is increasing the maximum move allowed in a single day.                                                                                                                                                                                                                                                                                                                                                                                                         , A new daily limit of a 15% move in the all-share index — up from 10% — will be implemented from Monday, Justin Bgoni, chief executive officer of the Zimbabwe Stock Exchange in Harare, said by phone Friday. Circuit breakers halted trading on the bourse on three consecutive days this week. “It’s in response to the recent activity,” he said.   </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 18:27:04 </td>
   <td style="text-align:left;"> Indian Shares Pare Weekly Gains on Friday </td>
   <td style="text-align:left;"> The BSE Sensex closed 235 points lower at 62,615 on Friday, trimming gains from earlier sessions to notch a broadly flat end to the week as tightening measures for key monetary authorities pressured equity markets. Despite holding rates yesterday, the RBI emphasized that borrowing costs must remain restrictive enough to prevent upside risks to inflation, paring hopes that the central bank could cut rates by the third quarter. Tech shares led the losses for the final session of the week, with Infosys and Mahindra &amp; Mahindra both dropping 1.2% while TCS shares decreased 0.6%. Public sector banks also declined, led by a 1.3% retreat for the State Bank of India. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cyprus/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 18:21:57 </td>
   <td style="text-align:left;"> Cyprus Trade Gap Widens Slightly in April </td>
   <td style="text-align:left;"> The trade deficit in Cyprus widened slightly year-on-year to EUR 570.1 million in April 2023 from EUR 560 million in the corresponding month of the previous year, a preliminary estimate showed. Imports rose by 4 percent to EUR 872.1 million, as purchases were up by 11 percent from the non-EU countries, while inched up by 0.01 percent from EU countries. Meanwhile, exports surged by 8.3 percent to EUR 302.1 million, as sales jumped to non-EU countries 16 percent whereas the ones to EU countries shrank 10.1 percent. From January to April, the trade shortfall expanded to EUR 3.112 million from EUR 2.178 million in the same period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/iron-ore </td>
   <td style="text-align:left;"> 2023-06-09 18:15:09 </td>
   <td style="text-align:left;"> Iron Ore Rises to 7-Week High </td>
   <td style="text-align:left;"> Prices for iron ore cargoes with a 63.5% iron ore content for delivery in Tianjin jumped past $110 per tonne in June, its highest in seven weeks and extending its rebound from the six-month low of $98.5 touched on May 25th amid expectations of improved demand. Although recent data stretched evidence that China’s economic recovery continues to underwhelm expectations, trade figures from May showed that iron ore imports rose by 4.5% annually, raising hopes of higher purchasing activity from steel producers. Market players continued to bet that the government will soon announce stimulus measures to support the country’s essential property sector and construction activity, shortly after the PBoC chose to inject CNY 2 billion of liquidity into banks. On the other hand, supply remained ample amid strong output for key producers Australia and Brazil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 18:10:00 </td>
   <td style="text-align:left;"> Greek Industrial Output Growth Picks Up in April </td>
   <td style="text-align:left;"> Industrial production in Greece surged by 4.2% year-on-year in April 2023, following a revised 0.1% increase in the prior month. It marks the 4th consecutive month of growth in industrial activity and at a solid pace, mainly boosted by electricity supply (9.9% vs -28.5% in March) and mining &amp; quarrying (9.2% vs 22.7%), and, to a lesser extent, manufacturing (3.2% vs 8%). On the other hand, output decreased for water supply (-1.7% vs 2.5%). On a seasonally adjusted monthly basis, industrial activity shrank by 1.9% in April, after a revised flat reading in the previous month. Considering the first four months of the year, industrial production advanced by 2.4% over a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 17:44:52 </td>
   <td style="text-align:left;"> Greece Inflation Continues Downward Trend </td>
   <td style="text-align:left;"> Greece annual consumer inflation eased for an eighth straight month to 2.8% in May 2023 from 3% in April, marking the lowest reading since September 2021. The cost rose softer for hotels, cafés &amp; restaurants (7.4% vs 8.5% in the previous period) and household equipment (9.9% vs 10.9%). It also declined for housing (-12.9% vs -13.4%), transport (-3.1% vs 1.4%), and communication (-2.3% vs -1.8%). On the other hand, inflation accelerated for food &amp; non-alcoholic beverages (11.6% vs 11.4%); health (7.8% vs 6.5%); miscellaneous goods &amp; services (6.8% vs 6.4%); and clothing &amp; footwear (11.8% vs 5.6%). On a monthly basis, consumer prices grew by 0.4%, slowing from a 0.6% gain in April. Additionally, harmonized inflation rate decelerated to a 1-1/2 year low of 4.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malta/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 17:25:25 </td>
   <td style="text-align:left;"> Malta Posts Largest Trade Deficit in 8 Months </td>
   <td style="text-align:left;"> The trade deficit in Malta widened to EUR 480.1 million in April 2023 from EUR 360.4 million in the same month a year earlier. It was the largest trade gap since August 2022, as exports shrank 9.4% year-on-year to EUR 296.6 million, weighed down by lower sales of mineral fuels, lubricants &amp; related materials (-25.4%), semi-manufactured goods (-18.3%), miscellaneous manufactured articles (-9.9%) and machinery &amp; transport equipment (-0.3%). On the other hand, imports climbed 12.9% to EUR 776.6 million, mainly driven by purchases of semi-manufactured goods (33.7%). Considering the four months of the year, the country’s trade deficit increased to EUR 1,174 million from EUR 979.3 million in the corresponding period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malta/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 17:19:00 </td>
   <td style="text-align:left;"> Malta Industrial Output Up 14.3% in April </td>
   <td style="text-align:left;"> Industrial production in Malta rose 14.3 percent year-on-year in April 2023, following an upwardly revised 13.2 percent growth in the previous month. Output increased sharply for energy (31.9 percent vs 2.7 percent in March), while it slowed for capital goods (4.2 percent vs 7.9 percent) and consumer goods (20.3 percent vs 27.4 percent), In contrast, production dropped for intermediate goods (-0.3 percent vs 0.9 percent). On a seasonally adjusted monthly basis, industrial output fell 2.5 percent, after a 1.3 percent rise in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/total-vehicle-sales </td>
   <td style="text-align:left;"> 2023-06-09 17:15:24 </td>
   <td style="text-align:left;"> China Vehicle Sales Continue to Rise </td>
   <td style="text-align:left;"> Vehicle sales in China increased 27.9% year-on-year to 2.382 million units in May of 2023, following an 82.7% surge in the previous month, according to data from the China Association of Automobile Manufacturers (CAAM). Sales of new energy vehicles jumped 60.2%. Considering the first four months of the year, total car sales rose 11.1% to 10.62 million units and those of new energy vehicles jumped 46.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 17:11:15 </td>
   <td style="text-align:left;"> Russian Stocks Advance on Friday </td>
   <td style="text-align:left;"> The ruble-based MOEX Russia index hovered above the flatline at the 2,715 mark on Friday, extending gains from the previous session with support from banks and oil companies ahead of the Central Bank of Russia’s interest rate decision. While the central bank is expected to hold interest rates unchanged, previous hawkish rhetoric from Governor Nabiullina raised small bets of a potential hike or signals of future rate increases. Banking giant Sberbank hovered flat ahead of its release of May corporate results, while shares in the rest of the sector booked sharp gains on the back of strong results from VTB posted earlier in the week. In the meantime, gains for oil companies were led by a 4.5% surge for preferred Surgut stocks following the announcement of strong 2022 results. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 17:03:00 </td>
   <td style="text-align:left;"> Spain Stocks Struggle for Direction </td>
   <td style="text-align:left;"> The IBEX 35 stayed muted at 9,350 on Friday amid prevailing cautiousness ahead of next week's central banks meetings. The top performers in the index were Laboratorios Farma (1.1%) and Melia Hotels (1%). Additionally, traders kept an eye on Inditex (0.8%), which announced joining forces with Jeanologia to recover microfibers in the production of textile garments, and Iberdrola (0.2%) after the company sealed the largest green ammonia framework contract in Europe with Trammo. On the side of losses, Ferrovial dropped the most (-1%). Grifols also surprised with a fall of 0.5% despite signing an agreement with Canadian Plasma Resources to obtain their donated plasma. The index was on track to end week 0.5% higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/economy/wedding-engagement-rings-economy.html </td>
   <td style="text-align:left;"> 2023-06-09 17:00:25 </td>
   <td style="text-align:left;"> How Engagement Rings Explain What’s Happening in the Economy - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , A major jeweler claims the pandemic may have prevented people from meeting their future fiancés, cutting demand for engagement rings. Inflation and anxiety among shoppers haven’t helped.                                                                                                                                                                                                                                                                                                                             , By Jeanna Smialek and Jason Karaian                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Aftershocks from the coronavirus pandemic continue to rumble across the U.S. economy, and Signet Jewelers shared a surprising one this week: The company is selling fewer engagement rings this year because, it says, singles who were stuck at home during lockdowns failed to meet their would-be fiancés in 2020.                                                                                                                                                                                                  , “As we predicted, there were fewer engagements in the quarter resulting from Covid’s disruption of dating three years ago,” Virginia C. Drosos, the chief executive at Signet, which owns Kay Jewelers and Zales, told investors on Thursday. Shares of Signet, the largest jewelry retailer in the United States, tumbled after the company cut its forecasts for sales and profit for the rest of the year.                                                                                                          , In a way, the engagement ring has become a sparkly microcosm of the American economy. The bridal jewelry business is being buffeted by the delayed effects of the pandemic, rapid inflation that is squeezing consumers and a growing sense of nervousness among shoppers.                                                                                                                                                                                                                                             , Some of the volatility is owed purely to the pandemic. Weddings were canceled in droves during 2020 lockdowns, but bounced back starting in late 2021 and throughout 2022, and were expected to level off over the coming years as more typical patterns returned. Wedding-related activity does appear to show some early signs of slowing in 2023, but it is unclear whether that’s the result of a 2020 dating dry spell, per Signet, or simply a return to the longstanding shift toward later and fewer marriages., What is clear? Wedding trends are also tied to broader, and potentially longer-lasting, economic forces. Signet may be selling less because fewer people are getting down on one knee, but also because ring shoppers are becoming more cautious and spending less amid rapid inflation and rising uncertainty about the direction of the economy. Both the volume and value of jewelry sold by Signet last quarter declined.                                                                                          , Ms. Drosos said that the company had “expected the low-double-digit decline in engagements that we saw this quarter,” but that other factors were also at play. “Recent consumer confidence, lower tax refunds, economic concerns triggered by regional bank failures and continued inflation led to a weakening trend in spending across the jewelry industry,” she added.                                                                                                                                            , Consumers are contending with big challenges this year. Prices have climbed about 15 percent cumulatively over the past three years, as measured by the Personal Consumption Expenditures index. Inflation has slowed in recent months, but many workers are finding that their wages are falling behind.                                                                                                                                                                                                              , The Federal Reserve has been raising interest rates to try to cool the economy and fight the stubborn price increases. Besides making it more expensive for consumers to shop on credit or take out loans, the rate moves have increased the chance that the economy might tip into a recession.                                                                                                                                                                                                                       , As many households watch their savings dwindle and worry about their job security, they may be less willing to spend on big-ticket items like fancy diamond rings and bespoke wedding dresses.                                                                                                                                                                                                                                                                                                                         , David’s Bridal, the wedding dress retailer, suggested in a bankruptcy filing this year that some brides had become increasingly budget-conscious.                                                                                                                                                                                                                                                                                                                                                                      , An “increasing number of brides are opting for less-traditional wedding attire, including thrift wedding dresses,” James Marcum, the company’s chief executive, said in a court filing.                                                                                                                                                                                                                                                                                                                                , Like much of the economy, the wedding industry has shown signs of a split, as higher earners find that they are able to reach into their savings and keep spending, and lower-income families that spend a bigger share of their earnings on necessities like food begin to crack under the weight of inflation.                                                                                                                                                                                                       , LVMH, the luxury retail group that owns jewelers including Tiffany, reported continued growth in early 2023, including solid sales of jewelry.                                                                                                                                                                                                                                                                                                                                                                         , “Everybody was expecting 2023 to be a horrendous year for luxury in the U.S.,” Jean-Jacques Guiony, LVMH’s chief financial officer, told investors in April, explaining that a collapse had not materialized. “It’s normalizing, but it’s not bad, either.”                                                                                                                                                                                                                                                            , But at more mass-market brands like Kay and Zales, shoppers may be starting to pull back.                                                                                                                                                                                                                                                                                                                                                                                                                              , “We began to see softening at higher price points, which previously had been relatively insulated, and lower price points remained under pressure,” Joan Hilson, Signet’s finance chief, said during Thursday’s call.                                                                                                                                                                                                                                                                                                  , Signet is hoping wedding-ring demand will bounce back: It is predicting 500,000 more engagements from 2024 to 2026 than the prepandemic trend would suggest, as dating delayed by the lockdowns leads to matches. But analysts at Bank of America “worry that some of that rebound will be offset” by a “pinched consumer” spending less on jewelry, they wrote.                                                                                                                                                       , Shane McMurray, founder of the Wedding Report, is skeptical of a big gap year in engagements. He expects weddings to fall 20 percent in 2023 from 2022 levels as trends return to normal. And Lyman Stone, director of research at the consulting firm Demographic Intelligence, agreed that the current slowdown in weddings might reflect a return to previous trends rather than a one-off weakening.                                                                                                               , “It does look like 2023 is going to be a low year,” he said. “I do think that placing the blame for that on lockdowns in 2020 is a little bit strained.”                                                                                                                                                                                                                                                                                                                                                               , Jeanna Smialek writes about the Federal Reserve and the economy for The Times. She previously covered economics at Bloomberg News.   @jeannasmialek                                                                                                                                                                                                                                                                                                                                                                    , Jason Karaian is the business news director, based in London. He was previously the editor of DealBook.  @jkaraian                                                                                                                                                                                                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/china-bank-deposit-rate-cuts.html </td>
   <td style="text-align:left;"> 2023-06-09 17:00:23 </td>
   <td style="text-align:left;"> China’s Biggest Banks Cut Deposit Rates to Spur Consumer Spending - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , By Daisuke Wakabayashi                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Reporting from Seoul                                                                                                                                                                                                                                                                                                                                                                                                                                                           , In the latest attempt to boost consumer spending, China’s largest state-run banks lowered interest rates on deposits this week. The rate cuts, the second such reductions since last year, reflect a growing concern that the world’s second-largest economy has not rebounded as strongly as expected after lifting its restrictive “zero-Covid” measures.                                                                                                                    , Six commercial banks all announced that they had lowered the rate for demand deposits, essentially a checking account, to 0.2 percent from 0.25 percent. The banks cut the interest rates on deposits covering a fixed period of time.                                                                                                                                                                                                                                         , The Industrial and Commercial Bank of China, the country’s biggest lender by assets, cut the five-year deposit rate to 2.5 percent from 2.65 percent and lowered the three-year rate to 2.45 percent from 2.6 percent, according to the bank’s website.                                                                                                                                                                                                                        , A reduction in the deposit rates is one lever that policymakers can use to stimulate spending. The hope is that the lower rates will give consumers an incentive to spend or invest money instead of parking their savings in the bank.                                                                                                                                                                                                                                        , The move is an indication that consumer spending, a key driver of economic growth, remains sluggish. After China scrapped its Covid restrictions late last year and reopened the economy, there were expectations that pent-up demand would push consumers to start spending freely — but that has not played out in many sectors of the economy.                                                                                                                              , Larry Hu, chief China economist at the finance firm Macquarie Group, said the change in deposit rates “paves the way for more easing measures.” He added that the People’s Bank of China, the country’s central bank, may lower the benchmark lending rate or take other steps to stimulate the economy in the coming months. Lowering how much banks pay out on deposits can offset some of the financial pressure when China’s central bank lowers the lending rate, he said., China has predicted that its economy will recover from one of the slowest years of growth in decades last year and that gross domestic product will grow at around 5 percent in 2023. But economic weakness continues to persist.                                                                                                                                                                                                                                              , In the first three months of the year, China’s economy grew at 4.5 percent, helped by a pickup in spending on dining out and luxury goods. But the outlook appears less promising. China’s second-quarter gross domestic product figures are expected to be announced next month.                                                                                                                                                                                              , The youth unemployment rate is at a record high. The real estate market, a critical sector of the economy for investment and job creation, continues to slump with little sign of a recovery on the horizon.                                                                                                                                                                                                                                                                   , Betty Rui Wang, senior China economist at the Australia-based bank ANZ, said confidence in the economy is weak across Chinese households and private-sector businesses. She said post-Covid demand helped to push the economy in the early part of the year, but there have been signs that May was a turning point.                                                                                                                                                           , “It’s losing momentum,” said Ms. Wang.                                                                                                                                                                                                                                                                                                                                                                                                                                         , Many economists and analysts are expecting a host of new stimulus measures to be announced after next month’s meeting of the Politburo, the Chinese Communist Party’s top decision-making body.                                                                                                                                                                                                                                                                                , Some new efforts are already rolling out. The Ministry of Commerce said on Thursday that it was starting a campaign to spur more automobile sales. Spending on cars, especially electric vehicles, had been a bright spot in recent years, helped by government subsidies and tax breaks. But as Beijing has rolled back some of those measures, car sales have slowed.                                                                                                        , The ministry said it would support policies to bolster the sale of new cars. It said, for example, that it would expand electric-vehicle charging infrastructure in rural areas to make it more practical to bring the technology to the countryside.                                                                                                                                                                                                                          , Li You contributed research.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Daisuke Wakabayashi is an Asia business correspondent for The Times, based in Seoul.  @daiwaka                                                                                                                                                                                                                                                                                                                                                                                 , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:56:23 </td>
   <td style="text-align:left;"> Stocks in France Flat on Friday </td>
   <td style="text-align:left;"> The CAC 40 index traded along the flatline at 7,215 on Friday, tracking a general cautious mood, as markets focus on policy meetings from the US Federal Reserve and the European Central Bank next week. Among single stocks, Dassault Systèmes (-2.4%) posted the biggest losses, despite saying it expects a doubling of its EPS by 2028, and announcing a new CEO. On the flip side, Teleperformance (+2.6%) and Unibail-Rodamco-We (+2%) were leading the gains. China-exposed luxury stocks such as Hermes (+0.1%) and LVMH (+0.2%) were also slightly higher, as the sharp decline in producer prices in China raised bets the authorities will unleave measures to support the economy. On the week, the CAC 40 is on track to lose nearly 0.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 16:49:51 </td>
   <td style="text-align:left;"> Slovenia Industrial Output Lowest in 4 Months </td>
   <td style="text-align:left;"> Industrial production in Slovenia declined 8.8 percent year-on-year in April of 2023, following an upwardly revised 4.8 percent decrease in the previous month. It was the lowest reading since December 2022, as output dropped further for manufacturing (-7.3 percent vs -1.1 percent in March). Meanwhile, production fell at a slower pace for electricity, gas, steam &amp; air conditioning supply (-20.6 percent vs -37.9 percent) and mining and quarrying (-29.5 percent vs -34 percent). On a seasonally adjusted monthly basis, industrial output shrank 7.9 percent, reversing an upwardly revised 2.5 percent growth in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:38:00 </td>
   <td style="text-align:left;"> Hang Seng Books 2.3% Gains Weekly </td>
   <td style="text-align:left;"> Equities in Hong Kong rose 90.77 points or 0.47% to end at two-week peaks of 19,389.95 on Friday, shifting from losses in morning trade, lifted by strong wins from tech and consumers. The Hang Seng also advanced for the third day and posted a 2.3% jump weekly, with investors being upbeat amid growing calls for China's central bank to cut interest rates as a recovery in the economy weakened. May's inflation data showed that the Chinese economy cooled further, while recent reports indicated that factory activity shrank, exports plunged, and a rebound in the housing market faded. A drop in US stock futures limited the gains, however, as worries mounted that the Federal Reserve could stay hawkish in its monetary policy meeting next week following tightening moves from several central banks this week. Among top performers were ESR Group (5.9%), Chow Tai Fook Jewellery (3.9%), H World Group (3.5%),  Wuxi Biologics (3.1%), Meituan (2.8%), and Innovent Biologics (2.7%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://foxbusiness.com/lifestyle/tampa-florida-residents-may-need-least-85k-afford-rent-study-finds </td>
   <td style="text-align:left;"> 2023-06-09 16:37:34 </td>
   <td style="text-align:left;"> Tampa, Florida residents may need at least $85K to afford rent, study finds </td>
   <td style="text-align:left;"> Real estate insiders Dolly and Jenny Lenz analyze the New York and Florida real estate markets on 'The Claman Countdown.'                                                                                                                                                                                                                               , A new study found that people living or wanting to move to one of the Sunshine's state fastest growing cities need to make at least $85,000 annually to afford the skyrocketing housing costs in Florida. Throughout the pandemic, Americans flocked to Florida causing rent to soar.                                                                   , An April study conducted by Florida Atlantic University (FAU), Florida Gulf Coast University (FGCU) and the University of Alabama found that rent in Tampa, Florida is 5.04% higher than last year. According to FAU and FGCU’s report, the average rent in Tampa is $2,118.75, which ranks 18th highest among the nation’s largest metropolitan areas. , A downtown sign and city skyline are viewed on February 14, 2011 in Tampa, Florida.  (George Rose/Getty Images / Getty Images)                                                                                                                                                                                                                          , According to the U.S. Department of Housing and Urban Development (HUD), residents are considered "rent burdened" if they spend more than 30% of their annual income toward rent and "severely rent burdened" if they spend more than 50%.                                                                                                              , WATCH OUT, SILICON VALLEY: MIAMI IS VYING TO BECOME AMERICA'S AI HUB                                                                                                                                                                                                                                                                                    , With the average rent and the HUD's definition of "rent burdened," individuals would need to make $84,750.12 to avoid being "rent burdened."                                                                                                                                                                                                            , Aerial drone View of sprawling Tampa Bay Skyline, Florida. (Joe Sohm/Visions of America/Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                                         , In 2022, during the COVID-19 pandemic, Florida saw about 319,000 Americans relocating as people sought more relaxed coronavirus rules, sunnier weather and no state income tax.                                                                                                                                                                         , FED PAUSING RATE INCREASES IN JUNE MAKES IT HARDER TO HIKE LATER: KATHRYN ROONEY VERA                                                                                                                                                                                                                                                                   , Florida saw a populating increase of nearly 2% – well above the 0.4% national growth rate recorded in the U.S. between July 2021 and July 2022.                                                                                                                                                                                                         , From 2020 to 2023, Tampa saw its population grow by a little less than 1% in 2023, compared with a more than 2% increase the previous two years. Orlando, Florida, matched Tampa with similar growth rates.                                                                                                                                             , Aerial View of road to Sunshine Skyway Bridge to Tampa Bay Florida and St. Petersburg.   | Getty Images                                                                                                                                                                                                                                                 , The Exodus to Florida was marked by Americans migrating away from blue states with steep taxes like California and New York to red states with lower taxes like Florida and Texas, according to a Bank of America analyst note that is based on aggregated and anonymous internal customer data.                                                        , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                 , Other red states saw substantial population growth include Texas, North Carolina, South Carolina, Tennessee, Georgia, Arizona and Idaho. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:35:00 </td>
   <td style="text-align:left;"> South African Stocks Slightly Up </td>
   <td style="text-align:left;"> The JSE FTSE All Share index was slightly up around 77,170 on Friday, its highest in over a week, mainly driven by heavyweight tech Naspers and Prosus, industrials and financials. Meanwhile, global investors keep a cautious stance ahead of the U.S. inflation release for May due next week, and the outcome of the Fed's two-day rate decision meeting, starting Tuesday. On the domestic front, the head of the presidency's project management office stated the energy crisis in South Africa should begin abating toward the end of the year, as repairs to Eskom’s two newest power stations Medupi and Kusile and the completion of maintenance at its Koeberg nuclear plant will be prioritized. The JSE was set to close the week almost flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/currency </td>
   <td style="text-align:left;"> 2023-06-09 16:33:00 </td>
   <td style="text-align:left;"> Turkish Lira Weakens to Fresh Record Low </td>
   <td style="text-align:left;"> The Turkish lira continued to weaken to a new record low of 23.5 per USD, extending the monthly loss to 13%, and bringing the total depreciation to about 18% since the runoff election on May 28th. Following the appointment of Mehmet Simsek, a former deputy prime minister known for his market-friendly policies, as the new finance minister, President Tayyip Erdogan appointed Hafize Gaye Erkan, formerly a co-CEO at First Republic Bank and a managing director at Goldman Sachs, as the head of Turkey's central bank. These moves were seen as a strong signal of a shift from unorthodox economic policies that had led to high inflation, low interest rates, a plummeting lira, and negative net foreign exchange reserves. Meanwhile, annual inflation rate has eased for the seventh consecutive month to 39.6% in May, mainly due to the government's move to provide unlimited free natural gas for all households for a year but it is still far from the central bank's target rate of 22.3% for 2023. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/retail-sales-annual </td>
   <td style="text-align:left;"> 2023-06-09 16:24:00 </td>
   <td style="text-align:left;"> Bulgaria Retail Sales Shrink the Most in Near 3 Years </td>
   <td style="text-align:left;"> Retail sales in Bulgaria contracted 2 percent year-on-year in April 2023, following a 1.1 percent rise in the previous month. It marked the first decline since July 2022 and the steepest since July 2020, as trade of non-food products decreased (-4.1 percent vs 0.9 percent in March), particularly computers, peripheral units, software and telecommunication equipment. At the same time, sales of food products stalled (vs 1.7%). On a seasonally adjusted monthly basis, retail trade shrank 2 percent, the largest fall since April 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/industrial-production-mom </td>
   <td style="text-align:left;"> 2023-06-09 16:24:00 </td>
   <td style="text-align:left;"> Italy Industrial Production Contracts for 4th Month </td>
   <td style="text-align:left;"> Industrial production in Italy sank by 1.9% from a month earlier in April of 2023, the fourth consecutive monthly contraction and the sharpest since September 2022, missing market forecasts of a 0.1% expansion to underscore that the industrial sector is under heavy pressure from higher borrowing costs set by the ECB. Output contracted for intermediate goods (-2.6% vs -0.4% in March), capital goods (-2.1% vs 0.7%), consumer goods (-0.4% vs -1.5%), and energy (-0.3% vs -1.7%). On a yearly basis, industrial production plummeted by 7.2%, the most since July 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 16:12:22 </td>
   <td style="text-align:left;"> Bulgaria Industrial Output Falls the Most Since 2020 </td>
   <td style="text-align:left;"> Industrial output in Bulgaria slumped 12.6% year-on-year in April 2023, the fourth consecutive month of decline in industrial activity, and from 9% fall in the previous month. It was the steepest contraction since May 2020, as output for manufacturing (-8.2% vs -0.9% in March) continued to fall sharply. Meanwhile, output declined at softer pace for mining &amp; quarrying (-10.5% vs -14.3%) and electricity, gas, steam &amp; air-conditioning supply (-38.7% vs -39.3%). On a monthly basis, industrial production went down to 2.9% in April, from a 1.2% drop in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/construction-output </td>
   <td style="text-align:left;"> 2023-06-09 16:09:00 </td>
   <td style="text-align:left;"> Bulgaria Construction Output Falls in April </td>
   <td style="text-align:left;"> Construction output in Bulgaria decreased by 2.3 percent year-on-year in April of 2023, reversing a 0.3 percent rise in the prior month, as both building construction (-0.5 percent vs 2.4 percent in March) and civil engineering (-4.7 percent vs -2.5 percent) declined. On a seasonally adjusted monthly basis, construction output was down by 1 percent, following a 0.4 percent gain in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 16:07:00 </td>
   <td style="text-align:left;"> Italian Stocks Almost Flat </td>
   <td style="text-align:left;"> The FTSE MIB index traded near the flatline around 27,300 on Friday, in line with its regional peers, as investors continued to assess the outlook for the global economy and interest rates ahead of key central bank meetings from the Fed and the ECB next week. Regarding the domestic economy, latest data showed Italy's industrial activity fell further in April and by more than analysts had anticipated. On the corporate front, Telecom Italia (+1.3%) was in focus as the US fund Kkr and the rival consortium formed by Cassa Depositi e Prestiti and the Australian fund Macquarie are set to present their respective improved offers for the network in view of today's deadline. Erg (+1.1%) and Leonardo (+1%) also advanced firmly, while Moncler (-1.1%), Inwit (-1%) and Interpump Group (-0.9%) posted the biggest losses. For the week, the FTSE MIB was on track to book a nearly 1% gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palm-oil </td>
   <td style="text-align:left;"> 2023-06-09 16:03:00 </td>
   <td style="text-align:left;"> Palm Oil Futures Move Higher </td>
   <td style="text-align:left;"> Malaysian palm oil futures were trading near MYR 3,400 per tonne after falling to around MYR 3,260 earlier in the week, supported by strong demand from China and  India. China reportedly increased its purchases of tropical oil in May, as it tried to replenish its stockpiles ahead of the peak consumption season. For the week, however, the contract was on course for a second weekly drop, with signs of rising production and inventories growing. Investors now await Malaysian Palm Oil Board data due Monday to study the extent of a rise in May production. Reuters projected that the country’s palm oil production jumped 21% to 1.45 metric tons last month, the highest level since last December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/09/ubs-and-the-swiss-governmen-sign-loss-protection-agreement-over-credit-suisse-takeover.html </td>
   <td style="text-align:left;"> 2023-06-09 15:58:42 </td>
   <td style="text-align:left;"> UBS and the Swiss government sign loss protection agreement over Credit Suisse takeover </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                                                , Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                                               , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                                                                         , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Banking                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                             , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                   , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                                                                           , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                                                                            , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                            , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                                                                                    , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                                                                                , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                      , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                          , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                              , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                                              , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                                                              , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                                                                                       , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                                                            , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , All Investing                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                                                                              , ETFs                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Bonds                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                           , UBS and the Swiss government announced Friday that they had signed a loss protection agreement, which will come into effect once the takeover of Credit Suisse is completed.                                                                                                                                                                                                                                                                                              , The provisions will see the Swiss government cover losses of up to 9 billion Swiss francs ($10 billion) following UBS' acquisition of its former rival. This is guaranteed on a "designated portfolio of Credit Suisse non-core assets," once UBS incurs the first 5 billion Swiss francs in losses.                                                                                                                                                                      , "The priority for the federal government and UBS is to minimise potential losses and risks so that recourse to the federal guarantee is avoided to the greatest extent possible," the Swiss government said in a statement.                                                                                                                                                                                                                                               , The administration added that it had facilitated the deal to "safeguard financial stability and thus avert damage to the Swiss economy," but had always agreed to guarantee a portion of losses due to UBS taking over a portfolio of assets that "do not fit its business and risk profile."                                                                                                                                                                             , In return, the agreement states that, after the takeover, UBS must support the development of Switzerland's status as a financial centre. The bank has confirmed intentions to keep the headquarters of the merged group in Switzerland for the duration of the loss protection provisions.                                                                                                                                                                               , "UBS will manage these assets in a prudent and diligent manner and intends to minimize any losses and maximize value realization on these assets," UBS said.                                                                                                                                                                                                                                                                                                              , UBS Group shares were down 0.2% at 10:00 a.m. London time.                                                                                                                                                                                                                                                                                                                                                                                                                , Last month, the bank disclosed it anticipated a financial hit of around $17 billion as a result of acquiring its rival, in what has been described in some quarters as a "shotgun wedding" to stabilize the Swiss financial system.                                                                                                                                                                                                                                       , The Swiss banking rivals agreed a $3.2 billion takeover deal at the start of spring, at a time of broader volatility in the banking sector that led to the collapse of three U.S. banks. Credit Suisse shares cratered through early March, with years of scandals, losses and alleged mismanagement coming to a head when its largest shareholder, the Saudi National Bank, said it was not able to provide any more cash to the bank because of regulatory restrictions., The merger of the two banking juggernauts has been greeted with some controversy, enraging Credit Suisse shareholders and bondholders as well as raising competition concerns.                                                                                                                                                                                                                                                                                            , The bank expects the Credit Suisse acquisition to complete as early as June 12.                                                                                                                                                                                                                                                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                          , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 15:45:00 </td>
   <td style="text-align:left;"> British Shares Hover Marginally Lower on Friday </td>
   <td style="text-align:left;"> The FTSE 100 hovered slightly below the flatline at the 7,590 level on Friday, also set to notch slight losses on the week as markets continued to assess the outlook on the economy ahead of incoming interest rate hikes. Energy shares booked losses after the British government announced that the current Energy Profits Levy on oil giants will remain until 2028, while a floor was set on the windfall tax. Both BP and Shell hovered around 0.5% lower. In the meantime, chemicals company Croda sank 12% after issuing a profit warning. On the other hand, miners edged higher with a 0.5% gain for Rio Tinto and Glencore despite the muted session for bullion prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 15:40:14 </td>
   <td style="text-align:left;"> The Shangai Composite Index rose 0.55% </td>
   <td style="text-align:left;"> In China the Shangai Composite Index rose 18 points or 0.55 percent on Friday. Leading the gains are Sh Pharmaceutical (3.65%), Sdic Power (2.50%) and BAIC BluePark (2.44%). Top losers were Poly Real Estate (-4.43%), Sanan Optoelectron (-4.41%) and China CITIC Bank (-3.80%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 15:39:00 </td>
   <td style="text-align:left;"> European Shares Subdued to End the Week </td>
   <td style="text-align:left;"> The DAX lost nearly 0.4% and the pan-European STOXX 600 traded around the flatline on Friday, as investors continue to assess the global economic outlook while awaiting key monetary policy decisions from the Fed and the ECB next week. There are no major economic releases today, so in the absence of further catalysts, trading is likely to remain lacklustre. Shares of chemicals were the worst performers, falling nearly 1.3% after earnings from Croda International disappointed, while tech and utilities were up nearly 0.2%. On the week, the DAX is down about 0.7% and the STOXX 600 lost nearly 0.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/moldova/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 15:28:09 </td>
   <td style="text-align:left;"> Moldova Inflation Slows for 7th Month </td>
   <td style="text-align:left;"> The annual inflation rate in Moldova dropped to a nearly one-and-a-half-year low of 16.3 percent in May 2023 from 18.3 percent in April, easing for the seventh month, as costs slowed for food products (14 percent vs 16.4 percent in the previous period) and non-food products (8.2 percent vs 10.6 percent ). Meanwhile, services inflation was little changed (33.3 percent vs 33.2 percent). Monthly, consumer prices increased 0.5 percent, following a 2.2 percent jump in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovakia/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 15:24:58 </td>
   <td style="text-align:left;"> Slovakia Trade Balance Swings to Surplus in April </td>
   <td style="text-align:left;"> Slovakia recorded a trade surplus of EUR 292.9 million in April 2023, compared to a deficit of EUR 516.4 million in the corresponding month of the previous year, preliminary estimates showed. Year-on-year, exports increased 7.4% to EUR 8,419 million, largely due to higher sales of machinery and transport equipment (25.9%), in particular motor vehicles and aircraft. Meanwhile, imports declined for the first time in over two years by 2.7% to EUR 8,126.1 million, as purchases dropped for mineral fuels (-45.5%), which includes oil, electricity and natural gas. The majority of goods from both of these sections were destined for EU markets. Considering the January-April period, the country posted a trade surplus of EUR 1,072 million, shifting from a deficit of EUR 1,657.5 million in the same period a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/turkey/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 15:24:00 </td>
   <td style="text-align:left;"> Turkey Industrial Output Unexpectedly Drops in April </td>
   <td style="text-align:left;"> Turkey’s industrial production unexpectedly fell by 1.2% year-on-year in April 2023, missing market forecasts of 1.2% gain, and shifting from an upwardly revised 0.4% growth in the previous month. Production continued to decline for mining &amp; quarrying (-12.2% vs -10.4% in March) and electricity, gas, steam &amp; air conditioning supply (-4.3% vs -7.8%). Meanwhile, output in manufacturing activities showed no growth (0% vs 1.9%). On a seasonally adjusted monthly basis, industrial output slumped 0.9%, reversing a downwardly revised 5.8% gain in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 15:15:27 </td>
   <td style="text-align:left;"> Austria Industrial Output Accelerates in April </td>
   <td style="text-align:left;"> Industrial production in Austria advanced 1% year-on-year in April 2023, accelerating from an upwardly revised 0.1% rise in the previous month, due to the strong rebound in production of energy (5.5% vs -10% in March). On the other hand, output eased for capital goods (6.7% vs 6.8%), consumer durables (2.7% vs 10.2%) and non-durables (3.2% vs 7.8%), while it fell further for intermediate goods (-4.5% vs -4.2%). On a seasonally adjusted monthly basis, industrial production rose 0.9%, recovering from a 3.4% drop in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovakia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 15:15:17 </td>
   <td style="text-align:left;"> Slovak Industrial Output Slips in April </td>
   <td style="text-align:left;"> Industrial production in Slovakia shrank 2% year-on-year in April 2023, following a 2.5% rise in the previous month. Output declined for manufacturing (-1.2% vs 3.3% in March), dragged down by the manufacture of textiles, apparel, leather &amp; related products (-10.6% vs 2.6%), manufacture of coke &amp; refined petroleum products (-11.1% vs 20.4%), and other manufacturing and repair &amp; installation of machinery &amp; equipment (-0.3% vs 4.6%). Meanwhile, output rebounded for manufacture of machinery &amp; equipment n.e.c (0.6% vs -1.1%), while increased sharply for manufacture of pharmaceuticals, medicinal chemical &amp; botanical products (43.3% vs 10.9%). On a seasonally adjusted monthly basis, industrial activity tumbled 1.2% in April, from 1.7% gain in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/prime-monster-energy-drinks-caffeine.html </td>
   <td style="text-align:left;"> 2023-06-09 15:00:21 </td>
   <td style="text-align:left;"> Energy Drinks Are Surging. So Are Their Caffeine Levels. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , More companies are pushing low-calorie, sugar-free beverages they say are healthy. Some servings have nearly the same level of caffeine as a six-pack of Coca-Cola.                                                                                                                                                                                                                                                                                                                                                                                                     , By Julie Creswell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , It has been more than 25 years since Red Bull hit the market and introduced caffeinated energy drinks to the United States. While the company claimed its beverage would “give you wings,” it never said it was actually good for people.                                                                                                                                                                                                                                                                                                                               , Yet as the energy drink market continues to grow rapidly, companies both new and old are trying to attract health-conscious customers with a wave of no-sugar, low-calorie drinks that claim to boost energy as well as replenish fluids with electrolytes and other ingredients.                                                                                                                                                                                                                                                                                       , The offerings include drinks from the popular brand Celsius, which has an investment from PepsiCo and uses the marketing line “Celsius Live Fit.” It claims to be made with “healthier ingredients” like ginger, green tea and vitamins. Likewise, the influencer-backed Prime Energy is sugar-free and has electrolytes, a main ingredient in most sports drinks.                                                                                                                                                                                                      , “All of them are zero sugar or zero calories,” said Jim Watson, a beverage analyst at Rabobank, a bank based in the Netherlands with a focus on food and agriculture. He added that energy drink consumption had increased partly because of the decades-long move away from sugary soda. “They’re going for the healthy image.”                                                                                                                                                                                                                                        , Even Gatorade, which has long marketed beverages to athletes hoping to replenish lost fluids or electrolytes after strenuous exercise, is jumping into the caffeine arms race. This year, Gatorade released Fast Twitch, a sugar-free beverage in flavors like Strawberry Watermelon and Cool Blue — with caffeine levels equivalent to more than two cups of coffee.                                                                                                                                                                                                   , This new focus has helped the energy drink market grow, with sales in the United States surging to $19 billion from $12 billion over the past five years, according to Circana, a market research firm.                                                                                                                                                                                                                                                                                                                                                                 , Last year, PepsiCo paid $550 million for an 8.5 percent stake in Celsius. In May, Celsius said revenues were $260 million in the first quarter of this year, double what they were a year earlier. At that ferocious pace, revenues could cross $1 billion this year, increasing from $314 million just two years ago. Shares of Celsius have shot up to $144 a share from $69 a year ago. Likewise, the stock of the beverage company Monster Energy has increased 31 percent in the past year.                                                                        , But there are concerns that drinks being pitched as healthy are resulting in children and teenagers consuming caffeine in unhealthy amounts.                                                                                                                                                                                                                                                                                                                                                                                                                            , In March, neon-colored Prime Energy cans began appearing in a lunchroom filled with fourth and fifth graders in the Wilmington public school district in Massachusetts. The popular drinks were released in January by the social media stars Logan Paul and Olajide Olayinka Williams Olatunji, better known as KSI.                                                                                                                                                                                                                                                   , For some young students, the Prime Energy drinks, which come in flavors like Strawberry Watermelon and Orange Mango, were delicious liquid gold.                                                                                                                                                                                                                                                                                                                                                                                                                        , “We even had entrepreneurs in fourth and fifth grade who were bringing them to school and selling them to other kids at lunch,” said Rebecca Brown, the health services coordinator for the district.                                                                                                                                                                                                                                                                                                                                                                   , But the eye-popping cans pack a serious punch. A 12-ounce can of Prime Energy contains 200 milligrams of caffeine. That’s roughly equivalent to two Red Bulls, two cups of coffee or six cans of Coca-Cola.                                                                                                                                                                                                                                                                                                                                                             , Some schools in Britain and Australia have already banned the beverages. In the United States, federal regulations say schools cannot sell or provide caffeinated drinks to elementary or middle school students, although many schools do not restrict what students can bring from home.                                                                                                                                                                                                                                                                              , “Not long after drinking them, the students showed up in the health office saying they didn’t feel good and that their hearts were racing,” said Ms. Brown, who inserted a note in the school’s weekly email to parents saying the energy drinks should not be brought to school.                                                                                                                                                                                                                                                                                       , A 12-ounce can of Red Bull contains about 114 milligrams of caffeine — more than three times the amount in a 12-ounce can of Coca-Cola. Prime Energy has more: 200 milligrams in each 12-ounce can. A 16-ounce can of Bang Energy Drink, the size typically sold in convenience stores, has 300 milligrams of caffeine.                                                                                                                                                                                                                                                 , In an email response to questions, representatives for Mr. Paul, the social media personality, and Prime Energy noted that the company’s cans labeled the drink as “not recommended for children under 18.” But parents and school officials are sometimes confusing the drink with Prime Hydration, a caffeine-free sports drink from the social media stars that is sold in bottles. That drink is also immensely popular, with more than $250 million in sales in its first year and customers waiting in line for hours to buy it at some grocery stores in Britain., “Everybody thought Red Bull was the peak of caffeine in energy drinks,” said Dr. Ryan Stanton, an emergency physician in Lexington, Ky., who said he saw patients, especially around finals weeks at local colleges, come in complaining about feeling anxious and experiencing racing heartbeats after consuming too much caffeine. “Now, some of these drinks have two or three times the level of caffeine as Red Bull.”                                                                                                                                             , Studies have shown that consuming caffeine may have health benefits, but that too much could result in cardiovascular and gastric issues. The Food and Drug Administration has investigated a handful of reports over the years involving people dying shortly after consuming energy drinks or five-hour energy shots. But the agency has never established a link between the two, a spokesman for the F.D.A. said in a response to emailed questions.                                                                                                                , Adults are recommended to have no more than 400 milligrams of caffeine per day. Pediatricians recommend that youths ages 12 to 18 should not consume more than 100 milligrams of caffeine per day and that children under 12 should avoid caffeine completely.                                                                                                                                                                                                                                                                                                          , Over the years, there have been efforts to increase government regulation of energy drinks and limit the caffeine allowed in beverages. Lawmakers in several states, including Indiana and Connecticut, have considered banning the sale of energy drinks to minors. But the industry has successfully pushed back, in part by arguing that young people can get caffeine from myriad sources, including soda and coffee. A 16-ounce cinnamon-caramel-cream cold brew from Starbucks, for instance, contains 265 milligrams of caffeine (not to mention 260 calories).  , About a decade ago, the energy drink industry, through its lobbying arm, the American Beverage Association, voluntarily adopted a set of principles, including labeling the amount of caffeine in products and noting on packaging that the beverages were not recommended for children. The industry also agreed not to sell or market its products in schools.                                                                                                                                                                                                        , But critics say some energy drinks are clearly marketed toward younger customers. Last year, the consumer advocacy group Truth in Advertising said companies like C4 Energy, which sells drinks in flavors like Starburst and Skittles, and Ghost Energy, which sells Sour Patch Kids and Swedish Fish-flavored drinks that contain more caffeine than two cups of coffee, were trying to appeal to minors.                                                                                                                                                             , Dan Lourenco, the chief executive and co-founder of Ghost, said in an email that the company’s products were geared toward millennials seeking the nostalgic flavors of their youth. C4 Energy, which is owned by Nutrabolt, did not respond to an email seeking comment.                                                                                                                                                                                                                                                                                               , The U.S. Department of Agriculture, whose Smart Snacks program creates the nutritional standards for foods and beverages sold in schools, said any products sold in elementary and middle schools must be caffeine-free. But for beverages sold in high schools, there are restrictions on the number of calories but none on the level of caffeine.                                                                                                                                                                                                                    , Moreover, the F.D.A. does not have specific regulations around “energy drinks,” deeming it a marketing term. A spokesman for the agency added in an email that companies were still responsible for including a safe amount of caffeine in beverages.                                                                                                                                                                                                                                                                                                                   , Chloe Fitzgibbon, 17, who graduated in May from Lincoln Southeast High School in Lincoln, Neb., questioned whether the school cafeteria should be selling energy drinks in an article published last year on the website of the school’s newspaper, The Clarion. Noting that the school sold Mountain Dew’s version, Kickstart, Ms. Fitzgibbon said students opted for the drink not only for the energy jolt but for the ease of buying it through their student accounts.                                                                                             , The high school cafeteria sells a number of caffeinated beverages, including Kickstart, which has 68 milligrams of caffeine in a 12-ounce can, and Bubbl’r, a sparkling water with 69 milligrams of caffeine in a 12-ounce can. Mindy Burbach, a spokeswoman for Lincoln Public Schools, said in an email that students were limited to buying two caffeinated beverages each day.                                                                                                                                                                                      , “When I took an early-morning class, A.P. Psych, almost everyone came in with a coffee or they would buy the energy drinks that we sell at school,” Ms. Fitzgibbon said.                                                                                                                                                                                                                                                                                                                                                                                                , Pasco County Schools, a Florida district just north of Tampa, also offers Kickstart drinks to high school students in its vending machines. But Stephen Hegarty, a spokesman for the district, noted that PepsiCo, which owns the brand, marketed the beverage as an “enhanced soft drink,” not an “energy drink.” PepsiCo declined to comment.                                                                                                                                                                                                                         , “If you go to any of our high schools, you’ll see students walking in with Starbucks, and some of those drinks have a lot of caffeine,” Mr. Hegarty said. “I’m not sure what the definition of an energy drink is these days.”                                                                                                                                                                                                                                                                                                                                          , Julie Creswell is a New York-based reporter. She has covered banks, private equity, retail and health care. She previously worked for Fortune Magazine and also wrote about debt, monetary policy and mutual funds at Dow Jones.  @julie_creswell                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tanzania/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 14:51:00 </td>
   <td style="text-align:left;"> Tanzania Inflation Rate Eases to 1-Year Low </td>
   <td style="text-align:left;"> Tanzania's annual inflation rate eased to 4% in May 2023,  the lowest in a year, from 4.3% rise in the previous month. Food inflation surged at the softest pace in 8 months (8.5% vs 9.1% in April). There was also a slowdown in prices of transport (1.3% vs 4.3%) and furnishings &amp; household equipment (2.9% vs 3.1%). On the other hand, inflation accelerated for housing &amp; utilities (0.8% vs 0.3%), clothing &amp; footwear (3.3% vs 2.8%) and recreation, sport &amp; culture (1.9% vs 1.8%). The core rate, which excludes volatile items such as unprocessed food and energy, stood at 2% in May, unchanged from the previous month. On a monthly basis, consumer prices advanced by 0.2%, after rising by 0.4% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 14:47:00 </td>
   <td style="text-align:left;"> Lithuania Posts Smallest Trade Gap in 15 Months </td>
   <td style="text-align:left;"> Lithuania's trade deficit fell to EUR 0.31 billion in April 2023 from EUR 0.83 billion in the same month a year earlier. It was the smallest trade gap since January 2022, as exports decreased less than imports. Imports plunged 16% from a year earlier to EUR 3.61 billion, dragged down by lower purchases of mineral fuels, mineral oils and products of their distillation (-41.3%), iron and steel (-55.4%) and organic chemicals (-40.3%). At the same time, exports dropped 5.1% to EUR 3.29 billion, amid declines in sales of mineral fuels, mineral oils and products of their distillation (-32.7%), wood and wood products (-31.9%) and furniture (-18.2%). Considering the first four months of the year, the country's trade deficit narrowed to EUR 1.73 billion from EUR 2.32 billion in the corresponding period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 14:42:00 </td>
   <td style="text-align:left;"> New Zealand Stocks End Week on Downbeat Note </td>
   <td style="text-align:left;"> New Zealand's shares lost 25.4 points or 0.22% to close at 11,690.34 on Friday after trading slightly higher in early trade, declining for the fifth day in a row while sliding 1.6% for the week, rattled by a drop in US stock futures amid speculation of the Federal Reserve keeping interest rates higher for longer. Meantime, inflation data from China, New Zealand's main trading partner, provided fresh signs that the economy cooled further in May. Traders also took a cautious stance ahead of New Zealand's Q1 GDP readings that will be due next week. Several economists forecast that the domestic economy had already been in recession, while local media said that the GDP print was probably a bit flat after contracting by 0.6% in Q4 of 2022 as efforts to rebuild activity from severe weather events continue. Among the biggest laggards were Delegat Group Ltd. (-3.2%), Fisher &amp; Paykel Healthcare (-2.2%), A2 Milk Co. (-1.6%), PGG Wrightson Ltd. (-1.5%), and Briscoe Group (-1.4%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 14:30:09 </td>
   <td style="text-align:left;"> The Nikkei 225 Index went up by 1.93% </td>
   <td style="text-align:left;"> In Tokyo the Nikkei 225 Index gained 610 points or 1.93 percent on Friday. Gains were led by Konami (5.66%), Fast Retailing (4.77%) and Marubeni (4.52%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/household-spending-mom </td>
   <td style="text-align:left;"> 2023-06-09 14:27:07 </td>
   <td style="text-align:left;"> Sweden Household Spending Rebounds </td>
   <td style="text-align:left;"> Household Spending in Sweden jumped 1.2% month-over-month in April of 2023, the biggest increase since March of 2022, following a downwardly revised 0.2% decline in the previous month. Compare to a year earlier, household consumption stalled, with retail trade, mostly food and beverages accounting for the largest weighted negative contribution (-6.1%)- On the other hand, retail sales of motor vehicles increased 2.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/romania/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 14:25:20 </td>
   <td style="text-align:left;"> Romania Trade Gap Narrows </td>
   <td style="text-align:left;"> Romania’s trade deficit decreased to EUR 2.06 billion in April 2023 from EUR 2.84 billion in the same month a year earlier. Exports grew by 4.9% from a year earlier to EUR 7.23 billion, as shipments rose both to EU countries (2.5%) and non-EU countries (11.6%). Meantime, imports fell 4.5% to EUR9.29 billion, amid lower purchases mainly from non-EU countries (-15.1%). Considering the first four months of the year, the trade gap narrowed to EUR 8.86 billion from EUR 10.04 billion in the corresponding period of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/lithuania/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 14:25:00 </td>
   <td style="text-align:left;"> Lithuania Producer Prices Drop for 2nd Month </td>
   <td style="text-align:left;"> Producer prices in Lithuania shrank 5.6% year-on-year in May 2023, extending the revised 0.2% drop in the prior month. It was the second consecutive month of deflation and the lowest reading since January 2021, due to lower cost in manufacturing (-8.8% vs -3.7% in April), particularly coke and refined petroleum products (-29.4% vs -16.4%). Additionally, prices eased for mining and quarrying (8.3% vs 13%), electricity, gas, steam &amp; air-conditioning supply (34.5% vs 45.8%), and water supply, sewerage, waste management &amp; remediation activities (24.7% vs 24.9%). On a monthly basis, producer prices fell by 2.3%, following a revised 2.5% decline in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/new-orders </td>
   <td style="text-align:left;"> 2023-06-09 14:24:49 </td>
   <td style="text-align:left;"> Swedish New Orders Drop 0.1% YoY in April </td>
   <td style="text-align:left;"> Total orders received by Swedish industries fell 0.1 percent year-on-year in April of 2023, following a downwardly revised 8 percent drop in the previous month. Orders from customers in Sweden declined (-4.7 percent vs 2 percent in March) while those from abroad rebounded (2.4 percent vs -14.9 percent). On a seasonally adjusted monthly basis, new orders surged 3 percent, reversing a 0.4 percent decline in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 14:24:00 </td>
   <td style="text-align:left;"> European Markets Set to Open Slightly Higher </td>
   <td style="text-align:left;"> European equity markets were set to open slightly higher on Friday, tracking gains among global peers as US Treasury yields fell after a surge in new unemployment claims in the US reinforced expectations that the Federal Reserve would hold interest rates steady next week. The European Central Bank is also set to decide on monetary policy next week. Meanwhile, investors remain cautious as the IMF urged major central banks to “stay the course” on monetary policy and watch inflation closely. There are no major data and earnings releases on Friday. DAX, Stoxx 600 and FTSE 100 futures drifted flat to slightly positive in premarket trade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/monthly-gdp-mom </td>
   <td style="text-align:left;"> 2023-06-09 14:17:02 </td>
   <td style="text-align:left;"> Swedish Economy Stalls in April </td>
   <td style="text-align:left;"> The Swedish economy flattened between April and March 2023, after falling 0.1% in the previous period. There were limited changes in several big aggregates. Compared to a year earlier, the GDP was 0.1% lower. April 2023 had one less working day than April 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/producer-prices-change </td>
   <td style="text-align:left;"> 2023-06-09 14:16:06 </td>
   <td style="text-align:left;"> Norway Producer Prices Lowest on Record </td>
   <td style="text-align:left;"> Producer prices in Norway shrank 23.5% year-on-year in May 2023, the fifth consecutive month of decline, and compared with 15.3% fall in the previous month. It was also marked as the lowest reading since records began in 2001, as prices continued to contract for energy goods (-37.8% vs -37.5%). At the same time, prices for electricity, gas &amp; steam declined (-9.2% vs 3.1%), while slowed for manufacturing (3% vs 10.4%). On a monthly basis, producer prices fell sharply to 8.3%, shifting from a 0.8% growth in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 14:16:00 </td>
   <td style="text-align:left;"> Norway Inflation Rate Rises to 6.7% in May </td>
   <td style="text-align:left;"> The annual inflation rate in Norway increased to 6.7% in May 2023 from 6.4% in the previous month and above market forecasts of 6.2%. Prices accelerated mainly for food &amp; non-alcoholic beverages (12.7% vs 10.5% in April), housing &amp; utilities (5% vs 4%), clothing &amp; footwear (3.4% vs 2.5%) and alcoholic beverages &amp; tobacco (6% vs 5.2%). On the other hand, inflation primarily slowed for transport (7.5% vs 7.9%), furnishings, household equipment &amp; maintenance (7.1% vs 10.9%) and recreation &amp; culture (7.3% vs 8.2%). Meanwhile, the CPI adjusted for tax changes and excluding energy products, advanced by 6.7% year-on-year, the highest reading since comparable records began in 2003. On a monthly basis, consumer prices rose 0.5%, slowing from a 1.1% jump in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/current-account </td>
   <td style="text-align:left;"> 2023-06-09 14:12:45 </td>
   <td style="text-align:left;"> Danish Current Account Surplus Largest in 8 Months </td>
   <td style="text-align:left;"> Denmark's current account surplus increased to DKK 35.6 billion in April 2023 in seasonally adjusted terms from DKK 33.0 billion in the prior month. It was the largest amount since last August, as the surplus of goods accounts rose to DKK 19.4 billion from DKK 17.6 billion in March and that of services account ticked higher to DKK 6.8 billion from DKK 6.5 billion. Also, the secondary income deficit fell to DKK 1.3 billion from DKK 2.2 billion in March. Meantime, the surplus of primary income surplus edged lower to DKK 10.7 billion from DKK 11.2 billion, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2023-06-09 14:11:00 </td>
   <td style="text-align:left;"> China 10-Year Bond Yield Hits 30-week Low </td>
   <td style="text-align:left;"> The yield on the 10-year Chinese government bond has been decreasing since the beginning of the year and fell below 2.7% in June, the lowest in eight months, as concerns mount regarding a sluggish recovery and a weakened outlook for the Chinese economy. Fresh data showed producer prices fell the most since 2016 and inflation rose less than expected, exports sank and imports were also lower while the official manufacturing PMI pointed to a second straight month of contraction in factory activity. These discouraging figures have heightened expectations that Chinese authorities will introduce additional stimulus measures to support the economy, potentially including a reduction in the reserve requirement ratio for banks. Yet, China's biggest banks recently lowered interest rates on a range of deposit products for both yuans and dollars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 14:11:00 </td>
   <td style="text-align:left;"> Swedish Industrial Output Growth Accelerates in April </td>
   <td style="text-align:left;"> Industrial production in Sweden rose by 3.4% year-on-year in April of 2023, following an upwardly revised 0.6% growth in March. The biggest upward contribution came from the motor vehicle industry (25.5%) while the largest downward contribution came from the pulp and paper industry (-20.4%). On a seasonally adjusted monthly basis, industrial production surged by 1.8%, reversing a 2.8% drop in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 14:05:00 </td>
   <td style="text-align:left;"> Danish Trade Surplus Largest in 3 Months </td>
   <td style="text-align:left;"> Denmark’s goods and services trade surplus increased to a seasonally adjusted DKK 26.2 billion in April 2023 from a downwardly revised DKK 24.1 billion in the prior month, pointing to the largest trade surplus since January as exports dropped less than imports. Exports fell by 1.2 percent from a month earlier to DKK 154.7 billion, due to a decline in the export of services, while imports shrank by 3.1 percent to DKK 128.5 billion. For the first four months of the year, the country's trade surplus widened to DKK 100 billion from DKK 88.5 billion in the corresponding period of the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 13:52:00 </td>
   <td style="text-align:left;"> India Shares Set to Close Week Slightly Higher </td>
   <td style="text-align:left;"> The BSE Sensex dropped 104.7 points or 0.1% to 62,765.3 in morning trade on Friday, down for the second session in a row, amid caution after several major central banks hiked interest rates this week. Market participants also anticipated US inflation data for May, which could provide clues for the Fed's next step next week. Meantime, the annual inflation is expected to ease to a 20-month low of 4.42% in May, staying within the RBI's 2%-6% target range for the second straight month and raising hopes that the RBI will continue to hold the interest rate for the third consecutive meeting. Tech stocks, consumer goods, and metals were mainly lower, amid falls from Hindustan Unilever (-1.7%), Tata Steel (-148%), and Infosys (-1.3%). Still, the index for the week is heading for a  0.3% rise, supported by robust foreign fund inflows, a flourishing service sector, and a narrowing current account deficit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/binance-us-trading-halt.html </td>
   <td style="text-align:left;"> 2023-06-09 13:44:43 </td>
   <td style="text-align:left;"> Binance Halts Trading in Dollars on Binance.US - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                         , Banks have signaled that they will stop working with the company’s American branch, it said, after the Securities and Exchange Commission sued it this week.                                                                                                                                                                                                                                                         , By David Yaffe-Bellany                                                                                                                                                                                                                                                                                                                                                                                               , Reporting from San Francisco                                                                                                                                                                                                                                                                                                                                                                                         , The American branch of Binance, the giant cryptocurrency exchange, said late on Thursday that it would no longer allow customers to trade on its platform using U.S. dollars, after its banking partners cut the firm off in response to a crackdown by federal regulators.                                                                                                                                          , The move is a major blow to Binance.US, the American arm of the world’s largest crypto exchange. One of the main functions of an exchange is allowing users to convert their traditional money into digital currencies like Bitcoin or Ether. Binance will no longer be able to offer that service in the United States.                                                                                             , In a message to customers, Binance.US said it was “taking necessary actions as we transition to a crypto-only exchange.” In recent days, the company said, its banking partners have signaled that they will no longer facilitate the movement of dollars on and off Binance.US’s platform.                                                                                                                          , The announcement comes after the Securities and Exchange Commission sued Binance on Monday, accusing the firm and its chief executive, Changpeng Zhao, of mishandling customer funds and lying to regulators. In a separate filing, the S.E.C. asked a federal judge in Washington to freeze assets related to U.S.-based customers of Binance, citing “the defendants’ years of violative conduct.”                 , Representatives for Binance did not immediately respond to a request for comment.                                                                                                                                                                                                                                                                                                                                    , The crypto industry has been under intense pressure from federal regulators since November, when the collapse of the FTX exchange set off an industrywide crisis. The day after it sued Binance, the S.E.C. filed a separate case against Coinbase, the largest American crypto exchange. Some crypto companies have vowed to fight the crackdown, while others are making plans to leave the United States entirely., In its message to customers on Thursday, Binance.US said it was facing “extremely aggressive and intimidating tactics” from the S.E.C. The company said it was suspending deposits of U.S. dollars and urged users to withdraw any dollars they have been storing on the exchange by June 13.                                                                                                                        , At the same time, the company tried to assure its customers that their savings were backed up by money it holds in reserve.                                                                                                                                                                                                                                                                                          , “To be clear, we maintain 1:1 reserves for all customer assets,” the message said. “Customer funds are always safe, secure, and available.”                                                                                                                                                                                                                                                                          , David Yaffe-Bellany covers cryptocurrencies and financial technology. He graduated from Yale University and previously reported in Texas, Ohio, Connecticut and Washington, D.C.  @yaffebellany                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://foxbusiness.com/markets/amazon-target-modify-deliveries-areas-poor-air-quality </td>
   <td style="text-align:left;"> 2023-06-09 13:34:26 </td>
   <td style="text-align:left;"> Amazon, Target modify deliveries in areas with poor air quality </td>
   <td style="text-align:left;"> FOX Weather’s Katie Byrne provides an update on air quality conditions in the Northeast stemming from Canadian wildfires on ‘The Big Money Show.’                                                                                 , The wildfires burning in Canada creating dangerous smoke conditions in the eastern part of the United States, have disrupted life in many ways.                                                                                   , You can add to the list package deliveries.                                                                                                                                                                                       , Amazon.com said on Thursday that it was cutting delivery routes short for drivers in places affected by poor air quality.                                                                                                         , Target has said its contactless order pickup service may not operate in the most affected areas.                                                                                                                                  , AIR QUALITY IMPROVES FOR CITIES ALONG I-95 CORRIDOR                                                                                                                                                                               , Amazon packages are pictured on a delivery cart in the Manhattan borough of New York City. ( REUTERS/Carlo Allegri / Reuters Photos)                                                                                              , Canada is suffering the worst start to fire season that the country has ever seen, with hundreds of blazes across much of Canada.                                                                                                 , The smoke from the fires have made its way to the United States in the form of a thick yellow haze.                                                                                                                               , On Wednesday, New York City's air quality was considered the worst in the world.                                                                                                                                                  , FLIGHTS DELAYED AT MAJOR US AIRPORTS AS WILDFIRE SMOKE SPREADS ACROSS STATES                                                                                                                                                      , People ride bicycles on 6th Avenue as haze and smoke caused by wildfires in Canada blanket New York City, June 7, 2023. (REUTERS/Andrew Kelly / Reuters Photos)                                                                   , The company was cutting routes short where air quality is hazardous, and providing N-95 masks to delivery workers, according to an Amazon spokesman. Drivers were also encouraged to return to delivery stations if they felt ill., Target said its "Drive Up" order pick-up service may be turned off at locations with poor air quality. Customers can check their Target mobile application to confirm if the services were available at their local store.        , US CARRIER ALLOWS REBOOKING WITHOUT FEES AS WILDFIRE SMOKE SPREADS                                                                                                                                                                , A Southwest Airlines plane approaches LaGuardia Airport in New York on Wednesday, June 7. (AP/David R. Martin / AP Images)                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                       , Schools across the region canceled outdoor activities and companies told employees to work from home, while health officials in more than a dozen states have urged millions of residents to stay indoors.                        , Reuters contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/finland/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 13:16:23 </td>
   <td style="text-align:left;"> Finish Industrial Output Shrinks 2.4% in April </td>
   <td style="text-align:left;"> Industrial production in Finland dropped by 2.4 percent year-on-year in April 2023, reversing a downwardly revised 4 percent growth in the previous month, amid declines in the manufacturing (-3.8 percent vs 2.8 percent in March) and mining and quarrying (-6.5% vs -7.6%) sectors. At the same time, output slowed sharply for electricity, gas, steam &amp; air conditioning supply (6.6 percent vs 13.9 percent). On a seasonally adjusted monthly basis, industrial production went down by 1.7 percent, after increasing by 2.8 percent in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/estonia/balance-of-trade </td>
   <td style="text-align:left;"> 2023-06-09 13:15:00 </td>
   <td style="text-align:left;"> Estonian Trade Gap Narrows Sharply in April </td>
   <td style="text-align:left;"> The trade deficit in Estonia fell sharply to EUR 227 million in April 2023 from EUR 532 million in the same month of the previous year, amid a slump in imports. Imports plunged by 18% to EUR 1,754 million, mainly dragged down by declines in mineral products (-42%), transport equipment (-76%), and metal &amp; metal products (-32%). Among major partners, Finland accounted for the biggest share at 15%, followed by Germany (11%), and Latvia (10%). Meanwhile, exports shrank by 4% to EUR 1,527 million, led by mineral products (-25%), wood and articles of wood (-18%), and articles of plastics and rubber (-8%). The highest share of exports went to Finland accounting for 15% of the total, followed by Latvia (13%), and Sweden (9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/manufacturing-production-mom </td>
   <td style="text-align:left;"> 2023-06-09 13:06:45 </td>
   <td style="text-align:left;"> Dutch Manufacturing Output Drops 3% in April </td>
   <td style="text-align:left;"> The manufacturing production in the Netherlands shrank 3% month-over-month in April 2023, hitting January’s near two-year low and slipping further from a downwardly revised 1.8% drop in the previous month. Output fell for most industries particularly, food (-2.8% vs 0.6% in March), beverage (-12.2% vs -1.8%), clothing (-7.8% vs -6.2%) and rubber &amp; plastic products (-6.1% vs 1.1%). Production also contracted for building materials (-4% vs -2%), basic metals (-12.1% vs 7.1%), metal products (-1.6% vs -2.8%) and electrical (-3.5% vs -1.5%). On a yearly basis, manufacturing output plunged 12.1%, the largest drop since April 2009. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/09/china-cant-rely-on-southeast-asian-exports-to-offset-a-us-slowdown.html </td>
   <td style="text-align:left;"> 2023-06-09 12:40:33 </td>
   <td style="text-align:left;"> China can't rely on Southeast Asian exports to offset a U.S. slowdown </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                  , Loans                                                                                                                                                                                                                                         , Banking                                                                                                                                                                                                                                       , Mortgages                                                                                                                                                                                                                                     , Insurance                                                                                                                                                                                                                                     , Credit Monitoring                                                                                                                                                                                                                             , Personal Finance                                                                                                                                                                                                                              , Small Business                                                                                                                                                                                                                                , Taxes                                                                                                                                                                                                                                         , Help for Low Credit Scores                                                                                                                                                                                                                    , Investing                                                                                                                                                                                                                                     , SELECT                                                                                                                                                                                                                                        , All Credit Cards                                                                                                                                                                                                                              , Find the Credit Card for You                                                                                                                                                                                                                  , Best Credit Cards                                                                                                                                                                                                                             , Best Rewards Credit Cards                                                                                                                                                                                                                     , Best Travel Credit Cards                                                                                                                                                                                                                      , Best 0% APR Credit Cards                                                                                                                                                                                                                      , Best Balance Transfer Credit Cards                                                                                                                                                                                                            , Best Cash Back Credit Cards                                                                                                                                                                                                                   , Best Credit Card Welcome Bonuses                                                                                                                                                                                                              , Best Credit Cards to Build Credit                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                        , All Loans                                                                                                                                                                                                                                     , Find the Best Personal Loan for You                                                                                                                                                                                                           , Best Personal Loans                                                                                                                                                                                                                           , Best Debt Consolidation Loans                                                                                                                                                                                                                 , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                      , Best Loans with Fast Funding                                                                                                                                                                                                                  , Best Small Personal Loans                                                                                                                                                                                                                     , Best Large Personal Loans                                                                                                                                                                                                                     , Best Personal Loans to Apply Online                                                                                                                                                                                                           , Best Student Loan Refinance                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                        , All Banking                                                                                                                                                                                                                                   , Find the Savings Account for You                                                                                                                                                                                                              , Best High Yield Savings Accounts                                                                                                                                                                                                              , Best Big Bank Savings Accounts                                                                                                                                                                                                                , Best Big Bank Checking Accounts                                                                                                                                                                                                               , Best No Fee Checking Accounts                                                                                                                                                                                                                 , No Overdraft Fee Checking Accounts                                                                                                                                                                                                            , Best Checking Account Bonuses                                                                                                                                                                                                                 , Best Money Market Accounts                                                                                                                                                                                                                    , Best CDs                                                                                                                                                                                                                                      , Best Credit Unions                                                                                                                                                                                                                            , SELECT                                                                                                                                                                                                                                        , All Mortgages                                                                                                                                                                                                                                 , Best Mortgages                                                                                                                                                                                                                                , Best Mortgages for Small Down Payment                                                                                                                                                                                                         , Best Mortgages for No Down Payment                                                                                                                                                                                                            , Best Mortgages with No Origination Fee                                                                                                                                                                                                        , Best Mortgages for Average Credit Score                                                                                                                                                                                                       , Adjustable Rate Mortgages                                                                                                                                                                                                                     , Affording a Mortgage                                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                        , All Insurance                                                                                                                                                                                                                                 , Best Life Insurance                                                                                                                                                                                                                           , Best Homeowners Insurance                                                                                                                                                                                                                     , Best Renters Insurance                                                                                                                                                                                                                        , Best Car Insurance                                                                                                                                                                                                                            , Travel Insurance                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                        , All Credit Monitoring                                                                                                                                                                                                                         , Best Credit Monitoring Services                                                                                                                                                                                                               , Best Identity Theft Protection                                                                                                                                                                                                                , How to Boost Your Credit Score                                                                                                                                                                                                                , Credit Repair Services                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                        , All Personal Finance                                                                                                                                                                                                                          , Best Budgeting Apps                                                                                                                                                                                                                           , Best Expense Tracker Apps                                                                                                                                                                                                                     , Best Money Transfer Apps                                                                                                                                                                                                                      , Best Resale Apps and Sites                                                                                                                                                                                                                    , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                 , Best Debt Relief                                                                                                                                                                                                                              , SELECT                                                                                                                                                                                                                                        , All Small Business                                                                                                                                                                                                                            , Best Small Business Savings Accounts                                                                                                                                                                                                          , Best Small Business Checking Accounts                                                                                                                                                                                                         , Best Credit Cards for Small Business                                                                                                                                                                                                          , Best Small Business Loans                                                                                                                                                                                                                     , Best Tax Software for Small Business                                                                                                                                                                                                          , SELECT                                                                                                                                                                                                                                        , All Taxes                                                                                                                                                                                                                                     , Best Tax Software                                                                                                                                                                                                                             , Best Tax Software for Small Businesses                                                                                                                                                                                                        , Tax Refunds                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                        , All Help for Low Credit Scores                                                                                                                                                                                                                , Best Credit Cards for Bad Credit                                                                                                                                                                                                              , Best Personal Loans for Bad Credit                                                                                                                                                                                                            , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                  , Personal Loans if You Don't Have Credit                                                                                                                                                                                                       , Best Credit Cards for Building Credit                                                                                                                                                                                                         , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                  , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                  , Best Mortgages for Bad Credit                                                                                                                                                                                                                 , Best Hardship Loans                                                                                                                                                                                                                           , How to Boost Your Credit Score                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                        , All Investing                                                                                                                                                                                                                                 , Best IRA Accounts                                                                                                                                                                                                                             , Best Roth IRA Accounts                                                                                                                                                                                                                        , Best Investing Apps                                                                                                                                                                                                                           , Best Free Stock Trading Platforms                                                                                                                                                                                                             , Best Robo-Advisors                                                                                                                                                                                                                            , Index Funds                                                                                                                                                                                                                                   , Mutual Funds                                                                                                                                                                                                                                  , ETFs                                                                                                                                                                                                                                          , Bonds                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                               , BEIJING — China can't easily rely on its neighbors as export markets in a global slowdown, the latest trade data show.                                                                                                                        , Exports to the Association of Southeast Asia Nations have been growing. The 10-member bloc surpassed the European Union during the pandemic to become China's largest trading partner on a regional basis.                                    , Data showed that exports to Southeast Asia fell by 16% in May compared to a year ago, dragging down China's overall exports.                                                                                                                  , Exports to the U.S. — China's largest trading partner on a single-country basis — fell by 18% from a year ago in U.S. dollar terms in May. That's according to official figures accessed through Wind Information.                            , At $42.48 billion, the U.S. exports in May were more than the $41.49 billion China exported to Southeast Asia that month, according to customs data.                                                                                          , Southeast Asia can't fully offset the loss from the U.S. market, said Bruce Pang, chief economist and head of research for Greater China at JLL.                                                                                              , ASEAN is made up of 10 countries: Brunei, Cambodia, Indonesia, Laos, Malaysia, Myanmar, the Philippines, Singapore, Thailand and Vietnam.                                                                                                     , The U.S. is one single market versus a grouping of 10 countries, Pang pointed out, adding that companies can also sell at higher profit margins in the U.S. market.                                                                           , Trade has been a key driver of China's growth, especially during the pandemic.                                                                                                                                                                , Exports still account for about 18% of the economy, although that's well below the roughly 30% share it once had, Tao Wang, head of Asia economics and chief China economist at UBS Investment Bank, told reporters Monday.                   , Slowing global growth, especially in the U.S. and Southeast Asia, doesn't bode well for the outlook on Chinese exports.                                                                                                                       , "We expect China's exports will remain subdued, as we anticipate the US economy to enter recession in H2 while global destocking pressures continue to rise," Lloyd Chan, senior economist at Oxford Economics, said in a note Wednesday.     , Businesses in the U.S. have also been working through high inventory that didn't get sold in the second half of last year due to high inflation.                                                                                              , U.S. GDP is expected to slow from 2.1% in 2022 to 1.6% this year, according to the International Monetary Fund.                                                                                                                               , ASEAN's GDP is set to slow to 4.6% growth this year, down from last year's 5.7% pace, the IMF said in April, when it trimmed its forecast for the region's GDP growth by 0.1 percentage points.                                               , "The sizeable slump in May reaffirms our suspicion that China's monthly export data to some ASEAN economies – particularly Vietnam, Singapore, Malaysia and Thailand — may be somewhat distorted," Nomura economists said in a note Wednesday., "Given the apparent plunge, exports to ASEAN has turned from a major driver to a drag, making a negative contribution of -2.4pp to headline growth in May."                                                                                   , The U.S. and ASEAN each accounted for 15% of China's total exports in May, according to CNBC calculations of Wind Information data.                                                                                                           , On a year-to-date basis, the bloc has a slightly higher share, at 16% of China's exports versus the United States' 14% share, the data showed.                                                                                                , "Looking forward, [China's] exports are likely to shrink further on a high base, the deepening global manufacturing downturn and intensifying trade sanctions from the West," the Nomura analysts said.                                       , The export declines come as U.S.-China relations remain tense, and Beijing has sought to bolster trade with the developing countries in Asia Pacific.                                                                                         , "It's 20-25% more expensive to sell lots of stuff to the US, particularly intermediate goods like machine parts," Jack Zhang, assistant professor of political science at the University of Kansas, told CNBC in an email.                    , "Boosting trade with developing countries has gained urgency with the closing of the US market and the EU-China investment deal falling apart after the Ukraine war," he said.                                                                , This fund puts a spin on emerging markets investing with bets from Nvidia to Chinese spirits                                                                                                                                                  , Morgan Stanley names 2 chip stocks with 'significant upside' as China bans Micron                                                                                                                                                             , Tesla vs. BYD: Here's why one fund manager prefers the Buffett-backed automaker                                                                                                                                                               , The 10-nation bloc — along with Japan, South Korea, Australia and New Zealand — signed a free trade agreement with China in 2020. The Regional Comprehensive Economic Partnership or RCEP is the largest such deal in the world.              , Beijing has said it would also like to join another trade bloc — the Comprehensive and Progressive Agreement for Trans-Pacific Partnership. The U.S. is not part of the CPTPP, while the U.K. announced a deal to join it in March.           , RCEP has boosted China's trade with ASEAN, as has the shift of some labor-intensive manufacturing to the region, Zhang said.                                                                                                                  , Meanwhile, he noted that "China has been ramping up negotiations for China-ASEAN FTA (CAFTA 3.0), it's exploring FTAs with Mercusor in LatAm and the Gulf Cooperation Council (GCC)."                                                         , The Mercusor trade bloc includes Argentina, Brazil, Paraguay, and Uruguay.                                                                                                                                                                    , — CNBC's Clement Tan contributed to this report.                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                              , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/industrial-production </td>
   <td style="text-align:left;"> 2023-06-09 12:31:00 </td>
   <td style="text-align:left;"> Malaysia Industrial Output Unexpectedly Drops </td>
   <td style="text-align:left;"> Industrial production in Malaysia unexpectedly fell by 3.3% year-on-year in April 2023, missing market forecasts of 2% gain, and shifting from a 3.2% growth in the previous month. It was also the first month of decline in industrial output since August 2021, dragged down by all of the sub-sectors, namely; manufacturing (-3% vs 4.1% in March), mining &amp; quarrying (-4.9% vs 0.8%), and electricity (-2% vs -0.3%). On a seasonally adjusted monthly basis, industrial output tumbled 5.6% in April, shifting from a downwardly revised 0.01% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://foxbusiness.com/markets/binance-us-suspends-usd-deposits-after-regulators-crackdown </td>
   <td style="text-align:left;"> 2023-06-09 12:28:17 </td>
   <td style="text-align:left;"> Binance.US suspends USD deposits after regulators crackdown </td>
   <td style="text-align:left;"> O'Leary Ventures Chairman Kevin O'Leary discusses his plans to build an oil refinery and reacts to the SEC's lawsuits against crypto exchanges Binance and Coinbase on 'The Claman Countdown.'                                    , The U.S. arm of the world's largest crypto exchange is suspending U.S. dollar deposits.                                                                                                                                           , Binance.US says its banking partners are preparing to pause fiat dollar withdrawal channels as early as June 13,                                                                                                                  , The announcement comes just days after U.S. regulators sued Binance and its CEO Changpeng Zhao.                                                                                                                                   , The firm made the announcement in a tweet on Thursday night.                                                                                                                                                                      , CRYPTO EXCHANGE BINANCE, CEO HIT WITH CHARGES IN SEC LAWSUIT                                                                                                                                                                      , Binance logo displayed on a phone screen and representation of cryptocurrencies are seen in this illustration. ((Photo by Jakub Porzycki/NurPhoto via Getty Images) / Getty Images)                                               , The company says it is taking "proactive steps" in its transition to a crypto-only exchange for the time being.                                                                                                                   , Trading, staking, deposits and withdrawals in crypto would remain fully operational, the exchange said in a notice to its customers.                                                                                              , In a 136-page complaint filed in federal court, the SEC accused Binance and the company’s CEO of operating a "web of deception."                                                                                                  , BINANCE, COINBASE CEOS' FORTUNES TAKE HIT AFTER SEC CRYPTO LAWSUITS                                                                                                                                                               , Changpeng Zhao, founder and chief executive officer of Binance. (REUTERS/Benoit Tessier/File Photo / Reuters Photos)                                                                                                              , With its 13 total charges, the SEC complaint accused Binance Holdings, Zhao, BAM Trading and BAM Management US Holdings of committing breaches of the Securities Act and the Exchange Act, two U.S. laws pertaining to securities., A day later, Coinbase, the largest U.S. cryptocurrency platform, was also sued.                                                                                                                                                   , .On Thursday, U.S. financial regulators said they supported a freeze on Binance's assets, according to a U.S. SEC filing.                                                                                                         , A representation of the cryptocurrency is seen in front of Coinbase logo. (Reuters/Dado Ruvic/Illustration/File Photo / Reuters Photos)                                                                                           , CLICK HERE FOR FOX BUSINESS' REAL-TIME CRYPTOCURRENCY PRICING DATA                                                                                                                                                                , Binance.US said in its tweet that the SEC's take on cryptocurrency is "extremely aggressive and intimidating," adding that it has created challenges between the exchange and its banking partners.                               , FOX Business' Joe Toppe and Reuters contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2023/06/08/banks-to-cut-off-binance-access-to-us-banking-system-exchange-says.html </td>
   <td style="text-align:left;"> 2023-06-09 12:14:38 </td>
   <td style="text-align:left;"> Banks are cutting off Binance's access to U.S. banking system, exchange says </td>
   <td style="text-align:left;"> Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                     , Loans                                                                                                                                                                                                                                                                                                                                                                                                                            , Banking                                                                                                                                                                                                                                                                                                                                                                                                                          , Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                        , Insurance                                                                                                                                                                                                                                                                                                                                                                                                                        , Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                                , Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                                 , Small Business                                                                                                                                                                                                                                                                                                                                                                                                                   , Taxes                                                                                                                                                                                                                                                                                                                                                                                                                            , Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                       , Investing                                                                                                                                                                                                                                                                                                                                                                                                                        , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                 , Find the Credit Card for You                                                                                                                                                                                                                                                                                                                                                                                                     , Best Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                                , Best Rewards Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                        , Best Travel Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                         , Best 0% APR Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                         , Best Balance Transfer Credit Cards                                                                                                                                                                                                                                                                                                                                                                                               , Best Cash Back Credit Cards                                                                                                                                                                                                                                                                                                                                                                                                      , Best Credit Card Welcome Bonuses                                                                                                                                                                                                                                                                                                                                                                                                 , Best Credit Cards to Build Credit                                                                                                                                                                                                                                                                                                                                                                                                , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Loans                                                                                                                                                                                                                                                                                                                                                                                                                        , Find the Best Personal Loan for You                                                                                                                                                                                                                                                                                                                                                                                              , Best Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                              , Best Debt Consolidation Loans                                                                                                                                                                                                                                                                                                                                                                                                    , Best Loans to Refinance Credit Card Debt                                                                                                                                                                                                                                                                                                                                                                                         , Best Loans with Fast Funding                                                                                                                                                                                                                                                                                                                                                                                                     , Best Small Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Best Large Personal Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Best Personal Loans to Apply Online                                                                                                                                                                                                                                                                                                                                                                                              , Best Student Loan Refinance                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Banking                                                                                                                                                                                                                                                                                                                                                                                                                      , Find the Savings Account for You                                                                                                                                                                                                                                                                                                                                                                                                 , Best High Yield Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                 , Best Big Bank Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                                   , Best Big Bank Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                  , Best No Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                                    , No Overdraft Fee Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                               , Best Checking Account Bonuses                                                                                                                                                                                                                                                                                                                                                                                                    , Best Money Market Accounts                                                                                                                                                                                                                                                                                                                                                                                                       , Best CDs                                                                                                                                                                                                                                                                                                                                                                                                                         , Best Credit Unions                                                                                                                                                                                                                                                                                                                                                                                                               , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Mortgages                                                                                                                                                                                                                                                                                                                                                                                                                   , Best Mortgages for Small Down Payment                                                                                                                                                                                                                                                                                                                                                                                            , Best Mortgages for No Down Payment                                                                                                                                                                                                                                                                                                                                                                                               , Best Mortgages with No Origination Fee                                                                                                                                                                                                                                                                                                                                                                                           , Best Mortgages for Average Credit Score                                                                                                                                                                                                                                                                                                                                                                                          , Adjustable Rate Mortgages                                                                                                                                                                                                                                                                                                                                                                                                        , Affording a Mortgage                                                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Insurance                                                                                                                                                                                                                                                                                                                                                                                                                    , Best Life Insurance                                                                                                                                                                                                                                                                                                                                                                                                              , Best Homeowners Insurance                                                                                                                                                                                                                                                                                                                                                                                                        , Best Renters Insurance                                                                                                                                                                                                                                                                                                                                                                                                           , Best Car Insurance                                                                                                                                                                                                                                                                                                                                                                                                               , Travel Insurance                                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Credit Monitoring                                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Monitoring Services                                                                                                                                                                                                                                                                                                                                                                                                  , Best Identity Theft Protection                                                                                                                                                                                                                                                                                                                                                                                                   , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                   , Credit Repair Services                                                                                                                                                                                                                                                                                                                                                                                                           , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Personal Finance                                                                                                                                                                                                                                                                                                                                                                                                             , Best Budgeting Apps                                                                                                                                                                                                                                                                                                                                                                                                              , Best Expense Tracker Apps                                                                                                                                                                                                                                                                                                                                                                                                        , Best Money Transfer Apps                                                                                                                                                                                                                                                                                                                                                                                                         , Best Resale Apps and Sites                                                                                                                                                                                                                                                                                                                                                                                                       , Buy Now Pay Later (BNPL) Apps                                                                                                                                                                                                                                                                                                                                                                                                    , Best Debt Relief                                                                                                                                                                                                                                                                                                                                                                                                                 , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Small Business                                                                                                                                                                                                                                                                                                                                                                                                               , Best Small Business Savings Accounts                                                                                                                                                                                                                                                                                                                                                                                             , Best Small Business Checking Accounts                                                                                                                                                                                                                                                                                                                                                                                            , Best Credit Cards for Small Business                                                                                                                                                                                                                                                                                                                                                                                             , Best Small Business Loans                                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software for Small Business                                                                                                                                                                                                                                                                                                                                                                                             , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Taxes                                                                                                                                                                                                                                                                                                                                                                                                                        , Best Tax Software                                                                                                                                                                                                                                                                                                                                                                                                                , Best Tax Software for Small Businesses                                                                                                                                                                                                                                                                                                                                                                                           , Tax Refunds                                                                                                                                                                                                                                                                                                                                                                                                                      , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Help for Low Credit Scores                                                                                                                                                                                                                                                                                                                                                                                                   , Best Credit Cards for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                 , Best Personal Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                               , Best Debt Consolidation Loans for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans if You Don't Have Credit                                                                                                                                                                                                                                                                                                                                                                                          , Best Credit Cards for Building Credit                                                                                                                                                                                                                                                                                                                                                                                            , Personal Loans for 580 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                     , Personal Loans for 670 Credit Score or Lower                                                                                                                                                                                                                                                                                                                                                                                     , Best Mortgages for Bad Credit                                                                                                                                                                                                                                                                                                                                                                                                    , Best Hardship Loans                                                                                                                                                                                                                                                                                                                                                                                                              , How to Boost Your Credit Score                                                                                                                                                                                                                                                                                                                                                                                                   , SELECT                                                                                                                                                                                                                                                                                                                                                                                                                           , All Investing                                                                                                                                                                                                                                                                                                                                                                                                                    , Best IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                                , Best Roth IRA Accounts                                                                                                                                                                                                                                                                                                                                                                                                           , Best Investing Apps                                                                                                                                                                                                                                                                                                                                                                                                              , Best Free Stock Trading Platforms                                                                                                                                                                                                                                                                                                                                                                                                , Best Robo-Advisors                                                                                                                                                                                                                                                                                                                                                                                                               , Index Funds                                                                                                                                                                                                                                                                                                                                                                                                                      , Mutual Funds                                                                                                                                                                                                                                                                                                                                                                                                                     , ETFs                                                                                                                                                                                                                                                                                                                                                                                                                             , Bonds                                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                  , Binance.US customers will no longer be able to use U.S. dollars to buy crypto on the platform as early as June 13, hobbling the exchange's ability to do business in the United States, after both payment and banking partners "signaled their intent to pause USD fiat channels," the exchange said.                                                                                                                           , Binance announced the change late Thursday night on Twitter, and blamed the Securities and Exchange Commission's "unjustified civil claims against our business." The exchange said it had preemptively disabled customers' ability to buy and deposit U.S. dollars.                                                                                                                                                             , Binance's banking transactions are the center of immense scrutiny by the SEC, which filed a civil complaint against the exchange and its founder, Changpeng Zhao, alleging both violated U.S. securities laws.                                                                                                                                                                                                                   , Zhao's influence over and ownership of the U.S. and international arms of Binance — an international network of offshore holding companies the SEC alleges have moved billions of dollars of assets between themselves — prompted the SEC to file an emergency motion for a temporary restraining order. That restraining order would have frozen U.S. dollars from the exchange anyway.                                         , Customers won't lose their money — those who haven't withdrawn their money by the shutdown date could still theoretically convert it to a stablecoin such as tether, then withdraw that and convert it back to dollars elsewhere. But it suggests that Binance's banking partners have decided the exchange is too risky a client to keep on, and that the revelations from the SEC case have grown too significant to ignore.   , The exchange's disclosed U.S. banking partners, which have included Axos Bank, Cross River Bank, and the failed Silvergate, Signature, and Silicon Valley Banks, processed billions of dollars in transactions for the U.S. exchange, according to documents Binance provided to the SEC. Multiple banking partners had already stopped serving Binance, and it wasn't immediately clear which banking partners Binance retained., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                 , © 2023 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malaysia/unemployment-rate </td>
   <td style="text-align:left;"> 2023-06-09 12:14:00 </td>
   <td style="text-align:left;"> Malaysia Jobless Rate Down to 3.5% in April </td>
   <td style="text-align:left;"> The unemployment rate in Malaysia fell to 3.5 percent in April 2023 from 3.9 percent in the corresponding month of the previous year, and pointing to its lowest level since February 2020. The number of unemployed declined by 9.6 percent from a year earlier to 586.9 thousand, while employment rose by 2.5 percent to 16.25 million. Meantime, the labor force participation rate edged up to 70 percent from 69.4 percent in the same month a year ago. In March, the jobless rate stood at 3.5 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2023-06-09 12:07:00 </td>
   <td style="text-align:left;"> South Korean Won Stays Weak </td>
   <td style="text-align:left;"> South Korean won was trading around 1,295 against USD on Friday, falling below the psychological level of 1,300 while heading for the fourth straight fall weekly, as the government recently flagged annual economic growth of below 1.6% this year, much lower than the 3.1% in 2022. The export-driven country logged a 14th successive trade deficit in May, the longest such sequence since 1997, as shipments tumbled on lower global demand and sluggish sales of semiconductors, while imports remained underpinned by higher food and energy commodities costs. On fresh data, South Korea's current account swung to a deficit of USD 790 million in April 2023 from a gain of USD 130 million in the same month of the prior year, marking the third shortfall so far this year.  The weakness in local currency occurred even as the US dollar softened, amid expectations that the Federal Reserve could pause its tightening campaign next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2023-06-09 12:07:00 </td>
   <td style="text-align:left;"> NZD Set to End Week Slightly Higher </td>
   <td style="text-align:left;"> The Kiwi dollar was changing hand around $0.6088 on Friday, staying not far from its highest level in over two weeks hit in the prior session, as traders digested decisions from several central banks to hike interest rates this week. Both the Reserve Bank of Australia and the Bank of Canada surprised markets with a 25bps interest rate hike, respectively, after pausing in the prior meeting. Market participants also anticipated the release of New Zealand's Q1 GDP growth next week, with local media saying that the figures are probably a bit flat after shrinking by 0.6% in the prior quarter amid efforts to rebuild activity from severe weather events earlier this year. For the week, the NZD is heading for a 0.3% rise, which would be the second consecutive increase, as the US dollar softened further, with investors expecting the Fed to pause its tightening path next week following a slowdown in the service sector. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2023-06-09 11:16:46 </td>
   <td style="text-align:left;"> Chinese Yuan Slips on Soft Inflation Data </td>
   <td style="text-align:left;"> The offshore yuan fell to around 7.13 per dollar, sliding back toward its lowest levels in six months as softer-than-expected Chinese inflation data pointed to underlying weakness in the country’s economy. China’s consumer price index rose 0.2% year-on-year in May, lower than the 0.3% forecast, while producer deflation continued last month. Latest data also showed that Chinese exports fell more than expected in May, pushing the country’s trade surplus to a three-month low. These figures reinforced speculations that the People’s Bank of China could lower interest rates again to boost the world’s second-largest economy. A lack of direct intervention by the central bank also weighed on the currency, even though some major state-owned lenders sold dollars in the spot market to keep the yuan from further losses. Furthermore, Chinese authorities reportedly asked key state-owned banks to lower dollar deposit interest rates to further bolster the local currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/indonesia/foreign-exchange-reserves </td>
   <td style="text-align:left;"> 2023-06-09 11:10:27 </td>
   <td style="text-align:left;"> Indonesia Forex Reserves Fall to 5-Month Low </td>
   <td style="text-align:left;"> Foreign exchange reserves in Indonesia dropped to a five-month low of USD 139.3 billion in May 2023 from 144.2 billion in the previous month. The decline was linked to payment of the government's external debt and in anticipation of demand for foreign currency liquidity in the banking industry as economic activity continued to accelerate. The central bank noted that the official reserve assets were equivalent to 6.0 months of imports and servicing the government's external debt and remained adequate, supported by stability in both macroeconomic and financial sectors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2023-06-09 11:09:38 </td>
   <td style="text-align:left;"> Gold Set to End Week Higher </td>
   <td style="text-align:left;"> Gold steadied above $1,960 an ounce on Friday and was on track to end the week higher, underpinned by a softer dollar as a surge in US weekly jobless claims reinforced expectations that the Federal Reserve will pause its interest rate hikes next week. Markets now anticipate the Fed to hold rates steady at next week’s policy meeting, before resuming the tightening cycle in July. The European Central Bank and the Bank of Japan are also set to decide on monetary policy next week. Meanwhile, investors remain cautious as the International Monetary Fund urged major central banks to “stay the course” on monetary policy and watch inflation closely. The Reserve Bank of Australia and the Bank of Canada both unexpectedly raised interest rates this week, raising the odds that other advanced economies could follow suit. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2023-06-09 22:04:01 UTC +8

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
   <td style="text-align:left;"> 2023-06-09 22:03:38 </td>
   <td style="text-align:left;"> $SPY holy moly poly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:37 </td>
   <td style="text-align:left;"> $SPY let it run faster please very fast up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:35 </td>
   <td style="text-align:left;"> $SPY some dumbass bear posted this , saying it would happen today 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $TSLA $X i usually dont eat cats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:28 </td>
   <td style="text-align:left;"> $SPY u got to pump it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:25 </td>
   <td style="text-align:left;"> $SPY And more up..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:18 </td>
   <td style="text-align:left;"> $SPY We now play in the 430 to 440 range for the next 6 weeks 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:17 </td>
   <td style="text-align:left;"> $SPY this reminds me exactly of the 21 run up.. MMs wiped bears out and then the market turned down. That’s the MO.. run run run when the market should not be running… and then sell sell sell when the bears are wiped. Over extended isn’t the word here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:13 </td>
   <td style="text-align:left;"> $SPY 
Crazy Bros 
Just Crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:07 </td>
   <td style="text-align:left;"> $SPY 1% up on no news is the new normal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:06 </td>
   <td style="text-align:left;"> $SPY $SCHD $VOO $QQQ 
Imagine betting against a market that has an average yearly return rate of +9% since 1902. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:06 </td>
   <td style="text-align:left;"> Don’t fight the fed and fomo friday. Fed printing cash daily to pay down interest. Too easy $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:02 </td>
   <td style="text-align:left;"> $SPY yes, b/c its simple: central banks alone cannot tame inflation.  its amazing how convenient this is overlooked.  why?  because serious heavy-lifting vis political means is required to engage the other tools to effectively fight inflation and the power that be haven’t the stomach to advocate for it.  so… we make believe rate hikes alone can get us to 2% inflation rate and those that started rebelling in ~Oct ended up right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:03:00 </td>
   <td style="text-align:left;"> $SPY The high back in August was 431.73. Look for a short-term pullback and buy the dip. #NewBullMarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:57 </td>
   <td style="text-align:left;"> $SPY NATO condemns Russia&amp;#39;s withdrawal from conventional armed forces treaty | $QQQ $TSLA $NVDA https://cyprus-mail.com/2023/06/09/nato-condemns-russias-withdrawal-from-conventional-armed-forces-treaty/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:57 </td>
   <td style="text-align:left;"> $SPY ohhh bears u guys are all bark ZERO bite can’t even cash my hedges :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:56 </td>
   <td style="text-align:left;"> $SPY insane pumpage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:38 </td>
   <td style="text-align:left;"> $SPY geez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:28 </td>
   <td style="text-align:left;"> $SPY rsi already smokin on the 5 min. Needs to cool to bust that resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:27 </td>
   <td style="text-align:left;"> $SPY $435? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:22 </td>
   <td style="text-align:left;"> $TMC congrats my dears .. nailed …  please stay rich and get richer, its a generational bull after all $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:02:09 </td>
   <td style="text-align:left;"> $SPY No more pull backs allowed in markets, only quick drops to reset RSI.  I mean they make it so easy these days, buy calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:58 </td>
   <td style="text-align:left;"> $SPY Too funny...so many stocks are red....how are shorts losing outside the few tech names?....LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:55 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Markets rally on Trump indictment&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:48 </td>
   <td style="text-align:left;"> $SPY what your problem with a little pullback??? damn. Ruined this entire market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:35 </td>
   <td style="text-align:left;"> $SPY any dip below $431 it bounces back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:32 </td>
   <td style="text-align:left;"> $SPY Since corporate media always makes up a narrative around price action, I&amp;#39;ll do the same, &amp;quot;Markets rally on Trump indictment&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:30 </td>
   <td style="text-align:left;"> $SPY  $QQQ    when you give your broker $1000 and he give you back $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:29 </td>
   <td style="text-align:left;"> @nsavc $SPY $ONE maybe some of the big boys at SPY know how to make this happen.  Would love to see the page ticker updated, it&amp;#39;s been almost a year since the ticker changed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:28 </td>
   <td style="text-align:left;"> $SPY insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:27 </td>
   <td style="text-align:left;"> $SPY I might swing into puts here. These bulls smoking crack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:24 </td>
   <td style="text-align:left;"> $SPY you can tell it is a blow off too extreme greed rotation before it really pulls back because all the junk companies are being pumped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:15 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P 500 exits longest bear market since 1948. What stock-market history says about what happens next.

https://www.marketwatch.com/story/s-p-500-exits-longest-bear-market-since-1948-what-stock-market-history-says-about-what-happens-next-a336a139?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:10 </td>
   <td style="text-align:left;"> $SPY Took a put here 0DTE for 428 retest. Stop at 432~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:01:07 </td>
   <td style="text-align:left;"> $SPY That move alone was a small fortune. Big boys like their work done early on Fridays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:56 </td>
   <td style="text-align:left;"> $SPY We at https://elliottwave-forecast.com/ have created a system up to 2023. We label the charts and forecast with High-Frequency Trading in mind. We use distribution and correlation to pick the higher probability path. #elliottwave #trading https://elliottwave-forecast.com/trading/high-frequency-trading-elliott-wave-theory/ $SPX $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:50 </td>
   <td style="text-align:left;"> $SPY Well I’m betting on $435 today 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:45 </td>
   <td style="text-align:left;"> $SPY fools gold fellas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:43 </td>
   <td style="text-align:left;"> $SPY  alert
added a few lotto put plays for intraday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:43 </td>
   <td style="text-align:left;"> $SPY yes it’s still safe to buy calls at 431 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:39 </td>
   <td style="text-align:left;"> $SPY now just pray Russia not nuke Eastern Europe and China not create another Cuban Missile Crisis $QQQ $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:33 </td>
   <td style="text-align:left;"> $SPY pullbacks are illegal. Calls only ladies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:32 </td>
   <td style="text-align:left;"> $SPY we are currently in a buying algo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:29 </td>
   <td style="text-align:left;"> @Trade4Life1 @JLubeTT @Doorstop @FTV @machumble @fraudguarantee @ShortyMcFly Well I&amp;#39;ll be goddamned! You guys actually pulled it off! 😑🤣👏👏👏

With all the craziness we&amp;#39;ve been going through, would you believe me if I told you $SPY is actually UP 5% over the last year!!! 🙃

***okay - shows over - you did it! Wooohoo...now we can fall*** Haha!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:20 </td>
   <td style="text-align:left;"> $SPY continuation here short squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:12 </td>
   <td style="text-align:left;"> $SPY 😅😅😅💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:06 </td>
   <td style="text-align:left;"> $SPY The Biden Market just hit a new high on the day Trump gets indicted on the thing he claimed Hillary did. 
 
You can&amp;#39;t make this stuff up! :o) 
 
$dwac $aapl $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:04 </td>
   <td style="text-align:left;"> $SPY the euphoria is about to come to a screeching halt, trade accordingly 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 22:00:03 </td>
   <td style="text-align:left;"> $SPY morning move that’s all you get folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:57 </td>
   <td style="text-align:left;"> $SPY &amp;gt;&amp;gt; call buyers gonna get squeezed here &amp;gt;&amp;gt;&amp;gt;&amp;gt;&amp;gt;&amp;gt;&amp;gt;&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:57 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ who buys CALLS on a stock up 11 days in a row into a huge gap up LMFAO  onky pajama can pull that off yes intook my profits alrwady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:56 </td>
   <td style="text-align:left;"> $SPY theyre doing it again be prepared for 460 at this rate 

Millions in 430p hittin tape they got fucked yesterday and are lubing up for round two </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:52 </td>
   <td style="text-align:left;"> $SPY and now get chopped at resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:49 </td>
   <td style="text-align:left;"> $SPY Fomc is at 2pm on Wednesday, correct? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA All headlines “entered new bull market” yup.. that’s how you know it’s time for some distribution.. get all the chumps buying up all the expensive shares🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:46 </td>
   <td style="text-align:left;"> $SPY don’t fight the printer…

You’ll always lose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:44 </td>
   <td style="text-align:left;"> $SPY will fall. It’s Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:42 </td>
   <td style="text-align:left;"> $NXPL HELL YEAH!!!

A beautiful beast ticker is waking up!!

Has more to give than $ADD 
 Trades with $SPY and $QQQ both are bullish $AI has been going up nicely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Muppets get murdered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:36 </td>
   <td style="text-align:left;"> $SPY 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:36 </td>
   <td style="text-align:left;"> $SPY Possible I won&amp;#39;t get another trade till Fomc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:32 </td>
   <td style="text-align:left;"> $SPY $QQQ OH Kay! 🥹🥹🥹 Closeddddd nasdaq and spy booola calls!! Think it camps now for theta partayyy before next moveeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:30 </td>
   <td style="text-align:left;"> $SPY OK IM GONNA NEED U TO PRINT MY HEDGES NOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:29 </td>
   <td style="text-align:left;"> $SPY and 431 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:25 </td>
   <td style="text-align:left;"> $SPY &amp;gt;&amp;gt; heavy volume to start the day &amp;gt;&amp;gt; 

Big Dogs 🐕 locking 🔒 in some gains 💪??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:23 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:21 </td>
   <td style="text-align:left;"> $SPY zero sellers. Endless buyers. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:59:06 </td>
   <td style="text-align:left;"> $SPY  now it camps all day lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:56 </td>
   <td style="text-align:left;"> $JETS 🛫 takeoff $SPY $AAPL $PLUG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:47 </td>
   <td style="text-align:left;"> @UpandDowns @corp_rat_exterminator $SPY back ratios have never been cheaper. 
 
.5% drop PAYS HUGE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:44 </td>
   <td style="text-align:left;"> EPIC INSTANT V DID YOU LISTEN 
 
WHEN PAJAMA SAYS BTFD V RALY COMING YOU NEED TO PAY ATTENTION 
 
KNEEL 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:43 </td>
   <td style="text-align:left;"> $QQQ $SPY  Lots of people will make money during this markets, but trust me they will all lose it back and some more just like the covid pumps and the dotcom bubble. Just wait and short at a round number. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:39 </td>
   <td style="text-align:left;"> $SPY GOT A LONG WAY TO GO $435 EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:27 </td>
   <td style="text-align:left;"> $LLAP 

Any good news from Terran just fizzles the next trading session. Opportunity cost is increasing as $SPY enters a bull trend.

I&amp;#39;m telling you, the share price won&amp;#39;t sustain a run until Marc Bell and management buy shares in the open market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:25 </td>
   <td style="text-align:left;"> $SPY that was top.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:16 </td>
   <td style="text-align:left;"> $SPY as I said few weeks ago. 430. Look at my previous post. I was called a clown, a moron, an idiot…. Well guess who are the clowns now?

Next step is 460, which should happen in 1-3 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:08 </td>
   <td style="text-align:left;"> $SPY $435 next boys. lets goo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:06 </td>
   <td style="text-align:left;"> $SPY $93 for Kirkland steak but spy hitting new highs. Cool. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:05 </td>
   <td style="text-align:left;"> $SPY Bad day for trading. Dangerous to long. Dangerous to short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:02 </td>
   <td style="text-align:left;"> $SPY will she hold 431!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:58:01 </td>
   <td style="text-align:left;"> $SPY Every stock market in the world is up as much as US, or more. Worldwide equity rally started the same time everywhere. This was a coordinated effort - Not one talking head dares mention it. Throw up any chart of any market, anywhere! They all look like our Nasdaq!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:58 </td>
   <td style="text-align:left;"> $SPY I’ve waited all year saving up this chunk to short this here!😎
Retail is the exit liquidity✔️✔️✔️⤵️🩸🩸
Wait until they start crying about manipulation….. 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:55 </td>
   <td style="text-align:left;"> $SPY that&amp;#39;s not down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Jokes aside, this is the kind of frothy top I was looking for. Would be nice to over extend it as an initial reaction to CPI or June pause. Max pain hopefully leading into a sharp pullback.

We need a distribution of ventilators to other market participants. 😷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:40 </td>
   <td style="text-align:left;"> $SPY the strategy today is simple , buy every fcking dip. No matter how small </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:35 </td>
   <td style="text-align:left;"> $SPY this is either going to correct it self real fast or it’s going to continue to run and everyone’s retirement accounts are going to finally go green from last years bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:29 </td>
   <td style="text-align:left;"> $SPY — it did </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:15 </td>
   <td style="text-align:left;"> $TSLA $NVDA $SPY $QQQ $AMD 

How’s my portfolio for a 24 year old? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:06 </td>
   <td style="text-align:left;"> 🔥Option: $SPY $430Put 0DTE 
🔥Price: $0.47/Contract 
👁️Stop_Loss Plan: -21%  
 
 
#NASDAQ #NASDAQ100 #SPY #QQQ #TQQQ #TSLA #FrogAlgo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:05 </td>
   <td style="text-align:left;"> $SPY bears is this the top 🤡😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:57:03 </td>
   <td style="text-align:left;"> $SPY Save what money you have left on Puts. Close them. This can go 437 with Powell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:56 </td>
   <td style="text-align:left;"> $SPY  😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:51 </td>
   <td style="text-align:left;"> $SPY Bear capitulation incoming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:48 </td>
   <td style="text-align:left;"> $NFLX  on the right track

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:45 </td>
   <td style="text-align:left;"> $SPY Large Option Trade  BOUGHT for $2,008,120
a PUT contract  with Strike @ 430.0 DTX = 98.0 days
https://fintel.io/sof/us/spy?utm_source=stocktwits.com&amp;amp;utm_medium=referral&amp;amp;utm_campaign=sof </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:39 </td>
   <td style="text-align:left;"> $SPY Early this week, we present the Blue Box buying area. The Index reached the area and reacted higher; very nice to know the area where to enter the market. #elliottwave #trading $SPX $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:37 </td>
   <td style="text-align:left;"> $SPY feels like it&amp;#39;s gonna be dips as we move up for the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:34 </td>
   <td style="text-align:left;"> $spy bears about to get moist over this pullback..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:29 </td>
   <td style="text-align:left;"> $AAPL watch it pump again , money is that easy 😂. Can’t scare me.. I won’t sell my calls $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:29 </td>
   <td style="text-align:left;"> $SPY ahh of course - stocks go up forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:26 </td>
   <td style="text-align:left;"> $SPY AHHHHH niiiice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:24 </td>
   <td style="text-align:left;"> $SPY the new normal is green vertical everyday $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:21 </td>
   <td style="text-align:left;"> $SPY bear market is over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:20 </td>
   <td style="text-align:left;"> $SPY Bear meat is yummy. Please keep shorting and eventually the market will drop some. We promise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:11 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P 500 Watching key pivots today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:06 </td>
   <td style="text-align:left;"> $SPY 4300 now support too much $$ brokies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:05 </td>
   <td style="text-align:left;"> $QCOM That my friends is a 16% play so far 💪 Not selling anything.

$SMH $NVDA $AMD $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:56:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Remember this @FTV kid was buying $UVXY hard at 10 !!! DUMB FAKE $$$ !!!  Im not sorry for his followers getting wiped out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:49 </td>
   <td style="text-align:left;"> $SPY Very oversold... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:49 </td>
   <td style="text-align:left;"> $spy $qqq Market keep ripping before the FOMC next week !! 
 
MOC was buy side at pulls — Big boys always knew how the week would be .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:47 </td>
   <td style="text-align:left;"> $SPY $QQQ Have a blessed day! 
Matthew 7:13-14 (King James Version) 
  
Enter ye in at the strait gate: for wide is the gate, and broad is the way, that leadeth to destruction, and many there be which go in thereat: Because strait is the gate, and narrow is the way, which leadeth unto life, and few there be that find it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:46 </td>
   <td style="text-align:left;"> $SPY $NVDA So, every RSI time period is now 70+. Weekly is 86. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:39 </td>
   <td style="text-align:left;"> $SPY 😂😂😂 just buy calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:38 </td>
   <td style="text-align:left;"> $KSS $spy $meta $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:36 </td>
   <td style="text-align:left;"> $SPY very </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:33 </td>
   <td style="text-align:left;"> $SPY fucking retarded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:32 </td>
   <td style="text-align:left;"> $SPY 

Indictment rallies are amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:24 </td>
   <td style="text-align:left;"> $SPY I’m calling it now , we will never see 400 again . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:17 </td>
   <td style="text-align:left;"> $COIN This website sucks. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:17 </td>
   <td style="text-align:left;"> $SPY counting premarket, thats 10 green 5 minute candles in a row </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:15 </td>
   <td style="text-align:left;"> $SPY 432 Come on, let’s Go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:11 </td>
   <td style="text-align:left;"> $SPY &amp;gt;&amp;gt; 10 green 5 minute candles 🕯 in a row going back to premarket 

RSI @ 86.59 on the 5 min. Chart

RSI @ 73.60 on the 15 min. Chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:11 </td>
   <td style="text-align:left;"> $TSLA update on the Tesla loss porn $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:07 </td>
   <td style="text-align:left;"> $SPY $428 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:05 </td>
   <td style="text-align:left;"> $SPY all week 430 was resistance and then all of a sudden in a few minutes after open today if just magically knifes thru like butter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:55:04 </td>
   <td style="text-align:left;"> $SPY 

Take out the June 2022 high and get it over with.   

Rates went up 500 basis points and market is flat for those 12 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:57 </td>
   <td style="text-align:left;"> @MoneyHungriest $SPY no gaps when it trades 24/5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:52 </td>
   <td style="text-align:left;"> $SPY Love the rocket ride!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:49 </td>
   <td style="text-align:left;"> $QQQ $SPY Extreme greed is going to hurt people next week. Fed will be sell the news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:38 </td>
   <td style="text-align:left;"> $SPY Way to go!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:33 </td>
   <td style="text-align:left;"> The bigger picture this morning... 
 
$SPY $QQQ $DIA $VIX 
 
https://share.trendspider.com/chart/m/6682omoet8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:31 </td>
   <td style="text-align:left;"> $SPY So why can&amp;#39;t taxes be raised again if the market has this much cash despite US treasuries auction this week? *shrugs* 
 
Almost seems like this is an indication that we need more taxes to pay down debt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:31 </td>
   <td style="text-align:left;"> $SPY oh whats that? Is that the 52wk??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:26 </td>
   <td style="text-align:left;"> $SPY bulls are such of losers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:25 </td>
   <td style="text-align:left;"> PAJAMA!!! 
 
ON!!!! 
 
FIRE!!!! 
 
absolutely KILLING IT just did a 10 minute trade in 0dte $tsla calls in addition to what i held overnight lmao  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:22 </td>
   <td style="text-align:left;"> $SPY In the future, when economic historians look back they will wonder about the &amp;quot;leaders&amp;quot; who screwed the markets up over COVID. All the bs is getting unwound now and things are going back to where it should have always been... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:17 </td>
   <td style="text-align:left;"> $QQQ $SPY FUCK YOU GARY GENSELR YOU CORRUPT ASS FUGGUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:14 </td>
   <td style="text-align:left;"> $SPY im glad a listened to @torrotrader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:13 </td>
   <td style="text-align:left;"> $SPY too many puts or whatever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:11 </td>
   <td style="text-align:left;"> $SPY market is way way ahead of itself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:10 </td>
   <td style="text-align:left;"> $DJIA $SPY $NASDAQ $SNDL &amp;lt;3 @ $1.40 LIFT OFF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:09 </td>
   <td style="text-align:left;"> $SPY wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:03 </td>
   <td style="text-align:left;"> $SPY loaded $430 puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:02 </td>
   <td style="text-align:left;"> $SPY L.M.F.A.O.  
 
that&amp;#39;s got to hurt.  
 
good ops all around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:01 </td>
   <td style="text-align:left;"> $IDEX ProTip: If you’re using CashApp for trading, you need to re think what youre doing… 

This new generation of retail traders are completely ignorant. It’s actually scary…🤦🏼‍♂️

$TSLA $SPY $RIVN $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:01 </td>
   <td style="text-align:left;"> $SPY 4325? That’s about last high before the huge drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:54:00 </td>
   <td style="text-align:left;"> $SPY this thing gets anywhere 1% and i’m out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:55 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA $NASDAQ $RUT 

Wait for monday and the following friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:55 </td>
   <td style="text-align:left;"> $spy Market seems to like  Trump getting indicated,..  
 
Breaking Video: FBI asking Trump to give the Documents back &amp;amp; his response 
 
https://www.youtube.com/watch?v=RKMNPQ35OUc 
 
$aapl $dwac $rum $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:50 </td>
   <td style="text-align:left;"> $SPY qqq 7 green weekly candles in a row. YEAH OK BUDDY 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:50 </td>
   <td style="text-align:left;"> $SPY A handful of mega techs are sucking money out of the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:45 </td>
   <td style="text-align:left;"> $SPY 500 plus EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:45 </td>
   <td style="text-align:left;"> $SPY 431 odte puts and il scale in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:37 </td>
   <td style="text-align:left;"> $AAP &amp;lt;—————. Way oversold pos here. $spy $qqq $VOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:32 </td>
   <td style="text-align:left;"> @corp_rat_exterminator $SPY they have no idea what is happening. 
 
Its FREE TO HEDGE...we have no risk on the downside due to cheap DTE0 options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:28 </td>
   <td style="text-align:left;"> $AAPL aapl so easy just buy calls and make $ . Didn’t sell my 190 contracts yet.. noobs love to buy 🤣. Just sit and let them push , easy $ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:26 </td>
   <td style="text-align:left;"> $SPY Hey bears, that&amp;#39;s what you get for betting against America you treasonous pigs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:25 </td>
   <td style="text-align:left;"> $SPY I count atleast 4 gaps that need to be filled on the downside. anyone else? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:22 </td>
   <td style="text-align:left;"> $SPY $QQQ 1% every day is the new norm. Wallstreet apparently smarter than us all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:22 </td>
   <td style="text-align:left;"> $SPY Say goodbye to the 420’s. Rear view mirror stuff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:17 </td>
   <td style="text-align:left;"> $SPY  CALLS NOW AT $1.01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:16 </td>
   <td style="text-align:left;"> $SPY lost everything. Divorce time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:16 </td>
   <td style="text-align:left;"> $SPY we may never see below 431 in our life time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:14 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:14 </td>
   <td style="text-align:left;"> $SPY holy smokes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:13 </td>
   <td style="text-align:left;"> $SPY The Index keep trading higher, and should remain supported in a series or 4-5. Here is the latest 1 Hour chart to member&amp;#39;s at https://elliottwave-forecast.com/, showing the idea. #elliottwave #trading $SPX $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:04 </td>
   <td style="text-align:left;"> $SPY let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:04 </td>
   <td style="text-align:left;"> $SPY remember CRAYON LINES are for kids. 
 
That stupid 430 resistance line was bogus...your cycle/wave shit is BOGUS 
 
Traders are just simple failures who read some outdated 1990s TA book and believed it while Wall St built machines to wipe out any moron using TA BOOKS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:03 </td>
   <td style="text-align:left;"> $SPY worried about the downside? buy calls. options are dirt cheap now (VIX &amp;lt; 14)! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:03 </td>
   <td style="text-align:left;"> latexf3c1ab6e5d6eb63a23a23bdf2103b534 prolly in less than half a year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:53:01 </td>
   <td style="text-align:left;"> I&amp;#39;m hearing news reports of another ventilator shortage... 😬😬😬

Due to all the market bears on life support. 

$spy $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:56 </td>
   <td style="text-align:left;"> $SPY calls printed, take the profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:56 </td>
   <td style="text-align:left;"> $SPY $ more .25 hikes already baked in.shorts will get burned again next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:52 </td>
   <td style="text-align:left;"> $SPY 436+ .. the squeeze is ON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:47 </td>
   <td style="text-align:left;"> $SPY Nobody needs y’all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:42 </td>
   <td style="text-align:left;"> $SPY Calls printed beautifully 👌🏼 RSI got a little hot, so I&amp;#39;m calling it a day. Not too bad for only working for 15 minutes. Now, I&amp;#39;m going to take a nap before heading to the gym. 

Bears are idiots! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:33 </td>
   <td style="text-align:left;"> $TSLA $SPY biggest question is where do we see consolidation? $200.00’s last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:29 </td>
   <td style="text-align:left;"> $SPY we are all being conditioned that the market will keep ripping.. until the rug is pulled lol. Everytime baby. Make your money in both directions! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:27 </td>
   <td style="text-align:left;"> $SPY $QQQ Gorgeous breakouts from open so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:26 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤑🤑🤑 called out in our free chat! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:21 </td>
   <td style="text-align:left;"> $SPY .4% with zero pullback...let&amp;#39;s see that retracement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:18 </td>
   <td style="text-align:left;"> $SPY 433 damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:17 </td>
   <td style="text-align:left;"> $SPY OMFG BEARS just stop 🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:10 </td>
   <td style="text-align:left;"> $DISH I would actually prefer to argue with bears all day than see these garbage discord bot spam. @Stocktwits what is going on? Can&amp;#39;t these be stopped? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:04 </td>
   <td style="text-align:left;"> $SPY going to 440 I guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:03 </td>
   <td style="text-align:left;"> $SPY  $QQQ  revised  CNN/CNBC article..  Good news ! After the nasdaq drops 45-50% and stocks struggle to recover for 6 months we should start a new Bull Run ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:02 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA $RUT $NASDAQ 

Staircase up, elevator down.  Every time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:02 </td>
   <td style="text-align:left;"> $AAPL $NFLX $NVDA $SPY $TSLA  
 
This is funny af. I don&amp;#39;t give a shit if its making fun of me. Can only laugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:01 </td>
   <td style="text-align:left;"> $SPY Powell just keeps printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:01 </td>
   <td style="text-align:left;"> $SPY yawn 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:52:01 </td>
   <td style="text-align:left;"> 🔥Out | Trimming: $SPY $430Put 0DTE 
🔥Price: $0.63/Contract 
😎Profit: $0.54 → $0.63 🍏🍏🍏 
 
 
#NASDAQ #NASDAQ100 #SPY #QQQ #TQQQ #TSLA #FrogAlgo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:59 </td>
   <td style="text-align:left;"> $SPY pumping, let’s break 435 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:59 </td>
   <td style="text-align:left;"> $SPY pure fucking greed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:51 </td>
   <td style="text-align:left;"> $SPY rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA clown market disconnected from reality. Stonks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:45 </td>
   <td style="text-align:left;"> $QQQ this is going to dump hard $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:33 </td>
   <td style="text-align:left;"> $SPY starting to look like TLRY remember that pump n dump? Lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:31 </td>
   <td style="text-align:left;"> $QQQ $SPY The pain trade still feels like it&amp;#39;s higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:29 </td>
   <td style="text-align:left;"> $SPY RSI is now finally overbought, 1D breaking over 70; and $QQQ is extreme overbought, with its 1W, 1D, 4H all overbought... while the vix has flattened and isn&amp;#39;t moving downward any further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:27 </td>
   <td style="text-align:left;"> $SPY 435c 6/30 50 contracts paid 1.06 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:24 </td>
   <td style="text-align:left;"> $spy 433 C </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:22 </td>
   <td style="text-align:left;"> $SPY Why is it that the dumbest most corrupt imbeciles get to run around scott free fcking up literally everything they touch yet the guy who gave me four years of 2.35/gallon gas gets indicted 738 times?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:17 </td>
   <td style="text-align:left;"> $SPY Gap and go? 🤔 I thought it would pull back alittle today then fly later in the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:16 </td>
   <td style="text-align:left;"> $SPY could be a fun Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:06 </td>
   <td style="text-align:left;"> One knows they&amp;#39;ve developed a good portfolio when you think there are too many holdings in it and some should be sold but you can&amp;#39;t find one to sell because you like then all , better yet, the market likes then too.. 
 
 
portfolio   14 holdings  and would like to bring it down some  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:04 </td>
   <td style="text-align:left;"> $SPY I feel like everyone bear and bull need to load calls today so we all win!! It&amp;#39;s only going up obviously 🎉🤘🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:02 </td>
   <td style="text-align:left;"> $SPY we blasting off to 431 today? Look at all the buying up here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:51:00 </td>
   <td style="text-align:left;"> $SPY 431 resistance. I think we sell off from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:53 </td>
   <td style="text-align:left;"> $SPY greed and fear at 78 from 82 on Feb 2 2023 so we are primed for the safer bet on puts for next week for sure .. I added 10 puts $417 June 30 at $1.68 and in addition to 10 puts bought yesterday at $1.88.. Will keep adding at $431.7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:50 </td>
   <td style="text-align:left;"> $SPY Just v it it will be okay 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:49 </td>
   <td style="text-align:left;"> $SPY ok bears heres a bone. buy the $431 call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:48 </td>
   <td style="text-align:left;"> $FUBO $30

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:42 </td>
   <td style="text-align:left;"> $SPY bears are needed for your precious market to go high you fucking nerds. I can’t wait til you all get wiped out. You don’t even understand fundamental economics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:42 </td>
   <td style="text-align:left;"> $SPY so... is this what Global peace looks like? No wars and all politicians are honest? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:42 </td>
   <td style="text-align:left;"> $SPY even the market likes it lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:40 </td>
   <td style="text-align:left;"> $SPY yum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:36 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Sanction even china now ? where is this ending lol ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:31 </td>
   <td style="text-align:left;"> $SPY $VOO no way feds pause rate hikes. Economy still wayyy too hot. They take their foot off the pedal now, it would be a disaster. This euphoria will not last. Still have a lot of cash on the sidelines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:24 </td>
   <td style="text-align:left;"> $SPY any bears😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX $AAPL $NVDA  
 
bearvastation: devastation beyond compare... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:18 </td>
   <td style="text-align:left;"> $SPY $NIO $AMD 

Let’s go 🟢🟢🟢🟢🟢🟢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:15 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ve seen enough...waiting for afternoon profit taking to take place before the next week. Good luck to anyone reading, no matter what side of the trade you&amp;#39;re in! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:14 </td>
   <td style="text-align:left;"> $SPY bears devastated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:10 </td>
   <td style="text-align:left;"> $SPY $TSLA link in the bio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:07 </td>
   <td style="text-align:left;"> $SPY what happened to all those triple top every one was obsessed over? 😂. Will probably come back and test 429.60. If that holds. Clear skies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:05 </td>
   <td style="text-align:left;"> $SPY Yogi said you bulls nasty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:04 </td>
   <td style="text-align:left;"> $SPY $TSLA 2 100+% days back to back. THANK THE MOST HIGH 🙏🏿✝️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:50:01 </td>
   <td style="text-align:left;"> $SPY They&amp;#39;ve really been sucking the money out of bears these weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:58 </td>
   <td style="text-align:left;"> $SPY Once again the poots I’ve sold are losing value. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Markets literally have no where to go but up!!! 📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:55 </td>
   <td style="text-align:left;"> $SPY futures are 1% higher than spy/spx? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:54 </td>
   <td style="text-align:left;"> $SPY $SPX open atm straddle worked great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:53 </td>
   <td style="text-align:left;"> $SPY here comes Aladdin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:50 </td>
   <td style="text-align:left;"> $SPY financials saying fade $FAS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:47 </td>
   <td style="text-align:left;"> $SPY Annnnnd I&amp;#39;m out. +80% on my 6/12 429 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:28 </td>
   <td style="text-align:left;"> $CCL $22 in 6 months. 80% covid debt paid off by Dec 2023. You will seeeeee. $NCLH $SAVE $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:26 </td>
   <td style="text-align:left;"> $SPY thank you Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:24 </td>
   <td style="text-align:left;"> $SPY really strange that they didnt use that tsla bs to gap this over rez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:18 </td>
   <td style="text-align:left;"> $SPY HEHE VIX BE LIKE NOT SURE IF SERIOUS👀😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:17 </td>
   <td style="text-align:left;"> $QQQ 12 mins before nasty drop, and $IWM should rise $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:16 </td>
   <td style="text-align:left;"> $SPY markets only up from here. Bears have been driven away </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:12 </td>
   <td style="text-align:left;"> $SPY are we voting for trump when he&amp;#39;s behind bars? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:11 </td>
   <td style="text-align:left;"> $SPY  
Patiently waiting ♻️🥂🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:08 </td>
   <td style="text-align:left;"> $SPY bears getting chopped. $$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:06 </td>
   <td style="text-align:left;"> $SPCE did you know $SPY is hitting $431?.🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:02 </td>
   <td style="text-align:left;"> $SPY welcome to the crazy BULL market rally ...how you doing bears .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:00 </td>
   <td style="text-align:left;"> $SPY okay so now what 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:49:00 </td>
   <td style="text-align:left;"> $SPY Friday&amp;#39;s rallies are as predictable as a two headed coin flip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:56 </td>
   <td style="text-align:left;"> $SPY Pakistan begins riots and poverty crisis intensifies. China has major symptomatic covid waves hit. Travel is limited </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:42 </td>
   <td style="text-align:left;"> $SPY $QQQ New investment thesis of 2023:

- Put a bunch of mega cap tickets on a dartboard
- Blindfold yourself
- Throw until something hits
- YOLO life savings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:36 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:28 </td>
   <td style="text-align:left;"> $SPY congratulations y’all, we’re thru. Time to get paid 🤌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:19 </td>
   <td style="text-align:left;"> $SPY Let&amp;#39;s see how fast this dumps next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:18 </td>
   <td style="text-align:left;"> $SPY Don’t chase. Don’t chase. Don’t chase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:15 </td>
   <td style="text-align:left;"> $SPY 

Bulls acting like we are about to enter long period of geopolitical stability, low inflation, fiscal stimulus and accommodative monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:15 </td>
   <td style="text-align:left;"> $SPY u guys just want people to  buy it into the greed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:12 </td>
   <td style="text-align:left;"> $NIO pt $20

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears what ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:48:00 </td>
   <td style="text-align:left;"> $SPY fade it now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:59 </td>
   <td style="text-align:left;"> $SPY  $QQQ  Europe announces they&amp;#39;re in a recession (Finally admit it) CNBC and CNN announce the start of a new Bull Run the same day.   Basically admitting they&amp;#39;re liars on the front page. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:55 </td>
   <td style="text-align:left;"> 🗣️: Option: $SPY $430Put 0DTE from $0.51→ $0.63 🍏 
 
#NASDAQ #NASDAQ100 #SPY #QQQ #TQQQ #TSLA #FrogAlgo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:46 </td>
   <td style="text-align:left;"> $SPY feels like the markets been open for 2 hrs already haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:45 </td>
   <td style="text-align:left;"> $SPY another Green Day yay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:44 </td>
   <td style="text-align:left;"> $AMC $GME  
🍿🎮👨‍🚀 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:41 </td>
   <td style="text-align:left;"> $SPY Damn lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:36 </td>
   <td style="text-align:left;"> $SPY bears: “any news ?” ._. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:31 </td>
   <td style="text-align:left;"> $SPY be very careful VIX downside compression historically speaking doesn’t have too much more to go, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:24 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Looking at $RSP tells me everything I need to know about what&amp;#39;s going on this morning.

Megas pumping again because no one has faith in the market.

Two highest volume days in tbe history of $FNGD this week as someone accumulates this instrument in anticipation of what&amp;#39;s coming.

Keep chasing the top 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:16 </td>
   <td style="text-align:left;"> $SPY $QQQ ATH cometh let&amp;#39;s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:13 </td>
   <td style="text-align:left;"> $SPY I’m playing puts on everything I didn t say just now I meant at the end of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:09 </td>
   <td style="text-align:left;"> $SPY Watch out for This 431-432 Area.  👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:08 </td>
   <td style="text-align:left;"> $SPY it’s not even like steady small moves up 🤣🤣🤣 it just rips like a meme penny stock 🤣 unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:07 </td>
   <td style="text-align:left;"> $SPY $AAPL just genuinely curious as to why Apple is up 40 this year that&amp;#39;s a staggering number in just 6 months time for a almost 3 trillion company what a beauty eh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:06 </td>
   <td style="text-align:left;"> $TSLA $SPY

bears getting greedy not locking in profits from that opening dip, squeeze em! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:47:01 </td>
   <td style="text-align:left;"> latex463bac9dd58885fe25bd1666d5ab7731tsla 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:59 </td>
   <td style="text-align:left;"> 🔥Option: $SPY $430Put 0DTE 
🔥Price: $0.51/Contract 
👁️Stop_Loss Plan: -21%  
 
 
#NASDAQ #NASDAQ100 #SPY #QQQ #TQQQ #TSLA #FrogAlgo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:58 </td>
   <td style="text-align:left;"> $SPY 1st hour ufugazee type moves taking place. Literally place your bets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:56 </td>
   <td style="text-align:left;"> $SPY so dumb that bulls can just buy calls on their only DD being that you should just buy calls and go do something else. Its that fucking easy somehow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:51 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s a trap ⬇️⬇️⬇️⬇️🍷😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:45 </td>
   <td style="text-align:left;"> $SPY $435 today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:44 </td>
   <td style="text-align:left;"> $SPY Added 440 Calls, this is. Lotto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:43 </td>
   <td style="text-align:left;"> Also helps when things are bullish for $SPY on the #UltimateIndicator!!! 
 
Bullish... bullish... trigger!!! 
✅✅🚀 
(not investment advice) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:42 </td>
   <td style="text-align:left;"> $SPY is this BS ever gonna pullback?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:42 </td>
   <td style="text-align:left;"> $SPY nice 100 percent on the swing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Institution FOMO alert elevated.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:35 </td>
   <td style="text-align:left;"> $SPY when is opec meeting next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:31 </td>
   <td style="text-align:left;"> $nio since 7.30s ✌️ told you buy the weakness dump instead chase the already pumped stocks  
 
$tsla $nvda $intc $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:29 </td>
   <td style="text-align:left;"> $BBBYQ Supposedly we are in a new &amp;quot;bull&amp;quot; market, how long will it last? Surprisingly no one knows? I for one am waiting on this horse. Giddy UP!   
$SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:23 </td>
   <td style="text-align:left;"> $SPY You stupid bears… you need to go redraw your drawings again! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:21 </td>
   <td style="text-align:left;"> $SPY market has no fear. $QQQ black swan around the corner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:18 </td>
   <td style="text-align:left;"> $SPY hope for a run if not reversal can happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:17 </td>
   <td style="text-align:left;"> $SPY I need all the bear gurus to come out and play 

Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:46:15 </td>
   <td style="text-align:left;"> $SPY can’t make this stuff up it’s just to easy 😂🤑😂🤑😂🤑😂🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:45:54 </td>
   <td style="text-align:left;"> $SPY Bull rally is back baby.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:45:52 </td>
   <td style="text-align:left;"> $QQQ $SPY fing disgusting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:45:49 </td>
   <td style="text-align:left;"> $SPY go up up up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:45:37 </td>
   <td style="text-align:left;"> $SPY Boom BOOm 4310 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:45:33 </td>
   <td style="text-align:left;"> $SPY FED is reason why we can&amp;#39;t have price stability </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:45:29 </td>
   <td style="text-align:left;"> $SPY 435 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:03:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $TSLA $X i usually dont eat cats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:03:10 </td>
   <td style="text-align:left;"> $QQQ Extreme Greed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:03:06 </td>
   <td style="text-align:left;"> $SPY $SCHD $VOO $QQQ 
Imagine betting against a market that has an average yearly return rate of +9% since 1902. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:02:57 </td>
   <td style="text-align:left;"> $SPY NATO condemns Russia&amp;#39;s withdrawal from conventional armed forces treaty | $QQQ $TSLA $NVDA https://cyprus-mail.com/2023/06/09/nato-condemns-russias-withdrawal-from-conventional-armed-forces-treaty/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:02:22 </td>
   <td style="text-align:left;"> $TMC congrats my dears .. nailed …  please stay rich and get richer, its a generational bull after all $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:02:21 </td>
   <td style="text-align:left;"> $QQQ greed and delusion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:02:06 </td>
   <td style="text-align:left;"> $QQQ This makes absolutely no sense… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:01:42 </td>
   <td style="text-align:left;"> $MRKR $NXPL $QQQ $VS adding big on Nxpl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:01:30 </td>
   <td style="text-align:left;"> $SPY  $QQQ    when you give your broker $1000 and he give you back $500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:01:19 </td>
   <td style="text-align:left;"> $NXPL look perfect for squeeze coming.
Over daily vol avg already. Locked

$VS and $MRKR tight consolidation
For a pop. 
$QQQ 💥
Nxpl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:01:08 </td>
   <td style="text-align:left;"> $QQQ bought 5 puts June 30 $365 at $10.62 GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:00:40 </td>
   <td style="text-align:left;"> $QQQ top of the gap fill is 360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:00:39 </td>
   <td style="text-align:left;"> $SPY now just pray Russia not nuke Eastern Europe and China not create another Cuban Missile Crisis $QQQ $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:00:22 </td>
   <td style="text-align:left;"> $QQQ Looks frothy, time to roll over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:00:10 </td>
   <td style="text-align:left;"> $UPST full fraud zone in effect. propped and support by the likes of the typical $qqq fraud and overall index fraud.   1% again how many days in a row now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:00:08 </td>
   <td style="text-align:left;"> $QQQ bubble is about to burst !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 22:00:06 </td>
   <td style="text-align:left;"> $QQQ If the Nasdaq continues at the same pace it has the past 6 months, it will finish the year +87%, which will be the HIGHEST EVER ANNUAL RETURN for the nasdaq, and quite honestly a bit ridiculous.  Near 100% returns in one year on a major index is a bubble. 
 
The only other time it did this even remotely close was 1999 which looking back was clearly a bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:57 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ who buys CALLS on a stock up 11 days in a row into a huge gap up LMFAO  onky pajama can pull that off yes intook my profits alrwady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:47 </td>
   <td style="text-align:left;"> $QQQ  has it ever? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA All headlines “entered new bull market” yup.. that’s how you know it’s time for some distribution.. get all the chumps buying up all the expensive shares🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:42 </td>
   <td style="text-align:left;"> $NXPL HELL YEAH!!!

A beautiful beast ticker is waking up!!

Has more to give than $ADD 
 Trades with $SPY and $QQQ both are bullish $AI has been going up nicely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Muppets get murdered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:36 </td>
   <td style="text-align:left;"> $QQQ red? yea you can go back up now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:32 </td>
   <td style="text-align:left;"> $SPY $QQQ OH Kay! 🥹🥹🥹 Closeddddd nasdaq and spy booola calls!! Think it camps now for theta partayyy before next moveeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:23 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:59:21 </td>
   <td style="text-align:left;"> $SPY zero sellers. Endless buyers. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:58:56 </td>
   <td style="text-align:left;"> $QQQ this makes absolutely no sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:58:47 </td>
   <td style="text-align:left;"> $QQQ $370 by end of next week. Don’t fight the trend bro😂😂. Markets are designed to keep going up Unless a black swan comes in and even then we just “V” later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:58:44 </td>
   <td style="text-align:left;"> What stocks might make more money? Pick the best $DIA vs. $QQQ vs. $VCR. https://srnk.us/go/4714406 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:58:44 </td>
   <td style="text-align:left;"> EPIC INSTANT V DID YOU LISTEN 
 
WHEN PAJAMA SAYS BTFD V RALY COMING YOU NEED TO PAY ATTENTION 
 
KNEEL 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:58:43 </td>
   <td style="text-align:left;"> $QQQ $SPY  Lots of people will make money during this markets, but trust me they will all lose it back and some more just like the covid pumps and the dotcom bubble. Just wait and short at a round number. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:57:57 </td>
   <td style="text-align:left;"> $QQQ timber bitches. Yall delusional af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:57:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Jokes aside, this is the kind of frothy top I was looking for. Would be nice to over extend it as an initial reaction to CPI or June pause. Max pain hopefully leading into a sharp pullback.

We need a distribution of ventilators to other market participants. 😷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:57:46 </td>
   <td style="text-align:left;"> $QQQ the only bull case for the last 6 months was that everyone was bearish, so thats the narrative now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:57:29 </td>
   <td style="text-align:left;"> $QQQ $AAPL dragging this down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:57:15 </td>
   <td style="text-align:left;"> $TSLA $NVDA $SPY $QQQ $AMD 

How’s my portfolio for a 24 year old? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:56:48 </td>
   <td style="text-align:left;"> $NFLX  on the right track

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:56:47 </td>
   <td style="text-align:left;"> $QQQ Stupidity, plain and simple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:56:24 </td>
   <td style="text-align:left;"> $SPY the new normal is green vertical everyday $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:56:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Remember this @FTV kid was buying $UVXY hard at 10 !!! DUMB FAKE $$$ !!!  Im not sorry for his followers getting wiped out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:55:49 </td>
   <td style="text-align:left;"> $spy $qqq Market keep ripping before the FOMC next week !! 
 
MOC was buy side at pulls — Big boys always knew how the week would be .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:55:47 </td>
   <td style="text-align:left;"> $SPY $QQQ Have a blessed day! 
Matthew 7:13-14 (King James Version) 
  
Enter ye in at the strait gate: for wide is the gate, and broad is the way, that leadeth to destruction, and many there be which go in thereat: Because strait is the gate, and narrow is the way, which leadeth unto life, and few there be that find it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:55:10 </td>
   <td style="text-align:left;"> $QQQ   New All Time Highs just around the corner! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:54:49 </td>
   <td style="text-align:left;"> $QQQ $SPY Extreme greed is going to hurt people next week. Fed will be sell the news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:54:38 </td>
   <td style="text-align:left;"> $QQQ Back @ 357 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:54:33 </td>
   <td style="text-align:left;"> The bigger picture this morning... 
 
$SPY $QQQ $DIA $VIX 
 
https://share.trendspider.com/chart/m/6682omoet8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:54:25 </td>
   <td style="text-align:left;"> PAJAMA!!! 
 
ON!!!! 
 
FIRE!!!! 
 
absolutely KILLING IT just did a 10 minute trade in 0dte $tsla calls in addition to what i held overnight lmao  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:54:17 </td>
   <td style="text-align:left;"> $QQQ $SPY FUCK YOU GARY GENSELR YOU CORRUPT ASS FUGGUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:54:11 </td>
   <td style="text-align:left;"> $QQQ you think we are done... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:55 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA $NASDAQ $RUT 

Wait for monday and the following friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:55 </td>
   <td style="text-align:left;"> $spy Market seems to like  Trump getting indicated,..  
 
Breaking Video: FBI asking Trump to give the Documents back &amp;amp; his response 
 
https://www.youtube.com/watch?v=RKMNPQ35OUc 
 
$aapl $dwac $rum $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:37 </td>
   <td style="text-align:left;"> $AAP &amp;lt;—————. Way oversold pos here. $spy $qqq $VOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:22 </td>
   <td style="text-align:left;"> $SPY $QQQ 1% every day is the new norm. Wallstreet apparently smarter than us all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:15 </td>
   <td style="text-align:left;"> $QQQ when is the last time this didn&amp;#39;t spring board at the open? 3 weeks ago? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:01 </td>
   <td style="text-align:left;"> $QQQ absolute insanity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:53:01 </td>
   <td style="text-align:left;"> I&amp;#39;m hearing news reports of another ventilator shortage... 😬😬😬

Due to all the market bears on life support. 

$spy $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:52:49 </td>
   <td style="text-align:left;"> $QQQ 370 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:52:27 </td>
   <td style="text-align:left;"> $SPY $QQQ Gorgeous breakouts from open so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:52:26 </td>
   <td style="text-align:left;"> $SPY $QQQ 🤑🤑🤑 called out in our free chat! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:52:03 </td>
   <td style="text-align:left;"> $SPY  $QQQ  revised  CNN/CNBC article..  Good news ! After the nasdaq drops 45-50% and stocks struggle to recover for 6 months we should start a new Bull Run ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:52:02 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DJIA $RUT $NASDAQ 

Staircase up, elevator down.  Every time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:51:51 </td>
   <td style="text-align:left;"> $QQQ TLT down, 10yr up hard, dxy holding important level. 
 
Q cash orgy defying gravity continues for now. Auctions will continue on bonds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:51:50 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA clown market disconnected from reality. Stonks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:51:45 </td>
   <td style="text-align:left;"> $QQQ this is going to dump hard $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:51:31 </td>
   <td style="text-align:left;"> $QQQ $SPY The pain trade still feels like it&amp;#39;s higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:51:29 </td>
   <td style="text-align:left;"> $SPY RSI is now finally overbought, 1D breaking over 70; and $QQQ is extreme overbought, with its 1W, 1D, 4H all overbought... while the vix has flattened and isn&amp;#39;t moving downward any further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:51:11 </td>
   <td style="text-align:left;"> $QQQ 90% of fridays have been trend days hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:50:55 </td>
   <td style="text-align:left;"> $BYND $NVDA $QQQ 

Let’s go now 🩸🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:50:48 </td>
   <td style="text-align:left;"> $FUBO $30

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:50:46 </td>
   <td style="text-align:left;"> $QQQ this is about where the big dump happened Wednesday, let&amp;#39;s see what happens this time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:50:38 </td>
   <td style="text-align:left;"> $QQQ I can not for the life of me understand any of the logic behind these ridiculous moves. What&amp;#39;s good about the next 6 months? It&amp;#39;s gunna be a bad year. I see it already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:50:36 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Sanction even china now ? where is this ending lol ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:50:26 </td>
   <td style="text-align:left;"> $QQQ 345 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:49:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Markets literally have no where to go but up!!! 📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:49:40 </td>
   <td style="text-align:left;"> $QQQ largest qqq pump known in history since january... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:49:28 </td>
   <td style="text-align:left;"> $QQQ 😂 oh god the bears from yesterday must be fucked. I’m not even sure what the premise for their thesis is at this point. We were pricing in a deep recession and uncontrollable inflation. I’m not sure what will get you back to not only even but recouping lost gains and time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:49:17 </td>
   <td style="text-align:left;"> $QQQ 12 mins before nasty drop, and $IWM should rise $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:49:02 </td>
   <td style="text-align:left;"> $QQQ straight up! Squeeze!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:48:42 </td>
   <td style="text-align:left;"> $SPY $QQQ New investment thesis of 2023:

- Put a bunch of mega cap tickets on a dartboard
- Blindfold yourself
- Throw until something hits
- YOLO life savings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:48:12 </td>
   <td style="text-align:left;"> $NIO pt $20

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:48:11 </td>
   <td style="text-align:left;"> $QQQ tesla carrying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:48:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears what ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:47:59 </td>
   <td style="text-align:left;"> $SPY  $QQQ  Europe announces they&amp;#39;re in a recession (Finally admit it) CNBC and CNN announce the start of a new Bull Run the same day.   Basically admitting they&amp;#39;re liars on the front page. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:47:55 </td>
   <td style="text-align:left;"> $QQQ wry smiles @Yael_22 @sonicmerlin 

Dip was to be purchased </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:47:24 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Looking at $RSP tells me everything I need to know about what&amp;#39;s going on this morning.

Megas pumping again because no one has faith in the market.

Two highest volume days in tbe history of $FNGD this week as someone accumulates this instrument in anticipation of what&amp;#39;s coming.

Keep chasing the top 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:47:16 </td>
   <td style="text-align:left;"> $SPY latex3f4f1de6eea283f2d57f805bd6df679atsla 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:46:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Institution FOMO alert elevated.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:46:29 </td>
   <td style="text-align:left;"> $BBBYQ Supposedly we are in a new &amp;quot;bull&amp;quot; market, how long will it last? Surprisingly no one knows? I for one am waiting on this horse. Giddy UP!   
$SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:46:21 </td>
   <td style="text-align:left;"> $SPY market has no fear. $QQQ black swan around the corner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:45:52 </td>
   <td style="text-align:left;"> $QQQ $SPY fing disgusting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:58 </td>
   <td style="text-align:left;"> $TSLA HOLDING SESSION HIGHS 
 
ITS GOING TO BREAK HIGHER AND RUN TODAY WOWOWOOWOW BEARS SHORTING IT AND GIVING IT THE POWER TO DO SO 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK 

When the hell are growth stocks going join the rally???!!!!!!

It&amp;#39;s been 2.5 FUCKING YEARS SINCE THE SELLOFF IN FEB 2021!!!!!!

ITS TIME TO GO BACK TO NORMAL PRICES!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

tried warning bears not to bet against cnbc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:23 </td>
   <td style="text-align:left;"> $QQQ upupup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:20 </td>
   <td style="text-align:left;"> $QQQ 360 baby !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:19 </td>
   <td style="text-align:left;"> $AAPL $MSFT $QQQ $SPX $SPY spx over my resistance of 4307! Looks like a meltup in progress! Pretty broad based rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:44:08 </td>
   <td style="text-align:left;"> $QQQ Reminder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:49 </td>
   <td style="text-align:left;"> @SeNSF $SPY max pain is a bogus zero math internet fake topic. 
 
Learn more  
 
$QQQ $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:43 </td>
   <td style="text-align:left;"> $QQQ algo powers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:39 </td>
   <td style="text-align:left;"> $QQQ wow 😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:35 </td>
   <td style="text-align:left;"> $TSLA when it break 250 it can rub ti 260 FAST FAST inagine cor weing thr market on gast stations at the advent of gas powered cars  
 
$spy $qqq  
 
🚀🚀🚀🚀🤑🤑🤑📈📈📈📈 
 
DID YOU LISTEN 
 
LETS GAMMA SQUEEZE THIS NAME!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:33 </td>
   <td style="text-align:left;"> $QQQ it’s called free lunch Friday for a reason. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:16 </td>
   <td style="text-align:left;"> $SOFI $QQQ  Run forest! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:15 </td>
   <td style="text-align:left;"> $QQQ — 356.50 is critical. Expect a reaction at or around that area of value

$TQQQ $SQQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA on steroids 
 
Do not short Strength 🐝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:04 </td>
   <td style="text-align:left;"> $QQQ $SPY here comes the flush. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:43:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

cnbc &amp;gt; bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:42:58 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ  
Lmfao 🤣🤣🤣🤣💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:42:38 </td>
   <td style="text-align:left;"> $SPY $QQQ Bloomberg reporting Michael Hartnett, BofA, remaining bearish - &amp;#39;Q1 recession fear...Q2 Goldilocks greed...S&amp;amp;P breaking out bull market bubbly (though ex-Magnificent 7 up more sober 1% YTD),,,Fed ain&amp;#39;t done with hikes so we stick with &amp;#39;sell the last rate hike&amp;#39; call.&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:42:31 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $QQQ $SPY fomo fomo… faster and furious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:42:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ 

BEARS ABOUT TO GET DOWNGRADED BY CNBC 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:41:34 </td>
   <td style="text-align:left;"> $NVDA $TSLA $SPY $QQQ Tech super bubble is back baby!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:40:50 </td>
   <td style="text-align:left;"> $SPCE 

🔥10 THINGS TO LOOK FORWARD TOO WITH VIRGIN GALACTIC SPCE🔥

1. First Ever Commercial Space Flight Coming Real Soon at the end of June
2. Huge Revenue Stream of $450,000 for Each Person Flying
3. Huge Media Coverage for Celebrities Flying to Space
4. Celebrities giving Virgin Galactic more Exposure leading to more ticket and stock sales
5. Possible New Partnerships including Space X (Richard Branson and Elon Musk are Great Friends)
6. New Delta Class Spaceships
7. New Future Space Technology
8. Supersonic Air Travel
9. Future Space Exploration
10. More Government Contracts

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:40:45 </td>
   <td style="text-align:left;"> $QQQ back to your regular broadcast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:40:15 </td>
   <td style="text-align:left;"> $SPY $QQQ

One little sell off we had completely erased in just over one trading day.

QE markets are back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:39:16 </td>
   <td style="text-align:left;"> $spy $qqq $spx $DJIA $dji 
People keep ignoring the inevitable 🫧📌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:39:10 </td>
   <td style="text-align:left;"> $QQQ so weird how we had that huge rotation out of tech Wednesday just to immidiatly rotate it back in. Anybody have an explanation for that? Or was it just fomo knuckleheads jumping on a dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:39:06 </td>
   <td style="text-align:left;"> $TSLA Today&amp;#39;s Max Pain @ 222.5. Bulls need 251.5 Breakout. Bears need 246 Breakdown. $SPY $QQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:38:38 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA see you next week! Just hodl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:38:30 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ NVDA SWING PAYING OFF.
WHAT A DAY. 💎💎💎💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:38:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Remember:

Thurs/Friday is squeeze day as long as I remember. Mkt loves to front rally cpi/fomc events and yesterday suprise jobless claim #s supporting it. Friday poot squeeze can happen on ramp and camp, especially with Tesla, Netflix, and other megas soaring.

Ride the Veeeeee with trailing stops now, and enjoy the weekend! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:38:17 </td>
   <td style="text-align:left;"> $QQQ $SPY I love fomo fridays. Printing machine and no downside risk. Rich af. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:38:05 </td>
   <td style="text-align:left;"> $DDS Dillards has been on a nice run the last few days.  It has such a low float.  I wouldn’t be surprised if it hits $400 again like it did last year. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:37:44 </td>
   <td style="text-align:left;"> $SPY Hedge funds have pumped the market high enough to create liquidity for themselves to dump.  It&amp;#39;s always retail that end up holding the bag.  Times are good?  Just wait for it.   $dxy $uvxy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:37:37 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $CVNA 725% GAIN AT OPEN. The community is BANKING. Unbelievable!!! 2-14‼️ 💎💎💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:37:01 </td>
   <td style="text-align:left;"> $SPY every day gonna rip. $QQQ problem is everyone just stays super bearish. Need sentiment to change </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:36:44 </td>
   <td style="text-align:left;"> $QQQ yeah shorting this isn’t smart, it’s not going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:36:36 </td>
   <td style="text-align:left;"> $SPY So which PM&amp;#39;s are going to front run next weeks drop &amp;amp; start Selling today? 
lets watch &amp;amp; find out 
 
$aapl $tlsa $nvda $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:36:26 </td>
   <td style="text-align:left;"> @MLinv @fvbusiness $SPY  $QQQ 
 
&amp;quot;This whole correction was just a rotation cycle.&amp;quot; 
 
yeah, it wasnt the insane inflation that had the FED running rates up 500 bps in the shortest period ever. 
 
IDIOT!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:36:18 </td>
   <td style="text-align:left;"> $QQQ Tech stocks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:36:14 </td>
   <td style="text-align:left;"> $SPY $QQQ if any one of the bitches say that we are in a bear market needs a good slap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:36:06 </td>
   <td style="text-align:left;"> $AAPL Today&amp;#39;s Max Pain @ 177.5. Bulls need 182.3 Breakout. Bears need 180.7 Breakdown. $SPY $QQQ $UVXY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:35:59 </td>
   <td style="text-align:left;"> $QQQ 357 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:34:59 </td>
   <td style="text-align:left;"> $QQQ $SPY $NVDA $MSFT $TSLA down we go told you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:34:56 </td>
   <td style="text-align:left;"> $NIO $QQQ $SPX $SPY  my regards to the idiots that went short 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:34:24 </td>
   <td style="text-align:left;"> $QQQ Today&amp;#39;s Max Pain @ 350. Bulls need 356 Breakout. Bears need 353.5 Breakdown. $SPY $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:34:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 52509100. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:32:38 </td>
   <td style="text-align:left;"> $TSLA keep dumping $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:32:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM massice rally to close the week huge upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:31:53 </td>
   <td style="text-align:left;"> $SPY Today&amp;#39;s Max Pain @ 425. Bulls need 431 Breakout. Bears need 429 Breakdown. $QQQ $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:31:46 </td>
   <td style="text-align:left;"> $QQQ why. Why why why 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:31:30 </td>
   <td style="text-align:left;"> $TSLA wow - that premium on the 250s halved in the first 10 seconds.

Best lock your profits 🤣

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:30:58 </td>
   <td style="text-align:left;"> $QQQ $SPY Usually not a fan of Casey but he really nailed it here, $AAPL anyways enjoy your Dystopian Future Bulls I&amp;#39;m sure this all ends well https://www.youtube.com/watch?v=UVX6kxnJgMU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:29:51 </td>
   <td style="text-align:left;"> $SPY $QQQ lets see if is a fake out or not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:29:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $NASDAQ $RUT 

Nobody wants to caution the fear/greed index.

Ok. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:29:24 </td>
   <td style="text-align:left;"> $VIX contango is a real drag.  
 
https://learn.optionsai.com/vix-contango-is-a-real-drag/ $SPY $QQQ $UVXY $VXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:28:55 </td>
   <td style="text-align:left;"> $SPY  $qqq there’s a difference between what CNBC says and what they do under the table .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:28:25 </td>
   <td style="text-align:left;"> $AAPL $MSFT $DIA $SPY $QQQ The Canadian labour market finally faltered in May, shedding 17,300 jobs to post the first decline since last August. That missed expectations for a gain of 21,300 jobs, though it is worth noting that there’s a reasonably significant confidence interval to these numbers, so that spread isn’t quite as wide as it seems at first glance. The unemployment rate rose 0.2 per cent to 5.2 per cent – also the first increase since August – but it’s the composition to things that catches the eye: employment among youth aged 15-24 fell by 77,000 positions, offsetting gains for older workers. In any case, that 17,300 drop doesn’t even offset the gains we saw in April, so it’s not as if the sky is falling on the labour market, and the Bank of Canada will likely need a whole lot more evidence that its policies are cooling the labour market before changing its tune.    https://www.bnnbloomberg.ca/?lid=l4d9fyn7fg2r </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:28:07 </td>
   <td style="text-align:left;"> latexf1279e49a73874b5d8727c41ad1ccceeSPY is exactly at its 0 618 FIB  retracement (429.50)

$TSLA after that big push, is now trading just 5-6 dollars below its 0.618 FIB retracement (255) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:26:40 </td>
   <td style="text-align:left;"> $QQQ just wow lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:26:11 </td>
   <td style="text-align:left;"> $SPY $QQQ 

If you see CNBC Dan Nathan living under a bridge or sleeping in the subway for the love of god don’t  throw him any spare change he will only use it to short more $TSLA  or $NVDA 
He has a problem he needs help </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:25:15 </td>
   <td style="text-align:left;"> $QQQ should flush this morning $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:24:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA $MSTR $AAPL they are going to send it straight down 5 mins afte open watch this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:24:11 </td>
   <td style="text-align:left;"> $QQQ $SPX loading shorts, when all crazy bubbles going in few hype bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:23:52 </td>
   <td style="text-align:left;"> $QQQ grinding... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:23:15 </td>
   <td style="text-align:left;"> $ATVI $qqq $spy if u support cod after yesterday u support pedophilia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:22:28 </td>
   <td style="text-align:left;"> $SPY $QQQ who trades using the news? 😂 oh yeah, bears 6-12 months behind the ball, CNBC is garbage, if you’re getting trade ideas from there, you’re already a failing trader(of course, always wise to stay hedged) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:21:27 </td>
   <td style="text-align:left;"> $QQQ this is top guys
We are range bound till 2024
Recession coming to a media outlet near you very very soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:21:26 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
AI, AI, AI hype is nearing a peak. Be careful what you do with AI hype and stock manipulation, because government can also use AI to spot scammers and catch them. LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:20:49 </td>
   <td style="text-align:left;"> $QQQ $SPY Let me see if there is $ above the previous highs too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:20:47 </td>
   <td style="text-align:left;"> $ES_F $QQQ $SPY 

Here comes our typical Friday 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:20:33 </td>
   <td style="text-align:left;"> Good Morning Legends!!!
We are looking at $SPY $QQQ $ADP $UPS $UNP 
Happy Friday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:20:33 </td>
   <td style="text-align:left;"> $QQQ So Wednesday&amp;#39;s -2% meant nothing? Load the shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:20:33 </td>
   <td style="text-align:left;"> $QQQ happy top buying 🤙🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:20:10 </td>
   <td style="text-align:left;"> @Bullorbear67 SEC like other 3-letter agencies works for the global private central bankers. GG worked as a $GS executive. Their ultimate goal is to take out DeFi which is the last main obstacle to rolling out CBDCs. Their stunt over the past 2-3 years taught them they could get away with way more than they thought they could. CBDC is next. SEC is using the worst of crypto (CEX where you don’t own your keys like you don’t own your shares in brokerages) to go after DeFi. 

$qqq $SPY $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:19:43 </td>
   <td style="text-align:left;"> $QQQ congrats you guys are buying some shit benchmarked to basically Dogecoin rn. This market is fucking goofy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:19:30 </td>
   <td style="text-align:left;"> $VIX $IWM $SPY $QQQ 😂 yes, lets ignore the well known fact that bull markets are 10x longer than bear ones and normally run in greed/extreme greed territory…bears are so smart, yet so dumb 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:18:59 </td>
   <td style="text-align:left;"> $SPY  $QQQ  I like how mainstream news got everyone extreme bearish in December right before the market went on a 7 month bull run,  now they&amp;#39;re trying to get everyone extreme Bullish before they pull the rug. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:18:07 </td>
   <td style="text-align:left;"> $QQQ greed index at 77 and vix at 13, man, either the market is just broken or its pulling back soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:17:55 </td>
   <td style="text-align:left;"> Sending wires every day now.  

When’s this going to stop $SPY $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:17:36 </td>
   <td style="text-align:left;"> $SPY $TSLS $AAPL $QQQ 

I’m guessing trumps puts expired worthless????…. 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:16:58 </td>
   <td style="text-align:left;"> Sent out another wire $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:14:47 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Is It A New Bull Market Yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:14:39 </td>
   <td style="text-align:left;"> $GME $QQQ $CVNA $BYND $SPCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:14:20 </td>
   <td style="text-align:left;"> $spy $qqq $tsla

folks are willing to risk hard earned money being stubbornly contrarian? gotta be allowance money haha. insanity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:14:17 </td>
   <td style="text-align:left;"> $QQQ $SPY  
HURRAH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:13:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $VIX  $DJIA 

The most obvious trap waiting to spring if I ever did see one.  Months of bad news media followed by THIS week of them saying we entered a bull market.

Horseshit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:13:30 </td>
   <td style="text-align:left;"> $CVNA 🚙 $BA 🏦 and $QQQ 💾 all went crazy 😜 yesterday! Let’s see what today brings for the market 🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:13:26 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:13:05 </td>
   <td style="text-align:left;"> Extremely low volume in pre market  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:12:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Today’s Economic Calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:12:05 </td>
   <td style="text-align:left;"> $VECO $SPY $NASDAQ $QQQ $TSLA  great stocks to short! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:11:08 </td>
   <td style="text-align:left;"> $qqq $spy not call of duty going after your kids too.. 😭😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:10:20 </td>
   <td style="text-align:left;"> $IWM this is about to breakout hard at open 190 in first 30 mins $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:09:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM this market is headed way higher I keep seeing great news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:08:55 </td>
   <td style="text-align:left;"> $SPY $QQQ TOO strong V and $IWM About to breakout hard soon...easy LONG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:08:17 </td>
   <td style="text-align:left;"> $SNAX retail sleeping on this one. They won&amp;#39;t be when it&amp;#39;s in the $1s range. 

$SPY $QQQ $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:07:20 </td>
   <td style="text-align:left;"> STUPID FED GOONS IN 🇨🇦 RAISING INTEREST RATES .25% THIS WEEK POST TODAY&amp;#39;S EMPLOYMENT REPORT RELEASED MOMENTS AGO @ https://global-premium.econoday.com/byshoweventfull.aspx?fid=570778&amp;amp;cust=global-premium&amp;amp;year=2023&amp;amp;lid=0&amp;amp;prev=/byweek.asp#top #TRUDEAUSUCKS $DIA $SPY $QQQ $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:07:09 </td>
   <td style="text-align:left;"> Morning News:

📈~ The S&amp;amp;P 500 is now up 20% from the October 12, 2022 low.
This means the $SPY &amp;amp; markets are now officially in a new bull market.

📉~ PacWest, $PACW, last month sold $2.6 billion of construction loans at a loss.

🇺🇸~ Donald Trump has become the first U.S. president, former or otherwise, to be indicted on federal criminal charges. $QQQ

🔥~ Wedbush adds $TSLA stock to it’s best ideas list. Raises PT to $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:06:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Bloomberg noting 5 biggest tech stocks now an all-time record 24% of SPX. Binky Chadha, Deustche Bank, calling for SPX 4500, Mike Wilson again saying we&amp;#39;re in the earnings bust period. Mohamed El-Erian saying next TUE-WED will the most interesting period for markets in mos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:06:26 </td>
   <td style="text-align:left;"> Thanks a lot you lazy Bears 🐻 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:06:01 </td>
   <td style="text-align:left;"> $QQQ Absurd, it wants to fill the gap at $360 i guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:05:35 </td>
   <td style="text-align:left;"> Squeezing the Market: Riding the Rollercoaster of Short Squeeze Mania. $GME $QQQ $CVNA $BYND $SPCE https://www.zacks.com/commentary/2106141/squeezing-the-market-riding-the-rollercoaster-of-short-squeeze-mania </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:04:57 </td>
   <td style="text-align:left;"> @MLinv @fvbusiness and Wychoff is still 100% useless when trading/investing in $SPY $QQQ  
 
I said this in 1990, 2000, 2010, 2020.....there will always random black swans and 100% of the time BTD will work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:04:45 </td>
   <td style="text-align:left;"> What are the most profitable stocks right now? Pick the best $QQQ vs. $XLE vs. $XOM. https://srnk.us/go/4714137 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:04:18 </td>
   <td style="text-align:left;"> $QQQ so how far into extreme greed do stocks get before going down to levels that make any sense lol are we headed back to dot-com territory here or what </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:03:42 </td>
   <td style="text-align:left;"> $QQQ so MAGA&amp;#39;s still complaining about Biden markets? just curious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:02:32 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $tsla read @pnvoss recent posts. Relax, trust the process, give your self time to make your money back. Relax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:01:04 </td>
   <td style="text-align:left;"> $SPY futes ripping $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:00:58 </td>
   <td style="text-align:left;"> $DJIA $QQQ $SPY $TSLA who&amp;#39;s ready for another day of crooked Wall Street trading? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:00:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA has joined the fun… now every Nasdaq stock has a parabolic chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 21:00:20 </td>
   <td style="text-align:left;"> $SPY $QQQ The communist traitor is indicted, time to rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:59:50 </td>
   <td style="text-align:left;"> $QQQ $SPY Bears your time is approaching shortly. Since last week Calls are about 2/3 over Puts day traders it may be time to just sit out at these levels until we see a confirmation esp in AI/Tech/Growth give it a few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:59:45 </td>
   <td style="text-align:left;"> $QQQ $SPY lmao look at the bulls. Looks like they’re trying to push up a boulder lmaoo. Going to roll back on their faces shortly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:58:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $VOO $VTI Bye-bye bear... New S&amp;amp;P 500 bull market has legs - BofA

https://www.investing.com/news/stock-market-news/byebye-bear-new-sp-500-bull-market-has-legs--bofa-432SI-3102066 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:58:09 </td>
   <td style="text-align:left;"> $QQQ only down for a couple minutes, it’ll shoot right back up don’t worry. I’m giving free advice here lol 100% guarantee 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:57:57 </td>
   <td style="text-align:left;"> $QQQ man getting the pump early today huh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:57:40 </td>
   <td style="text-align:left;"> $SPY $QQQ 
CNBC has former Fed equating getting vaccines to raising rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:57:07 </td>
   <td style="text-align:left;"> HAMMMMMEEER GOLD 💰❗❗❗
CANADA LOSES 17.3K JOBS IN MAY; UNEMPLOYMENT RISES TO 5.2% FROM 5.0%
$QQQ $SPY $DJIA $ARKK $NASDAQ  jdjs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:56:36 </td>
   <td style="text-align:left;"> $SPY $QQQ im I the only one thinking this is a fake out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:56:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Too many calls - OI at the close yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:56:19 </td>
   <td style="text-align:left;"> $QQQ Back heavy short /NQ. Let&amp;#39;s ride. Not a hedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:55:56 </td>
   <td style="text-align:left;"> $BBBYQ + 20% premarket $QQQ $MULN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:55:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $ADBE Will be at least a 500% winner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:55:24 </td>
   <td style="text-align:left;"> $MSFT $QQQ $SPY Time to go up! 🚀🚀🚀🚀 

Microsoft : BMO raises target price to $385 from $347 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:54:01 </td>
   <td style="text-align:left;"> $SIEN chk this fda clearance 
$QQQ $SPY $UDOW $KOLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:53:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX at $13.6 😳😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:53:23 </td>
   <td style="text-align:left;"> DIA $F $SPY $TSLA $GM $QQQ  #todamoon  #carsonmars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:51:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA The market looks like it&amp;#39;s going up 2.75% across the board today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:51:07 </td>
   <td style="text-align:left;"> $CVNA  $SPY $QQQ $GME $SOFI .... also rolling 2-month t-bills.  weeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:50:04 </td>
   <td style="text-align:left;"> Top Watches today: Lots of movers today large caps small caps med caps, everything is flying, IMPORTANT to MANAGE RISK well though on a Friday after a long week... Looking for a nice bounce back day.** $MDGS $NFLX $TSLA $QQQ #PLTR #AFRM $WLDS **. Good luck out there! 🙏🍺❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:49:45 </td>
   <td style="text-align:left;"> $QQQ more pumps to the upside, neverending story </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:49:44 </td>
   <td style="text-align:left;"> The FBI has a server. Somewhere. Set up in a room running futures $SPY $QQQ 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:48:35 </td>
   <td style="text-align:left;"> $TSLA $spy $qqq $lcid go

https://www.twitch.tv/tramplewun/v/1841749838?sr=a&amp;amp;t=2s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:48:17 </td>
   <td style="text-align:left;"> $SPY what entities are sophisticated enough to manipulate Futures? $QQQ  CIA, FBI maybe DOJ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:48:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $NASDAQ $RUT $DJIA 

I&amp;#39;m stunned at how meny people are oblivious of the rise in BRICS economy.

Be educated people.  This will affect the USD.

https://www.newsweek.com/how-brics-evolving-china-russia-dream-us-defying-reality-1804844 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:48:08 </td>
   <td style="text-align:left;"> $QQQ next target = top of MM octave @ 355.5 ... = decision for next move...IF higher ~&amp;gt; shift of Murrey Math to a higher octave... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:47:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOFI Remember when people said inflation would be at 2% by summer 2023, and that the fed would be preparing for cuts. 
 
Lol. Most over-front runned pivot in history. So crowded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:46:25 </td>
   <td style="text-align:left;"> $SOFI we know CPI will be down. Fed pause oe no pause dpnt care we still doing very well $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:46:18 </td>
   <td style="text-align:left;"> $spy $qqq $ndx $NQ_F $nasdaq AI breached </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:45:57 </td>
   <td style="text-align:left;"> Or maybe it’s the CIA manipulating the futures $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:45:49 </td>
   <td style="text-align:left;"> $CVNA $TSLA $ADBE $SPY $QQQ my bags pre market 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:44:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:44:31 </td>
   <td style="text-align:left;"> Mixed Performance In US Futures As Investors Await Key Economic Reports $QQQ $DIA $SPX https://talkmarkets.com/content/us-markets/mixed-performance-in-us-futures-as-investors-await-key-economic-reports?post=398982 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:44:24 </td>
   <td style="text-align:left;"> The FBI probably manipulating futures too $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:43:40 </td>
   <td style="text-align:left;"> $QQQ CNBC calling it a mixed open. Its a downopen... except they are doing non-stop TSLA schilling lol dragging Qs irrationally 0.5% higher than the other indexes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:43:31 </td>
   <td style="text-align:left;"> $COIN DOWNGRADED to NEGATIVE by Moody&amp;#39;s might have an impact to bring it to the DOWNSIDE.  What is interesting that $SPY $QQQ $BTC.X DIA are all over the place in the last few hours. Let&amp;#39;s see the direction after the open as it could go either way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:42:41 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:41:48 </td>
   <td style="text-align:left;"> $SPY  $QQQ  -   Remember Kids, we don&amp;#39;t talk to strangers or get in vans with people who claim &amp;quot;we&amp;#39;re in a new bull market&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:41:10 </td>
   <td style="text-align:left;"> DIA $F $SPY $TSLA $GM $QQQ   CARS ON MARS ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:39:06 </td>
   <td style="text-align:left;"> $SPY  $QQQ   Happy Proud of Yahweh Month ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:38:08 </td>
   <td style="text-align:left;"> $QQQ lol now they have deepwater schill on to pump tsla even more. Just a constant pump, without any discussion of how this changes any dynamics regarding making money. 
 
The stock market is about companies making money. This does not change any underlying earnings or revenue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:37:37 </td>
   <td style="text-align:left;"> $QQQ $SPY isn’t this what the Fed (central banks) want in their fight against inflation?  🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:37:26 </td>
   <td style="text-align:left;"> $tsla Kathie Woods just gave Tesla the kiss of death 💋💀 $COIN $ARKK $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:36:51 </td>
   <td style="text-align:left;"> Give it to Mike z Wilson today $450 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:36:03 </td>
   <td style="text-align:left;"> $SPY Morgan Stanly being the biggest joke of them all $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:36:00 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:35:54 </td>
   <td style="text-align:left;"> $TSLA pump to 300 with your fake upgrade so massive dump happens. The wait for many shareholders tired of Felon Muskarat, thanks to GM and Ford takeover, is over! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:35:31 </td>
   <td style="text-align:left;"> In Group 3 Live Session today, we will also explain that the #Dollar has ended the bounce and will get sideways to lower in a Negative USD Dynamic. #Equities and #commodities should rally.  #Elliottwave #Stocks #Trading $SPY $SPX $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:34:51 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
LMAO 
Meme stocks are back! I guess Fed&amp;#39;s rate hikes did shit for anything. Inflation is naturally subsiding. However, it will spike back with vengeance, if Fed keeps adding secret liquidity because it is scared shitless with banking crisis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:34:07 </td>
   <td style="text-align:left;"> Big Bears 🐻 are a disgrace to Humanity $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:34:05 </td>
   <td style="text-align:left;"> $SPY $QQQ  with dxy about to tumble, the market is about to take off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:34:02 </td>
   <td style="text-align:left;"> $SPY $QQQ a preview of what’s coming globally. RISING UNEMPLOYMENT. ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:33:53 </td>
   <td style="text-align:left;"> $QQQ $SPY one more hour until bulls get rugged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:32:58 </td>
   <td style="text-align:left;"> $SPY $QQQ zero sells, only buys since Oct-Dec 2022... 
 
- Hedged when things looked rough. 
- Cashed those in when things looked better. 
- Trolled the dooomers on ST. 
 
That was the way. 
 
No need to change it, *even* if we get further pullbacks/consolidations... even corrections. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:32:52 </td>
   <td style="text-align:left;"> You Bears 🐻 are a disgrace to the Stock Race $SPY $QQQ $NDX   a disgrace! Flat out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:32:45 </td>
   <td style="text-align:left;"> $SPY $QQQ WSJ - The S&amp;amp;P 500 starts a new bull market. Outsize gains from a handful of companies, including Amazon, Tesla and Nvidia, helped power the S&amp;amp;P 500 higher over the past few months. Many of those same stocks led Thursday’s market advance, propelling the broad index up 0.6% and ending its longest bear market since the 1940s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:32:35 </td>
   <td style="text-align:left;"> What stocks might make more money? Pick the best $QQQ vs. $VCR vs. $VXUS. https://srnk.us/go/4713993 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:32:04 </td>
   <td style="text-align:left;"> $QQQ did you get a treat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:32:00 </td>
   <td style="text-align:left;"> $QQQ option holders are insufferable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:31:24 </td>
   <td style="text-align:left;"> Group 3 Live Session will start at 9AM. Tune in @ https://elliottwave-forecast.com/amember/go.php?r=34991&amp;amp;i=l1 where we will explain all the instruments and what should be happening next. #Elliottwave #Stocks #Trading $SPY $QQQ $TSLA $AAPL $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:31:16 </td>
   <td style="text-align:left;"> $QQQ I want to die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:31:15 </td>
   <td style="text-align:left;"> $QQQ pumped out more gains on a garage sale  LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:31:04 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY is now 429.3s. it so strong. AI Tech Rally and Banks Come Back help it a lot. SPY will drop 2-4 $ After the Open. $SOXL is now 22.75. I Shorts it for 22.5s avg and I have take +0.5 +1.2 in two days. I will have another +0.5-1. 1-2 Trading days. I had +0.4 yesterday and I did not Take  it bc I want at least +0.5. 
 
$SPY was 373.s 13 July at CPI I have Calls for 410+ for FOMC ER rally. SPY 410 FOMC and 431 at ER mid August. I calls later 400 in 1-3 weeks. 1st week 410 2nd week 400 3rd week 390. 13 oct 350 -1.5%. at 10h19 am I calls for a Close Green and 410+ in 4-6 weeks. SPY Close 365 +2.6% 13 dec CPI SPY 411.s. Icalls for Taxes Losses Selling 390-380. a week later 378 and I Calls for FOMC 400-405 etc.. Msgs Posted and Saves. 
 
Soon or Later SPY will Crash FED Rates  5.25%+  Always make market  Crash. AI Stocks have drop as I Predicted and Banks will be next aGain as I Predicted. 13 march Banks Crash and SPY 380. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:30:42 </td>
   <td style="text-align:left;"> $RIVN 

🔥40 REASONS TO BUY RIVIAN STOCK🔥

1. Amazon owns 20% of Rivian
2. Amazon Partnership
3. 100,000 Amazon Van Orders
4. R2 Vehicles
5. Amazon Buyout target
6. Already producing EV Truck &amp;amp; SUV
7. $12 Billion Cash
8. Motortrend Truck of the Year
9. Huge Growth Strategy
10. 100k+ R1 Orders
11. IL Factory=200K Vehicles
12. New Georgia Factory
13. New Factory=400K Vehicles
14. 50k Vehicles 2023
15. Improved Gross Profit
16. Enough Cash to 2026
17. 2024 Positive Gross Profit
18. Huge Backlog
19. Targets 25% GP
20. L3 Autonomy
21. EV Rebate
22. Executives from Tesla, Nissan etc.
23. EV Incentives
24. Undervalued
25. 10K+ Employees
26. Level 2 Autonomy standard
27. Manufactures Battery Pack
28. Delivery Subscription
29. Experienced Executives
30. Ford owns 1%
31. 1M EV’s by 2030
32. Blackrock Invested
33. Fidelity invested
34. Own Charging Infrastructure
35. Oversold
36. Fleet OS
37. R1T=Best Seller
38. Skateboard Chassis
39. 800HP Vehicles
40. Untapped EV Market

$SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:29:58 </td>
   <td style="text-align:left;"> These bears turned into complete losers $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:27:40 </td>
   <td style="text-align:left;"> $QQQ if the current pricing holds at the open the SOXX will have 3 gaps ..all decent size. There is no way that one down at 433 stays open.. so we have an idea of the target.. the million $$ question is when </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:27:33 </td>
   <td style="text-align:left;"> $SPY $QQQ smart money is going to cash out soon. Today could be a good day to do so before next weeks Fed meeting and CPI.  They used 7 big companies to take the markets out of the bear market.  Is it sustainable?. We will see.  See you at open. GLTA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:26:50 </td>
   <td style="text-align:left;"> $QQQ this small little pullback that just happened is about to go right back up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:26:36 </td>
   <td style="text-align:left;"> latexb3c6b8ea8c852354aad7a34c125cf8b9SPY ...$IWM next let&amp;#39;s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:26:11 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $NVDA 

I am posting less on Stocktwits! 

If u want to follow me I’m on Twitter @Banana3Stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:25:11 </td>
   <td style="text-align:left;"> $QQQ CNBC had cathie wood on to help pump nonsense --- now they cant stop showing the &amp;quot;highlights&amp;quot;. 
 
This is a person who took billions of dollars and made them burn and disappear. -300% returns in 24 months. Flat returns over 4 years. 
 
One trick pony who got lucky with free money era, and we still put her on tv lol. 
 
How will the charging stations increase margins for Tsla? If anything TSLA is making it more viable to lose more market share domestically. 
 
Some people are so bad at understanding underlying fundamentals. But I am very happy for your pumps, they dont last, enjoy while they do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:24:06 </td>
   <td style="text-align:left;"> $TSLA widespread use of EVs causes a phenomenon known as ion pollution leading to a shift in the electrical polarity of the earth. This shift in polarity can cause drastic changes in weather patterns and temperatures across the globe!  
$RIVN $NIO $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:21:34 </td>
   <td style="text-align:left;"> $QQQ tired of trading SPY it’s so lame, took a nice position here for more $$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:20:18 </td>
   <td style="text-align:left;"> $QQQ greatest ponzi schemes.  The greater fool is always there to keep buying , nothing will ever be corrected.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:20:18 </td>
   <td style="text-align:left;"> The Nasdaq $QQQ broke out several weeks ago. The S&amp;amp;P 500 $SPY broke out two weeks ago. Now it looks like the DJIA $DIA is headed in that direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:19:34 </td>
   <td style="text-align:left;"> Watchlist 6/9

$AAPL, $NVDA, $TSLA, $ADBE, SPX, $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:17:29 </td>
   <td style="text-align:left;"> $QQQ so we just go up everyday forever? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:16:55 </td>
   <td style="text-align:left;"> $QQQ looks very good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:16:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL  market is going to go parabolic, scary but deserved by the world&amp;#39;s tried and hardened bulls of the globe. Take a bow. You are believers in America. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:16:26 </td>
   <td style="text-align:left;"> $QQQ makes total sense, ticking up premarket nonstop until .50% gap open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:16:23 </td>
   <td style="text-align:left;"> $QQQ why god fucking dammit why 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:15:48 </td>
   <td style="text-align:left;"> $SPY $QQQ never been more bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:15:48 </td>
   <td style="text-align:left;"> $SPY $QQQ are they planning to dump the markets today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:15:10 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 282.9K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:14:10 </td>
   <td style="text-align:left;"> $QQQ Imagine buying TSLA up 150% with margins collapsing every quarter, revenues dying, expansions in china going horribly. 
 
Sure it has some FCF, but with a PE in nosebleeds, we like to call that dead money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:13:55 </td>
   <td style="text-align:left;"> How #Buybacks Came to Drive the Stock Market

https://www.bloomberg.com/news/articles/2023-06-08/how-stock-buybacks-came-to-drive-the-stock-market-quicktake?srnd=markets-vp
#ceo #compensation #governance #investments $qqq $spx $

https://twitter.com/mohossain/status/1667141906512457728?s=46&amp;amp;t=GtuOmoaTjOwevz2JidiiDQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:13:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK $META . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:10:58 </td>
   <td style="text-align:left;"> $TSLA $QQQ $ARKK $FNGU $ARKF Cathie&amp;#39;s 24month performance on ARK is a tasty -300%. give her billions boys! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:10:35 </td>
   <td style="text-align:left;"> $QQQ $SPY free money day is here!! No downside risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:10:25 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  do all  nvidia bulls feel safe relying on TSMC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:09:47 </td>
   <td style="text-align:left;"> $QQQ never ending pump what could ever go wrong 😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:09:13 </td>
   <td style="text-align:left;"> $TSLA $ARKK $ARKF $QQQ $FNGU Cathie Wood entered her office today 🤑💎😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:08:22 </td>
   <td style="text-align:left;"> $NIO $QQQ $SPX $SPY 

And shorts already blasted. They don’t learn 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:08:03 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:07:49 </td>
   <td style="text-align:left;"> $QQQ More stupidity that most people thinks the FED needs to pause or cut. Really with this nonstop bullshit mania, nothing has been corrected, if anything need to be raising 100bps each meeting! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:07:37 </td>
   <td style="text-align:left;"> Feels like there’s a hedge fund going broke today on a massive short squeeze break out $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:05:58 </td>
   <td style="text-align:left;"> $4750  $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 22:02:52 </td>
   <td style="text-align:left;"> $AAPL we&amp;#39;ve gone past resistance twice and got smacked back down. The third times the charm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 22:00:06 </td>
   <td style="text-align:left;"> $SPY The Biden Market just hit a new high on the day Trump gets indicted on the thing he claimed Hillary did. 
 
You can&amp;#39;t make this stuff up! :o) 
 
$dwac $aapl $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:59:21 </td>
   <td style="text-align:left;"> ‘We’ve Never Seen Anything Like This in VR’, Says The Sandbox ... $AAPL
► https://decrypt.co/videos/live-events/GQ29RaHw/weve-never-seen-an </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:59:12 </td>
   <td style="text-align:left;"> $AAPL sell now guys. sell!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:59:03 </td>
   <td style="text-align:left;"> $AAPL  new branches?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:58:56 </td>
   <td style="text-align:left;"> $JETS 🛫 takeoff $SPY $AAPL $PLUG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:58:53 </td>
   <td style="text-align:left;"> $ROKU $TSLA $NFLX $AAPL - Pending long trade on ROKU 
&amp;gt;$74.23 else avoid the session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:58:28 </td>
   <td style="text-align:left;"> $AAPL oof not good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:57:29 </td>
   <td style="text-align:left;"> $QQQ $AAPL dragging this down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:56:29 </td>
   <td style="text-align:left;"> $AAPL watch it pump again , money is that easy 😂. Can’t scare me.. I won’t sell my calls $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:55:51 </td>
   <td style="text-align:left;"> $AAPL absolutely gorgeous setup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:55:20 </td>
   <td style="text-align:left;"> @WKHSguyUSA  Then work deal out with $AAPL  to sell factory/partner w/ them.  $AAPL would LOVE to have one of the top 5 largest auto factories in the U.S. for sure.  Lease it back to whomever their builder is.  I LOVE THIS IDEA.  $RIDE $AAPL  
 
Maybe $TSLA and Elon should initiate a quick conversation with LMC leadership IF &amp;quot;clawing back&amp;quot; the factory is on the table.   
 
$GME $AMC  crew....look at our float now after reverse 15:1 split.  Maybe it&amp;#39;s time to make lemonade outta lemons finally.  Ford and friends tried to destroy LMC imo w/ their cronies from GSCO (walled us in for over a year on Lev II it shows), Cramer, CNBC, TheStreet and banks that own Ford debt.  It&amp;#39;s time to fight back and 16 million shares only in float!  (some other EV stocks have a BILLION shares and ones like Fisker have over 300 million.. $RIDE 16 milly only...) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:55:10 </td>
   <td style="text-align:left;"> $u Accumulate Unity Software Inc for future $aapl VR... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:54:27 </td>
   <td style="text-align:left;"> $FFIE perfect time to buy,  buy $100 worth of shares here and by next year you&amp;#39;ll have your $AAPL vision pro fund!!! $TSLA $PLTR $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:54:03 </td>
   <td style="text-align:left;"> $AAPL hey android idiots......AAPL WON AGAIN!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:53:55 </td>
   <td style="text-align:left;"> $spy Market seems to like  Trump getting indicated,..  
 
Breaking Video: FBI asking Trump to give the Documents back &amp;amp; his response 
 
https://www.youtube.com/watch?v=RKMNPQ35OUc 
 
$aapl $dwac $rum $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:53:46 </td>
   <td style="text-align:left;"> @Tikto and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:53:28 </td>
   <td style="text-align:left;"> $AAPL aapl so easy just buy calls and make $ . Didn’t sell my 190 contracts yet.. noobs love to buy 🤣. Just sit and let them push , easy $ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:53:15 </td>
   <td style="text-align:left;"> $ZM $TSLA $NFLX $AAPL - Pending long trade on Zoom 
&amp;gt;$68.84 else avoid the session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:52:29 </td>
   <td style="text-align:left;"> $AAPL new highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:52:10 </td>
   <td style="text-align:left;"> $AAPL Yeesh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:52:02 </td>
   <td style="text-align:left;"> $AAPL $NFLX $NVDA $SPY $TSLA  
 
This is funny af. I don&amp;#39;t give a shit if its making fun of me. Can only laugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:51:40 </td>
   <td style="text-align:left;"> $AAPL any reason Wall Street is giving us easy money??? lol $$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:51:22 </td>
   <td style="text-align:left;"> $AAPL insanity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:50:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX $AAPL $NVDA  
 
bearvastation: devastation beyond compare... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:49:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Markets literally have no where to go but up!!! 📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:47:07 </td>
   <td style="text-align:left;"> $SPY $AAPL just genuinely curious as to why Apple is up 40 this year that&amp;#39;s a staggering number in just 6 months time for a almost 3 trillion company what a beauty eh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:46:35 </td>
   <td style="text-align:left;"> $AAPL  sharks are selling second leg. AAPL will go down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:46:31 </td>
   <td style="text-align:left;"> Laggered names for the week on tech ripping ww them all $ORCL $SHOP $AAPL $MSFT etc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:45:43 </td>
   <td style="text-align:left;"> $AAPL  come on push bull, stupid fools. I’m trying to sell .. push up and take my contracts WTH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:44:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

tried warning bears not to bet against cnbc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:44:19 </td>
   <td style="text-align:left;"> $AAPL $MSFT $QQQ $SPX $SPY spx over my resistance of 4307! Looks like a meltup in progress! Pretty broad based rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:44:06 </td>
   <td style="text-align:left;"> $RIDE   Stocktwits sure seems anti-RIDE.  Paid &amp;quot;news&amp;quot; on the right is negative usually.  Weird charting and whatnot.  Letting Bears w/ MANY accounts bash share price when they are obviously short (short and distort is illegal).   Seems like a HUGE class action lawsuit against Stocktwits would be viable due to so many microcaps getting attacked by sentiment negative farming as they are shorted down.  $GME $AMC $TSLA $AAPL  p.s.  Our float is only 16 million for an EV company w/ a product ready to produce that was finalist for TRUCK OF THE YEAR recently.   
 
Maybe join $RIDE w/ a long starter position?  Foxconn is trying to bully LMC and they are fighting back...FINALLY.  Help a small EV company in Ohio fight back.   FTD&amp;#39;s every day for 2 years.  Short % each day OVER 50% for years.  The attack almost worked...but now insane value play and very squeezy.   
 
Do your own DD, buuuuut..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:43:49 </td>
   <td style="text-align:left;"> @SeNSF $SPY max pain is a bogus zero math internet fake topic. 
 
Learn more  
 
$QQQ $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:43:40 </td>
   <td style="text-align:left;"> $AAPL $MSFT +2-3% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:43:38 </td>
   <td style="text-align:left;"> $TSLA $AAPL 
Never ever chase a bull trap in a bear market! 
Believe me thats the worst mistake! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:43:17 </td>
   <td style="text-align:left;"> $AAPL who wants my 190 contracts? Push up and I sell to someone . Is that easy come on 🤦‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:43:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

cnbc &amp;gt; bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:42:58 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ  
Lmfao 🤣🤣🤣🤣💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:42:31 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $QQQ $SPY fomo fomo… faster and furious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:42:22 </td>
   <td style="text-align:left;"> $AAPL this is what inflation did, it’s not reflected everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:42:15 </td>
   <td style="text-align:left;"> $AAPL leggooo $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:42:13 </td>
   <td style="text-align:left;"> $AAPL go up so I can sell. Wtf? When u set a limit sell.. the stock wanna drop .. manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:42:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ 

BEARS ABOUT TO GET DOWNGRADED BY CNBC 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:41:49 </td>
   <td style="text-align:left;"> $BLX $SPY $JPM $AAPL 

Great report on Bladex. So much upside for a really strong bank 🏦 🚀

https://www.linkedin.com/feed/update/urn:li:activity:7072574762136268800?utm_source=share&amp;amp;utm_medium=member_ios </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:40:56 </td>
   <td style="text-align:left;"> $AAPL $UBER Have a Great Weekend Bulls 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:40:43 </td>
   <td style="text-align:left;"> $AAPL it should go back up I will sell once it goes up. Easy $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:39:45 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;ll buy back in at 150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:39:06 </td>
   <td style="text-align:left;"> $TSLA Today&amp;#39;s Max Pain @ 222.5. Bulls need 251.5 Breakout. Bears need 246 Breakdown. $SPY $QQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:38:43 </td>
   <td style="text-align:left;"> $AAPL should I sell my calls? I’m up almost 100% lmao. Didn’t think it be so easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:37:50 </td>
   <td style="text-align:left;"> $AAPL buy this dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:36:36 </td>
   <td style="text-align:left;"> $SPY So which PM&amp;#39;s are going to front run next weeks drop &amp;amp; start Selling today? 
lets watch &amp;amp; find out 
 
$aapl $tlsa $nvda $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:36:06 </td>
   <td style="text-align:left;"> $AAPL Today&amp;#39;s Max Pain @ 177.5. Bulls need 182.3 Breakout. Bears need 180.7 Breakdown. $SPY $QQQ $UVXY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:34:24 </td>
   <td style="text-align:left;"> $QQQ Today&amp;#39;s Max Pain @ 350. Bulls need 356 Breakout. Bears need 353.5 Breakdown. $SPY $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:33:53 </td>
   <td style="text-align:left;"> $AAPL finally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:33:37 </td>
   <td style="text-align:left;"> $AAPL Blink 182 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:31:53 </td>
   <td style="text-align:left;"> $SPY Today&amp;#39;s Max Pain @ 425. Bulls need 431 Breakout. Bears need 429 Breakdown. $QQQ $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:30:58 </td>
   <td style="text-align:left;"> $QQQ $SPY Usually not a fan of Casey but he really nailed it here, $AAPL anyways enjoy your Dystopian Future Bulls I&amp;#39;m sure this all ends well https://www.youtube.com/watch?v=UVX6kxnJgMU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:30:52 </td>
   <td style="text-align:left;"> $AAPL $AMZN $NVDA $MSFT $GOOG  
There it is SPY 4300+  
 
Market closes @ or above 4300 &amp;amp; with Powell likely pausing SPY 4600 with the help of a nice fat &amp;quot;short squeeze&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:30:30 </td>
   <td style="text-align:left;"> $VUZI upside on pps here is major. It’s way undervalued. Big tech $AAPL $META &amp;amp; $MSFT have spent billions, 10s of billions of real $’s &amp;amp; Vuzix still has edge on fashion form factor, AR expertise, devices to market, 1st mover advantage, etc. 
300m? Market Cap can turn into 5x very quickly &amp;amp; it’s warranted given the AR IP race
It’s $TSLA of AR
Super </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:29:07 </td>
   <td style="text-align:left;"> $RIDE    Time for DOJ and SEC to investigate Foxconn I guess.  Share price manipulation, bad faith negotiating and attacking microcap EV in Ohio. 
 
Can LMC take factory back?  Seems all tied together with this contract.  Time to tie up the factory, make a deal with $AAPL  to sell THEM the factory and lease it back to Foxconn to build the Apple ICar.  Foxconn will come crawling to AAPL tail between legs to get ICar contract.  Win for everyone.   
 
If not, Elon is a great option b/c doesn&amp;#39;t overlap and LMC and Elon BOTH would benefit against Ford on the consumer AND the commercial side that way.  Win-Win again. 
 
Foxconn has a small window to save faith no matter what happens at this point.  YES, it may kill LMC in the process, but Foxconn is not looking good for their new EV business in U.S.. ...unless they just do tractors. 
 
I liked Jack b/c of his karaoke fun too.  Not the man/company I had thought they were I guess.  It was all lies? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:28:49 </td>
   <td style="text-align:left;"> $AAPL going to be nice profit at open $$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:28:25 </td>
   <td style="text-align:left;"> $AAPL $MSFT $DIA $SPY $QQQ The Canadian labour market finally faltered in May, shedding 17,300 jobs to post the first decline since last August. That missed expectations for a gain of 21,300 jobs, though it is worth noting that there’s a reasonably significant confidence interval to these numbers, so that spread isn’t quite as wide as it seems at first glance. The unemployment rate rose 0.2 per cent to 5.2 per cent – also the first increase since August – but it’s the composition to things that catches the eye: employment among youth aged 15-24 fell by 77,000 positions, offsetting gains for older workers. In any case, that 17,300 drop doesn’t even offset the gains we saw in April, so it’s not as if the sky is falling on the labour market, and the Bank of Canada will likely need a whole lot more evidence that its policies are cooling the labour market before changing its tune.    https://www.bnnbloomberg.ca/?lid=l4d9fyn7fg2r </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:27:07 </td>
   <td style="text-align:left;"> $AAPL 183 EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:26:02 </td>
   <td style="text-align:left;"> $aapl

very long term, yea. short term, you know what this means haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:25:28 </td>
   <td style="text-align:left;"> $AAPL I’m a buyer for 1 week Tim </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:25:05 </td>
   <td style="text-align:left;"> $AAPL Slow growth, no innovation, you want to beat $TSLA to $200 today? Lol, spike under $180 after market open.  This afternoon big sell off, no ppl wants hold it over Fed meeting.  It’s on the peak! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:24:51 </td>
   <td style="text-align:left;"> $SPY $AMD $TSLA $NVDA $AAPL we can’t lose, we’ll go up forever!!!! Hahahahahaha! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:24:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $NVDA $MSTR $AAPL they are going to send it straight down 5 mins afte open watch this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:24:37 </td>
   <td style="text-align:left;"> June 9, 2023 
$SPY $428 to $429.50. Over $429.50 to $430.50-$431.50-$432. Under $428 to $426.70-$426 
  
$AAPL $179.50 to $181. Over $181 to $181.80-$183. Under $179.50 to $178.30-$177.50 
  
$BA $217 to $219. Over $219 to $221.50-$223.50-$224.50. Under $216.70 to $213.50-212 
  
$NFLX $415 to $418.50-$420. Over $420 to $425-$427-$430-$432. Under $415 to $410-$406 
  
$NVDA $388.50 to $391. Over $391 to $396-$398-$400. Under $388 to $384-$383 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:23:39 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:23:07 </td>
   <td style="text-align:left;"> KeyBanc survey data indicates weaker Apple $AAPL iPhone sales in May 
 
https://www.streetinsider.com/Analyst+Comments/KeyBanc+survey+data+indicates+weaker+Apple+%28AAPL%29+iPhone+sales+in+May/21781659.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:22:27 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:21:50 </td>
   <td style="text-align:left;"> $AAPL our $180 calls June 16 would sure go above 100% today ..said it before that $200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:21:30 </td>
   <td style="text-align:left;"> $AAPL Drop at op3n </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:21:10 </td>
   <td style="text-align:left;"> SIDE WATCHLIST: $TSLA , $AAPL , $META(weakness only on a market reversal) 
 
/NQ - $NASDAQ (legendstrading.com) 
Bull: 14525 bounce -&amp;gt; 14600 
Bear: 14600 rejection -&amp;gt; 14500 
 
/ES - $SPY (legendstrading.com) 
Bull: 4300 bounce -&amp;gt; 4305.75 -&amp;gt; 4327.5 -&amp;gt; 4400 
Bear: 4305.75 rejection -&amp;gt; 4300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:20:36 </td>
   <td style="text-align:left;"> $AAPL Crazy Wall Street, easy money $$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:19:11 </td>
   <td style="text-align:left;"> $AAPL printing HOD.... Love it. Am I too gready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:17:36 </td>
   <td style="text-align:left;"> $SPY $TSLS $AAPL $QQQ 

I’m guessing trumps puts expired worthless????…. 🥸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:14:39 </td>
   <td style="text-align:left;"> $AAPL Sticker Shock seems to be fading🤷🏼‍♂️ but getting over $183 will be a challenge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:07:20 </td>
   <td style="text-align:left;"> STUPID FED GOONS IN 🇨🇦 RAISING INTEREST RATES .25% THIS WEEK POST TODAY&amp;#39;S EMPLOYMENT REPORT RELEASED MOMENTS AGO @ https://global-premium.econoday.com/byshoweventfull.aspx?fid=570778&amp;amp;cust=global-premium&amp;amp;year=2023&amp;amp;lid=0&amp;amp;prev=/byweek.asp#top #TRUDEAUSUCKS $DIA $SPY $QQQ $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:05:24 </td>
   <td style="text-align:left;"> $AAPL VR head set is going to be a nice $3000 stocking stuffer this Christmas.  Credit Card debt is surging, Visa and Mastercard report that people aren&amp;#39;t paying them off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:03:10 </td>
   <td style="text-align:left;"> $WLDS It&amp;#39;s happening..Broke 2.40 and she&amp;#39;s going hard..815% ctb with 10k shares.
Shorts are trapped..Lets GO.
$AAPL $MSFT $MULN $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:02:49 </td>
   <td style="text-align:left;"> $SPY $META $AAPL this looks like something that astronauts would wear, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:02:32 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $tsla read @pnvoss recent posts. Relax, trust the process, give your self time to make your money back. Relax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:00:37 </td>
   <td style="text-align:left;"> $AAPL $googl $amzn $tsla $bntx 
 
https://www.twitch.tv/videos/1841749838?t=00h00m05s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 21:00:30 </td>
   <td style="text-align:left;"> $AAPL TOI and AI teaming up to battle cancer 😎😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:57:41 </td>
   <td style="text-align:left;"> HAMMER GOLD ❗❗❗
CANADA LOSES 17.3K JOBS IN MAY; UNEMPLOYMENT RISES TO 5.2% FROM 5.0%
$TSLA $AAPL $AMZN $NVDA $AMD  dbbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:55:20 </td>
   <td style="text-align:left;"> $AAPL is apple going to develop ai for there stuff? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:53:40 </td>
   <td style="text-align:left;"> $META $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:51:56 </td>
   <td style="text-align:left;"> $SIEN check this fda clearance 
$BOIL $AAPL $MSFT $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:47:23 </td>
   <td style="text-align:left;"> $QCOM  Seems they “kitchen sinked” their earnings announcement last month.  The stock had already been beaten up, then was kicked while it was down.  Expectations were lowered.  I think there’s more risk in not owning it than there is in owning it.  I sold some $AAPL on May 5 and added to QCOM at $108.  QCOM has outperformed AAPL since then and I think it will continue to do so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:46:44 </td>
   <td style="text-align:left;"> $AAPL $LCID $aapl $lcid a flashlight 🔦?  makes sense, since peter is in the dark about how to run a business… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:46:30 </td>
   <td style="text-align:left;"> $AAPL    
Calls:     
📈  at $179.70 - $179 
📈 above $181 
Puts:    
📉  at $184 - $184.95 if we get rejected  
  
Let the setup come to you!  
Manage risk properly! cut losses quickly! And always take profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:45:31 </td>
   <td style="text-align:left;"> $WLDS  $AAPL $MSFT $SPY 
It&amp;#39;s getting hot..jump in before it&amp;#39;s to late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:44:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:44:07 </td>
   <td style="text-align:left;"> $LCID What do you see on right side of Peter hand $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:44:02 </td>
   <td style="text-align:left;"> $TSLA map update: we&amp;#39;re just shy 10 points of my ultimate target on news today.  Only I was way off on the timing.  Wow. 
 
Underlining my thesis that Tesla is now THE market leader, replacing $AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:43:39 </td>
   <td style="text-align:left;"> My Option Watchlist For 06/09/2023   
  
$AAPL    
Calls:     
📈  at $179.70 - $179 
📈 above $181 
Puts:    
📉  at $184 - $184.95 if we get rejected  
  
$SPY    
Calls:   
📈  1st at $428.22 - $427.70 
📈  2nd at $426.70 - $426 
Puts:   
📉 below $425.99  
 
  
$TSLA    
 Calls:    
📈 at $245 - $243  
Puts:   
📉  below $241 
   
Let the setup come to you!  
Manage risk properly! cut losses quickly! And always take profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:42:41 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:42:07 </td>
   <td style="text-align:left;"> $nvda AI already breached and in trouble. $googl $aapl $tsla $nflx 🫧📌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:39:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL $GOOG Our Long Watchlist of plays we alerted 3/12 is KILLING IT…
It’s what we do 🤷🏼‍♂️😎
Ready for our release? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:38:08 </td>
   <td style="text-align:left;"> IT IS OFFICIAL! The longest bear market since the 40&amp;#39;s has come to a conclusion for now. Most of the gains have been from big tech like $AAPL $NVDA and $TSLA. 
 
Tesla is going crazy this morning after closing another charging station deal, this time with $GM.  
 
META is trying to make a platform to compete with twitter, saying that creators have asked for a version of twitter that is &amp;quot;sanely run&amp;quot; which is a little ridiculous considering all the Meta employees probably drive teslas. They want to do the platform on instagram and make it just like twitter. I will not be particpating.  
 
CVNA had a big day yesterday, rising 51% after their profit outlook improved. Pretty flat trading premarket, but that could be a fun one to trade today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:37:31 </td>
   <td style="text-align:left;"> $AAPL TOI going to use AI to go after cancer 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:35:31 </td>
   <td style="text-align:left;"> In Group 3 Live Session today, we will also explain that the #Dollar has ended the bounce and will get sideways to lower in a Negative USD Dynamic. #Equities and #commodities should rally.  #Elliottwave #Stocks #Trading $SPY $SPX $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:33:11 </td>
   <td style="text-align:left;"> $AAPL Use AI to increase your stock portfolio  https://youtu.be/9wFufMFG5fE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:31:24 </td>
   <td style="text-align:left;"> Group 3 Live Session will start at 9AM. Tune in @ https://elliottwave-forecast.com/amember/go.php?r=34991&amp;amp;i=l1 where we will explain all the instruments and what should be happening next. #Elliottwave #Stocks #Trading $SPY $QQQ $TSLA $AAPL $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:30:36 </td>
   <td style="text-align:left;"> $AAPL $185 today or $190 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:19:34 </td>
   <td style="text-align:left;"> Watchlist 6/9

$AAPL, $NVDA, $TSLA, $ADBE, SPX, $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:16:53 </td>
   <td style="text-align:left;"> $PLTR $AMZN $MSFT $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:16:40 </td>
   <td style="text-align:left;"> $PLTR @Pocoyo $f $tsla $aapl $docu over  $1 billion  in  sales  this  week!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:16:35 </td>
   <td style="text-align:left;"> $AAPL wants 200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:16:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL  market is going to go parabolic, scary but deserved by the world&amp;#39;s tried and hardened bulls of the globe. Take a bow. You are believers in America. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:14:12 </td>
   <td style="text-align:left;"> $PLTR  &amp;lt;- this will be the runner of the day $TSLA $NIO $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:12:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 28.40%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:11:29 </td>
   <td style="text-align:left;"> $AAPL since you dropped &amp;quot;i&amp;quot; for vision pro. Vision pro is individual experience.  Why have you dropped it?  Also price tag is expensive and users are going to be stationary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:07:52 </td>
   <td style="text-align:left;"> $PLTR quick  summary  of  over  $1 billion  in  sales  this  week!!!    $tsla battery  maker  $pc aka  Panasonic!!!   $msft $AAPL @Pocoyo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:04:46 </td>
   <td style="text-align:left;"> $AAPL $SOFI 

👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:04:10 </td>
   <td style="text-align:left;"> $AAPL more magical delays $META $MSFT https://seekingalpha.com/article/4610418-apple-magical-delays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:01:12 </td>
   <td style="text-align:left;"> 🛑*PUTIN: RUSSIA TO PLACE NUKE WEAPONS IN BELARUS AFTER JULY 7-8❗
https://twitter.com/PaulVikingGlob1/status/1667135168002260992?t=e3fQ2lRL9nuqVgfvBAAb2A&amp;amp;s=19
$TSLA $AAPL $AMZN $NVDA $AMD  VSVZV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 20:00:20 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The Fintech Industry Will Be Worth $1.5 Trillion By 2030: 2 Magnificent Stocks to Buy Now https://www.stck.pro/news/AAPL/52580305/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:57:14 </td>
   <td style="text-align:left;"> $AAPL $META 

Already printing 🩸🩸🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:56:41 </td>
   <td style="text-align:left;"> $AAPL let&amp;#39;s hear the bull case vs bear case </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:55:19 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT $GOOGL $TSLA watch this for motivation.

WHY YOU SHOULD NEVER QUIT - Denzel Washington Motivational Speech 2023
https://youtu.be/RBltxXaxgXI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:52:41 </td>
   <td style="text-align:left;"> $META (-0.6% pre) Meta Reveals Twitter Competitor It Plans to Launch as Stand-Alone App - WSJ

Zuckerberg criticizes $AAPL Apple’s Vision Pro headset, saying Meta has tried to make products affordable

https://openoutcrier.com/l/1686311553377408 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:45:49 </td>
   <td style="text-align:left;"> $META $AAPL Meta&amp;#39;s Zuckerberg addresses Apple&amp;#39;s Vision Pro at meeting, The Verge reports 
 
Meta CEO Mark Zuckerberg addressed Apple&amp;#39;s Vision Pro headset at a meeting on Thursday, telling employees that it &amp;quot;could be the vision of the future of computing, but like, it&amp;#39;s not the one that I want,&amp;quot; The Verge&amp;#39;s Alex Heath reports. He also pointed to the fact that Meta&amp;#39;s upcoming Quest 3 headset will be much cheaper, at $499 compared to the Vision Pro&amp;#39;s $3,499 price tag, saying that &amp;quot;I think that their announcement really showcases the difference in the values and the vision that our companies bring to this in a way that I think is really important.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:45:24 </td>
   <td style="text-align:left;"> $AAPL time for this to run back up and hold gains like Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:40:58 </td>
   <td style="text-align:left;"> $META $AAPL 

Ok, Zuckerberg....

I suppose you envisioned all of us standing in the kitchen.

Not the couch! That would be a VR crime, lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:38:45 </td>
   <td style="text-align:left;"> My alerts for LARGE caps.This shows the result of ONLY buying when H% is low.
I have timestamps + buy fills for everything

$TSLA + $AAPL + $NKE are just few of many I&amp;#39;ve traded. $SPY 
I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:37:21 </td>
   <td style="text-align:left;"> $AAPL time to step up apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:36:36 </td>
   <td style="text-align:left;"> $TSLA the new $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:32:00 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - 3 Semiconductor Stocks That Could Skyrocket in the Next 12 Months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:28:51 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #5 stock that institutions are trading with 41.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:25:16 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $SOXS &amp;quot;JP Morgan&amp;quot; is talking down markets, just as &amp;quot;Morgan Stanley&amp;quot; is. All about the disconnect beween the Bond&amp;amp; Equities. &amp;quot;If stock markets trade, as bond markets, the result will be -20%&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:21:05 </td>
   <td style="text-align:left;"> $AAPL enters bullish trend https://srnk.us/go/4713757 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:18:44 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple, AI, Metaverse: Meta&amp;#39;s Identity Crisis Is Getting Worse Not Better. https://www.stck.pro/news/AAPL/52579783/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:17:23 </td>
   <td style="text-align:left;"> $AAPL 🆘just look at that 6 month graph of sweet price!!🆘
u short sellers/shorting entities etc are idiots ..
300 shares bought in 1987 are now 67,000 due to splits
12,060,000 bucks now
young folks should buy n hold …dividends are nice as well🏌️‍♂️⛳️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:12:01 </td>
   <td style="text-align:left;"> $AAPL 👁💚🍏⛳️🏌️‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:10:45 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$LCID vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:06:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 19:00:49 </td>
   <td style="text-align:left;"> 3 Mid Caps You Haven&amp;#39;t Heard Of But Need To Know About $AAPL https://www.marketbeat.com/originals/3-mid-caps-you-havent-heard-of-but-need-t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 18:40:13 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 18:24:39 </td>
   <td style="text-align:left;"> $AAPL $META  latexed2b778936329e84cd326f912790bbcd$ success, $$ privilege = running over inferior humans. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 18:14:07 </td>
   <td style="text-align:left;"> $AAPL under 80 coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:58:45 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : NVDA to META: Insiders Capitalise on Tech Stocks Surge https://www.stck.pro/news/AAPL/52573454/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:54:48 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:50:52 </td>
   <td style="text-align:left;"> $AAPL Green or Red today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:45:33 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #5 ticker with sweep activity where institutions are trading options urgently with 29.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:42:51 </td>
   <td style="text-align:left;"> DIA DIS SPY QQQ $aapl  ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:34:46 </td>
   <td style="text-align:left;"> My track record for CHIP stocks. I have timestamps + buy fills for everything. What&amp;#39;s my win rate? 

My trading strategy is to buy the dip when Algos are tired of selling. I buy when &amp;quot;Heaviness %&amp;quot; by Algos is low. 

$NVDA + $AMD + $QCOM + $MU + $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:10:00 </td>
   <td style="text-align:left;"> The industry average Profit Margin is 8.03%. $AAPL outperforms 93% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:04:01 </td>
   <td style="text-align:left;"> $AAPL vision pro bullshit price and ugly gimmick . Shorting PT 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 17:03:38 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;#39;s Face Computer, Crypto Chaos and How Teens Really Feel About Social Media https://www.stck.pro/news/AAPL/52570055/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:55:50 </td>
   <td style="text-align:left;"> $DOCU standouts , why it caters to non corporate mainly small to medium size businesses that can&amp;#39;t afford the hefty SUB cost by$msft $AAPL $ADBE .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:46:42 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:44:24 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:27:08 </td>
   <td style="text-align:left;"> $AAPL $SPYD $QQQ $NVDA $IWM Inspite of the hype and exaggeration, markets are headed lower on &amp;quot;Hard Landing&amp;quot;. Do remember, the &amp;quot;shit hitting the fan&amp;quot; will be sudden and the draw down will be fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:22:17 </td>
   <td style="text-align:left;"> $aapl $dis $TSLA $F $wmt and more Excellent, welcome to crash Friday.  
Enjoy the Armageddon Autogeddon Recession.  
🐻❤😈💲💰🤑✔ 
TOP 10 AT: ▪TRADING ECONOMICS tradingeconomics.com ▪REUTERS U.S. MORNING BID ▪ WSJ MARKETS A.M. ▪WSJ REAL TIME ECONOMICS ▪YAHOO FINANCE MORNING BRIEF ▪JOHN KEMP ENERGY jkempenergy.com/ + REUTERS: Oil prices looked set to post their second straight weekly loss as prices continued to fall over demand concerns and skepticism that the United States and Iran could strike a nuclear deal. ▪TODAY&amp;#39;S WSJ PRINT EDITION 
https://wsjtodaysedition.cmail19.com/t/d-e-vblhjk-judrvtlm-r/   ▪CNBC DAILY OPEN 
https://link.cnbc.com/public/31739636  
▪CNBC BEYOND THE VALLEY 
https://link.cnbc.com/public/31739634   
▪REUTERS EU MORNING BID 
https://newslink.reuters.com/public/31739605  ▪TODAY&amp;#39;S WSJ HEADLINES 
https://intodayspaper.cmail20.com/t/d-e-vbljg-jidrghyo-r/  
▪FUTURES https://www.investing.com/indices/indices-futures 
▪FINVIZ https://finviz.com/news.ashx#  
▪🇨🇦 forest fire update @ https://ca.news.yahoo.com/wildfires-canada-south-africa-edmonton-airport-firefighters-040321703.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 16:21:22 </td>
   <td style="text-align:left;"> $AAPL average is at 155 why would you purchase at 180???? $VIX also prepared explode up around 18-19, Apple will get sledge hammered lower when that happens, Apple worth 160 if that happens (closer with the average) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:51:17 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Meta&amp;#39;s Zuckerberg shakes off Apple Vision Pro: report https://www.stck.pro/news/AAPL/52564995/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:50:27 </td>
   <td style="text-align:left;"> $AAPL 174 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:39:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:18:34 </td>
   <td style="text-align:left;"> $AAPL $META the more I read about visionpro, the more i want one. 
 
...zucks lost this one imo,.. even before it&amp;#39;s available. 
 
(Both stonks will likely do well regardless). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:16:37 </td>
   <td style="text-align:left;"> Result of ONLY buying when H% is low. Small + Mid cap edition.

$SPY $TSLA $AAPL $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 15:07:12 </td>
   <td style="text-align:left;"> 20 mins YouTube Stock Market Technical Analysis:                                              
https://youtu.be/R_76OIZzEzU 
Subscribe on YouTube for daily market updates &amp;amp; plays 
 
- Tesla Stock TSLA CLEAR 12 EMA 4 hour time frame support guide 
- Nvidia Stock NVDA falling Wedge Guide 
- google Stock GOOGL Lead Bear of big tech bull break with no follow through on Monday 
- Amazon Stock AMZN potential setting a lower high on daily. 
- Apple Stock AAPL stronger big tech 2 day time frame EMA 12 perfect support guide 
$AAPL $AMZN $MSFT $META $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:33:48 </td>
   <td style="text-align:left;"> $AAPL $NVDA $QQQ i&amp;#39;m in tech and don&amp;#39;t believe a word these companies are saying. 
 
Y2K all over again. 
 
RIP Google Glass AI 2.0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:21:23 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The “Magnificent 7” – mega-tech stocks that led the market higher https://www.stck.pro/news/AAPL/52559221/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:20:36 </td>
   <td style="text-align:left;"> @J0hnCandleW1ck yes on $tsla put are worthless

Not $meta 
. Puts very much alive 

Sell meta buy tsla or $aapl 

Meta is promoting pedo network ewwww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:06:35 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:01:30 </td>
   <td style="text-align:left;"> $TSLA puts are worthless now 

$spy $aapl $meta $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 14:00:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $NVDA $TSLA 

How tf is NQ1 already up 1.20% since last closing?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:58:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:40:39 </td>
   <td style="text-align:left;"> $CVNA FED will ease by end of year! 
https://truflation.com/ 
Carvana will be $180 by that time and $360+ in next year! 
$AMZN $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:34:13 </td>
   <td style="text-align:left;"> $AAPL $AHI 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:32:49 </td>
   <td style="text-align:left;"> $AMC and $AAPL should engage in a joint venture and offer all of AMC&amp;#39;s movie content on the Apple ProVision headset. This way, AMC can save billions of USD on physical theaters. As for AMC&amp;#39;s profitable popcorn sales, they can utilize Doordash for the delivery of beverages and snacks (including popcorn). By taking these steps, the company should become profitable in less than two years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:29:14 </td>
   <td style="text-align:left;"> $spy $aapl $nvda $meta $goog

Yup!!!

https://www.cnbc.com/2023/06/09/ubs-strategist-theres-too-much-risk-in-big-tech-right-now-heres-where-to-invest-instead.html?__source=androidappshare

Sector rotation is coming... Many sold faang stock and buying other sectors..m

Beware for those still holding, take profit and buy at lower price... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 13:20:41 </td>
   <td style="text-align:left;"> SweepCast ⚡ Unusual Options Detected: $AAPL with Unusual Options Activity Alerted on $185 CALL Expiring: 12-15-2023 worth 69K🐂 |🥇 Start Using SweepCast! @SweepCast  🥇 | </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:55:09 </td>
   <td style="text-align:left;"> $AAPL still holding 25yrs later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:25:06 </td>
   <td style="text-align:left;"> $TSLA 👈 Tesla to make 25 Billion alone in super charging revenues. $SPY $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:23:01 </td>
   <td style="text-align:left;"> $AAPL Hard to be bullish here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:20:44 </td>
   <td style="text-align:left;"> $AAPL the company that thinks people are going to pay $3500 to walk around town with VR headsets on is carrying the whole market.

They have jumped the shark. Cash out.

$QQQ $NVDA 

Collapse is inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:13:39 </td>
   <td style="text-align:left;"> $AAPL 
 
Levels and how they’ve played out all week, calls broke early Monday but sold off back into the range, failed to break downside of 177.5 got bought up today. More upside over 182. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:06:00 </td>
   <td style="text-align:left;"> $AAPL has a good Piotroski-F score of 7.00. This indicates a good health and profitability. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 12:01:05 </td>
   <td style="text-align:left;"> @deltax10 

couldn’t agree more. holding t-bills, $nu shares (dirt cheap &amp;amp; warren buffett backed), &amp;amp; the rest cash. the fib retracement sequence on every tech stock (except $aapl &amp;amp; slightly latex45db8a3a2026f157f1e0c6f18dd019d7SPY latex125ff9b4045585e8f05dd0b62c7c6f0cAAPL 8 wins + NT / 0 loss
$PARA 7 wins + NT / 0 loss

I don&amp;#39;t make 100s of trades. I only buy when I get a confirmation. Ask me for the receipts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:23:10 </td>
   <td style="text-align:left;"> $AAPL $IMMR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:17:00 </td>
   <td style="text-align:left;"> $SPY next week is going to be something else. With a Market overvalued on Hype &amp;amp; now at the top we have the Fed, Treasury &amp;amp; now a bunch of poorly educated cult members looking to act up so,.. Where was the VIX? where was the hedges?,... they&amp;#39;re coming! :o) 
 
$aapl $qqq $tsla $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:16:25 </td>
   <td style="text-align:left;"> Looks like we want to further squeeze shorts and reach all time highs. We are not out of the woods yet tho! $SPY $QQQ $AAPL  https://www.youtube.com/watch?v=P5mgvlo_Xdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:14:54 </td>
   <td style="text-align:left;"> $AAPL lovely day for Apple shareholders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:11:23 </td>
   <td style="text-align:left;"> $AAPL $AMD $AMZN How much do you dedicate? Hope you at least spend the 2 mins reading the OP Wire sent each morning 90 mins before the bell…. 😏📈

https://www.instagram.com/reel/CrZyq0Ku-bo/?igshid=YmMyMTA2M2Y= </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:07:12 </td>
   <td style="text-align:left;"> $AAPL $LCID $QQQ $RIVN $TSLA who the duck cares.  This is AAPL board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:06:34 </td>
   <td style="text-align:left;"> $AAPL Dystopia is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:04:57 </td>
   <td style="text-align:left;"> $AAPL it’s due to rip. I don’t know for how long. But this is a juicy ass setup. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 11:04:16 </td>
   <td style="text-align:left;"> $BA Trading Top Range Could B/O if $DIA Up 

$SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:57:53 </td>
   <td style="text-align:left;"> $lcid Lucid Motors already have world class EV tech. They should really execute strategically to grow while controlling cost. China news is very big and promising. Apple and Tesla make most profit out of China production as labor and other cost is cheaper.  
 
Lucid current market cap 13 BN can grow over 100 bn, if they execute well over next 3-5 years.  
 
$tsla $rivn $qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:50:24 </td>
   <td style="text-align:left;"> $HOOD app on $AAPL  Vision Pro will be 🔥 🔥 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:49:10 </td>
   <td style="text-align:left;"> $AAPL They release content on goggles. SELL! Yawn ok, next day, I will buy this dip right here $178.20. Well look at that back into $180s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:39:51 </td>
   <td style="text-align:left;"> $QQQ Guy updates on SPY chart https://youtu.be/VWYLOOYhUUw $GOOG $AAPL 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:28:25 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #5 stock that institutions are trading with 41.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:27:06 </td>
   <td style="text-align:left;"> $PLTR $PC aka $tsla battery maker!!!  $aapl Titan needs BATTERIES!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:25:52 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy Jun 16, 2023 $182.5 Calls 
Entry Price: $1.49 - $1.49 
Exit Price: $1.68 
Stop Loss: $1.41 
Potential ROI: 13% 
Estimated Hold Time: 70 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:24:32 </td>
   <td style="text-align:left;"> $SPY  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:24:13 </td>
   <td style="text-align:left;"> $AAPL can we see $185+ Tmr 🤔👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:24:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Vision Pro: Everyone Is Missing The Big Picture https://www.stck.pro/news/AAPL/52545921/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:22:21 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple Vision Pro: Everyone Is Missing The Big Picture </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:08:38 </td>
   <td style="text-align:left;"> $SPY $qqq $tsla $meta $aapl 
 
NEXT WEEK GOING to be volatile as FED MEETING on Thursday! 
 
Canada &amp;amp; Australia - Hike Rates.  US will HIKE TOO 
 
TAKE PROFIT and WAITING ON SIDELINE to see what feds decision!!! 
 
We might see MASSIVE PROFIT TAKING from TOMORROW Until Thursday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 10:00:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:59:37 </td>
   <td style="text-align:left;"> $GOOGL $MSFT such obvious longs buy and hold ignore the noise greatest companies on Earth and you will compound beyond your wildest dreams $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:57:05 </td>
   <td style="text-align:left;"> $AAPL $MSFT $DIS $F $TSLA Confucius say ... fku #fraudstreetboilerroommarketmakersandcronies  ... enjoy crash Friday you unregulated manipulated goons pumping bullshit 24x7 until you can&amp;#39;t  ... China&amp;#39;s producer prices slump 4.6% in May, worse than expected.  This is a developing news story. Please check back for updates:  
https://www.cnbc.com/2023/06/09/chinas-inflation-rises/falls.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:56:47 </td>
   <td style="text-align:left;"> &amp;gt; **MY TOP WATCHES FOR TOMORROW!**

&amp;gt; **Other**

&amp;gt; $COIN
&amp;gt; $DOCU
&amp;gt; $PYPL
&amp;gt; $AAPL
&amp;gt; $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:54:43 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:53:22 </td>
   <td style="text-align:left;"> $AAPL $NVDA $SPY $TSLA $SOFI AI hardware = Y2K. 
 
This ends badly. 
 
In tech.  Channel check yourself, the sales are not there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:51:24 </td>
   <td style="text-align:left;"> $META $SPY $QQQ $AAPL $TSLA 
 
ZUCK IS PANICKING!!!  
 
BASHING APPLE VR 
 
WANT TO CREATE STANDALONE to FIGHT TWITTER because he knows he can&amp;#39;t compete with PAPA ELON!!!! 
 
INSTAGRAM PROMOTES PEDO NETWORK 
 
GET FINE 1.3 B in EURO 
 
https://www.wsj.com/articles/meta-reveals-twitter-competitor-it-plans-to-launch-as-stand-alone-app-4a9b7721 
 
SELL META, buy AAPLE, TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:50:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $SOFI 

&amp;quot;The mother of all melt ups&amp;quot; gonna nice ring to it, I like it!

Let the bull market begin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:40:49 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/bsl9_uJ08uE 
$CVNA $BYND $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:37:29 </td>
   <td style="text-align:left;"> $AAPL calls above 180.84
Posted by @macrozz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:33:43 </td>
   <td style="text-align:left;"> $AAPL officially in bull market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:27:54 </td>
   <td style="text-align:left;"> $SPY $AAPL in spite of being the richest company in the world and talking so much about ESG, Apple pays almost no taxes to the state of California becuz they use loopholes to avoid them 
https://qz.com/apple-sales-tax-deal-cupertino-regulatory-scrutiny-1850331553 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:24:10 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Want to Invest in Republican or Democratic Stocks? Check Out These 2 ETFs https://www.stck.pro/news/AAPL/52542039/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:12:42 </td>
   <td style="text-align:left;"> $SPY    2 more hikes this summer 

groceries and gas have not hardly come off the highs $AAPL $MSFT $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:07:06 </td>
   <td style="text-align:left;"> $DOCU  docusign beat earnings and mention a.I!! This is apple at $30 situation , look at apple now at $180! buy now and get 6x later for your investments!!! $AAPL $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 09:02:26 </td>
   <td style="text-align:left;"> $GOOGL can this POS go green like $MSFT and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:54:56 </td>
   <td style="text-align:left;"> $DAL Delta Air Lines profit expected to soar 75% per report released today. $UAL $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:54:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:53:09 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m wrong, very bullish going to 190. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:50:39 </td>
   <td style="text-align:left;"> $QQQ Guy updates on SPY https://youtu.be/VWYLOOYhUUw $GOOG $AAPL 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:41:20 </td>
   <td style="text-align:left;"> $META META $AAPL  
https://www.theverge.com/2023/6/8/23754239/mark-zuckerberg-meta-apple-vision-pro-headset </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:40:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:37:37 </td>
   <td style="text-align:left;"> @Traidn clearly $AAPL snubbed Roblox.  Only way to win advertising is to team with $META </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:37:34 </td>
   <td style="text-align:left;"> $spy $nvda $aapl $tsla $BTC.X ❗️@MurdaCwrote BRILLIANT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:36:42 </td>
   <td style="text-align:left;"> $AAPL Extremely smart people... they are highly intelligent, these people I mingle with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:35:29 </td>
   <td style="text-align:left;"> $AAPL I think the trading volume is really important, so I oft talk about it. 
 
Oft, that&amp;#39;s short for often for the really smart people I hang out with. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:35:03 </td>
   <td style="text-align:left;"> @rexman 

as in, $aapl will see $230s? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:34:01 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $tsla

in a time of extreme greed, when news like this are announced, events (recessions, bull/bear markets, etc.) usually have already occurred. meaning, get your money now because it may not last long. apparently, the bull market began in october, which makes sense. stocks generally don’t grow 100%+ in a year either. markets can remain irrational longer than we can stay solvent, so this isn’t surprising. just know when to get off the wave. hold some cash, grab some shares, load some t-bills, and stay vigilant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:32:59 </td>
   <td style="text-align:left;"> $AAPL Elon is right on this one. 
 
Apple made a gigantic mistake. 
 
https://twitter.com/elonmusk/status/1666964082363371520?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:20:46 </td>
   <td style="text-align:left;"> 🐻❤😈🤯💲💰🤑✔ #JustShortIt  ... $aapl $amzn $dis $tsla $F and more ... https://link.cnbc.com/public/31738681 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:16:34 </td>
   <td style="text-align:left;"> $AAPL $META $RBLX disagree. 
 
Always been whack. 
 
Always will be. 
 
https://www.youtube.com/watch?v=qk3PK3W_wvo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:14:35 </td>
   <td style="text-align:left;"> $AAPL not a fan of either headset...but Apple at least gets points for not being as whack as Metaverse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:12:13 </td>
   <td style="text-align:left;"> $RBLX https://youtu.be/BdJdAu2ytNE. Check out this interview, his facial expressions when $AAPL is mentioned.  You can tell there is some bad blood like they were cut out of the goggle launch.  Esp last minute when asked if he would buy it…basically says no.   Because the ZUCK is coming in to team with them  $META   What does he bid 75-90? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:11:11 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA Who’s ready for a collossal dump??! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:04:38 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - Apple: Magical Delays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 08:00:38 </td>
   <td style="text-align:left;"> $BA clears closes &amp;gt; 221
Dow Jones goes up then $BA 238.00 next resistance 
$QQQ $AAPL $MSFT $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:59:00 </td>
   <td style="text-align:left;"> $AAPL is one of the better performing stocks in the Technology Hardware, Storage &amp;amp; Peripherals industry. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:57:54 </td>
   <td style="text-align:left;"> $AAPL 

🍎- should hit $203 if we get a pause next week !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:54:45 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:52:26 </td>
   <td style="text-align:left;"> $META $aapl $tsla $spy $qqq

Zuck whine like a baby over apple VR headset

Infact apple headset much more superior than meta 

Suck it zuck....

Buy aapl tsla DUMP meta

Not to mention meta getting their revenue and traffic from pedo network 

EWWW..... 🤮🤮🤮🤮

https://www.wsj.com/articles/instagram-vast-pedophile-network-4ab7189 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:42:41 </td>
   <td style="text-align:left;"> $PLTR Dr.  Karp  working  with  the  FREE  WORLD!!!    $f $tsla $arkk $AAPL  
 
https://www.mirror.co.uk/news/politics/rishi-sunak-meet-boss-scariest-30178412 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:41:27 </td>
   <td style="text-align:left;"> Who needs $WBD content? 
$AMZN? $AAPL? $CMCSA?  
https://deadline.com/feature/writers-strike-tv-shows-affected-cobra-kai-yellowjackets-abbott-elementary-1235354256/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:40:48 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - 7 Tech Stocks to Avoid Like the Plague in June </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:39:27 </td>
   <td style="text-align:left;"> Incoming crash Friday @ https://www.investing.com/indices/indices-futures  
$dis too sell off @ https://www.marketwatch.com/investing/stock/dis?mod=search_symbol 
You&amp;#39;re welcome 🐻❤😈 $aapl $msft amzn $tsla $f and more goofy overpriced nonsense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:38:50 </td>
   <td style="text-align:left;"> $ROKU $AAPL $BYND 

Bearish reversal 🩸🩸🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:36:53 </td>
   <td style="text-align:left;"> $AAPL i feel bearish short term for stocks. long term is still good. u.s economy wont be as bad as  any greats recession before. technologies makes it better forecast so most companies can adjust themselves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:36:00 </td>
   <td style="text-align:left;"> $TSLA JUST KIDDING, WE ARENT SELLING UNTIL $350 NOW

$GM $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:34:48 </td>
   <td style="text-align:left;"> $TSLA plus chart history never fails on record of days in green..it happened to $AAPL past year that repeated previous record a dropped harder after.. same here tomorrow will be a green day as said it during regular hours to match Jan 8 2021 record (11 days in red) and then it would pull back 8% to around $230.. don&amp;#39;t chase </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:33:56 </td>
   <td style="text-align:left;"> $CVNA $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:33:24 </td>
   <td style="text-align:left;"> $AAPL $NFLX $NVDA $SPY $TSLA LOL.  Just wait till the FED pivots and see what happens. LOL. Clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:30:26 </td>
   <td style="text-align:left;"> $AAPL $DIS $QQQ ever wondered how proven traders (pros) manage their trade plans and portfolios? We teach this at Optionsplayers and the alert plays, mentoring, &amp;amp; premarket news/plans are all free for you for a month with no risk- can stay as long or as little as you wish. Get it all by using the link in bio or this!

https://app.optionsplayers.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:28:42 </td>
   <td style="text-align:left;"> $AAPL Hello dumb dumb shorts - this is the gift that keeps on giving ~ Gazoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:23:54 </td>
   <td style="text-align:left;"> $AAPL What&amp;#39;s up with the BiG boUNce? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:21:11 </td>
   <td style="text-align:left;"> $AHI AI Health $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:17:05 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NFLX $NVDA 

shorts are about to get destroyed

A new bull market is about to begin

I warned you... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:15:20 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Zuckerberg: Apple Vision Pro is ‘not the one that I want,&amp;#39; doesn&amp;#39;t have any ‘magical solutions&amp;#39; https://www.stck.pro/news/AAPL/52531701/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:08:44 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $TSLA 4/4 not too shabbyyyyy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:04:06 </td>
   <td style="text-align:left;"> $PLTR just  signed  deal  with  Panasonic $pc aka  $tsla battery  maker!!!    $aapl has  5,000  people  working on  their  Apple  Car!!!    Apple  needs  BATTERIES!!!    Who  makes  the  best  batteries???    Project  Titan  has  their  own  Wikipedia  page!!! 
 
https://en.wikipedia.org/wiki/Apple_electric_car_project </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:03:19 </td>
   <td style="text-align:left;"> How to trade using Blue Boxes? | Elliott Wave Learning | Elliott Wave Forecast, video tutorial at: https://t.co/LEwTOxOvJq #Elliottwave #Stocks #Trading $DJIA $AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:00:53 </td>
   <td style="text-align:left;"> $SPY Latest 1H view from the Midday update. Showing a reaction higher taking place as expected. Longs should be risk free by now. #Elliottwave #Stocks #Trading $DJIA $AAPL $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:00:40 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 07:00:13 </td>
   <td style="text-align:left;"> $SPY 1H view from today&amp;#39;s Pre-Market update. Called for a pullback towards the blue box area where buyers were expected to appear. #Elliottwave #Stocks #Trading $DJIA $AAPL $SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:52:45 </td>
   <td style="text-align:left;"> $SPY $AAPL what was the reason for the pump today again?  Did AAPL come out with a stupid goggle for blind people which will cost $6,499.99? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:51:48 </td>
   <td style="text-align:left;"> $AAPL &amp;#39;bout 40-50 points more to go, imo. 
 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:43:52 </td>
   <td style="text-align:left;"> $AAPL kind of crazy when you think that people are actually buying in at these levels and they will still double their money in 10 years or less </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:41:34 </td>
   <td style="text-align:left;"> $PLTR just  signed  a  deal  with  Panasonic  aka  $pc aka  $tsla battery  maker!!!  COINCIDENCE???  $aapl needs  a  battery  maker  for  their  long  anticipated Apple  Car!!! 
 
https://9to5mac.com/2021/08/09/apple-car-korean-partners/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:36:21 </td>
   <td style="text-align:left;"> $aapl $spy $qqq

exactly why i took profit on long calls and will wait patiently for a pullback. will look juicy @ ~ $150. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:36:15 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #5 ticker with sweep activity where institutions are trading options urgently with 29.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:33:33 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : How To Allocate $25,000 Among My Top 20 Dividend Income Stocks For June 2023 https://www.stck.pro/news/AAPL/52528374/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:31:50 </td>
   <td style="text-align:left;"> $SPY $AAPL Apple is very close to its all-time high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:29:28 </td>
   <td style="text-align:left;"> $AAPL 
👁
❤️
🍏👁❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:24:07 </td>
   <td style="text-align:left;"> $SPY $AAPL the camera on the Samsung Galaxy is amazing! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:22:52 </td>
   <td style="text-align:left;"> $TSLA $AAPL 
The games MMs playing is DIRTY af!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:20:35 </td>
   <td style="text-align:left;"> $PLTR just  signed  $tsla battery  maker  $PC aka  Panasonic!!!    YESTERDAY!!!    Does  $aapl need  a  battery  maker  for  the  Apple  Car???    Apple  rolls  with  best  in  class!!    $f Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:19:25 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - 7 Momentum Stocks That Could Skyrocket in the Next 12 Months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:15:37 </td>
   <td style="text-align:left;"> $PLTR is  ENTERPRISE AI  like  $msft $csco $pc not  yet  for  $aapl!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:15:33 </td>
   <td style="text-align:left;"> $TSLA  
 
I called $230+ on May 1st when @ $160, now I am calling $280 ON DECK! 
 
 
$NVDA $QQQ $META $AAPL  
 
LFG, Greedy Index 76! (Extreme Greedy) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:14:05 </td>
   <td style="text-align:left;"> $SPY I have said before. This market is fixed to go up. There are literally a million ways to f with bears. Every time something about to break something else will show up to pump the market up. Unreal lol 😂 $TSLA $CVNA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:13:05 </td>
   <td style="text-align:left;"> Trillion Dollar Stocks $AAPL $MSFT $GOOG $AMZN $NVDA  
 
https://www.dividendpower.org/2023/06/08/trillion-dollar-stocks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:11:27 </td>
   <td style="text-align:left;"> $AAPL  nice average on 15 calls $180June 16 let&amp;#39;s see how much they print after FED meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:09:52 </td>
   <td style="text-align:left;"> $AAPL 250 by xmas no brainer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:08:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
08-June Stock Market Update: Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:06:40 </td>
   <td style="text-align:left;"> $AAPL https://www.stockilluminati.com/aapl/news.php - How To Allocate $25,000 Among My Top 20 Dividend Income Stocks For June 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:04:00 </td>
   <td style="text-align:left;"> $aapl $msft $amzn $dis $tsla and more ... stfu already #fraudstreetboilerroommarketmakersandcronies with your unregulated manipulated unsubstantiated self serving bullshit rallies in queue to implode is these trying times overflowing with valid socioeconomic concerns in tandem with more coming including higher interest rates.  &amp;quot;China inflation could spoil the weekend party.&amp;quot; @ https://newslink.reuters.com/public/31737940  Welcome to crash Friday and the Armageddon Recession you goons. Thank dog that I am here to help @Profit_Maker https://stocktwits.com/Profit_Maker 🐻❤🤯😈💲💰🤑✔ 
Stock Futures 
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
   <td style="text-align:left;"> 2023-06-09 06:01:24 </td>
   <td style="text-align:left;"> $BABA $JD latex4dc141bca9a8686cb584d0d68df3715eaapl start by banning apple products. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:00:40 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 06:00:39 </td>
   <td style="text-align:left;"> $AAPL love the LT chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:59:56 </td>
   <td style="text-align:left;"> $TSLA yes the shareholders are really good at pushing the price up with buying 1 share at a time

but if the market starts to sour on rate effects and another rate higher 

then this will see some heavy volatility 

because over 200 has been mostly lower volume 

$AAPL $SPY $IWM $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:55:59 </td>
   <td style="text-align:left;"> $TSLA Holding shares from 130 but i expect a pullback after fed raises again 

they know they have to, because prices aren&amp;#39;t really down hardly 

$SPY $AAPL $NVDA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:53:45 </td>
   <td style="text-align:left;"> $AAPL Reminder #6: $180 new solid support, will test $185 soon, by mid-June. $QQQ $META $TLSA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:53:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 81%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:03:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA $TSLA $X i usually dont eat cats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:03:34 </td>
   <td style="text-align:left;"> $TSLA Wouldn’t be surprised if Elon sold some shares to spite the gullible baggies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:03:28 </td>
   <td style="text-align:left;"> $TSLQ 🙏 for me. Doubled down here. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:03:28 </td>
   <td style="text-align:left;"> $TSLA will finish below 240 today...this bulk rally is overextended...will be lots of profit taking today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:03:12 </td>
   <td style="text-align:left;"> @GoodNewsBull its all $tsla.. because a competitor will add a levitom switch to their car port in 2025.  should be good for another trillion or two </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:57 </td>
   <td style="text-align:left;"> $SPY NATO condemns Russia&amp;#39;s withdrawal from conventional armed forces treaty | $QQQ $TSLA $NVDA https://cyprus-mail.com/2023/06/09/nato-condemns-russias-withdrawal-from-conventional-armed-forces-treaty/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:42 </td>
   <td style="text-align:left;"> $TSLA about to see $300 soon enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:35 </td>
   <td style="text-align:left;"> $TSLA $260 I sell remaining shares.  Come on market manipulators </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:34 </td>
   <td style="text-align:left;"> $TSLA I’m not charging my EV at any Tesla stations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:19 </td>
   <td style="text-align:left;"> $TSLA closed my calls, its lookimg a little weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:09 </td>
   <td style="text-align:left;"> $TSLA $260 today market manipulators.  Make it happen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:02:04 </td>
   <td style="text-align:left;"> $TSLA Rip some faces Tesla. LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:53 </td>
   <td style="text-align:left;"> $MULN  under 0.5  I’m in 💰
😎💸🔝 
$ABBV $RIVN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:53 </td>
   <td style="text-align:left;"> $COIN will be next growing company in next 10 years like  $NVDA  $TSLA $NFLX 10 years ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:49 </td>
   <td style="text-align:left;"> $TSLA we need to create a spring at 235 to jump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:45 </td>
   <td style="text-align:left;"> $TSLA Some nice accumulation and resistance as we push higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:42 </td>
   <td style="text-align:left;"> $TSLA 254 - 255$ on the horizon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:39 </td>
   <td style="text-align:left;"> $TSLA wouldnt surprise me if it rugs all gains and goes red. Never trust this scam market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:35 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:21 </td>
   <td style="text-align:left;"> $RGTI 5M volume the first 30minutes is massive. Someone wants in $TSLA $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:19 </td>
   <td style="text-align:left;"> $TSLA i dont see this going above 254 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:17 </td>
   <td style="text-align:left;"> $TSLA kinda curious now how next week might be, yall thoughts? https://www.reddit.com/r/shortsqueeze2023/comments/14562jk/what_to_expect_for_tsla_going_into_next_week_must/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:17 </td>
   <td style="text-align:left;"> $KERN $tsla gET SOME kern. KERN IS GRYPHON! https://gryphondigitalmining.com/media/michael-saylor-and-elon-musk-ask-bitcoin-mining-companies-to-be-more-like-gryphon/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:16 </td>
   <td style="text-align:left;"> $TSLA $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:09 </td>
   <td style="text-align:left;"> New video at $TSLA $250 👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:09 </td>
   <td style="text-align:left;"> $TSLA We will break $250 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:05 </td>
   <td style="text-align:left;"> $TSLA range market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:02 </td>
   <td style="text-align:left;"> $TSLA ‘s charging standard is now being adopted by $GM in addition to $F 

The more licensing and collaboration announcements like this the more Tesla is being cemented as a leader in this technology.

$TSLA bulls very happy right now:

https://commonstock.com/post/998f4143-d218-4296-8ee3-c030d699f4cc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:01:01 </td>
   <td style="text-align:left;"> $TSLA So overbought but it just goes higher and higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:57 </td>
   <td style="text-align:left;"> $TSLA 

The only direction is up, right bulls. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:54 </td>
   <td style="text-align:left;"> $TSLA Cycle started at $175 and right to $250 with a that C leg up  🌊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:48 </td>
   <td style="text-align:left;"> $TSLA scalpers are gone ^🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:39 </td>
   <td style="text-align:left;"> $SPY now just pray Russia not nuke Eastern Europe and China not create another Cuban Missile Crisis $QQQ $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:20 </td>
   <td style="text-align:left;"> $TSLA   Imagine if Ford owned all the gas stations and GM’s had to fill up at Ford branded gas stations while  using Ford’s  satellite WIFI network </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:20 </td>
   <td style="text-align:left;"> $TSLA 
Wedbush coming up on CNBC after break.  Talking Tesla and $300.00 PT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:19 </td>
   <td style="text-align:left;"> $TSLA Going to a million gazillion!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:18 </td>
   <td style="text-align:left;"> $TSLA sell the news.. wallstreet knew about this a month ago and front ran </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:17 </td>
   <td style="text-align:left;"> $NIO $tsla $9 nio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:15 </td>
   <td style="text-align:left;"> $TSLA I am very bullish, But Dan Ives raising his price target to $300 or not. Its Overbought and will pull back. I have been redcung my total position size as we have been moving up and will load up on any decent pull back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:06 </td>
   <td style="text-align:left;"> $SPY The Biden Market just hit a new high on the day Trump gets indicted on the thing he claimed Hillary did. 
 
You can&amp;#39;t make this stuff up! :o) 
 
$dwac $aapl $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:04 </td>
   <td style="text-align:left;"> $TSLA hey simps, your diaper is full. dumping time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 22:00:01 </td>
   <td style="text-align:left;"> $TSLA From Bull to Bear. Was Short hear between $248 and $252. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:59:57 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ who buys CALLS on a stock up 11 days in a row into a huge gap up LMFAO  onky pajama can pull that off yes intook my profits alrwady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:59:27 </td>
   <td style="text-align:left;"> $MDGS nice accumulation. Soon $20 $20 $20. $TSLA $MSFT $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:59:17 </td>
   <td style="text-align:left;"> $TSLA I’m just a simple man but $305 seems to be reasonable in the next 30 days, given the developments in the business. Could Toyota be the next to sign up with Tesla? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:59:11 </td>
   <td style="text-align:left;"> $TSLA if tesla is sharing their charging stations im just getting a Ford </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:59:07 </td>
   <td style="text-align:left;"> $NVDA $TSLA Beast Mode Again ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:59:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:58:53 </td>
   <td style="text-align:left;"> $ROKU $TSLA $NFLX $AAPL - Pending long trade on ROKU 
&amp;gt;$74.23 else avoid the session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:58:47 </td>
   <td style="text-align:left;"> $TSLA Only makes sense EV superchargers follow one standard.  TSLA will dominate the energy grid and cars. 
This is a no-brainer.  TSLA 1k in short order. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:58:43 </td>
   <td style="text-align:left;"> $TSLA @elonmusk (everyone else) yall out here playing hop scotch, (Elon) when we&amp;#39;re out here playing double Dutch, whilst writing a Shakspearian sonnets, while playing chess. Great move #Tesla #gobulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:58:29 </td>
   <td style="text-align:left;"> $TSLA I guess everyone is waiting for this to run or not. Otherwise this is staying flat and dropping a bit by EOD. I was hoping for a good ol fashion run to at least noon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:58:22 </td>
   <td style="text-align:left;"> the gameplan for today is essentially, all UPSIDE $ARRY $PYPL $DIS $INTC SWINGS ARE IN TACT — 

For NEW or AVERAGING IN PLAY, 243.20s $TSLA becoming resistance, it’s go time on SWING puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:58:00 </td>
   <td style="text-align:left;"> $TSLA $260 CALL

6/9 EXP 

THANK ME LATER🤝🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:52 </td>
   <td style="text-align:left;"> $TSLA tesla themselves have not monetized the charging network yet, so this is not about $$$ to the bottom line immediately…this is strategic industry acceptance… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:46 </td>
   <td style="text-align:left;"> Some whale is keen on shorting $TSLA after its recent run 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:36 </td>
   <td style="text-align:left;"> $TSLA $PLTR 💪 👌 🔥 👀 💵 👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:17 </td>
   <td style="text-align:left;"> $TSLA RSI88 with 11 straight up day. Who is buying today ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:15 </td>
   <td style="text-align:left;"> $TSLA $NVDA $SPY $QQQ $AMD 

How’s my portfolio for a 24 year old? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:10 </td>
   <td style="text-align:left;"> $TSLA could close at 220 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:08 </td>
   <td style="text-align:left;"> $TSLA setting up for a big move imo. Its about to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:57:02 </td>
   <td style="text-align:left;"> $TSLA holy shet the volume ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:58 </td>
   <td style="text-align:left;"> $TSLA on no step-stock, why are you stuck? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:55 </td>
   <td style="text-align:left;"> GM CEO Mary Barra says Tesla charging deal will save the automaker up to $400 million

$GM $TSLA

https://www.cnbc.com/2023/06/08/gm-says-tesla-charging-deal-will-save-the-automaker-up-to-400-million.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:54 </td>
   <td style="text-align:left;"> latex9564766916880e542a9718299a88f100AABB OTC gold/crypto lotto play 
$TGT keep on crashing for my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:37 </td>
   <td style="text-align:left;"> @cubie77 said it earlier $249 to $241 to $253 to $231 on Monday June 12 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:35 </td>
   <td style="text-align:left;"> $TSLA love this action! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:34 </td>
   <td style="text-align:left;"> $TSLA 🚨 Wedbush upgrade from 215 to 300🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:22 </td>
   <td style="text-align:left;"> $NASDAQ is growing insane today! Hoping this can nudge $MVIS past squeeze territory. 
 
$LAZR $TSLA $CVNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:19 </td>
   <td style="text-align:left;"> $TSLA Tesla is the daddy of chicks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:16 </td>
   <td style="text-align:left;"> $TSLA  The 180 Lucids that are on the road …are still aloud to use the broken chargers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:15 </td>
   <td style="text-align:left;"> $TSLA 250 and we pass 260!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:12 </td>
   <td style="text-align:left;"> $TSLA Never thought i&amp;#39;d see the legacy autos cave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:56:10 </td>
   <td style="text-align:left;"> $TSLA what really matters long term strategically…tesla is now in good graces with the government and the industry…full acceptance… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:55 </td>
   <td style="text-align:left;"> If you have the same 14 holdings I have in the portfolio, you will see that you are UP $1014.39 already this morning ! 
 
 
 
two BULLdogs leading .... $AEHR  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:55 </td>
   <td style="text-align:left;"> The battle for 250 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:45 </td>
   <td style="text-align:left;"> $MSFT it took microsoft extra day to do 50% retracement of $335 to $323s drop.  like clockwork huh. 

lets go bubbles $nvda $adbe $amd $tsla🙄😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:45 </td>
   <td style="text-align:left;"> $TSLA Sold half my position in Microsoft and bought Tesla, Google, and Amazon. Good move? I know the Tesla part is a winner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:44 </td>
   <td style="text-align:left;"> $TSLA might be a small dip, big dip whatever, but this MF is resuming it’s beast-ness on Monday. Don’t think it stops here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:40 </td>
   <td style="text-align:left;"> $TSLA $F $GM Tesla is on an 11-Day win streak and +5% as GM and Ford adopt Tesla Supercharger Network </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:38 </td>
   <td style="text-align:left;"> $KSS $spy $meta $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:36 </td>
   <td style="text-align:left;"> $TSLA 250p for september lets see how it goes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:28 </td>
   <td style="text-align:left;"> $TSLA 
$300.00 PT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:26 </td>
   <td style="text-align:left;"> $AAP waited since ER for bottom/entry, starting position here $TSLA $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:20 </td>
   <td style="text-align:left;"> $TSLA i see $250 and i’m gone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:20 </td>
   <td style="text-align:left;"> @WKHSguyUSA  Then work deal out with $AAPL  to sell factory/partner w/ them.  $AAPL would LOVE to have one of the top 5 largest auto factories in the U.S. for sure.  Lease it back to whomever their builder is.  I LOVE THIS IDEA.  $RIDE $AAPL  
 
Maybe $TSLA and Elon should initiate a quick conversation with LMC leadership IF &amp;quot;clawing back&amp;quot; the factory is on the table.   
 
$GME $AMC  crew....look at our float now after reverse 15:1 split.  Maybe it&amp;#39;s time to make lemonade outta lemons finally.  Ford and friends tried to destroy LMC imo w/ their cronies from GSCO (walled us in for over a year on Lev II it shows), Cramer, CNBC, TheStreet and banks that own Ford debt.  It&amp;#39;s time to fight back and 16 million shares only in float!  (some other EV stocks have a BILLION shares and ones like Fisker have over 300 million.. $RIDE 16 milly only...) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:11 </td>
   <td style="text-align:left;"> $TSLA update on the Tesla loss porn $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:55:07 </td>
   <td style="text-align:left;"> $TSLA this will be 260 before noon going to get ugly fast once the first short breaks and covers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:57 </td>
   <td style="text-align:left;"> $TSLA will it keep climbing today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:42 </td>
   <td style="text-align:left;"> $TSLA tsla is buying even more batteries from catl, the world leader in battery technology by far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:35 </td>
   <td style="text-align:left;"> $TSLA $CVNA $NVDA  #dead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:29 </td>
   <td style="text-align:left;"> $TSLA when $1.69 tril MC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:27 </td>
   <td style="text-align:left;"> $FFIE perfect time to buy,  buy $100 worth of shares here and by next year you&amp;#39;ll have your $AAPL vision pro fund!!! $TSLA $PLTR $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:27 </td>
   <td style="text-align:left;"> $TSLA Really, buying here??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:25 </td>
   <td style="text-align:left;"> PAJAMA!!! 
 
ON!!!! 
 
FIRE!!!! 
 
absolutely KILLING IT just did a 10 minute trade in 0dte $tsla calls in addition to what i held overnight lmao  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:19 </td>
   <td style="text-align:left;"> $TSLA   The road to $420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:54:01 </td>
   <td style="text-align:left;"> $IDEX ProTip: If you’re using CashApp for trading, you need to re think what youre doing… 

This new generation of retail traders are completely ignorant. It’s actually scary…🤦🏼‍♂️

$TSLA $SPY $RIVN $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:55 </td>
   <td style="text-align:left;"> $TSLA Already broke $250.  Time to stop dancing around it and rocket to $310. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:39 </td>
   <td style="text-align:left;"> $DWAC $TSLA only conservatives are willing to listen to all sides, this is why we luv Elon! 
https://ca.finance.yahoo.com/news/elon-musk-asking-big-name-123259887.html#:~:text=Elon%20Musk%20is%20again%20asking,to%20balance%20out%20Tucker%20Carlson.&amp;amp;text=%22It&amp;#39;d%20be%20great%20to,full%20support%2C%22%20Musk%20added. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:30 </td>
   <td style="text-align:left;"> $TSLA $250 falls today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:26 </td>
   <td style="text-align:left;"> $TSLA trapping bears hard at the moment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:21 </td>
   <td style="text-align:left;"> $MULN $TSLA $NIO $RIVN $ABBV 

https://www.fxstreet.com/amp/news/mullen-automotive-stock-forecast-muln-continues-to-reach-new-lows-with-13-slide-on-tuesday-202306071314 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:15 </td>
   <td style="text-align:left;"> $ZM $TSLA $NFLX $AAPL - Pending long trade on Zoom 
&amp;gt;$68.84 else avoid the session </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:11 </td>
   <td style="text-align:left;"> $TSLA  better bring lube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:06 </td>
   <td style="text-align:left;"> $TSLA poots poots, get your poots right &amp;#39;ere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:53:00 </td>
   <td style="text-align:left;"> $TSLA opps ment 250 sorry 🫣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:58 </td>
   <td style="text-align:left;"> $TSLA and then they said, &amp;quot;Timber&amp;quot; rofl 
#roadto300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:57 </td>
   <td style="text-align:left;"> $TSLA re*arded exuberance for nothing. All I see are baggies bashing their heads open while the sky is getting red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:57 </td>
   <td style="text-align:left;"> $TSLA  So the othe EV’s have to use the broken chargers only </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:52 </td>
   <td style="text-align:left;"> $TSLA $GME $F , looking to add small short position

Higher interest rate, increase purchase cancellations, auto loan payments default growing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:52 </td>
   <td style="text-align:left;"> $TSLA   Overnight TSLA  Play - WINNER  
                Cashed  Out  AT  THE  TOP 
 
                395%  Gainer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:47 </td>
   <td style="text-align:left;"> $TSLA 250 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:43 </td>
   <td style="text-align:left;"> $TSLA no choice but to buy puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:41 </td>
   <td style="text-align:left;"> $TSLA morning buyers ? Dried ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:36 </td>
   <td style="text-align:left;"> $TSLA hmm where shall we land today $260? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:33 </td>
   <td style="text-align:left;"> $TSLA $SPY biggest question is where do we see consolidation? $200.00’s last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:31 </td>
   <td style="text-align:left;"> $KERN $tsla Elon loves Gryphon. look it up and get some KERN. https://www.prweb.com/releases/gryphon_digital_mining_is_growing_its_self_mining_fleet/prweb19376844.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:31 </td>
   <td style="text-align:left;"> $TSLA  get to 240💪🏼💪🏼💪🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:26 </td>
   <td style="text-align:left;"> $TSLA  $GM is a joke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:19 </td>
   <td style="text-align:left;"> $TSLA chase or wait? Not sure there will be a dip today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:13 </td>
   <td style="text-align:left;"> $TSLA $250 wall to break 🚀 
Lots of shorts to Squeezzz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:52:02 </td>
   <td style="text-align:left;"> $AAPL $NFLX $NVDA $SPY $TSLA  
 
This is funny af. I don&amp;#39;t give a shit if its making fun of me. Can only laugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:47 </td>
   <td style="text-align:left;"> $TSLA Bears are quiet and start partying when they see Tesla go down a mere 5-10 points thinking it’s the end of Tesla. Fools </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:45 </td>
   <td style="text-align:left;"> $QQQ this is going to dump hard $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:27 </td>
   <td style="text-align:left;"> $TSLA 11 days of green why not believe .  Many positive news to ignore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:25 </td>
   <td style="text-align:left;"> $TSLA  Imagine your EV company has not sucked Elons balls yet ….and you have to use the broken chargers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:25 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/batmann_333/status/1667166908855070722?t=ChuWwXu0X3SwcCL2tQLqvg&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:24 </td>
   <td style="text-align:left;"> $TSLA no major sell off looking strong and primed for a continued to pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:14 </td>
   <td style="text-align:left;"> $TSLA cackling at shorts. More car companies will adopt Tesla charge stations opening up more revenue stream.
Wait until they get FSD and open up the software to competitors also. 

Superchargers
Robots
Cars
Solar
FSD 
ai </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:10 </td>
   <td style="text-align:left;"> $SOUN $Tsla news coming !! $5 plus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:03 </td>
   <td style="text-align:left;"> $TSLA please someone tell me should i take profit? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:51:00 </td>
   <td style="text-align:left;"> $TSLA when $260??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:50 </td>
   <td style="text-align:left;"> $TSLA Silly people - you could have bought this for $180 ten days ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:41 </td>
   <td style="text-align:left;"> $CVNA $NVDA $TSLA timber </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:30 </td>
   <td style="text-align:left;"> $TSLA $CVNA $NVDA *flute wailing* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:26 </td>
   <td style="text-align:left;"> $TSLA search and destroy price action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:20 </td>
   <td style="text-align:left;"> $TSLA Lfg‼️‼️🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:18 </td>
   <td style="text-align:left;"> $SPY $TSLA $NFLX $AAPL $NVDA  
 
bearvastation: devastation beyond compare... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:14 </td>
   <td style="text-align:left;"> $TSLA CRUSH&amp;#39;EM ELONNNNNNNNNNNNNNNNNNNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:13 </td>
   <td style="text-align:left;"> $TSLA The simple fact of the matter is that there are double the Teslas on the roads here in Redmond, WA today than there were three months ago at which point there were alot. Tesla will crush deliveries and ER next month. Crush.
I don&amp;#39;t like Musk, but that has zero bearing on a dispassionate analysis of the company and its share price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:10 </td>
   <td style="text-align:left;"> $TSLA Sell or keep till expiration ? decisions decisions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:10 </td>
   <td style="text-align:left;"> $SPY $TSLA link in the bio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:07 </td>
   <td style="text-align:left;"> $TSLA what idiot would short this stock now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:04 </td>
   <td style="text-align:left;"> $SPY $TSLA 2 100+% days back to back. THANK THE MOST HIGH 🙏🏿✝️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:04 </td>
   <td style="text-align:left;"> $TSLA we got 300$ PT from Wedbush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:50:01 </td>
   <td style="text-align:left;"> $TSLA short squeeze. As shorts starting to cover this will go up even higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:58 </td>
   <td style="text-align:left;"> $TSLA where’s that wumao traidn? $38 dollar stock huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:57 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Markets literally have no where to go but up!!! 📈🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:51 </td>
   <td style="text-align:left;"> $TSLA everyone knows where this is going moon boots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:47 </td>
   <td style="text-align:left;"> $TSLA  Cybertruck reservation holders communications starting next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:46 </td>
   <td style="text-align:left;"> Man who got $tsla 245 for .16 yesterday I salute you .. mofo opened at $575 today lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:34 </td>
   <td style="text-align:left;"> $TSLA loaded with $230k for 250cs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:32 </td>
   <td style="text-align:left;"> $TSLA $NVDA $AI ... I missed entries... I need a long stock to hold... HALP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:32 </td>
   <td style="text-align:left;"> $TSLA damn the volume only going to go higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:16 </td>
   <td style="text-align:left;"> $TSLA RSI 14 days is 86.6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:16 </td>
   <td style="text-align:left;"> $TSLA 

Hulk that 250 resistance. Let’s go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:11 </td>
   <td style="text-align:left;"> $RYCEY Rolls-Royce Chillin  $LYFT ’d 🍁💨 
 
$TSLA Tooo Easy @ $106 .. 🏎️ 
 
Let’s $GRIL !! 🔥🥩🦞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:49:01 </td>
   <td style="text-align:left;"> $TSLA Covering? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:57 </td>
   <td style="text-align:left;"> $TSLA yay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:57 </td>
   <td style="text-align:left;"> $TSLA what if it just skips jumps $150 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:55 </td>
   <td style="text-align:left;"> $TSLA was the last real dip opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:50 </td>
   <td style="text-align:left;"> $NIO Wow this donkey poop is up too? Thank god. Waiting to short more of this 💩  $TSLA , $XPEV and $ of course the biggest piece of dung $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:29 </td>
   <td style="text-align:left;"> $TSLA son of hgun!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:24 </td>
   <td style="text-align:left;"> $TSLA shorts got WRECKED and it’s only 6.48 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:20 </td>
   <td style="text-align:left;"> $TSLA there we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:15 </td>
   <td style="text-align:left;"> More insider buys here in $NXGL 🐳 

CEO giving guidance of quadrupling REVENUE next few quarters 📈

7 INSIDERS HAVE LOADED THE LAST 2 WEEKS 🕵️‍♂️ 

2 FDA approved products to replace MMMs tagederm in all hospital settings !!! HUGE 💥 

$TSLA running recently with $NVDA and $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:09 </td>
   <td style="text-align:left;"> $TSLA that&amp;#39;s the dip? Bloody hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:08 </td>
   <td style="text-align:left;"> $TSLA lock in profits hold runners.... Congrats on the PUMP!! 250 256 then 265 gap fill big area&amp;#39;s for this name </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:07 </td>
   <td style="text-align:left;"> $TSLA  I did say to buy early  at open yesterday for best prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:48:06 </td>
   <td style="text-align:left;"> $CHPT Bring it to GREEN today make the GM-TSLA non event which is the fact. 
 
I sense $TSLA going to buy CHPT that&amp;#39;s the reason F and GM move to TSLA early! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:57 </td>
   <td style="text-align:left;"> $TSLA make money both ways, down is profitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:41 </td>
   <td style="text-align:left;"> $TSLA Teslas kill the planet, #facts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:23 </td>
   <td style="text-align:left;"> $TSLA I think these TSLA morons like @inevercomment fell in love. Did you guys fall in love with your Stonk and Grindr date? Just tell me, everyone knows, it’ll be ok if you just tell me you Perma turds fell in love. Fkn chimps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:18 </td>
   <td style="text-align:left;"> $TSLA It&amp;#39;s gathering more rocket fuel ⛽ 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:16 </td>
   <td style="text-align:left;"> $TSLA how high can we go??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:09 </td>
   <td style="text-align:left;"> $TSLA hella profits overnight hahahahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:06 </td>
   <td style="text-align:left;"> $TSLA $SPY

bears getting greedy not locking in profits from that opening dip, squeeze em! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:05 </td>
   <td style="text-align:left;"> $TSLA Momma of all short squeezes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:47:05 </td>
   <td style="text-align:left;"> latexf9f45e840f78da4e04061c4d56b92791tsla 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:49 </td>
   <td style="text-align:left;"> $TSLA back in the green baby :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:42 </td>
   <td style="text-align:left;"> $TSLA  the only way the next car co stays relevant is to add Tesla  software </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:39 </td>
   <td style="text-align:left;"> $TSLA $251 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:34 </td>
   <td style="text-align:left;"> $TSLA now Toyota faces VHS /Betamax moment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:31 </td>
   <td style="text-align:left;"> $TSLA just buy stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:31 </td>
   <td style="text-align:left;"> $nio since 7.30s ✌️ told you buy the weakness dump instead chase the already pumped stocks  
 
$tsla $nvda $intc $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:30 </td>
   <td style="text-align:left;"> $TSLA turned 600 into 6k in 22 hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:25 </td>
   <td style="text-align:left;"> $TSLA lowkey sold my 250 early but didn’t wanna get too greedy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:22 </td>
   <td style="text-align:left;"> $LUNR 🚀  $TSLA $MULN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:19 </td>
   <td style="text-align:left;"> $TSLA gap to fill $265 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:16 </td>
   <td style="text-align:left;"> $nio even this pos is loosing.. $lcid $tsla will be worse.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:10 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/ZzTbtMKxD7w ☝️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:06 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:46:02 </td>
   <td style="text-align:left;"> $TSLA bears cover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:55 </td>
   <td style="text-align:left;"> $TSLA fuck yeah... 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:50 </td>
   <td style="text-align:left;"> $TSLA +110% ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:49 </td>
   <td style="text-align:left;"> $TSLA that’s how you turn 3k into 20k in a day🤧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:36 </td>
   <td style="text-align:left;"> $TSLA 💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:28 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:18 </td>
   <td style="text-align:left;"> $TSLA focus on the bigger picture 📸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:15 </td>
   <td style="text-align:left;"> $TSLA $1.8M OTM Put 
 
Strike: 195 
Expiration: 12/15/23 
 
*Above the Ask* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:08 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/ZzTbtMKxD7w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:07 </td>
   <td style="text-align:left;"> $TSLA don&amp;#39;t be surprised to see 270 today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:45:05 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-is-reportedly-mobilizing-chinese-suppliers-to-open-factories-in-mexico
Tesla long 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:59 </td>
   <td style="text-align:left;"> $TSLA profit take, or be prepared to bag hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:58 </td>
   <td style="text-align:left;"> $TSLA HOLDING SESSION HIGHS 
 
ITS GOING TO BREAK HIGHER AND RUN TODAY WOWOWOOWOW BEARS SHORTING IT AND GIVING IT THE POWER TO DO SO 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:58 </td>
   <td style="text-align:left;"> $TSLA &amp;amp; $NFLX made me some decent money today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:56 </td>
   <td style="text-align:left;"> $TSLA sell sell sell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:55 </td>
   <td style="text-align:left;"> $TSLA $SPY Had to send this again. Calls hit 725% at open. The community banked. Onto the next trade 💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:44 </td>
   <td style="text-align:left;"> $TSLA if we lose 245 I don’t know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:33 </td>
   <td style="text-align:left;"> $TSLA holy shit.... that might have been my biggest trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:29 </td>
   <td style="text-align:left;"> $TSLA commence gapfill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:26 </td>
   <td style="text-align:left;"> $RIOT wish I was in $TSLA instead...they get nonstop rocketing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

tried warning bears not to bet against cnbc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:19 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s about to be so green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:18 </td>
   <td style="text-align:left;"> $DIA $TSLA $GM $F Stocks were mixed on Friday morning as investors digested a pairing between two of the largest American automakers and prepared for the Federal Reserve&amp;#39;s next decision on rate hikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:06 </td>
   <td style="text-align:left;"> $TSLA breaks 249 and it will run allday wrecking ball. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:06 </td>
   <td style="text-align:left;"> $RIDE   Stocktwits sure seems anti-RIDE.  Paid &amp;quot;news&amp;quot; on the right is negative usually.  Weird charting and whatnot.  Letting Bears w/ MANY accounts bash share price when they are obviously short (short and distort is illegal).   Seems like a HUGE class action lawsuit against Stocktwits would be viable due to so many microcaps getting attacked by sentiment negative farming as they are shorted down.  $GME $AMC $TSLA $AAPL  p.s.  Our float is only 16 million for an EV company w/ a product ready to produce that was finalist for TRUCK OF THE YEAR recently.   
 
Maybe join $RIDE w/ a long starter position?  Foxconn is trying to bully LMC and they are fighting back...FINALLY.  Help a small EV company in Ohio fight back.   FTD&amp;#39;s every day for 2 years.  Short % each day OVER 50% for years.  The attack almost worked...but now insane value play and very squeezy.   
 
Do your own DD, buuuuut..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:44:04 </td>
   <td style="text-align:left;"> $TSLA $CVNA $U $AFRM $UPST  
$U hits my 38 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:56 </td>
   <td style="text-align:left;"> $TSLA the BULLS really want that 250 break.. we will have it too. Strong push </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:49 </td>
   <td style="text-align:left;"> @SeNSF $SPY max pain is a bogus zero math internet fake topic. 
 
Learn more  
 
$QQQ $UVXY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:45 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:42 </td>
   <td style="text-align:left;"> $TSLA $300+ next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:38 </td>
   <td style="text-align:left;"> $TSLA $AAPL 
Never ever chase a bull trap in a bear market! 
Believe me thats the worst mistake! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:35 </td>
   <td style="text-align:left;"> $TSLA when it break 250 it can rub ti 260 FAST FAST inagine cor weing thr market on gast stations at the advent of gas powered cars  
 
$spy $qqq  
 
🚀🚀🚀🚀🤑🤑🤑📈📈📈📈 
 
DID YOU LISTEN 
 
LETS GAMMA SQUEEZE THIS NAME!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:29 </td>
   <td style="text-align:left;"> What a gap!!! $TSLA #Tesla #OptionsTrading #optionstrade #DayTrading #Daytrader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:28 </td>
   <td style="text-align:left;"> $TSLA Not letting go of a single fraction of my Tesla shares. DCA&amp;#39;ing clear through 2030. This is only the beginning of the climb! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:27 </td>
   <td style="text-align:left;"> $TSLA Position size now at 11X normal allocation, ugh…risk is nerve racking now. This is hard, LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:25 </td>
   <td style="text-align:left;"> $KODK $CVNA $BAOS $TSLA 

Kodak meme potential could run like Carvana!!!

💥 💥 💥 💥 💥 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:18 </td>
   <td style="text-align:left;"> $TSLA updates:
Intraday +5%
5-day +14%
1-month +44%
3-month +42%
6-month +41%
1-yr +6%
2-yr +23%
5-yr +1,052%
10-yr +3,688%
Since IPO +15,472%

Source: James Stephenson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:04 </td>
   <td style="text-align:left;"> $TSLA  Each new Car company added  to the Tesla network pays  
more than the last one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:01 </td>
   <td style="text-align:left;"> $TSLA or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:43:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

cnbc &amp;gt; bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:58 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ  
Lmfao 🤣🤣🤣🤣💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:56 </td>
   <td style="text-align:left;"> $TSLA  covered as well $245.12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:49 </td>
   <td style="text-align:left;"> $TSLA $$nvda $AMD $NFLX $FNGU going to da Moooon🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:45 </td>
   <td style="text-align:left;"> $TSLA the 250 party is over.
going lower to close the gap.
will see 230 within next wk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:40 </td>
   <td style="text-align:left;"> $TSLA I think atleast $250+ today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:30 </td>
   <td style="text-align:left;"> $TSLA buy buy bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:27 </td>
   <td style="text-align:left;"> $SPY $TSLA im getting out soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:24 </td>
   <td style="text-align:left;"> $NIO earnings fail miserably and just moving up with $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:23 </td>
   <td style="text-align:left;"> $TSLA i Am shorting here. 800 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:21 </td>
   <td style="text-align:left;"> $TSLA oh fuck this suit want to fucking closed the gap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:18 </td>
   <td style="text-align:left;"> $TSLA options were overnight. Picked up commons last week 🔥🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:08 </td>
   <td style="text-align:left;"> $F and now $GM are adopting the $TSLA charging standard.

The more licensing and collaboration announcements like this, the more Tesla is being cemented as a leader in this technology.

$TSLA’s plan is working.

https://commonstock.com/post/998f4143-d218-4296-8ee3-c030d699f4cc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ 

BEARS ABOUT TO GET DOWNGRADED BY CNBC 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:42:00 </td>
   <td style="text-align:left;"> @YipMen no cookie jar rule now. if ya got 249s short, take profit on pullback to $245-246s just now.  trading these names ($tsla and $nvda), u gotta be quick and not greedy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:59 </td>
   <td style="text-align:left;"> $TSLA keep gambling on your puts while i slowly add up without stress every single paycheck without having to stress about the daily price and being emotional” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:58 </td>
   <td style="text-align:left;"> $TSLA stock will close $ 230 today.This was a propaganda news about tsla partnership that will add at  max 1 to 3 billion in 2025 for rsla revenue 127b.garbage garbage news.gm and f could not deliver for yrs and looking for last straw news to drive their stock higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:54 </td>
   <td style="text-align:left;"> $TSLA $300 very soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:52 </td>
   <td style="text-align:left;"> $DOGE.X what is this elon will dump tesla to buy doge $TSLA 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:38 </td>
   <td style="text-align:left;"> $TSLA  265$ for Telsa AI play 

Good luck everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:36 </td>
   <td style="text-align:left;"> $CHPT Jolt after the $GM $TSLA and $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:34 </td>
   <td style="text-align:left;"> $NVDA $TSLA $SPY latexeba1881e98b00a6ea495d312dc87fa30 premium !!! I think the stock will soon be exhausted …. Hopefully by next week i will buy back those calls for 4-5$ for a nice premium in pocket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:26 </td>
   <td style="text-align:left;"> $TSLA $8k Investment 💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:23 </td>
   <td style="text-align:left;"> $TSLA  Does VW have a hope in North America now?  No they don’t ……. 
 
Better ask Elon nicely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:15 </td>
   <td style="text-align:left;"> $TSLA Super strong! Most buyers today compared to recent days! $250 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:13 </td>
   <td style="text-align:left;"> latexeeb7335431d5c2f8e7ccbe640bd8d30b or 260$ least 📈🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:05 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:41:02 </td>
   <td style="text-align:left;"> $TSLA again wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:55 </td>
   <td style="text-align:left;"> $ZEV 33% short interest. Low float. $CVNA $TSLA going para. Won&amp;#39;t be long. Look at $PEV too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:54 </td>
   <td style="text-align:left;"> $TSLA I had 900 shares sold  150  at the open  I had to take some  off the table </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:46 </td>
   <td style="text-align:left;"> $TSLA bears all out now having lost a ton of puts...they all like see..it&amp;#39;s going down... 🐂 See us eating steak 🥩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:40 </td>
   <td style="text-align:left;"> $TSLA Wedbush updates price target to $300 from $215 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:40 </td>
   <td style="text-align:left;"> $TSLA still buying up all sells regardless of price for the objetive of winning time sequences as the end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:38 </td>
   <td style="text-align:left;"> $TSLA keep adding those puts bears. Fueling the fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:37 </td>
   <td style="text-align:left;"> $TSLA  since yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:34 </td>
   <td style="text-align:left;"> $TSLA ehhh yea ima wait to get in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:31 </td>
   <td style="text-align:left;"> $SPY $500 $TSLA today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:29 </td>
   <td style="text-align:left;"> $TSLA had to buy puts just because i need the money for more calls later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:22 </td>
   <td style="text-align:left;"> $TSLA no sellssssss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:17 </td>
   <td style="text-align:left;"> $TSLA Merry Christmas everyone 😂😂😂 one hell of a week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:40:12 </td>
   <td style="text-align:left;"> $TSLA https://www.reuters.com/technology/gm-ceo-discuss-future-ev-charging-with-musk-twitter-2023-06-08/
👉👉👉👉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:59 </td>
   <td style="text-align:left;"> $TSLA bears will loose so much money today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:56 </td>
   <td style="text-align:left;"> $TSLA Almost reminds me of the old days. Just need like a $40 run.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:49 </td>
   <td style="text-align:left;"> $TSLA $250 call 👌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:48 </td>
   <td style="text-align:left;"> $TSLA aint going down 
big money very short, and now need to cover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:46 </td>
   <td style="text-align:left;"> $TSLA  Does Chrysler have an option ……no they don’t  
 
better ask Elon nicely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:46 </td>
   <td style="text-align:left;"> $TSLA 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:41 </td>
   <td style="text-align:left;"> $TSLA watch the flags starting..no profit taking till close..Mostly rolling options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:38 </td>
   <td style="text-align:left;"> $TSLA BTFD .. huge bear squeeze coming this afternoon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:28 </td>
   <td style="text-align:left;"> $TSLA  $xela leader in BPA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:24 </td>
   <td style="text-align:left;"> $SPY Will it fade here? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:22 </td>
   <td style="text-align:left;"> $TSLA Wow Tesla is doing so well! Been green for awhile. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:17 </td>
   <td style="text-align:left;"> $TSLA Epic bear trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:16 </td>
   <td style="text-align:left;"> $TSLA feeling like a cult again!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:15 </td>
   <td style="text-align:left;"> $TSLA 250 imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:15 </td>
   <td style="text-align:left;"> $TSLA big ass red canlde lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:12 </td>
   <td style="text-align:left;"> $TSLA PUTS at the top, FLUUUUUSH baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:06 </td>
   <td style="text-align:left;"> $TSLA Today&amp;#39;s Max Pain @ 222.5. Bulls need 251.5 Breakout. Bears need 246 Breakdown. $SPY $QQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:02 </td>
   <td style="text-align:left;"> $TSLA CJET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:39:01 </td>
   <td style="text-align:left;"> $TSLA I think we break into the $260’s today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:38:56 </td>
   <td style="text-align:left;"> $TSLA Covered partial from premarket...$250.16 - $245.32...Gapped to 86 daily RSI as anticipated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:38:53 </td>
   <td style="text-align:left;"> $TSLA y’all got suckered in by those who were going to sell their calls at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:38:51 </td>
   <td style="text-align:left;"> $TSLA so overbought this could really plunge on a sell off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:38:45 </td>
   <td style="text-align:left;"> $TSLA bought some puts for the dump. thanks pumpers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:38:44 </td>
   <td style="text-align:left;"> $tsla sub 242.70s and becomes a resistance, go deep on swing puts for an entire $50 pullback </td>
  </tr>
</tbody>
</table></div>

---
